#### Test 87137063ea72b13_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
,09-28 13:13:10.887   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 13:13:10.888   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-28 13:13:11.407  5636  5636 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-28 13:13:11.413  5636  5636 D AndroidRuntime: CheckJNI is OFF
09-28 13:13:11.446  5636  5636 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-28 13:13:11.483  5636  5636 I Radio-JNI: register_android_hardware_Radio DONE
09-28 13:13:11.501  5636  5636 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-28 13:13:11.505   929  3768 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-28 13:13:11.547   929  3768 I ActivityManager: Start proc 5645:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-28 13:13:11.552  5636  5636 D AndroidRuntime: Shutting down VM
,09-28 13:13:11.888   929  3831 I WindowManager: Screenshot max retries 4 of Token{e3d40dc ActivityRecord{c28314f u0 com.test.thalitest/.MainActivity t2}} appWin=Window{372fb47 u0 Starting com.test.thalitest} drawState=2
,09-28 13:13:11.955  5645  5645 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-28 13:13:11.988  5645  5645 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-28 13:13:12.011  5645  5645 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 537-556)
,09-28 13:13:12.011  5645  5645 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-28 13:13:12.031  5645  5645 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {34a37f5}
,09-28 13:13:12.031  5645  5645 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-28 13:13:12.032  5645  5645 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-28 13:13:12.037  5645  5645 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-28 13:13:12.039  5645  5645 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-28 13:13:12.073  5645  5645 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-28 13:13:12.088  5645  5645 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-28 13:13:12.089  5645  5645 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-28 13:13:12.089  5645  5645 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-28 13:13:12.089  5645  5645 I Adreno  : Build Date                       : 12/06/15
09-28 13:13:12.089  5645  5645 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-28 13:13:12.089  5645  5645 I Adreno  : Local Branch                     : mybranch17112971
09-28 13:13:12.089  5645  5645 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-28 13:13:12.089  5645  5645 I Adreno  : Remote Branch                    : NONE
09-28 13:13:12.089  5645  5645 I Adreno  : Reconstruct Branch               : NOTHING
,09-28 13:13:12.142   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@904146a:true
,09-28 13:13:12.175   743   743 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[23355]" dev="sockfs" ino=23355 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 13:13:12.175   743   743 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[23355]" dev="sockfs" ino=23355 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 13:13:12.189  5645  5645 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-28 13:13:12.199  5645  5645 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-28 13:13:12.222   743   743 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33241]" dev="sockfs" ino=33241 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 13:13:12.222   743   743 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33241]" dev="sockfs" ino=33241 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-28 13:13:12.225  5645  5683 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-28 13:13:12.225  3878  3878 W Binder_D: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[23366]" dev="sockfs" ino=23366 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 13:13:12.225  3878  3878 W Binder_D: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[23366]" dev="sockfs" ino=23366 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 13:13:12.233  5645  5670 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-28 13:13:12.258  5645  5683 I OpenGLRenderer: Initialized EGL, version 1.4
,09-28 13:13:12.338   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +444ms (total +818ms)
,09-28 13:13:12.363  5645  5645 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5645
,09-28 13:13:12.458  5645  5645 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-28 13:13:12.512   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 13:13:12.651  5645  5686 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -586675920
,09-28 13:13:12.655  5645  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-28 13:13:12.655  5645  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-28 13:13:12.655  5645  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-28 13:13:12.655  5645  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-28 13:13:12.655  5645  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-28 13:13:12.656  5645  5686 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cb23ea2 added. We now have 1 listener(s)
,09-28 13:13:12.660  5645  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-28 13:13:12.661  5645  5686 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 13:13:12.661  5645  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 13:13:12.661  5645  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-28 13:13:12.664  5645  5686 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c236869 added. We now have 1 listener(s)
09-28 13:13:12.664  5645  5686 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:13:12.670   929  2977 D WifiService: New client listening to asynchronous messages
,09-28 13:13:12.672  5645  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 13:13:12.672  5645  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-28 13:13:12.672  5645  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-28 13:13:12.672  5645  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-28 13:13:12.672  5645  5686 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-28 13:13:12.674  5645  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:13:12.674  5645  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-28 13:13:12.679  5645  5686 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:12.679  5645  5686 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:12.679  5645  5686 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-28 13:13:12.679  5645  5686 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 13:13:12.680  5645  5686 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-28 13:13:12.685  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:12.691  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:12.714  5645  5645 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-28 13:13:13.698  5645  5645 I Choreographer: Skipped 56 frames!  The application may be doing too much work on its main thread.
,09-28 13:13:13.991  5645  5654 I art     : Background sticky concurrent mark sweep GC freed 76903(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.164ms total 190.522ms
,09-28 13:13:14.157  5645  5692 W jxcore-log: Initializing JXcore engine
,09-28 13:13:14.157  5645  5692 W jxcore-log: JXcore engine is ready
,09-28 13:13:14.198  5692  5692 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12328 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-28 13:13:14.198  5692  5692 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[10977]" dev="sockfs" ino=10977 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-28 13:13:14.198  5692  5692 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-28 13:13:14.198  5692  5692 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32351]" dev="sockfs" ino=32351 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-28 13:13:14.212  5645  5692 W jxcore-log: Starting JXcore engine
,09-28 13:13:14.265  5645  5692 W jxcore-log: Platform android
09-28 13:13:14.265  5645  5692 W jxcore-log: 
,09-28 13:13:14.265  5645  5692 W jxcore-log: Process ARCH arm
09-28 13:13:14.265  5645  5692 W jxcore-log: 
,09-28 13:13:14.360  5645  5692 I jxcore-log: JXcore Cordova bridge is ready!
09-28 13:13:14.360  5645  5692 I jxcore-log: 
,09-28 13:13:14.360  5645  5692 W jxcore-log: JXcore engine is started
,09-28 13:13:14.370  5645  5686 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-28 13:13:14.376  5645  5645 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-28 13:13:20.889   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:21.890   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:22.892   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:23.893   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:24.080  5645  5692 I jxcore-log: 2016-09-28 17:13:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 13:13:24.080  5645  5692 I jxcore-log: 
,09-28 13:13:24.082  5645  5692 I jxcore-log: 2016-09-28 17:13:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 13:13:24.082  5645  5692 I jxcore-log: 
,09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:24.085  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:13:24.087  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:13:24.089  5645  5692 I jxcore-log: 2016-09-28 17:13:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 13:13:24.089  5645  5692 I jxcore-log: 
,09-28 13:13:24.090  5645  5692 I jxcore-log: 2016-09-28 17:13:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 13:13:24.090  5645  5692 I jxcore-log: 
,09-28 13:13:24.337  5645  5692 I jxcore-log: 2016-09-28 17:13:24 - DEBUG UnitTest_app: 'Running unit tests'
09-28 13:13:24.337  5645  5692 I jxcore-log: 
,09-28 13:13:24.337  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:13:24.337  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4142ad added. We now have 2 listener(s)
09-28 13:13:24.338  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 13:13:24.338  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:13:24.338  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:13:24.339  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:13:24.339  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee849e2 added. We now have 2 listener(s)
09-28 13:13:24.339  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:13:24.339  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:13:24.341  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:24.344  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:13:24.349  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:24.350  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:13:24.351  5645  5692 D executeNativeTests: Running unit tests
,09-28 13:13:24.356  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:24.362  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:24.391  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 13:13:24.391  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 added. We now have 3 listener(s)
09-28 13:13:24.392  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:13:24.392  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:13:24.392  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:13:24.392  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:13:24.392  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 added. We now have 3 listener(s)
09-28 13:13:24.392  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:13:24.392  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:13:24.394  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:24.396  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:24.397  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:24.397  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:13:24.398  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 13:13:24.398  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 13:13:24.398  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 13:13:24.398  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 13:13:24.399  5645  5692 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-28 13:13:24.399  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 13:13:24.399  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 13:13:24.399  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 13:13:24.399  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 13:13:24.399  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 13:13:24.400  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:24.400  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:24.400  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:24.401  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:24.401  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:24.401  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:13:24.401  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:24.401  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:13:24.401  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject,.p2p.btconnectorlib.ConnectionManager@4a2d60 removed from the list
09-28 13:13:24.401  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:24.401  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 removed from the list
09-28 13:13:24.402  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:24.406  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:24.408  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:24.408  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:24.408  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:24.408  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:24.409  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:24.409  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:24.409  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:24.409  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:24.410  5645  5692 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-28 13:13:24.410  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:24.410  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:24.410  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:24.410  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:24.410  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:24.410  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:24.410  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:24.410  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:24.410  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:24.410  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:24.410  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:24.410  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:24.410  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:24.410  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:24.410  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:13:24.411  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:24.411  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:24.411  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:24.411  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:24.413  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 13:13:24.413  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 13:13:24.413  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 13:13:24.413  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 13:13:24.413  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-28 13:13:24.413  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 13:13:24.413  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 13:13:24.414  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 13:13:24.414  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:24.414  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 13:13:24.414  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:24.414  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:24.414  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:24.414  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:24.414  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 13:13:24.415  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:24.415  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:24.415  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:24.415  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:24.415  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:24.415  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:24.415  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:24.415  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:24.415  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 13:13:24.415  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:24.415  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:24.415  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:24.416  5645  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 13:13:24.417  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:24.419  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:24.420  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:24.420  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:13:24.420  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:13:24.420  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 13:13:24.420  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-28 13:13:24.420  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 13:13:24.420  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 13:13:24.422  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:24.423  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:24.424  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 13:13:24.424  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 13:13:24.426  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 13:13:24.427  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 13:13:24.427  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 13:13:24.429  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-28 13:13:24.430  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-28 13:13:24.430  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 13:13:24.430  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 13:13:24.430  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 13:13:24.430  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 13:13:24.430  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 13:13:24.430  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:13:24.433  4601  4619 D BtGatt.GattService: registerClient() - UUID=15a70dd9-abf5-441d-9ecb-28b0fcf8490e
,09-28 13:13:24.433  4601  4672 D BtGatt.GattService: onClientRegistered() - UUID=15a70dd9-abf5-441d-9ecb-28b0fcf8490e, clientIf=5
,09-28 13:13:24.434  5645  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 13:13:24.437  4601  4841 D BtGatt.GattService: start scan with filters
,09-28 13:13:24.443  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 13:13:24.443  4601  4677 D BtGatt.ScanManager: handling starting scan
09-28 13:13:24.443  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 13:13:24.443  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:13:24.443  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 13:13:24.443  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 13:13:24.443  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 13:13:24.443  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 13:13:24.444  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:13:24.445  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-28 13:13:24.445  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 13:13:24.445  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 13:13:24.445  4601  4677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:13:24.446  5645  5692 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 13:13:24.453  4601  4672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 13:13:24.453  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:24.454  4601  4677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 13:13:24.461  4601  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 13:13:24.461  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:24.461  4601  4677 D BtGatt.ScanManager: Starting BLE batch scan
,09-28 13:13:24.461  4601  4677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 13:13:24.474  4601  4672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 13:13:24.474  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:24.480  4601  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 13:13:24.481  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:24.895   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:24.947  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 13:13:24.948  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:13:24.948  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 13:13:25.896   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 13:13:26.199   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 13:13:26.206   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-28 13:13:29.231   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 13:13:29.236   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-28 13:13:29.451  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 13:13:29.451  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:29.451  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 13:13:29.451  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:29.451  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-28 13:13:29.451  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:29.451  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 13:13:29.451  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 13:13:29.452  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 13:13:29.452  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 13:13:29.452  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 13:13:29.453  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 13:13:29.454  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:13:29.454  4601  4622 D BtGatt.GattService: stopScan() - queue size =1
09-28 13:13:29.455  4601  4842 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 13:13:29.456  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 13:13:29.456  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-28 13:13:29.456  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 13:13:29.456  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:13:29.456  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,09-28 13:13:29.456  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 13:13:29.456  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 13:13:29.457  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 13:13:29.458  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:13:29.458  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 13:13:29.458  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 13:13:29.459  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 13:13:29.459  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 13:13:29.460  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 13:13:29.461  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:29.461  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:29.461  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:13:29.461  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:13:29.461  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:29.462  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:29.462  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:29.462  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:13:29.462  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:29.462  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:29.462  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:13:29.462  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:29.467  4601  4601 D BtGatt.ScanManager: awakened up at time 238012
,09-28 13:13:29.472  4601  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 13:13:29.472  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:29.473  4601  4677 D BtGatt.ScanManager: stopping BLe Batch
,09-28 13:13:29.484  4601  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 13:13:29.485  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:29.485  4601  4677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 13:13:29.516  4601  4672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 13:13:29.516  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:29.516  4601  4672 D BtGatt.GattService: current time is 238062182040
09-28 13:13:29.517  4601  4672 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -76, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -75, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -77, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -70, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -73, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 13:13:29.520  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-28 13:13:29.522  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 13:13:29.523  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-28 13:13:29.523  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 13:13:29.523  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 13:13:29.524  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 13:13:29.963  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 13:13:30.897   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:31.898   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:32.900   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:33.902   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:34.464  5645  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 13:13:34.469  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:34.480  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:13:34.485  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:13:34.485  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:13:34.485  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:13:34.486  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-28 13:13:34.486  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 13:13:34.486  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 13:13:34.486  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 13:13:34.492  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:34.495  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 13:13:34.495  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 13:13:34.500  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:34.504  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 13:13:34.505  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 13:13:34.505  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 13:13:34.511  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 13:13:34.512  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 13:13:34.512  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 13:13:34.512  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 13:13:34.512  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 13:13:34.513  5645  5692 D BluetoothAdapter: STATE_ON
,09-28 13:13:34.517  4601  4622 D BtGatt.GattService: registerClient() - UUID=3323b6b4-5641-4de5-970e-f297b8b8c9f8
09-28 13:13:34.517  4601  4672 D BtGatt.GattService: onClientRegistered() - UUID=3323b6b4-5641-4de5-970e-f297b8b8c9f8, clientIf=5
09-28 13:13:34.518  5645  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 13:13:34.518  4601  4822 D BtGatt.GattService: start scan with filters
,09-28 13:13:34.523  4601  4677 D BtGatt.ScanManager: handling starting scan
09-28 13:13:34.524  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 13:13:34.524  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 13:13:34.524  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:13:34.524  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 13:13:34.524  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 13:13:34.524  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 13:13:34.524  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 13:13:34.530  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:13:34.530  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 13:13:34.530  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:13:34.533  4601  4672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 13:13:34.533  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.534  4601  4677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 13:13:34.534  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 13:13:34.540  5645  5692 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 13:13:34.542  4601  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 13:13:34.542  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.543  4601  4677 D BtGatt.ScanManager: Starting BLE batch scan
09-28 13:13:34.543  4601  4677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 13:13:34.544  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 13:13:34.544  5645  5692 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 13:13:34.545  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:34.545  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 13:13:34.545  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:34.545  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 13:13:34.545  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:34.545  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 13:13:34.545  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 13:13:34.545  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 13:13:34.545  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 13:13:34.546  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 13:13:34.546  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 13:13:34.546  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:13:34.547  4601  4841 D BtGatt.GattService: stopScan() - queue size =1
09-28 13:13:34.548  4601  4822 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 13:13:34.549  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 13:13:34.549  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 13:13:34.549  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 13:13:34.549  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:13:34.549  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 13:13:34.550  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 13:13:34.550  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 13:13:34.550  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 13:13:34.551  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:13:34.551  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 13:13:34.551  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 13:13:34.551  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 13:13:34.551  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 13:13:34.552  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:13:34.554  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:34.554  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:34.554  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 13:13:34.554  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:13:34.554  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:34.554  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:13:34.554  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:34.554  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:13:34.554  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:34.554  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:34.554  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:34.554  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:34.555  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:34.556  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:13:34.557  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:34.558  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:34.558  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:34.558  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:34.558  4601  4672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 13:13:34.558  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.559  5645  5692 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 13:13:34.561  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:13:34.566  4601  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 13:13:34.566  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:34.566  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:13:34.569  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:34.569  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:13:34.569  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:13:34.569  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 13:13:34.569  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 13:13:34.569  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 13:13:34.569  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 13:13:34.573  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:34.576  4601  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 13:13:34.576  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.576  4601  4677 D BtGatt.ScanManager: stopping BLe Batch
09-28 13:13:34.576  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:34.577  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 13:13:34.577  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 13:13:34.583  4601  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 13:13:34.583  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.583  4601  4677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 13:13:34.584  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 13:13:34.584  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 13:13:34.584  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 13:13:34.589  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 13:13:34.589  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 13:13:34.589  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-28 13:13:34.589  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 13:13:34.589  4601  4672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 13:13:34.589  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 13:13:34.589  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.590  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:13:34.592  4601  4822 D BtGatt.GattService: registerClient() - UUID=8468e0a3-b561-444b-8899-cec772a853b8
09-28 13:13:34.592  4601  4672 D BtGatt.GattService: onClientRegistered() - UUID=8468e0a3-b561-444b-8899-cec772a853b8, clientIf=5
09-28 13:13:34.592  5645  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 13:13:34.593  4601  4842 D BtGatt.GattService: start scan with filters
,09-28 13:13:34.595  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 13:13:34.595  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 13:13:34.595  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:13:34.595  4601  4677 D BtGatt.ScanManager: handling starting scan
09-28 13:13:34.595  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 13:13:34.595  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 13:13:34.595  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 13:13:34.595  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 13:13:34.597  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 13:13:34.598  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 13:13:34.598  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 13:13:34.599  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 13:13:34.601  5645  5692 I io.jxcore.node.ConnectionHelper: start: OK
09-28 13:13:34.601  4601  4672 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 13:13:34.601  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.601  4601  4677 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 13:13:34.607  4601  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-28 13:13:34.607  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:34.607  4601  4677 D BtGatt.ScanManager: Starting BLE batch scan
09-28 13:13:34.607  4601  4677 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 13:13:34.617  4601  4672 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 13:13:34.617  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:34.622  4601  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 13:13:34.622  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:34.904   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:35.099  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 13:13:35.099  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:13:35.100  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 13:13:35.292   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 13:13:35.302   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-28 13:13:35.905   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 13:13:38.313   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 13:13:38.320   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-28 13:13:39.602  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 13:13:39.602  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:39.602  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 13:13:39.602  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:39.602  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-28 13:13:39.603  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:39.603  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 13:13:39.603  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 13:13:39.603  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-28 13:13:39.603  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 13:13:39.603  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 13:13:39.604  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 13:13:39.605  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:13:39.607  4601  4622 D BtGatt.GattService: stopScan() - queue size =1
09-28 13:13:39.609  4601  4822 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 13:13:39.609  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-28 13:13:39.610  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-28 13:13:39.610  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 13:13:39.610  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:13:39.610  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 13:13:39.610  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 13:13:39.610  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 13:13:39.610  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 13:13:39.613  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:13:39.613  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 13:13:39.613  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 13:13:39.613  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 13:13:39.613  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 13:13:39.616  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:13:39.617  4601  4601 D BtGatt.ScanManager: awakened up at time 248162
09-28 13:13:39.621  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:13:39.621  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:13:39.621  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 13:13:39.624  4601  4672 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 13:13:39.624  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:39.624  4601  4677 D BtGatt.ScanManager: stopping BLe Batch
,09-28 13:13:39.632  4601  4672 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 13:13:39.632  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:13:39.632  4601  4677 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 13:13:39.650  4601  4672 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-28 13:13:39.650  4601  4672 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:13:39.650  4601  4672 D BtGatt.GattService: current time is 248196019298
,09-28 13:13:39.651  4601  4672 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -77, 100, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -76, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -70, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -77, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-28 13:13:39.651  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 13:13:39.651  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 13:13:39.651  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 13:13:39.652  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 13:13:39.652  4601  4672 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-28 13:13:40.122  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 13:13:40.123  5645  5645 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 13:13:40.123  5645  5645 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 13:13:41.345   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 13:13:44.377   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 13:13:44.622  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.622  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.622  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 13:13:44.622  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.623  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.623  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:13:44.623  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.623  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
,09-28 13:13:44.623  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.623  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.624  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.624  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.625  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:44.625  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.629  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 13:13:44.629  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 13:13:44.630  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.630  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:44.634  5645  5692 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-28 13:13:44.636  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.636  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 13:13:44.636  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.637  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.637  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.637  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.638  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 13:13:44.638  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.638  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.638  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.638  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.638  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.639  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.639  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.639  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:13:44.643  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 13:13:44.643  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:44.643  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.643  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:44.645  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-28 13:13:44.645  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.645  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.646  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.646  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.646  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.646  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.646  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.646  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
,09-28 13:13:44.646  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.646  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.646  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.646  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.646  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.646  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:44.647  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:13:44.648  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.648  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:44.648  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.649  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:44.650  5645  5692 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-28 13:13:44.650  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.650  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.650  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.650  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.650  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.650  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.650  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.650  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
,09-28 13:13:44.650  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.650  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.651  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.651  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.651  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.651  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.651  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.653  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.653  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 13:13:44.653  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.653  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:44.654  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-28 13:13:44.655  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 13:13:44.655  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.655  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.655  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.655  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.655  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.655  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.655  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.655  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:44.655  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.655  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.655  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.655  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.656  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.656  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.657  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.657  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 13:13:44.657  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.657  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.658  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 13:13:44.659  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 13:13:44.659  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 13:13:44.659  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 13:13:44.659  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 13:13:44.659  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 13:13:44.659  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-28 13:13:44.659  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 13:13:44.659  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 13:13:44.659  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.659  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.659  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.659  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.660  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.660  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.660  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.660  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.660  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.660  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.660  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 13:13:44.660  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.660  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.660  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.660  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.662  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.662  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:44.662  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.662  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.663  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-28 13:13:44.663  5645  5692 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 13:13:44.663  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 13:13:44.667  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 13:13:44.668  5645  5692 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-28 13:13:44.668  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 13:13:44.668  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 13:13:44.668  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 13:13:44.669  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 13:13:44.670  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 13:13:44.671  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 13:13:44.671  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-28 13:13:44.671  5645  5692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 13:13:44.671  5645  5692 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-28 13:13:44.671  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 13:13:44.671  5645  5692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 13:13:44.671  5645  5692 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-28 13:13:44.672  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 13:13:44.672  5645  5692 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 13:13:44.672  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-28 13:13:44.675  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-28 13:13:44.676  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-28 13:13:44.677  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-28 13:13:44.677  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-28 13:13:44.677  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-28 13:13:44.677  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-28 13:13:44.678  5645  5692 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 13:13:44.678  5645  5692 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-28 13:13:44.678  5645  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
09-28 13:13:44.678  5645  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-28 13:13:44.679  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.679  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.679  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.679  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.679  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.679  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.679  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.680  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-28 13:13:44.680  5645  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-28 13:13:44.680  5645  5693 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-28 13:13:44.680  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.680  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.680  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.681  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.681  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.681  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.681  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.681  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.681  5645  5694 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-28 13:13:44.683  5645  5693 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-28 13:13:44.683  5645  5693 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 13:13:44.682  4619  4619 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32411]" dev="sockfs" ino=32411 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 13:13:44.682  4619  4619 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32411]" dev="sockfs" ino=32411 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 13:13:44.685  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.685  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:44.685  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.685  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.686  5645  5692 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-28 13:13:44.687  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.687  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.687  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.687  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.687  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.687  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.687  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.687  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.687  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.687  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.687  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.687  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.687  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.688  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.688  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.691  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.691  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:44.691  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.691  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.692  5645  5692 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-28 13:13:44.692  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.692  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.692  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.692  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.692  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.692  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.692  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.692  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.692  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.693  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.693  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.693  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.693  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.693  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.693  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.695  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.695  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:44.695  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.695  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.696  5645  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-28 13:13:44.696  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-28 13:13:44.696  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 13:13:44.696  5645  5692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-28 13:13:44.696  5645  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 13:13:44.696  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-28 13:13:44.696  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 13:13:44.697  5645  5692 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-28 13:13:44.697  5645  5692 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 13:13:44.697  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 13:13:44.697  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 13:13:44.697  5645  5692 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-28 13:13:44.697  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:44.697  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:44.697  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:44.697  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.697  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.697  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.697  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.697  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.698  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.698  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.698  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.698  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.698  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.698  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.698  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.699  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:44.699  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:44.699  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.699  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.700  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:44.700  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.700  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:44.700  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:44.700  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:44.700  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:44.701  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:44.701  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:44.701  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:44.701  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:13:45.906   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:46.907   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:47.908   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:48.909   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:49.701  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:49.702  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.702  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 13:13:49.702  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.702  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.702  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 13:13:49.703  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:49.703  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:49.703  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 13:13:49.703  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:49.703  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:49.704  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.704  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.704  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:49.704  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:49.704  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:49.704  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.705  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 13:13:49.705  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.705  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.705  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.705  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.709  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:49.709  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:49.709  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:49.709  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.714  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 13:13:49.715  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 13:13:49.717  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-28 13:13:49.719  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-28 13:13:49.720  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-28 13:13:49.720  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-28 13:13:49.720  5645  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
09-28 13:13:49.721  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 13:13:49.721  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 13:13:49.721  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-28 13:13:49.722  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:49.722  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 13:13:49.722  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 13:13:49.722  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-28 13:13:49.722  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.722  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-28 13:13:49.722  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 13:13:49.723  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:49.723  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:49.723  5645  5645 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 13:13:49.723  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 13:13:49.723  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 13:13:49.723  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 13:13:49.723  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.723  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.724  5645  5695 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 13:13:49.725  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:13:49.725  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.726  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:13:49.726  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:13:49.726  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:49.726  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 13:13:49.726  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 13:13:49.726  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:49.726  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:49.726  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:49.726  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.726  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-28 13:13:49.726  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:49.726  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:49.722  4822  4822 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30202]" dev="sockfs" ino=30202 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 13:13:49.722  4822  4822 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30202]" dev="sockfs" ino=30202 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 13:13:49.726  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.727  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:49.727  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.727  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.727  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:49.727  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.728  5645  5695 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 13:13:49.728  5645  5695 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 13:13:49.729  5645  5695 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 13:13:49.729  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:49.729  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:49.729  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:49.729  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.729  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 13:13:49.730  5645  5645 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:49.731  5645  5692 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-28 13:13:49.732  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 13:13:49.732  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 13:13:49.732  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 13:13:49.732  5645  5692 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 13:13:49.732  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 13:13:49.732  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:49.732  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:49.732  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:49.732  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.733  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.733  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:49.733  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:49.734  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:49.734  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.734  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:49.734  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.734  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:13:49.735  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.735  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.739  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:49.739  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:49.739  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:49.739  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:49.744  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 13:13:49.745  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:49.745  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:49.745  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:49.745  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.745  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.745  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:49.745  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:49.745  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:49.745  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:49.745  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:49.745  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.745  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.745  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.745  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.747  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:49.747  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:49.747  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:49.747  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:49.748  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:13:49.748  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:13:49.748  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:13:49.748  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:13:49.748  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.748  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.748  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:13:49.748  5645  5692 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a2d60 not in the list
09-28 13:13:49.748  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:49.748  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
09-28 13:13:49.748  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:13:49.748  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.748  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.748  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:13:49.748  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:49.749  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:13:49.750  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:13:49.750  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:49.750  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a8c219 not in the list
,09-28 13:13:49.751  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-28 13:13:49.751  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 13:13:49.751  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-28 13:13:49.751  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-28 13:13:49.751  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-28 13:13:49.751  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-28 13:13:49.753  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-28 13:13:49.753  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-28 13:13:49.754  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-28 13:13:49.754  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,09-28 13:13:49.755  5645  5692 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-28 13:13:49.755  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 13:13:49.755  5645  5692 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-28 13:13:49.755  5645  5692 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-28 13:13:49.756  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-28 13:13:49.756  5645  5692 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-28 13:13:49.756  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-28 13:13:49.756  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-28 13:13:49.756  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-28 13:13:49.756  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-28 13:13:49.757  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:13:49.757  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b69b553 added. We now have 3 listener(s)
09-28 13:13:49.757  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:13:49.759  5645  5692 D BluetoothAdapter: enable(): BT is already enabled..!
09-28 13:13:49.759   929  3878 D WifiService: setWifiEnabled: true pid=5645, uid=10077
09-28 13:13:49.759   929  3878 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 13:13:49.811  4601  4817 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-28 13:13:49.812  4601  4820 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-28 13:13:49.812  5645  5693 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
09-28 13:13:49.812  5645  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-28 13:13:49.812  5645  5693 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,09-28 13:13:49.910   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:13:50.227  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 13:13:50.911   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 13:13:52.516   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 13:13:54.765  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:13:54.765  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@273ae90 added. We now have 4 listener(s)
,09-28 13:13:54.765  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:13:54.779  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:13:54.779  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@273ae90 removed from the list
09-28 13:13:54.779  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 13:13:54.780  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:54.780  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:54.782  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 13:13:54.782  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd16389 added. We now have 4 listener(s)
09-28 13:13:54.782  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:13:54.785  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:13:54.786  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd16389 removed from the list
,09-28 13:13:54.786  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 13:13:54.786  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:13:54.786  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:13:54.789  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:13:54.789  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3714f8e added. We now have 4 listener(s)
09-28 13:13:54.789  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:13:54.794   929  3564 D WifiService: setWifiEnabled: false pid=5645, uid=10077
09-28 13:13:54.794   929  3564 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 13:13:54.800   929  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 13:13:54.801   929  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-28 13:13:54.801   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 13:13:54.801   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 13:13:54.805  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:13:54.809  4601  4668 D BluetoothAdapterState: Current state: ON, message: 23
09-28 13:13:54.809  4601  4668 D BluetoothAdapterProperties: Setting state to 13
09-28 13:13:54.809  4601  4668 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-28 13:13:54.811  4601  4668 D BluetoothAdapterProperties: onBluetoothDisable()
09-28 13:13:54.814  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:54.815  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:54.815  4601  4668 I BluetoothAdapterState: Entering PendingCommandState
,09-28 13:13:54.818  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:13:54.818  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:54.819  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 13:13:54.819  4601  4672 D BluetoothAdapterProperties: Scan Mode:20
09-28 13:13:54.820  4601  4668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-28 13:13:54.821   507   923 D CommandListener: Clearing all IP addresses on wlan0
09-28 13:13:54.822   929  5395 D DhcpClient: Clearing IP address
09-28 13:13:54.824  4601  4601 D HeadsetService: Received stop request...Stopping profile...
09-28 13:13:54.826  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:54.832  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:54.834   507   923 D CommandListener: Setting iface cfg
,09-28 13:13:54.835  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:54.835  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:54.836  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.836  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:54.839  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:54.839  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:54.840  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.840  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:13:54.844  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:54.844  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:54.845  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.846  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:13:54.847   929   942 I ActivityManager: Start proc 5699:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-28 13:13:54.849   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 13:13:54.849   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-28 13:13:54.850  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:13:54.850  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:54.851   929  5396 D DhcpClient: Receive thread stopped
,09-28 13:13:54.854  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.854  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:13:54.856   929   929 D RttService: SCAN_AVAILABLE : 1
,09-28 13:13:54.856   533   533 E Parcel  : Reading a NULL string not supported here.
,09-28 13:13:54.856   929  3085 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 13:13:54.856  4601  4601 D BluetoothMapService: onReceive
09-28 13:13:54.856  4601  4601 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 13:13:54.856  4601  4601 D BluetoothMapService: STATE_TURNING_OFF
09-28 13:13:54.857  3789  4011 D BluetoothHeadset: Proxy object disconnected
09-28 13:13:54.857  3144  3955 D BluetoothHeadset: Proxy object disconnected
09-28 13:13:54.858  3144  3144 D HeadsetProfile: Bluetooth service disconnected
09-28 13:13:54.858   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 13:13:54.858   929   929 D BluetoothHeadset: Proxy object disconnected
,09-28 13:13:54.858   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 13:13:54.858  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.858  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:54.858  4601  4601 D A2dpService: Received stop request...Stopping profile...
,09-28 13:13:54.859  4601  4825 D A2dpStateMachine: Exit Disconnected: -1
09-28 13:13:54.859  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.859  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 13:13:54.859  3570  5451 V NativeCrypto: Read error: ssl=0x7fa9963200: I/O error during system call, Connection timed out
09-28 13:13:54.861   929   929 D BluetoothA2dp: Proxy object disconnected
,09-28 13:13:54.861  3144  3144 D BluetoothA2dp: Proxy object disconnected
09-28 13:13:54.862  3570  5451 V NativeCrypto: SSL shutdown failed: ssl=0x7fa9963200: I/O error during system call, Broken pipe
09-28 13:13:54.862  4601  4601 D HidService: Received stop request...Stopping profile...
09-28 13:13:54.863  4601  4601 D HidService: Stopping Bluetooth HidService
09-28 13:13:54.863   929  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-28 13:13:54.864  3144  3144 D BluetoothInputDevice: Proxy object disconnected
09-28 13:13:54.864  3144  3144 D HidProfile: Bluetooth service disconnected
,09-28 13:13:54.864  4601  4601 V BluetoothAdapterState: isTurningOff()=true
09-28 13:13:54.865  4601  4601 V BluetoothAdapterState: isTurningOn()=false
09-28 13:13:54.865  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:54.865  4601  4601 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:13:54.866  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.866  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:13:54.866  4601  4601 D HealthService: Received stop request...Stopping profile...
09-28 13:13:54.866  3742  3903 W QCNEJ   : |CORE| network lost: 100
09-28 13:13:54.869  3742  3903 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-28 13:13:54.871   929  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-28 13:13:54.875  4601  4601 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 13:13:54.875  4601  4601 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-28 13:13:54.876  4601  4672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 13:13:54.876  4601  4601 D PanService: Received stop request...Stopping profile...
09-28 13:13:54.876  4601  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:13:54.876  4601  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:13:54.876  4601  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:13:54.876  4601  4672 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 13:13:54.877  4601  4601 D BluetoothMapService: MAP Service closeService in
09-28 13:13:54.877  4601  4601 D BluetoothMapMasInstance0: MAP Service shutdown
,09-28 13:13:54.877  4601  4601 D ObexServerSockets0: shutdown(block = true)
09-28 13:13:54.877  4601  4601 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 13:13:54.877  4601  4843 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-28 13:13:54.877  4601  4601 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 13:13:54.877  4601  4820 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 13:13:54.877  4601  4844 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 13:13:54.878  4601  4601 I BtOppRfcommListener: stopping Accept Thread
09-28 13:13:54.878  4601  5336 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-28 13:13:54.878  4601  5336 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-28 13:13:54.879  4601  4601 D BluetoothMapService: Received stop request...Stopping profile...
09-28 13:13:54.880  4601  4601 D BluetoothMapService: stop()
09-28 13:13:54.880  4601  4601 D BluetoothMapAppObserver: deinitObservers()
09-28 13:13:54.880  4601  4601 D BluetoothMapAppObserver: removeReceiver()
09-28 13:13:54.883   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 13:13:54.885  4601  4601 V BluetoothAdapterState: isTurningOff()=true
09-28 13:13:54.885  4601  4601 V BluetoothAdapterState: isTurningOn()=false
09-28 13:13:54.885  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:54.885  4601  4601 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:13:54.886  4601  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:13:54.886  4601  4601 V BluetoothAdapterState: isTurningOff()=true
09-28 13:13:54.886  4601  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 13:13:54.886  4601  4601 V BluetoothAdapterState: isTurningOn()=false
09-28 13:13:54.886  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:54.886  4601  4601 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:13:54.886  4601  4672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 13:13:54.886  4601  4817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 13:13:54.886  4601  4817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 13:13:54.886  4601  4817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 13:13:54.886  4601  4817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 13:13:54.886  4601  4601 D SapService: Received stop request...Stopping profile...
09-28 13:13:54.886  4601  4601 V SapService: stop()
,09-28 13:13:54.887   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 13:13:54.888  4601  4601 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 13:13:54.888  4601  4601 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 13:13:54.888  4601  4672 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 13:13:54.888  4601  4601 V BluetoothAdapterState: isTurningOff()=true
09-28 13:13:54.888  4601  4601 V BluetoothAdapterState: isTurningOn()=false
09-28 13:13:54.888  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:54.888  4601  4601 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:13:54.889  4601  4601 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 13:13:54.889  4601  4672 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 13:13:54.889  4601  4601 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 13:13:54.889  3144  3144 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 13:13:54.889  3144  3144 D PanProfile: Bluetooth service disconnected
09-28 13:13:54.889  3144  3144 D BluetoothMap: Proxy object disconnected
09-28 13:13:54.889  4601  4601 V BluetoothAdapterState: isTurningOff()=true
,09-28 13:13:54.889  3144  3144 D MapProfile: Bluetooth service disconnected
09-28 13:13:54.889  4601  4601 V BluetoothAdapterState: isTurningOn()=false
09-28 13:13:54.889  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:54.889  4601  4601 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:13:54.890  4601  4601 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 13:13:54.890  4601  4601 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-28 13:13:54.892  4601  4601 D BluetoothMapService: MAP Service closeService in
,09-28 13:13:54.892  4601  4601 V BluetoothAdapterState: isTurningOff()=true
09-28 13:13:54.892  4601  4601 V BluetoothAdapterState: isTurningOn()=false
,09-28 13:13:54.892  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:54.892  4601  4601 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:13:54.892  4601  4601 D BluetoothMapService: cleanup()
09-28 13:13:54.892  4601  4601 D BluetoothMapService: MAP Service closeService in
,09-28 13:13:54.892  4601  4601 V BluetoothAdapterState: isTurningOff()=true
09-28 13:13:54.892  4601  4601 V BluetoothAdapterState: isTurningOn()=false
09-28 13:13:54.892  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:54.893  4601  4601 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:13:54.893  4601  4668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 13:13:54.893  4601  4668 D BluetoothAdapterProperties: Setting state to 15
,09-28 13:13:54.893  4601  4668 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 13:13:54.893  4601  4668 I BluetoothAdapterState: Entering BleOnState
09-28 13:13:54.895   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:13:54.895  3144  3157 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 13:13:54.895   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 13:13:54.895   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 13:13:54.896  3144  3158 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 13:13:54.897  3144  3955 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 13:13:54.897  3789  3813 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:13:54.897  3144  3157 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:13:54.897   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:13:54.899  3144  3158 D BluetoothPan: onBluetoothStateChange on: false
09-28 13:13:54.900  3144  3955 D BluetoothMap: onBluetoothStateChange: up=false
09-28 13:13:54.900  4601  4668 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-28 13:13:54.900  4601  4668 D BluetoothAdapterProperties: Setting state to 16
09-28 13:13:54.900  4601  4668 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 13:13:54.901  4601  4668 D BluetoothAdapterProperties: onBleDisable
09-28 13:13:54.901  4601  4668 I BluetoothAdapterState: Entering PendingCommandState
09-28 13:13:54.901  4601  4669 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 13:13:54.902  4601  4817 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 13:13:54.902  4601  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:13:54.902  4601  4672 D BluetoothAdapterProperties: Scan Mode:20
09-28 13:13:54.904  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.904  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 13:13:54.908  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.908  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 13:13:54.911  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.911  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:13:54.912   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 13:13:54.913  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:54.913   507   923 D CommandListener: Clearing all IP addresses on wlan0
09-28 13:13:54.913   507   923 D TetherController: Setting IP forward enable = 0
,09-28 13:13:54.913   929  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-28 13:13:54.914   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 13:13:54.914  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:54.916  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:54.918   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 13:13:54.918  5699  5699 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-28 13:13:54.921   929  2976 D DhcpClient: doQuit
,09-28 13:13:54.922   929  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 13:13:54.922   929  5395 D DhcpClient: onQuitting
09-28 13:13:54.923  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:54.923  5306  5306 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@6c56431 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-28 13:13:54.924  3452  3452 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 13:13:54.924  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:54.927  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.927  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 13:13:54.929  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:13:54.929  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:13:54.933  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.934  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:13:54.935  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.935  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:13:54.937  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:13:54.937  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:13:54.939  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:13:54.939  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:13:54.941  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:54.941  3452  3452 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 13:13:54.942  4943  4943 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-28 13:13:54.946  3452  3452 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-28 13:13:54.947  5057  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 13:13:54.947  5057  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 13:13:54.947  5057  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 13:13:54.947  5057  5089 E SarControlService: no key has been found,reset the power
,09-28 13:13:54.947  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 13:13:54.947  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 13:13:54.947  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 13:13:54.948  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 13:13:54.948  5090  5090 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 13:13:54.949  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-28 13:13:54.949  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-28 13:13:54.949  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-28 13:13:54.951  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 13:13:54.952  5090  5090 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 13:13:54.953  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000ea03000000000000ffffffff]
09-28 13:13:54.953  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:13:54.953  5090  5104 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-28 13:13:54.954  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:13:54.954  5057  5067 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 13:13:54.957  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000eb03000000000000ffffffff]
09-28 13:13:54.957  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:13:54.957  5090  5104 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-28 13:13:54.958  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:13:54.958  5057  5068 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 13:13:54.967  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 13:13:54.970   507   923 E Netd    : netlink response contains error (No such file or directory)
,09-28 13:13:54.971   507   923 D TetherController: Setting IP forward enable = 0
,09-28 13:13:54.973   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@53d03d2:true
09-28 13:13:54.974  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 13:13:54.980  3452  3452 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 13:13:54.987   929  3871 I ActivityManager: Start proc 5730:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-28 13:13:54.988  3452  3452 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 13:13:55.004  5699  5699 D LocalBluetoothProfileManager: Adding local MAP profile
,09-28 13:13:55.008  5699  5699 D BluetoothMap: Create BluetoothMap proxy object
,09-28 13:13:55.022  5699  5699 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-28 13:13:55.029  5730  5730 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-28 13:13:55.035  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,09-28 13:13:55.043   929  3153 I ActivityManager: Killing 4983:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-28 13:13:55.093  5032  5032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 13:13:55.093   929  2976 D wifi    : In wifi stop Hal
09-28 13:13:55.093   929  2976 D wifi    : halHandle = 0x7f97e08b80, mVM = 0x7fb448d140, mCls = 0x100a06
09-28 13:13:55.093   929  3451 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 13:13:55.094   929  3451 D WifiHAL : Got a signal to exit!!!
,09-28 13:13:55.094   929  3451 I WifiHAL : Exit wifi_event_loop
09-28 13:13:55.094   929  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 13:13:55.094   929  2976 E WifiHAL : Event processing terminated
09-28 13:13:55.094   929  2976 D wifi    : In wifi cleaned up handler
,09-28 13:13:55.094   929  2976 I WifiHAL : Internal cleanup completed
09-28 13:13:55.095  4076  4223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 13:13:55.096  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:55.098  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:13:55.099  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:13:55.109  4601  4672 I bt_hci  : shut_down
,09-28 13:13:55.112  4601  4678 D bt_hwcfg: hw_epilog_process
,09-28 13:13:55.113  4601  4678 I bt_vendor: low_power_mode_cb
09-28 13:13:55.113   929  3451 D wifi    : set interface wlan0 flags (DOWN)
09-28 13:13:55.113   929  2976 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 13:13:55.116  4601  4678 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-28 13:13:55.116  4601  4678 I bt_vendor: epilog_cb
09-28 13:13:55.116  4601  4678 I bt_hci  : epilog_finished_callback
,09-28 13:13:55.118  4601  4672 I bt_hci_h4: hal_close
09-28 13:13:55.118  4601  4672 I bt_userial_vendor: device fd = 54 close
,09-28 13:13:55.226  4601  4669 D bt_stack_manager: event_shut_down_stack finished.
,09-28 13:13:55.226  4601  4668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 13:13:55.228  4601  4668 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 13:13:55.228  4601  4601 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 13:13:55.228  4601  4601 D BtGatt.GattService: Received stop request...Stopping profile...
,09-28 13:13:55.228  4601  4601 D BtGatt.GattService: stop()
09-28 13:13:55.228  4601  4601 D BtGatt.AdvertiseManager: advertise clients cleared
,09-28 13:13:55.231  4601  4601 V BluetoothAdapterState: isTurningOff()=false
,09-28 13:13:55.231  4601  4601 V BluetoothAdapterState: isTurningOn()=false
09-28 13:13:55.231  4601  4601 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:13:55.231  4601  4601 V BluetoothAdapterState: isBleTurningOff()=true
09-28 13:13:55.231  4601  4668 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 13:13:55.231  4601  4668 D BluetoothAdapterProperties: Setting state to 10
,09-28 13:13:55.231  4601  4668 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 13:13:55.232  4601  4668 I BluetoothAdapterState: Entering OffState
,09-28 13:13:55.233   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-28 13:13:55.239  4601  4601 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 13:13:55.239  4601  4601 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 13:13:55.239  4601  4601 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 13:13:55.241  4601  4669 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 13:13:55.249  4601  4601 I art     : System.exit called, status: 0
,09-28 13:13:55.249  4601  4601 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 13:13:55.270  5,730  5730 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.k.d(PG:583)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 1,3:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 13:13:55.270  5730  5730 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 13:13:55.270  5730  5730 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 13:13:55.275  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 13:13:55.277   929  3878 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-28 13:13:55.278   929  3878 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-28 13:13:55.279   929  3878 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-28 13:13:55.279   929  3878 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-28 13:13:55.279   929  3878 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-28 13:13:55.290   929  3878 I ActivityManager: Start proc 5762:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-28 13:13:55.290   929   940 W ActivityManager: Spurious death for ProcessRecord{d861054 5762:com.android.bluetooth/1002}, curProc for 4601: null
09-28 13:13:55.291  5699  5699 D DockEventReceiver: finishStartingService: stopping service
09-28 13:13:55.299   929  3564 I ActivityManager: Killing 5425:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-28 13:13:55.315   929   946 D Tethering: InitialState.processMessage what=4
09-28 13:13:55.333   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 13:13:55.382  5762  5762 D AdapterServiceConfig: Adding HeadsetService
,09-28 13:13:55.382  5762  5762 D AdapterServiceConfig: Adding A2dpService
09-28 13:13:55.383  5762  5762 D AdapterServiceConfig: Adding HidService
09-28 13:13:55.383  5762  5762 D AdapterServiceConfig: Adding HealthService
09-28 13:13:55.383  5762  5762 D AdapterServiceConfig: Adding PanService
09-28 13:13:55.383  5762  5762 D AdapterServiceConfig: Adding GattService
,09-28 13:13:55.383  5762  5762 D AdapterServiceConfig: Adding BluetoothMapService
09-28 13:13:55.383  5762  5762 D AdapterServiceConfig: Adding SapService
09-28 13:13:55.385   929  3768 I ActivityManager: Killing 5438:com.android.chrome/u0a39 (adj 15): empty #17
,09-28 13:13:55.434  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 13:13:55.442  3685  3685 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 13:13:55.445  3685  3685 D SystemUpdateService: onCreate
,09-28 13:13:55.450  3685  3685 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 13:13:55.459  3685  3685 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 13:13:55.464  3685  5422 I iu.UploadsManager: num queued entries: 0
,09-28 13:13:55.464  3685  5422 I iu.UploadsManager: num updated entries: 0
,09-28 13:13:55.466  3685  3685 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 13:13:55.469  3685  3685 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 13:13:55.469  3685  5775 I SystemUpdateService: active receiver: enabled
09-28 13:13:55.472  3685  5422 I iu.SyncManager: NEXT; no task
,09-28 13:13:55.480   929  3153 I ActivityManager: Start proc 5777:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-28 13:13:55.482  3685  5775 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 13:13:55.485  3685  5775 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 13:13:55.485  3685  5775 I SystemUpdateService: now status is 0 (complete)
09-28 13:13:55.485  3685  5775 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 13:13:55.485  3685  5775 I SystemUpdateService: file has been verified
,09-28 13:13:55.485  3685  5775 I SystemUpdateService: OTA package size = 21989297
,09-28 13:13:55.501  3685  5775 I SystemUpdateService: showing system update notification
,09-28 13:13:55.523  5777  5777 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-28 13:13:55.526  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 13:13:55.533  5777  5777 D SprintDMHelper: simOperator: 
,09-28 13:13:55.533  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 13:13:55.545   929  3831 I ActivityManager: Start proc 5789:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-28 13:13:55.548  3685  3685 D SystemUpdateService: onDestroy
,09-28 13:13:55.550   929  3768 I ActivityManager: Killing 5455:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-28 13:13:55.646  5032  5803 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 13:13:55.653   929  3564 I ActivityManager: Start proc 5804:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-28 13:13:55.655   929   939 I ActivityManager: Killing 5306:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-28 13:13:55.683  5730  5749 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-28 13:13:55.715  5804  5804 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-28 13:13:55.785   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22632a6:true
,09-28 13:13:55.919   929  3152 I ActivityManager: Killing 4682:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-28 13:13:55.967   929  3584 I ActivityManager: Start proc 5818:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-28 13:13:55.997  5818  5818 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-28 13:13:56.005   929   940 I ActivityManager: Killing 5507:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-28 13:13:59.821   929  3779 D WifiService: setWifiEnabled: true pid=5645, uid=10077
,09-28 13:13:59.822   929  3779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 13:13:59.833   507   923 D SoftapController: Softap fwReload - Ok
,09-28 13:13:59.839   507   923 D CommandListener: Setting iface cfg
,09-28 13:13:59.839   507   923 D CommandListener: Trying to bring down wlan0
,09-28 13:13:59.842   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-28 13:13:59.847   929  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 13:14:00.417   929  2976 D wifi    : set interface wlan0 flags (UP)
,09-28 13:14:00.420   929  2976 I WifiHAL : Initializing wifi
09-28 13:14:00.420   929  2976 I WifiHAL : Creating socket
,09-28 13:14:00.423   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 13:14:00.426   929  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 13:14:00.427   929  2976 D wifi    : Did set static halHandle = 0x7f97e08b80
09-28 13:14:00.427   929  2976 D wifi    : halHandle = 0x7f97e08b80, mVM = 0x7fb448d140, mCls = 0x19d2
09-28 13:14:00.427   929  2976 D wifi    : array field set
,09-28 13:14:00.427   929  2976 I WifiNative-HAL: interface[0] = wlan0
,09-28 13:14:00.429   929  5836 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=548008921984
09-28 13:14:00.430   929  5836 D wifi    : waitForHalEvents called, vm = 0x7fb448d140, obj = 0x19d2, env = 0x7f955fdd40
,09-28 13:14:00.499  5837  5837 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 13:14:00.523  5837  5837 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 13:14:00.530   929  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 13:14:00.539  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:00.540  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:00.542  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:00.546  5837  5837 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 13:14:00.547  5837  5837 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 13:14:00.561   929  2976 D WifiConfigStore: Loading config and enabling all networks 
,09-28 13:14:00.562  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:00.563  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:00.563  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:00.563  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:00.564  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:00.565  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:00.565  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:00.565  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:00.565  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:00.566  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:00.566  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:00.570   929  2976 D WifiConfigStore: loaded 0 passpoint configs
09-28 13:14:00.570   929  2976 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 13:14:00.570   929  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-28 13:14:00.571   929  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-28 13:14:00.572   929  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-28 13:14:00.572   929  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 13:14:00.572   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 13:14:00.572   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 13:14:00.574   929  2976 D WifiNative-HAL: Setting external_sim to 1
,09-28 13:14:00.574   929  2976 D wifi    : setting dfs flag to true, 0x7f9afcace0
09-28 13:14:00.575  5032  5032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 13:14:00.575   929  2976 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 13:14:00.575   929  2976 D wifi    : setting scan oui 0x7f9afcace0
09-28 13:14:00.575   929  2976 D WifiHAL : Sending mac address OUI
,09-28 13:14:00.578   929  2976 E native  : do suspend false
,09-28 13:14:00.585   929  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 13:14:00.585   929   929 D RttService: SCAN_AVAILABLE : 3
09-28 13:14:00.585   929  3085 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 13:14:00.585   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-28 13:14:00.586   507   923 D CommandListener: Setting iface cfg
,09-28 13:14:00.590   929  2961 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-28 13:14:00.590   929  2961 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 13:14:00.599   929  2961 D WifiNative-HAL: p2pGetDeviceAddress
09-28 13:14:00.600   929  2961 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 13:14:00.607   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=269152 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-28 13:14:03.763  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:03.769  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:03.774  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:03.782  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:03.841   929  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 13:14:03.842   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 13:14:03.842   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 13:14:03.854   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 13:14:03.888   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 13:14:03.890  5837  5837 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 13:14:04.316  5837  5837 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 13:14:04.351  5837  5837 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-28 13:14:04.353  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 13:14:04.365   929  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 13:14:04.365   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 13:14:04.365   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 13:14:04.382   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 13:14:04.398   507   923 D CommandListener: Setting iface cfg
,09-28 13:14:04.404   929  2976 D WifiStateMachine: Start Dhcp Watchdog 2
,09-28 13:14:04.410   929  5843 D DhcpClient: Receive thread started
,09-28 13:14:04.415   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 13:14:04.415   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
09-28 13:14:04.416   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 13:14:04.496   929  2976 E native  : do suspend false
,09-28 13:14:04.511   929  5842 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 13:14:04.530   929  5843 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172568, domain null
,09-28 13:14:04.531   929  5842 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172568 seconds
,09-28 13:14:04.533   929  5842 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 13:14:04.547   929  5843 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 13:14:04.548   929  5842 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 13:14:04.551   507   923 D CommandListener: Setting iface cfg
,09-28 13:14:04.556   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 13:14:04.562   929  5842 D DhcpClient: Scheduling renewal in 86399s
,09-28 13:14:04.570   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-28 13:14:04.571   929  2976 D WifiConfigStore: No blacklist allowed without epno enabled
09-28 13:14:04.572   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 13:14:04.574   929  2978 D ConnectivityService: Adding iface wlan0 to network 101
09-28 13:14:04.582   929  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 13:14:04.621   929  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 13:14:04.622   929  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-28 13:14:04.624   929  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-28 13:14:04.626   929  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-28 13:14:04.629   929  2978 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-28 13:14:04.635   929  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 13:14:04.639   929  2978 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-28 13:14:04.639   929  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-28 13:14:04.639   929  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-28 13:14:04.639   929  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 13:14:04.639   929  2978 D ConnectivityService:    accepting network in place of null
09-28 13:14:04.639   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 13:14:04.640   929  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 13:14:04.655   929  5841 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273200, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 13:14:04.662   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 13:14:04.682   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 13:14:04.685   929  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-28 13:14:04.685  3742  3903 W QCNEJ   : |CORE| network available: 101
09-28 13:14:04.685   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 13:14:04.687   929  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-28 13:14:04.688   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-28 13:14:04.690  3742  3903 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-28 13:14:04.691  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:04.691  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:14:04.691  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.691  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:04.691  3742  3903 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 13:14:04.691  3742  3903 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 13:14:04.696  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:04.696  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:14:04.696  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.696  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:04.699  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:04.699  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:14:04.699  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:04.699  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:04.701  5057  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 13:14:04.702  5057  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 13:14:04.702  5057  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 13:14:04.702  5057  5089 E SarControlService: no key has been found,reset the power
09-28 13:14:04.702  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 13:14:04.702  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 13:14:04.702  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 13:14:04.703  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 13:14:04.703  5090  5090 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 13:14:04.703  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-28 13:14:04.703  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 13:14:04.704  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 13:14:04.704  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 13:14:04.704  5090  5090 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 13:14:04.705  4943  4943 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-28 13:14:04.708  3685  3685 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 13:14:04.711  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000ec03000000000000ffffffff]
09-28 13:14:04.711  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:14:04.711  5090  5104 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-28 13:14:04.712  3685  3685 D SystemUpdateService: onCreate
,09-28 13:14:04.712  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:14:04.713  5057  5067 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 13:14:04.717  3685  3685 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 13:14:04.718  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000ed03000000000000ffffffff]
09-28 13:14:04.718  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:14:04.718  5090  5104 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-28 13:14:04.719  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:14:04.719  5057  5068 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-28 13:14:04.724   929  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.238,2a00:1450:4001:819::200e
,09-28 13:14:04.730  3685  3685 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 13:14:04.735  3685  5422 I iu.UploadsManager: num queued entries: 0
,09-28 13:14:04.736  3685  5422 I iu.UploadsManager: num updated entries: 0
09-28 13:14:04.736  3685  5422 I iu.SyncManager: NEXT; no task
,09-28 13:14:04.738  3685  5853 I SystemUpdateService: active receiver: enabled
,09-28 13:14:04.741  3685  3685 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 13:14:04.743  3685  3685 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 13:14:04.744  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 13:14:04.748  5777  5777 D SprintDMHelper: simOperator: 
09-28 13:14:04.748  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 13:14:04.772  3685  5853 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 13:14:04.780   929  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 17:14:04 GMT], X-Android-Received-Millis=[1475082844779], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475082844753]}
09-28 13:14:04.780   929  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 13:14:04.780   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-28 13:14:04.780   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 13:14:04.782   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 13:14:04.788  3685  5853 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 13:14:04.789  3685  5853 I SystemUpdateService: now status is 0 (complete)
09-28 13:14:04.789  3685  5853 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 13:14:04.789  3685  5853 I SystemUpdateService: file has been verified
09-28 13:14:04.789  3685  5853 I SystemUpdateService: OTA package size = 21989297
,09-28 13:14:04.794  3685  5853 I SystemUpdateService: showing system update notification
,09-28 13:14:04.807  3685  3685 D SystemUpdateService: onDestroy
,09-28 13:14:04.829   929  3874 D WifiService: setWifiEnabled: false pid=5645, uid=10077
,09-28 13:14:04.829   929  3874 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 13:14:04.830   929  2976 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 13:14:04.830   929  2976 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 13:14:04.831   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 13:14:04.831   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 13:14:04.839   929  5842 D DhcpClient: Clearing IP address
,09-28 13:14:04.840   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-28 13:14:04.841   507   923 D CommandListener: Setting iface cfg
09-28 13:14:04.842   929  5843 D DhcpClient: Receive thread stopped
,09-28 13:14:04.846  3570  5854 V NativeCrypto: SSL handshake aborted: ssl=0x7f98f78380: I/O error during system call, Connection timed out
,09-28 13:14:04.853   929  3584 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,09-28 13:14:04.853   929  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
09-28 13:14:04.853   929  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.238,2a00:1450:4001:819::200e
,09-28 13:14:04.859   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-28 13:14:04.859   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-28 13:14:04.862   533   533 E Parcel  : Reading a NULL string not supported here.
,09-28 13:14:04.865   929  5840 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:819::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-28 13:14:04.866  5032  5857 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-28 13:14:04.868   929  2976 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-28 13:14:04.868   929   929 D RttService: SCAN_AVAILABLE : 1
09-28 13:14:04.868   929  3085 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 13:14:04.868   929  2978 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-28 13:14:04.870  3742  3903 W QCNEJ   : |CORE| network lost: 101
09-28 13:14:04.870  3742  3903 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-28 13:14:04.872   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException: failed to connect to clients3.google.com/172.217.21.238 (port 80) after 5000ms: isConnected failed: ETIMEDOUT (Connection timed out)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConnected(IoBridge.java:232)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connectErrno(IoBridge.java:171)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.connect(IoBridge.java:122)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:452)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at java.net.Socket.connect(Socket.java:884)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:117)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectRawSocket(SocketConnector.java:160)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.SocketConnector.connectCleartext(SocketConnector.java:67)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connect(Connection.java:152)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.Connection.connectAndSetOwner(Connection.java:185)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.OkHttpClient$1.connectAndSetOwner(OkHttpClient.java:128)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.nextConnection(HttpEngine.java:341)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:330)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:248)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:437)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: Caused by: android.system.ErrnoException: isConnected failed: ETIMEDOUT (Connection timed out)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	at libcore.io.IoBridge.isConne,cted(IoBridge.java:223)
09-28 13:14:04.884  5032  5857 W Babel_NetworkConnectionCheckingService: 	... 23 more
09-28 13:14:04.884  5032  5857 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 13:14:04.893   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 13:14:04.911   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 13:14:04.911   507   923 D CommandListener: Clearing all IP addresses on wlan0
09-28 13:14:04.911   929  2978 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 13:14:04.911   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 13:14:04.913   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-28 13:14:04.915   929  2976 D DhcpClient: doQuit
09-28 13:14:04.915   929  2976 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 13:14:04.915   929  5842 D DhcpClient: onQuitting
09-28 13:14:04.916  5837  5837 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 13:14:04.916  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:04.916  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:04.916  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:04.916  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:04.917  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:04.917  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:04.917  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.918  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:04.919  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:04.919  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:04.919  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.919  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:04.921  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:04.922  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:04.922  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:04.922  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:04.923  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:04.924  4943  4943 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-28 13:14:04.926  3685  3685 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 13:14:04.928  5837  5837 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 13:14:04.928  5057  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 13:14:04.929  5057  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 13:14:04.929  5057  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 13:14:04.929  5057  5089 E SarControlService: no key has been found,reset the power
09-28 13:14:04.929  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 13:14:04.929  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 13:14:04.929  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-28 13:14:04.930  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 13:14:04.930  5090  5090 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 13:14:04.931  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 13:14:04.931  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-28 13:14:04.933  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 13:14:04.933  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 13:14:04.934  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 13:14:04.934  5090  5090 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 13:14:04.935  3685  3685 D SystemUpdateService: onCreate
,09-28 13:14:04.936  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000ee03000000000000ffffffff]
09-28 13:14:04.936  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:14:04.936  5090  5104 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-28 13:14:04.936  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:14:04.936  5057  5068 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 13:14:04.938  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000ef03000000000000ffffffff]
09-28 13:14:04.938  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:14:04.938  5090  5104 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-28 13:14:04.939  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:14:04.939  5057  5067 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 13:14:04.941  3685  3685 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 13:14:04.946  3685  5871 I SystemUpdateService: active receiver: enabled
,09-28 13:14:04.947  3685  3685 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 13:14:04.952  3685  5422 I iu.UploadsManager: num queued entries: 0
,09-28 13:14:04.952  3685  5422 I iu.UploadsManager: num updated entries: 0
09-28 13:14:04.952  3685  5422 I iu.SyncManager: NEXT; no task
,09-28 13:14:04.955  3685  3685 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 13:14:04.956  3685  3685 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 13:14:04.958  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 13:14:04.962  5777  5777 D SprintDMHelper: simOperator: 
09-28 13:14:04.962  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 13:14:04.974  5032  5874 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 13:14:04.972  3685  5871 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 13:14:04.980  3685  5871 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 13:14:04.980  3685  5871 I SystemUpdateService: now status is 0 (complete)
09-28 13:14:04.980  3685  5871 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 13:14:04.980  3685  5871 I SystemUpdateService: file has been verified
09-28 13:14:04.980   507   923 E Netd    : netlink response contains error (No such file or directory)
,09-28 13:14:04.981   929  2978 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-28 13:14:04.981   929  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 13:14:04.982  3685  5871 I SystemUpdateService: OTA package size = 21989297
,09-28 13:14:04.988  5837  5837 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 13:14:04.995  3685  5871 I SystemUpdateService: showing system update notification
,09-28 13:14:05.002  3685  3685 D SystemUpdateService: onDestroy
,09-28 13:14:05.005  5837  5837 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 13:14:05.110   929  2976 D wifi    : In wifi stop Hal
,09-28 13:14:05.110   929  2976 D wifi    : halHandle = 0x7f97e08b80, mVM = 0x7fb448d140, mCls = 0x19d2
,09-28 13:14:05.111   929  5836 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-28 13:14:05.111   929  5836 D WifiHAL : Got a signal to exit!!!
09-28 13:14:05.111   929  5836 I WifiHAL : Exit wifi_event_loop
09-28 13:14:05.111   929  2976 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 13:14:05.111   929  2976 E WifiHAL : Event processing terminated
,09-28 13:14:05.111   929  2976 D wifi    : In wifi cleaned up handler
09-28 13:14:05.111   929  2976 I WifiHAL : Internal cleanup completed
09-28 13:14:05.113  4076  4223 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 13:14:05.113  5032  5032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 13:14:05.114  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:05.114  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:05.115  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:05.134   929  5836 D wifi    : set interface wlan0 flags (DOWN)
,09-28 13:14:05.134   929  2976 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 13:14:05.340   929   946 D Tethering: InitialState.processMessage what=4
,09-28 13:14:05.347   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 13:14:05.686   929  2978 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-28 13:14:05.912   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:06.913   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:07.914   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:08.915   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:09.865   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@579f531:true
,09-28 13:14:09.866  5762  5762 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 13:14:09.871  5762  5762 I bt_bluedroid: init
,09-28 13:14:09.871  5762  5878 I BluetoothAdapterState: Entering OffState
,09-28 13:14:09.874  5762  5879 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 13:14:09.874  5762  5879 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 13:14:09.874  5762  5879 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 13:14:09.875  5762  5879 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-28 13:14:09.875  5762  5762 I bt_bluedroid: get_profile_interface socket
,09-28 13:14:09.878  5762  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 13:14:09.879  5762  5762 I bt_bluedroid: get_profile_interface sdp
09-28 13:14:09.881  5762  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 13:14:09.886  5762  5773 I bt_bluedroid: config_hci_snoop_log
,09-28 13:14:09.887   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 13:14:09.892  5762  5878 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 13:14:09.892  5762  5878 D BluetoothAdapterProperties: Setting state to 14
09-28 13:14:09.893  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-28 13:14:09.894  5762  5878 D BluetoothBondStateMachine: make
,09-28 13:14:09.897  5762  5883 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 13:14:09.900  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
,09-28 13:14:09.901  5762  5762 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 13:14:09.904  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:09.905  5762  5762 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 13:14:09.905  5762  5762 D BtGatt.GattService: Received start request. Starting profile...
,09-28 13:14:09.906  5762  5762 D BtGatt.GattService: start()
09-28 13:14:09.906  5762  5762 I bt_bluedroid: get_profile_interface gatt
,09-28 13:14:09.907  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:09.907  5762  5762 D BtGatt.AdvertiseManager: advertise manager created
,09-28 13:14:09.913  5762  5762 V BluetoothAdapterState: isTurningOff()=false
,09-28 13:14:09.914  5762  5762 V BluetoothAdapterState: isTurningOn()=false
,09-28 13:14:09.914  5762  5762 V BluetoothAdapterState: isBleTurningOn()=true
09-28 13:14:09.914  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:09.914  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-28 13:14:09.915   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:09.916  5762  5878 I bt_bluedroid: bt_bluedroid
09-28 13:14:09.916  5762  5879 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 13:14:09.916  5762  5879 I bt_hci  : start_up
,09-28 13:14:09.923  5762  5879 I bt_vendor: alloc value 0xf3bec871
09-28 13:14:09.923  5762  5879 I bt_vendor: init
,09-28 13:14:09.923  5762  5879 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 13:14:09.924  5762  5879 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 13:14:10.034  5762  5879 D bt_hci  : start_up starting async portion
09-28 13:14:10.035  5762  5886 I bt_hci  : event_finish_startup
,09-28 13:14:10.035  5762  5886 I bt_hci_h4: hal_open
09-28 13:14:10.035  5762  5886 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 13:14:10.038  5762  5886 I bt_userial_vendor: device fd = 54 open
,09-28 13:14:10.032  5887  5887 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 13:14:10.057  5762  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 13:14:10.060  5762  5886 D bt_hwcfg: Chipset BCM4358A3
09-28 13:14:10.061  5762  5886 D bt_hwcfg: Target name = [BCM4358A3]
09-28 13:14:10.061  5762  5886 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 13:14:10.441  5762  5886 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 13:14:10.442  5762  5886 D bt_hwcfg: Settlement delay -- 100 ms
09-28 13:14:10.442  5762  5886 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 13:14:10.576  5762  5886 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 13:14:10.576  5762  5886 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 13:14:10.578  5762  5886 I bt_hwcfg: vendor lib fwcfg completed
09-28 13:14:10.578  5762  5886 I bt_vendor: firmware callback
09-28 13:14:10.578  5762  5886 I bt_hci  : firmware_config_callback
,09-28 13:14:10.587  5762  5889 I bt_btu  : btu_task pending for preload complete event
,09-28 13:14:10.587  5762  5889 I bt_btu_task: Bluetooth chip preload is complete
,09-28 13:14:10.587  5762  5889 I bt_btu  : btu_task received preload complete event
,09-28 13:14:10.596  5762  5889 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 13:14:10.596  5762  5889 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 13:14:10.596  5762  5889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 13:14:10.596  5762  5889 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 13:14:10.596  5762  5889 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_SMP
,09-28 13:14:10.597  5762  5889 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 13:14:10.598  5762  5889 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 13:14:10.681  5762  5889 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b6a549
,09-28 13:14:10.682  5762  5889 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b6a549 
,09-28 13:14:10.700  5762  5882 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 13:14:10.702  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 13:14:10.702  5762  5882 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 13:14:10.705  5762  5882 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 13:14:10.708  5762  5882 D BluetoothAdapterProperties: Scan Mode:20
,09-28 13:14:10.708  5762  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 13:14:10.709  5762  5882 D bt_hci  : do_postload posting postload work item
09-28 13:14:10.709  5762  5886 I bt_hci  : event_postload
,09-28 13:14:10.709  5762  5886 I bt_vendor: sco_config_cb
09-28 13:14:10.709  5762  5886 I bt_hci  : sco_config_callback postload finished.
09-28 13:14:10.712  5762  5882 D bt_bte_conf: Device ID record 1 : primary
09-28 13:14:10.712  5762  5882 D bt_bte_conf:   vendorId            = 000f
,09-28 13:14:10.712  5762  5882 D bt_bte_conf:   vendorIdSource      = 0001
09-28 13:14:10.712  5762  5882 D bt_bte_conf:   product             = 1200
,09-28 13:14:10.712  5762  5882 D bt_bte_conf:   version             = 1436
09-28 13:14:10.712  5762  5882 D bt_bte_conf:   clientExecutableURL = 
09-28 13:14:10.712  5762  5882 D bt_bte_conf:   serviceDescription  = 
09-28 13:14:10.712  5762  5882 D bt_bte_conf:   documentationURL    = 
09-28 13:14:10.713  5762  5882 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 13:14:10.713  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:10.713  5762  5879 D bt_stack_manager: event_start_up_stack finished
09-28 13:14:10.714  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 13:14:10.714  5762  5878 D BluetoothAdapterProperties: Setting state to 15
09-28 13:14:10.714  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 13:14:10.716  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:10.717  5762  5886 I bt_vendor: low_power_mode_cb
09-28 13:14:10.717  5762  5878 I BluetoothAdapterState: Entering BleOnState
09-28 13:14:10.719  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:10.723  5762  5878 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 13:14:10.723  5762  5878 D BluetoothAdapterProperties: Setting state to 11
09-28 13:14:10.723  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 13:14:10.731  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:10.734  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:10.735  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:10.735  5762  5762 D HeadsetService: Received start request. Starting profile...
,09-28 13:14:10.738  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:10.739  5762  5762 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 13:14:10.739  5762  5762 D HeadsetStateMachine: make
,09-28 13:14:10.748  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
,09-28 13:14:10.749  5762  5762 D HeadsetStateMachine: max_hf_connections = 1
,09-28 13:14:10.749  5762  5762 I bt_bluedroid: get_profile_interface handsfree
09-28 13:14:10.750  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 13:14:10.750  5762  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-28 13:14:10.753  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:10.753  5762  5762 D A2dpService: Received start request. Starting profile...
09-28 13:14:10.754  5762  5762 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 13:14:10.754  5762  5762 I bt_bluedroid: get_profile_interface avrcp
,09-28 13:14:10.760  5762  5762 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 13:14:10.760  5762  5762 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 13:14:10.760  5762  5762 D A2dpStateMachine: make
09-28 13:14:10.761  5762  5762 I bt_bluedroid: get_profile_interface a2dp
,09-28 13:14:10.761  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 13:14:10.763  5762  5896 D A2dpStateMachine: Enter Disconnected: -2
,09-28 13:14:10.764  5762  5762 I BluetoothHidServiceJni: classInitNative: succeeds
,09-28 13:14:10.765  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:10.766  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 13:14:10.766  5699  5699 D BluetoothInputDevice: Proxy object connected
09-28 13:14:10.766  5762  5762 D HidService: Received start request. Starting profile...
09-28 13:14:10.767  5762  5762 I bt_bluedroid: get_profile_interface hidhost
09-28 13:14:10.767  5762  5882 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b4b56d
,09-28 13:14:10.767  5762  5762 D HidService: setHidService(): set to: null
09-28 13:14:10.767  5699  5699 D HidProfile: Bluetooth service connected
09-28 13:14:10.767  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 13:14:10.767  5762  5762 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 13:14:10.768  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:10.769  5762  5762 D HealthService: Received start request. Starting profile...
,09-28 13:14:10.770  5762  5762 I bt_bluedroid: get_profile_interface health
09-28 13:14:10.771  5762  5762 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-28 13:14:10.772  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:10.773  5699  5699 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 13:14:10.773  5762  5762 D PanService: Received start request. Starting profile...
09-28 13:14:10.773  5762  5762 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 13:14:10.773  5762  5762 I bt_bluedroid: get_profile_interface pan
,09-28 13:14:10.773  5699  5699 D PanProfile: Bluetooth service connected
09-28 13:14:10.774  5762  5882 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-28 13:14:10.775  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:10.777  5699  5699 D BluetoothMap: Proxy object connected
09-28 13:14:10.778  5762  5762 D BluetoothMapService: Received start request. Starting profile...
,09-28 13:14:10.778  5762  5762 D BluetoothMapService: start()
09-28 13:14:10.780  5762  5762 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 13:14:10.781  5762  5762 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-28 13:14:10.781  5762  5762 D BluetoothMapAppObserver: createReceiver()
09-28 13:14:10.783  5762  5762 D BluetoothMapAppObserver: initObservers()
09-28 13:14:10.783  5762  5762 D BluetoothMapAppObserver: getEnabledAccountItems()
09-28 13:14:10.788  5699  5699 D MapProfile: Bluetooth service connected
09-28 13:14:10.788  5699  5699 D BluetoothMap: getConnectedDevices()
09-28 13:14:10.789  5699  5699 D BluetoothMap: Bluetooth is Not enabled
,09-28 13:14:10.790  5762  5762 V SapService: SapBinder()
,09-28 13:14:10.790  5762  5762 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:10.791  5762  5762 D SapService: Received start request. Starting profile...
09-28 13:14:10.791  5762  5762 V SapService: start()
09-28 13:14:10.792  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:10.792  5762  5762 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 13:14:10.793  5762  5894 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:10.793  5762  5762 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:10.794  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:10.795  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 13:14:10.795  5762  5878 D BluetoothAdapterProperties: ScanMode =  20
09-28 13:14:10.795  5762  5878 D BluetoothAdapterProperties: State =  11
09-28 13:14:10.796  5762  5882 D BluetoothAdapterProperties: Scan Mode:21
09-28 13:14:10.796  5762  5882 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 13:14:10.797  5762  5878 D BluetoothAdapterProperties: Setting state to 12
,09-28 13:14:10.797  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-28 13:14:10.797  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-28 13:14:10.797  5762  5878 I BluetoothAdapterState: Entering OnState
09-28 13:14:10.798  5699  5713 D BluetoothMap: onBluetoothStateChange: up=true
09-28 13:14:10.798   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:10.798  3144  3955 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 13:14:10.800   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:10.800   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:10.800  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:10.801  3144  3157 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 13:14:10.802   929   929 D BluetoothA2dp: Proxy object connected
09-28 13:14:10.802  3144  3144 D BluetoothA2dp: Proxy object connected
,09-28 13:14:10.803  5699  5710 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 13:14:10.803  3144  3955 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 13:14:10.805  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:10.805  3789  3813 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:10.806  3144  3144 D BluetoothInputDevice: Proxy object connected
,09-28 13:14:10.806  3144  3144 D HidProfile: Bluetooth service connected
09-28 13:14:10.808  5699  5713 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:10.808  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:10.809  5762  5762 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 13:14:10.809  3144  3157 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:10.809  5762  5762 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 13:14:10.810  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:10.810  5699  5710 D BluetoothPan: onBluetoothStateChange on: true
09-28 13:14:10.810   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:10.810  3144  3955 D BluetoothPan: onBluetoothStateChange on: true
09-28 13:14:10.811  5762  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 13:14:10.812  3144  3157 D BluetoothMap: onBluetoothStateChange: up=true
09-28 13:14:10.812  3144  3144 D BluetoothPan: BluetoothPAN Proxy object connected
,09-28 13:14:10.812  3144  3144 D PanProfile: Bluetooth service connected
09-28 13:14:10.813  5762  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 13:14:10.813  3144  3144 D BluetoothMap: Proxy object connected
09-28 13:14:10.813  3144  3144 D MapProfile: Bluetooth service connected
09-28 13:14:10.813  3144  3144 D BluetoothMap: getConnectedDevices()
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:10.814  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:10.814   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-28 13:14:10.816  5762  5762 D ObexServerSockets: Succeed to create listening sockets 
,09-28 13:14:10.816  5762  5762 D ObexServerSockets0: startAccept()
,09-28 13:14:10.816  5762  5762 D ObexServerSockets0: prepareForNewConnect()
09-28 13:14:10.817  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:10.817  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-28 13:14:10.817  5699  5699 D LocalBluetoothProfileManager: Adding local A2DP profile
09-28 13:14:10.818  5762  5762 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 13:14:10.819  5762  5762 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 13:14:10.819  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:10.819  5762  5905 D ObexServerSockets0: Accepting socket connection...
09-28 13:14:10.820  5762  5904 D ObexServerSockets0: Accepting socket connection...
,09-28 13:14:10.822  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:10.822  5699  5699 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-28 13:14:10.823  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:10.823  5762  5762 D BluetoothMapService: onReceive
09-28 13:14:10.823  5762  5762 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 13:14:10.823  5762  5762 D BluetoothMapService: STATE_ON
,09-28 13:14:10.826  5762  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 13:14:10.828  5762  5906 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-28 13:14:10.828  5762  5906 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 13:14:10.830  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 13:14:10.833  5699  5699 D BluetoothA2dp: Proxy object connected
,09-28 13:14:10.836  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 13:14:10.844  3144  3144 D BluetoothPbap: Proxy object connected
09-28 13:14:10.844  3144  3144 D PbapServerProfile: Bluetooth service connected
,09-28 13:14:10.849  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,09-28 13:14:10.850  5762  5762 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 13:14:10.850  5762  5762 D ObexServerSockets0: prepareForNewConnect()
09-28 13:14:10.850  5699  5699 D BluetoothPbap: Proxy object connected
09-28 13:14:10.851  5699  5699 D PbapServerProfile: Bluetooth service connected
09-28 13:14:10.854  5762  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 13:14:10.864  5762  5914 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 13:14:10.865  5762  5914 I BtOppRfcommListener: Accept thread started.
,09-28 13:14:10.899  3789  4011 D BluetoothHeadset: Proxy object connected
,09-28 13:14:10.900  3144  3157 D BluetoothHeadset: Proxy object connected
09-28 13:14:10.900  3144  3144 D HeadsetProfile: Bluetooth service connected
09-28 13:14:10.900   929   929 D BluetoothHeadset: Proxy object connected
09-28 13:14:10.900   929   929 D BluetoothHeadset: Proxy object connected
09-28 13:14:10.900   929   929 D BluetoothHeadset: Proxy object connected
,09-28 13:14:10.900   929   946 D BluetoothHeadset: Proxy object connected
,09-28 13:14:10.908  3789  3812 D BluetoothHeadset: Proxy object connected
,09-28 13:14:10.910  3144  3955 D BluetoothHeadset: Proxy object connected
,09-28 13:14:10.910  3144  3144 D HeadsetProfile: Bluetooth service connected
09-28 13:14:10.910   929   946 D BluetoothHeadset: Proxy object connected
,09-28 13:14:10.915   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 13:14:10.925  5699  5713 D BluetoothHeadset: Proxy object connected
,09-28 13:14:10.926  5699  5699 D HeadsetProfile: Bluetooth service connected
,09-28 13:14:12.646   929  2978 D ConnectivityService: handlePromptUnvalidated 101
,09-28 13:14:14.847  5762  5878 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 13:14:14.847  5762  5878 D BluetoothAdapterProperties: Setting state to 13
,09-28 13:14:14.848  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-28 13:14:14.849  5762  5878 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 13:14:14.852  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
09-28 13:14:14.855  5762  5882 D BluetoothAdapterProperties: Scan Mode:20
,09-28 13:14:14.859  5762  5762 D BluetoothMapService: onReceive
,09-28 13:14:14.859  5762  5762 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 13:14:14.859  5762  5762 D BluetoothMapService: STATE_TURNING_OFF
09-28 13:14:14.859  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 13:14:14.860  5762  5762 D BluetoothMapService: MAP Service closeService in
09-28 13:14:14.860  5762  5762 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 13:14:14.860  5762  5762 D ObexServerSockets0: shutdown(block = true)
,09-28 13:14:14.861  5762  5904 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-28 13:14:14.862  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:14.862  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:14.863  5762  5762 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 13:14:14.864  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:14.864  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:14.865  5762  5891 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 13:14:14.865  5762  5762 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 13:14:14.865  5762  5905 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-28 13:14:14.869  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 13:14:14.872  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:14.874  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:14.876  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:14.876  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:14.877  5762  5762 I BtOppRfcommListener: stopping Accept Thread
,09-28 13:14:14.877  5762  5914 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 13:14:14.879  5762  5914 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-28 13:14:14.882  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:14.882  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 13:14:14.884  5645  5645 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 13:14:14.885  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 13:14:14.884  5762  5762 D HeadsetService: Received stop request...Stopping profile...
,09-28 13:14:14.888  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:14.889  3789  4009 D BluetoothHeadset: Proxy object disconnected
09-28 13:14:14.889  5762  5762 D A2dpService: Received stop request...Stopping profile...
09-28 13:14:14.889  5762  5896 D A2dpStateMachine: Exit Disconnected: -1
09-28 13:14:14.889  3144  3158 D BluetoothHeadset: Proxy object disconnected
,09-28 13:14:14.890   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 13:14:14.891  5699  5713 D BluetoothHeadset: Proxy object disconnected
09-28 13:14:14.891  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:14.891   929   929 D BluetoothHeadset: Proxy object disconnected
,09-28 13:14:14.891   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 13:14:14.891   929   929 D BluetoothA2dp: Proxy object disconnected
09-28 13:14:14.892  3144  3144 D HeadsetProfile: Bluetooth service disconnected
09-28 13:14:14.892  3144  3144 D BluetoothA2dp: Proxy object disconnected
09-28 13:14:14.893  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:14.893  5762  5762 D HidService: Received stop request...Stopping profile...
09-28 13:14:14.893  5762  5762 D HidService: Stopping Bluetooth HidService
,09-28 13:14:14.893  3144  3144 D BluetoothInputDevice: Proxy object disconnected
09-28 13:14:14.894  3144  3144 D HidProfile: Bluetooth service disconnected
09-28 13:14:14.894  5762  5762 D HealthService: Received stop request...Stopping profile...
,09-28 13:14:14.896  5699  5699 D DockEventReceiver: finishStartingService: stopping service
09-28 13:14:14.896  5762  5762 D PanService: Received stop request...Stopping profile...
09-28 13:14:14.897  5699  5699 D BluetoothA2dp: Proxy object disconnected
09-28 13:14:14.897  3144  3144 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-28 13:14:14.897  3144  3144 D PanProfile: Bluetooth service disconnected
09-28 13:14:14.897  5699  5699 D HeadsetProfile: Bluetooth service disconnected
09-28 13:14:14.901  5762  5762 D BluetoothMapService: Received stop request...Stopping profile...
09-28 13:14:14.910  5699  5699 D BluetoothInputDevice: Proxy object disconnected
09-28 13:14:14.910  5699  5699 D HidProfile: Bluetooth service disconnected
09-28 13:14:14.910  5762  5762 D BluetoothMapService: stop()
09-28 13:14:14.910  5699  5699 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 13:14:14.910  5699  5699 D PanProfile: Bluetooth service disconnected
09-28 13:14:14.901  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 13:14:14.911  5762  5762 D BluetoothMapAppObserver: deinitObservers()
09-28 13:14:14.911  5762  5762 D BluetoothMapAppObserver: removeReceiver()
,09-28 13:14:14.913  3144  3144 D BluetoothMap: Proxy object disconnected
09-28 13:14:14.913  3144  3144 D MapProfile: Bluetooth service disconnected
09-28 13:14:14.913  5699  5699 D BluetoothMap: Proxy object disconnected
09-28 13:14:14.914  5699  5699 D MapProfile: Bluetooth service disconnected
,09-28 13:14:14.915  5762  5762 D SapService: Received stop request...Stopping profile...
09-28 13:14:14.915  5762  5762 V SapService: stop()
09-28 13:14:14.916  5762  5762 V BluetoothAdapterState: isTurningOff()=true
09-28 13:14:14.916  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:14.916  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:14.916  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:14.917  5762  5762 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 13:14:14.917  5762  5762 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 13:14:14.917  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:14:14.917  5762  5762 V BluetoothAdapterState: isTurningOff()=true
09-28 13:14:14.917  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:14:14.917  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:14.917  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:14:14.918  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-28 13:14:14.918  5762  5882 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 13:14:14.917  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:14.918  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:14.919  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 13:14:14.919  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:14:14.919  5762  5762 V BluetoothAdapterState: isTurningOff()=true
09-28 13:14:14.919  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:14.919  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:14:14.919  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:14.919  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:14.919  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 13:14:14.919  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 13:14:14.919  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 13:14:14.919  5762  5889 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 13:14:14.919  5762  5762 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 13:14:14.919  5762  5762 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 13:14:14.920  5762  5762 V BluetoothAdapterState: isTurningOff()=true
09-28 13:14:14.920  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:14.920  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 13:14:14.920  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:14.920  5762  5762 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 13:14:14.920  5762  5762 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 13:14:14.920  5762  5882 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 13:14:14.921  5762  5762 V BluetoothAdapterState: isTurningOff()=true
09-28 13:14:14.921  5762  5882 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 13:14:14.921  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:14.921  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:14.921  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 13:14:14.921  5762  5762 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 13:14:14.921  5762  5762 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-28 13:14:14.925  3144  3144 D BluetoothPbap: Proxy object disconnected
09-28 13:14:14.925  3144  3144 D PbapServerProfile: Bluetooth service disconnected
,09-28 13:14:14.926  5762  5762 D BluetoothMapService: MAP Service closeService in
,09-28 13:14:14.926  5762  5762 V BluetoothAdapterState: isTurningOff()=true
09-28 13:14:14.926  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:14.926  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:14.926  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:14.926  5762  5762 D BluetoothMapService: cleanup()
,09-28 13:14:14.926  5762  5762 D BluetoothMapService: MAP Service closeService in
09-28 13:14:14.927  5762  5762 V BluetoothAdapterState: isTurningOff()=true
09-28 13:14:14.927  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:14.927  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:14.927  5762  5762 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:14.927  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 13:14:14.928  5762  5878 D BluetoothAdapterProperties: Setting state to 15
09-28 13:14:14.928  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-28 13:14:14.928  5762  5878 I BluetoothAdapterState: Entering BleOnState
09-28 13:14:14.929  5699  5713 D BluetoothMap: onBluetoothStateChange: up=false
09-28 13:14:14.929   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:14:14.929  5699  5710 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 13:14:14.930  3144  3158 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 13:14:14.930   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:14:14.930   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 13:14:14.930  5699  5713 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:14:14.931  3144  3157 D BluetoothPbap: onBluetoothStateChange: up=false
,09-28 13:14:14.931  5699  5710 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 13:14:14.932  3144  3955 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 13:14:14.932  3789  3813 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:14:14.933  5699  5713 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 13:14:14.934  3144  3158 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:14:14.935  5699  5710 D BluetoothPan: onBluetoothStateChange on: false
09-28 13:14:14.935  5699  5699 D BluetoothPbap: Proxy object disconnected
09-28 13:14:14.935   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 13:14:14.936  3144  3157 D BluetoothPan: onBluetoothStateChange on: false
09-28 13:14:14.936  3144  3955 D BluetoothMap: onBluetoothStateChange: up=false
09-28 13:14:14.937  5762  5878 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 13:14:14.937  5762  5878 D BluetoothAdapterProperties: Setting state to 16
09-28 13:14:14.937  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 13:14:14.935  5699  5699 D PbapServerProfile: Bluetooth service disconnected
09-28 13:14:14.937  5762  5878 D BluetoothAdapterProperties: onBleDisable
09-28 13:14:14.938  5762  5879 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 13:14:14.939  5762  5889 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 13:14:14.939  5762  5889 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 13:14:14.939  5762  5878 I BluetoothAdapterState: Entering PendingCommandState
09-28 13:14:14.940  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:14.941  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:14.941  5762  5882 D BluetoothAdapterProperties: Scan Mode:20
,09-28 13:14:14.942  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:14.943  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 13:14:14.946  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:14.949  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:14.951  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:14.954  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 13:14:14.956  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,09-28 13:14:15.152  5762  5882 I bt_hci  : shut_down
,09-28 13:14:15.157  5762  5886 D bt_hwcfg: hw_epilog_process
,09-28 13:14:15.158  5762  5886 I bt_vendor: low_power_mode_cb
,09-28 13:14:15.161  5762  5886 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-28 13:14:15.162  5762  5886 I bt_vendor: epilog_cb
,09-28 13:14:15.162  5762  5886 I bt_hci  : epilog_finished_callback
,09-28 13:14:15.167  5762  5882 I bt_hci_h4: hal_close
,09-28 13:14:15.168  5762  5882 I bt_userial_vendor: device fd = 54 close
,09-28 13:14:15.287  5762  5879 D bt_stack_manager: event_shut_down_stack finished.
,09-28 13:14:15.287  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 13:14:15.291  5762  5878 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-28 13:14:15.292  5762  5762 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 13:14:15.293  5762  5762 D BtGatt.GattService: Received stop request...Stopping profile...
09-28 13:14:15.293  5762  5762 D BtGatt.GattService: stop()
,09-28 13:14:15.293  5762  5762 D BtGatt.AdvertiseManager: advertise clients cleared
,09-28 13:14:15.296  5762  5762 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:15.296  5762  5762 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:15.296  5762  5762 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 13:14:15.297  5762  5762 V BluetoothAdapterState: isBleTurningOff()=true
09-28 13:14:15.297  5762  5878 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 13:14:15.297  5762  5878 D BluetoothAdapterProperties: Setting state to 10
09-28 13:14:15.297  5762  5878 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 13:14:15.298  5762  5878 I BluetoothAdapterState: Entering OffState
,09-28 13:14:15.299   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-28 13:14:15.311  5762  5762 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-28 13:14:15.311  5762  5762 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-28 13:14:15.311  5762  5879 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-28 13:14:15.313  5762  5762 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-28 13:14:15.317  5762  5762 I art     : System.exit called, status: 0
,09-28 13:14:15.317  5762  5762 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 13:14:15.342   929  3768 I ActivityManager: Process com.android.bluetooth (pid 5762) has died
,09-28 13:14:19.848  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 13:14:19.848  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:19.853  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:14:19.853  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3714f8e removed from the list
09-28 13:14:19.853  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:19.853  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:19.853  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:19.858  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 13:14:19.858  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0d23bc added. We now have 4 listener(s)
09-28 13:14:19.858  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:19.860  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:14:19.860  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b0d23bc removed from the list
09-28 13:14:19.860  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:19.861  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:19.861  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:19.862  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:19.863  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e3af45 added. We now have 4 listener(s)
09-28 13:14:19.863  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:14:24.872  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:24.907   929   946 I ActivityManager: Start proc 5922:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 13:14:24.985  5922  5922 D AdapterServiceConfig: Adding HeadsetService
,09-28 13:14:24.985  5922  5922 D AdapterServiceConfig: Adding A2dpService
09-28 13:14:24.985  5922  5922 D AdapterServiceConfig: Adding HidService
09-28 13:14:24.985  5922  5922 D AdapterServiceConfig: Adding HealthService
09-28 13:14:24.985  5922  5922 D AdapterServiceConfig: Adding PanService
09-28 13:14:24.986  5922  5922 D AdapterServiceConfig: Adding GattService
09-28 13:14:24.986  5922  5922 D AdapterServiceConfig: Adding BluetoothMapService
09-28 13:14:24.986  5922  5922 D AdapterServiceConfig: Adding SapService
,09-28 13:14:24.996   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@deb36d6:true
,09-28 13:14:24.997  5922  5922 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 13:14:24.999  5922  5922 I bt_bluedroid: init
09-28 13:14:25.000  5922  5934 I BluetoothAdapterState: Entering OffState
,09-28 13:14:25.002  5922  5935 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-28 13:14:25.002  5922  5935 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 13:14:25.002  5922  5935 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 13:14:25.002  5922  5935 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-28 13:14:25.003  5922  5922 I bt_bluedroid: get_profile_interface socket
,09-28 13:14:25.005  5922  5938 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 13:14:25.006  5922  5922 I bt_bluedroid: get_profile_interface sdp
09-28 13:14:25.007  5922  5938 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 13:14:25.012  5922  5933 I bt_bluedroid: config_hci_snoop_log
,09-28 13:14:25.016   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 13:14:25.020  5922  5934 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 13:14:25.021  5922  5934 D BluetoothAdapterProperties: Setting state to 14
09-28 13:14:25.021  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-28 13:14:25.022  5922  5934 D BluetoothBondStateMachine: make
,09-28 13:14:25.024  5922  5939 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 13:14:25.027  5922  5934 I BluetoothAdapterState: Entering PendingCommandState
,09-28 13:14:25.029  5922  5922 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 13:14:25.031  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:25.032  5922  5922 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 13:14:25.033  5922  5922 D BtGatt.GattService: Received start request. Starting profile...
09-28 13:14:25.033  5922  5922 D BtGatt.GattService: start()
09-28 13:14:25.033  5922  5922 I bt_bluedroid: get_profile_interface gatt
,09-28 13:14:25.035  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:25.035  5922  5922 D BtGatt.AdvertiseManager: advertise manager created
,09-28 13:14:25.041  5922  5922 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:25.041  5922  5922 V BluetoothAdapterState: isTurningOn()=false
09-28 13:14:25.042  5922  5922 V BluetoothAdapterState: isBleTurningOn()=true
,09-28 13:14:25.042  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:25.042  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-28 13:14:25.044  5922  5934 I bt_bluedroid: bt_bluedroid
09-28 13:14:25.044  5922  5935 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 13:14:25.044  5922  5935 I bt_hci  : start_up
,09-28 13:14:25.050  5922  5935 I bt_vendor: alloc value 0xf3c3f871
09-28 13:14:25.050  5922  5935 I bt_vendor: init
09-28 13:14:25.050  5922  5935 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 13:14:25.051  5922  5935 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 13:14:25.163  5922  5935 D bt_hci  : start_up starting async portion
,09-28 13:14:25.164  5922  5942 I bt_hci  : event_finish_startup
09-28 13:14:25.164  5922  5942 I bt_hci_h4: hal_open
,09-28 13:14:25.164  5922  5942 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 13:14:25.162  5943  5943 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 13:14:25.169  5922  5942 I bt_userial_vendor: device fd = 54 open
,09-28 13:14:25.186  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 13:14:25.190  5922  5942 D bt_hwcfg: Chipset BCM4358A3
,09-28 13:14:25.190  5922  5942 D bt_hwcfg: Target name = [BCM4358A3]
09-28 13:14:25.190  5922  5942 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 13:14:25.699  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-28 13:14:25.700  5922  5942 D bt_hwcfg: Settlement delay -- 100 ms
,09-28 13:14:25.700  5922  5942 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 13:14:25.835  5922  5942 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 13:14:25.835  5922  5942 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 13:14:25.837  5922  5942 I bt_hwcfg: vendor lib fwcfg completed
09-28 13:14:25.837  5922  5942 I bt_vendor: firmware callback
09-28 13:14:25.837  5922  5942 I bt_hci  : firmware_config_callback
,09-28 13:14:25.847  5922  5945 I bt_btu  : btu_task pending for preload complete event
,09-28 13:14:25.847  5922  5945 I bt_btu_task: Bluetooth chip preload is complete
09-28 13:14:25.847  5922  5945 I bt_btu  : btu_task received preload complete event
,09-28 13:14:25.855  5922  5945 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 13:14:25.855  5922  5945 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_BNEP
09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTM
,09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 13:14:25.856  5922  5945 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 13:14:25.857  5922  5945 I         : BTE_InitTraceLevels -- TRC_SDP
09-28 13:14:25.857  5922  5945 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 13:14:25.857  5922  5945 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 13:14:25.857  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 13:14:25.857  5922  5945 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 13:14:25.953  5922  5945 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bbd549
,09-28 13:14:25.954  5922  5945 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bbd549 
,09-28 13:14:25.986  5922  5938 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 13:14:25.988  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 13:14:25.988  5922  5938 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 13:14:25.990  5922  5938 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 13:14:25.994  5922  5938 D BluetoothAdapterProperties: Scan Mode:20
,09-28 13:14:25.994  5922  5938 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 13:14:25.994  5922  5938 D bt_hci  : do_postload posting postload work item
09-28 13:14:25.995  5922  5942 I bt_hci  : event_postload
09-28 13:14:25.995  5922  5942 I bt_vendor: sco_config_cb
09-28 13:14:25.995  5922  5942 I bt_hci  : sco_config_callback postload finished.
,09-28 13:14:26.001  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:26.002  5922  5942 I bt_vendor: low_power_mode_cb
09-28 13:14:26.003  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:26.004  5922  5938 D bt_bte_conf: Device ID record 1 : primary
09-28 13:14:26.004  5922  5938 D bt_bte_conf:   vendorId            = 000f
09-28 13:14:26.004  5922  5938 D bt_bte_conf:   vendorIdSource      = 0001
09-28 13:14:26.004  5922  5938 D bt_bte_conf:   product             = 1200
,09-28 13:14:26.004  5922  5938 D bt_bte_conf:   version             = 1436
09-28 13:14:26.004  5922  5938 D bt_bte_conf:   clientExecutableURL = 
09-28 13:14:26.004  5922  5938 D bt_bte_conf:   serviceDescription  = 
09-28 13:14:26.004  5922  5938 D bt_bte_conf:   documentationURL    = 
09-28 13:14:26.004  5922  5938 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 13:14:26.004  5922  5935 D bt_stack_manager: event_start_up_stack finished
09-28 13:14:26.005  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 13:14:26.005  5922  5934 D BluetoothAdapterProperties: Setting state to 15
09-28 13:14:26.005  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 13:14:26.006  5922  5934 I BluetoothAdapterState: Entering BleOnState
,09-28 13:14:26.009  5922  5934 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 13:14:26.009  5922  5934 D BluetoothAdapterProperties: Setting state to 11
09-28 13:14:26.009  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 13:14:26.013  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:26.016  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:26.018  5922  5922 D HeadsetService: Received start request. Starting profile...
,09-28 13:14:26.018  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:26.020  5922  5922 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-28 13:14:26.021  5922  5922 D HeadsetStateMachine: make
,09-28 13:14:26.029  5922  5934 I BluetoothAdapterState: Entering PendingCommandState
,09-28 13:14:26.030  5922  5922 D HeadsetStateMachine: max_hf_connections = 1
,09-28 13:14:26.030  5922  5922 I bt_bluedroid: get_profile_interface handsfree
09-28 13:14:26.030  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 13:14:26.030  5922  5938 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-28 13:14:26.035  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:26.035  5922  5922 D A2dpService: Received start request. Starting profile...
,09-28 13:14:26.036  5922  5922 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 13:14:26.036  5922  5922 I bt_bluedroid: get_profile_interface avrcp
,09-28 13:14:26.043  5922  5922 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 13:14:26.043  5922  5922 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 13:14:26.043  5922  5922 D A2dpStateMachine: make
,09-28 13:14:26.045  5922  5922 I bt_bluedroid: get_profile_interface a2dp
,09-28 13:14:26.045  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 13:14:26.046  5922  5953 D A2dpStateMachine: Enter Disconnected: -2
09-28 13:14:26.048  5922  5922 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 13:14:26.049  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:26.049  5922  5922 D HidService: Received start request. Starting profile...
09-28 13:14:26.049  5922  5922 I bt_bluedroid: get_profile_interface hidhost
09-28 13:14:26.050  5922  5922 D HidService: setHidService(): set to: null
09-28 13:14:26.050  5922  5922 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 13:14:26.050  5922  5938 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9e56d
09-28 13:14:26.050  5922  5938 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 13:14:26.051  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
09-28 13:14:26.051  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 13:14:26.051  5922  5922 D HealthService: Received start request. Starting profile...
,09-28 13:14:26.053  5922  5922 I bt_bluedroid: get_profile_interface health
,09-28 13:14:26.054  5922  5922 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-28 13:14:26.055  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:26.055  5922  5922 D PanService: Received start request. Starting profile...
09-28 13:14:26.056  5922  5922 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-28 13:14:26.056  5922  5922 I bt_bluedroid: get_profile_interface pan
09-28 13:14:26.056  5922  5938 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-28 13:14:26.062  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:26.063  5922  5922 D BluetoothMapService: Received start request. Starting profile...
09-28 13:14:26.063  5922  5922 D BluetoothMapService: start()
,09-28 13:14:26.065  5922  5922 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-28 13:14:26.066  5922  5922 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 13:14:26.066  5922  5922 D BluetoothMapAppObserver: createReceiver()
,09-28 13:14:26.067  5922  5922 D BluetoothMapAppObserver: initObservers()
09-28 13:14:26.067  5922  5922 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 13:14:26.075  5922  5922 V SapService: SapBinder()
09-28 13:14:26.075  5922  5922 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:26.076  5922  5922 D SapService: Received start request. Starting profile...
09-28 13:14:26.076  5922  5922 V SapService: start()
,09-28 13:14:26.077  5922  5922 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:26.077  5922  5922 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:26.077  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 13:14:26.077  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:26.077  5922  5951 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 13:14:26.077  5922  5922 V BluetoothAdapterState: isTurningOff()=false
,09-28 13:14:26.077  5922  5922 V BluetoothAdapterState: isTurningOn()=true
,09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isTurningOn()=true
,09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:26.078  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:26.079  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:26.080  5922  5922 V BluetoothAdapterState: isTurningOff()=false
09-28 13:14:26.080  5922  5922 V BluetoothAdapterState: isTurningOn()=true
09-28 13:14:26.080  5922  5922 V BluetoothAdapterState: isBleTurningOn()=false
09-28 13:14:26.080  5922  5922 V BluetoothAdapterState: isBleTurningOff()=false
09-28 13:14:26.080  5922  5934 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-28 13:14:26.080  5922  5934 D BluetoothAdapterProperties: ScanMode =  20
09-28 13:14:26.080  5922  5934 D BluetoothAdapterProperties: State =  11
09-28 13:14:26.081  5922  5934 D BluetoothAdapterProperties: Setting state to 12
09-28 13:14:26.081  5922  5934 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 13:14:26.081  5922  5934 I BluetoothAdapterState: Entering OnState
09-28 13:14:26.082  5699  5710 D BluetoothMap: onBluetoothStateChange: up=true
09-28 13:14:26.085  5922  5938 D BluetoothAdapterProperties: Scan Mode:21
09-28 13:14:26.085  5922  5938 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 13:14:26.086  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-28 13:14:26.086   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:26.086  5699  5713 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 13:14:26.088  3144  3157 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:26.089  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:26.090   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:26.090   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 13:14:26.090  3144  3144 D BluetoothA2dp: Proxy object connected
09-28 13:14:26.090   929   929 D BluetoothA2dp: Proxy object connected
09-28 13:14:26.090  5699  5713 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:26.091  3144  3158 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 13:14:26.091  5699  5699 D BluetoothMap: Proxy object connected
09-28 13:14:26.092  5699  5699 D MapProfile: Bluetooth service connected
09-28 13:14:26.092  5699  5699 D BluetoothMap: getConnectedDevices()
,09-28 13:14:26.094  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:26.094  5699  5699 D BluetoothA2dp: Proxy object connected
09-28 13:14:26.094  5922  5922 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 13:14:26.095  5922  5922 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 13:14:26.097  5922  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 13:14:26.097  5699  5710 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:26.097  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:26.099  3144  3157 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 13:14:26.099  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:26.100  3789  3813 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:26.101  5699  5713 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 13:14:26.101  5922  5922 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 13:14:26.102  3144  3955 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:26.102  5922  5922 D ObexServerSockets: Succeed to create listening sockets 
,09-28 13:14:26.102  5922  5922 D ObexServerSockets0: startAccept()
,09-28 13:14:26.102  5922  5922 D ObexServerSockets0: prepareForNewConnect()
09-28 13:14:26.103  5699  5958 D BluetoothPan: onBluetoothStateChange on: true
09-28 13:14:26.104   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 13:14:26.104  3144  3158 D BluetoothPan: onBluetoothStateChange on: true
09-28 13:14:26.105  5922  5922 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 13:14:26.105  5922  5922 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 13:14:26.106  5922  5961 D ObexServerSockets0: Accepting socket connection...
09-28 13:14:26.106  5922  5962 D ObexServerSockets0: Accepting socket connection...
09-28 13:14:26.106  3144  3157 D BluetoothMap: onBluetoothStateChange: up=true
,09-28 13:14:26.106  3144  3144 D BluetoothInputDevice: Proxy object connected
09-28 13:14:26.106  3144  3144 D HidProfile: Bluetooth service connected
09-28 13:14:26.108  5699  5699 D BluetoothInputDevice: Proxy object connected
09-28 13:14:26.108  5699  5699 D HidProfile: Bluetooth service connected
09-28 13:14:26.109  3144  3144 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 13:14:26.110  3144  3144 D PanProfile: Bluetooth service connected
09-28 13:14:26.110  3144  3144 D BluetoothMap: Proxy object connected
09-28 13:14:26.110  3144  3144 D MapProfile: Bluetooth service connected
09-28 13:14:26.110  3144  3144 D BluetoothMap: getConnectedDevices()
09-28 13:14:26.110  5645  5645 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-28 13:14:26.110  5922  5922 D BluetoothMapService: onReceive
09-28 13:14:26.110  5922  5922 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 13:14:26.110  5922  5922 D BluetoothMapService: STATE_ON
09-28 13:14:26.111   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-28 13:14:26.112  5699  5699 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 13:14:26.112  5699  5699 D PanProfile: Bluetooth service connected
09-28 13:14:26.112  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:26.113  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:26.113  5922  5963 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 13:14:26.115  5922  5963 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 13:14:26.115  5922  5963 D BluetoothSdpJni: SDP Create record success - handle: 1
09-28 13:14:26.117  5699  5699 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 13:14:26.123  5699  5699 D DockEventReceiver: finishStartingService: stopping service
,09-28 13:14:26.125  3570  3570 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 13:14:26.131  5699  5699 D BluetoothPbap: Proxy object connected
,09-28 13:14:26.131  5699  5699 D PbapServerProfile: Bluetooth service connected
,09-28 13:14:26.137  3144  3144 D BluetoothPbap: Proxy object connected
09-28 13:14:26.137  3144  3144 D PbapServerProfile: Bluetooth service connected
,09-28 13:14:26.138  5922  5922 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 13:14:26.138  5922  5922 D ObexServerSockets0: prepareForNewConnect()
09-28 13:14:26.140  5922  5967 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 13:14:26.154  5922  5971 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 13:14:26.155  5922  5971 I BtOppRfcommListener: Accept thread started.
,09-28 13:14:26.188  3789  4011 D BluetoothHeadset: Proxy object connected
09-28 13:14:26.188  3144  3157 D BluetoothHeadset: Proxy object connected
09-28 13:14:26.188  3144  3144 D HeadsetProfile: Bluetooth service connected
,09-28 13:14:26.189   929   929 D BluetoothHeadset: Proxy object connected
,09-28 13:14:26.189  5699  5710 D BluetoothHeadset: Proxy object connected
,09-28 13:14:26.189   929   929 D BluetoothHeadset: Proxy object connected
09-28 13:14:26.189   929   929 D BluetoothHeadset: Proxy object connected
09-28 13:14:26.190   929   946 D BluetoothHeadset: Proxy object connected
09-28 13:14:26.190  5699  5699 D HeadsetProfile: Bluetooth service connected
09-28 13:14:26.192  5699  5713 D BluetoothHeadset: Proxy object connected
09-28 13:14:26.192  5699  5699 D HeadsetProfile: Bluetooth service connected
,09-28 13:14:26.202  3789  3812 D BluetoothHeadset: Proxy object connected
,09-28 13:14:26.203  3144  3158 D BluetoothHeadset: Proxy object connected
,09-28 13:14:26.203  3144  3144 D HeadsetProfile: Bluetooth service connected
,09-28 13:14:26.205   929   946 D BluetoothHeadset: Proxy object connected
,09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:29.889  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 13:14:29.895  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 13:14:29.895  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:29.896  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4e3af45 removed from the list
,09-28 13:14:29.896  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:29.896  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:14:29.896  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:29.898  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:29.899  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b6d69a added. We now have 4 listener(s)
,09-28 13:14:29.899  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:14:29.902   929  3779 D WifiService: setWifiEnabled: false pid=5645, uid=10077
,09-28 13:14:29.903   929  3779 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 13:14:30.916   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:31.918   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:32.919   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:33.920   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:34.913  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:34.914   929  3831 D WifiService: setWifiEnabled: true pid=5645, uid=10077
09-28 13:14:34.915   929  3831 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 13:14:34.921   507   923 D SoftapController: Softap fwReload - Ok
,09-28 13:14:34.921   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:14:34.927   507   923 D CommandListener: Setting iface cfg
,09-28 13:14:34.928   507   923 D CommandListener: Trying to bring down wlan0
,09-28 13:14:34.930   507   923 D CommandListener: Clearing all IP addresses on wlan0
,09-28 13:14:34.937   929  2976 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 13:14:35.622   929  2976 D wifi    : set interface wlan0 flags (UP)
,09-28 13:14:35.625   929  2976 I WifiHAL : Initializing wifi
09-28 13:14:35.625   929  2976 I WifiHAL : Creating socket
,09-28 13:14:35.631   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 13:14:35.633   929  2976 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 13:14:35.634   929  2976 D wifi    : Did set static halHandle = 0x7f97e08b80
09-28 13:14:35.634   929  2976 D wifi    : halHandle = 0x7f97e08b80, mVM = 0x7fb448d140, mCls = 0x157a
09-28 13:14:35.634   929  2976 D wifi    : array field set
09-28 13:14:35.634   929  2976 I WifiNative-HAL: interface[0] = wlan0
09-28 13:14:35.636   929  5976 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=548008921984
09-28 13:14:35.636   929  5976 D wifi    : waitForHalEvents called, vm = 0x7fb448d140, obj = 0x157a, env = 0x7f981f3840
,09-28 13:14:35.693  5977  5977 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 13:14:35.714  5977  5977 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 13:14:35.727  5977  5977 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 13:14:35.727  5977  5977 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 13:14:35.738   929  2976 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 13:14:35.744  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:35.748   929  2976 D WifiConfigStore: Loading config and enabling all networks 
,09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:35.752  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 13:14:35.754  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 13:14:35.757  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 13:14:35.759  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 13:14:35.760  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:35.766   929  2976 D WifiConfigStore: loaded 0 passpoint configs
09-28 13:14:35.766   929  2976 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 13:14:35.767   929  2976 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 13:14:35.769   929  2976 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-28 13:14:35.770   929  2976 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 13:14:35.770   929  2976 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 13:14:35.770   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 13:14:35.770   929  2976 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 13:14:35.774   929  2976 D WifiNative-HAL: Setting external_sim to 1
,09-28 13:14:35.774  5032  5032 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 13:14:35.774   929  2976 D wifi    : setting dfs flag to true, 0x7f9afca2c0
09-28 13:14:35.775   929  2976 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 13:14:35.775   929  2976 D wifi    : setting scan oui 0x7f9afca2c0
09-28 13:14:35.775   929  2976 D WifiHAL : Sending mac address OUI
,09-28 13:14:35.779   929  2976 E native  : do suspend false
,09-28 13:14:35.787   929  2976 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-28 13:14:35.788   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 13:14:35.788   929   929 D RttService: SCAN_AVAILABLE : 3
09-28 13:14:35.788   929  3085 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 13:14:35.789   507   923 D CommandListener: Setting iface cfg
,09-28 13:14:35.792   929  2961 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-28 13:14:35.792   929  2961 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 13:14:35.802   929  2961 D WifiNative-HAL: p2pGetDeviceAddress
,09-28 13:14:35.803   929  2961 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 13:14:35.809   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=304354 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-28 13:14:35.922   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 13:14:38.990  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:38.999  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:39.004  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:39.010  5977  5977 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 13:14:39.045   929  2976 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 13:14:39.046   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 13:14:39.046   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 13:14:39.058   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 13:14:39.092   929  2976 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 13:14:39.095  5977  5977 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 13:14:39.518  5977  5977 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 13:14:39.550  5977  5977 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 13:14:39.550  5977  5977 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 13:14:39.564   929  2976 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 13:14:39.564   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-28 13:14:39.564   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 13:14:39.580   929  2976 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 13:14:39.593   507   923 D CommandListener: Setting iface cfg
,09-28 13:14:39.599   929  2976 D WifiStateMachine: Start Dhcp Watchdog 3
,09-28 13:14:39.610   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 13:14:39.610   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 13:14:39.611   929  2978 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 13:14:39.614   929  5982 D DhcpClient: Receive thread started
,09-28 13:14:39.695   929  2976 E native  : do suspend false
,09-28 13:14:39.708   929  5981 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 13:14:39.723   929  5982 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-28 13:14:39.724   929  5981 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
09-28 13:14:39.725   929  5981 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 13:14:39.740   929  5982 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 13:14:39.740   929  5981 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 13:14:39.744   507   923 D CommandListener: Setting iface cfg
,09-28 13:14:39.749   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 13:14:39.752   929  5981 D DhcpClient: Scheduling renewal in 86399s
,09-28 13:14:39.761   929  2976 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-28 13:14:39.763   929  2976 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 13:14:39.764   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-28 13:14:39.766   929  2978 D ConnectivityService: Adding iface wlan0 to network 102
09-28 13:14:39.769   929  2976 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 13:14:39.820   929  2978 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-28 13:14:39.821   929  2978 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-28 13:14:39.823   929  2978 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-28 13:14:39.827   929  2978 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-28 13:14:39.830   929  2978 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-28 13:14:39.837   929  2978 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 13:14:39.842   929  2978 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-28 13:14:39.842   929  2978 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-28 13:14:39.842   929  2978 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-28 13:14:39.842   929  2976 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 13:14:39.842   929  2978 D ConnectivityService:    accepting network in place of null
09-28 13:14:39.842   929  2976 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 13:14:39.843   929  2978 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 13:14:39.855   929  5980 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308400, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 13:14:39.864   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 13:14:39.884   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 13:14:39.887   929  2978 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-28 13:14:39.888   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 13:14:39.888  3742  3903 W QCNEJ   : |CORE| network available: 102
09-28 13:14:39.889   929  2978 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-28 13:14:39.891   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-28 13:14:39.894  3742  3903 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 13:14:39.895  3742  3903 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 13:14:39.896  3742  3903 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:39.898  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:14:39.900  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:39.905  5645  5645 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:14:39.906  5645  5645 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:14:39.912  5057  5089 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 13:14:39.912  5057  5089 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 13:14:39.912  5057  5089 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 13:14:39.912  5057  5089 E SarControlService: no key has been found,reset the power
09-28 13:14:39.912  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 13:14:39.912  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 13:14:39.912  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 13:14:39.913  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 13:14:39.913  5090  5090 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 13:14:39.914  5057  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 13:14:39.914  5057  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 13:14:39.914  5057  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-28 13:14:39.915  4943  4943 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-28 13:14:39.917  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 13:14:39.918  3685  3685 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 13:14:39.920  5090  5090 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 13:14:39.922   929  5979 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.238,2a00:1450:4001:819::200e
09-28 13:14:39.925  3685  3685 D SystemUpdateService: onCreate
,09-28 13:14:39.926  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000f003000000000000ffffffff]
09-28 13:14:39.927  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:14:39.927  5090  5104 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,09-28 13:14:39.927  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:14:39.927  5057  5068 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 13:14:39.928  5090  5104 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8a0df HexData = [00000000f103000000000000ffffffff]
,09-28 13:14:39.928  5090  5104 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 13:14:39.928  5090  5104 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-28 13:14:39.928  5090  5090 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:39.929  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:14:39.929  5057  5067 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 13:14:39.930  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:39.930  3685  3685 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 13:14:39.931  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:39.931  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8b6d69a removed from the list
09-28 13:14:39.931  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:39.931  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:39.931  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:39.936  5645  5993 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-28 13:14:39.936  5645  5993 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 13:14:39.940  3685  3685 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 13:14:39.945  3685  5422 I iu.UploadsManager: num queued entries: 0
,09-28 13:14:39.945  3685  5422 I iu.UploadsManager: num updated entries: 0
09-28 13:14:39.946  3685  5422 I iu.SyncManager: NEXT; no task
,09-28 13:14:39.950  3685  3685 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 13:14:39.951  3685  3685 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-28 13:14:39.953  5777  5777 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 13:14:39.956  5777  5777 D SprintDMHelper: simOperator: 
09-28 13:14:39.956  5777  5777 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 13:14:39.965  3685  5992 I SystemUpdateService: active receiver: enabled
,09-28 13:14:39.990  3685  5992 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 13:14:39.990   929  5979 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 17:14:39 GMT], X-Android-Received-Millis=[1475082879990], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475082879954]}
09-28 13:14:39.991   929  2978 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 13:14:39.991   929  2978 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-28 13:14:39.991   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 13:14:39.992   929  2978 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 13:14:39.995  3685  5992 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 13:14:39.995  3685  5992 I SystemUpdateService: now status is 0 (complete)
09-28 13:14:39.995  3685  5992 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 13:14:39.995  3685  5992 I SystemUpdateService: file has been verified
09-28 13:14:39.995  3685  5992 I SystemUpdateService: OTA package size = 21989297
,09-28 13:14:40.000  3685  5992 I SystemUpdateService: showing system update notification
,09-28 13:14:40.009  3685  3685 D SystemUpdateService: onDestroy
,09-28 13:14:40.091  5032  5997 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 13:14:42.629   929  2978 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 13:14:42.947  5645  6005 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-28 13:14:42.947  5645  5993 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-28 13:14:42.949  5645  6005 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 13:14:42.949  5645  5993 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-28 13:14:42.950  5645  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 13:14:42.950  5645  6005 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 13:14:42.952  5645  5993 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 13:14:42.952  5645  6005 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 13:14:42.955  5645  5993 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 13:14:42.955  5645  6005 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-28 13:14:42.957  5645  6007 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:42.957  5645  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:42.959  5645  6008 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:42.959  5645  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 13:14:42.960  5645  6009 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:42.960  5645  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:42.961  5645  6010 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:42.961  5645  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-28 13:14:42.962  5645  6010 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:42.962  5645  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-28 13:14:42.962  5645  6010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:14:42.962  5645  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-28 13:14:42.963  5645  6010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-28 13:14:42.963  5645  6010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 13:14:42.963  5645  6009 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:42.963  5645  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:42.963  5645  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:14:42.963  5645  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:14:42.963  5645  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 13:14:42.963  5645  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-28 13:14:42.963  5645  6010 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:14:42.963  5645  6008 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 158, thread name: IncomingSocketThread/Sender): Socket closed
09-28 13:14:42.963  5645  6007 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 157, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:42.963  5645  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:14:42.964  5645  6010 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-28 13:14:42.964  5645  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:14:42.964  5645  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:14:42.964  5645  6010 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-28 13:14:42.964  5645  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 13:14:42.964  5645  6008 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:42.964  5645  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 13:14:42.964  5645  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 13:14:42.964  5645  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:14:42.964  5645  6010 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-28 13:14:42.964  5645  6007 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:14:42.964  5645  6008 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 13:14:42.964  5645  6007 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-28 13:14:42.964  5645  6009 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 13:14:42.964  5645  6008 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 13:14:42.964  5645  6010 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:42.964  5645  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 13:14:42.964  5645  6007 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 13:14:42.964  5645  6009 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 13:14:42.964  5645  6008 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:42.964  5645  6008 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 13:14:42.964  5645  6009 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 13:14:42.964  5645  6007 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-28 13:14:42.965  5645  6009 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
,09-28 13:14:42.965  5645  6007 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-28 13:14:42.965  5645  6009 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:42.965  5645  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 13:14:42.965  5645  6007 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:42.965  5645  6007 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 13:14:45.944  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-28 13:14:45.947  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-28 13:14:45.955  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dea5f73 Bundle[{}]
,09-28 13:14:45.956  5645  5692 I io.jxcore.node.LifeCycleMonitor: start: OK
09-28 13:14:45.956  5645  5692 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-28 13:14:45.958  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-28 13:14:45.959  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-28 13:14:45.960  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-28 13:14:45.962  5645  5692 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-28 13:14:45.969  5645  5692 I System.out: Running OutgoingSocketThread
,09-28 13:14:45.972  5645  6011 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-28 13:14:45.972  5645  6011 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 13:14:47.848   929  2978 D ConnectivityService: handlePromptUnvalidated 102
,09-28 13:14:48.982  5645  6012 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-28 13:14:48.982  5645  6011 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-28 13:14:48.982  5645  6011 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-28 13:14:48.982  5645  6012 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 13:14:48.982  5645  6011 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 13:14:48.982  5645  6012 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 13:14:48.984  5645  6012 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 13:14:48.985  5645  6011 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 13:14:48.986  5645  6015 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:48.986  5645  6015 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:48.988  5645  6014 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:48.988  5645  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-28 13:14:48.989  5645  6011 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-28 13:14:48.990  5645  6012 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-28 13:14:48.992  5645  6016 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:48.992  5645  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:48.995  5645  6016 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:48.995  5645  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:48.995  5645  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:14:48.995  5645  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:14:48.995  5645  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 13:14:48.995  5645  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 13:14:48.995  5645  6017 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:48.995  5645  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 13:14:48.996  5645  6015 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: OutgoingSocketThread/Sender): Socket closed
,09-28 13:14:48.996  5645  6016 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:14:48.996  5645  6016 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 13:14:48.996  5645  6015 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:48.996  5645  6015 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 13:14:48.996  5645  6016 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-28 13:14:48.997  5645  6016 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 13:14:48.997  5645  6015 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 13:14:48.997  5645  6015 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 13:14:48.997  5645  6016 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:48.997  5645  6016 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 13:14:48.997  5645  6017 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:48.997  5645  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 13:14:48.997  5645  6015 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:48.997  5645  6015 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 13:14:48.997  5645  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:14:48.997  5645  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 13:14:48.997  5645  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 13:14:48.997  5645  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-28 13:14:48.997  5645  6017 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:14:48.998  5645  6017 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 13:14:48.998  5645  6017 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 13:14:48.998  5645  6017 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 13:14:48.998  5645  6017 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 13:14:48.998  5645  6017 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-28 13:14:48.998  5645  6014 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 170, thread name: IncomingSocketThread/Sender): Socket closed
09-28 13:14:48.998  5645  6014 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:48.998  5645  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 13:14:48.999  5645  6014 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 13:14:48.999  5645  6014 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 13:14:48.999  5645  6014 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 13:14:48.999  5645  6014 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-28 13:14:50.804   929  2976 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-28 13:14:51.984  5645  5692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-28 13:14:51.986  5645  5692 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-28 13:14:51.986  5645  5692 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-28 13:14:51.993  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 13:14:51.993  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@587bcb added. We now have 3 listener(s)
,09-28 13:14:51.995  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:51.996  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:51.996  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:51.996  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:51.996  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@566bfa8 added. We now have 4 listener(s)
09-28 13:14:51.997  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:14:51.998  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:14:52.003  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:52.010  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:14:52.013  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:14:52.014  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:14:52.014  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.014  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29bc266 added. We now have 4 listener(s)
,09-28 13:14:52.016  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 13:14:52.017  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:52.017  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.017  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.017  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27109a7 added. We now have 5 listener(s)
09-28 13:14:52.018  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.018  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:14:52.018  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:14:52.018  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:14:52.018  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 13:14:52.018  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.018  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:14:52.019  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.019  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.019  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@587bcb removed from the list
09-28 13:14:52.019  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:14:52.019  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@566bfa8 removed from the list
09-28 13:14:52.020  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.020  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 13:14:52.020  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:52.021  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.022  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.023  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.023  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.023  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.023  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@566bfa8 not in the list
09-28 13:14:52.023  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.023  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:52.025  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 13:14:52.026  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.026  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.026  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.026  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27109a7 removed from the list
09-28 13:14:52.026  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.026  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.026  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:52.026  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.026  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.026  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29bc266 removed from the list
09-28 13:14:52.027  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.027  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93c2e54 added. We now have 3 listener(s)
09-28 13:14:52.028  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:52.028  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 13:14:52.028  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.029  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.029  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db581fd added. We now have 4 listener(s)
09-28 13:14:52.029  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.030  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:14:52.033  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:52.037  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:14:52.038  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:52.039  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:14:52.039  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.039  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9a9943 added. We now have 4 listener(s)
09-28 13:14:52.040  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:52.040  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:52.040  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.041  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.041  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c57dbc0 added. We now have 5 listener(s)
09-28 13:14:52.041  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.041  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:14:52.041  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 13:14:52.041  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:52.041  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 13:14:52.041  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 13:14:52.041  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 13:14:52.044  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 13:14:52.044  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 13:14:52.044  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.047  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 13:14:52.048  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 13:14:52.048  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 13:14:52.050  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 13:14:52.050  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 13:14:52.050  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 13:14:52.050  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 13:14:52.050  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 13:14:52.051  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:14:52.054  5922  5932 D BtGatt.GattService: registerClient() - UUID=59387cd3-6adb-4f9f-97da-8b0bfd8f243a
09-28 13:14:52.055  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=59387cd3-6adb-4f9f-97da-8b0bfd8f243a, clientIf=5
,09-28 13:14:52.055  5645  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 13:14:52.056  5922  5960 D BtGatt.GattService: start scan with filters
,09-28 13:14:52.059  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 13:14:52.060  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 13:14:52.060  5922  5941 D BtGatt.ScanManager: handling starting scan
09-28 13:14:52.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:14:52.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 13:14:52.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 13:14:52.060  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 13:14:52.060  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 13:14:52.061  5922  5941 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bfde9c4
,09-28 13:14:52.062  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:14:52.062  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 13:14:52.062  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:14:52.064  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 13:14:52.067  5645  5692 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 13:14:52.068  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 13:14:52.068  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 13:14:52.068  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.068  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 13:14:52.068  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.068  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 13:14:52.068  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 13:14:52.068  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 13:14:52.068  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 13:14:52.068  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 13:14:52.068  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 13:14:52.068  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 13:14:52.068  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:14:52.069  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:14:52.069  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 13:14:52.070  5922  5960 D BtGatt.GattService: stopScan() - queue size =1
,09-28 13:14:52.071  5922  5959 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 13:14:52.071  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 13:14:52.071  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 13:14:52.071  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 13:14:52.071  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:14:52.071  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 13:14:52.072  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 13:14:52.072  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 13:14:52.072  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 13:14:52.073  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:14:52.073  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 13:14:52.073  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 13:14:52.073  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 13:14:52.073  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 13:14:52.073  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:14:52.074  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:14:52.074  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:14:52.074  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:14:52.075  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 13:14:52.075  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.076  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
09-28 13:14:52.076  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 13:14:52.077  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:14:52.077  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:14:52.077  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:14:52.077  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 13:14:52.077  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.077  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:14:52.077  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.077  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.077  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@93c2e54 removed from the list
09-28 13:14:52.077  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.077  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db581fd removed from the list
09-28 13:14:52.077  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:52.078  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.078  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.078  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:52.079  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 13:14:52.080  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.080  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.080  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db581fd not in the list
09-28 13:14:52.080  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.080  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.080  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.081  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.081  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.081  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c57dbc0 removed from the list
09-28 13:14:52.081  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.081  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:14:52.081  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.081  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.081  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.081  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f9a9943 removed from the list
09-28 13:14:52.082  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.082  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bef3ec added. We now have 3 listener(s)
09-28 13:14:52.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 13:14:52.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:52.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.084  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.084  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@827f3b5 added. We now have 4 listener(s)
09-28 13:14:52.084  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:14:52.085  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:14:52.088  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 13:14:52.088  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.088  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:52.092  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:14:52.093  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 13:14:52.093  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:14:52.094  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:14:52.094  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:14:52.094  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.094  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@763edbb added. We now have 4 listener(s)
09-28 13:14:52.095  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:52.095  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:52.095  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 13:14:52.095  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.095  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d62d8 added. We now have 5 listener(s)
09-28 13:14:52.095  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.096  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:14:52.096  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.096  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:14:52.096  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 13:14:52.096  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 13:14:52.096  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 13:14:52.096  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 13:14:52.098  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.099  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 13:14:52.099  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.099  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
09-28 13:14:52.099  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 13:14:52.099  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 13:14:52.102  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 13:14:52.103  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 13:14:52.103  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 13:14:52.104  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 13:14:52.104  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.104  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 13:14:52.105  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 13:14:52.105  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 13:14:52.105  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 13:14:52.105  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 13:14:52.106  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 13:14:52.106  5645  5692 D BluetoothAdapter: STATE_ON
,09-28 13:14:52.108  5922  5932 D BtGatt.GattService: registerClient() - UUID=35948ecf-a3f3-4504-8d6c-8b08a73d2c14
09-28 13:14:52.108  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=35948ecf-a3f3-4504-8d6c-8b08a73d2c14, clientIf=5
09-28 13:14:52.109  5645  5745 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 13:14:52.109  5922  5960 D BtGatt.GattService: start scan with filters
,09-28 13:14:52.110  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 13:14:52.110  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.111  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 13:14:52.111  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 13:14:52.111  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:14:52.111  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-28 13:14:52.111  5922  5941 D BtGatt.ScanManager: handling starting scan
09-28 13:14:52.111  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 13:14:52.111  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 13:14:52.111  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 13:14:52.114  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:14:52.114  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 13:14:52.114  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:14:52.116  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 13:14:52.116  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 13:14:52.116  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.116  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 13:14:52.118  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:14:52.118  5645  5692 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-28 13:14:52.118  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:14:52.118  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:14:52.119  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 13:14:52.119  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.119  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.119  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 13:14:52.119  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.119  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.119  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4bef3ec removed from the list
09-28 13:14:52.119  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.119  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@827f3b5 removed from the list
09-28 13:14:52.119  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:52.119  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:14:52.120  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.120  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-28 13:14:52.120  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.120  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 13:14:52.121  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 13:14:52.121  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.121  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
09-28 13:14:52.121  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 13:14:52.121  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.122  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.122  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.122  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@827f3b5 not in the list
09-28 13:14:52.122  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 13:14:52.122  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 13:14:52.122  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 13:14:52.122  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 13:14:52.122  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 13:14:52.123  5645  5692 D BluetoothAdapter: STATE_ON
,09-28 13:14:52.124  5922  5959 D BtGatt.GattService: stopScan() - queue size =1
,09-28 13:14:52.124  5922  5933 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 13:14:52.125  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 13:14:52.125  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 13:14:52.125  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-28 13:14:52.125  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:14:52.125  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 13:14:52.125  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 13:14:52.125  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 13:14:52.125  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 13:14:52.126  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:14:52.127  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 13:14:52.127  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-28 13:14:52.127  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 13:14:52.127  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-28 13:14:52.127  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:52.130  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 13:14:52.130  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.130  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.130  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.130  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:14:52.130  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19d62d8 removed from the list
09-28 13:14:52.130  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 13:14:52.130  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.130  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.130  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.130  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.130  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.130  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@763edbb removed from the list
09-28 13:14:52.131  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:14:52.131  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:14:52.131  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.131  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1d484 added. We now have 3 listener(s)
09-28 13:14:52.132  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:52.132  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 13:14:52.132  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.132  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.133  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfe46d added. We now have 4 listener(s)
09-28 13:14:52.133  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.134  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 13:14:52.134  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.134  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:14:52.136  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:52.140  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 13:14:52.140  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 13:14:52.140  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.140  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
,09-28 13:14:52.142  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:14:52.142  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:14:52.142  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.142  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c845933 added. We now have 4 listener(s)
09-28 13:14:52.143  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:52.143  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:52.143  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.144  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.144  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f9b4f0 added. We now have 5 listener(s)
09-28 13:14:52.144  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.144  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.144  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:14:52.144  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 13:14:52.144  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 13:14:52.144  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 13:14:52.144  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 13:14:52.145  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 13:14:52.145  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.145  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 13:14:52.146  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:14:52.147  5645  5692 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 13:14:52.147  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 13:14:52.151  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 13:14:52.151  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:14:52.151  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 13:14:52.152  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 13:14:52.152  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 13:14:52.155  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 13:14:52.155  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 13:14:52.155  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 13:14:52.155  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 13:14:52.155  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-28 13:14:52.155  5645  5692 D BluetoothAdapter: STATE_ON
09-28 13:14:52.157  5922  5933 D BtGatt.GattService: registerClient() - UUID=201ddcf9-3506-4912-9900-a4b476f8f431
,09-28 13:14:52.157  5922  5938 D BtGatt.GattService: onClientRegistered() - UUID=201ddcf9-3506-4912-9900-a4b476f8f431, clientIf=5
09-28 13:14:52.157  5645  5656 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 13:14:52.158  5922  5932 D BtGatt.GattService: start scan with filters
,09-28 13:14:52.159  5922  5941 D BtGatt.ScanManager: handling starting scan
,09-28 13:14:52.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 13:14:52.160  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 13:14:52.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:14:52.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 13:14:52.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 13:14:52.160  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 13:14:52.160  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 13:14:52.162  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 13:14:52.162  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 13:14:52.162  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 13:14:52.163  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 13:14:52.164  5922  5938 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 13:14:52.165  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.165  5922  5941 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 13:14:52.167  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 13:14:52.167  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:14:52.167  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:14:52.167  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.167  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.167  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 13:14:52.167  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.167  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.167  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6f1d484 removed from the list
09-28 13:14:52.167  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.167  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfe46d removed from the list
09-28 13:14:52.167  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:52.167  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 13:14:52.168  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.168  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-28 13:14:52.168  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.168  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:14:52.169  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.169  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.169  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 13:14:52.169  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5cfe46d not in the list
09-28 13:14:52.169  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 13:14:52.169  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 13:14:52.169  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 13:14:52.169  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 13:14:52.169  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 13:14:52.170  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 13:14:52.170  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.170  5922  5941 D BtGatt.ScanManager: Starting BLE batch scan
09-28 13:14:52.170  5922  5941 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 13:14:52.170  5645  5692 D BluetoothAdapter: STATE_ON
,09-28 13:14:52.170  5922  5933 D BtGatt.GattService: stopScan() - queue size =1
,09-28 13:14:52.171  5922  5960 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 13:14:52.171  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 13:14:52.171  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 13:14:52.171  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 13:14:52.171  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 13:14:52.171  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 13:14:52.171  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 13:14:52.171  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 13:14:52.172  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 13:14:52.172  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:14:52.172  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 13:14:52.172  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 13:14:52.172  5645  5692 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 13:14:52.172  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 13:14:52.173  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.174  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.174  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.174  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.174  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7f9b4f0 removed from the list
09-28 13:14:52.174  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:14:52.174  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.174  5645  5645 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 13:14:52.174  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.174  5645  5645 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 13:14:52.174  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:52.175  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.175  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.175  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c845933 removed from the list
09-28 13:14:52.175  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.175  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5d301c added. We now have 3 listener(s)
09-28 13:14:52.177  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:52.177  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:52.177  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.177  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:14:52.177  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fe3425 added. We now have 4 listener(s)
09-28 13:14:52.177  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.178  5922  5938 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-28 13:14:52.178  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.178  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 13:14:52.180  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:14:52.183  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 13:14:52.183  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:14:52.187  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:14:52.188  5922  5938 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 13:14:52.188  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.188  5922  5941 D BtGatt.ScanManager: stopping BLe Batch
,09-28 13:14:52.190  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:14:52.190  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:14:52.190  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 13:14:52.190  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7bbab added. We now have 4 listener(s)
09-28 13:14:52.191  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:14:52.191  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:14:52.191  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:14:52.191  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 13:14:52.191  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1b3208 added. We now have 5 listener(s)
09-28 13:14:52.191  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:14:52.192  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:14:52.192  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:14:52.192  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:14:52.192  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.192  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.192  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 13:14:52.192  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.192  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.192  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.192  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c5d301c removed from the list
09-28 13:14:52.192  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.192  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fe3425 removed from the list
09-28 13:14:52.193  5922  5938 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 13:14:52.193  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 13:14:52.193  5922  5941 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 13:14:52.194  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:14:52.194  5645  5692 D io.jxcore.node.ConnectivityMonitor: stop
09-28 13:14:52.194  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 13:14:52.195  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 13:14:52.195  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.195  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.195  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 13:14:52.196  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.196  5645  5692 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9fe3425 not in the list
09-28 13:14:52.196  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.196  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.196  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 13:14:52.196  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 13:14:52.197  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 13:14:52.197  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1b3208 removed from the list
09-28 13:14:52.197  5645  5692 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 13:14:52.197  5645  5692 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 13:14:52.197  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 13:14:52.197  5645  5692 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 13:14:52.197  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 13:14:52.197  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e7bbab removed from the list
09-28 13:14:52.197  5922  5938 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 13:14:52.197  5922  5938 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 13:14:52.197  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-28 13:14:52.198  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 13:14:52.198  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-28 13:14:52.198  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 13:14:52.198  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-28 13:14:52.198  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 13:14:52.576  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 13:14:52.631  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 13:14:52.675  5645  5645 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 13:14:54.359  5645  6018 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 13:14:54.359  5645  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:55.164  5645  6018 W !!      : call onHalfStreamCopied
,09-28 13:14:55.164  5645  6018 I testCopyDataAndClose: closing input stream
,09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 13:14:55.940  5645  6018 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-28 13:14:59.711  5645  6019 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:14:59.711  5645  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:15:00.923   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-28 13:15:00.923   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 13:15:01.711  5645  5692 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 193. Connection data: Peer properties: [null null].
09-28 13:15:01.711  5645  5692 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:15:01.711  5645  5692 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 193, name: My test thread name)
,09-28 13:15:01.739  5645  6019 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-28 13:15:01.739  5645  6019 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:15:01.739  5645  6019 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
,09-28 13:15:01.848  5645  6021 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 13:15:01.848  5645  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 13:15:03.535  5645  6021 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-28 13:15:07.260  5645  6022 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:15:07.260  5645  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 13:15:07.260  5645  6022 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 197, thread name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:15:07.260  5645  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:15:07.260  5645  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 13:15:07.260  5645  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:15:07.261  5645  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 13:15:07.261  5645  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 13:15:07.261  5645  6022 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 13:15:07.261  5645  6022 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 13:15:07.261  5645  6022 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 13:15:07.262  5645  6022 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:15:07.262  5645  6022 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-28 13:15:07.263  5645  5692 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 13:15:07.266  5645  6023 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:15:07.266  5645  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 13:15:07.267  5645  6023 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: My test thread name): Test exception.
09-28 13:15:07.267  5645  6023 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:15:07.267  5645  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-28 13:15:07.267  5645  6023 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-28 13:15:07.267  5645  6023 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-28 13:15:07.267  5645  6023 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-28 13:15:07.272  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-28 13:15:07.272  5645  5692 I jxcore-log: 
09-28 13:15:07.272  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Number of passed tests:  83'
09-28 13:15:07.272  5645  5692 I jxcore-log: 
09-28 13:15:07.272  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Number of failed tests:  1'
09-28 13:15:07.272  5645  5692 I jxcore-log: 
,09-28 13:15:07.273  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-28 13:15:07.273  5645  5692 I jxcore-log: 
09-28 13:15:07.273  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Total duration:  102879'
09-28 13:15:07.273  5645  5692 I jxcore-log: 
09-28 13:15:07.274  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Failures: 
09-28 13:15:07.274  5645  5692 I jxcore-log:  OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-28 13:15:07.274  5645  5692 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-28 13:15:07.274  5645  5692 I jxcore-log:      but: was ""
09-28 13:15:07.274  5645  5692 I jxcore-log: '
09-28 13:15:07.274  5645  5692 I jxcore-log: 
09-28 13:15:07.275  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-28 13:15:07.275  5645  5692 I jxcore-log: 
,09-28 13:15:07.276  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-28 13:15:07.276  5645  5692 I jxcore-log: 
,09-28 13:15:07.280  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.280  5645  5692 I jxcore-log: 
,09-28 13:15:07.281  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.281  5645  5692 I jxcore-log: 
09-28 13:15:07.281  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.281  5645  5692 I jxcore-log: 
09-28 13:15:07.282  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.282  5645  5692 I jxcore-log: 
09-28 13:15:07.282  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 13:15:07.282  5645  5692 I jxcore-log: 
09-28 13:15:07.283  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 13:15:07.283  5645  5692 I jxcore-log: 
09-28 13:15:07.283  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.283  5645  5692 I jxcore-log: 
09-28 13:15:07.283  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.283  5645  5692 I jxcore-log: 
09-28 13:15:07.283  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 13:15:07.283  5645  5692 I jxcore-log: 
,09-28 13:15:07.284  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 13:15:07.284  5645  5692 I jxcore-log: 
09-28 13:15:07.284  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 13:15:07.284  5645  5692 I jxcore-log: 
09-28 13:15:07.284  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.284  5645  5692 I jxcore-log: 
09-28 13:15:07.284  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.284  5645  5692 I jxcore-log: 
09-28 13:15:07.285  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.285  5645  5692 I jxcore-log: 
09-28 13:15:07.285  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.285  5645  5692 I jxcore-log: 
09-28 13:15:07.285  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.285  5645  5692 I jxcore-log: 
09-28 13:15:07.286  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.286  5645  5692 I jxcore-log: 
09-28 13:15:07.286  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.286  5645  5692 I jxcore-log: 
09-28 13:15:07.286  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.286  5645  5692 I jxcore-log: 
09-28 13:15:07.286  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.286  5645  5692 I jxcore-log: 
09-28 13:15:07.287  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.287  5645  5692 I jxcore-log: 
09-28 13:15:07.287  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.287  5645  5692 I jxcore-log: 
09-28 13:15:07.289  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.289  5645  5692 I jxcore-log: 
09-28 13:15:07.289  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.289  5645  5692 I jxcore-log: 
09-28 13:15:07.290  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.290  5645  5692 I jxcore-lo,g: 
09-28 13:15:07.290  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.290  5645  5692 I jxcore-log: 
09-28 13:15:07.290  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.290  5645  5692 I jxcore-log: 
09-28 13:15:07.290  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.290  5645  5692 I jxcore-log: 
09-28 13:15:07.291  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.291  5645  5692 I jxcore-log: 
09-28 13:15:07.291  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.291  5645  5692 I jxcore-log: 
09-28 13:15:07.291  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.291  5645  5692 I jxcore-log: 
09-28 13:15:07.291  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.291  5645  5692 I jxcore-log: 
09-28 13:15:07.292  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.292  5645  5692 I jxcore-log: 
09-28 13:15:07.292  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.292  5645  5692 I jxcore-log: 
09-28 13:15:07.292  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.292  5645  5692 I jxcore-log: 
,09-28 13:15:07.292  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.292  5645  5692 I jxcore-log: 
09-28 13:15:07.293  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.293  5645  5692 I jxcore-log: 
09-28 13:15:07.293  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.293  5645  5692 I jxcore-log: 
09-28 13:15:07.293  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 13:15:07.293  5645  5692 I jxcore-log: 
09-28 13:15:07.293  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.293  5645  5692 I jxcore-log: 
09-28 13:15:07.293  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 13:15:07.293  5645  5692 I jxcore-log: 
,09-28 13:15:07.294  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.294  5645  5692 I jxcore-log: 
09-28 13:15:07.294  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.294  5645  5692 I jxcore-log: 
09-28 13:15:07.294  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.294  5645  5692 I jxcore-log: 
09-28 13:15:07.294  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.294  5645  5692 I jxcore-log: 
09-28 13:15:07.295  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.295  5645  5692 I jxcore-log: 
,09-28 13:15:07.295  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:15:07.295  5645  5692 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-28 13:15:07.295  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.295  5645  5692 I jxcore-log: 
09-28 13:15:07.296  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.296  5645  5692 I jxcore-log: 
09-28 13:15:07.296  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 13:15:07.296  5645  5692 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-28 13:15:07.296  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:07.296  5645  5692 I jxcore-log: 
09-28 13:15:07.296  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 13:15:07.296  5645  5692 I jxcore-log: 
09-28 13:15:07.296  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 13:15:07.296  5645  5692 I jxcore-log: 
09-28 13:15:07.297  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 13:15:07.297  5645  5692 I jxcore-log: 
,09-28 13:15:07.302  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-28 13:15:07.302  5645  5692 I jxcore-log: 
09-28 13:15:07.302  5645  5645 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-28 13:15:07.303  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - WARN testUtils: 'myNameCallback not set!'
09-28 13:15:07.303  5645  5692 I jxcore-log: 
09-28 13:15:07.304  5645  5692 I jxcore-log: 2016-09-28 17:15:07 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-28 13:15:07.304  5645  5692 I jxcore-log: 
,09-28 13:15:09.311  5645  5692 I jxcore-log: 2016-09-28 17:15:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-28 13:15:09.311  5645  5692 I jxcore-log: 
,09-28 13:15:09.649  5645  5692 I jxcore-log: 2016-09-28 17:15:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-28 13:15:09.649  5645  5692 I jxcore-log: 
,09-28 13:15:09.663  5645  5692 I jxcore-log: 2016-09-28 17:15:09 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-28 13:15:09.663  5645  5692 I jxcore-log: 
,09-28 13:15:10.767  5645  5692 I jxcore-log: 2016-09-28 17:15:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-28 13:15:10.767  5645  5692 I jxcore-log: 
,09-28 13:15:10.920  5645  5692 I jxcore-log: 2016-09-28 17:15:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-28 13:15:10.920  5645  5692 I jxcore-log: 
,09-28 13:15:10.925  5645  5692 I jxcore-log: 2016-09-28 17:15:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-28 13:15:10.925  5645  5692 I jxcore-log: 
,09-28 13:15:10.929  5645  5692 I jxcore-log: 2016-09-28 17:15:10 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-28 13:15:10.929  5645  5692 I jxcore-log: 
,09-28 13:15:11.475  5645  5692 I jxcore-log: 2016-09-28 17:15:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-28 13:15:11.475  5645  5692 I jxcore-log: 
,09-28 13:15:11.527  5645  5692 I jxcore-log: 2016-09-28 17:15:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-28 13:15:11.527  5645  5692 I jxcore-log: 
,09-28 13:15:11.539  5645  5692 I jxcore-log: 2016-09-28 17:15:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-28 13:15:11.539  5645  5692 I jxcore-log: 
,09-28 13:15:11.544  5645  5692 I jxcore-log: 2016-09-28 17:15:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-28 13:15:11.544  5645  5692 I jxcore-log: 
,09-28 13:15:11.822  5645  5692 I jxcore-log: 2016-09-28 17:15:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-28 13:15:11.822  5645  5692 I jxcore-log: 
,09-28 13:15:11.946  5645  5692 I jxcore-log: 2016-09-28 17:15:11 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-28 13:15:11.946  5645  5692 I jxcore-log: 
,09-28 13:15:12.180  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-28 13:15:12.180  5645  5692 I jxcore-log: 
,09-28 13:15:12.190  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-28 13:15:12.190  5645  5692 I jxcore-log: 
,09-28 13:15:12.194  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-28 13:15:12.194  5645  5692 I jxcore-log: 
,09-28 13:15:12.329  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-28 13:15:12.329  5645  5692 I jxcore-log: 
,09-28 13:15:12.336  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-28 13:15:12.336  5645  5692 I jxcore-log: 
,09-28 13:15:12.364  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-28 13:15:12.364  5645  5692 I jxcore-log: 
,09-28 13:15:12.398  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-28 13:15:12.398  5645  5692 I jxcore-log: 
,09-28 13:15:12.404  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-28 13:15:12.404  5645  5692 I jxcore-log: 
,09-28 13:15:12.410  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-28 13:15:12.410  5645  5692 I jxcore-log: 
,09-28 13:15:12.423  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-28 13:15:12.423  5645  5692 I jxcore-log: 
,09-28 13:15:12.427  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-28 13:15:12.427  5645  5692 I jxcore-log: 
,09-28 13:15:12.432  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-28 13:15:12.432  5645  5692 I jxcore-log: 
,09-28 13:15:12.437  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-28 13:15:12.437  5645  5692 I jxcore-log: 
,09-28 13:15:12.449  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-28 13:15:12.449  5645  5692 I jxcore-log: 
,09-28 13:15:12.468  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-28 13:15:12.468  5645  5692 I jxcore-log: 
,09-28 13:15:12.476  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-28 13:15:12.476  5645  5692 I jxcore-log: 
,09-28 13:15:12.487  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-28 13:15:12.487  5645  5692 I jxcore-log: 
,09-28 13:15:12.496  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-28 13:15:12.496  5645  5692 I jxcore-log: 
,09-28 13:15:12.508  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-28 13:15:12.508  5645  5692 I jxcore-log: 
,09-28 13:15:12.518  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-28 13:15:12.518  5645  5692 I jxcore-log: 
,09-28 13:15:12.523  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-28 13:15:12.523  5645  5692 I jxcore-log: 
,09-28 13:15:12.543  5645  5692 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-28 13:15:12.545  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - INFO testUtils: 'BLE multiple advertisement supported'
09-28 13:15:12.545  5645  5692 I jxcore-log: 
,09-28 13:15:12.647  5645  5692 I jxcore-log: 2016-09-28 17:15:12 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 13:15:12.647  5645  5692 I jxcore-log: 
,09-28 13:15:13.198  5645  5692 I jxcore-log: TAP version 13
09-28 13:15:13.198  5645  5692 I jxcore-log: 
,09-28 13:15:13.240  5645  5692 I jxcore-log: # setup
09-28 13:15:13.240  5645  5692 I jxcore-log: 
,09-28 13:15:14.024  5645  5692 I jxcore-log: # calling createNativeListener directly rejects
09-28 13:15:14.024  5645  5692 I jxcore-log: 
,09-28 13:15:14.190  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:14.190  5645  5692 I jxcore-log: 
,09-28 13:15:14.196  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'listening 41804'
09-28 13:15:14.196  5645  5692 I jxcore-log: 
,09-28 13:15:14.203  5645  5692 I jxcore-log: ok 1 Should throw
09-28 13:15:14.203  5645  5692 I jxcore-log: 
,09-28 13:15:14.214  5645  5692 I jxcore-log: # teardown
09-28 13:15:14.214  5645  5692 I jxcore-log: 
,09-28 13:15:14.254  5645  5692 I jxcore-log: # setup
09-28 13:15:14.254  5645  5692 I jxcore-log: 
,09-28 13:15:14.326  5645  5692 I jxcore-log: # emits incomingConnectionState
09-28 13:15:14.326  5645  5692 I jxcore-log: 
,09-28 13:15:14.380  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:14.380  5645  5692 I jxcore-log: 
,09-28 13:15:14.385  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'listening 42885'
09-28 13:15:14.385  5645  5692 I jxcore-log: 
,09-28 13:15:14.397  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:14.397  5645  5692 I jxcore-log: 
,09-28 13:15:14.400  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:14.400  5645  5692 I jxcore-log: 
,09-28 13:15:14.412  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new mux'
09-28 13:15:14.412  5645  5692 I jxcore-log: 
,09-28 13:15:14.417  5645  5692 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-28 13:15:14.417  5645  5692 I jxcore-log: 
,09-28 13:15:14.435  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:14.435  5645  5692 I jxcore-log: 
,09-28 13:15:14.436  5645  5692 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-28 13:15:14.436  5645  5692 I jxcore-log: 
,09-28 13:15:14.444  5645  5692 I jxcore-log: # teardown
09-28 13:15:14.444  5645  5692 I jxcore-log: 
,09-28 13:15:14.473  5645  5692 I jxcore-log: # setup
09-28 13:15:14.473  5645  5692 I jxcore-log: 
,09-28 13:15:14.531  5645  5692 I jxcore-log: # emits routerPortConnectionFailed
09-28 13:15:14.531  5645  5692 I jxcore-log: 
,09-28 13:15:14.603  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:14.603  5645  5692 I jxcore-log: 
,09-28 13:15:14.607  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'listening 40741'
09-28 13:15:14.607  5645  5692 I jxcore-log: 
,09-28 13:15:14.616  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:14.616  5645  5692 I jxcore-log: 
,09-28 13:15:14.617  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:14.617  5645  5692 I jxcore-log: 
,09-28 13:15:14.621  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new mux'
09-28 13:15:14.621  5645  5692 I jxcore-log: 
,09-28 13:15:14.647  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:14.647  5645  5692 I jxcore-log: 
,09-28 13:15:14.650  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:14.650  5645  5692 I jxcore-log: 
,09-28 13:15:14.655  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: ' $c@net.js:837:7
09-28 13:15:14.655  5645  5692 I jxcore-log: $09@net.js:829:13
09-28 13:15:14.655  5645  5692 I jxcore-log: '
09-28 13:15:14.655  5645  5692 I jxcore-log: 
,09-28 13:15:14.656  5645  5692 I jxcore-log: ok 4 tried to connect to right port
09-28 13:15:14.656  5645  5692 I jxcore-log: 
09-28 13:15:14.656  5645  5692 I jxcore-log: ok 5 failed due to refused connection
09-28 13:15:14.656  5645  5692 I jxcore-log: 
09-28 13:15:14.657  5645  5692 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-28 13:15:14.657  5645  5692 I jxcore-log: 
,09-28 13:15:14.661  5645  5692 I jxcore-log: # teardown
09-28 13:15:14.661  5645  5692 I jxcore-log: 
,09-28 13:15:14.663  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:14.663  5645  5692 I jxcore-log: 
,09-28 13:15:14.702  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'mux close'
09-28 13:15:14.702  5645  5692 I jxcore-log: 
,09-28 13:15:14.706  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:14.706  5645  5692 I jxcore-log: 
,09-28 13:15:14.719  5645  5692 I jxcore-log: # setup
09-28 13:15:14.719  5645  5692 I jxcore-log: 
,09-28 13:15:14.771  5645  5692 I jxcore-log: # native server connections all up
09-28 13:15:14.771  5645  5692 I jxcore-log: 
,09-28 13:15:14.810  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:14.810  5645  5692 I jxcore-log: 
,09-28 13:15:14.814  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'listening 37184'
09-28 13:15:14.814  5645  5692 I jxcore-log: 
,09-28 13:15:14.823  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:14.823  5645  5692 I jxcore-log: 
,09-28 13:15:14.826  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:14.826  5645  5692 I jxcore-log: 
,09-28 13:15:14.830  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new mux'
09-28 13:15:14.830  5645  5692 I jxcore-log: 
,09-28 13:15:14.863  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:14.863  5645  5692 I jxcore-log: 
,09-28 13:15:14.867  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:14.867  5645  5692 I jxcore-log: 
,09-28 13:15:14.871  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:14.871  5645  5692 I jxcore-log: 
,09-28 13:15:14.874  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:14.874  5645  5692 I jxcore-log: 
,09-28 13:15:14.899  5645  5692 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-28 13:15:14.899  5645  5692 I jxcore-log: 
,09-28 13:15:14.900  5645  5692 I jxcore-log: ok 8 Send/recvd #1 should be same
09-28 13:15:14.900  5645  5692 I jxcore-log: 
09-28 13:15:14.903  5645  5692 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-28 13:15:14.903  5645  5692 I jxcore-log: 
09-28 13:15:14.903  5645  5692 I jxcore-log: ok 10 Send/recvd #2 should be same
09-28 13:15:14.903  5645  5692 I jxcore-log: 
09-28 13:15:14.906  5645  5692 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-28 13:15:14.906  5645  5692 I jxcore-log: 
,09-28 13:15:14.914  5645  5692 I jxcore-log: # teardown
09-28 13:15:14.914  5645  5692 I jxcore-log: 
,09-28 13:15:14.966  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:14.966  5645  5692 I jxcore-log: 
,09-28 13:15:14.968  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:14.968  5645  5692 I jxcore-log: 
09-28 13:15:14.970  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'mux close'
09-28 13:15:14.970  5645  5692 I jxcore-log: 
,09-28 13:15:14.976  5645  5692 I jxcore-log: 2016-09-28 17:15:14 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:14.976  5645  5692 I jxcore-log: 
,09-28 13:15:14.987  5645  5692 I jxcore-log: # setup
09-28 13:15:14.987  5645  5692 I jxcore-log: 
,09-28 13:15:15.033  5645  5692 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-28 13:15:15.033  5645  5692 I jxcore-log: 
,09-28 13:15:15.099  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:15.099  5645  5692 I jxcore-log: 
,09-28 13:15:15.104  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'listening 46399'
09-28 13:15:15.104  5645  5692 I jxcore-log: 
,09-28 13:15:15.111  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:15.111  5645  5692 I jxcore-log: 
,09-28 13:15:15.113  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:15.113  5645  5692 I jxcore-log: 
,09-28 13:15:15.117  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new mux'
09-28 13:15:15.117  5645  5692 I jxcore-log: 
,09-28 13:15:15.129  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:15.129  5645  5692 I jxcore-log: 
,09-28 13:15:15.132  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:15.132  5645  5692 I jxcore-log: 
,09-28 13:15:15.146  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:15.146  5645  5692 I jxcore-log: 
,09-28 13:15:15.160  5645  5692 I jxcore-log: ok 12 socket shouldn't close until after stream
09-28 13:15:15.160  5645  5692 I jxcore-log: 
,09-28 13:15:15.160  5645  5692 I jxcore-log: ok 13 incoming remains open
09-28 13:15:15.160  5645  5692 I jxcore-log: 
,09-28 13:15:15.169  5645  5692 I jxcore-log: # teardown
09-28 13:15:15.169  5645  5692 I jxcore-log: 
,09-28 13:15:15.207  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'mux close'
09-28 13:15:15.207  5645  5692 I jxcore-log: 
,09-28 13:15:15.213  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:15.213  5645  5692 I jxcore-log: 
,09-28 13:15:15.221  5645  5692 I jxcore-log: # setup
09-28 13:15:15.221  5645  5692 I jxcore-log: 
,09-28 13:15:15.286  5645  5692 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-28 13:15:15.286  5645  5692 I jxcore-log: 
,09-28 13:15:15.336  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:15.336  5645  5692 I jxcore-log: 
,09-28 13:15:15.340  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'listening 44475'
09-28 13:15:15.340  5645  5692 I jxcore-log: 
,09-28 13:15:15.347  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:15.347  5645  5692 I jxcore-log: 
,09-28 13:15:15.350  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:15.350  5645  5692 I jxcore-log: 
,09-28 13:15:15.352  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new mux'
09-28 13:15:15.352  5645  5692 I jxcore-log: 
,09-28 13:15:15.360  5645  5692 I jxcore-log: ok 14 we should not have gotten an error
09-28 13:15:15.360  5645  5692 I jxcore-log: 
,09-28 13:15:15.364  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:15.364  5645  5692 I jxcore-log: 
,09-28 13:15:15.367  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:15.367  5645  5692 I jxcore-log: 
,09-28 13:15:15.376  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:15.376  5645  5692 I jxcore-log: 
,09-28 13:15:15.378  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:15.378  5645  5692 I jxcore-log: 
,09-28 13:15:15.386  5645  5692 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-28 13:15:15.386  5645  5692 I jxcore-log: 
,09-28 13:15:15.386  5645  5692 I jxcore-log: ok 16 incoming is cleaned up
09-28 13:15:15.386  5645  5692 I jxcore-log: 
,09-28 13:15:15.394  5645  5692 I jxcore-log: # teardown
09-28 13:15:15.394  5645  5692 I jxcore-log: 
,09-28 13:15:15.472  5645  5692 I jxcore-log: # setup
09-28 13:15:15.472  5645  5692 I jxcore-log: 
,09-28 13:15:15.540  5645  5692 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-28 13:15:15.540  5645  5692 I jxcore-log: 
,09-28 13:15:15.582  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:15.582  5645  5692 I jxcore-log: 
,09-28 13:15:15.587  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'listening 39150'
09-28 13:15:15.587  5645  5692 I jxcore-log: 
,09-28 13:15:15.597  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:15.597  5645  5692 I jxcore-log: 
,09-28 13:15:15.599  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:15.599  5645  5692 I jxcore-log: 
,09-28 13:15:15.603  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new mux'
09-28 13:15:15.603  5645  5692 I jxcore-log: 
,09-28 13:15:15.620  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:15.620  5645  5692 I jxcore-log: 
,09-28 13:15:15.623  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:15.623  5645  5692 I jxcore-log: 
,09-28 13:15:15.639  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:15.639  5645  5692 I jxcore-log: 
,09-28 13:15:15.648  5645  5692 I jxcore-log: ok 17 stream was closed
09-28 13:15:15.648  5645  5692 I jxcore-log: 
,09-28 13:15:15.649  5645  5692 I jxcore-log: ok 18 incoming should survive
09-28 13:15:15.649  5645  5692 I jxcore-log: 
09-28 13:15:15.649  5645  5692 I jxcore-log: ok 19 mux should have no streams
09-28 13:15:15.649  5645  5692 I jxcore-log: 
,09-28 13:15:15.655  5645  5692 I jxcore-log: # teardown
09-28 13:15:15.655  5645  5692 I jxcore-log: 
,09-28 13:15:15.708  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'mux close'
09-28 13:15:15.708  5645  5692 I jxcore-log: 
,09-28 13:15:15.724  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:15.724  5645  5692 I jxcore-log: 
,09-28 13:15:15.735  5645  5692 I jxcore-log: # setup
09-28 13:15:15.735  5645  5692 I jxcore-log: 
,09-28 13:15:15.801  5645  5692 I jxcore-log: # native server - closing the whole server cleans everything up
09-28 13:15:15.801  5645  5692 I jxcore-log: 
,09-28 13:15:15.876  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:15.876  5645  5692 I jxcore-log: 
,09-28 13:15:15.887  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'listening 45550'
09-28 13:15:15.887  5645  5692 I jxcore-log: 
,09-28 13:15:15.895  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:15.895  5645  5692 I jxcore-log: 
,09-28 13:15:15.897  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:15.897  5645  5692 I jxcore-log: 
09-28 13:15:15.898  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new mux'
09-28 13:15:15.898  5645  5692 I jxcore-log: 
,09-28 13:15:15.911  5645  5692 I jxcore-log: ok 20 we should not have gotten an error
09-28 13:15:15.911  5645  5692 I jxcore-log: 
,09-28 13:15:15.916  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:15.916  5645  5692 I jxcore-log: 
,09-28 13:15:15.919  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:15.919  5645  5692 I jxcore-log: 
,09-28 13:15:15.924   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:15.928  5645  5692 I jxcore-log: ok 21 Buffers are identical
09-28 13:15:15.928  5645  5692 I jxcore-log: 
,09-28 13:15:15.929  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:15.929  5645  5692 I jxcore-log: 
09-28 13:15:15.932  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'mux close'
09-28 13:15:15.932  5645  5692 I jxcore-log: 
09-28 13:15:15.934  5645  5692 I jxcore-log: ok 22 native server is nulled out
09-28 13:15:15.934  5645  5692 I jxcore-log: 
,09-28 13:15:15.934  5645  5692 I jxcore-log: ok 23 native server should be closed
09-28 13:15:15.934  5645  5692 I jxcore-log: 
09-28 13:15:15.935  5645  5692 I jxcore-log: ok 24 incoming has been removed
09-28 13:15:15.935  5645  5692 I jxcore-log: 
09-28 13:15:15.935  5645  5692 I jxcore-log: ok 25 Incoming should be done
09-28 13:15:15.935  5645  5692 I jxcore-log: 
09-28 13:15:15.936  5645  5692 I jxcore-log: ok 26 The mux object should be closed
09-28 13:15:15.936  5645  5692 I jxcore-log: 
09-28 13:15:15.936  5645  5692 I jxcore-log: ok 27 The mux stream should be closed
09-28 13:15:15.936  5645  5692 I jxcore-log: 
,09-28 13:15:15.937  5645  5692 I jxcore-log: 2016-09-28 17:15:15 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:15.937  5645  5692 I jxcore-log: 
,09-28 13:15:15.950  5645  5692 I jxcore-log: # teardown
09-28 13:15:15.950  5645  5692 I jxcore-log: 
,09-28 13:15:15.986  5645  5692 I jxcore-log: # setup
09-28 13:15:15.986  5645  5692 I jxcore-log: 
,09-28 13:15:16.030  5645  5692 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-28 13:15:16.030  5645  5692 I jxcore-log: 
,09-28 13:15:16.106  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:16.106  5645  5692 I jxcore-log: 
,09-28 13:15:16.112  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'listening 49065'
09-28 13:15:16.112  5645  5692 I jxcore-log: 
,09-28 13:15:16.143  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.143  5645  5692 I jxcore-log: 
,09-28 13:15:16.144  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.144  5645  5692 I jxcore-log: 
,09-28 13:15:16.145  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.145  5645  5692 I jxcore-log: 
,09-28 13:15:16.150  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.150  5645  5692 I jxcore-log: 
,09-28 13:15:16.150  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.150  5645  5692 I jxcore-log: 
,09-28 13:15:16.151  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.151  5645  5692 I jxcore-log: 
,09-28 13:15:16.153  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.153  5645  5692 I jxcore-log: 
09-28 13:15:16.154  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.154  5645  5692 I jxcore-log: 
09-28 13:15:16.155  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.155  5645  5692 I jxcore-log: 
09-28 13:15:16.158  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.158  5645  5692 I jxcore-log: 
,09-28 13:15:16.158  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.158  5645  5692 I jxcore-log: 
09-28 13:15:16.159  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.159  5645  5692 I jxcore-log: 
09-28 13:15:16.162  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.162  5645  5692 I jxcore-log: 
09-28 13:15:16.163  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.163  5645  5692 I jxcore-log: 
,09-28 13:15:16.165  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.165  5645  5692 I jxcore-log: 
,09-28 13:15:16.175  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.175  5645  5692 I jxcore-log: 
,09-28 13:15:16.175  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.175  5645  5692 I jxcore-log: 
,09-28 13:15:16.177  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.177  5645  5692 I jxcore-log: 
,09-28 13:15:16.179  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.179  5645  5692 I jxcore-log: 
,09-28 13:15:16.180  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.180  5645  5692 I jxcore-log: 
,09-28 13:15:16.181  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.181  5645  5692 I jxcore-log: 
,09-28 13:15:16.183  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.183  5645  5692 I jxcore-log: 
,09-28 13:15:16.184  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.184  5645  5692 I jxcore-log: 
,09-28 13:15:16.185  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.185  5645  5692 I jxcore-log: 
,09-28 13:15:16.186  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.186  5645  5692 I jxcore-log: 
,09-28 13:15:16.187  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.187  5645  5692 I jxcore-log: 
,09-28 13:15:16.187  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.187  5645  5692 I jxcore-log: 
,09-28 13:15:16.188  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:16.188  5645  5692 I jxcore-log: 
,09-28 13:15:16.189  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:16.189  5645  5692 I jxcore-log: 
,09-28 13:15:16.189  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new mux'
09-28 13:15:16.189  5645  5692 I jxcore-log: 
,09-28 13:15:16.243  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.243  5645  5692 I jxcore-log: 
,09-28 13:15:16.244  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.244  5645  5692 I jxcore-log: 
,09-28 13:15:16.246  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.246  5645  5692 I jxcore-log: 
,09-28 13:15:16.247  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.247  5645  5692 I jxcore-log: 
09-28 13:15:16.247  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.247  5645  5692 I jxcore-log: 
,09-28 13:15:16.248  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.248  5645  5692 I jxcore-log: 
,09-28 13:15:16.249  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.249  5645  5692 I jxcore-log: 
09-28 13:15:16.250  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.250  5645  5692 I jxcore-log: 
,09-28 13:15:16.252  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.252  5645  5692 I jxcore-log: 
,09-28 13:15:16.253  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.253  5645  5692 I jxcore-log: 
,09-28 13:15:16.254  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.254  5645  5692 I jxcore-log: 
,09-28 13:15:16.255  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.255  5645  5692 I jxcore-log: 
09-28 13:15:16.255  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.255  5645  5692 I jxcore-log: 
,09-28 13:15:16.256  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.256  5645  5692 I jxcore-log: 
09-28 13:15:16.257  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.257  5645  5692 I jxcore-log: 
,09-28 13:15:16.258  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.258  5645  5692 I jxcore-log: 
09-28 13:15:16.259  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.259  5645  5692 I jxcore-log: 
,09-28 13:15:16.260  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.260  5645  5692 I jxcore-log: 
,09-28 13:15:16.261  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.261  5645  5692 I jxcore-log: 
09-28 13:15:16.261  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.261  5645  5692 I jxcore-log: 
,09-28 13:15:16.262  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.262  5645  5692 I jxcore-log: 
09-28 13:15:16.263  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.263  5645  5692 I jxcore-log: 
,09-28 13:15:16.264  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.264  5645  5692 I jxcore-log: 
09-28 13:15:16.264  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.264  5645  5692 I jxcore-log: 
,09-28 13:15:16.266  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.266  5645  5692 I jxcore-log: 
,09-28 13:15:16.267  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.267  5645  5692 I jxcore-log: 
09-28 13:15:16.267  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.267  5645  5692 I jxcore-log: 
,09-28 13:15:16.268  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.268  5645  5692 I jxcore-log: 
09-28 13:15:16.269  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.269  5645  5692 I jxcore-log: 
,09-28 13:15:16.270  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.270  5645  5692 I jxcore-log: 
09-28 13:15:16.270  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.270  5645  5692 I jxcore-log: 
,09-28 13:15:16.271  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.271  5645  5692 I jxcore-log: 
,09-28 13:15:16.272  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.272  5645  5692 I jxcore-log: 
09-28 13:15:16.273  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.273  5645  5692 I jxcore-log: 
,09-28 13:15:16.274  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.274  5645  5692 I jxcore-log: 
,09-28 13:15:16.274  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.274  5645  5692 I jxcore-log: 
09-28 13:15:16.275  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.275  5645  5692 I jxcore-log: 
,09-28 13:15:16.276  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.276  5645  5692 I jxcore-log: 
09-28 13:15:16.276  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.276  5645  5692 I jxcore-log: 
09-28 13:15:16.277  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.277  5645  5692 I jxcore-log: 
,09-28 13:15:16.278  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.278  5645  5692 I jxcore-log: 
,09-28 13:15:16.279  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.279  5645  5692 I jxcore-log: 
09-28 13:15:16.280  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.280  5645  5692 I jxcore-log: 
09-28 13:15:16.281  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.281  5645  5692 I jxcore-log: 
,09-28 13:15:16.281  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.281  5645  5692 I jxcore-log: 
09-28 13:15:16.282  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.282  5645  5692 I jxcore-log: 
,09-28 13:15:16.283  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.283  5645  5692 I jxcore-log: 
09-28 13:15:16.283  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.283  5645  5692 I jxcore-log: 
,09-28 13:15:16.290  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.290  5645  5692 I jxcore-log: 
,09-28 13:15:16.291  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.291  5645  5692 I jxcore-log: 
,09-28 13:15:16.292  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.292  5645  5692 I jxcore-log: 
09-28 13:15:16.293  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.293  5645  5692 I jxcore-log: 
,09-28 13:15:16.293  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.293  5645  5692 I jxcore-log: 
09-28 13:15:16.294  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.294  5645  5692 I jxcore-log: 
,09-28 13:15:16.295  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.295  5645  5692 I jxcore-log: 
09-28 13:15:16.295  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.295  5645  5692 I jxcore-log: 
,09-28 13:15:16.296  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.296  5645  5692 I jxcore-log: 
,09-28 13:15:16.297  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.297  5645  5692 I jxcore-log: 
09-28 13:15:16.298  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.298  5645  5692 I jxcore-log: 
,09-28 13:15:16.298  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.298  5645  5692 I jxcore-log: 
09-28 13:15:16.299  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.299  5645  5692 I jxcore-log: 
,09-28 13:15:16.300  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.300  5645  5692 I jxcore-log: 
09-28 13:15:16.300  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.300  5645  5692 I jxcore-log: 
,09-28 13:15:16.301  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.301  5645  5692 I jxcore-log: 
09-28 13:15:16.302  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.302  5645  5692 I jxcore-log: 
09-28 13:15:16.303  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.303  5645  5692 I jxcore-log: 
,09-28 13:15:16.303  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.303  5645  5692 I jxcore-log: 
09-28 13:15:16.304  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.304  5645  5692 I jxcore-log: 
,09-28 13:15:16.304  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.304  5645  5692 I jxcore-log: 
09-28 13:15:16.305  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.305  5645  5692 I jxcore-log: 
,09-28 13:15:16.306  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.306  5645  5692 I jxcore-log: 
,09-28 13:15:16.306  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.306  5645  5692 I jxcore-log: 
,09-28 13:15:16.307  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.307  5645  5692 I jxcore-log: 
09-28 13:15:16.308  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.308  5645  5692 I jxcore-log: 
,09-28 13:15:16.309  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.309  5645  5692 I jxcore-log: 
09-28 13:15:16.309  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.309  5645  5692 I jxcore-log: 
09-28 13:15:16.310  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.310  5645  5692 I jxcore-log: 
,09-28 13:15:16.310  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.310  5645  5692 I jxcore-log: 
09-28 13:15:16.311  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:16.311  5645  5692 I jxcore-log: 
,09-28 13:15:16.312  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:16.312  5645  5692 I jxcore-log: 
,09-28 13:15:16.356  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.356  5645  5692 I jxcore-log: 
,09-28 13:15:16.357  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.357  5645  5692 I jxcore-log: 
,09-28 13:15:16.358  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.358  5645  5692 I jxcore-log: 
,09-28 13:15:16.359  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.359  5645  5692 I jxcore-log: 
09-28 13:15:16.360  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.360  5645  5692 I jxcore-log: 
,09-28 13:15:16.360  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.360  5645  5692 I jxcore-log: 
,09-28 13:15:16.361  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.361  5645  5692 I jxcore-log: 
09-28 13:15:16.361  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.361  5645  5692 I jxcore-log: 
09-28 13:15:16.362  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.362  5645  5692 I jxcore-log: 
,09-28 13:15:16.362  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.362  5645  5692 I jxcore-log: 
09-28 13:15:16.363  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.363  5645  5692 I jxcore-log: 
,09-28 13:15:16.363  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.363  5645  5692 I jxcore-log: 
09-28 13:15:16.364  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.364  5645  5692 I jxcore-log: 
,09-28 13:15:16.364  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.364  5645  5692 I jxcore-log: 
09-28 13:15:16.365  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.365  5645  5692 I jxcore-log: 
,09-28 13:15:16.365  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.365  5645  5692 I jxcore-log: 
,09-28 13:15:16.366  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.366  5645  5692 I jxcore-log: 
09-28 13:15:16.366  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.366  5645  5692 I jxcore-log: 
09-28 13:15:16.367  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.367  5645  5692 I jxcore-log: 
09-28 13:15:16.367  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.367  5645  5692 I jxcore-log: 
09-28 13:15:16.368  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.368  5645  5692 I jxcore-log: 
,09-28 13:15:16.368  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.368  5645  5692 I jxcore-log: 
09-28 13:15:16.368  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.368  5645  5692 I jxcore-log: 
,09-28 13:15:16.369  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.369  5645  5692 I jxcore-log: 
09-28 13:15:16.369  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.369  5645  5692 I jxcore-log: 
,09-28 13:15:16.370  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.370  5645  5692 I jxcore-log: 
09-28 13:15:16.370  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.370  5645  5692 I jxcore-log: 
,09-28 13:15:16.371  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.371  5645  5692 I jxcore-log: 
09-28 13:15:16.371  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.371  5645  5692 I jxcore-log: 
,09-28 13:15:16.372  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.372  5645  5692 I jxcore-log: 
09-28 13:15:16.372  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.372  5645  5692 I jxcore-log: 
,09-28 13:15:16.373  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.373  5645  5692 I jxcore-log: 
09-28 13:15:16.373  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.373  5645  5692 I jxcore-log: 
09-28 13:15:16.374  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.374  5645  5692 I jxcore-log: 
,09-28 13:15:16.374  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.374  5645  5692 I jxcore-log: 
09-28 13:15:16.374  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.374  5645  5692 I jxcore-log: 
,09-28 13:15:16.375  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.375  5645  5692 I jxcore-log: 
09-28 13:15:16.375  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.375  5645  5692 I jxcore-log: 
,09-28 13:15:16.376  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.376  5645  5692 I jxcore-log: 
09-28 13:15:16.376  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.376  5645  5692 I jxcore-log: 
09-28 13:15:16.376  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.376  5645  5692 I jxcore-log: 
,09-28 13:15:16.377  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.377  5645  5692 I jxcore-log: 
09-28 13:15:16.377  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.377  5645  5692 I jxcore-log: 
09-28 13:15:16.378  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.378  5645  5692 I jxcore-log: 
09-28 13:15:16.379  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.379  5645  5692 I jxcore-log: 
,09-28 13:15:16.380  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.380  5645  5692 I jxcore-log: 
,09-28 13:15:16.382  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.382  5645  5692 I jxcore-log: 
,09-28 13:15:16.383  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.383  5645  5692 I jxcore-log: 
09-28 13:15:16.383  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:16.383  5645  5692 I jxcore-log: 
09-28 13:15:16.384  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'mux close'
09-28 13:15:16.384  5645  5692 I jxcore-log: 
,09-28 13:15:16.386  5645  5692 I jxcore-log: ok 28 native server is nulled out
09-28 13:15:16.386  5645  5692 I jxcore-log: 
,09-28 13:15:16.386  5645  5692 I jxcore-log: ok 29 native server should be closed
09-28 13:15:16.386  5645  5692 I jxcore-log: 
09-28 13:15:16.386  5645  5692 I jxcore-log: ok 30 incoming has been removed
09-28 13:15:16.386  5645  5692 I jxcore-log: 
09-28 13:15:16.387  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.387  5645  5692 I jxcore-log: 
,09-28 13:15:16.388  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.388  5645  5692 I jxcore-log: 
09-28 13:15:16.388  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.388  5645  5692 I jxcore-log: 
09-28 13:15:16.388  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.388  5645  5692 I jxcore-log: 
09-28 13:15:16.389  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.389  5645  5692 I jxcore-log: 
,09-28 13:15:16.389  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.389  5645  5692 I jxcore-log: 
09-28 13:15:16.389  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.389  5645  5692 I jxcore-log: 
09-28 13:15:16.389  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.389  5645  5692 I jxcore-log: 
,09-28 13:15:16.389  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.389  5645  5692 I jxcore-log: 
09-28 13:15:16.390  5645  5692 I jxcore-log: 2016-09-28 17:15:16 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:16.390  5645  5692 I jxcore-log: 
,09-28 13:15:16.461  5645  5692 I jxcore-log: # teardown
09-28 13:15:16.461  5645  5692 I jxcore-log: 
,09-28 13:15:16.532  5645  5692 I jxcore-log: # setup
09-28 13:15:16.532  5645  5692 I jxcore-log: 
,09-28 13:15:16.925   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:17.926   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:18.294  5645  5692 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-28 13:15:18.294  5645  5692 I jxcore-log: 
,09-28 13:15:18.334  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:18.334  5645  5692 I jxcore-log: 
,09-28 13:15:18.339  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'listening 45924'
09-28 13:15:18.339  5645  5692 I jxcore-log: 
,09-28 13:15:18.348  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:18.348  5645  5692 I jxcore-log: 
,09-28 13:15:18.350  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:18.350  5645  5692 I jxcore-log: 
,09-28 13:15:18.353  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new mux'
09-28 13:15:18.353  5645  5692 I jxcore-log: 
,09-28 13:15:18.364  5645  5692 I jxcore-log: ok 31 we should not have gotten an error
09-28 13:15:18.364  5645  5692 I jxcore-log: 
,09-28 13:15:18.368  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:18.368  5645  5692 I jxcore-log: 
,09-28 13:15:18.373  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:18.373  5645  5692 I jxcore-log: 
,09-28 13:15:18.380  5645  5692 I jxcore-log: ok 32 Buffers are identical
09-28 13:15:18.380  5645  5692 I jxcore-log: 
,09-28 13:15:18.382  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:18.382  5645  5692 I jxcore-log: 
,09-28 13:15:18.383  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'mux close'
09-28 13:15:18.383  5645  5692 I jxcore-log: 
,09-28 13:15:18.395  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:18.395  5645  5692 I jxcore-log: 
,09-28 13:15:18.396  5645  5692 I jxcore-log: ok 33 server should be fine
09-28 13:15:18.396  5645  5692 I jxcore-log: 
09-28 13:15:18.396  5645  5692 I jxcore-log: ok 34 server should be open
09-28 13:15:18.396  5645  5692 I jxcore-log: 
09-28 13:15:18.396  5645  5692 I jxcore-log: ok 35 incoming has been removed
09-28 13:15:18.396  5645  5692 I jxcore-log: 
09-28 13:15:18.397  5645  5692 I jxcore-log: ok 36 The mux object should be closed
09-28 13:15:18.397  5645  5692 I jxcore-log: 
09-28 13:15:18.397  5645  5692 I jxcore-log: ok 37 The mux stream should be closed
09-28 13:15:18.397  5645  5692 I jxcore-log: 
,09-28 13:15:18.403  5645  5692 I jxcore-log: # teardown
09-28 13:15:18.403  5645  5692 I jxcore-log: 
,09-28 13:15:18.450  5645  5692 I jxcore-log: # setup
09-28 13:15:18.450  5645  5692 I jxcore-log: 
,09-28 13:15:18.490  5645  5692 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-28 13:15:18.490  5645  5692 I jxcore-log: 
,09-28 13:15:18.529  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'creating native server'
09-28 13:15:18.529  5645  5692 I jxcore-log: 
,09-28 13:15:18.532  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'listening 39970'
09-28 13:15:18.532  5645  5692 I jxcore-log: 
,09-28 13:15:18.538  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new incoming socket'
09-28 13:15:18.538  5645  5692 I jxcore-log: 
,09-28 13:15:18.539  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'creating incoming mux'
09-28 13:15:18.539  5645  5692 I jxcore-log: 
,09-28 13:15:18.540  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new mux'
09-28 13:15:18.540  5645  5692 I jxcore-log: 
,09-28 13:15:18.546  5645  5692 I jxcore-log: ok 38 we should not have gotten an error
09-28 13:15:18.546  5645  5692 I jxcore-log: 
,09-28 13:15:18.549  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new stream: '
09-28 13:15:18.549  5645  5692 I jxcore-log: 
,09-28 13:15:18.552  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'new outgoing socket'
09-28 13:15:18.552  5645  5692 I jxcore-log: 
,09-28 13:15:18.559  5645  5692 I jxcore-log: ok 39 Buffers are identical
09-28 13:15:18.559  5645  5692 I jxcore-log: 
,09-28 13:15:18.563  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'incoming socket timeout'
09-28 13:15:18.563  5645  5692 I jxcore-log: 
,09-28 13:15:18.564  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'stream close:'
09-28 13:15:18.564  5645  5692 I jxcore-log: 
09-28 13:15:18.566  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'mux close'
09-28 13:15:18.566  5645  5692 I jxcore-log: 
,09-28 13:15:18.571  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG createNativeListener: 'incoming socket close'
09-28 13:15:18.571  5645  5692 I jxcore-log: 
09-28 13:15:18.572  5645  5692 I jxcore-log: ok 40 server should be fine
09-28 13:15:18.572  5645  5692 I jxcore-log: 
,09-28 13:15:18.572  5645  5692 I jxcore-log: ok 41 server should be open
09-28 13:15:18.572  5645  5692 I jxcore-log: 
09-28 13:15:18.572  5645  5692 I jxcore-log: ok 42 incoming has been removed
09-28 13:15:18.572  5645  5692 I jxcore-log: 
09-28 13:15:18.572  5645  5692 I jxcore-log: ok 43 The mux object should be closed
09-28 13:15:18.572  5645  5692 I jxcore-log: 
09-28 13:15:18.573  5645  5692 I jxcore-log: ok 44 The mux stream should be closed
09-28 13:15:18.573  5645  5692 I jxcore-log: 
,09-28 13:15:18.579  5645  5692 I jxcore-log: # teardown
09-28 13:15:18.579  5645  5692 I jxcore-log: 
,09-28 13:15:18.643  5645  5692 I jxcore-log: # setup
09-28 13:15:18.643  5645  5692 I jxcore-log: 
,09-28 13:15:18.674  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-28 13:15:18.674  5645  5692 I jxcore-log: 
,09-28 13:15:18.866  5645  5692 I jxcore-log: 2016-09-28 17:15:18 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-28 13:15:18.866  5645  5692 I jxcore-log: 
,09-28 13:15:18.868  5645  5692 I jxcore-log: ok 45 Got right error
09-28 13:15:18.868  5645  5692 I jxcore-log: 
,09-28 13:15:18.873  5645  5692 I jxcore-log: # teardown
09-28 13:15:18.873  5645  5692 I jxcore-log: 
,09-28 13:15:18.923  5645  5692 I jxcore-log: # setup
09-28 13:15:18.923  5645  5692 I jxcore-log: 
,09-28 13:15:18.927   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:18.979  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-28 13:15:18.979  5645  5692 I jxcore-log: 
,09-28 13:15:19.076  5645  5692 I jxcore-log: 2016-09-28 17:15:19 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-28 13:15:19.076  5645  5692 I jxcore-log: 
,09-28 13:15:19.078  5645  5692 I jxcore-log: ok 46 Got socket hang up
09-28 13:15:19.078  5645  5692 I jxcore-log: 
,09-28 13:15:19.082  5645  5692 I jxcore-log: # teardown
09-28 13:15:19.082  5645  5692 I jxcore-log: 
,09-28 13:15:19.110  5645  5692 I jxcore-log: # setup
09-28 13:15:19.110  5645  5692 I jxcore-log: 
,09-28 13:15:19.192  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-28 13:15:19.192  5645  5692 I jxcore-log: 
,09-28 13:15:19.340  5645  5692 I jxcore-log: 2016-09-28 17:15:19 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-28 13:15:19.340  5645  5692 I jxcore-log: 
,09-28 13:15:19.340  5645  5692 I jxcore-log: ok 47 Got 500 as expected
09-28 13:15:19.340  5645  5692 I jxcore-log: 
,09-28 13:15:19.344  5645  5692 I jxcore-log: # teardown
09-28 13:15:19.344  5645  5692 I jxcore-log: 
,09-28 13:15:19.375  5645  5692 I jxcore-log: # setup
09-28 13:15:19.375  5645  5692 I jxcore-log: 
,09-28 13:15:19.415  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-28 13:15:19.415  5645  5692 I jxcore-log: 
,09-28 13:15:19.825   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 13:15:19.928   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:20.928   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 13:15:20.976  5645  5692 I jxcore-log: ok 48 should be equal
09-28 13:15:20.976  5645  5692 I jxcore-log: 
,09-28 13:15:20.977  5645  5692 I jxcore-log: ok 49 revs are equal
09-28 13:15:20.977  5645  5692 I jxcore-log: 
,09-28 13:15:20.984  5645  5692 I jxcore-log: # teardown
09-28 13:15:20.984  5645  5692 I jxcore-log: 
,09-28 13:15:21.027  5645  5692 I jxcore-log: # setup
09-28 13:15:21.027  5645  5692 I jxcore-log: 
,09-28 13:15:21.781  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-28 13:15:21.781  5645  5692 I jxcore-log: 
,09-28 13:15:22.411  5645  5692 I jxcore-log: ok 50 should be equal
09-28 13:15:22.411  5645  5692 I jxcore-log: 
,09-28 13:15:22.411  5645  5692 I jxcore-log: ok 51 revs are equal
09-28 13:15:22.411  5645  5692 I jxcore-log: 
,09-28 13:15:22.416  5645  5692 I jxcore-log: # teardown
09-28 13:15:22.416  5645  5692 I jxcore-log: 
,09-28 13:15:22.448  5645  5692 I jxcore-log: # setup
09-28 13:15:22.448  5645  5692 I jxcore-log: 
,09-28 13:15:22.514  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-28 13:15:22.514  5645  5692 I jxcore-log: 
,09-28 13:15:23.036  5645  5692 I jxcore-log: ok 52 should be equal
09-28 13:15:23.036  5645  5692 I jxcore-log: 
,09-28 13:15:23.036  5645  5692 I jxcore-log: ok 53 revs are equal
09-28 13:15:23.036  5645  5692 I jxcore-log: 
,09-28 13:15:23.166  5645  5692 I jxcore-log: ok 54 should be equal
09-28 13:15:23.166  5645  5692 I jxcore-log: 
,09-28 13:15:23.167  5645  5692 I jxcore-log: ok 55 revs are equal
09-28 13:15:23.167  5645  5692 I jxcore-log: 
,09-28 13:15:23.290  5645  5692 I jxcore-log: ok 56 should be equal
09-28 13:15:23.290  5645  5692 I jxcore-log: 
,09-28 13:15:23.290  5645  5692 I jxcore-log: ok 57 revs are equal
09-28 13:15:23.290  5645  5692 I jxcore-log: 
,09-28 13:15:23.295  5645  5692 I jxcore-log: # teardown
09-28 13:15:23.295  5645  5692 I jxcore-log: 
,09-28 13:15:23.325  5645  5692 I jxcore-log: # setup
09-28 13:15:23.325  5645  5692 I jxcore-log: 
,09-28 13:15:23.403  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-28 13:15:23.403  5645  5692 I jxcore-log: 
,09-28 13:15:23.983  5645  5692 I jxcore-log: 2016-09-28 17:15:23 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-28 13:15:23.983  5645  5692 I jxcore-log: 
,09-28 13:15:23.984  5645  5692 I jxcore-log: ok 58 Our rev is old so we should fail
09-28 13:15:23.984  5645  5692 I jxcore-log: 
,09-28 13:15:23.987  5645  5692 I jxcore-log: # teardown
09-28 13:15:23.987  5645  5692 I jxcore-log: 
,09-28 13:15:24.094  5645  5692 I jxcore-log: # setup
09-28 13:15:24.094  5645  5692 I jxcore-log: 
,09-28 13:15:24.112  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-28 13:15:24.112  5645  5692 I jxcore-log: 
,09-28 13:15:24.195  5645  5692 I jxcore-log: ok 59 confirm stop caused failure
09-28 13:15:24.195  5645  5692 I jxcore-log: 
,09-28 13:15:24.203  5645  5692 I jxcore-log: # teardown
09-28 13:15:24.203  5645  5692 I jxcore-log: 
,09-28 13:15:24.237  5645  5692 I jxcore-log: # setup
09-28 13:15:24.237  5645  5692 I jxcore-log: 
,09-28 13:15:24.281  5645  5692 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-28 13:15:24.281  5645  5692 I jxcore-log: 
,09-28 13:15:24.590  5645  5692 I jxcore-log: 2016-09-28 17:15:24 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-28 13:15:24.590  5645  5692 I jxcore-log: 
,09-28 13:15:24.591  5645  5692 I jxcore-log: ok 60 stop caused us to fail
09-28 13:15:24.591  5645  5692 I jxcore-log: 
09-28 13:15:24.591  5645  5692 I jxcore-log: ok 61 We specifically failed on a stop before put
09-28 13:15:24.591  5645  5692 I jxcore-log: 
,09-28 13:15:24.597  5645  5692 I jxcore-log: # teardown
09-28 13:15:24.597  5645  5692 I jxcore-log: 
,09-28 13:15:24.640  5645  5692 I jxcore-log: # setup
09-28 13:15:24.640  5645  5692 I jxcore-log: 
,09-28 13:15:24.696  5645  5692 I jxcore-log: # #update - fail if stop is called
09-28 13:15:24.696  5645  5692 I jxcore-log: 
,09-28 13:15:24.861  5645  5692 I jxcore-log: ok 62 failed due to stop
09-28 13:15:24.861  5645  5692 I jxcore-log: 
09-28 13:15:24.864  5645  5692 I jxcore-log: ok 63 failed due to stop
09-28 13:15:24.864  5645  5692 I jxcore-log: 
,09-28 13:15:24.877  5645  5692 I jxcore-log: # teardown
09-28 13:15:24.877  5645  5692 I jxcore-log: 
,09-28 13:15:24.903  5645  5692 I jxcore-log: # setup
09-28 13:15:24.903  5645  5692 I jxcore-log: 
,09-28 13:15:24.948  5645  5692 I jxcore-log: # #update - set seq for first time
09-28 13:15:24.948  5645  5692 I jxcore-log: 
,09-28 13:15:25.442  5645  5692 I jxcore-log: ok 64 should be equal
09-28 13:15:25.442  5645  5692 I jxcore-log: 
,09-28 13:15:25.448  5645  5692 I jxcore-log: # teardown
09-28 13:15:25.448  5645  5692 I jxcore-log: 
,09-28 13:15:25.503  5645  5692 I jxcore-log: # setup
09-28 13:15:25.503  5645  5692 I jxcore-log: 
,09-28 13:15:25.548  5645  5692 I jxcore-log: # #update - Fail on bad seq value
09-28 13:15:25.548  5645  5692 I jxcore-log: 
,09-28 13:15:25.922  5645  5692 I jxcore-log: 2016-09-28 17:15:25 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-28 13:15:25.922  5645  5692 I jxcore-log: 
,09-28 13:15:25.924  5645  5692 I jxcore-log: ok 65 Expected bad seq error
09-28 13:15:25.924  5645  5692 I jxcore-log: 
,09-28 13:15:25.928  5645  5692 I jxcore-log: # teardown
09-28 13:15:25.928  5645  5692 I jxcore-log: 
,09-28 13:15:25.929   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:26.008  5645  5692 I jxcore-log: # setup
09-28 13:15:26.008  5645  5692 I jxcore-log: 
,09-28 13:15:26.049  5645  5692 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-28 13:15:26.049  5645  5692 I jxcore-log: 
,09-28 13:15:26.494  5645  5692 I jxcore-log: ok 66 Different promises
09-28 13:15:26.494  5645  5692 I jxcore-log: 
,09-28 13:15:26.497  5645  5692 I jxcore-log: ok 67 Timer was cancelled
09-28 13:15:26.497  5645  5692 I jxcore-log: 
,09-28 13:15:26.625  5645  5692 I jxcore-log: ok 68 should be equal
09-28 13:15:26.625  5645  5692 I jxcore-log: 
,09-28 13:15:26.631  5645  5692 I jxcore-log: # teardown
09-28 13:15:26.631  5645  5692 I jxcore-log: 
,09-28 13:15:26.711  5645  5692 I jxcore-log: # setup
09-28 13:15:26.711  5645  5692 I jxcore-log: 
,09-28 13:15:26.731  5645  5692 I jxcore-log: # #update - do we wait for blocked update
09-28 13:15:26.731  5645  5692 I jxcore-log: 
,09-28 13:15:26.824  5645  5692 I jxcore-log: ok 69 One go and one blocked
09-28 13:15:26.824  5645  5692 I jxcore-log: 
,09-28 13:15:26.825  5645  5692 I jxcore-log: ok 70 All blocked
09-28 13:15:26.825  5645  5692 I jxcore-log: 
09-28 13:15:26.825  5645  5692 I jxcore-log: ok 71 Still blocked
09-28 13:15:26.825  5645  5692 I jxcore-log: 
,09-28 13:15:26.930   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:27.279  5645  5692 I jxcore-log: ok 72 should be equal
09-28 13:15:27.279  5645  5692 I jxcore-log: 
,09-28 13:15:27.287  5645  5692 I jxcore-log: # teardown
09-28 13:15:27.287  5645  5692 I jxcore-log: 
,09-28 13:15:27.357  5645  5692 I jxcore-log: # setup
09-28 13:15:27.357  5645  5692 I jxcore-log: 
,09-28 13:15:27.401  5645  5692 I jxcore-log: # #update - test that we wait long enough
09-28 13:15:27.401  5645  5692 I jxcore-log: 
,09-28 13:15:27.930   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:28.931   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:29.168  5645  5692 I jxcore-log: ok 73 We waited long enough
09-28 13:15:29.168  5645  5692 I jxcore-log: 
,09-28 13:15:29.273  5645  5692 I jxcore-log: ok 74 should be equal
09-28 13:15:29.273  5645  5692 I jxcore-log: 
,09-28 13:15:29.280  5645  5692 I jxcore-log: # teardown
09-28 13:15:29.280  5645  5692 I jxcore-log: 
,09-28 13:15:29.315  5645  5692 I jxcore-log: # setup
09-28 13:15:29.315  5645  5692 I jxcore-log: 
,09-28 13:15:29.391  5645  5692 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-28 13:15:29.391  5645  5692 I jxcore-log: 
,09-28 13:15:29.809  5645  5692 I jxcore-log: ok 75 Should have gotten same timer promise
09-28 13:15:29.809  5645  5692 I jxcore-log: 
,09-28 13:15:29.809  5645  5692 I jxcore-log: ok 76 Still same timer promise
09-28 13:15:29.809  5645  5692 I jxcore-log: 
,09-28 13:15:29.932   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:30.588  5645  5692 I jxcore-log: ok 77 We waited long enough
09-28 13:15:30.588  5645  5692 I jxcore-log: 
,09-28 13:15:30.659  5645  5692 I jxcore-log: ok 78 should be equal
09-28 13:15:30.659  5645  5692 I jxcore-log: 
,09-28 13:15:30.665  5645  5692 I jxcore-log: # teardown
09-28 13:15:30.665  5645  5692 I jxcore-log: 
,09-28 13:15:30.713  5645  5692 I jxcore-log: # setup
09-28 13:15:30.713  5645  5692 I jxcore-log: 
,09-28 13:15:30.788  5645  5692 I jxcore-log: # Coordinated seq test
09-28 13:15:30.788  5645  5692 I jxcore-log: 
,09-28 13:15:30.792  5645  5692 I jxcore-log: 2016-09-28 17:15:30 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-28 13:15:30.792  5645  5692 I jxcore-log: 
,09-28 13:15:30.890  5645  5692 I jxcore-log: # teardown
09-28 13:15:30.890  5645  5692 I jxcore-log: 
,09-28 13:15:30.931  5645  5692 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-28 13:15:30.931  5645  5692 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 13:15:30.931  5645  5692 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 13:15:30.931  5645  5692 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 13:15:30.933   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 13:15:30.944  5645  5692 I jxcore-log: # setup
09-28 13:15:30.944  5645  5692 I jxcore-log: 
,09-28 13:15:30.999  5645  5692 I jxcore-log: # closeAll can close even when connections open
09-28 13:15:30.999  5645  5692 I jxcore-log: 
,09-28 13:15:31.160  5645  5692 I jxcore-log: ok 79 not possible to connect to the server anymore
09-28 13:15:31.160  5645  5692 I jxcore-log: 
,09-28 13:15:31.171  5645  5692 I jxcore-log: # teardown
09-28 13:15:31.171  5645  5692 I jxcore-log: 
,09-28 13:15:31.232  5645  5692 I jxcore-log: # setup
09-28 13:15:31.232  5645  5692 I jxcore-log: 
,09-28 13:15:31.276  5645  5692 I jxcore-log: # closeAll with promise
09-28 13:15:31.276  5645  5692 I jxcore-log: 
,09-28 13:15:31.434  5645  5692 I jxcore-log: ok 80 not possible to connect to the server anymore
09-28 13:15:31.434  5645  5692 I jxcore-log: 
,09-28 13:15:31.443  5645  5692 I jxcore-log: # teardown
09-28 13:15:31.443  5645  5692 I jxcore-log: 
,09-28 13:15:31.489  5645  5692 I jxcore-log: # setup
09-28 13:15:31.489  5645  5692 I jxcore-log: 
,09-28 13:15:31.545  5645  5692 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-28 13:15:31.545  5645  5692 I jxcore-log: 
,09-28 13:15:31.688  5645  5692 I jxcore-log: ok 81 Got the right error
09-28 13:15:31.688  5645  5692 I jxcore-log: 
,09-28 13:15:31.703  5645  5692 I jxcore-log: # teardown
09-28 13:15:31.703  5645  5692 I jxcore-log: 
,09-28 13:15:31.752  5645  5692 I jxcore-log: # setup
09-28 13:15:31.752  5645  5692 I jxcore-log: 
,09-28 13:15:31.799  5645  5692 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-28 13:15:31.799  5645  5692 I jxcore-log: 
,09-28 13:15:31.957  5645  5692 I jxcore-log: # teardown
09-28 13:15:31.957  5645  5692 I jxcore-log: 
,09-28 13:15:32.013  5645  5692 I jxcore-log: # setup
09-28 13:15:32.013  5645  5692 I jxcore-log: 
,09-28 13:15:32.059  5645  5692 I jxcore-log: # onPeerLost calls jxcore
09-28 13:15:32.059  5645  5692 I jxcore-log: 
,09-28 13:15:32.115  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 13:15:32.115  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b02eda1 added. We now have 3 listener(s)
09-28 13:15:32.117  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 13:15:32.117  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:15:32.117  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 13:15:32.117  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:15:32.118  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c6bc6 added. We now have 4 listener(s)
09-28 13:15:32.118  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 13:15:32.119  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:15:32.127  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:15:32.132  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:15:32.135  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:15:32.135  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 13:15:32.135  5645  5692 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-28 13:15:32.135  5645  5692 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-28 13:15:32.140  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 13:15:32.143  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:15:34.139  5645  5692 I jxcore-log: onPeerLost
09-28 13:15:34.139  5645  5692 I jxcore-log: 
,09-28 13:15:34.142  5645  5692 I jxcore-log: 2016-09-28 17:15:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:34.142  5645  5692 I jxcore-log: 
,09-28 13:15:34.156  5645  5692 I jxcore-log: # teardown
09-28 13:15:34.156  5645  5692 I jxcore-log: 
,09-28 13:15:34.160  5645  5692 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-28 13:15:34.160  5645  5692 I jxcore-log: 
,09-28 13:15:34.161  5645  5692 I jxcore-log: ok 83 check if peerAvailable is false
09-28 13:15:34.161  5645  5692 I jxcore-log: 
,09-28 13:15:34.260  5645  5692 I jxcore-log: 2016-09-28 17:15:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 13:15:34.260  5645  5692 I jxcore-log: 
,09-28 13:15:34.263  5645  5692 I jxcore-log: 2016-09-28 17:15:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 13:15:34.263  5645  5692 I jxcore-log: 
,09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:15:34.273  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:15:34.276  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:15:34.278  5645  5692 I jxcore-log: 2016-09-28 17:15:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 13:15:34.278  5645  5692 I jxcore-log: 
,09-28 13:15:34.280  5645  5692 I jxcore-log: 2016-09-28 17:15:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 13:15:34.280  5645  5692 I jxcore-log: 
,09-28 13:15:34.286  5645  5692 I jxcore-log: 2016-09-28 17:15:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:34.286  5645  5692 I jxcore-log: 
,09-28 13:15:34.291  5645  5692 I jxcore-log: # setup
09-28 13:15:34.291  5645  5692 I jxcore-log: 
,09-28 13:15:34.677  5645  5692 I jxcore-log: # onPeerDiscovered calls jxcore
09-28 13:15:34.677  5645  5692 I jxcore-log: 
,09-28 13:15:34.737  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 13:15:34.738  5645  5692 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e3566b4 added. We now have 4 listener(s)
,09-28 13:15:34.740  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 13:15:34.740  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 13:15:34.741  5645  5692 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 13:15:34.741  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 13:15:34.741  5645  5692 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53fc2dd added. We now have 5 listener(s)
09-28 13:15:34.741  5645  5692 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 13:15:34.742  5645  5692 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 13:15:34.748  5645  5692 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:15:34.754  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:15:34.757  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:15:34.758  5645  5692 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 13:15:34.758  5645  5692 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-28 13:15:34.762  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:15:34.766  5645  5645 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 13:15:36.760  5645  5692 I jxcore-log: onPeerDiscovered
09-28 13:15:36.760  5645  5692 I jxcore-log: 
,09-28 13:15:36.763  5645  5692 I jxcore-log: 2016-09-28 17:15:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:36.763  5645  5692 I jxcore-log: 
,09-28 13:15:36.774  5645  5692 I jxcore-log: # teardown
09-28 13:15:36.774  5645  5692 I jxcore-log: 
,09-28 13:15:36.779  5645  5692 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-28 13:15:36.779  5645  5692 I jxcore-log: 
,09-28 13:15:36.780  5645  5692 I jxcore-log: ok 85 check if peerAvailable is true
09-28 13:15:36.780  5645  5692 I jxcore-log: 
,09-28 13:15:36.802  5645  5692 I jxcore-log: 2016-09-28 17:15:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 13:15:36.802  5645  5692 I jxcore-log: 
,09-28 13:15:36.804  5645  5692 I jxcore-log: 2016-09-28 17:15:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 13:15:36.804  5645  5692 I jxcore-log: 
,09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 13:15:36.810  5645  5692 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 13:15:36.813  5645  5692 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 13:15:36.814  5645  5692 I jxcore-log: 2016-09-28 17:15:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 13:15:36.814  5645  5692 I jxcore-log: 
09-28 13:15:36.816  5645  5692 I jxcore-log: 2016-09-28 17:15:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 13:15:36.816  5645  5692 I jxcore-log: 
09-28 13:15:36.820  5645  5692 I jxcore-log: 2016-09-28 17:15:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 13:15:36.820  5645  5692 I jxcore-log: 
,09-28 13:15:36.826  5645  5692 I jxcore-log: # setup
09-28 13:15:36.826  5645  5692 I jxcore-log: 
,09-28 13:15:37.243  5645  5692 I jxcore-log: # Call of onCheckpointReached handler on a single db change
09-28 13:15:37.243  5645  5692 I jxcore-log: 
,09-28 13:15:37.572  5645  5692 I jxcore-log: # teardown
09-28 13:15:37.572  5645  5692 I jxcore-log: 
,09-28 13:15:37.712  5645  5692 I jxcore-log: # setup
09-28 13:15:37.712  5645  5692 I jxcore-log: 
,09-28 13:15:37.756  5645  5692 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-28 13:15:37.756  5645  5692 I jxcore-log: 
,09-28 13:15:38.053  5645  5692 I jxcore-log: # teardown
09-28 13:15:38.053  5645  5692 I jxcore-log: 
,09-28 13:15:38.148  5645  5692 I jxcore-log: # setup
09-28 13:15:38.148  5645  5692 I jxcore-log: 
,09-28 13:15:38.215  5645  5692 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-28 13:15:38.215  5645  5692 I jxcore-log: 
,09-28 13:15:39.518  5645  5692 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-28 13:15:39.518  5645  5692 I jxcore-log: 
,09-28 13:15:39.534  5645  5692 I jxcore-log: # teardown
09-28 13:15:39.534  5645  5692 I jxcore-log: 
,09-28 13:15:39.635  5645  5692 I jxcore-log: # setup
09-28 13:15:39.635  5645  5692 I jxcore-log: 
,09-28 13:15:39.682  5645  5692 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-28 13:15:39.682  5645  5692 I jxcore-log: 
,09-28 13:15:39.828   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 13:15:40.252  5645  5692 I jxcore-log: # teardown
09-28 13:15:40.252  5645  5692 I jxcore-log: 
,09-28 13:15:40.345  5645  5692 I jxcore-log: # setup
09-28 13:15:40.345  5645  5692 I jxcore-log: 
,09-28 13:15:40.382  5645  5692 I jxcore-log: # test defaultDirectory
09-28 13:15:40.382  5645  5692 I jxcore-log: 
,09-28 13:15:40.419  5645  5692 I jxcore-log: ok 87 should be equal
09-28 13:15:40.419  5645  5692 I jxcore-log: 
,09-28 13:15:40.425  5645  5692 I jxcore-log: ok 88 should be equal
09-28 13:15:40.425  5645  5692 I jxcore-log: 
,09-28 13:15:40.428  5645  5692 I jxcore-log: ok 89 should be equal
09-28 13:15:40.428  5645  5692 I jxcore-log: 
,09-28 13:15:40.437  5645  5692 I jxcore-log: # teardown
09-28 13:15:40.437  5645  5692 I jxcore-log: 
,09-28 13:15:40.510  5645  5692 I jxcore-log: # setup
09-28 13:15:40.510  5645  5692 I jxcore-log: 
,09-28 13:15:40.550  5645  5692 I jxcore-log: # test defaultAdapter
09-28 13:15:40.550  5645  5692 I jxcore-log: 
,09-28 13:15:40.599  5645  5692 I jxcore-log: ok 90 should be equal
09-28 13:15:40.599  5645  5692 I jxcore-log: 
,09-28 13:15:40.600  5645  5692 I jxcore-log: ok 91 should be equal
09-28 13:15:40.600  5645  5692 I jxcore-log: 
,09-28 13:15:40.604  5645  5692 I jxcore-log: ok 92 should be equal
09-28 13:15:40.604  5645  5692 I jxcore-log: 
,09-28 13:15:40.605  5645  5692 I jxcore-log: ok 93 should be equal
09-28 13:15:40.605  5645  5692 I jxcore-log: 
,09-28 13:15:40.609  5645  5692 I jxcore-log: ok 94 should be equal
09-28 13:15:40.609  5645  5692 I jxcore-log: 
,09-28 13:15:40.611  5645  5692 I jxcore-log: ok 95 should be equal
09-28 13:15:40.611  5645  5692 I jxcore-log: 
,09-28 13:15:40.758  5645  5692 I jxcore-log: ok 96 should be equal
09-28 13:15:40.758  5645  5692 I jxcore-log: 
,09-28 13:15:40.759  5645  5692 I jxcore-log: ok 97 should be equal
09-28 13:15:40.759  5645  5692 I jxcore-log: 
,09-28 13:15:40.766  5645  5692 I jxcore-log: # teardown
09-28 13:15:40.766  5645  5692 I jxcore-log: 
,09-28 13:15:40.862  5645  5692 I jxcore-log: # setup
09-28 13:15:40.862  5645  5692 I jxcore-log: 
,09-28 13:15:40.898  5645  5692 I jxcore-log: # enqueue and run in order
09-28 13:15:40.898  5645  5692 I jxcore-log: 
,09-28 13:15:40.933   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:41.045  5645  5692 I jxcore-log: ok 98 firstPromise setTimeout
09-28 13:15:41.045  5645  5692 I jxcore-log: 
,09-28 13:15:41.050  5645  5692 I jxcore-log: ok 99 firstPromise result
09-28 13:15:41.050  5645  5692 I jxcore-log: 
,09-28 13:15:41.052  5645  5692 I jxcore-log: ok 100 firstPromise testValue
09-28 13:15:41.052  5645  5692 I jxcore-log: 
,09-28 13:15:41.156  5645  5692 I jxcore-log: ok 101 secondPromise setTimeout
09-28 13:15:41.156  5645  5692 I jxcore-log: 
,09-28 13:15:41.159  5645  5692 I jxcore-log: ok 102 secondPromise result
09-28 13:15:41.159  5645  5692 I jxcore-log: 
,09-28 13:15:41.161  5645  5692 I jxcore-log: ok 103 secondPromise testValue
09-28 13:15:41.161  5645  5692 I jxcore-log: 
,09-28 13:15:41.164  5645  5692 I jxcore-log: ok 104 thirdPromise in promise
09-28 13:15:41.164  5645  5692 I jxcore-log: 
,09-28 13:15:41.167  5645  5692 I jxcore-log: ok 105 thirdPromise result
09-28 13:15:41.167  5645  5692 I jxcore-log: 
,09-28 13:15:41.169  5645  5692 I jxcore-log: ok 106 thirdPromise testValue
09-28 13:15:41.169  5645  5692 I jxcore-log: 
,09-28 13:15:41.178  5645  5692 I jxcore-log: # teardown
09-28 13:15:41.178  5645  5692 I jxcore-log: 
,09-28 13:15:41.250  5645  5692 I jxcore-log: # setup
09-28 13:15:41.250  5645  5692 I jxcore-log: 
,09-28 13:15:41.548  5645  5692 I jxcore-log: # enqueueAtTop and run backwards
09-28 13:15:41.548  5645  5692 I jxcore-log: 
,09-28 13:15:41.935   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:42.460  5645  5692 I jxcore-log: ok 107 thirdPromise - first to run
09-28 13:15:42.460  5645  5692 I jxcore-log: 
,09-28 13:15:42.463  5645  5692 I jxcore-log: ok 108 thirdPromise - in resolve
09-28 13:15:42.463  5645  5692 I jxcore-log: 
,09-28 13:15:42.464  5645  5692 I jxcore-log: ok 109 secondPromise - second to run
09-28 13:15:42.464  5645  5692 I jxcore-log: 
,09-28 13:15:42.466  5645  5692 I jxcore-log: ok 110 secondPromise - in catch
09-28 13:15:42.466  5645  5692 I jxcore-log: 
,09-28 13:15:42.468  5645  5692 I jxcore-log: ok 111 firstPromise - third to run
09-28 13:15:42.468  5645  5692 I jxcore-log: 
,09-28 13:15:42.470  5645  5692 I jxcore-log: ok 112 firstPromise - in then
09-28 13:15:42.470  5645  5692 I jxcore-log: 
,09-28 13:15:42.471  5645  5692 I jxcore-log: ok 113 testing promises
09-28 13:15:42.471  5645  5692 I jxcore-log: 
,09-28 13:15:42.480  5645  5692 I jxcore-log: # teardown
09-28 13:15:42.480  5645  5692 I jxcore-log: 
,09-28 13:15:42.662  5645  5692 I jxcore-log: # setup
09-28 13:15:42.662  5645  5692 I jxcore-log: 
,09-28 13:15:42.708  5645  5692 I jxcore-log: # mix enqueue and enqueueAtTop
09-28 13:15:42.708  5645  5692 I jxcore-log: 
,09-28 13:15:42.779  5645  5692 I jxcore-log: ok 114 fourth
09-28 13:15:42.779  5645  5692 I jxcore-log: 
,09-28 13:15:42.782  5645  5692 I jxcore-log: ok 115 fourth
09-28 13:15:42.782  5645  5692 I jxcore-log: 
,09-28 13:15:42.783  5645  5692 I jxcore-log: ok 116 second
09-28 13:15:42.783  5645  5692 I jxcore-log: 
,09-28 13:15:42.786  5645  5692 I jxcore-log: ok 117 secondPromise - in then
09-28 13:15:42.786  5645  5692 I jxcore-log: 
,09-28 13:15:42.891  5645  5692 I jxcore-log: ok 118 first
09-28 13:15:42.891  5645  5692 I jxcore-log: 
,09-28 13:15:42.894  5645  5692 I jxcore-log: ok 119 firstPromise - in catch
09-28 13:15:42.894  5645  5692 I jxcore-log: 
09-28 13:15:42.896  5645  5692 I jxcore-log: ok 120 third
09-28 13:15:42.896  5645  5692 I jxcore-log: 
,09-28 13:15:42.902  5645  5692 I jxcore-log: ok 121 thirdPromise - in then
09-28 13:15:42.902  5645  5692 I jxcore-log: 
,09-28 13:15:42.904  5645  5692 I jxcore-log: ok 122 testingPromises
09-28 13:15:42.904  5645  5692 I jxcore-log: 
,09-28 13:15:42.916  5645  5692 I jxcore-log: # teardown
09-28 13:15:42.916  5645  5692 I jxcore-log: 
,09-28 13:15:42.935   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:42.953  5645  5692 I jxcore-log: # setup
09-28 13:15:42.953  5645  5692 I jxcore-log: 
,09-28 13:15:43.075  5645  5692 I jxcore-log: # queues handled independently
09-28 13:15:43.075  5645  5692 I jxcore-log: 
,09-28 13:15:43.143  5645  5692 I jxcore-log: ok 123 all short operations completed before the long resolves
09-28 13:15:43.143  5645  5692 I jxcore-log: 
,09-28 13:15:43.152  5645  5692 I jxcore-log: # teardown
09-28 13:15:43.152  5645  5692 I jxcore-log: 
,09-28 13:15:43.211  5645  5692 I jxcore-log: # setup
09-28 13:15:43.211  5645  5692 I jxcore-log: 
,09-28 13:15:43.260  5645  5692 I jxcore-log: # basic
09-28 13:15:43.260  5645  5692 I jxcore-log: 
,09-28 13:15:43.295  5645  5692 I jxcore-log: ok 124 sane
09-28 13:15:43.295  5645  5692 I jxcore-log: 
,09-28 13:15:43.310  5645  5692 I jxcore-log: # teardown
09-28 13:15:43.310  5645  5692 I jxcore-log: 
,09-28 13:15:43.339  5645  5692 I jxcore-log: # setup
09-28 13:15:43.339  5645  5692 I jxcore-log: 
,09-28 13:15:43.367  5645  5692 I jxcore-log: # another
09-28 13:15:43.367  5645  5692 I jxcore-log: 
,09-28 13:15:43.395  5645  5692 I jxcore-log: ok 125 sane
09-28 13:15:43.395  5645  5692 I jxcore-log: 
,09-28 13:15:43.402  5645  5692 I jxcore-log: # teardown
09-28 13:15:43.402  5645  5692 I jxcore-log: 
,09-28 13:15:43.430  5645  5692 I jxcore-log: # setup
09-28 13:15:43.430  5645  5692 I jxcore-log: 
,09-28 13:15:43.464  5645  5692 I jxcore-log: # can pass data in setup
09-28 13:15:43.464  5645  5692 I jxcore-log: 
,09-28 13:15:43.498  5645  5692 I jxcore-log: ok 126 test participant has uuid
09-28 13:15:43.498  5645  5692 I jxcore-log: 
,09-28 13:15:43.498  5645  5692 I jxcore-log: ok 127 participant data matches
09-28 13:15:43.498  5645  5692 I jxcore-log: 
09-28 13:15:43.499  5645  5692 I jxcore-log: ok 128 test participant has uuid
09-28 13:15:43.499  5645  5692 I jxcore-log: 
09-28 13:15:43.499  5645  5692 I jxcore-log: ok 129 participant data matches
09-28 13:15:43.499  5645  5692 I jxcore-log: 
09-28 13:15:43.500  5645  5692 I jxcore-log: ok 130 test participant has uuid
09-28 13:15:43.500  5645  5692 I jxcore-log: 
,09-28 13:15:43.500  5645  5692 I jxcore-log: ok 131 participant data matches
09-28 13:15:43.500  5645  5692 I jxcore-log: 
09-28 13:15:43.501  5645  5692 I jxcore-log: ok 132 own UUID is found from the participants list
09-28 13:15:43.501  5645  5692 I jxcore-log: 
,09-28 13:15:43.507  5645  5692 I jxcore-log: # teardown
09-28 13:15:43.507  5645  5692 I jxcore-log: 
,09-28 13:15:43.544  5645  5692 I jxcore-log: # setup
09-28 13:15:43.544  5645  5692 I jxcore-log: 
,09-28 13:15:43.588  5645  5692 I jxcore-log: # test thali manager spies
09-28 13:15:43.588  5645  5692 I jxcore-log: 
,09-28 13:15:43.733  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-28 13:15:43.733  5645  5692 I jxcore-log: 
,09-28 13:15:43.738  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-28 13:15:43.738  5645  5692 I jxcore-log: 
,09-28 13:15:43.740  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'creating express pouchdb instance'
09-28 13:15:43.740  5645  5692 I jxcore-log: 
,09-28 13:15:43.756  5645  5692 I jxcore-log: ok 133 expressPouchDB was called once
09-28 13:15:43.756  5645  5692 I jxcore-log: 
,09-28 13:15:43.757  5645  5692 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-28 13:15:43.757  5645  5692 I jxcore-log: 
09-28 13:15:43.757  5645  5692 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-28 13:15:43.757  5645  5692 I jxcore-log: 
09-28 13:15:43.757  5645  5692 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-28 13:15:43.757  5645  5692 I jxcore-log: 
09-28 13:15:43.757  5645  5692 I jxcore-log: ok 137 PouchDB was called once
09-28 13:15:43.757  5645  5692 I jxcore-log: 
,09-28 13:15:43.758  5645  5692 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-28 13:15:43.758  5645  5692 I jxcore-log: 
09-28 13:15:43.758  5645  5692 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-28 13:15:43.758  5645  5692 I jxcore-log: 
09-28 13:15:43.758  5645  5692 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-28 13:15:43.758  5645  5692 I jxcore-log: 
,09-28 13:15:43.758  5645  5692 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-28 13:15:43.758  5645  5692 I jxcore-log: 
09-28 13:15:43.759  5645  5692 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-28 13:15:43.759  5645  5692 I jxcore-log: 
09-28 13:15:43.759  5645  5692 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-28 13:15:43.759  5645  5692 I jxcore-log: 
09-28 13:15:43.759  5645  5692 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-28 13:15:43.759  5645  5692 I jxcore-log: 
09-28 13:15:43.759  5645  5692 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-28 13:15:43.759  5645  5692 I jxcore-log: 
09-28 13:15:43.760  5645  5692 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-28 13:15:43.760  5645  5692 I jxcore-log: 
,09-28 13:15:43.760  5645  5692 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-28 13:15:43.760  5645  5692 I jxcore-log: 
09-28 13:15:43.760  5645  5692 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-28 13:15:43.760  5645  5692 I jxcore-log: 
09-28 13:15:43.760  5645  5692 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-28 13:15:43.760  5645  5692 I jxcore-log: 
09-28 13:15:43.761  5645  5692 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-28 13:15:43.761  5645  5692 I jxcore-log: 
09-28 13:15:43.761  5645  5692 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-28 13:15:43.761  5645  5692 I jxcore-log: 
,09-28 13:15:43.761  5645  5692 I jxcore-log: ok 152 Salti was called once
09-28 13:15:43.761  5645  5692 I jxcore-log: 
09-28 13:15:43.761  5645  5692 I jxcore-log: ok 153 Salti was called with 4 arguments
09-28 13:15:43.761  5645  5692 I jxcore-log: 
09-28 13:15:43.761  5645  5692 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-28 13:15:43.761  5645  5692 I jxcore-log: 
09-28 13:15:43.762  5645  5692 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-28 13:15:43.762  5645  5692 I jxcore-log: 
,09-28 13:15:43.762  5645  5692 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-28 13:15:43.762  5645  5692 I jxcore-log: 
09-28 13:15:43.762  5645  5692 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-28 13:15:43.762  5645  5692 I jxcore-log: 
,09-28 13:15:43.763  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 13:15:43.763  5645  5692 I jxcore-log: 
,09-28 13:15:43.764  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 13:15:43.764  5645  5692 I jxcore-log: 
,09-28 13:15:43.765  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 13:15:43.765  5645  5692 I jxcore-log: 
,09-28 13:15:43.768  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'start listening for advertisements'
09-28 13:15:43.768  5645  5692 I jxcore-log: 
,09-28 13:15:43.772  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'start update advertising and listening'
09-28 13:15:43.772  5645  5692 I jxcore-log: 
,09-28 13:15:43.798  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliWifiInfrastructure: 'listening 47794'
09-28 13:15:43.798  5645  5692 I jxcore-log: 
,09-28 13:15:43.801  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 13:15:43.801  5645  5692 I jxcore-log: 
,09-28 13:15:43.821  5645  5692 I jxcore-log: ok 158 ThaliMobile.start was called once
09-28 13:15:43.821  5645  5692 I jxcore-log: 
,09-28 13:15:43.821  5645  5692 I jxcore-log: ok 159 ThaliMobile.start was called with 2 arguments
09-28 13:15:43.821  5645  5692 I jxcore-log: 
09-28 13:15:43.822  5645  5692 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-28 13:15:43.822  5645  5692 I jxcore-log: 
09-28 13:15:43.822  5645  5692 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-28 13:15:43.822  5645  5692 I jxcore-log: 
09-28 13:15:43.822  5645  5692 I jxcore-log: ok 162 ThaliMobile.startListeningForAdvertisements was called once
09-28 13:15:43.822  5645  5692 I jxcore-log: 
,09-28 13:15:43.822  5645  5692 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-28 13:15:43.822  5645  5692 I jxcore-log: 
09-28 13:15:43.823  5645  5692 I jxcore-log: ok 164 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-28 13:15:43.823  5645  5692 I jxcore-log: 
09-28 13:15:43.823  5645  5692 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-28 13:15:43.823  5645  5692 I jxcore-log: 
09-28 13:15:43.823  5645  5692 I jxcore-log: ok 166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-28 13:15:43.823  5645  5692 I jxcore-log: 
09-28 13:15:43.823  5645  5692 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-28 13:15:43.823  5645  5692 I jxcore-log: 
09-28 13:15:43.823  5645  5692 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 13:15:43.823  5645  5692 I jxcore-log: 
,09-28 13:15:43.824  5645  5692 I jxcore-log: ok 169 ThaliPullReplicationFromNotification.prototype.start was called once
09-28 13:15:43.824  5645  5692 I jxcore-log: 
09-28 13:15:43.824  5645  5692 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-28 13:15:43.824  5645  5692 I jxcore-log: 
09-28 13:15:43.824  5645  5692 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 13:15:43.824  5645  5692 I jxcore-log: 
,09-28 13:15:43.825  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 13:15:43.825  5645  5692 I jxcore-log: 
,09-28 13:15:43.826  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 13:15:43.826  5645  5692 I jxcore-log: 
,09-28 13:15:43.827  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 13:15:43.827  5645  5692 I jxcore-log: 
,09-28 13:15:43.829  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 13:15:43.829  5645  5692 I jxcore-log: 
,09-28 13:15:43.833  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 13:15:43.833  5645  5692 I jxcore-log: 
,09-28 13:15:43.835  5645  5692 I jxcore-log: 2016-09-28 17:15:43 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 13:15:43.835  5645  5692 I jxcore-log: 
,09-28 13:15:43.838  5645  5692 I jxcore-log: ok 172 ThaliMobile.stop was called once
09-28 13:15:43.838  5645  5692 I jxcore-log: 
,09-28 13:15:43.839  5645  5692 I jxcore-log: ok 173 ThaliMobile.stop was called with 0 arguments
09-28 13:15:43.839  5645  5692 I jxcore-log: 
09-28 13:15:43.839  5645  5692 I jxcore-log: ok 174 ThaliMobile.stopListeningForAdvertisements was called once
09-28 13:15:43.839  5645  5692 I jxcore-log: 
09-28 13:15:43.839  5645  5692 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-28 13:15:43.839  5645  5692 I jxcore-log: 
,09-28 13:15:43.839  5645  5692 I jxcore-log: ok 176 ThaliMobile.stopAdvertisingAndListening was called once
09-28 13:15:43.839  5645  5692 I jxcore-log: 
09-28 13:15:43.839  5645  5692 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-28 13:15:43.839  5645  5692 I jxcore-log: 
09-28 13:15:43.840  5645  5692 I jxcore-log: ok 178 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-28 13:15:43.840  5645  5692 I jxcore-log: 
09-28 13:15:43.840  5645  5692 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-28 13:15:43.840  5645  5692 I jxcore-log: 
09-28 13:15:43.840  5645  5692 I jxcore-log: ok 180 ThaliPullReplicationFromNotification.prototype.stop was called once
09-28 13:15:43.840  5645  5692 I jxcore-log: 
09-28 13:15:43.840  5645  5692 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-28 13:15:43.840  5645  5692 I jxcore-log: 
,09-28 13:15:43.850  5645  5692 I jxcore-log: # teardown
09-28 13:15:43.850  5645  5692 I jxcore-log: 
,09-28 13:15:43.904  5645  5692 I jxcore-log: # setup
09-28 13:15:43.904  5645  5692 I jxcore-log: 
,09-28 13:15:43.936   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:43.942  5645  5692 I jxcore-log: # test thali manager multiple starts and stops
09-28 13:15:43.942  5645  5692 I jxcore-log: 
,09-28 13:15:44.108  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-28 13:15:44.108  5645  5692 I jxcore-log: 
,09-28 13:15:44.116  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-28 13:15:44.116  5645  5692 I jxcore-log: 
,09-28 13:15:44.118  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'creating express pouchdb instance'
09-28 13:15:44.118  5645  5692 I jxcore-log: 
,09-28 13:15:44.141  5645  5692 I jxcore-log: ok 182 expressPouchDB was called once
09-28 13:15:44.141  5645  5692 I jxcore-log: 
09-28 13:15:44.141  5645  5692 I jxcore-log: ok 183 expressPouchDB was called with 2 arguments
09-28 13:15:44.141  5645  5692 I jxcore-log: 
,09-28 13:15:44.142  5645  5692 I jxcore-log: ok 184 expressPouchDB was called with 'PouchDB' as 1-st argument
09-28 13:15:44.142  5645  5692 I jxcore-log: 
09-28 13:15:44.142  5645  5692 I jxcore-log: ok 185 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-28 13:15:44.142  5645  5692 I jxcore-log: 
09-28 13:15:44.142  5645  5692 I jxcore-log: ok 186 PouchDB was called once
09-28 13:15:44.142  5645  5692 I jxcore-log: 
09-28 13:15:44.142  5645  5692 I jxcore-log: ok 187 PouchDB was called with 1 arguments
09-28 13:15:44.142  5645  5692 I jxcore-log: 
09-28 13:15:44.143  5645  5692 I jxcore-log: ok 188 PouchDB was called with 'dbName' as 1-st argument
09-28 13:15:44.143  5645  5692 I jxcore-log: 
,09-28 13:15:44.143  5645  5692 I jxcore-log: ok 189 ThaliSendNotificationBasedOnReplication was called once
09-28 13:15:44.143  5645  5692 I jxcore-log: 
09-28 13:15:44.143  5645  5692 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-28 13:15:44.143  5645  5692 I jxcore-log: 
09-28 13:15:44.143  5645  5692 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-28 13:15:44.143  5645  5692 I jxcore-log: 
09-28 13:15:44.144  5645  5692 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-28 13:15:44.144  5645  5692 I jxcore-log: 
,09-28 13:15:44.144  5645  5692 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-28 13:15:44.144  5645  5692 I jxcore-log: 
09-28 13:15:44.144  5645  5692 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-28 13:15:44.144  5645  5692 I jxcore-log: 
09-28 13:15:44.145  5645  5692 I jxcore-log: ok 195 ThaliPullReplicationFromNotification was called once
09-28 13:15:44.145  5645  5692 I jxcore-log: 
09-28 13:15:44.145  5645  5692 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called with 4 arguments
09-28 13:15:44.145  5645  5692 I jxcore-log: 
09-28 13:15:44.145  5645  5692 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-28 13:15:44.145  5645  5692 I jxcore-log: 
09-28 13:15:44.145  5645  5692 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-28 13:15:44.145  5645  5692 I jxcore-log: 
09-28 13:15:44.145  5645  5692 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-28 13:15:44.145  5645  5692 I jxcore-log: 
09-28 13:15:44.146  5645  5692 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-28 13:15:44.146  5645  5692 I jxcore-log: 
09-28 13:15:44.146  5645  5692 I jxcore-log: ok 201 Salti was called once
09-28 13:15:44.146  5645  5692 I jxcore-log: 
09-28 13:15:44.146  5645  5692 I jxcore-log: ok 202 Salti was called with 4 arguments
09-28 13:15:44.146  5645  5692 I jxcore-log: 
,09-28 13:15:44.146  5645  5692 I jxcore-log: ok 203 Salti was called with 'dbName' as 1-st argument
09-28 13:15:44.146  5645  5692 I jxcore-log: 
09-28 13:15:44.146  5645  5692 I jxcore-log: ok 204 Salti was called with 'acl' as 2-st argument
09-28 13:15:44.146  5645  5692 I jxcore-log: 
09-28 13:15:44.147  5645  5692 I jxcore-log: ok 205 Salti was called with 'thaliIdCallback' as 3-st argument
09-28 13:15:44.147  5645  5692 I jxcore-log: 
09-28 13:15:44.147  5645  5692 I jxcore-log: ok 206 Salti was called with 'options' as 4-st argument
09-28 13:15:44.147  5645  5692 I jxcore-log: 
,09-28 13:15:44.148  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 13:15:44.148  5645  5692 I jxcore-log: 
09-28 13:15:44.148  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 13:15:44.148  5645  5692 I jxcore-log: 
,09-28 13:15:44.149  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 13:15:44.149  5645  5692 I jxcore-log: 
,09-28 13:15:44.152  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start listening for advertisements'
09-28 13:15:44.152  5645  5692 I jxcore-log: 
,09-28 13:15:44.156  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start update advertising and listening'
09-28 13:15:44.156  5645  5692 I jxcore-log: 
,09-28 13:15:44.161  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliWifiInfrastructure: 'listening 44960'
09-28 13:15:44.161  5645  5692 I jxcore-log: 
,09-28 13:15:44.162  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 13:15:44.162  5645  5692 I jxcore-log: 
,09-28 13:15:44.232  5645  5692 I jxcore-log: ok 207 ThaliMobile.start was called once
09-28 13:15:44.232  5645  5692 I jxcore-log: 
,09-28 13:15:44.232  5645  5692 I jxcore-log: ok 208 ThaliMobile.start was called with 2 arguments
09-28 13:15:44.232  5645  5692 I jxcore-log: 
09-28 13:15:44.233  5645  5692 I jxcore-log: ok 209 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-28 13:15:44.233  5645  5692 I jxcore-log: 
09-28 13:15:44.233  5645  5692 I jxcore-log: ok 210 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-28 13:15:44.233  5645  5692 I jxcore-log: 
09-28 13:15:44.233  5645  5692 I jxcore-log: ok 211 ThaliMobile.startListeningForAdvertisements was called once
09-28 13:15:44.233  5645  5692 I jxcore-log: 
,09-28 13:15:44.233  5645  5692 I jxcore-log: ok 212 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-28 13:15:44.233  5645  5692 I jxcore-log: 
09-28 13:15:44.234  5645  5692 I jxcore-log: ok 213 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-28 13:15:44.234  5645  5692 I jxcore-log: 
09-28 13:15:44.234  5645  5692 I jxcore-log: ok 214 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-28 13:15:44.234  5645  5692 I jxcore-log: 
,09-28 13:15:44.234  5645  5692 I jxcore-log: ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-28 13:15:44.234  5645  5692 I jxcore-log: 
09-28 13:15:44.234  5645  5692 I jxcore-log: ok 216 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-28 13:15:44.234  5645  5692 I jxcore-log: 
09-28 13:15:44.235  5645  5692 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 13:15:44.235  5645  5692 I jxcore-log: 
09-28 13:15:44.235  5645  5692 I jxcore-log: ok 218 ThaliPullReplicationFromNotification.prototype.start was called once
09-28 13:15:44.235  5645  5692 I jxcore-log: 
,09-28 13:15:44.235  5645  5692 I jxcore-log: ok 219 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-28 13:15:44.235  5645  5692 I jxcore-log: 
09-28 13:15:44.235  5645  5692 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 13:15:44.235  5645  5692 I jxcore-log: 
09-28 13:15:44.236  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 13:15:44.236  5645  5692 I jxcore-log: 
09-28 13:15:44.237  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 13:15:44.237  5645  5692 I jxcore-log: 
,09-28 13:15:44.240  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 13:15:44.240  5645  5692 I jxcore-log: 
,09-28 13:15:44.242  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 13:15:44.242  5645  5692 I jxcore-log: 
,09-28 13:15:44.247  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 13:15:44.247  5645  5692 I jxcore-log: 
,09-28 13:15:44.249  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 13:15:44.249  5645  5692 I jxcore-log: 
,09-28 13:15:44.255  5645  5692 I jxcore-log: ok 221 ThaliMobile.stop was called once
09-28 13:15:44.255  5645  5692 I jxcore-log: 
,09-28 13:15:44.255  5645  5692 I jxcore-log: ok 222 ThaliMobile.stop was called with 0 arguments
09-28 13:15:44.255  5645  5692 I jxcore-log: 
09-28 13:15:44.255  5645  5692 I jxcore-log: ok 223 ThaliMobile.stopListeningForAdvertisements was called once
09-28 13:15:44.255  5645  5692 I jxcore-log: 
,09-28 13:15:44.256  5645  5692 I jxcore-log: ok 224 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-28 13:15:44.256  5645  5692 I jxcore-log: 
09-28 13:15:44.256  5645  5692 I jxcore-log: ok 225 ThaliMobile.stopAdvertisingAndListening was called once
09-28 13:15:44.256  5645  5692 I jxcore-log: 
09-28 13:15:44.256  5645  5692 I jxcore-log: ok 226 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-28 13:15:44.256  5645  5692 I jxcore-log: 
,09-28 13:15:44.256  5645  5692 I jxcore-log: ok 227 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-28 13:15:44.256  5645  5692 I jxcore-log: 
09-28 13:15:44.256  5645  5692 I jxcore-log: ok 228 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-28 13:15:44.256  5645  5692 I jxcore-log: 
09-28 13:15:44.257  5645  5692 I jxcore-log: ok 229 ThaliPullReplicationFromNotification.prototype.stop was called once
09-28 13:15:44.257  5645  5692 I jxcore-log: 
09-28 13:15:44.257  5645  5692 I jxcore-log: ok 230 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-28 13:15:44.257  5645  5692 I jxcore-log: 
,09-28 13:15:44.257  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 13:15:44.257  5645  5692 I jxcore-log: 
09-28 13:15:44.258  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 13:15:44.258  5645  5692 I jxcore-log: 
09-28 13:15:44.258  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 13:15:44.258  5645  5692 I jxcore-log: 
,09-28 13:15:44.261  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start listening for advertisements'
09-28 13:15:44.261  5645  5692 I jxcore-log: 
,09-28 13:15:44.263  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start update advertising and listening'
09-28 13:15:44.263  5645  5692 I jxcore-log: 
,09-28 13:15:44.267  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliWifiInfrastructure: 'listening 47652'
09-28 13:15:44.267  5645  5692 I jxcore-log: 
,09-28 13:15:44.269  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 13:15:44.269  5645  5692 I jxcore-log: 
,09-28 13:15:44.272  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 13:15:44.272  5645  5692 I jxcore-log: 
,09-28 13:15:44.272  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 13:15:44.272  5645  5692 I jxcore-log: 
,09-28 13:15:44.274  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 13:15:44.274  5645  5692 I jxcore-log: 
,09-28 13:15:44.275  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 13:15:44.275  5645  5692 I jxcore-log: 
,09-28 13:15:44.281  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 13:15:44.281  5645  5692 I jxcore-log: 
,09-28 13:15:44.283  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 13:15:44.283  5645  5692 I jxcore-log: 
,09-28 13:15:44.286  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 13:15:44.286  5645  5692 I jxcore-log: 
,09-28 13:15:44.286  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 13:15:44.286  5645  5692 I jxcore-log: 
09-28 13:15:44.287  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 13:15:44.287  5645  5692 I jxcore-log: 
,09-28 13:15:44.289  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start listening for advertisements'
09-28 13:15:44.289  5645  5692 I jxcore-log: 
,09-28 13:15:44.291  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start update advertising and listening'
09-28 13:15:44.291  5645  5692 I jxcore-log: 
,09-28 13:15:44.297  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliWifiInfrastructure: 'listening 43236'
09-28 13:15:44.297  5645  5692 I jxcore-log: 
,09-28 13:15:44.298  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 13:15:44.298  5645  5692 I jxcore-log: 
,09-28 13:15:44.301  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 13:15:44.301  5645  5692 I jxcore-log: 
,09-28 13:15:44.301  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 13:15:44.301  5645  5692 I jxcore-log: 
,09-28 13:15:44.303  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 13:15:44.303  5645  5692 I jxcore-log: 
,09-28 13:15:44.304  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 13:15:44.304  5645  5692 I jxcore-log: 
,09-28 13:15:44.308  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 13:15:44.308  5645  5692 I jxcore-log: 
,09-28 13:15:44.309  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 13:15:44.309  5645  5692 I jxcore-log: 
,09-28 13:15:44.312  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 13:15:44.312  5645  5692 I jxcore-log: 
,09-28 13:15:44.312  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 13:15:44.312  5645  5692 I jxcore-log: 
,09-28 13:15:44.313  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 13:15:44.313  5645  5692 I jxcore-log: 
,09-28 13:15:44.314  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start listening for advertisements'
09-28 13:15:44.314  5645  5692 I jxcore-log: 
,09-28 13:15:44.316  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start update advertising and listening'
09-28 13:15:44.316  5645  5692 I jxcore-log: 
,09-28 13:15:44.321  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliWifiInfrastructure: 'listening 42320'
09-28 13:15:44.321  5645  5692 I jxcore-log: 
,09-28 13:15:44.322  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 13:15:44.322  5645  5692 I jxcore-log: 
,09-28 13:15:44.326  5645  5692 I jxcore-log: ok 231 ThaliMobile.start was called once
09-28 13:15:44.326  5645  5692 I jxcore-log: 
,09-28 13:15:44.326  5645  5692 I jxcore-log: ok 232 ThaliMobile.start was called with 2 arguments
09-28 13:15:44.326  5645  5692 I jxcore-log: 
09-28 13:15:44.326  5645  5692 I jxcore-log: ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-28 13:15:44.326  5645  5692 I jxcore-log: 
,09-28 13:15:44.326  5645  5692 I jxcore-log: ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-28 13:15:44.326  5645  5692 I jxcore-log: 
09-28 13:15:44.327  5645  5692 I jxcore-log: ok 235 ThaliMobile.startListeningForAdvertisements was called once
09-28 13:15:44.327  5645  5692 I jxcore-log: 
,09-28 13:15:44.327  5645  5692 I jxcore-log: ok 236 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-28 13:15:44.327  5645  5692 I jxcore-log: 
09-28 13:15:44.327  5645  5692 I jxcore-log: ok 237 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-28 13:15:44.327  5645  5692 I jxcore-log: 
09-28 13:15:44.327  5645  5692 I jxcore-log: ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-28 13:15:44.327  5645  5692 I jxcore-log: 
09-28 13:15:44.327  5645  5692 I jxcore-log: ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-28 13:15:44.327  5645  5692 I jxcore-log: 
,09-28 13:15:44.327  5645  5692 I jxcore-log: ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-28 13:15:44.327  5645  5692 I jxcore-log: 
09-28 13:15:44.328  5645  5692 I jxcore-log: ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 13:15:44.328  5645  5692 I jxcore-log: 
09-28 13:15:44.328  5645  5692 I jxcore-log: ok 242 ThaliPullReplicationFromNotification.prototype.start was called once
09-28 13:15:44.328  5645  5692 I jxcore-log: 
,09-28 13:15:44.328  5645  5692 I jxcore-log: ok 243 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-28 13:15:44.328  5645  5692 I jxcore-log: 
09-28 13:15:44.328  5645  5692 I jxcore-log: ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 13:15:44.328  5645  5692 I jxcore-log: 
09-28 13:15:44.329  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 13:15:44.329  5645  5692 I jxcore-log: 
09-28 13:15:44.329  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 13:15:44.329  5645  5692 I jxcore-log: 
,09-28 13:15:44.331  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 13:15:44.331  5645  5692 I jxcore-log: 
09-28 13:15:44.332  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 13:15:44.332  5645  5692 I jxcore-log: 
,09-28 13:15:44.336  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 13:15:44.336  5645  5692 I jxcore-log: 
,09-28 13:15:44.337  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 13:15:44.337  5645  5692 I jxcore-log: 
,09-28 13:15:44.343  5645  5692 I jxcore-log: # teardown
09-28 13:15:44.343  5645  5692 I jxcore-log: 
,09-28 13:15:44.374  5645  5692 I jxcore-log: # setup
09-28 13:15:44.374  5645  5692 I jxcore-log: 
,09-28 13:15:44.445  5645  5692 I jxcore-log: # test write
09-28 13:15:44.445  5645  5692 I jxcore-log: 
,09-28 13:15:44.637  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-28 13:15:44.637  5645  5692 I jxcore-log: 
,09-28 13:15:44.639  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-28 13:15:44.639  5645  5692 I jxcore-log: 
,09-28 13:15:44.641  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'creating express pouchdb instance'
09-28 13:15:44.641  5645  5692 I jxcore-log: 
,09-28 13:15:44.664  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 13:15:44.664  5645  5692 I jxcore-log: 
,09-28 13:15:44.665  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 13:15:44.665  5645  5692 I jxcore-log: 
,09-28 13:15:44.665  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 13:15:44.665  5645  5692 I jxcore-log: 
,09-28 13:15:44.667  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start listening for advertisements'
09-28 13:15:44.667  5645  5692 I jxcore-log: 
,09-28 13:15:44.671  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'start update advertising and listening'
09-28 13:15:44.671  5645  5692 I jxcore-log: 
,09-28 13:15:44.677  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliWifiInfrastructure: 'listening 49660'
09-28 13:15:44.677  5645  5692 I jxcore-log: 
,09-28 13:15:44.681  5645  5692 I jxcore-log: 2016-09-28 17:15:44 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 13:15:44.681  5645  5692 I jxcore-log: 
,09-28 13:15:44.937   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:15:45.858  5645  5692 I jxcore-log: 2016-09-28 17:15:45 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-28 13:15:45.858  5645  5692 I jxcore-log: 
,09-28 13:15:45.938   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 13:15:46.053  5645  5692 I jxcore-log: 2016-09-28 17:15:46 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-28 13:15:46.053  5645  5692 I jxcore-log: 
,09-28 13:15:46.082  5645  5692 I jxcore-log: 2016-09-28 17:15:46 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-28 13:15:46.082  5645  5692 I jxcore-log: 
,09-28 13:15:46.237  5645  5692 E jxcore-log: Error in .on("change", function): { [AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.]
09-28 13:15:46.237  5645  5692 E jxcore-log:   name: 'AssertionError',
09-28 13:15:46.237  5645  5692 E jxcore-log:   actual: null,
09-28 13:15:46.237  5645  5692 E jxcore-log:   expected: true,
09-28 13:15:46.237  5645  5692 E jxcore-log:   operator: '==',
09-28 13:15:46.237  5645  5692 E jxcore-log:   message: 'If beacons werepreviously updated then there has to be a refresh timer for them.',
09-28 13:15:46.237  5645  5692 E jxcore-log:   stack: 'ok@assert.js:126:1\nThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:358:9\nemit@events.js:82:1' }
09-28 13:15:46.237  5645  5692 E jxcore-log: 
,09-28 13:15:46.270  5645  5692 I jxcore-log: # teardown
09-28 13:15:46.270  5645  5692 I jxcore-log: 
,09-28 13:15:46.588  5645  5692 I jxcore-log: 2016-09-28 17:15:46 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-28 13:15:46.588  5645  5692 I jxcore-log: 
,09-28 13:15:46.903  5645  5692 I jxcore-log: 2016-09-28 17:15:46 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-28 13:15:46.903  5645  5692 I jxcore-log: 
,09-28 13:15:47.023  5645  5692 I jxcore-log: 2016-09-28 17:15:47 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-28 13:15:47.023  5645  5692 I jxcore-log: 
,09-28 13:15:47.024  5645  5692 I jxcore-log: 2016-09-28 17:15:47 - DEBUG thaliReplicationPeerAction: 'Got error in update, waiting for main loop to detect and handle -  409 Document update conflict'
09-28 13:15:47.024  5645  5692 I jxcore-log: 
,09-28 13:15:47.098  5645  5692 I jxcore-log: 2016-09-28 17:15:47 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-28 13:15:47.098  5645  5692 I jxcore-log: 
,09-28 13:15:59.828   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 13:16:00.939   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:01.940   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:02.941   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:03.942   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:04.944   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:05.945   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 13:16:16.163  5645  5692 I jxcore-log: 2016-09-28 17:16:16 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
09-28 13:16:16.163  5645  5692 I jxcore-log: 
,09-28 13:16:16.211  5645  5692 I jxcore-log: 2016-09-28 17:16:16 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
09-28 13:16:16.211  5645  5692 I jxcore-log: 
,09-28 13:16:16.492  5645  5692 I jxcore-log: 2016-09-28 17:16:16 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
09-28 13:16:16.492  5645  5692 I jxcore-log: 
,09-28 13:16:19.829   929  2976 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 13:16:25.946   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:26.947   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:27.948   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:28.949   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:29.951   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 13:16:30.952   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 13:16:46.287  5645  5692 I jxcore-log: 2016-09-28 17:16:46 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-28 13:16:46.287  5645  5692 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-28 13:16:46.287  5645  5692 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-28 13:16:46.287  5645  5692 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-28 13:16:46.287  5645  5692 I jxcore-log:     at $9@timers.js:120:1
09-28 13:16:46.287  5645  5692 I jxcore-log: ''
09-28 13:16:46.287  5645  5692 I jxcore-log: 
,09-28 13:16:46.289  5645  5692 I jxcore-log: 2016-09-28 17:16:46 - DEBUG CoordinatedClient: 'test client failed'
09-28 13:16:46.289  5645  5692 I jxcore-log: 
,09-28 13:16:46.301  5645  5692 I jxcore-log: 2016-09-28 17:16:46 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-28 13:16:46.301  5645  5692 I jxcore-log: 
,09-28 13:16:46.309  5645  5692 I jxcore-log: 2016-09-28 17:16:46 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
09-28 13:16:46.309  5645  5692 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-28 13:16:46.309  5645  5692 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-28 13:16:46.309  5645  5692 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-28 13:16:46.309  5645  5692 I jxcore-log:     at $9@timers.js:120:1
09-28 13:16:46.309  5645  5692 I jxcore-log: ''
09-28 13:16:46.309  5645  5692 I jxcore-log: 
,09-28 13:16:46.310  5645  5692 I jxcore-log: 2016-09-28 17:16:46 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-28 13:16:46.310  5645  5692 I jxcore-log: 
,09-28 13:16:46.891  6033  6033 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-28 13:16:46.916  6033  6033 D AndroidRuntime: CheckJNI is OFF
,09-28 13:16:46.940  6033  6033 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-28 13:16:46.977  6033  6033 I Radio-JNI: register_android_hardware_Radio DONE
,09-28 13:16:46.993  6033  6033 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-28 13:16:47.006   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-28 13:16:47.007   929   942 I ActivityManager: Killing 5645:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-28 13:16:47.127   929   940 D GraphicsStats: Buffer count: 2
09-28 13:16:47.129   929  2977 D WifiService: Client connection lost with reason: 4
09-28 13:16:47.129   929  3768 I WindowState: WIN DEATH: Window{7826c1a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-28 13:16:47.172   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-28 13:16:47.173   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-28 13:16:47.173   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-28 13:16:47.173   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-28 13:16:47.173   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:16:47.173   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:16:47.173   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 13:16:47.173   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 13:16:47.174   929   942 I ActivityManager:   Force finishing activity ActivityRecord{c28314f u0 com.test.thalitest/.MainActivity t2}
,09-28 13:16:47.176   929   954 I art     : Starting a blocking GC Explicit
,09-28 13:16:47.182   929  3878 W ActivityManager: Spurious death for ProcessRecord{f71fb60 0:com.test.thalitest/u0a77}, curProc for 5645: null
,09-28 13:16:47.186   929   947 W WindowManager: Attempted to add application window with unknown token Token{e3d40dc ActivityRecord{c28314f u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
09-28 13:16:47.186   929   947 W WindowManager: Token{e3d40dc ActivityRecord{c28314f u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{e3d40dc ActivityRecord{c28314f u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-28 13:16:47.186   929   947 W WindowManager: view not successfully added to wm, removing view
,09-28 13:16:47.187   929   947 W WindowManager: Exception when adding starting window
09-28 13:16:47.187   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{b476bdb V.E...... R.....ID 0,0-0,0} not attached to window manager
09-28 13:16:47.187   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-28 13:16:47.187   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-28 13:16:47.187   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-28 13:16:47.187   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-28 13:16:47.187   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-28 13:16:47.187   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:16:47.187   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:16:47.187   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 13:16:47.187   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 13:16:47.284   929   954 I art     : Explicit concurrent mark sweep GC freed 94919(6MB) AllocSpace objects, 51(2MB) LOS objects, 33% free, 29MB/43MB, paused 1.923ms total 107.330ms
,09-28 13:16:47.302   929   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-28 13:16:47.306  6033  6033 I art     : System.exit called, status: 0
09-28 13:16:47.306  6033  6033 I AndroidRuntime: VM exiting with result code 0.
,09-28 13:16:47.328   929   954 I ActivityManager: Start proc 6043:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-28 13:16:47.328   929   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-28 13:16:47.334   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-28 13:16:47.338  5922  5922 D BluetoothMapAppObserver: onReceive
,09-28 13:16:47.338  5922  5922 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-28 13:16:47.343   929  2942 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-28 13:16:47.347  4076  4174 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-28 13:16:47.348  3664  3664 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-28 13:16:47.371  3664  6055 I Keyboard.Facilitator.DecoderInitializer: run()
,09-28 13:16:47.373  3394  6056 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-28 13:16:47.394  3789  3789 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-28 13:16:47.404  3570  3570 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-28 13:16:47.404  3570  3570 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-28 13:16:47.423   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-28 13:16:47.445  3664  6055 I Decoder : createOrResetDecoder
,09-28 13:16:47.448    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 13:16:47.458    17    17 W kworker/2:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 13:16:47.468  3685  6062 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-28 13:16:47.468  3685  6062 D AccountUtils: Clearing selected account for com.test.thalitest
,09-28 13:16:47.472    17    17 W kworker/2:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 13:16:47.486  3570  3570 I ConfigService: onCreate
,09-28 13:16:47.487  3394  3415 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjA5BAFF998) - 
,09-28 13:16:47.489  3570  6065 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-28 13:16:47.489  3570  6065 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-28 13:16:47.490  3570  6065 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-28 13:16:47.493  3570  6065 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-28 13:16:47.502  3664  6055 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-28 13:16:47.514  3685  6062 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-28 13:16:47.537  3685  6062 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:16:47.537  3685  6062 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:16:47.537  3685  6062 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 13:16:47.538  3685  6062 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,--------- beginning of crash
09-28 13:16:47.577  3394  3415 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-28 13:16:47.577  3394  3415 E AndroidRuntime: Process: android.process.acore, PID: 3394
09-28 13:16:47.577  3394  3415 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-28 13:16:47.577  3394  3415 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 13:16:47.590  3685  3685 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-28 13:16:47.590  3685  3685 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-28 13:16:47.595  3685  3685 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-28 13:16:47.595  3685  3685 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-28 13:16:47.621  4943  6072 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-28 13:16:47.635   929   940 I ActivityManager: Start proc 6076:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-28 13:16:47.666  3394  3415 I Process : Sending signal. PID: 3394 SIG: 9
,09-28 13:16:47.685  3685  6071 W BaseAppContext: Using Auth Proxy for data requests.
,09-28 13:16:47.691  4943  6072 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-28 13:16:47.708   929  3779 I ActivityManager: Start proc 6081:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-28 13:16:47.713  3685  6071 W BaseAppContext: Using Auth Proxy for data requests.
09-28 13:16:47.723  3685  3685 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-28 13:16:47.737  3685  6087 I GMPM-SVC: App measurement is starting up
,09-28 13:16:47.740  3685  6087 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-28 13:16:47.740  3685  6087 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-28 13:16:47.872   386   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
