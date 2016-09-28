#### Test 8693049090de6dc_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of system
09-28 07:47:59.779   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-28 07:48:01.502   567   567 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 07:48:01.502   567   567 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-28 07:48:01.816  5540  5540 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-28 07:48:01.822  5540  5540 D AndroidRuntime: CheckJNI is OFF
09-28 07:48:01.854  5540  5540 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-28 07:48:01.891  5540  5540 I Radio-JNI: register_android_hardware_Radio DONE
09-28 07:48:01.906  5540  5540 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-28 07:48:01.910   929   940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-28 07:48:01.951   929   940 I ActivityManager: Start proc 5549:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-28 07:48:01.962  5540  5540 D AndroidRuntime: Shutting down VM
,09-28 07:48:02.300   929  3750 I WindowManager: Screenshot max retries 4 of Token{9c269e8 ActivityRecord{60b670b u0 com.test.thalitest/.MainActivity t2}} appWin=Window{cd7ac83 u0 Starting com.test.thalitest} drawState=4
,09-28 07:48:02.388  5549  5549 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-28 07:48:02.422  5549  5549 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-28 07:48:02.444  5549  5549 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 9625-9643)
,09-28 07:48:02.445  5549  5549 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-28 07:48:02.462  5549  5549 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d311280}
,09-28 07:48:02.462  5549  5549 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-28 07:48:02.462  5549  5549 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-28 07:48:02.466  5549  5549 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-28 07:48:02.467  5549  5549 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-28 07:48:02.500  5549  5549 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-28 07:48:02.513  5549  5549 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-28 07:48:02.513  5549  5549 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-28 07:48:02.513  5549  5549 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-28 07:48:02.513  5549  5549 I Adreno  : Build Date                       : 12/06/15
09-28 07:48:02.513  5549  5549 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-28 07:48:02.513  5549  5549 I Adreno  : Local Branch                     : mybranch17112971
09-28 07:48:02.513  5549  5549 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-28 07:48:02.513  5549  5549 I Adreno  : Remote Branch                    : NONE
09-28 07:48:02.513  5549  5549 I Adreno  : Reconstruct Branch               : NOTHING
,09-28 07:48:02.545   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b07556:true
,09-28 07:48:02.580  3864  3864 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33946]" dev="sockfs" ino=33946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 07:48:02.580  3864  3864 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33946]" dev="sockfs" ino=33946 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 07:48:02.591  5549  5549 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-28 07:48:02.599  5549  5549 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-28 07:48:02.623   409   409 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33023]" dev="sockfs" ino=33023 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 07:48:02.627  5549  5586 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
09-28 07:48:02.623   409   409 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33023]" dev="sockfs" ino=33023 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-28 07:48:02.630  3104  3104 W Binder_4: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[16054]" dev="sockfs" ino=16054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 07:48:02.630  3104  3104 W Binder_4: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[16054]" dev="sockfs" ino=16054 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-28 07:48:02.635  5549  5573 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-28 07:48:02.653  5549  5586 I OpenGLRenderer: Initialized EGL, version 1.4
,09-28 07:48:02.724   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +420ms (total +798ms)
,09-28 07:48:02.771  5549  5549 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5549
,09-28 07:48:02.859  5549  5549 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-28 07:48:02.981  5549  5588 D jxcore_app_log: JniHelper::setJavaVM(0xf503c000), pthread_self() = -583010000
,09-28 07:48:02.985  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-28 07:48:02.985  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-28 07:48:02.985  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-28 07:48:02.985  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-28 07:48:02.985  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-28 07:48:02.985  5549  5588 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56ba3b1 added. We now have 1 listener(s)
,09-28 07:48:02.987  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-28 07:48:02.988  5549  5588 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:48:02.988  5549  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 07:48:02.988  5549  5588 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-28 07:48:02.990  5549  5588 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c1e004 added. We now have 1 listener(s)
09-28 07:48:02.990  5549  5588 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:48:02.995   929  2926 D WifiService: New client listening to asynchronous messages
09-28 07:48:02.995  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 07:48:02.995  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-28 07:48:02.995  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-28 07:48:02.995  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-28 07:48:02.995  5549  5588 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-28 07:48:02.998  5549  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:48:02.998  5549  5588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-28 07:48:03.002  5549  5588 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:03.002  5549  5588 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:03.003  5549  5588 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-28 07:48:03.003  5549  5588 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:48:03.003  5549  5588 I io.jxcore.node.LifeCycleMonitor: start: OK
09-28 07:48:03.007  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:03.013  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:03.018  5549  5549 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-28 07:48:03.340  5549  5595 W jxcore-log: Initializing JXcore engine
09-28 07:48:03.340  5549  5595 W jxcore-log: JXcore engine is ready
,09-28 07:48:03.359  5549  5558 I art     : Background sticky concurrent mark sweep GC freed 86216(8MB) AllocSpace objects, 18(1892KB) LOS objects, 26% free, 24MB/32MB, paused 2.216ms total 107.684ms
,09-28 07:48:03.363  5595  5595 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11796 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-28 07:48:03.363  5595  5595 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13348]" dev="sockfs" ino=13348 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-28 07:48:03.363  5595  5595 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-28 07:48:03.363  5595  5595 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33003]" dev="sockfs" ino=33003 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-28 07:48:03.373  5549  5595 W jxcore-log: Starting JXcore engine
,09-28 07:48:03.427  5549  5595 W jxcore-log: Platform android
09-28 07:48:03.427  5549  5595 W jxcore-log: 
,09-28 07:48:03.428  5549  5595 W jxcore-log: Process ARCH arm
09-28 07:48:03.428  5549  5595 W jxcore-log: 
,09-28 07:48:03.536  5549  5595 I jxcore-log: JXcore Cordova bridge is ready!
09-28 07:48:03.536  5549  5595 I jxcore-log: 
,09-28 07:48:03.537  5549  5595 W jxcore-log: JXcore engine is started
,09-28 07:48:03.541  5549  5588 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-28 07:48:03.547  5549  5549 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-28 07:48:04.063   929  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 07:48:11.503   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:12.505   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:13.082  5549  5595 I jxcore-log: 2016-09-28 11:48:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 07:48:13.082  5549  5595 I jxcore-log: 
,09-28 07:48:13.084  5549  5595 I jxcore-log: 2016-09-28 11:48:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 07:48:13.084  5549  5595 I jxcore-log: 
,09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:13.088  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:48:13.089  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:48:13.091  5549  5595 I jxcore-log: 2016-09-28 11:48:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 07:48:13.091  5549  5595 I jxcore-log: 
,09-28 07:48:13.093  5549  5595 I jxcore-log: 2016-09-28 11:48:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 07:48:13.093  5549  5595 I jxcore-log: 
,09-28 07:48:13.341  5549  5595 I jxcore-log: 2016-09-28 11:48:13 - DEBUG UnitTest_app: 'Running unit tests'
09-28 07:48:13.341  5549  5595 I jxcore-log: 
,09-28 07:48:13.342  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:48:13.342  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a838c29 added. We now have 2 listener(s)
09-28 07:48:13.343  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:48:13.343  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 07:48:13.343  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:48:13.343  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:48:13.343  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f6d5bae added. We now have 2 listener(s)
,09-28 07:48:13.343  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:48:13.344  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 07:48:13.346  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:13.349  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:13.349  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:13.350  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:48:13.350  5549  5595 D executeNativeTests: Running unit tests
,09-28 07:48:13.355  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:13.362  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:13.387  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 07:48:13.387  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c added. We now have 3 listener(s)
,09-28 07:48:13.388  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 07:48:13.388  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:48:13.388  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:48:13.388  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 07:48:13.388  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 added. We now have 3 listener(s)
09-28 07:48:13.388  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:48:13.388  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 07:48:13.390  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:13.392  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:48:13.393  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:48:13.393  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:48:13.394  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-28 07:48:13.395  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 07:48:13.395  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 07:48:13.395  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-28 07:48:13.395  5549  5595 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-28 07:48:13.395  5549  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 07:48:13.395  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 07:48:13.395  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 07:48:13.396  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 07:48:13.396  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 07:48:13.396  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 07:48:13.396  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:13.396  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:13.396  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:13.396  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.396  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 07:48:13.396  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:13.396  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:48:13.396  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c removed from the list
09-28 07:48:13.397  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:13.397  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 removed from the list
,09-28 07:48:13.398  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:13.404  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:13.405  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:13.405  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:13.405  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.405  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:13.406  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:13.406  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:13.406  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:13.406  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:13.407  5549  5595 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-28 07:48:13.407  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:13.407  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:13.407  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:13.407  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:13.407  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.407  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:13.407  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 07:48:13.407  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:13.407  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:13.407  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:13.407  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:13.407  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.407  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:13.407  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.407  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:13.408  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:13.408  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:13.408  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:13.408  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 07:48:13.410  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 07:48:13.411  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 07:48:13.411  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:13.411  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:13.411  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:13.411  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:13.411  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.411  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:13.411  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:13.412  5549  5595 E org.thali,project.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:13.412  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:13.412  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:13.412  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:13.412  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.412  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:13.412  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:13.412  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:13.412  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:13.412  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:13.412  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:13.412  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:13.413  5549  5595 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 07:48:13.413  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:13.415  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:13.416  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:13.416  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:48:13.416  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:48:13.417  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 07:48:13.417  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 07:48:13.417  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:48:13.417  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 07:48:13.423  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:13.425  5549  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 07:48:13.425  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 07:48:13.427  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:13.430  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-28 07:48:13.430  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 07:48:13.431  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 07:48:13.432  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-28 07:48:13.433  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-28 07:48:13.433  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 07:48:13.433  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 07:48:13.433  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 07:48:13.434  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 07:48:13.434  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 07:48:13.434  5549  5595 D BluetoothAdapter: STATE_ON
09-28 07:48:13.436  4556  4767 D BtGatt.GattService: registerClient() - UUID=a3bcf2fd-5931-4d7d-a64f-5d4b288d9229
09-28 07:48:13.437  4556  4618 D BtGatt.GattService: onClientRegistered() - UUID=a3bcf2fd-5931-4d7d-a64f-5d4b288d9229, clientIf=5
09-28 07:48:13.438  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 07:48:13.439  4556  4572 D BtGatt.GattService: start scan with filters
09-28 07:48:13.444  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 07:48:13.444  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 07:48:13.444  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:48:13.444  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 07:48:13.444  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 07:48:13.444  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 07:48:13.444  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 07:48:13.444  4556  4621 D BtGatt.ScanManager: handling starting scan
09-28 07:48:13.445  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 07:48:13.445  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 07:48:13.446  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 07:48:13.446  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 07:48:13.447  5549  5595 I io.jxcore.node.ConnectionHelper: start: OK
09-28 07:48:13.449  4556  4621 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:13.457  4556  4618 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 07:48:13.457  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:13.457  4556  4621 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 07:48:13.464  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 07:48:13.464  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:13.465  4556  4621 D BtGatt.ScanManager: Starting BLE batch scan
09-28 07:48:13.465  4556  4621 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 07:48:13.477  4556  4618 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 07:48:13.477  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:13.484  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 07:48:13.484  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:48:13.505   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:13.948  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-28 07:48:13.948  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 07:48:13.948  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 07:48:14.506   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:14.887   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 07:48:15.507   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:16.508   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 07:48:17.912   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 07:48:18.451  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:18.451  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:48:18.452  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 07:48:18.452  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:18.452  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 07:48:18.452  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:18.452  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 07:48:18.452  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 07:48:18.452  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-28 07:48:18.452  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 07:48:18.453  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 07:48:18.453  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 07:48:18.454  5549  5595 D BluetoothAdapter: STATE_ON
09-28 07:48:18.455  4556  4767 D BtGatt.GattService: stopScan() - queue size =1
09-28 07:48:18.456  4556  4572 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 07:48:18.458  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 07:48:18.458  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-28 07:48:18.458  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 07:48:18.458  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-28 07:48:18.458  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,09-28 07:48:18.458  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 07:48:18.459  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 07:48:18.459  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 07:48:18.460  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:48:18.460  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 07:48:18.460  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
,09-28 07:48:18.460  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 07:48:18.461  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 07:48:18.462  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:48:18.463  4556  4556 D BtGatt.ScanManager: awakened up at time 235661
,09-28 07:48:18.463  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:18.463  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:18.463  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:48:18.463  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 07:48:18.463  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:18.464  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:18.464  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:18.464  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:48:18.464  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:18.464  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:18.464  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:48:18.464  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:18.473  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 07:48:18.474  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:18.474  4556  4621 D BtGatt.ScanManager: stopping BLe Batch
,09-28 07:48:18.483  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 07:48:18.483  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:18.484  4556  4621 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 07:48:18.505  4556  4618 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-28 07:48:18.505  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:48:18.506  4556  4618 D BtGatt.GattService: current time is 235704732390
,09-28 07:48:18.506  4556  4618 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -76, 35, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -73, 58, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -70, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -79, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 07:48:18.508  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-28 07:48:18.509  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 07:48:18.509  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 07:48:18.510  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-28 07:48:18.510  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-28 07:48:18.965  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 07:48:21.509   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:22.511   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:23.468  5549  5595 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-28 07:48:23.473  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:23.484  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:48:23.489  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:23.490  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:48:23.490  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:48:23.490  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 07:48:23.491  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 07:48:23.491  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:48:23.491  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 07:48:23.497  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:23.499  5549  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 07:48:23.499  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 07:48:23.503  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:23.506  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 07:48:23.508  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 07:48:23.508  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 07:48:23.511   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:23.514  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-28 07:48:23.515  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 07:48:23.515  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 07:48:23.515  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 07:48:23.515  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 07:48:23.516  5549  5595 D BluetoothAdapter: STATE_ON
,09-28 07:48:23.520  4556  4767 D BtGatt.GattService: registerClient() - UUID=11c9d3a1-397b-465a-93cb-b938293e9602
,09-28 07:48:23.521  4556  4618 D BtGatt.GattService: onClientRegistered() - UUID=11c9d3a1-397b-465a-93cb-b938293e9602, clientIf=5
09-28 07:48:23.521  5549  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 07:48:23.522  4556  4787 D BtGatt.GattService: start scan with filters
,09-28 07:48:23.527  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 07:48:23.527  4556  4621 D BtGatt.ScanManager: handling starting scan
09-28 07:48:23.527  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 07:48:23.527  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:48:23.528  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 07:48:23.528  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,09-28 07:48:23.528  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 07:48:23.528  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 07:48:23.533  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 07:48:23.534  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 07:48:23.534  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 07:48:23.537  4556  4618 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 07:48:23.537  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:23.537  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 07:48:23.538  4556  4621 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 07:48:23.542  5549  5595 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 07:48:23.547  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:23.547  5549  5595 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-28 07:48:23.547  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 07:48:23.547  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:23.547  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:23.547  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 07:48:23.548  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:23.548  4556  4621 D BtGatt.ScanManager: Starting BLE batch scan
09-28 07:48:23.548  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 07:48:23.548  4556  4621 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 07:48:23.548  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:23.548  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 07:48:23.548  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 07:48:23.548  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 07:48:23.548  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 07:48:23.548  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 07:48:23.548  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 07:48:23.550  5549  5595 D BluetoothAdapter: STATE_ON
,09-28 07:48:23.551  4556  4767 D BtGatt.GattService: stopScan() - queue size =1
09-28 07:48:23.552  4556  4787 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 07:48:23.552  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 07:48:23.552  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 07:48:23.552  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-28 07:48:23.552  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:48:23.553  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 07:48:23.553  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,09-28 07:48:23.553  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 07:48:23.553  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 07:48:23.554  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:48:23.555  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-28 07:48:23.555  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 07:48:23.555  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 07:48:23.555  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 07:48:23.556  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:48:23.558  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:23.558  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:48:23.558  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:23.558  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:48:23.558  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:48:23.558  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:48:23.558  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:23.558  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:23.559  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:23.559  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:23.559  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:23.559  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:23.559  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:23.559  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:23.560  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:23.561  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:23.561  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:23.561  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:23.562  5549  5595 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-28 07:48:23.564  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:48:23.565  4556  4618 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 07:48:23.565  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:23.570  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:23.572  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 07:48:23.572  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:23.572  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:23.572  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 07:48:23.573  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:48:23.573  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 07:48:23.573  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 07:48:23.573  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:48:23.573  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-28 07:48:23.577  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:23.580  5549  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 07:48:23.580  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 07:48:23.580  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:23.581  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 07:48:23.581  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:23.581  4556  4621 D BtGatt.ScanManager: stopping BLe Batch
,09-28 07:48:23.586  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 07:48:23.587  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 07:48:23.587  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 07:48:23.588  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 07:48:23.589  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:23.589  4556  4621 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 07:48:23.590  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 07:48:23.591  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 07:48:23.591  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 07:48:23.591  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-28 07:48:23.591  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 07:48:23.591  5549  5595 D BluetoothAdapter: STATE_ON
,09-28 07:48:23.594  4556  4618 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 07:48:23.594  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:48:23.594  4556  4767 D BtGatt.GattService: registerClient() - UUID=0d2999d2-e233-4de3-a0a8-b595c030ab57
09-28 07:48:23.595  4556  4618 D BtGatt.GattService: onClientRegistered() - UUID=0d2999d2-e233-4de3-a0a8-b595c030ab57, clientIf=5
09-28 07:48:23.595  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 07:48:23.596  4556  4570 D BtGatt.GattService: start scan with filters
,09-28 07:48:23.598  4556  4621 D BtGatt.ScanManager: handling starting scan
09-28 07:48:23.599  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-28 07:48:23.599  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 07:48:23.599  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:48:23.599  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 07:48:23.599  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 07:48:23.599  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 07:48:23.599  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 07:48:23.602  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 07:48:23.602  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 07:48:23.602  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 07:48:23.604  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 07:48:23.604  4556  4618 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 07:48:23.604  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:23.604  4556  4621 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 07:48:23.606  5549  5595 I io.jxcore.node.ConnectionHelper: start: OK
,09-28 07:48:23.610  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 07:48:23.610  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:48:23.610  4556  4621 D BtGatt.ScanManager: Starting BLE batch scan
09-28 07:48:23.610  4556  4621 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-28 07:48:23.619  4556  4618 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 07:48:23.619  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:48:23.624  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 07:48:23.624  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:48:23.970   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 07:48:24.064   929  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 07:48:24.103  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-28 07:48:24.104  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 07:48:24.104  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 07:48:24.513   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:25.514   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:26.514   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 07:48:26.991   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 07:48:26.998   929  2927 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-28 07:48:28.607  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 07:48:28.607  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:48:28.607  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 07:48:28.607  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:28.607  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 07:48:28.608  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:28.608  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 07:48:28.608  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 07:48:28.608  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 07:48:28.608  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 07:48:28.609  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 07:48:28.609  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 07:48:28.611  5549  5595 D BluetoothAdapter: STATE_ON
,09-28 07:48:28.612  4556  4570 D BtGatt.GattService: stopScan() - queue size =1
09-28 07:48:28.614  4556  4787 D BtGatt.GattService: unregisterClient() - clientIf=5
09-28 07:48:28.615  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 07:48:28.615  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 07:48:28.615  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 07:48:28.615  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:48:28.616  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 07:48:28.616  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 07:48:28.616  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 07:48:28.616  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 07:48:28.619  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:48:28.620  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 07:48:28.620  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 07:48:28.620  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 07:48:28.620  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 07:48:28.621  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:48:28.623  4556  4556 D BtGatt.ScanManager: awakened up at time 245822
09-28 07:48:28.624  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:48:28.625  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:48:28.625  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 07:48:28.628  4556  4618 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 07:48:28.628  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:28.628  4556  4621 D BtGatt.ScanManager: stopping BLe Batch
,09-28 07:48:28.635  4556  4618 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-28 07:48:28.635  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:28.635  4556  4621 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 07:48:28.652  4556  4618 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-28 07:48:28.652  4556  4618 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:48:28.653  4556  4618 D BtGatt.GattService: current time is 245851561045
09-28 07:48:28.653  4556  4618 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -77, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -78, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -79, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -71, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -78, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-28 07:48:28.653  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-28 07:48:28.653  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-28 07:48:28.653  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
09-28 07:48:28.654  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-28 07:48:28.654  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-28 07:48:28.654  4556  4618 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-28 07:48:29.126  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 07:48:29.126  5549  5549 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:29.126  5549  5549 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 07:48:30.020   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 07:48:30.026   929  2927 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-28 07:48:33.625  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 07:48:33.625  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:33.626  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.626  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.626  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:33.626  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:48:33.626  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.627  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.627  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.627  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.627  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.627  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:33.630  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:33.630  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.633  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.634  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.634  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:33.634  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.635  5549  5595 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-28 07:48:33.638  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.638  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:48:33.639  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.639  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.639  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.639  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.639  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.639  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.640  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.640  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.640  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.640  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.640  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.640  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:33.640  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.643  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.643  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.643  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.643  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:33.645  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 07:48:33.645  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.645  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:33.645  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.645  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.645  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.645  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:33.645  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.645  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.646  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.646  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.646  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.646  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.646  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.646  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.646  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:33.647  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.648  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.648  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.648  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.649  5549  5595 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-28 07:48:33.649  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.649  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:48:33.649  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.649  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.650  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.650  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.650  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.650  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.650  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.650  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.650  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 07:48:33.650  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.650  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.650  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.650  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.652  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.652  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.652  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.652  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:33.653  5549  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-28 07:48:33.653  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.654  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:33.654  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.654  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.654  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.654  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.654  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.654  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.654  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.654  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:33.654  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.654  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.655  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.655  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.655  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:33.656  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.656  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.656  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.656  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.657  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-28 07:48:33.658  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 07:48:33.658  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 07:48:33.658  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 07:48:33.658  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 07:48:33.658  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 07:48:33.658  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-28 07:48:33.658  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 07:48:33.659  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-28 07:48:33.659  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.659  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:48:33.659  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.659  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.659  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.659  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.659  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.659  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.659  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.660  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.660  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.660  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:33.660  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.660  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.660  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.662  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.662  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.663  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.663  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.664  5549  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 07:48:33.664  5549  5595 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 07:48:33.664  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-28 07:48:33.667  5549  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 07:48:33.667  5549  5595 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-28 07:48:33.668  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-28 07:48:33.669  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-28 07:48:33.670  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-28 07:48:33.670  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-28 07:48:33.670  5549  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-28 07:48:33.670  5549  5595 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-28 07:48:33.670  5549  5595 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-28 07:48:33.670  5549  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 07:48:33.670  5549  5595 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 07:48:33.670  5549  5595 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-28 07:48:33.670  5549  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 07:48:33.671  5549  5595 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-28 07:48:33.671  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-28 07:48:33.675  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-28 07:48:33.676  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-28 07:48:33.676  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-28 07:48:33.677  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-28 07:48:33.677  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-28 07:48:33.677  5549  5595 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-28 07:48:33.677  5549  5595 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-28 07:48:33.677  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-28 07:48:33.677  5549  5595 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-28 07:48:33.677  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-28 07:48:33.677  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-28 07:48:33.677  5549  5596 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,09-28 07:48:33.679  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.679  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:33.679  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.679  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.679  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.679  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.679  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.680  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-28 07:48:33.680  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.680  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.681  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.681  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.681  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.681  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.681  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:33.681  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.681  5549  5597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-28 07:48:33.681  5549  5596 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
09-28 07:48:33.681  5549  5596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 07:48:33.680  4572  4572 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28634]" dev="sockfs" ino=28634 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-28 07:48:33.680  4572  4572 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28634]" dev="sockfs" ino=28634 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 07:48:33.682  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.682  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.682  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.682  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.683  5549  5595 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-28 07:48:33.684  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.684  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:33.684  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.684  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.684  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.684  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:33.684  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.684  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.684  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.684  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.684  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.684  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.684  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.685  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.685  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:33.686  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.686  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.686  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:33.686  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.687  5549  5595 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-28 07:48:33.687  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.687  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:33.687  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.687  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.687  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.687  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.687  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.687  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.687  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.687  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.687  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.687  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.688  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.688  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:33.688  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.689  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.689  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.689  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.689  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.690  5549  5595 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-28 07:48:33.690  5549  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-28 07:48:33.690  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 07:48:33.691  5549  5595 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-28 07:48:33.691  5549  5595 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-28 07:48:33.691  5549  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-28 07:48:33.691  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 07:48:33.691  5549  5595 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-28 07:48:33.691  5549  5595 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-28 07:48:33.691  5549  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-28 07:48:33.691  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 07:48:33.691  5549  5595 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-28 07:48:33.691  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:33.691  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:33.691  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:33.692  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.692  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.692  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.692  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.692  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.692  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.692  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.692  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.692  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:33.692  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.692  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.692  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.693  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:33.693  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:33.693  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.693  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:33.694  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:33.694  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.694  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:33.694  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:33.694  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:33.694  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:33.694  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:33.694  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:33.694  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:33.694  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:36.515   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:37.516   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:38.517   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:38.695  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:38.695  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.695  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:38.695  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.696  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:38.696  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:38.696  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:38.696  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:38.696  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:48:38.697  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:38.697  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:38.697  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.697  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:38.697  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:38.697  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:38.697  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:38.698  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.698  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:38.698  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.698  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:38.698  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.698  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.702  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:38.702  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:38.702  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:38.703  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.706  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-28 07:48:38.707  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:48:38.710  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-28 07:48:38.712  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-28 07:48:38.713  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-28 07:48:38.713  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-28 07:48:38.713  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-28 07:48:38.714  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 07:48:38.714  5549  5549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-28 07:48:38.714  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,09-28 07:48:38.716  4767  4767 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31239]" dev="sockfs" ino=31239 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 07:48:38.715  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:38.715  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-28 07:48:38.715  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-28 07:48:38.715  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-28 07:48:38.715  5549  5598 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 07:48:38.715  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:38.715  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-28 07:48:38.716  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-28 07:48:38.716  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:38.716  5549  5549 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-28 07:48:38.716  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:38.716  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 07:48:38.716  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 07:48:38.716  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-28 07:48:38.716  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.716  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.718  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:48:38.719  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:38.719  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:48:38.719  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:38.719  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:48:38.719  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:48:38.719  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:38.719  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 07:48:38.719  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:38.719  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.719  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.719  5549  5598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-28 07:48:38.720  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-28 07:48:38.720  5549  5598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-28 07:48:38.720  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
,09-28 07:48:38.720  5549  5598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-28 07:48:38.720  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:38.720  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.716  4767  4767 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31239]" dev="sockfs" ino=31239 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-28 07:48:38.720  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:38.720  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.720  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.720  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:38.720  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.720  5549  5549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-28 07:48:38.721  5549  5549 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:38.722  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:38.722  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:38.722  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:38.722  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.724  5549  5595 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-28 07:48:38.725  5549  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-28 07:48:38.725  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-28 07:48:38.725  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 07:48:38.725  5549  5595 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-28 07:48:38.725  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:38.725  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:48:38.726  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:38.726  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:38.726  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.726  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.726  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:38.726  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
,09-28 07:48:38.726  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:38.726  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.726  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:38.726  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.727  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.727  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.728  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:48:38.733  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:38.733  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:38.734  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:38.734  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
,09-28 07:48:38.742  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 07:48:38.742  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:38.742  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:38.742  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:48:38.742  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.742  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.742  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:38.743  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:38.743  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:38.743  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.743  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:38.743  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:38.743  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.743  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.743  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.744  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:48:38.744  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:38.744  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:38.745  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.746  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:48:38.746  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:48:38.746  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:48:38.746  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-28 07:48:38.746  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.746  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.746  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:48:38.746  5549  5595 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d3bb50c not in the list
09-28 07:48:38.746  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:38.746  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.746  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:38.746  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.746  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.746  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:38.747  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:38.748  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 07:48:38.748  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:48:38.748  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:38.748  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ddee55 not in the list
09-28 07:48:38.749  5549  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-28 07:48:38.749  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 07:48:38.749  5549  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-28 07:48:38.749  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-28 07:48:38.749  5549  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-28 07:48:38.750  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-28 07:48:38.752  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-28 07:48:38.752  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-28 07:48:38.753  5549  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-28 07:48:38.754  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 07:48:38.754  5549  5595 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-28 07:48:38.754  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-28 07:48:38.754  5549  5595 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-28 07:48:38.754  5549  5595 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-28 07:48:38.755  5549  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-28 07:48:38.755  5549  5595 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-28 07:48:38.756  5549  5595 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-28 07:48:38.756  5549  5595 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-28 07:48:38.756  5549  5595 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-28 07:48:38.756  5549  5595 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-28 07:48:38.757  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:48:38.757  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1d98f2f added. We now have 3 listener(s)
09-28 07:48:38.757  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:48:38.759  5549  5595 D BluetoothAdapter: enable(): BT is already enabled..!
09-28 07:48:38.760   929  3360 D WifiService: setWifiEnabled: true pid=5549, uid=10077
09-28 07:48:38.760   929  3360 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 07:48:38.811  4556  4759 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-28 07:48:38.812  4556  4765 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-28 07:48:38.812  5549  5596 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
09-28 07:48:38.812  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-28 07:48:38.812  5549  5596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,09-28 07:48:39.221  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 07:48:39.518   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:40.519   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:41.520   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 07:48:43.766  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-28 07:48:43.766  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c793c added. We now have 4 listener(s)
09-28 07:48:43.766  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:48:43.779  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:48:43.779  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9c793c removed from the list
09-28 07:48:43.779  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 07:48:43.779  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:48:43.780  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:43.782  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:48:43.783  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ff816c5 added. We now have 4 listener(s)
,09-28 07:48:43.783  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:48:43.785  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:48:43.785  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ff816c5 removed from the list
09-28 07:48:43.786  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:48:43.786  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-28 07:48:43.786  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:48:43.787  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:48:43.787  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4efe81a added. We now have 4 listener(s)
09-28 07:48:43.788  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:48:43.793   929  3755 D WifiService: setWifiEnabled: false pid=5549, uid=10077
09-28 07:48:43.793   929  3755 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 07:48:43.802   929  2925 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-28 07:48:43.802   929  2925 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-28 07:48:43.802   929  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 07:48:43.803   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:48:43.808  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:48:43.808  4556  4614 D BluetoothAdapterState: Current state: ON, message: 23
09-28 07:48:43.808  4556  4614 D BluetoothAdapterProperties: Setting state to 13
09-28 07:48:43.808  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 07:48:43.809  4556  4614 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 07:48:43.813  4556  4614 I BluetoothAdapterState: Entering PendingCommandState
09-28 07:48:43.814  4556  4556 D BluetoothMapService: onReceive
09-28 07:48:43.814  4556  4556 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 07:48:43.814  4556  4556 D BluetoothMapService: STATE_TURNING_OFF
09-28 07:48:43.815  4556  4556 D BluetoothMapService: MAP Service closeService in
09-28 07:48:43.815  4556  4556 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 07:48:43.815  4556  4556 D ObexServerSockets0: shutdown(block = true)
,09-28 07:48:43.816  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 07:48:43.816  4556  4556 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 07:48:43.816  4556  4765 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 07:48:43.816  4556  4788 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-28 07:48:43.817  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:43.817  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:43.817  4556  4789 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 07:48:43.818  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.818  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:43.818  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:48:43.818  4556  4556 I BtOppRfcommListener: stopping Accept Thread
,09-28 07:48:43.819  4556  5224 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 07:48:43.819  4556  5224 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 07:48:43.822   510   921 D CommandListener: Clearing all IP addresses on wlan0
09-28 07:48:43.824  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:43.825   929  5299 D DhcpClient: Clearing IP address
09-28 07:48:43.827  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:43.829   510   921 D CommandListener: Setting iface cfg
09-28 07:48:43.830   929   942 I ActivityManager: Start proc 5602:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-28 07:48:43.831  4556  4618 D BluetoothAdapterProperties: Scan Mode:20
09-28 07:48:43.831  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 07:48:43.834  3528  5355 V NativeCrypto: Read error: ssl=0x7faae05000: I/O error during system call, Connection timed out
09-28 07:48:43.834  4556  4556 D HeadsetService: Received stop request...Stopping profile...
,09-28 07:48:43.836   929  5300 D DhcpClient: Receive thread stopped
09-28 07:48:43.836  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:43.836  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:43.836  3528  5355 V NativeCrypto: SSL shutdown failed: ssl=0x7faae05000: I/O error during system call, Broken pipe
09-28 07:48:43.837  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.837  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:43.838   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 07:48:43.839  3761  3785 D BluetoothHeadset: Proxy object disconnected
09-28 07:48:43.839   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 07:48:43.839   929  3750 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-28 07:48:43.840   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 07:48:43.840  3077  3920 D BluetoothHeadset: Proxy object disconnected
09-28 07:48:43.840   929  5297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-28 07:48:43.841  4556  4556 D A2dpService: Received stop request...Stopping profile...
09-28 07:48:43.842  4556  4770 D A2dpStateMachine: Exit Disconnected: -1
09-28 07:48:43.843  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:43.843  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:43.843  3077  3077 D HeadsetProfile: Bluetooth service disconnected
09-28 07:48:43.843  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.843  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:43.845  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:43.847   929   929 D BluetoothA2dp: Proxy object disconnected
09-28 07:48:43.847  3077  3077 D BluetoothA2dp: Proxy object disconnected
,09-28 07:48:43.848   929  5297 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-28 07:48:43.849  4556  4556 D HidService: Received stop request...Stopping profile...
09-28 07:48:43.849   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-28 07:48:43.849  4556  4556 D HidService: Stopping Bluetooth HidService
09-28 07:48:43.849   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-28 07:48:43.850  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:43.851   929  2927 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-28 07:48:43.851   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-28 07:48:43.852   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-28 07:48:43.852   565   565 E Parcel  : Reading a NULL string not supported here.
09-28 07:48:43.853  4556  4556 D HealthService: Received stop request...Stopping profile...
09-28 07:48:43.854  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:43.854  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:43.855  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.855  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:43.855  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-28 07:48:43.856  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-28 07:48:43.856  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:43.856  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:43.856   929   929 D RttService: SCAN_AVAILABLE : 1
,09-28 07:48:43.858  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-28 07:48:43.858  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:43.858  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:43.858  4556  4556 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 07:48:43.857   929  3031 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 07:48:43.859  4556  4759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 07:48:43.859  4556  4759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 07:48:43.859  4556  4759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 07:48:43.859   929  2927 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-28 07:48:43.859  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.859  4556  4618 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 07:48:43.859  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:43.859  4556  4618 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-28 07:48:43.859  4556  4556 D PanService: Received stop request...Stopping profile...
09-28 07:48:43.860  3718  3852 W QCNEJ   : |CORE| network lost: 100
09-28 07:48:43.860  3718  3852 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-28 07:48:43.861  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-28 07:48:43.861  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-28 07:48:43.861  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:43.861  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:43.861  4556  4556 D BluetoothMapService: Received stop request...Stopping profile...
,09-28 07:48:43.861  4556  4556 D BluetoothMapService: stop()
,09-28 07:48:43.862  4556  4556 D BluetoothMapAppObserver: deinitObservers()
09-28 07:48:43.862  4556  4556 D BluetoothMapAppObserver: removeReceiver()
09-28 07:48:43.864  3077  3077 D BluetoothInputDevice: Proxy object disconnected
09-28 07:48:43.864  3077  3077 D HidProfile: Bluetooth service disconnected
09-28 07:48:43.864  3077  3077 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 07:48:43.864  3077  3077 D PanProfile: Bluetooth service disconnected
09-28 07:48:43.865  3077  3077 D BluetoothMap: Proxy object disconnected
,09-28 07:48:43.866  3077  3077 D MapProfile: Bluetooth service disconnected
,09-28 07:48:43.869  4556  4556 D SapService: Received stop request...Stopping profile...
,09-28 07:48:43.869  4556  4556 V SapService: stop()
,09-28 07:48:43.875  4556  4759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 07:48:43.875  4556  4556 V BluetoothAdapterState: isTurningOff()=true
,09-28 07:48:43.875  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,09-28 07:48:43.875  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 07:48:43.875  4556  4759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 07:48:43.875  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 07:48:43.875  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 07:48:43.875   929  2925 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-28 07:48:43.875  4556  4556 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 07:48:43.875  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-28 07:48:43.875  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-28 07:48:43.875  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:43.876  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:43.876  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 07:48:43.876  4556  4618 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 07:48:43.876  4556  4759 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 07:48:43.876  4556  4556 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-28 07:48:43.876  4556  4759 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-28 07:48:43.876  4556  4759 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 07:48:43.876  4556  4618 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-28 07:48:43.876  4556  4759 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-28 07:48:43.876  4556  4556 V BluetoothAdapterState: isTurningOff()=true
,09-28 07:48:43.876  4556  4618 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-28 07:48:43.876  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,09-28 07:48:43.876  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 07:48:43.876  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:43.876  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-28 07:48:43.876  4556  4556 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 07:48:43.877  4556  4556 D BluetoothMapService: MAP Service closeService in
09-28 07:48:43.877  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-28 07:48:43.877  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-28 07:48:43.877  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:43.877  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:43.877  4556  4556 D BluetoothMapService: cleanup()
09-28 07:48:43.878  4556  4556 D BluetoothMapService: MAP Service closeService in
09-28 07:48:43.878  4556  4556 V BluetoothAdapterState: isTurningOff()=true
09-28 07:48:43.878  4556  4556 V BluetoothAdapterState: isTurningOn()=false
,09-28 07:48:43.878  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:43.878  4556  4556 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:43.880  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-28 07:48:43.880  4556  4614 D BluetoothAdapterProperties: Setting state to 15
,09-28 07:48:43.880  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 07:48:43.880  3077  3090 D BluetoothMap: onBluetoothStateChange: up=false
09-28 07:48:43.881   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:48:43.881  3077  3089 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 07:48:43.881  4556  4614 I BluetoothAdapterState: Entering BleOnState
09-28 07:48:43.882   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 07:48:43.882  3077  3920 D BluetoothPan: onBluetoothStateChange on: false
09-28 07:48:43.882  3077  3090 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:48:43.883   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:48:43.883  3761  3947 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 07:48:43.883   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:48:43.883  3077  3089 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 07:48:43.883   929  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 07:48:43.884  3077  3920 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 07:48:43.885  4556  4614 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 07:48:43.885  4556  4614 D BluetoothAdapterProperties: Setting state to 16
09-28 07:48:43.885  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 07:48:43.886  4556  4614 D BluetoothAdapterProperties: onBleDisable
09-28 07:48:43.886  4556  4614 I BluetoothAdapterState: Entering PendingCommandState
09-28 07:48:43.886  4556  4615 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 07:48:43.887  4556  4618 D BluetoothAdapterProperties: Scan Mode:20
09-28 07:48:43.888  4556  4759 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 07:48:43.888  4556  4759 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 07:48:43.888   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 07:48:43.891  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:43.892  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:43.892  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.892  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:43.894  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:43.894  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:43.896  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:43.897  5602  5602 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:43.897  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:43.899  5549  554,9 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:43.901  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:43.902  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:43.906   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-28 07:48:43.906   510   921 D CommandListener: Clearing all IP addresses on wlan0
09-28 07:48:43.906   510   921 D TetherController: Setting IP forward enable = 0
09-28 07:48:43.908   929  2927 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-28 07:48:43.908   929  2927 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 07:48:43.912   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 07:48:43.912  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:43.914  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:43.915  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:43.922  5195  5195 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@b170f6c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-28 07:48:43.926  4964  4981 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 07:48:43.926  4964  4981 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 07:48:43.926  4964  4981 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 07:48:43.926  4964  4981 E SarControlService: no key has been found,reset the power
09-28 07:48:43.926  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 07:48:43.926  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 07:48:43.926  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 07:48:43.927  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 07:48:43.927  4991  4991 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 07:48:43.929  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 07:48:43.929  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 07:48:43.929  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 07:48:43.930  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 07:48:43.930  4991  4991 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-28 07:48:43.933  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000ea03000000000000ffffffff]
09-28 07:48:43.933  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-28 07:48:43.933  4991  5005 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-28 07:48:43.933  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 07:48:43.933  4964  4974 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-28 07:48:43.936  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 07:48:43.940  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000eb03000000000000ffffffff]
,09-28 07:48:43.941  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 07:48:43.941  4991  5005 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-28 07:48:43.941  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-28 07:48:43.942  4964  4975 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 07:48:43.942  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 07:48:43.943   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@205af3e:true
,09-28 07:48:43.958   929  3755 I ActivityManager: Start proc 5630:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-28 07:48:43.972  5602  5602 D LocalBluetoothProfileManager: Adding local MAP profile
,09-28 07:48:43.981  5602  5602 D BluetoothMap: Create BluetoothMap proxy object
,09-28 07:48:43.989  5602  5602 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-28 07:48:43.995  5630  5630 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-28 07:48:44.004  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-28 07:48:44.011   929  3750 I ActivityManager: Killing 4928:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-28 07:48:44.095  4556  4618 I bt_hci  : shut_down
,09-28 07:48:44.109  4556  4623 D bt_hwcfg: hw_epilog_process
,09-28 07:48:44.109  4556  4623 I bt_vendor: low_power_mode_cb
,09-28 07:48:44.111  4556  4623 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 07:48:44.111  4556  4623 I bt_vendor: epilog_cb
09-28 07:48:44.111  4556  4623 I bt_hci  : epilog_finished_callback
,09-28 07:48:44.114  4556  4618 I bt_hci_h4: hal_close
09-28 07:48:44.114  4556  4618 I bt_userial_vendor: device fd = 54 close
,09-28 07:48:44.212  5630  5630 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.212  5630  5630 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.212  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.213  5630  5630 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.213  5630  5630 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.213  5630  5630 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.k.d(PG:583)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:170)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.213  5630  5630 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.213  5630  5630 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.File.exists(File.java:361)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.213  5630  5630 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-28 07:48:44.213  5630  5630 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-28 07:48:44.219  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 07:48:44.225  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 07:48:44.229  4556  4615 D bt_stack_manager: event_shut_down_stack finished.
09-28 07:48:44.229  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-28 07:48:44.231  4556  4614 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-28 07:48:44.231  4556  4556 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 07:48:44.231  4556  4556 D BtGatt.GattService: Received stop request...Stopping profile...
09-28 07:48:44.231  4556  4556 D BtGatt.GattService: stop()
09-28 07:48:44.232  4556  4556 D BtGatt.AdvertiseManager: advertise clients cleared
09-28 07:48:44.234  4556  4556 V BluetoothAdapterState: isTurningOff()=false
09-28 07:48:44.234  4556  4556 V BluetoothAdapterState: isTurningOn()=false
09-28 07:48:44.234  4556  4556 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:44.234  4556  4556 V BluetoothAdapterState: isBleTurningOff()=true
09-28 07:48:44.235  4556  4614 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 07:48:44.235  4556  4614 D BluetoothAdapterProperties: Setting state to 10
09-28 07:48:44.235  4556  4614 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-28 07:48:44.236  4556  4614 I BluetoothAdapterState: Entering OffState
09-28 07:48:44.236  3951  3951 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 07:48:44.236   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-28 07:48:44.244  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 07:48:44.245  4556  4556 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 07:48:44.245  4556  4556 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 07:48:44.245  4556  4615 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-28 07:48:44.248  3951  3951 D SystemUpdateService: onCreate
09-28 07:48:44.252  3951  3951 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 07:48:44.256  4556  4615 D bt_stack_manager: event_clean_up_stack finished.
09-28 07:48:44.257  5602  5602 D DockEventReceiver: finishStartingService: stopping service
09-28 07:48:44.262  3951  3951 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-28 07:48:44.265  3951  5325 I iu.UploadsManager: num queued entries: 0
09-28 07:48:44.266  3951  5325 I iu.UploadsManager: num updated entries: 0
09-28 07:48:44.266  3951  5325 I iu.SyncManager: NEXT; no task
,09-28 07:48:44.283  4556  4556 I art     : System.exit called, status: 0
,09-28 07:48:44.283  4556  4556 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 07:48:44.306  3951  3951 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 07:48:44.307  3951  3951 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-28 07:48:44.308  5328  5328 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 07:48:44.312  5328  5328 D SprintDMHelper: simOperator: 
09-28 07:48:44.312  5328  5328 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 07:48:44.324   929   940 I ActivityManager: Process com.android.bluetooth (pid 4556) has died
,09-28 07:48:44.320  3951  5662 I SystemUpdateService: active receiver: enabled
,09-28 07:48:44.336  4356  5665 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 07:48:44.348  3951  5662 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 07:48:44.363  3951  5662 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 07:48:44.363  3951  5662 I SystemUpdateService: now status is 0 (complete)
09-28 07:48:44.363  3951  5662 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 07:48:44.363  3951  5662 I SystemUpdateService: file has been verified
09-28 07:48:44.363  3951  5662 I SystemUpdateService: OTA package size = 21989297
,09-28 07:48:44.377  3951  5662 I SystemUpdateService: showing system update notification
,09-28 07:48:44.410  3951  3951 D SystemUpdateService: onDestroy
,09-28 07:48:44.412   929   940 I ActivityManager: Killing 5195:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-28 07:48:44.537  5630  5651 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-28 07:48:44.546   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c23f023:true
,09-28 07:48:44.993   510   921 E Netd    : netlink response contains error (No such file or directory)
,09-28 07:48:44.995   929  2927 E NetdConnector: NDC Command {112 network destroy 100} took too long (1086ms)
09-28 07:48:44.996   929  2927 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 07:48:44.997   929  2925 E NetdConnector: NDC Command {113 interface ipv6 wlan0 disable} took too long (1086ms)
,09-28 07:48:44.999   929  2925 D DhcpClient: doQuit
,09-28 07:48:44.999   929  2923 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1083ms)
,09-28 07:48:44.999   510   921 D TetherController: Setting IP forward enable = 0
,09-28 07:48:45.000   929  2925 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-28 07:48:45.004   929  5299 D DhcpClient: onQuitting
09-28 07:48:45.005  3399  3399 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-28 07:48:45.012  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:45.012  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:45.012  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:45.012  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:45.014  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:45.014  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:45.014  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:45.014  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:45.016  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:45.016  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:45.016  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:45.016  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 07:48:45.025   929   942 I ActivityManager: Start proc 5673:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-28 07:48:45.027  3399  3399 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-28 07:48:45.033  3399  3399 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-28 07:48:45.053  3399  3399 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 07:48:45.059  5673  5673 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-28 07:48:45.066   929  3755 I ActivityManager: Killing 4628:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-28 07:48:45.068  3399  3399 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 07:48:45.084   929  2925 D wifi    : In wifi stop Hal
09-28 07:48:45.084   929  2925 D wifi    : halHandle = 0x7f94a88e00, mVM = 0x7fb10cd140, mCls = 0x100a02
,09-28 07:48:45.084  4356  4356 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 07:48:45.084   929  3398 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 07:48:45.085   929  3398 D WifiHAL : Got a signal to exit!!!
09-28 07:48:45.085   929  3398 I WifiHAL : Exit wifi_event_loop
09-28 07:48:45.086   929  2925 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-28 07:48:45.086   929  2925 E WifiHAL : Event processing terminated
09-28 07:48:45.086   929  2925 D wifi    : In wifi cleaned up handler
09-28 07:48:45.086   929  2925 I WifiHAL : Internal cleanup completed
09-28 07:48:45.087  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:45.087  3696  4158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 07:48:45.088  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:45.090  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:45.107   929  3398 D wifi    : set interface wlan0 flags (DOWN)
,09-28 07:48:45.108   929  2925 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 07:48:45.315   929   946 D Tethering: InitialState.processMessage what=4
,09-28 07:48:45.322   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 07:48:48.822   929  3911 D WifiService: setWifiEnabled: true pid=5549, uid=10077
,09-28 07:48:48.822   929  3911 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 07:48:48.831   510   921 D SoftapController: Softap fwReload - Ok
,09-28 07:48:48.837   510   921 D CommandListener: Setting iface cfg
,09-28 07:48:48.837   510   921 D CommandListener: Trying to bring down wlan0
09-28 07:48:48.838   510   921 D CommandListener: Clearing all IP addresses on wlan0
,09-28 07:48:48.842   929  2925 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 07:48:49.430   929  2925 D wifi    : set interface wlan0 flags (UP)
,09-28 07:48:49.437   929  2925 I WifiHAL : Initializing wifi
,09-28 07:48:49.437   929  2925 I WifiHAL : Creating socket
,09-28 07:48:49.438   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 07:48:49.445   929  2925 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-28 07:48:49.445   929  2925 D wifi    : Did set static halHandle = 0x7f94a88e00
09-28 07:48:49.445   929  2925 D wifi    : halHandle = 0x7f94a88e00, mVM = 0x7fb10cd140, mCls = 0x101992
,09-28 07:48:49.445   929  2925 D wifi    : array field set
09-28 07:48:49.446   929  2925 I WifiNative-HAL: interface[0] = wlan0
09-28 07:48:49.449   929  5687 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547954920960
,09-28 07:48:49.450   929  5687 D wifi    : waitForHalEvents called, vm = 0x7fb10cd140, obj = 0x101992, env = 0x7f924533c0
,09-28 07:48:49.529  5688  5688 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 07:48:49.549   929  2925 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 07:48:49.550  5688  5688 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-28 07:48:49.560  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:49.562  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:49.563  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:49.574  5688  5688 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 07:48:49.575  5688  5688 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 07:48:49.590  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:49.590  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:49.590  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:49.590  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:49.591   929  2925 D WifiConfigStore: Loading config and enabling all networks 
,09-28 07:48:49.592  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:49.592  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:49.592  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:49.592  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:49.593  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:49.593  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:49.594  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:49.594  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-28 07:48:49.607   929  2925 D WifiConfigStore: loaded 0 passpoint configs
,09-28 07:48:49.607   929  2925 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 07:48:49.608   929  2925 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 07:48:49.609   929  2925 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-28 07:48:49.610   929  2925 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-28 07:48:49.610   929  2925 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 07:48:49.610   929  2925 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 07:48:49.610   929  2925 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 07:48:49.613   929  2925 D WifiNative-HAL: Setting external_sim to 1
,09-28 07:48:49.614  4356  4356 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 07:48:49.614   929  2925 D wifi    : setting dfs flag to true, 0x7f95a16920
09-28 07:48:49.614   929  2925 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 07:48:49.614   929  2925 D wifi    : setting scan oui 0x7f95a16920
09-28 07:48:49.615   929  2925 D WifiHAL : Sending mac address OUI
,09-28 07:48:49.618   929  2925 E native  : do suspend false
,09-28 07:48:49.625   929   929 D RttService: SCAN_AVAILABLE : 3
,09-28 07:48:49.625   929  2925 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 07:48:49.625   929  3031 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-28 07:48:49.625   510   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-28 07:48:49.626   510   921 D CommandListener: Setting iface cfg
,09-28 07:48:49.629   929  2924 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-28 07:48:49.630   929  2924 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 07:48:49.638   929  2924 D WifiNative-HAL: p2pGetDeviceAddress
,09-28 07:48:49.643   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=266841 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
09-28 07:48:49.643   929  2924 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 07:48:52.803  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 07:48:52.809  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 07:48:52.815  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 07:48:52.819  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 07:48:52.872   929  2925 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 07:48:52.873   929  2925 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 07:48:52.874   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:48:52.885   929  2925 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 07:48:52.919   929  2925 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 07:48:52.921  5688  5688 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 07:48:53.355  5688  5688 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 07:48:53.390  5688  5688 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 07:48:53.390  5688  5688 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 07:48:53.400   929  2925 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-28 07:48:53.400   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:48:53.400   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 07:48:53.416   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:48:53.429   510   921 D CommandListener: Setting iface cfg
,09-28 07:48:53.435   929  2925 D WifiStateMachine: Start Dhcp Watchdog 2
,09-28 07:48:53.444   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-28 07:48:53.444   929  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-28 07:48:53.444   929  2927 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-28 07:48:53.446   929  5696 D DhcpClient: Receive thread started
,09-28 07:48:53.527   929  2925 E native  : do suspend false
,09-28 07:48:53.541   929  5695 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 07:48:53.576   929  5696 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172571, domain null
,09-28 07:48:53.576   929  5695 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172571 seconds
,09-28 07:48:53.578   929  5695 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 07:48:53.593   929  5696 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 07:48:53.593   929  5695 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 07:48:53.596   510   921 D CommandListener: Setting iface cfg
,09-28 07:48:53.603   929  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 07:48:53.607   929  5695 D DhcpClient: Scheduling renewal in 86399s
,09-28 07:48:53.616   929  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-28 07:48:53.618   929  2925 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 07:48:53.619   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 07:48:53.622   929  2927 D ConnectivityService: Adding iface wlan0 to network 101
,09-28 07:48:53.637   929  2925 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 07:48:53.679   929  2927 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 07:48:53.679   929  2927 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-28 07:48:53.685   929  2927 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
09-28 07:48:53.687   929  2927 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-28 07:48:53.690   929  2927 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-28 07:48:53.697   929  2927 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-28 07:48:53.701   929  2927 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-28 07:48:53.701   929  2927 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-28 07:48:53.702   929  2927 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-28 07:48:53.702   929  2927 D ConnectivityService:    accepting network in place of null
09-28 07:48:53.702   929  2925 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 07:48:53.702   929  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-28 07:48:53.703   929  2927 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 07:48:53.722   929  5694 D NetlinkSocketObserver: NeighborEvent{elapsedMs=270920, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 07:48:53.726   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 07:48:53.749   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 07:48:53.752   929  2927 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-28 07:48:53.752   929  2927 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 07:48:53.752  3718  3852 W QCNEJ   : |CORE| network available: 101
09-28 07:48:53.753   929  2927 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-28 07:48:53.757  3718  3852 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 07:48:53.758  3718  3852 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 07:48:53.759  3718  3852 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-28 07:48:53.759   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 07:48:53.760  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:53.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:53.760  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:53.760  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:48:53.764  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:53.764  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:53.765  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.765  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:53.767  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:48:53.767  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:48:53.767  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.767  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:48:53.771  4964  4981 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 07:48:53.771  4964  4981 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 07:48:53.771  4964  4981 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 07:48:53.772  4964  4981 E SarControlService: no key has been found,reset the power
,09-28 07:48:53.772  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 07:48:53.772  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-28 07:48:53.772  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-28 07:48:53.773  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 07:48:53.773  4991  4991 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 07:48:53.774  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 07:48:53.774  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 07:48:53.774  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 07:48:53.775  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 07:48:53.775  4991  4991 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-28 07:48:53.778  3951  3951 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-28 07:48:53.779  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000ec03000000000000ffffffff]
09-28 07:48:53.779  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 07:48:53.779  4991  5005 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-28 07:48:53.781  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 07:48:53.782  4964  4974 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 07:48:53.783  3951  3951 D SystemUpdateService: onCreate
09-28 07:48:53.786  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000ed03000000000000ffffffff]
09-28 07:48:53.786  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 07:48:53.786  4991  5005 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-28 07:48:53.786  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-28 07:48:53.787  4964  4975 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 07:48:53.787  3951  3951 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 07:48:53.792   929  5693 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-28 07:48:53.797  3951  3951 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 07:48:53.803  3951  5325 I iu.UploadsManager: num queued entries: 0
,09-28 07:48:53.803  3951  5325 I iu.UploadsManager: num updated entries: 0
09-28 07:48:53.803  3951  5325 I iu.SyncManager: NEXT; no task
,09-28 07:48:53.805  3951  5706 I SystemUpdateService: active receiver: enabled
,09-28 07:48:53.808  3951  3951 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 07:48:53.809  3951  3951 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-28 07:48:53.811  5328  5328 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 07:48:53.814  5328  5328 D SprintDMHelper: simOperator: 
09-28 07:48:53.815  5328  5328 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 07:48:53.827   929  3794 D WifiService: setWifiEnabled: false pid=5549, uid=10077
,09-28 07:48:53.828   929  3794 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 07:48:53.829   929  2925 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-28 07:48:53.829   929  2925 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-28 07:48:53.829   929  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 07:48:53.829   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:48:53.836  3951  5706 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 07:48:53.837   929  5695 D DhcpClient: Clearing IP address
,09-28 07:48:53.837   510   921 D CommandListener: Clearing all IP addresses on wlan0
,09-28 07:48:53.839   510   921 D CommandListener: Setting iface cfg
09-28 07:48:53.839  4356  5711 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-28 07:48:53.839  4356  5711 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-28 07:48:53.841   929  5693 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,09-28 07:48:53.843   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,09-28 07:48:53.847   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-28 07:48:53.847   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-28 07:48:53.850   565   565 E Parcel  : Reading a NULL string not supported here.
09-28 07:48:53.852   929  2927 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-28 07:48:53.853  3951  5706 I SystemUpdateService: network: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-28 07:48:53.853  3951  5706 I SystemUpdateService: now status is 0 (complete)
09-28 07:48:53.853  3951  5706 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 07:48:53.853  3951  5706 I SystemUpdateService: file has been verified
09-28 07:48:53.853  3951  5706 I SystemUpdateService: OTA package size = 21989297
09-28 07:48:53.854   929   929 D RttService: SCAN_AVAILABLE : 1
09-28 07:48:53.855  3718  3852 W QCNEJ   : |CORE| network lost: 101
,09-28 07:48:53.855   929  3031 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-28 07:48:53.855  3718  3852 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-28 07:48:53.860   929  2925 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-28 07:48:53.861  3951  5706 I SystemUpdateService: showing system update notification
,09-28 07:48:53.863   929  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 07:48:53.865   929  5696 D DhcpClient: Receive thread stopped
,09-28 07:48:53.870  3951  3951 D SystemUpdateService: onDestroy
,09-28 07:48:53.880   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 07:48:53.899   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 07:48:53.899   510   921 D CommandListener: Clearing all IP addresses on wlan0
09-28 07:48:53.899   929  2927 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-28 07:48:53.899   929  2927 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-28 07:48:53.901   929  2925 D DhcpClient: doQuit
,09-28 07:48:53.901   929  2925 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 07:48:53.903   929  5695 D DhcpClient: onQuitting
09-28 07:48:53.904  5688  5688 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-28 07:48:53.904  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.904   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:53.904  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:53.904  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.904  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:53.906  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:53.906  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:53.906  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:48:53.906  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:53.908  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:53.908  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:53.908  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.908  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:53.909  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:53.909  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:53.909  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:48:53.909  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:53.910  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:53.912  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:53.915  4964  4981 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-28 07:48:53.915  4964  4981 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 07:48:53.915  4964  4981 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-28 07:48:53.916  4964  4981 E SarControlService: no key has been found,reset the power
09-28 07:48:53.917  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 07:48:53.917  3951  3951 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 07:48:53.918  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 07:48:53.918  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-28 07:48:53.919  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 07:48:53.919  4991  4991 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-28 07:48:53.922  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 07:48:53.922  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-28 07:48:53.922  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-28 07:48:53.922  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 07:48:53.922  4991  4991 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 07:48:53.923  3951  3951 D SystemUpdateService: onCreate
09-28 07:48:53.925  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000ee03000000000000ffffffff]
09-28 07:48:53.925  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 07:48:53.925  4991  5005 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-28 07:48:53.925  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 07:48:53.925  4964  4975 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 07:48:53.927  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000ef03000000000000ffffffff]
09-28 07:48:53.927  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 07:48:53.928  4991  5005 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-28 07:48:53.928  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 07:48:53.928  4964  4974 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 07:48:53.929  3951  3951 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-28 07:48:53.932  5688  5688 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-28 07:48:53.936  5688  5688 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-28 07:48:53.936  3951  5723 I SystemUpdateService: active receiver: enabled
,09-28 07:48:53.940  3951  3951 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-28 07:48:53.945  3951  5325 I iu.UploadsManager: num queued entries: 0
,09-28 07:48:53.945  3951  5325 I iu.UploadsManager: num updated entries: 0
09-28 07:48:53.946  3951  5325 I iu.SyncManager: NEXT; no task
,09-28 07:48:53.948  3951  3951 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 07:48:53.949  3951  3951 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 07:48:53.951  5328  5328 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 07:48:53.956  5328  5328 D SprintDMHelper: simOperator: 
09-28 07:48:53.956  5328  5328 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 07:48:53.956   510   921 E Netd    : netlink response contains error (No such file or directory)
09-28 07:48:53.958   929  2927 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-28 07:48:53.958   929  2927 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-28 07:48:53.958  3951  5723 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 07:48:53.966  3951  5723 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-28 07:48:53.966  4356  5727 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-28 07:48:53.970  3951  5723 I SystemUpdateService: now status is 0 (complete)
,09-28 07:48:53.970  3951  5723 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-28 07:48:53.970  3951  5723 I SystemUpdateService: file has been verified
09-28 07:48:53.970  3951  5723 I SystemUpdateService: OTA package size = 21989297
,09-28 07:48:53.977  5688  5688 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-28 07:48:53.986  3951  5723 I SystemUpdateService: showing system update notification
,09-28 07:48:53.992  3951  3951 D SystemUpdateService: onDestroy
,09-28 07:48:53.994  5688  5688 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-28 07:48:54.095   929  2925 D wifi    : In wifi stop Hal
,09-28 07:48:54.096   929  2925 D wifi    : halHandle = 0x7f94a88e00, mVM = 0x7fb10cd140, mCls = 0x101992
09-28 07:48:54.096   929  5687 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-28 07:48:54.096   929  5687 D WifiHAL : Got a signal to exit!!!
09-28 07:48:54.096   929  5687 I WifiHAL : Exit wifi_event_loop
09-28 07:48:54.096   929  2925 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-28 07:48:54.096   929  2925 E WifiHAL : Event processing terminated
09-28 07:48:54.096   929  2925 D wifi    : In wifi cleaned up handler
,09-28 07:48:54.096   929  2925 I WifiHAL : Internal cleanup completed
09-28 07:48:54.097  3696  4158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 07:48:54.097  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:54.099  4356  4356 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-28 07:48:54.099  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:54.102  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:54.123   929  5687 D wifi    : set interface wlan0 flags (DOWN)
,09-28 07:48:54.123   929  2925 D WifiNative-HAL: HAL event thread stopped successfully
,09-28 07:48:54.329   929   946 D Tethering: InitialState.processMessage what=4
,09-28 07:48:54.339   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-28 07:48:54.754   929  2927 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-28 07:48:56.522   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:57.523   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:58.524   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:58.867   929   946 I ActivityManager: Start proc 5729:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 07:48:58.983  5729  5729 D AdapterServiceConfig: Adding HeadsetService
,09-28 07:48:58.984  5729  5729 D AdapterServiceConfig: Adding A2dpService
09-28 07:48:58.984  5729  5729 D AdapterServiceConfig: Adding HidService
09-28 07:48:58.984  5729  5729 D AdapterServiceConfig: Adding HealthService
,09-28 07:48:58.985  5729  5729 D AdapterServiceConfig: Adding PanService
09-28 07:48:58.985  5729  5729 D AdapterServiceConfig: Adding GattService
09-28 07:48:58.985  5729  5729 D AdapterServiceConfig: Adding BluetoothMapService
09-28 07:48:58.985  5729  5729 D AdapterServiceConfig: Adding SapService
,09-28 07:48:58.998   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f4779d1:true
,09-28 07:48:58.999  5729  5729 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 07:48:59.003  5729  5729 I bt_bluedroid: init
09-28 07:48:59.003  5729  5741 I BluetoothAdapterState: Entering OffState
,09-28 07:48:59.006  5729  5742 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-28 07:48:59.006  5729  5742 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-28 07:48:59.006  5729  5742 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 07:48:59.006  5729  5742 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-28 07:48:59.007  5729  5729 I bt_bluedroid: get_profile_interface socket
,09-28 07:48:59.010  5729  5729 I bt_bluedroid: get_profile_interface sdp
09-28 07:48:59.010  5729  5745 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 07:48:59.013  5729  5745 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 07:48:59.018  5729  5740 I bt_bluedroid: config_hci_snoop_log
,09-28 07:48:59.020   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 07:48:59.025  5729  5741 D BluetoothAdapterState: Current state: OFF, message: 0
,09-28 07:48:59.025  5729  5741 D BluetoothAdapterProperties: Setting state to 14
09-28 07:48:59.025  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-28 07:48:59.026  5729  5741 D BluetoothBondStateMachine: make
,09-28 07:48:59.028  5729  5746 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 07:48:59.031  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
,09-28 07:48:59.032  5729  5729 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 07:48:59.035  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:59.035  5729  5729 D BtGatt.DebugUtils: handleDebugAction() action=null
09-28 07:48:59.036  5729  5729 D BtGatt.GattService: Received start request. Starting profile...
09-28 07:48:59.036  5729  5729 D BtGatt.GattService: start()
09-28 07:48:59.036  5729  5729 I bt_bluedroid: get_profile_interface gatt
09-28 07:48:59.037  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:59.037  5729  5729 D BtGatt.AdvertiseManager: advertise manager created
,09-28 07:48:59.042  5729  5729 V BluetoothAdapterState: isTurningOff()=false
,09-28 07:48:59.042  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:48:59.042  5729  5729 V BluetoothAdapterState: isBleTurningOn()=true
09-28 07:48:59.043  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:59.043  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 07:48:59.044  5729  5741 I bt_bluedroid: bt_bluedroid
,09-28 07:48:59.044  5729  5742 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 07:48:59.045  5729  5742 I bt_hci  : start_up
,09-28 07:48:59.050  5729  5742 I bt_vendor: alloc value 0xf3cf5871
09-28 07:48:59.050  5729  5742 I bt_vendor: init
09-28 07:48:59.050  5729  5742 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-28 07:48:59.050  5729  5742 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 07:48:59.160  5729  5742 D bt_hci  : start_up starting async portion
09-28 07:48:59.160  5729  5749 I bt_hci  : event_finish_startup
09-28 07:48:59.160  5729  5749 I bt_hci_h4: hal_open
09-28 07:48:59.160  5729  5749 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 07:48:59.163  5729  5749 I bt_userial_vendor: device fd = 54 open
,09-28 07:48:59.160  5750  5750 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 07:48:59.177  5729  5749 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 07:48:59.180  5729  5749 D bt_hwcfg: Chipset BCM4358A3
,09-28 07:48:59.180  5729  5749 D bt_hwcfg: Target name = [BCM4358A3]
09-28 07:48:59.180  5729  5749 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 07:48:59.525   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:48:59.571  5729  5749 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 07:48:59.571  5729  5749 D bt_hwcfg: Settlement delay -- 100 ms
09-28 07:48:59.571  5729  5749 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 07:48:59.705  5729  5749 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 07:48:59.706  5729  5749 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-28 07:48:59.707  5729  5749 I bt_hwcfg: vendor lib fwcfg completed
09-28 07:48:59.707  5729  5749 I bt_vendor: firmware callback
09-28 07:48:59.707  5729  5749 I bt_hci  : firmware_config_callback
,09-28 07:48:59.717  5729  5752 I bt_btu  : btu_task pending for preload complete event
,09-28 07:48:59.717  5729  5752 I bt_btu_task: Bluetooth chip preload is complete
09-28 07:48:59.717  5729  5752 I bt_btu  : btu_task received preload complete event
,09-28 07:48:59.723  5729  5752 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 07:48:59.724  5729  5752 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 07:48:59.724  5729  5752 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-28 07:48:59.724  5729  5752 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 07:48:59.724  5729  5752 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 07:48:59.724  5729  5752 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 07:48:59.724  5729  5752 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 07:48:59.724  5729  5752 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 07:48:59.725  5729  5752 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 07:48:59.725  5729  5752 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 07:48:59.725  5729  5752 I         : BTE_InitTraceLevels -- TRC_SDP
,09-28 07:48:59.725  5729  5752 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 07:48:59.725  5729  5752 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 07:48:59.725  5729  5752 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-28 07:48:59.725  5729  5752 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 07:48:59.808  5729  5752 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c73549
,09-28 07:48:59.808  5729  5752 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c73549 
,09-28 07:48:59.822  5729  5745 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 07:48:59.823  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 07:48:59.823  5729  5745 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 07:48:59.826  5729  5745 D BluetoothAdapterProperties: Name is: Nexus 6P
09-28 07:48:59.829  5729  5745 D BluetoothAdapterProperties: Scan Mode:20
09-28 07:48:59.829  5729  5745 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 07:48:59.830  5729  5745 D bt_hci  : do_postload posting postload work item
09-28 07:48:59.830  5729  5749 I bt_hci  : event_postload
,09-28 07:48:59.830  5729  5749 I bt_vendor: sco_config_cb
09-28 07:48:59.830  5729  5749 I bt_hci  : sco_config_callback postload finished.
,09-28 07:48:59.833  5729  5745 D bt_bte_conf: Device ID record 1 : primary
,09-28 07:48:59.833  5729  5745 D bt_bte_conf:   vendorId            = 000f
,09-28 07:48:59.833  5729  5745 D bt_bte_conf:   vendorIdSource      = 0001
09-28 07:48:59.833  5729  5745 D bt_bte_conf:   product             = 1200
09-28 07:48:59.833  5729  5745 D bt_bte_conf:   version             = 1436
09-28 07:48:59.834  5729  5745 D bt_bte_conf:   clientExecutableURL = 
09-28 07:48:59.834  5729  5745 D bt_bte_conf:   serviceDescription  = 
09-28 07:48:59.834  5729  5745 D bt_bte_conf:   documentationURL    = 
09-28 07:48:59.834  5729  5745 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 07:48:59.834  5729  5742 D bt_stack_manager: event_start_up_stack finished
09-28 07:48:59.835  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 07:48:59.836  5729  5741 D BluetoothAdapterProperties: Setting state to 15
09-28 07:48:59.836  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-28 07:48:59.839  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:59.839  5729  5741 I BluetoothAdapterState: Entering BleOnState
09-28 07:48:59.840  5729  5749 I bt_vendor: low_power_mode_cb
09-28 07:48:59.844  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:59.846  5729  5741 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-28 07:48:59.847  5729  5741 D BluetoothAdapterProperties: Setting state to 11
09-28 07:48:59.847  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-28 07:48:59.848  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:59.852  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:59.853  5729  5729 D HeadsetService: Received start request. Starting profile...
09-28 07:48:59.855  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:59.857  5729  5729 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 07:48:59.857  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:59.857  5729  5729 D HeadsetStateMachine: make
09-28 07:48:59.859  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:48:59.869  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
,09-28 07:48:59.870  5729  5729 D HeadsetStateMachine: max_hf_connections = 1
,09-28 07:48:59.870  5729  5729 I bt_bluedroid: get_profile_interface handsfree
09-28 07:48:59.871  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-28 07:48:59.871  5729  5745 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-28 07:48:59.874  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:48:59.875  5729  5729 D A2dpService: Received start request. Starting profile...
,09-28 07:48:59.875  5729  5729 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 07:48:59.876  5729  5729 I bt_bluedroid: get_profile_interface avrcp
,09-28 07:48:59.881  5729  5729 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 07:48:59.881  5729  5729 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 07:48:59.882  5729  5729 D A2dpStateMachine: make
09-28 07:48:59.883  5729  5729 I bt_bluedroid: get_profile_interface a2dp
,09-28 07:48:59.883  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 07:48:59.885  5729  5760 D A2dpStateMachine: Enter Disconnected: -2
,09-28 07:48:59.885  5729  5729 I BluetoothHidServiceJni: classInitNative: succeeds
,09-28 07:48:59.886  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:48:59.887  5729  5729 D HidService: Received start request. Starting profile...
09-28 07:48:59.888  5729  5729 I bt_bluedroid: get_profile_interface hidhost
,09-28 07:48:59.888  5729  5729 D HidService: setHidService(): set to: null
09-28 07:48:59.888  5729  5745 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c5456d
09-28 07:48:59.888  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 07:48:59.888  5729  5729 I BluetoothHealthServiceJni: classInitNative: succeeds
09-28 07:48:59.888  5602  5602 D BluetoothInputDevice: Proxy object connected
09-28 07:48:59.889  5602  5602 D HidProfile: Bluetooth service connected
09-28 07:48:59.889  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:59.890  5729  5729 D HealthService: Received start request. Starting profile...
,09-28 07:48:59.891  5729  5729 I bt_bluedroid: get_profile_interface health
09-28 07:48:59.892  5729  5729 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-28 07:48:59.893  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:59.893  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 07:48:59.894  5729  5729 D PanService: Received start request. Starting profile...
,09-28 07:48:59.895  5729  5729 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-28 07:48:59.895  5729  5729 I bt_bluedroid: get_profile_interface pan
,09-28 07:48:59.895  5729  5745 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-28 07:48:59.896  5602  5602 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 07:48:59.897  5602  5602 D PanProfile: Bluetooth service connected
09-28 07:48:59.897  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:59.898  5602  5602 D BluetoothMap: Proxy object connected
09-28 07:48:59.898  5729  5729 D BluetoothMapService: Received start request. Starting profile...
09-28 07:48:59.898  5729  5729 D BluetoothMapService: start()
09-28 07:48:59.898  5602  5602 D MapProfile: Bluetooth service connected
09-28 07:48:59.899  5602  5602 D BluetoothMap: getConnectedDevices()
09-28 07:48:59.899  5602  5602 D BluetoothMap: Bluetooth is Not enabled
,09-28 07:48:59.900  5729  5729 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-28 07:48:59.901  5729  5729 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-28 07:48:59.901  5729  5729 D BluetoothMapAppObserver: createReceiver()
,09-28 07:48:59.903  5729  5729 D BluetoothMapAppObserver: initObservers()
,09-28 07:48:59.903  5729  5729 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 07:48:59.910  5729  5729 V SapService: SapBinder()
,09-28 07:48:59.910  5729  5729 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:48:59.910  5729  5729 D SapService: Received start request. Starting profile...
09-28 07:48:59.910  5729  5729 V SapService: start()
,09-28 07:48:59.912  5729  5729 V BluetoothAdapterState: isTurningOff()=false
,09-28 07:48:59.912  5729  5729 V BluetoothAdapterState: isTurningOn()=true
09-28 07:48:59.912  5729  5758 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 07:48:59.912  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:59.912  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isTurningOff()=false
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isTurningOn()=true
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isTurningOff()=false
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isTurningOn()=true
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isTurningOff()=false
09-28 07:48:59.913  5729  5729 V BluetoothAdapterState: isTurningOn()=true
09-28 07:48:59.914  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:59.914  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 07:48:59.914  5729  5729 V BluetoothAdapterState: isTurningOff()=false
09-28 07:48:59.914  5729  5729 V BluetoothAdapterState: isTurningOn()=true
,09-28 07:48:59.914  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 07:48:59.915  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:59.915  5729  5729 V BluetoothAdapterState: isTurningOff()=false
09-28 07:48:59.915  5729  5729 V BluetoothAdapterState: isTurningOn()=true
09-28 07:48:59.915  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:59.915  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:59.916  5729  5729 V BluetoothAdapterState: isTurningOff()=false
09-28 07:48:59.916  5729  5729 V BluetoothAdapterState: isTurningOn()=true
09-28 07:48:59.916  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:48:59.916  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:48:59.916  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 07:48:59.916  5729  5741 D BluetoothAdapterProperties: ScanMode =  20
09-28 07:48:59.916  5729  5741 D BluetoothAdapterProperties: State =  11
09-28 07:48:59.917  5729  5745 D BluetoothAdapterProperties: Scan Mode:21
09-28 07:48:59.917  5729  5745 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 07:48:59.918  5729  5741 D BluetoothAdapterProperties: Setting state to 12
,09-28 07:48:59.918  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 07:48:59.918  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-28 07:48:59.919  5729  5741 I BluetoothAdapterState: Entering OnState
09-28 07:48:59.919  3077  3920 D BluetoothMap: onBluetoothStateChange: up=true
,09-28 07:48:59.921  3077  3077 D BluetoothMap: Proxy object connected
,09-28 07:48:59.921   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:48:59.921  3077  3077 D MapProfile: Bluetooth service connected
09-28 07:48:59.921  3077  3077 D BluetoothMap: getConnectedDevices()
09-28 07:48:59.922  3077  3090 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 07:48:59.923   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:59.924  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 07:48:59.924  3077  3089 D BluetoothPan: onBluetoothStateChange on: true
09-28 07:48:59.925   929   929 D BluetoothA2dp: Proxy object connected
09-28 07:48:59.926  3077  3090 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:48:59.926  3077  3077 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 07:48:59.926  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:59.926  3077  3077 D PanProfile: Bluetooth service connected
09-28 07:48:59.927   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:48:59.927  5602  5613 D BluetoothPbap: onBluetoothStateChange: up=true
,09-28 07:48:59.928  5602  5615 D BluetoothMap: onBluetoothStateChange: up=true
,09-28 07:48:59.928  5729  5729 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 07:48:59.929  3761  3995 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:48:59.929  5729  5729 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 07:48:59.929  5602  5613 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 07:48:59.929   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:59.929  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:59.930  3077  3089 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-28 07:48:59.931  5729  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 07:48:59.931  3077  3077 D BluetoothInputDevice: Proxy object connected
09-28 07:48:59.931  5602  5615 D BluetoothPan: onBluetoothStateChange on: true
09-28 07:48:59.932  3077  3077 D HidProfile: Bluetooth service connected
09-28 07:48:59.932  3077  3090 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 07:48:59.932  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:59.933  3077  3077 D BluetoothA2dp: Proxy object connected
09-28 07:48:59.934   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:48:59.936  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:48:59.937  5729  5729 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 07:48:59.938  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:48:59.939  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-28 07:48:59.939  5729  5729 D ObexServerSockets: Succeed to create listening sockets 
,09-28 07:48:59.939  5729  5729 D ObexServerSockets0: startAccept()
09-28 07:48:59.939  5602  5602 D LocalBluetoothProfileManager: Adding local A2DP profile
09-28 07:48:59.939  5729  5729 D ObexServerSockets0: prepareForNewConnect()
09-28 07:48:59.940  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:59.942  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:59.942  5729  5729 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 07:48:59.942  5729  5729 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 07:48:59.942  5729  5729 D BluetoothMapService: onReceive
09-28 07:48:59.942  5729  5769 D ObexServerSockets0: Accepting socket connection...
09-28 07:48:59.942  5729  5729 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 07:48:59.943  5729  5729 D BluetoothMapService: STATE_ON
09-28 07:48:59.943  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:48:59.943  5729  5770 D ObexServerSockets0: Accepting socket connection...
,09-28 07:48:59.945  5729  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 07:48:59.945  5602  5602 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-28 07:48:59.947  5729  5771 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-28 07:48:59.947  5729  5771 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 07:48:59.951  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 07:48:59.954  5602  5602 D BluetoothA2dp: Proxy object connected
,09-28 07:48:59.959  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 07:48:59.960  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-28 07:48:59.966  3077  3077 D BluetoothPbap: Proxy object connected
,09-28 07:48:59.966  3077  3077 D PbapServerProfile: Bluetooth service connected
,09-28 07:48:59.967  5729  5729 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 07:48:59.967  5729  5729 D ObexServerSockets0: prepareForNewConnect()
09-28 07:48:59.969  5729  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 07:48:59.970  5602  5602 D BluetoothPbap: Proxy object connected
09-28 07:48:59.971  5602  5602 D PbapServerProfile: Bluetooth service connected
,09-28 07:48:59.986  5729  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 07:48:59.987  5729  5779 I BtOppRfcommListener: Accept thread started.
,09-28 07:49:00.023   929   929 D BluetoothHeadset: Proxy object connected
,09-28 07:49:00.023  3761  3785 D BluetoothHeadset: Proxy object connected
09-28 07:49:00.023   929   929 D BluetoothHeadset: Proxy object connected
09-28 07:49:00.023   929   929 D BluetoothHeadset: Proxy object connected
09-28 07:49:00.024  3077  3089 D BluetoothHeadset: Proxy object connected
,09-28 07:49:00.027  3077  3920 D BluetoothHeadset: Proxy object connected
,09-28 07:49:00.027   929   946 D BluetoothHeadset: Proxy object connected
,09-28 07:49:00.029  3761  3947 D BluetoothHeadset: Proxy object connected
,09-28 07:49:00.030   929   946 D BluetoothHeadset: Proxy object connected
,09-28 07:49:00.033  3077  3077 D HeadsetProfile: Bluetooth service connected
,09-28 07:49:00.035  3077  3077 D HeadsetProfile: Bluetooth service connected
,09-28 07:49:00.047  5602  5615 D BluetoothHeadset: Proxy object connected
,09-28 07:49:00.049  5602  5602 D HeadsetProfile: Bluetooth service connected
,09-28 07:49:00.526   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:49:01.527   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 07:49:01.708   929  2927 D ConnectivityService: handlePromptUnvalidated 101
,09-28 07:49:03.843  5729  5741 D BluetoothAdapterState: Current state: ON, message: 23
,09-28 07:49:03.843  5729  5741 D BluetoothAdapterProperties: Setting state to 13
,09-28 07:49:03.844  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-28 07:49:03.845  5729  5741 D BluetoothAdapterProperties: onBluetoothDisable()
,09-28 07:49:03.847  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
09-28 07:49:03.851  5729  5729 D BluetoothMapService: onReceive
09-28 07:49:03.851  5729  5729 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 07:49:03.851  5729  5729 D BluetoothMapService: STATE_TURNING_OFF
09-28 07:49:03.852  5729  5729 D BluetoothMapService: MAP Service closeService in
09-28 07:49:03.852  5729  5729 D BluetoothMapMasInstance0: MAP Service shutdown
09-28 07:49:03.852  5729  5729 D ObexServerSockets0: shutdown(block = true)
09-28 07:49:03.854  5729  5729 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 07:49:03.854  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:03.855  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:49:03.856  5729  5769 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-28 07:49:03.856  5729  5745 D BluetoothAdapterProperties: Scan Mode:20
09-28 07:49:03.856  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-28 07:49:03.856  5729  5770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-28 07:49:03.859  5729  5754 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-28 07:49:03.859  5729  5729 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-28 07:49:03.860  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:49:03.860  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:49:03.863  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 07:49:03.864  5729  5729 I BtOppRfcommListener: stopping Accept Thread
,09-28 07:49:03.866  5729  5779 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-28 07:49:03.867  5729  5779 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-28 07:49:03.867  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:03.867  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 07:49:03.868  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-28 07:49:03.868  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:49:03.869  5729  5729 D HeadsetService: Received stop request...Stopping profile...
09-28 07:49:03.872  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:03.872  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:49:03.873  5549  5549 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-28 07:49:03.874  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:49:03.877  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.878  5602  5602 D DockEventReceiver: finishStartingService: stopping service
09-28 07:49:03.879  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.882  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.882   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 07:49:03.883  5602  5615 D BluetoothHeadset: Proxy object disconnected
09-28 07:49:03.883  5729  5729 D A2dpService: Received stop request...Stopping profile...
09-28 07:49:03.883  5729  5760 D A2dpStateMachine: Exit Disconnected: -1
09-28 07:49:03.883  3761  3995 D BluetoothHeadset: Proxy object disconnected
09-28 07:49:03.883   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 07:49:03.883   929   929 D BluetoothHeadset: Proxy object disconnected
09-28 07:49:03.884  3077  3920 D BluetoothHeadset: Proxy object disconnected
,09-28 07:49:03.884  3077  3077 D HeadsetProfile: Bluetooth service disconnected
09-28 07:49:03.885  5602  5602 D HeadsetProfile: Bluetooth service disconnected
09-28 07:49:03.888   929   929 D BluetoothA2dp: Proxy object disconnected
09-28 07:49:03.888  5602  5602 D BluetoothA2dp: Proxy object disconnected
09-28 07:49:03.889  3077  3077 D BluetoothA2dp: Proxy object disconnected
09-28 07:49:03.890  5729  5729 D HidService: Received stop request...Stopping profile...
09-28 07:49:03.890  5729  5729 D HidService: Stopping Bluetooth HidService
09-28 07:49:03.891  5602  5602 D BluetoothInputDevice: Proxy object disconnected
,09-28 07:49:03.892  5602  5602 D HidProfile: Bluetooth service disconnected
09-28 07:49:03.892  3077  3077 D BluetoothInputDevice: Proxy object disconnected
09-28 07:49:03.892  3077  3077 D HidProfile: Bluetooth service disconnected
09-28 07:49:03.895  5729  5729 D HealthService: Received stop request...Stopping profile...
,09-28 07:49:03.896  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 07:49:03.896  5729  5729 V BluetoothAdapterState: isTurningOff()=true
09-28 07:49:03.897  5729  5729 V BluetoothAdapterState: isTurningOn()=false
,09-28 07:49:03.897  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:03.897  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 07:49:03.899  5729  5729 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-28 07:49:03.899  5729  5729 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-28 07:49:03.899  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 07:49:03.900  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 07:49:03.900  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 07:49:03.900  5729  5729 D PanService: Received stop request...Stopping profile...
09-28 07:49:03.900  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-28 07:49:03.900  5729  5745 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-28 07:49:03.901  5602  5602 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 07:49:03.901  5602  5602 D PanProfile: Bluetooth service disconnected
09-28 07:49:03.901  5729  5729 D BluetoothMapService: Received stop request...Stopping profile...
09-28 07:49:03.901  5729  5729 D BluetoothMapService: stop()
09-28 07:49:03.901  3077  3077 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-28 07:49:03.901  3077  3077 D PanProfile: Bluetooth service disconnected
09-28 07:49:03.902  5729  5729 D BluetoothMapAppObserver: deinitObservers()
09-28 07:49:03.902  5729  5729 D BluetoothMapAppObserver: removeReceiver()
09-28 07:49:03.904  5602  5602 D BluetoothMap: Proxy object disconnected
09-28 07:49:03.904  5602  5602 D MapProfile: Bluetooth service disconnected
09-28 07:49:03.904  3077  3077 D BluetoothMap: Proxy object disconnected
09-28 07:49:03.904  3077  3077 D MapProfile: Bluetooth service disconnected
09-28 07:49:03.905  5729  5729 D SapService: Received stop request...Stopping profile...
09-28 07:49:03.905  5729  5729 V SapService: stop()
09-28 07:49:03.908  5729  5729 V BluetoothAdapterState: isTurningOff()=true
,09-28 07:49:03.908  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:03.908  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:03.908  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 07:49:03.909  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 07:49:03.909  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-28 07:49:03.909  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-28 07:49:03.910  5729  5729 V BluetoothAdapterState: isTurningOff()=true
09-28 07:49:03.910  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 07:49:03.910  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:03.910  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 07:49:03.910  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:03.910  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-28 07:49:03.910  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:03.910  5729  5752 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-28 07:49:03.910  5729  5729 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-28 07:49:03.910  5729  5729 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-28 07:49:03.910  5729  5745 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 07:49:03.912  5729  5729 V BluetoothAdapterState: isTurningOff()=true
09-28 07:49:03.912  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:03.912  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:03.912  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:03.912  5729  5729 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-28 07:49:03.912  5729  5745 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-28 07:49:03.913  5729  5729 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-28 07:49:03.913  5729  5729 V BluetoothAdapterState: isTurningOff()=true
09-28 07:49:03.913  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:03.913  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:03.913  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:03.914  5729  5729 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-28 07:49:03.914  5729  5729 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-28 07:49:03.914  3077  3077 D BluetoothPbap: Proxy object disconnected
,09-28 07:49:03.914  3077  3077 D PbapServerProfile: Bluetooth service disconnected
09-28 07:49:03.915  5729  5729 D BluetoothMapService: MAP Service closeService in
09-28 07:49:03.915  5729  5729 V BluetoothAdapterState: isTurningOff()=true
09-28 07:49:03.915  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:03.915  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:03.915  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:03.915  5729  5729 D BluetoothMapService: cleanup()
09-28 07:49:03.915  5729  5729 D BluetoothMapService: MAP Service closeService in
09-28 07:49:03.916  5729  5729 V BluetoothAdapterState: isTurningOff()=true
09-28 07:49:03.916  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:03.916  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
,09-28 07:49:03.916  5729  5729 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:03.916  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-28 07:49:03.916  5729  5741 D BluetoothAdapterProperties: Setting state to 15
09-28 07:49:03.916  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-28 07:49:03.917  5729  5741 I BluetoothAdapterState: Entering BleOnState
09-28 07:49:03.918  3077  3090 D BluetoothMap: onBluetoothStateChange: up=false
,09-28 07:49:03.918  5602  5602 D BluetoothPbap: Proxy object disconnected
,09-28 07:49:03.918  5602  5602 D PbapServerProfile: Bluetooth service disconnected
09-28 07:49:03.919   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:49:03.919  3077  3920 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 07:49:03.920   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-28 07:49:03.920  3077  3089 D BluetoothPan: onBluetoothStateChange on: false
09-28 07:49:03.921  3077  3090 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-28 07:49:03.921  5602  5613 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-28 07:49:03.922   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:49:03.922  5602  5615 D BluetoothPbap: onBluetoothStateChange: up=false
09-28 07:49:03.922  5602  5613 D BluetoothMap: onBluetoothStateChange: up=false
09-28 07:49:03.923  3761  3785 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:49:03.923  5602  5615 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:49:03.924  5602  5613 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-28 07:49:03.924   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-28 07:49:03.924  3077  3920 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-28 07:49:03.925  5602  5615 D BluetoothPan: onBluetoothStateChange on: false
,09-28 07:49:03.926  3077  3089 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-28 07:49:03.926  5729  5741 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-28 07:49:03.926  5729  5741 D BluetoothAdapterProperties: Setting state to 16
09-28 07:49:03.926  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-28 07:49:03.927  5729  5741 D BluetoothAdapterProperties: onBleDisable
09-28 07:49:03.927  5729  5741 I BluetoothAdapterState: Entering PendingCommandState
09-28 07:49:03.928  5729  5742 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-28 07:49:03.929  5729  5752 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-28 07:49:03.929  5729  5752 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-28 07:49:03.929  5729  5745 D BluetoothAdapterProperties: Scan Mode:20
09-28 07:49:03.929  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.932  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-28 07:49:03.932  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.935  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.937  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.938  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 07:49:03.938  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:03.940  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:03.940  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-28 07:49:04.142  5729  5745 I bt_hci  : shut_down
,09-28 07:49:04.145  5729  5749 D bt_hwcfg: hw_epilog_process
,09-28 07:49:04.146  5729  5749 I bt_vendor: low_power_mode_cb
,09-28 07:49:04.150  5729  5749 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-28 07:49:04.150  5729  5749 I bt_vendor: epilog_cb
09-28 07:49:04.150  5729  5749 I bt_hci  : epilog_finished_callback
,09-28 07:49:04.155  5729  5745 I bt_hci_h4: hal_close
,09-28 07:49:04.156  5729  5745 I bt_userial_vendor: device fd = 54 close
,09-28 07:49:04.275  5729  5742 D bt_stack_manager: event_shut_down_stack finished.
,09-28 07:49:04.276  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-28 07:49:04.281  5729  5741 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-28 07:49:04.282  5729  5729 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 07:49:04.284  5729  5729 D BtGatt.GattService: Received stop request...Stopping profile...
09-28 07:49:04.285  5729  5729 D BtGatt.GattService: stop()
,09-28 07:49:04.285  5729  5729 D BtGatt.AdvertiseManager: advertise clients cleared
09-28 07:49:04.288  5729  5729 V BluetoothAdapterState: isTurningOff()=false
09-28 07:49:04.289  5729  5729 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:04.289  5729  5729 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:04.289  5729  5729 V BluetoothAdapterState: isBleTurningOff()=true
09-28 07:49:04.290  5729  5741 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-28 07:49:04.290  5729  5741 D BluetoothAdapterProperties: Setting state to 10
09-28 07:49:04.290  5729  5741 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-28 07:49:04.292  5729  5741 I BluetoothAdapterState: Entering OffState
09-28 07:49:04.294   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-28 07:49:04.309  5729  5729 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-28 07:49:04.310  5729  5729 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-28 07:49:04.310  5729  5729 I BluetoothServiceJni: cleanupNative: return from cleanup
09-28 07:49:04.312  5729  5742 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-28 07:49:04.318  5729  5729 I art     : System.exit called, status: 0
,09-28 07:49:04.319  5729  5729 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-28 07:49:04.350   929  3794 I ActivityManager: Process com.android.bluetooth (pid 5729) has died
,09-28 07:49:08.841  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:08.842  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:08.847  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:49:08.847  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4efe81a removed from the list
09-28 07:49:08.847  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
,09-28 07:49:08.847  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:08.847  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:08.850  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:08.850  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@55ed28 added. We now have 4 listener(s)
,09-28 07:49:08.850  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:49:08.854  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:49:08.872  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@55ed28 removed from the list
09-28 07:49:08.873  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:08.873  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:08.873  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:08.874  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:08.874  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c85a41 added. We now have 4 listener(s)
09-28 07:49:08.874  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:49:13.883  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:13.916   929   946 I ActivityManager: Start proc 5787:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-28 07:49:14.000  5787  5787 D AdapterServiceConfig: Adding HeadsetService
,09-28 07:49:14.001  5787  5787 D AdapterServiceConfig: Adding A2dpService
09-28 07:49:14.001  5787  5787 D AdapterServiceConfig: Adding HidService
09-28 07:49:14.001  5787  5787 D AdapterServiceConfig: Adding HealthService
09-28 07:49:14.001  5787  5787 D AdapterServiceConfig: Adding PanService
09-28 07:49:14.001  5787  5787 D AdapterServiceConfig: Adding GattService
09-28 07:49:14.002  5787  5787 D AdapterServiceConfig: Adding BluetoothMapService
,09-28 07:49:14.002  5787  5787 D AdapterServiceConfig: Adding SapService
,09-28 07:49:14.012   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9a8ef6:true
,09-28 07:49:14.013  5787  5787 D BluetoothAdapterState: make() - Creating AdapterState
,09-28 07:49:14.016  5787  5787 I bt_bluedroid: init
,09-28 07:49:14.016  5787  5799 I BluetoothAdapterState: Entering OffState
,09-28 07:49:14.019  5787  5800 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-28 07:49:14.019  5787  5800 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-28 07:49:14.019  5787  5800 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-28 07:49:14.019  5787  5800 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-28 07:49:14.020  5787  5787 I bt_bluedroid: get_profile_interface socket
,09-28 07:49:14.022  5787  5803 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 07:49:14.022  5787  5787 I bt_bluedroid: get_profile_interface sdp
,09-28 07:49:14.024  5787  5803 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-28 07:49:14.028  5787  5798 I bt_bluedroid: config_hci_snoop_log
,09-28 07:49:14.030   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-28 07:49:14.035  5787  5799 D BluetoothAdapterState: Current state: OFF, message: 0
09-28 07:49:14.035  5787  5799 D BluetoothAdapterProperties: Setting state to 14
09-28 07:49:14.035  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-28 07:49:14.037  5787  5799 D BluetoothBondStateMachine: make
,09-28 07:49:14.039  5787  5804 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-28 07:49:14.042  5787  5799 I BluetoothAdapterState: Entering PendingCommandState
,09-28 07:49:14.043  5787  5787 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-28 07:49:14.046  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:49:14.047  5787  5787 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-28 07:49:14.047  5787  5787 D BtGatt.GattService: Received start request. Starting profile...
,09-28 07:49:14.047  5787  5787 D BtGatt.GattService: start()
09-28 07:49:14.047  5787  5787 I bt_bluedroid: get_profile_interface gatt
09-28 07:49:14.048  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:49:14.049  5787  5787 D BtGatt.AdvertiseManager: advertise manager created
,09-28 07:49:14.055  5787  5787 V BluetoothAdapterState: isTurningOff()=false
09-28 07:49:14.055  5787  5787 V BluetoothAdapterState: isTurningOn()=false
09-28 07:49:14.055  5787  5787 V BluetoothAdapterState: isBleTurningOn()=true
,09-28 07:49:14.055  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:14.056  5787  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-28 07:49:14.057  5787  5799 I bt_bluedroid: bt_bluedroid
,09-28 07:49:14.057  5787  5800 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-28 07:49:14.058  5787  5800 I bt_hci  : start_up
,09-28 07:49:14.064  5787  5800 I bt_vendor: alloc value 0xf3cf5871
09-28 07:49:14.064  5787  5800 I bt_vendor: init
09-28 07:49:14.064  5787  5800 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-28 07:49:14.064  5787  5800 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-28 07:49:14.172  5787  5800 D bt_hci  : start_up starting async portion
09-28 07:49:14.173  5787  5807 I bt_hci  : event_finish_startup
,09-28 07:49:14.173  5787  5807 I bt_hci_h4: hal_open
09-28 07:49:14.173  5787  5807 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-28 07:49:14.173  5808  5808 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 07:49:14.176  5787  5807 I bt_userial_vendor: device fd = 54 open
,09-28 07:49:14.191  5787  5807 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-28 07:49:14.195  5787  5807 D bt_hwcfg: Chipset BCM4358A3
,09-28 07:49:14.195  5787  5807 D bt_hwcfg: Target name = [BCM4358A3]
09-28 07:49:14.195  5787  5807 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-28 07:49:14.590  5787  5807 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-28 07:49:14.590  5787  5807 D bt_hwcfg: Settlement delay -- 100 ms
09-28 07:49:14.590  5787  5807 I bt_hwcfg: Setting fw settlement delay to 100 
,09-28 07:49:14.724  5787  5807 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-28 07:49:14.725  5787  5807 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-28 07:49:14.726  5787  5807 I bt_hwcfg: vendor lib fwcfg completed
09-28 07:49:14.727  5787  5807 I bt_vendor: firmware callback
09-28 07:49:14.727  5787  5807 I bt_hci  : firmware_config_callback
,09-28 07:49:14.734  5787  5810 I bt_btu  : btu_task pending for preload complete event,
09-28 07:49:14.734  5787  5810 I bt_btu_task: Bluetooth chip preload is complete
,09-28 07:49:14.734  5787  5810 I bt_btu  : btu_task received preload complete event
,09-28 07:49:14.740  5787  5810 I         : BTE_InitTraceLevels -- TRC_HCI
,09-28 07:49:14.740  5787  5810 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-28 07:49:14.740  5787  5810 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-28 07:49:14.740  5787  5810 I         : BTE_InitTraceLevels -- TRC_AVDT
09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_AVRC
09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_A2D
09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_BTM
09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_GAP
09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_PAN
09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_SDP
,09-28 07:49:14.741  5787  5810 I         : BTE_InitTraceLevels -- TRC_GATT
09-28 07:49:14.742  5787  5810 I         : BTE_InitTraceLevels -- TRC_SMP
09-28 07:49:14.742  5787  5810 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-28 07:49:14.742  5787  5810 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-28 07:49:14.823  5787  5810 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c73549
,09-28 07:49:14.824  5787  5810 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c73549 
,09-28 07:49:14.834  5787  5803 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-28 07:49:14.835  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-28 07:49:14.836  5787  5803 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-28 07:49:14.839  5787  5803 D BluetoothAdapterProperties: Name is: Nexus 6P
09-28 07:49:14.841  5787  5803 D BluetoothAdapterProperties: Scan Mode:20
09-28 07:49:14.842  5787  5803 D BluetoothAdapterProperties: Discoverable Timeout:120
09-28 07:49:14.842  5787  5803 D bt_hci  : do_postload posting postload work item
09-28 07:49:14.842  5787  5807 I bt_hci  : event_postload
,09-28 07:49:14.842  5787  5807 I bt_vendor: sco_config_cb
09-28 07:49:14.843  5787  5807 I bt_hci  : sco_config_callback postload finished.
,09-28 07:49:14.847  5787  5803 D bt_bte_conf: Device ID record 1 : primary
09-28 07:49:14.847  5787  5803 D bt_bte_conf:   vendorId            = 000f
09-28 07:49:14.847  5787  5803 D bt_bte_conf:   vendorIdSource      = 0001
09-28 07:49:14.847  5787  5803 D bt_bte_conf:   product             = 1200
,09-28 07:49:14.847  5787  5803 D bt_bte_conf:   version             = 1436
09-28 07:49:14.847  5787  5803 D bt_bte_conf:   clientExecutableURL = 
09-28 07:49:14.848  5787  5803 D bt_bte_conf:   serviceDescription  = 
09-28 07:49:14.848  5787  5803 D bt_bte_conf:   documentationURL    = 
09-28 07:49:14.848  5787  5803 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-28 07:49:14.848  5787  5800 D bt_stack_manager: event_start_up_stack finished
,09-28 07:49:14.849  5787  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-28 07:49:14.849  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:14.849  5787  5799 D BluetoothAdapterProperties: Setting state to 15
09-28 07:49:14.849  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-28 07:49:14.851  5787  5799 I BluetoothAdapterState: Entering BleOnState
,09-28 07:49:14.852  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:14.854  5787  5807 I bt_vendor: low_power_mode_cb
,09-28 07:49:14.862  5787  5799 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-28 07:49:14.862  5787  5799 D BluetoothAdapterProperties: Setting state to 11
09-28 07:49:14.862  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-28 07:49:14.866  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:49:14.867  5787  5787 D HeadsetService: Received start request. Starting profile...
,09-28 07:49:14.870  5787  5787 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-28 07:49:14.871  5787  5787 D HeadsetStateMachine: make
,09-28 07:49:14.872  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:14.875  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:14.885  5787  5799 I BluetoothAdapterState: Entering PendingCommandState
,09-28 07:49:14.887  5787  5787 D HeadsetStateMachine: max_hf_connections = 1
09-28 07:49:14.887  5787  5787 I bt_bluedroid: get_profile_interface handsfree
09-28 07:49:14.888  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-28 07:49:14.888  5787  5803 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-28 07:49:14.892  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:49:14.893  5787  5787 D A2dpService: Received start request. Starting profile...
09-28 07:49:14.893  5787  5787 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-28 07:49:14.894  5787  5787 I bt_bluedroid: get_profile_interface avrcp
,09-28 07:49:14.900  5787  5787 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-28 07:49:14.901  5787  5787 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-28 07:49:14.901  5787  5787 D A2dpStateMachine: make
,09-28 07:49:14.902  5787  5787 I bt_bluedroid: get_profile_interface a2dp
,09-28 07:49:14.903  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-28 07:49:14.905  5787  5818 D A2dpStateMachine: Enter Disconnected: -2
,09-28 07:49:14.906  5787  5787 I BluetoothHidServiceJni: classInitNative: succeeds
09-28 07:49:14.907  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:49:14.907  5787  5787 D HidService: Received start request. Starting profile...
,09-28 07:49:14.907  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-28 07:49:14.908  5787  5787 I bt_bluedroid: get_profile_interface hidhost
09-28 07:49:14.908  5787  5787 D HidService: setHidService(): set to: null
09-28 07:49:14.908  5787  5803 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c5456d
09-28 07:49:14.908  5787  5803 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-28 07:49:14.908  5787  5787 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-28 07:49:14.909  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
09-28 07:49:14.910  5787  5787 D HealthService: Received start request. Starting profile...
,09-28 07:49:14.912  5787  5787 I bt_bluedroid: get_profile_interface health
,09-28 07:49:14.914  5787  5787 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-28 07:49:14.915  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:49:14.916  5787  5787 D PanService: Received start request. Starting profile...
,09-28 07:49:14.916  5787  5787 D BluetoothPanServiceJni: initializeNative(L110): pan
09-28 07:49:14.916  5787  5787 I bt_bluedroid: get_profile_interface pan
09-28 07:49:14.917  5787  5803 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-28 07:49:14.919  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:49:14.920  5787  5787 D BluetoothMapService: Received start request. Starting profile...
09-28 07:49:14.920  5787  5787 D BluetoothMapService: start()
,09-28 07:49:14.923  5787  5787 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-28 07:49:14.924  5787  5787 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-28 07:49:14.925  5787  5787 D BluetoothMapAppObserver: createReceiver()
09-28 07:49:14.926  5787  5787 D BluetoothMapAppObserver: initObservers()
,09-28 07:49:14.926  5787  5787 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-28 07:49:14.935  5787  5787 V SapService: SapBinder()
,09-28 07:49:14.935  5787  5787 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:49:14.935  5787  5787 D SapService: Received start request. Starting profile...
09-28 07:49:14.935  5787  5787 V SapService: start()
,09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isTurningOff()=false
,09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isTurningOn()=true
09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:14.937  5787  5815 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isTurningOff()=false
09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isTurningOn()=true
09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isTurningOff()=false
,09-28 07:49:14.937  5787  5787 V BluetoothAdapterState: isTurningOn()=true
09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isTurningOff()=false
09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isTurningOn()=true
,09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isTurningOff()=false
09-28 07:49:14.938  5787  5787 V BluetoothAdapterState: isTurningOn()=true
09-28 07:49:14.939  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:14.939  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:14.939  5787  5787 V BluetoothAdapterState: isTurningOff()=false
09-28 07:49:14.939  5787  5787 V BluetoothAdapterState: isTurningOn()=true
,09-28 07:49:14.939  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:14.939  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
09-28 07:49:14.940  5787  5787 V BluetoothAdapterState: isTurningOff()=false
09-28 07:49:14.940  5787  5787 V BluetoothAdapterState: isTurningOn()=true
09-28 07:49:14.940  5787  5787 V BluetoothAdapterState: isBleTurningOn()=false
09-28 07:49:14.940  5787  5787 V BluetoothAdapterState: isBleTurningOff()=false
,09-28 07:49:14.940  5787  5799 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-28 07:49:14.940  5787  5799 D BluetoothAdapterProperties: ScanMode =  20
,09-28 07:49:14.940  5787  5799 D BluetoothAdapterProperties: State =  11
09-28 07:49:14.941  5787  5799 D BluetoothAdapterProperties: Setting state to 12
09-28 07:49:14.941  5787  5799 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-28 07:49:14.941  5787  5799 I BluetoothAdapterState: Entering OnState
09-28 07:49:14.941  3077  3920 D BluetoothMap: onBluetoothStateChange: up=true
09-28 07:49:14.942  5787  5803 D BluetoothAdapterProperties: Scan Mode:21
09-28 07:49:14.942  5787  5803 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-28 07:49:14.942  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-28 07:49:14.945   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:49:14.945  3077  3077 D BluetoothMap: Proxy object connected
09-28 07:49:14.945  3077  3077 D MapProfile: Bluetooth service connected
09-28 07:49:14.945  3077  3077 D BluetoothMap: getConnectedDevices()
,09-28 07:49:14.945  3077  3090 D BluetoothPbap: onBluetoothStateChange: up=true
09-28 07:49:14.946   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:14.947  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:49:14.947  3077  3920 D BluetoothPan: onBluetoothStateChange on: true
09-28 07:49:14.948   929   929 D BluetoothA2dp: Proxy object connected
09-28 07:49:14.949  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 07:49:14.949  3077  3089 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:49:14.949  3077  3077 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 07:49:14.949  5602  5615 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 07:49:14.949  3077  3077 D PanProfile: Bluetooth service connected
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:14.951  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:49:14.951   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-28 07:49:14.951  5602  5613 D BluetoothPbap: onBluetoothStateChange: up=true
,09-28 07:49:14.952  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:49:14.952  5602  5615 D BluetoothMap: onBluetoothStateChange: up=true
09-28 07:49:14.953  5787  5787 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-28 07:49:14.953  5787  5787 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-28 07:49:14.954  5602  5602 D BluetoothA2dp: Proxy object connected
,09-28 07:49:14.955  3761  3785 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:49:14.955  5787  5787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 07:49:14.955  5602  5613 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:49:14.956  5602  5615 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 07:49:14.956  5787  5787 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 07:49:14.957   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-28 07:49:14.957  5787  5787 D ObexServerSockets: Succeed to create listening sockets 
09-28 07:49:14.957  5787  5787 D ObexServerSockets0: startAccept()
09-28 07:49:14.957  5787  5787 D ObexServerSockets0: prepareForNewConnect()
09-28 07:49:14.957  3077  3089 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-28 07:49:14.959  5787  5787 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-28 07:49:14.959  5787  5787 D BluetoothSdpJni: SDP Create record success - handle: 0
09-28 07:49:14.959  5602  5602 D BluetoothMap: Proxy object connected
09-28 07:49:14.959  5787  5825 D ObexServerSockets0: Accepting socket connection...
09-28 07:49:14.959  5602  5613 D BluetoothPan: onBluetoothStateChange on: true
09-28 07:49:14.960  3077  3077 D BluetoothInputDevice: Proxy object connected
09-28 07:49:14.960  3077  3077 D HidProfile: Bluetooth service connected
09-28 07:49:14.960  5787  5826 D ObexServerSockets0: Accepting socket connection...
09-28 07:49:14.959  5602  5602 D MapProfile: Bluetooth service connected
09-28 07:49:14.961  5602  5602 D BluetoothMap: getConnectedDevices()
09-28 07:49:14.962  3077  3920 D BluetoothA2dp: onBluetoothStateChange: up=true
09-28 07:49:14.963  3077  3077 D BluetoothA2dp: Proxy object connected
09-28 07:49:14.964   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-28 07:49:14.965  5549  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,09-28 07:49:14.965  5787  5787 D BluetoothMapService: onReceive
09-28 07:49:14.965  5787  5787 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-28 07:49:14.965  5787  5787 D BluetoothMapService: STATE_ON
09-28 07:49:14.966  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:14.967  5787  5827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-28 07:49:14.967  5602  5602 D BluetoothInputDevice: Proxy object connected
09-28 07:49:14.967  5602  5602 D HidProfile: Bluetooth service connected
,09-28 07:49:14.967  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:14.968  5787  5827 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-28 07:49:14.968  5787  5827 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-28 07:49:14.970  5602  5602 D BluetoothPan: BluetoothPAN Proxy object connected
09-28 07:49:14.970  5602  5602 D PanProfile: Bluetooth service connected
,09-28 07:49:14.974  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-28 07:49:14.980  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-28 07:49:14.982  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-28 07:49:14.986  3077  3077 D BluetoothPbap: Proxy object connected
09-28 07:49:14.986  3077  3077 D PbapServerProfile: Bluetooth service connected
,09-28 07:49:14.990  5602  5602 D BluetoothPbap: Proxy object connected
,09-28 07:49:14.990  5602  5602 D PbapServerProfile: Bluetooth service connected
,09-28 07:49:14.991  5787  5787 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-28 07:49:14.991  5787  5787 D ObexServerSockets0: prepareForNewConnect()
,09-28 07:49:14.993  5787  5831 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 07:49:15.005  5787  5835 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-28 07:49:15.006  5787  5835 I BtOppRfcommListener: Accept thread started.
,09-28 07:49:15.046   929   929 D BluetoothHeadset: Proxy object connected
,09-28 07:49:15.046  5602  5615 D BluetoothHeadset: Proxy object connected
09-28 07:49:15.047  3761  3947 D BluetoothHeadset: Proxy object connected
09-28 07:49:15.047   929   929 D BluetoothHeadset: Proxy object connected
09-28 07:49:15.047   929   929 D BluetoothHeadset: Proxy object connected
,09-28 07:49:15.047  3077  3920 D BluetoothHeadset: Proxy object connected
09-28 07:49:15.047  3077  3077 D HeadsetProfile: Bluetooth service connected
09-28 07:49:15.048  5602  5602 D HeadsetProfile: Bluetooth service connected
09-28 07:49:15.050  3077  3089 D BluetoothHeadset: Proxy object connected
,09-28 07:49:15.052   929   946 D BluetoothHeadset: Proxy object connected
09-28 07:49:15.052  3077  3077 D HeadsetProfile: Bluetooth service connected
,09-28 07:49:15.055  3761  3793 D BluetoothHeadset: Proxy object connected
,09-28 07:49:15.056  5602  5824 D BluetoothHeadset: Proxy object connected
09-28 07:49:15.056   929   946 D BluetoothHeadset: Proxy object connected
,09-28 07:49:15.056  5602  5602 D HeadsetProfile: Bluetooth service connected
,09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:18.900  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 07:49:18.906  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-28 07:49:18.906  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:18.907  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7c85a41 removed from the list
09-28 07:49:18.907  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:18.907  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:18.907  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:18.909  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:18.909  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b146be6 added. We now have 4 listener(s)
,09-28 07:49:18.910  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:49:18.913   929  3750 D WifiService: setWifiEnabled: false pid=5549, uid=10077
,09-28 07:49:18.914   929  3750 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-28 07:49:21.528   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:49:22.529   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:49:23.530   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:49:23.923  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:23.924   929  3359 D WifiService: setWifiEnabled: true pid=5549, uid=10077
09-28 07:49:23.924   929  3359 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-28 07:49:23.933   510   921 D SoftapController: Softap fwReload - Ok
,09-28 07:49:23.939   510   921 D CommandListener: Setting iface cfg
,09-28 07:49:23.939   510   921 D CommandListener: Trying to bring down wlan0
09-28 07:49:23.941   510   921 D CommandListener: Clearing all IP addresses on wlan0
,09-28 07:49:23.945   929  2925 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-28 07:49:24.532   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:49:24.615   929  2925 D wifi    : set interface wlan0 flags (UP)
,09-28 07:49:24.615   929  2925 I WifiHAL : Initializing wifi
09-28 07:49:24.615   929  2925 I WifiHAL : Creating socket
,09-28 07:49:24.622   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-28 07:49:24.625   929  2925 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-28 07:49:24.625   929  2925 D wifi    : Did set static halHandle = 0x7f94a88e00
,09-28 07:49:24.625   929  2925 D wifi    : halHandle = 0x7f94a88e00, mVM = 0x7fb10cd140, mCls = 0x1015ea
09-28 07:49:24.626   929  2925 D wifi    : array field set
09-28 07:49:24.626   929  2925 I WifiNative-HAL: interface[0] = wlan0
09-28 07:49:24.629   929  5840 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547954920960
,09-28 07:49:24.629   929  5840 D wifi    : waitForHalEvents called, vm = 0x7fb10cd140, obj = 0x1015ea, env = 0x7f92455700
,09-28 07:49:24.675  5841  5841 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-28 07:49:24.698  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 07:49:24.724  5841  5841 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-28 07:49:24.724  5841  5841 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-28 07:49:24.731   929  2925 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-28 07:49:24.744  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:24.746  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:24.749   929  2925 D WifiConfigStore: Loading config and enabling all networks 
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:24.753  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-28 07:49:24.756  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:49:24.759   929  2925 D WifiConfigStore: loaded 0 passpoint configs
09-28 07:49:24.759   929  2925 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-28 07:49:24.760   929  2925 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-28 07:49:24.760  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-28 07:49:24.761   929  2925 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-28 07:49:24.761  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-28 07:49:24.762   929  2925 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-28 07:49:24.762   929  2925 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-28 07:49:24.762   929  2925 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-28 07:49:24.762   929  2925 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-28 07:49:24.766   929  2925 D WifiNative-HAL: Setting external_sim to 1
,09-28 07:49:24.766   929  2925 D wifi    : setting dfs flag to true, 0x7f94ab1fa0
09-28 07:49:24.767   929  2925 D WifiStateMachine: Setting OUI to DA-A1-19
09-28 07:49:24.767   929  2925 D wifi    : setting scan oui 0x7f94ab1fa0
09-28 07:49:24.767   929  2925 D WifiHAL : Sending mac address OUI
,09-28 07:49:24.766  4356  4356 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-28 07:49:24.771   929  2925 E native  : do suspend false
,09-28 07:49:24.780   929  2925 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-28 07:49:24.781   929   929 D RttService: SCAN_AVAILABLE : 3
09-28 07:49:24.781   510   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-28 07:49:24.781   929  3031 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-28 07:49:24.782   510   921 D CommandListener: Setting iface cfg
,09-28 07:49:24.786   929  2924 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-28 07:49:24.786   929  2924 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-28 07:49:24.795   929  2924 D WifiNative-HAL: p2pGetDeviceAddress
09-28 07:49:24.795   929  2924 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-28 07:49:24.800   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=301999 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-28 07:49:25.534   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:49:26.535   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 07:49:27.954  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 07:49:27.963  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 07:49:27.968  5841  5841 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-28 07:49:28.000   929  2925 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-28 07:49:28.000   929  2925 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-28 07:49:28.000   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:49:28.010   929  2925 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-28 07:49:28.039   929  2925 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-28 07:49:28.042  5841  5841 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-28 07:49:28.482  5841  5841 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-28 07:49:28.523  5841  5841 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-28 07:49:28.524  5841  5841 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-28 07:49:28.533   929  2925 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-28 07:49:28.533   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:49:28.533   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-28 07:49:28.550   929  2925 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-28 07:49:28.560   510   921 D CommandListener: Setting iface cfg
,09-28 07:49:28.565   929  2925 D WifiStateMachine: Start Dhcp Watchdog 3
,09-28 07:49:28.571   929  5846 D DhcpClient: Receive thread started
,09-28 07:49:28.575   929  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-28 07:49:28.576   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-28 07:49:28.576   929  2927 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-28 07:49:28.655   929  2925 E native  : do suspend false
,09-28 07:49:28.666   929  5845 D DhcpClient: Broadcasting DHCPDISCOVER
,09-28 07:49:28.726   929  5846 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-28 07:49:28.727   929  5845 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-28 07:49:28.729   929  5845 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-28 07:49:28.766   929  5846 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-28 07:49:28.767   929  5845 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-28 07:49:28.773   510   921 D CommandListener: Setting iface cfg
,09-28 07:49:28.779   929  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-28 07:49:28.782   929  5845 D DhcpClient: Scheduling renewal in 86399s
,09-28 07:49:28.792   929  2925 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-28 07:49:28.794   929  2925 D WifiConfigStore: No blacklist allowed without epno enabled
,09-28 07:49:28.795   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-28 07:49:28.799   929  2927 D ConnectivityService: Adding iface wlan0 to network 102
,09-28 07:49:28.804   929  2925 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-28 07:49:28.845   929  2927 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-28 07:49:28.845   929  2927 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-28 07:49:28.847   929  2927 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-28 07:49:28.852   929  2927 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-28 07:49:28.856   929  2927 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-28 07:49:28.862   929  2927 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 07:49:28.869   929  2927 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-28 07:49:28.869   929  2927 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-28 07:49:28.869   929  2927 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-28 07:49:28.869   929  2925 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-28 07:49:28.869   929  2927 D ConnectivityService:    accepting network in place of null
09-28 07:49:28.869   929  2925 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-28 07:49:28.870   929  2927 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -39]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-28 07:49:28.892   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 07:49:28.914   510   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-28 07:49:28.917   929  2927 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-28 07:49:28.917   929  2927 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-28 07:49:28.917  3718  3852 W QCNEJ   : |CORE| network available: 102
09-28 07:49:28.919   929  2927 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-28 07:49:28.920   929   946 D Tethering: MasterInitialState.processMessage what=3
09-28 07:49:28.922  3718  3852 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-28 07:49:28.923  3718  3852 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-28 07:49:28.923  3718  3852 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:28.927  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:49:28.928  4964  4981 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-28 07:49:28.929  4964  4981 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-28 07:49:28.929  4964  4981 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-28 07:49:28.930  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:28.933  4964  4981 E SarControlService: no key has been found,reset the power
09-28 07:49:28.934  3951  3951 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:28.934  5549  5549 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:49:28.936  5549  5549 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:28.939  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-28 07:49:28.939  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-28 07:49:28.939  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-28 07:49:28.939  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-28 07:49:28.940  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-28 07:49:28.940  4991  4991 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-28 07:49:28.940  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:28.940  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:28.940  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b146be6 removed from the list
09-28 07:49:28.940  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:28.940  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:28.940  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:28.941  4964  5003 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-28 07:49:28.941  4964  5003 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-28 07:49:28.941  4964  5003 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-28 07:49:28.942  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-28 07:49:28.942  4991  4991 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-28 07:49:28.943  3951  3951 D SystemUpdateService: onCreate
09-28 07:49:28.944  5549  5856 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-28 07:49:28.944  5549  5856 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 07:49:28.946  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000f003000000000000ffffffff]
,09-28 07:49:28.946  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 07:49:28.947  4991  5005 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-28 07:49:28.947  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-28 07:49:28.947  4964  4975 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-28 07:49:28.947  4991  5005 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@88ec7b2 HexData = [00000000f103000000000000ffffffff]
09-28 07:49:28.947  4991  5005 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-28 07:49:28.947  4991  5005 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-28 07:49:28.948  4991  4991 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-28 07:49:28.948  4964  4974 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-28 07:49:28.949  3951  3951 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-28 07:49:28.957  3951  3951 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-28 07:49:28.963  3951  5325 I iu.UploadsManager: num queued entries: 0
,09-28 07:49:28.964  3951  5325 I iu.UploadsManager: num updated entries: 0
09-28 07:49:28.964  3951  5325 I iu.SyncManager: NEXT; no task
,09-28 07:49:28.967   929  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=306165, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 07:49:28.967  3951  3951 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-28 07:49:28.968  3951  3951 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-28 07:49:28.970  5328  5328 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-28 07:49:28.973  5328  5328 D SprintDMHelper: simOperator: 
,09-28 07:49:28.973  5328  5328 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-28 07:49:28.984  3951  5857 I SystemUpdateService: active receiver: enabled
,09-28 07:49:29.004  3951  5857 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-28 07:49:29.009  3951  5857 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-28 07:49:29.009  3951  5857 I SystemUpdateService: now status is 0 (complete)
09-28 07:49:29.009  3951  5857 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-28 07:49:29.009  3951  5857 I SystemUpdateService: file has been verified
09-28 07:49:29.010  3951  5857 I SystemUpdateService: OTA package size = 21989297
,09-28 07:49:29.015  3951  5857 I SystemUpdateService: showing system update notification
,09-28 07:49:29.023  3951  3951 D SystemUpdateService: onDestroy
,09-28 07:49:29.035   929  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-28 07:49:29.080  4356  5862 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-28 07:49:29.094   929  5843 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 28 Sep 2016 11:49:29 GMT], X-Android-Received-Millis=[1475063369093], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475063369071]}
09-28 07:49:29.095   929  2927 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-28 07:49:29.095   929  2927 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-28 07:49:29.095   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 07:49:29.096   929  2927 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-28 07:49:31.598   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 07:49:31.955  5549  5869 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-28 07:49:31.955  5549  5856 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-28 07:49:31.956  5549  5869 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-28 07:49:31.956  5549  5856 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 07:49:31.956  5549  5856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 07:49:31.956  5549  5869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 07:49:31.958  5549  5869 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 07:49:31.958  5549  5856 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 07:49:31.961  5549  5871 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:31.961  5549  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 07:49:31.961  5549  5869 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-28 07:49:31.962  5549  5856 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 07:49:31.963  5549  5872 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:31.963  5549  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:31.965  5549  5873 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:31.965  5549  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 07:49:31.967  5549  5873 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:31.967  5549  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 07:49:31.967  5549  5874 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 156, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:31.967  5549  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:31.967  5549  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:31.967  5549  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 07:49:31.967  5549  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 07:49:31.967  5549  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 07:49:31.968  5549  5874 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 156, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:31.968  5549  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:31.968  5549  5871 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 154, thread name: IncomingSocketThread/Sender): Socket closed
,09-28 07:49:31.968  5549  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:31.968  5549  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:31.968  5549  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 07:49:31.968  5549  5871 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:31.968  5549  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 07:49:31.968  5549  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-28 07:49:31.968  5549  5872 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 153, thread name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:31.968  5549  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:31.968  5549  5873 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:31.969  5549  5873 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 07:49:31.969  5549  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:31.969  5549  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:31.969  5549  5871 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 07:49:31.969  5549  5873 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-28 07:49:31.969  5549  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 07:49:31.969  5549  5874 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:31.969  5549  5871 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 07:49:31.969  5549  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 07:49:31.969  5549  5874 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-28 07:49:31.969  5549  5873 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-28 07:49:31.969  5549  5872 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:31.969  5549  5871 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 154, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:31.969  5549  5871 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 07:49:31.969  5549  5874 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 07:49:31.969  5549  5872 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-28 07:49:31.969  5549  5873 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:31.969  5549  5873 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 07:49:31.969  5549  5874 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 07:49:31.969  5549  5872 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 07:49:31.969  5549  5874 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-28 07:49:31.969  5549  5872 I io.jxcore.node.OutgoingSocketThread: The sending thread is done
09-28 07:49:31.969  5549  5872 I io.jxcore.node.OutgoingSocketThread: Both threads are done, notifying the listener...
09-28 07:49:31.970  5549  5874 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 156, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:31.970  5549  5874 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 07:49:31.970  5549  5872 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 153, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:31.970  5549  5872 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-28 07:49:34.955  5549  5595 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-28 07:49:34.957  5549  5595 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-28 07:49:34.962  5549  5595 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ae85dd6 Bundle[{}]
,09-28 07:49:34.963  5549  5595 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-28 07:49:34.964  5549  5595 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-28 07:49:34.964  5549  5595 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-28 07:49:34.965  5549  5595 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-28 07:49:34.965  5549  5595 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-28 07:49:34.967  5549  5595 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-28 07:49:34.973  5549  5595 I System.out: Running OutgoingSocketThread
,09-28 07:49:34.975  5549  5875 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-28 07:49:34.976  5549  5875 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-28 07:49:36.875   929  2927 D ConnectivityService: handlePromptUnvalidated 102
,09-28 07:49:37.645   929  2927 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-28 07:49:37.987  5549  5876 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-28 07:49:37.988  5549  5876 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-28 07:49:37.988  5549  5876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 07:49:37.988  5549  5875 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-28 07:49:37.988  5549  5875 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-28 07:49:37.989  5549  5875 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 07:49:37.989  5549  5876 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-28 07:49:37.989  5549  5875 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 07:49:37.991  5549  5876 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-28 07:49:37.996  5549  5875 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-28 07:49:37.996  5549  5878 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:37.996  5549  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-28 07:49:38.000  5549  5879 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:38.000  5549  5879 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:38.000  5549  5880 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:38.000  5549  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-28 07:49:38.001  5549  5881 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:38.001  5549  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-28 07:49:38.002  5549  5881 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 168, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:38.002  5549  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:38.002  5549  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:38.002  5549  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:38.002  5549  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 07:49:38.002  5549  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 07:49:38.002  5549  5880 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 07:49:38.003  5549  5880 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-28 07:49:38.003  5549  5881 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:38.003  5549  5881 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 07:49:38.003  5549  5880 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:38.003  5549  5880 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 07:49:38.003  5549  5881 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 07:49:38.003  5549  5881 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-28 07:49:38.003  5549  5881 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-28 07:49:38.003  5549  5881 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-28 07:49:38.004  5549  5879 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 166, thread name: OutgoingSocketThread/Sender): Socket closed
,09-28 07:49:38.004  5549  5878 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 165, thread name: IncomingSocketThread/Sender): Socket closed
09-28 07:49:38.004  5549  5879 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 166, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:38.004  5549  5879 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 07:49:38.005  5549  5878 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:38.005  5549  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-28 07:49:38.005  5549  5878 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 07:49:38.005  5549  5879 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-28 07:49:38.005  5549  5879 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-28 07:49:38.005  5549  5878 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-28 07:49:38.005  5549  5879 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 166, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:38.005  5549  5879 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-28 07:49:38.005  5549  5878 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-28 07:49:38.005  5549  5878 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-28 07:49:39.797   929  2925 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,09-28 07:49:40.986  5549  5595 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-28 07:49:40.988  5549  5595 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-28 07:49:40.988  5549  5595 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 178)
,09-28 07:49:40.994  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:40.994  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a763527 added. We now have 3 listener(s)
,09-28 07:49:40.998  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 07:49:40.998  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:40.998  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:40.998  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:40.998  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb0b3d4 added. We now have 4 listener(s)
09-28 07:49:40.999  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:49:41.000  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 07:49:41.005  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:41.012  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:49:41.014  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:49:41.015  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:49:41.015  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.015  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fab6072 added. We now have 4 listener(s)
,09-28 07:49:41.017  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 07:49:41.017  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.017  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.017  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.017  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d86fcc3 added. We now have 5 listener(s)
09-28 07:49:41.017  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.017  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 07:49:41.018  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:41.018  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:49:41.018  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:49:41.018  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.019  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.019  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:49:41.019  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.019  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.019  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a763527 removed from the list
,09-28 07:49:41.019  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.019  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb0b3d4 removed from the list
09-28 07:49:41.021  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:41.022  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:41.022  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:41.023  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.023  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:41.024  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.025  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.025  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:49:41.025  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bb0b3d4 not in the list
09-28 07:49:41.025  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.025  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:41.026  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.026  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-28 07:49:41.026  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.027  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d86fcc3 removed from the list
09-28 07:49:41.027  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.027  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.027  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.027  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.027  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-28 07:49:41.027  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fab6072 removed from the list
09-28 07:49:41.028  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 07:49:41.028  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54f3940 added. We now have 3 listener(s)
09-28 07:49:41.030  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 07:49:41.030  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.030  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.030  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.030  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad1079 added. We now have 4 listener(s)
,09-28 07:49:41.031  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.031  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 07:49:41.035  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:41.040  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:49:41.043  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.043  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 07:49:41.043  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.043  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a52a21f added. We now have 4 listener(s)
09-28 07:49:41.047  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:49:41.047  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.047  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.047  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.047  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ea96c added. We now have 5 listener(s)
09-28 07:49:41.047  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.048  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-28 07:49:41.049  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 07:49:41.049  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 07:49:41.049  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:49:41.049  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 07:49:41.049  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:41.053  5549  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 07:49:41.054  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-28 07:49:41.054  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:41.058  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 07:49:41.059  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 07:49:41.059  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 07:49:41.063  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 07:49:41.064  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 07:49:41.064  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-28 07:49:41.064  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 07:49:41.064  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-28 07:49:41.065  5549  5595 D BluetoothAdapter: STATE_ON
09-28 07:49:41.068  5787  5798 D BtGatt.GattService: registerClient() - UUID=7fc647f0-2b62-4d3c-bc50-b028ba061f06
09-28 07:49:41.069  5787  5803 D BtGatt.GattService: onClientRegistered() - UUID=7fc647f0-2b62-4d3c-bc50-b028ba061f06, clientIf=5
,09-28 07:49:41.070  5549  5559 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-28 07:49:41.071  5787  5816 D BtGatt.GattService: start scan with filters
,09-28 07:49:41.075  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 07:49:41.075  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 07:49:41.075  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-28 07:49:41.075  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 07:49:41.075  5787  5806 D BtGatt.ScanManager: handling starting scan
09-28 07:49:41.075  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 07:49:41.075  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 07:49:41.075  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-28 07:49:41.077  5787  5806 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e223f7b
,09-28 07:49:41.078  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 07:49:41.078  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 07:49:41.078  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 07:49:41.079  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-28 07:49:41.082  5549  5595 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-28 07:49:41.082  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-28 07:49:41.082  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-28 07:49:41.082  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.082  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 07:49:41.082  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.082  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-28 07:49:41.082  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-28 07:49:41.082  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 07:49:41.082  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 07:49:41.082  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 07:49:41.082  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 07:49:41.084  5549  5595 D BluetoothAdapter: STATE_ON
09-28 07:49:41.084  5787  5816 D BtGatt.GattService: stopScan() - queue size =1
09-28 07:49:41.085  5787  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 07:49:41.085  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:49:41.085  5787  5823 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 07:49:41.085  5787  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 07:49:41.086  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 07:49:41.086  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-28 07:49:41.086  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-28 07:49:41.086  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:49:41.086  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 07:49:41.086  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 07:49:41.086  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 07:49:41.086  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 07:49:41.087  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:49:41.087  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 07:49:41.087  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 07:49:41.087  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 07:49:41.088  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 07:49:41.088  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:49:41.090  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 07:49:41.090  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:49:41.091  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:49:41.092  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 07:49:41.092  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.092  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 07:49:41.093  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:49:41.093  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:49:41.093  5787  5806 D BtGatt.ScanManager: Starting BLE batch scan
09-28 07:49:41.093  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.093  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.093  5787  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 07:49:41.093  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:49:41.093  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.093  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.093  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54f3940 removed from the list
09-28 07:49:41.093  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.093  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad1079 removed from the list
09-28 07:49:41.093  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:41.093  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.094  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.094  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.096  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.096  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.096  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.096  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dad1079 not in the list
09-28 07:49:41.096  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.096  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:41.098  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.098  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.098  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.099  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58ea96c removed from the list
09-28 07:49:41.099  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.099  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.099  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.099  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.099  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.099  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a52a21f removed from the list
09-28 07:49:41.099  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.100  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72f058 added. We now have 3 listener(s)
09-28 07:49:41.101  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:49:41.101  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-28 07:49:41.101  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.101  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.101  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b55b1 added. We now have 4 listener(s)
09-28 07:49:41.101  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.102  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 07:49:41.103  5787  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 07:49:41.104  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:49:41.105  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:49:41.109  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 07:49:41.109  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:41.110  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:49:41.112  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:49:41.112  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:49:41.112  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.112  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0b617 added. We now have 4 listener(s)
,09-28 07:49:41.114  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:49:41.114  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.114  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.114  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.114  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52ba04 added. We now have 5 listener(s)
09-28 07:49:41.114  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.114  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:49:41.115  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:49:41.115  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 07:49:41.115  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-28 07:49:41.115  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:49:41.115  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 07:49:41.116  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:41.118  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-28 07:49:41.118  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.118  5787  5806 D BtGatt.ScanManager: stopping BLe Batch
09-28 07:49:41.119  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:41.120  5549  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-28 07:49:41.120  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 07:49:41.123  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 07:49:41.123  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.123  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 07:49:41.123  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 07:49:41.124  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-28 07:49:41.124  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-28 07:49:41.129  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 07:49:41.129  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 07:49:41.129  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 07:49:41.129  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 07:49:41.129  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.129  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 07:49:41.129  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-28 07:49:41.130  5549  5595 D BluetoothAdapter: STATE_ON
,09-28 07:49:41.132  5787  5823 D BtGatt.GattService: registerClient() - UUID=2ca8908e-f16a-41d2-88ed-4cc0c19f07bd
,09-28 07:49:41.132  5787  5803 D BtGatt.GattService: onClientRegistered() - UUID=2ca8908e-f16a-41d2-88ed-4cc0c19f07bd, clientIf=5
09-28 07:49:41.133  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 07:49:41.133  5787  5816 D BtGatt.GattService: start scan with filters
,09-28 07:49:41.135  5787  5806 D BtGatt.ScanManager: handling starting scan
,09-28 07:49:41.136  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 07:49:41.136  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 07:49:41.136  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:49:41.136  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 07:49:41.136  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 07:49:41.136  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 07:49:41.136  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 07:49:41.139  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 07:49:41.139  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 07:49:41.139  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 07:49:41.140  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 07:49:41.141  5787  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-28 07:49:41.141  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.141  5787  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-28 07:49:41.143  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:49:41.143  5549  5595 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-28 07:49:41.143  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:49:41.143  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:49:41.144  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:49:41.144  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.144  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.144  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 07:49:41.144  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.144  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.144  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b72f058 removed from the list
09-28 07:49:41.144  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.144  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b55b1 removed from the list
09-28 07:49:41.144  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:41.144  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 07:49:41.145  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.145  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-28 07:49:41.145  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.145  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 07:49:41.146  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 07:49:41.146  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.146  5787  5806 D BtGatt.ScanManager: Starting BLE batch scan
09-28 07:49:41.146  5787  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 07:49:41.146  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.146  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-28 07:49:41.147  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.147  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b55b1 not in the list
09-28 07:49:41.147  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 07:49:41.147  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 07:49:41.147  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 07:49:41.147  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 07:49:41.147  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-28 07:49:41.148  5549  5595 D BluetoothAdapter: STATE_ON
,09-28 07:49:41.149  5787  5797 D BtGatt.GattService: stopScan() - queue size =1
,09-28 07:49:41.149  5787  5798 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 07:49:41.150  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 07:49:41.150  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 07:49:41.150  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 07:49:41.150  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:49:41.150  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 07:49:41.150  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 07:49:41.150  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 07:49:41.150  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-28 07:49:41.151  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:49:41.151  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 07:49:41.151  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 07:49:41.151  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-28 07:49:41.151  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 07:49:41.151  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.152  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.152  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.152  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.152  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:49:41.152  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@52ba04 removed from the list
09-28 07:49:41.152  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.152  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 07:49:41.152  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.152  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:49:41.152  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.152  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.152  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.153  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c0b617 removed from the list
09-28 07:49:41.153  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.153  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a437270 added. We now have 3 listener(s)
09-28 07:49:41.154  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:49:41.154  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.154  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.155  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.155  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3609e9 added. We now have 4 listener(s)
09-28 07:49:41.155  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.156  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-28 07:49:41.156  5787  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 07:49:41.156  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.158  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:49:41.161  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-28 07:49:41.161  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:41.162  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:49:41.165  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.165  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:49:41.165  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.166  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e510f added. We now have 4 listener(s)
09-28 07:49:41.167  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 07:49:41.167  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:49:41.167  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.167  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.167  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.167  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.167  5787  5806 D BtGatt.ScanManager: stopping BLe Batch
09-28 07:49:41.167  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@945459c added. We now have 5 listener(s)
09-28 07:49:41.167  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.167  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:49:41.167  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-28 07:49:41.167  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-28 07:49:41.167  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-28 07:49:41.167  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-28 07:49:41.169  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:41.170  5549  5595 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-28 07:49:41.170  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-28 07:49:41.172  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:49:41.172  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 07:49:41.172  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.172  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-28 07:49:41.173  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-28 07:49:41.174  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-28 07:49:41.174  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-28 07:49:41.177  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 07:49:41.177  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-28 07:49:41.178  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-28 07:49:41.178  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-28 07:49:41.178  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-28 07:49:41.178  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-28 07:49:41.178  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-28 07:49:41.179  5549  5595 D BluetoothAdapter: STATE_ON
,09-28 07:49:41.180  5787  5797 D BtGatt.GattService: registerClient() - UUID=dc288133-1199-42e3-9014-046f6b50e75e
09-28 07:49:41.181  5787  5803 D BtGatt.GattService: onClientRegistered() - UUID=dc288133-1199-42e3-9014-046f6b50e75e, clientIf=5
09-28 07:49:41.181  5549  5560 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-28 07:49:41.181  5787  5823 D BtGatt.GattService: start scan with filters
,09-28 07:49:41.183  5787  5806 D BtGatt.ScanManager: handling starting scan
,09-28 07:49:41.184  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-28 07:49:41.184  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-28 07:49:41.184  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-28 07:49:41.184  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-28 07:49:41.184  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-28 07:49:41.185  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-28 07:49:41.185  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-28 07:49:41.187  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-28 07:49:41.187  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-28 07:49:41.188  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-28 07:49:41.188  5787  5803 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-28 07:49:41.188  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.189  5787  5806 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-28 07:49:41.189  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-28 07:49:41.193  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-28 07:49:41.193  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.193  5787  5806 D BtGatt.ScanManager: Starting BLE batch scan
,09-28 07:49:41.193  5787  5806 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-28 07:49:41.194  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-28 07:49:41.194  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:49:41.194  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:49:41.194  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.194  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.194  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-28 07:49:41.194  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.194  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.194  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a437270 removed from the list
09-28 07:49:41.194  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.194  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3609e9 removed from the list
09-28 07:49:41.194  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:41.195  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:49:41.195  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.195  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-28 07:49:41.195  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.195  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-28 07:49:41.196  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.196  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.196  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.196  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3609e9 not in the list
09-28 07:49:41.196  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-28 07:49:41.196  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-28 07:49:41.196  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-28 07:49:41.196  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-28 07:49:41.196  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-28 07:49:41.197  5549  5595 D BluetoothAdapter: STATE_ON
09-28 07:49:41.197  5787  5798 D BtGatt.GattService: stopScan() - queue size =1
,09-28 07:49:41.200  5787  5797 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-28 07:49:41.200  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-28 07:49:41.201  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-28 07:49:41.201  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-28 07:49:41.201  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-28 07:49:41.201  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-28 07:49:41.201  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-28 07:49:41.201  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-28 07:49:41.201  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-28 07:49:41.202  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-28 07:49:41.202  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-28 07:49:41.202  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-28 07:49:41.202  5549  5595 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-28 07:49:41.202  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-28 07:49:41.202  5787  5803 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-28 07:49:41.202  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.202  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.203  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.203  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.203  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.203  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-28 07:49:41.203  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@945459c removed from the list
09-28 07:49:41.203  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.203  5549  5549 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-28 07:49:41.203  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.203  5549  5549 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-28 07:49:41.203  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.203  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-28 07:49:41.204  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.204  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16e510f removed from the list
09-28 07:49:41.204  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.204  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2f1f88 added. We now have 3 listener(s)
09-28 07:49:41.205  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-28 07:49:41.205  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.205  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.206  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.206  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc0d21 added. We now have 4 listener(s)
09-28 07:49:41.206  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:49:41.207  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 07:49:41.207  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-28 07:49:41.207  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.209  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:49:41.213  5787  5803 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-28 07:49:41.213  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.213  5787  5806 D BtGatt.ScanManager: stopping BLe Batch
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:49:41.214  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:49:41.216  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:49:41.216  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-28 07:49:41.216  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-28 07:49:41.216  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe55307 added. We now have 4 listener(s)
09-28 07:49:41.217  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:49:41.217  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:49:41.217  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:49:41.217  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:49:41.217  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25aac34 added. We now have 5 listener(s)
09-28 07:49:41.218  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:49:41.218  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:49:41.218  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:49:41.218  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-28 07:49:41.218  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:41.218  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.218  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.218  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-28 07:49:41.218  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 07:49:41.218  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.218  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2f1f88 removed from the list
09-28 07:49:41.218  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.218  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc0d21 removed from the list
09-28 07:49:41.219  5787  5803 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-28 07:49:41.219  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.220  5787  5806 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-28 07:49:41.220  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-28 07:49:41.220  5549  5595 D io.jxcore.node.ConnectivityMonitor: stop
09-28 07:49:41.220  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-28 07:49:41.221  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.221  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.222  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.222  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.222  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-28 07:49:41.222  5549  5595 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dc0d21 not in the list
09-28 07:49:41.222  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.222  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.223  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-28 07:49:41.223  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-28 07:49:41.223  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-28 07:49:41.223  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25aac34 removed from the list
09-28 07:49:41.223  5549  5595 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-28 07:49:41.223  5549  5595 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-28 07:49:41.223  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-28 07:49:41.223  5549  5595 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-28 07:49:41.223  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-28 07:49:41.223  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe55307 removed from the list
09-28 07:49:41.224  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-28 07:49:41.224  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-28 07:49:41.224  5787  5803 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-28 07:49:41.224  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-28 07:49:41.224  5787  5803 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-28 07:49:41.224  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:49:41.224  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-28 07:49:41.224  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:49:41.591  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 07:49:41.654  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 07:49:41.704  5549  5549 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-28 07:49:43.370  5549  5882 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 07:49:43.370  5549  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:44.202  5549  5882 W !!      : call onHalfStreamCopied
09-28 07:49:44.202  5549  5882 I testCopyDataAndClose: closing input stream
,09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 186, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-28 07:49:44.979  5549  5882 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-28 07:49:48.696  5549  5883 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:48.696  5549  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:50.499   929  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=327697, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 07:49:50.696  5549  5595 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 189. Connection data: Peer properties: [null null].
09-28 07:49:50.696  5549  5595 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:50.696  5549  5595 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 189, name: My test thread name)
,09-28 07:49:50.731  5549  5883 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-28 07:49:50.731  5549  5883 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:50.731  5549  5883 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-28 07:49:50.833  5549  5884 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 07:49:50.833  5549  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:51.536   567   567 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-28 07:49:51.536   567   567 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 191, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-28 07:49:52.445  5549  5884 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-28 07:49:56.178  5549  5885 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:56.178  5549  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-28 07:49:56.178  5549  5885 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 193, thread name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:56.178  5549  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:56.178  5549  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-28 07:49:56.178  5549  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:56.178  5549  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-28 07:49:56.179  5549  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-28 07:49:56.179  5549  5885 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-28 07:49:56.179  5549  5885 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-28 07:49:56.179  5549  5885 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-28 07:49:56.179  5549  5885 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:56.179  5549  5885 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-28 07:49:56.181  5549  5595 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-28 07:49:56.184  5549  5886 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:56.184  5549  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-28 07:49:56.184  5549  5886 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 197, thread name: My test thread name): Test exception.
,09-28 07:49:56.185  5549  5886 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:56.185  5549  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-28 07:49:56.185  5549  5886 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-28 07:49:56.185  5549  5886 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-28 07:49:56.185  5549  5886 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-28 07:49:56.190  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-28 07:49:56.190  5549  5595 I jxcore-log: 
,09-28 07:49:56.190  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-28 07:49:56.190  5549  5595 I jxcore-log: 
09-28 07:49:56.191  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-28 07:49:56.191  5549  5595 I jxcore-log: 
09-28 07:49:56.191  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-28 07:49:56.191  5549  5595 I jxcore-log: 
09-28 07:49:56.191  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Total duration:  102800'
09-28 07:49:56.191  5549  5595 I jxcore-log: 
09-28 07:49:56.192  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Failures: 
09-28 07:49:56.192  5549  5595 I jxcore-log:  IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-28 07:49:56.192  5549  5595 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-28 07:49:56.192  5549  5595 I jxcore-log:      but: was ""
09-28 07:49:56.192  5549  5595 I jxcore-log: IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-28 07:49:56.192  5549  5595 I jxcore-log: Expected: is "Nullam in massa. Vivamus elit odio, in neque ut congue quis, venenatis placerat, nulla ornare suscipit, erat urna, pellentesque dapibus vel, lorem. Sed egestas non, dolor. Aliquam hendrerit sollicitudin sed."
09-28 07:49:56.192  5549  5595 I jxcore-log:      but: was ""
09-28 07:49:56.192  5549  5595 I jxcore-log: '
09-28 07:49:56.192  5549  5595 I jxcore-log: 
09-28 07:49:56.193  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-28 07:49:56.193  5549  5595 I jxcore-log: 
,09-28 07:49:56.194  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-28 07:49:56.194  5549  5595 I jxcore-log: 
,09-28 07:49:56.197  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.197  5549  5595 I jxcore-log: 
,09-28 07:49:56.198  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.198  5549  5595 I jxcore-log: 
09-28 07:49:56.198  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.198  5549  5595 I jxcore-log: 
09-28 07:49:56.198  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.198  5549  5595 I jxcore-log: 
09-28 07:49:56.199  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 07:49:56.199  5549  5595 I jxcore-log: 
,09-28 07:49:56.199  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 07:49:56.199  5549  5595 I jxcore-log: 
09-28 07:49:56.199  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.199  5549  5595 I jxcore-log: 
09-28 07:49:56.200  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.200  5549  5595 I jxcore-log: 
09-28 07:49:56.200  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-28 07:49:56.200  5549  5595 I jxcore-log: 
09-28 07:49:56.200  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 07:49:56.200  5549  5595 I jxcore-log: 
09-28 07:49:56.200  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 07:49:56.200  5549  5595 I jxcore-log: 
09-28 07:49:56.201  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.201  5549  5595 I jxcore-log: 
09-28 07:49:56.201  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.201  5549  5595 I jxcore-log: 
09-28 07:49:56.201  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.201  5549  5595 I jxcore-log: 
09-28 07:49:56.201  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.201  5549  5595 I jxcore-log: 
09-28 07:49:56.202  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.202  5549  5595 I jxcore-log: 
,09-28 07:49:56.202  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.202  5549  5595 I jxcore-log: 
09-28 07:49:56.202  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.202  5549  5595 I jxcore-log: 
09-28 07:49:56.203  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.203  5549  5595 I jxcore-log: 
09-28 07:49:56.203  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.203  5549  5595 I jxcore-log: 
09-28 07:49:56.203  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.203  5549  5595 I jxcore-log: 
09-28 07:49:56.203  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.203  5549  5595 I jxcore-log: 
09-28 07:49:56.205  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.205  5549  5595 I jxcore-log: 
09-28 07:49:56.205  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.205  5549  5595 I jxcore-log: 
09-28 07:49:56.205  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.205  5549  5595 I jxcore-log: 
09-28 07:49:56.205  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.205  5549  5595 I jxcore-log: 
09-28 07:49:56.206  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.206  5549  5595 I jxcore-log: 
09-28 07:49:56.206  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.206  5549  5595 I jxcore-log: 
09-28 07:49:56.206  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.206  5549  5595 I jxcore-log: 
09-28 07:49:56.206  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.206  5549  5595 I jxcore-log: 
09-28 07:49:56.207  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.207  5549  5595 I jxcore-log: 
09-28 07:49:56.207  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.207  5549  5595 I jxcore-log: 
09-28 07:49:56.207  5549  5595 I jxcore-log:, 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.207  5549  5595 I jxcore-log: 
09-28 07:49:56.207  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.207  5549  5595 I jxcore-log: 
09-28 07:49:56.208  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.208  5549  5595 I jxcore-log: 
09-28 07:49:56.208  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.208  5549  5595 I jxcore-log: 
09-28 07:49:56.208  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.208  5549  5595 I jxcore-log: 
09-28 07:49:56.208  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.208  5549  5595 I jxcore-log: 
09-28 07:49:56.209  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-28 07:49:56.209  5549  5595 I jxcore-log: 
09-28 07:49:56.209  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.209  5549  5595 I jxcore-log: 
09-28 07:49:56.209  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-28 07:49:56.209  5549  5595 I jxcore-log: 
09-28 07:49:56.209  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.209  5549  5595 I jxcore-log: 
09-28 07:49:56.209  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.209  5549  5595 I jxcore-log: 
09-28 07:49:56.210  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.210  5549  5595 I jxcore-log: 
09-28 07:49:56.210  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.210  5549  5595 I jxcore-log: 
09-28 07:49:56.210  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.210  5549  5595 I jxcore-log: 
09-28 07:49:56.210  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-28 07:49:56.210  5549  5595 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-28 07:49:56.211  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.211  5549  5595 I jxcore-log: 
09-28 07:49:56.211  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.211  5549  5595 I jxcore-log: 
09-28 07:49:56.211  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-28 07:49:56.211  5549  5595 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-28 07:49:56.211  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:49:56.211  5549  5595 I jxcore-log: 
09-28 07:49:56.211  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 07:49:56.211  5549  5595 I jxcore-log: 
09-28 07:49:56.212  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 07:49:56.212  5549  5595 I jxcore-log: 
09-28 07:49:56.212  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-28 07:49:56.212  5549  5595 I jxcore-log: 
,09-28 07:49:56.217  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-28 07:49:56.217  5549  5595 I jxcore-log: 
09-28 07:49:56.217  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - WARN testUtils: 'myNameCallback not set!'
09-28 07:49:56.217  5549  5595 I jxcore-log: 
09-28 07:49:56.218  5549  5549 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-28 07:49:56.218  5549  5595 I jxcore-log: 2016-09-28 11:49:56 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-28 07:49:56.218  5549  5595 I jxcore-log: 
,09-28 07:49:58.258  5549  5595 I jxcore-log: 2016-09-28 11:49:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-28 07:49:58.258  5549  5595 I jxcore-log: 
,09-28 07:49:58.583  5549  5595 I jxcore-log: 2016-09-28 11:49:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-28 07:49:58.583  5549  5595 I jxcore-log: 
,09-28 07:49:58.595  5549  5595 I jxcore-log: 2016-09-28 11:49:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-28 07:49:58.595  5549  5595 I jxcore-log: 
,09-28 07:49:59.687  5549  5595 I jxcore-log: 2016-09-28 11:49:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-28 07:49:59.687  5549  5595 I jxcore-log: 
,09-28 07:49:59.847  5549  5595 I jxcore-log: 2016-09-28 11:49:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-28 07:49:59.847  5549  5595 I jxcore-log: 
,09-28 07:49:59.852  5549  5595 I jxcore-log: 2016-09-28 11:49:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-28 07:49:59.852  5549  5595 I jxcore-log: 
,09-28 07:49:59.857  5549  5595 I jxcore-log: 2016-09-28 11:49:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-28 07:49:59.857  5549  5595 I jxcore-log: 
,09-28 07:50:00.381  5549  5595 I jxcore-log: 2016-09-28 11:50:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-28 07:50:00.381  5549  5595 I jxcore-log: 
,09-28 07:50:00.432  5549  5595 I jxcore-log: 2016-09-28 11:50:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-28 07:50:00.432  5549  5595 I jxcore-log: 
,09-28 07:50:00.445  5549  5595 I jxcore-log: 2016-09-28 11:50:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-28 07:50:00.445  5549  5595 I jxcore-log: 
,09-28 07:50:00.449  5549  5595 I jxcore-log: 2016-09-28 11:50:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-28 07:50:00.449  5549  5595 I jxcore-log: 
,09-28 07:50:00.720  5549  5595 I jxcore-log: 2016-09-28 11:50:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-28 07:50:00.720  5549  5595 I jxcore-log: 
,09-28 07:50:00.844  5549  5595 I jxcore-log: 2016-09-28 11:50:00 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-28 07:50:00.844  5549  5595 I jxcore-log: 
,09-28 07:50:01.213  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-28 07:50:01.213  5549  5595 I jxcore-log: 
,09-28 07:50:01.221  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-28 07:50:01.221  5549  5595 I jxcore-log: 
,09-28 07:50:01.224  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-28 07:50:01.224  5549  5595 I jxcore-log: 
,09-28 07:50:01.229  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-28 07:50:01.229  5549  5595 I jxcore-log: 
,09-28 07:50:01.234  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-28 07:50:01.234  5549  5595 I jxcore-log: 
,09-28 07:50:01.260  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-28 07:50:01.260  5549  5595 I jxcore-log: 
,09-28 07:50:01.294  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-28 07:50:01.294  5549  5595 I jxcore-log: 
,09-28 07:50:01.300  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-28 07:50:01.300  5549  5595 I jxcore-log: 
,09-28 07:50:01.306  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-28 07:50:01.306  5549  5595 I jxcore-log: 
,09-28 07:50:01.320  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-28 07:50:01.320  5549  5595 I jxcore-log: 
,09-28 07:50:01.325  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-28 07:50:01.325  5549  5595 I jxcore-log: 
,09-28 07:50:01.331  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-28 07:50:01.331  5549  5595 I jxcore-log: 
,09-28 07:50:01.336  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-28 07:50:01.336  5549  5595 I jxcore-log: 
,09-28 07:50:01.349  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-28 07:50:01.349  5549  5595 I jxcore-log: 
,09-28 07:50:01.370  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-28 07:50:01.370  5549  5595 I jxcore-log: 
,09-28 07:50:01.379  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-28 07:50:01.379  5549  5595 I jxcore-log: 
,09-28 07:50:01.390  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-28 07:50:01.390  5549  5595 I jxcore-log: 
,09-28 07:50:01.399  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-28 07:50:01.399  5549  5595 I jxcore-log: 
,09-28 07:50:01.411  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-28 07:50:01.411  5549  5595 I jxcore-log: 
,09-28 07:50:01.420  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-28 07:50:01.420  5549  5595 I jxcore-log: 
,09-28 07:50:01.425  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-28 07:50:01.425  5549  5595 I jxcore-log: 
,09-28 07:50:01.446  5549  5595 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-28 07:50:01.447  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - INFO testUtils: 'BLE multiple advertisement supported'
09-28 07:50:01.447  5549  5595 I jxcore-log: 
,09-28 07:50:01.553  5549  5595 I jxcore-log: 2016-09-28 11:50:01 - DEBUG CoordinatedClient: 'connected to the test server'
09-28 07:50:01.553  5549  5595 I jxcore-log: 
,09-28 07:50:02.031  5549  5595 I jxcore-log: TAP version 13
09-28 07:50:02.031  5549  5595 I jxcore-log: 
,09-28 07:50:02.070  5549  5595 I jxcore-log: # setup
09-28 07:50:02.070  5549  5595 I jxcore-log: 
,09-28 07:50:03.208  5549  5595 I jxcore-log: # calling createNativeListener directly rejects
09-28 07:50:03.208  5549  5595 I jxcore-log: 
,09-28 07:50:03.577  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:03.577  5549  5595 I jxcore-log: 
,09-28 07:50:03.587  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'listening 37948'
09-28 07:50:03.587  5549  5595 I jxcore-log: 
,09-28 07:50:03.596  5549  5595 I jxcore-log: ok 1 Should throw
09-28 07:50:03.596  5549  5595 I jxcore-log: 
,09-28 07:50:03.604  5549  5595 I jxcore-log: # teardown
09-28 07:50:03.604  5549  5595 I jxcore-log: 
,09-28 07:50:03.671  5549  5595 I jxcore-log: # setup
09-28 07:50:03.671  5549  5595 I jxcore-log: 
,09-28 07:50:03.748  5549  5595 I jxcore-log: # emits incomingConnectionState
09-28 07:50:03.748  5549  5595 I jxcore-log: 
,09-28 07:50:03.826  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:03.826  5549  5595 I jxcore-log: 
,09-28 07:50:03.831  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'listening 39976',
09-28 07:50:03.831  5549  5595 I jxcore-log: 
,09-28 07:50:03.840  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:03.840  5549  5595 I jxcore-log: 
,09-28 07:50:03.843  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:03.843  5549  5595 I jxcore-log: 
,09-28 07:50:03.854  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'new mux'
09-28 07:50:03.854  5549  5595 I jxcore-log: 
,09-28 07:50:03.859  5549  5595 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-28 07:50:03.859  5549  5595 I jxcore-log: 
,09-28 07:50:03.885  5549  5595 I jxcore-log: 2016-09-28 11:50:03 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:03.885  5549  5595 I jxcore-log: 
,09-28 07:50:03.886  5549  5595 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-28 07:50:03.886  5549  5595 I jxcore-log: 
,09-28 07:50:03.893  5549  5595 I jxcore-log: # teardown
09-28 07:50:03.893  5549  5595 I jxcore-log: 
,09-28 07:50:03.950  5549  5595 I jxcore-log: # setup
09-28 07:50:03.950  5549  5595 I jxcore-log: 
,09-28 07:50:04.073  5549  5595 I jxcore-log: # emits routerPortConnectionFailed
09-28 07:50:04.073  5549  5595 I jxcore-log: 
,09-28 07:50:04.158  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:04.158  5549  5595 I jxcore-log: 
,09-28 07:50:04.162  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'listening 39805'
09-28 07:50:04.162  5549  5595 I jxcore-log: 
,09-28 07:50:04.170  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:04.170  5549  5595 I jxcore-log: 
,09-28 07:50:04.172  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:04.172  5549  5595 I jxcore-log: 
,09-28 07:50:04.175  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new mux'
09-28 07:50:04.175  5549  5595 I jxcore-log: 
,09-28 07:50:04.203  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:04.203  5549  5595 I jxcore-log: 
,09-28 07:50:04.206  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:04.206  5549  5595 I jxcore-log: 
,09-28 07:50:04.210  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: ''
09-28 07:50:04.210  5549  5595 I jxcore-log: 
,09-28 07:50:04.211  5549  5595 I jxcore-log: ok 4 tried to connect to right port
09-28 07:50:04.211  5549  5595 I jxcore-log: 
,09-28 07:50:04.212  5549  5595 I jxcore-log: ok 5 failed due to refused connection
09-28 07:50:04.212  5549  5595 I jxcore-log: 
,09-28 07:50:04.213  5549  5595 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-28 07:50:04.213  5549  5595 I jxcore-log: 
,09-28 07:50:04.216  5549  5595 I jxcore-log: # teardown
09-28 07:50:04.216  5549  5595 I jxcore-log: 
,09-28 07:50:04.219  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:04.219  5549  5595 I jxcore-log: 
,09-28 07:50:04.267  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'mux close'
09-28 07:50:04.267  5549  5595 I jxcore-log: 
,09-28 07:50:04.272  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:04.272  5549  5595 I jxcore-log: 
,09-28 07:50:04.282  5549  5595 I jxcore-log: # setup
09-28 07:50:04.282  5549  5595 I jxcore-log: 
,09-28 07:50:04.370  5549  5595 I jxcore-log: # native server connections all up
09-28 07:50:04.370  5549  5595 I jxcore-log: 
,09-28 07:50:04.462  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:04.462  5549  5595 I jxcore-log: 
,09-28 07:50:04.464  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'listening 37998'
09-28 07:50:04.464  5549  5595 I jxcore-log: 
,09-28 07:50:04.470  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:04.470  5549  5595 I jxcore-log: 
,09-28 07:50:04.471  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:04.471  5549  5595 I jxcore-log: 
,09-28 07:50:04.473  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new mux'
09-28 07:50:04.473  5549  5595 I jxcore-log: 
,09-28 07:50:04.503  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:04.503  5549  5595 I jxcore-log: 
,09-28 07:50:04.507  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:04.507  5549  5595 I jxcore-log: 
,09-28 07:50:04.510  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:04.510  5549  5595 I jxcore-log: 
,09-28 07:50:04.512  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:04.512  5549  5595 I jxcore-log: 
,09-28 07:50:04.530  5549  5595 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-28 07:50:04.530  5549  5595 I jxcore-log: 
,09-28 07:50:04.531  5549  5595 I jxcore-log: ok 8 Send/recvd #1 should be same
09-28 07:50:04.531  5549  5595 I jxcore-log: 
,09-28 07:50:04.533  5549  5595 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-28 07:50:04.533  5549  5595 I jxcore-log: 
,09-28 07:50:04.534  5549  5595 I jxcore-log: ok 10 Send/recvd #2 should be same
09-28 07:50:04.534  5549  5595 I jxcore-log: 
,09-28 07:50:04.536  5549  5595 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-28 07:50:04.536  5549  5595 I jxcore-log: 
,09-28 07:50:04.543  5549  5595 I jxcore-log: # teardown
09-28 07:50:04.543  5549  5595 I jxcore-log: 
,09-28 07:50:04.617  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:04.617  5549  5595 I jxcore-log: 
,09-28 07:50:04.621  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:04.621  5549  5595 I jxcore-log: 
,09-28 07:50:04.624  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'mux close'
09-28 07:50:04.624  5549  5595 I jxcore-log: 
,09-28 07:50:04.629  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:04.629  5549  5595 I jxcore-log: 
,09-28 07:50:04.639  5549  5595 I jxcore-log: # setup
09-28 07:50:04.639  5549  5595 I jxcore-log: 
,09-28 07:50:04.725  5549  5595 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-28 07:50:04.725  5549  5595 I jxcore-log: 
,09-28 07:50:04.805  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:04.805  5549  5595 I jxcore-log: 
,09-28 07:50:04.812  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'listening 38674'
09-28 07:50:04.812  5549  5595 I jxcore-log: 
,09-28 07:50:04.819  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:04.819  5549  5595 I jxcore-log: 
,09-28 07:50:04.820  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:04.820  5549  5595 I jxcore-log: 
,09-28 07:50:04.824  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new mux'
09-28 07:50:04.824  5549  5595 I jxcore-log: 
,09-28 07:50:04.839  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:04.839  5549  5595 I jxcore-log: 
,09-28 07:50:04.842  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:04.842  5549  5595 I jxcore-log: 
,09-28 07:50:04.854  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:04.854  5549  5595 I jxcore-log: 
,09-28 07:50:04.865  5549  5595 I jxcore-log: ok 12 socket shouldn't close until after stream
09-28 07:50:04.865  5549  5595 I jxcore-log: 
,09-28 07:50:04.865  5549  5595 I jxcore-log: ok 13 incoming remains open
09-28 07:50:04.865  5549  5595 I jxcore-log: 
,09-28 07:50:04.871  5549  5595 I jxcore-log: # teardown
09-28 07:50:04.871  5549  5595 I jxcore-log: 
,09-28 07:50:04.929  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'mux close'
09-28 07:50:04.929  5549  5595 I jxcore-log: 
,09-28 07:50:04.934  5549  5595 I jxcore-log: 2016-09-28 11:50:04 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:04.934  5549  5595 I jxcore-log: 
,09-28 07:50:04.940  5549  5595 I jxcore-log: # setup
09-28 07:50:04.940  5549  5595 I jxcore-log: 
,09-28 07:50:05.035  5549  5595 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-28 07:50:05.035  5549  5595 I jxcore-log: 
,09-28 07:50:05.114  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:05.114  5549  5595 I jxcore-log: 
,09-28 07:50:05.120  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'listening 44506'
09-28 07:50:05.120  5549  5595 I jxcore-log: 
,09-28 07:50:05.128  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:05.128  5549  5595 I jxcore-log: 
,09-28 07:50:05.130  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:05.130  5549  5595 I jxcore-log: 
,09-28 07:50:05.132  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new mux'
09-28 07:50:05.132  5549  5595 I jxcore-log: 
,09-28 07:50:05.143  5549  5595 I jxcore-log: ok 14 we should not have gotten an error
09-28 07:50:05.143  5549  5595 I jxcore-log: 
,09-28 07:50:05.152  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:05.152  5549  5595 I jxcore-log: 
,09-28 07:50:05.157  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:05.157  5549  5595 I jxcore-log: 
,09-28 07:50:05.165  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:05.165  5549  5595 I jxcore-log: 
,09-28 07:50:05.167  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:05.167  5549  5595 I jxcore-log: 
,09-28 07:50:05.174  5549  5595 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-28 07:50:05.174  5549  5595 I jxcore-log: 
,09-28 07:50:05.174  5549  5595 I jxcore-log: ok 16 incoming is cleaned up
09-28 07:50:05.174  5549  5595 I jxcore-log: 
,09-28 07:50:05.177  5549  5595 I jxcore-log: # teardown
09-28 07:50:05.177  5549  5595 I jxcore-log: 
,09-28 07:50:05.248  5549  5595 I jxcore-log: # setup
09-28 07:50:05.248  5549  5595 I jxcore-log: 
,09-28 07:50:05.323  5549  5595 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-28 07:50:05.323  5549  5595 I jxcore-log: 
,09-28 07:50:05.386  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:05.386  5549  5595 I jxcore-log: 
,09-28 07:50:05.391  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'listening 37835'
09-28 07:50:05.391  5549  5595 I jxcore-log: 
,09-28 07:50:05.400  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:05.400  5549  5595 I jxcore-log: 
,09-28 07:50:05.402  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:05.402  5549  5595 I jxcore-log: 
,09-28 07:50:05.405  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new mux'
09-28 07:50:05.405  5549  5595 I jxcore-log: 
,09-28 07:50:05.418  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:05.418  5549  5595 I jxcore-log: 
,09-28 07:50:05.421  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:05.421  5549  5595 I jxcore-log: 
,09-28 07:50:05.434  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:05.434  5549  5595 I jxcore-log: 
,09-28 07:50:05.447  5549  5595 I jxcore-log: ok 17 stream was closed
09-28 07:50:05.447  5549  5595 I jxcore-log: 
,09-28 07:50:05.448  5549  5595 I jxcore-log: ok 18 incoming should survive
09-28 07:50:05.448  5549  5595 I jxcore-log: 
09-28 07:50:05.448  5549  5595 I jxcore-log: ok 19 mux should have no streams
09-28 07:50:05.448  5549  5595 I jxcore-log: 
,09-28 07:50:05.453  5549  5595 I jxcore-log: # teardown
09-28 07:50:05.453  5549  5595 I jxcore-log: 
,09-28 07:50:05.506  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'mux close'
09-28 07:50:05.506  5549  5595 I jxcore-log: 
,09-28 07:50:05.512  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:05.512  5549  5595 I jxcore-log: 
,09-28 07:50:05.520  5549  5595 I jxcore-log: # setup
09-28 07:50:05.520  5549  5595 I jxcore-log: 
,09-28 07:50:05.663  5549  5595 I jxcore-log: # native server - closing the whole server cleans everything up
09-28 07:50:05.663  5549  5595 I jxcore-log: 
,09-28 07:50:05.741  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:05.741  5549  5595 I jxcore-log: 
,09-28 07:50:05.750  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'listening 38506'
09-28 07:50:05.750  5549  5595 I jxcore-log: 
,09-28 07:50:05.760  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:05.760  5549  5595 I jxcore-log: 
,09-28 07:50:05.762  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:05.762  5549  5595 I jxcore-log: 
,09-28 07:50:05.765  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new mux'
09-28 07:50:05.765  5549  5595 I jxcore-log: 
,09-28 07:50:05.776  5549  5595 I jxcore-log: ok 20 we should not have gotten an error
09-28 07:50:05.776  5549  5595 I jxcore-log: 
,09-28 07:50:05.788  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:05.788  5549  5595 I jxcore-log: 
,09-28 07:50:05.791  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:05.791  5549  5595 I jxcore-log: 
,09-28 07:50:05.800  5549  5595 I jxcore-log: ok 21 Buffers are identical
09-28 07:50:05.800  5549  5595 I jxcore-log: 
,09-28 07:50:05.802  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:05.802  5549  5595 I jxcore-log: 
09-28 07:50:05.804  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'mux close'
09-28 07:50:05.804  5549  5595 I jxcore-log: 
,09-28 07:50:05.807  5549  5595 I jxcore-log: ok 22 native server is nulled out
09-28 07:50:05.807  5549  5595 I jxcore-log: 
,09-28 07:50:05.807  5549  5595 I jxcore-log: ok 23 native server should be closed
09-28 07:50:05.807  5549  5595 I jxcore-log: 
09-28 07:50:05.808  5549  5595 I jxcore-log: ok 24 incoming has been removed
09-28 07:50:05.808  5549  5595 I jxcore-log: 
09-28 07:50:05.808  5549  5595 I jxcore-log: ok 25 Incoming should be done
09-28 07:50:05.808  5549  5595 I jxcore-log: 
,09-28 07:50:05.808  5549  5595 I jxcore-log: ok 26 The mux object should be closed
09-28 07:50:05.808  5549  5595 I jxcore-log: 
09-28 07:50:05.809  5549  5595 I jxcore-log: ok 27 The mux stream should be closed
09-28 07:50:05.809  5549  5595 I jxcore-log: 
09-28 07:50:05.809  5549  5595 I jxcore-log: 2016-09-28 11:50:05 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:05.809  5549  5595 I jxcore-log: 
,09-28 07:50:05.822  5549  5595 I jxcore-log: # teardown
09-28 07:50:05.822  5549  5595 I jxcore-log: 
,09-28 07:50:05.869  5549  5595 I jxcore-log: # setup
09-28 07:50:05.869  5549  5595 I jxcore-log: 
,09-28 07:50:05.922  5549  5595 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-28 07:50:05.922  5549  5595 I jxcore-log: 
,09-28 07:50:06.003  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:06.003  5549  5595 I jxcore-log: 
,09-28 07:50:06.009  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'listening 42079'
09-28 07:50:06.009  5549  5595 I jxcore-log: 
,09-28 07:50:06.043  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.043  5549  5595 I jxcore-log: 
09-28 07:50:06.044  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.044  5549  5595 I jxcore-log: 
,09-28 07:50:06.046  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.046  5549  5595 I jxcore-log: 
,09-28 07:50:06.049  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.049  5549  5595 I jxcore-log: 
,09-28 07:50:06.050  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.050  5549  5595 I jxcore-log: 
09-28 07:50:06.051  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.051  5549  5595 I jxcore-log: 
,09-28 07:50:06.053  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.053  5549  5595 I jxcore-log: 
,09-28 07:50:06.054  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.054  5549  5595 I jxcore-log: 
,09-28 07:50:06.055  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.055  5549  5595 I jxcore-log: 
,09-28 07:50:06.058  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.058  5549  5595 I jxcore-log: 
,09-28 07:50:06.059  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.059  5549  5595 I jxcore-log: 
09-28 07:50:06.059  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.059  5549  5595 I jxcore-log: 
,09-28 07:50:06.062  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.062  5549  5595 I jxcore-log: 
,09-28 07:50:06.063  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.063  5549  5595 I jxcore-log: 
,09-28 07:50:06.065  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.065  5549  5595 I jxcore-log: 
,09-28 07:50:06.067  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.067  5549  5595 I jxcore-log: 
09-28 07:50:06.068  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.068  5549  5595 I jxcore-log: 
,09-28 07:50:06.069  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.069  5549  5595 I jxcore-log: 
,09-28 07:50:06.071  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.071  5549  5595 I jxcore-log: 
,09-28 07:50:06.072  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.072  5549  5595 I jxcore-log: 
,09-28 07:50:06.073  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.073  5549  5595 I jxcore-log: 
,09-28 07:50:06.085  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.085  5549  5595 I jxcore-log: 
,09-28 07:50:06.086  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.086  5549  5595 I jxcore-log: 
,09-28 07:50:06.088  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.088  5549  5595 I jxcore-log: 
,09-28 07:50:06.092  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.092  5549  5595 I jxcore-log: 
,09-28 07:50:06.092  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.092  5549  5595 I jxcore-log: 
09-28 07:50:06.093  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.093  5549  5595 I jxcore-log: 
,09-28 07:50:06.094  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:06.094  5549  5595 I jxcore-log: 
,09-28 07:50:06.094  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:06.094  5549  5595 I jxcore-log: 
09-28 07:50:06.095  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new mux'
09-28 07:50:06.095  5549  5595 I jxcore-log: 
,09-28 07:50:06.148  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.148  5549  5595 I jxcore-log: 
,09-28 07:50:06.150  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.150  5549  5595 I jxcore-log: 
,09-28 07:50:06.152  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.152  5549  5595 I jxcore-log: 
,09-28 07:50:06.153  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.153  5549  5595 I jxcore-log: 
,09-28 07:50:06.154  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.154  5549  5595 I jxcore-log: 
,09-28 07:50:06.155  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.155  5549  5595 I jxcore-log: 
,09-28 07:50:06.156  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.156  5549  5595 I jxcore-log: 
,09-28 07:50:06.157  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.157  5549  5595 I jxcore-log: 
,09-28 07:50:06.159  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.159  5549  5595 I jxcore-log: 
,09-28 07:50:06.160  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.160  5549  5595 I jxcore-log: 
09-28 07:50:06.161  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.161  5549  5595 I jxcore-log: 
09-28 07:50:06.162  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.162  5549  5595 I jxcore-log: 
09-28 07:50:06.162  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.162  5549  5595 I jxcore-log: 
09-28 07:50:06.163  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.163  5549  5595 I jxcore-log: 
,09-28 07:50:06.164  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.164  5549  5595 I jxcore-log: 
09-28 07:50:06.165  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.165  5549  5595 I jxcore-log: 
,09-28 07:50:06.166  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.166  5549  5595 I jxcore-log: 
,09-28 07:50:06.167  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.167  5549  5595 I jxcore-log: 
,09-28 07:50:06.168  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.168  5549  5595 I jxcore-log: 
09-28 07:50:06.168  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.168  5549  5595 I jxcore-log: 
,09-28 07:50:06.169  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.169  5549  5595 I jxcore-log: 
09-28 07:50:06.170  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.170  5549  5595 I jxcore-log: 
,09-28 07:50:06.170  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.170  5549  5595 I jxcore-log: 
09-28 07:50:06.171  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.171  5549  5595 I jxcore-log: 
,09-28 07:50:06.172  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.172  5549  5595 I jxcore-log: 
,09-28 07:50:06.173  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.173  5549  5595 I jxcore-log: 
,09-28 07:50:06.173  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.173  5549  5595 I jxcore-log: 
,09-28 07:50:06.179  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.179  5549  5595 I jxcore-log: 
,09-28 07:50:06.180  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.180  5549  5595 I jxcore-log: 
,09-28 07:50:06.181  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.181  5549  5595 I jxcore-log: 
09-28 07:50:06.181  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.181  5549  5595 I jxcore-log: 
,09-28 07:50:06.182  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.182  5549  5595 I jxcore-log: 
,09-28 07:50:06.183  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.183  5549  5595 I jxcore-log: 
09-28 07:50:06.184  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.184  5549  5595 I jxcore-log: 
,09-28 07:50:06.185  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.185  5549  5595 I jxcore-log: 
09-28 07:50:06.186  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.186  5549  5595 I jxcore-log: 
,09-28 07:50:06.186  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.186  5549  5595 I jxcore-log: 
,09-28 07:50:06.187  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.187  5549  5595 I jxcore-log: 
09-28 07:50:06.187  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.187  5549  5595 I jxcore-log: 
,09-28 07:50:06.188  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.188  5549  5595 I jxcore-log: 
09-28 07:50:06.189  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.189  5549  5595 I jxcore-log: 
,09-28 07:50:06.190  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.190  5549  5595 I jxcore-log: 
,09-28 07:50:06.190  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.190  5549  5595 I jxcore-log: 
09-28 07:50:06.191  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.191  5549  5595 I jxcore-log: 
09-28 07:50:06.192  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.192  5549  5595 I jxcore-log: 
,09-28 07:50:06.193  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.193  5549  5595 I jxcore-log: 
09-28 07:50:06.193  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.193  5549  5595 I jxcore-log: 
,09-28 07:50:06.194  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.194  5549  5595 I jxcore-log: 
,09-28 07:50:06.195  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.195  5549  5595 I jxcore-log: 
,09-28 07:50:06.195  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.195  5549  5595 I jxcore-log: 
09-28 07:50:06.196  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.196  5549  5595 I jxcore-log: 
09-28 07:50:06.197  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.197  5549  5595 I jxcore-log: 
,09-28 07:50:06.197  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.197  5549  5595 I jxcore-log: 
09-28 07:50:06.198  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.198  5549  5595 I jxcore-log: 
,09-28 07:50:06.198  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.198  5549  5595 I jxcore-log: 
09-28 07:50:06.199  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.199  5549  5595 I jxcore-log: 
,09-28 07:50:06.201  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.201  5549  5595 I jxcore-log: 
,09-28 07:50:06.202  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.202  5549  5595 I jxcore-log: 
,09-28 07:50:06.202  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.202  5549  5595 I jxcore-log: 
09-28 07:50:06.203  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.203  5549  5595 I jxcore-log: 
,09-28 07:50:06.204  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.204  5549  5595 I jxcore-log: 
09-28 07:50:06.204  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.204  5549  5595 I jxcore-log: 
,09-28 07:50:06.205  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.205  5549  5595 I jxcore-log: 
09-28 07:50:06.206  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.206  5549  5595 I jxcore-log: 
,09-28 07:50:06.207  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.207  5549  5595 I jxcore-log: 
,09-28 07:50:06.207  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.207  5549  5595 I jxcore-log: 
09-28 07:50:06.208  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.208  5549  5595 I jxcore-log: 
,09-28 07:50:06.209  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.209  5549  5595 I jxcore-log: 
09-28 07:50:06.209  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.209  5549  5595 I jxcore-log: 
,09-28 07:50:06.210  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.210  5549  5595 I jxcore-log: 
09-28 07:50:06.211  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.211  5549  5595 I jxcore-log: 
,09-28 07:50:06.211  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.211  5549  5595 I jxcore-log: 
,09-28 07:50:06.212  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.212  5549  5595 I jxcore-log: 
09-28 07:50:06.213  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.213  5549  5595 I jxcore-log: 
,09-28 07:50:06.214  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.214  5549  5595 I jxcore-log: 
,09-28 07:50:06.215  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.215  5549  5595 I jxcore-log: 
09-28 07:50:06.215  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.215  5549  5595 I jxcore-log: 
,09-28 07:50:06.216  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.216  5549  5595 I jxcore-log: 
09-28 07:50:06.216  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:06.216  5549  5595 I jxcore-log: 
,09-28 07:50:06.217  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:06.217  5549  5595 I jxcore-log: 
,09-28 07:50:06.267  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.267  5549  5595 I jxcore-log: 
,09-28 07:50:06.268  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.268  5549  5595 I jxcore-log: 
,09-28 07:50:06.269  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.269  5549  5595 I jxcore-log: 
,09-28 07:50:06.270  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.270  5549  5595 I jxcore-log: 
09-28 07:50:06.271  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.271  5549  5595 I jxcore-log: 
,09-28 07:50:06.271  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.271  5549  5595 I jxcore-log: 
09-28 07:50:06.272  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.272  5549  5595 I jxcore-log: 
,09-28 07:50:06.272  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.272  5549  5595 I jxcore-log: 
09-28 07:50:06.273  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.273  5549  5595 I jxcore-log: 
09-28 07:50:06.273  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.273  5549  5595 I jxcore-log: 
,09-28 07:50:06.274  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.274  5549  5595 I jxcore-log: 
,09-28 07:50:06.275  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.275  5549  5595 I jxcore-log: 
09-28 07:50:06.276  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.276  5549  5595 I jxcore-log: 
,09-28 07:50:06.277  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.277  5549  5595 I jxcore-log: 
,09-28 07:50:06.278  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.278  5549  5595 I jxcore-log: 
,09-28 07:50:06.282  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.282  5549  5595 I jxcore-log: 
,09-28 07:50:06.283  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.283  5549  5595 I jxcore-log: 
,09-28 07:50:06.284  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.284  5549  5595 I jxcore-log: 
09-28 07:50:06.285  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.285  5549  5595 I jxcore-log: 
09-28 07:50:06.285  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.285  5549  5595 I jxcore-log: 
,09-28 07:50:06.286  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.286  5549  5595 I jxcore-log: 
09-28 07:50:06.286  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.286  5549  5595 I jxcore-log: 
,09-28 07:50:06.286  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.286  5549  5595 I jxcore-log: 
09-28 07:50:06.287  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.287  5549  5595 I jxcore-log: 
09-28 07:50:06.287  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.287  5549  5595 I jxcore-log: 
,09-28 07:50:06.288  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.288  5549  5595 I jxcore-log: 
09-28 07:50:06.288  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.288  5549  5595 I jxcore-log: 
,09-28 07:50:06.289  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.289  5549  5595 I jxcore-log: 
09-28 07:50:06.289  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.289  5549  5595 I jxcore-log: 
,09-28 07:50:06.290  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.290  5549  5595 I jxcore-log: 
09-28 07:50:06.290  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.290  5549  5595 I jxcore-log: 
,09-28 07:50:06.291  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.291  5549  5595 I jxcore-log: 
09-28 07:50:06.291  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.291  5549  5595 I jxcore-log: 
,09-28 07:50:06.291  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.291  5549  5595 I jxcore-log: 
,09-28 07:50:06.292  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.292  5549  5595 I jxcore-log: 
09-28 07:50:06.292  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.292  5549  5595 I jxcore-log: 
09-28 07:50:06.293  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.293  5549  5595 I jxcore-log: 
,09-28 07:50:06.293  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.293  5549  5595 I jxcore-log: 
09-28 07:50:06.293  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.293  5549  5595 I jxcore-log: 
09-28 07:50:06.294  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.294  5549  5595 I jxcore-log: 
09-28 07:50:06.294  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.294  5549  5595 I jxcore-log: 
,09-28 07:50:06.295  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.295  5549  5595 I jxcore-log: 
09-28 07:50:06.295  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.295  5549  5595 I jxcore-log: 
09-28 07:50:06.295  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.295  5549  5595 I jxcore-log: 
09-28 07:50:06.296  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.296  5549  5595 I jxcore-log: 
,09-28 07:50:06.296  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.296  5549  5595 I jxcore-log: 
09-28 07:50:06.299  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.299  5549  5595 I jxcore-log: 
09-28 07:50:06.300  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.300  5549  5595 I jxcore-log: 
09-28 07:50:06.300  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:06.300  5549  5595 I jxcore-log: 
09-28 07:50:06.301  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'mux close'
09-28 07:50:06.301  5549  5595 I jxcore-log: 
09-28 07:50:06.303  5549  5595 I jxcore-log: ok 28 native server is nulled out
09-28 07:50:06.303  5549  5595 I jxcore-log: 
09-28 07:50:06.303  5549  5595 I jxcore-log: ok 29 native server should be closed
09-28 07:50:06.303  5549  5595 I jxcore-log: 
09-28 07:50:06.303  5549  5595 I jxcore-log: ok 30 incoming has been removed
09-28 07:50:06.303  5549  5595 I jxcore-log: 
09-28 07:50:06.304  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.304  5549  5595 I jxcore-log: 
09-28 07:50:06.305  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.305  5549  5595 I jxcore-log: 
09-28 07:50:06.306  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.306  5549  5595 I jxcore-log: 
09-28 07:50:06.307  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.307  5549  5595 I jxcore-log: 
09-28 07:50:06.307  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.307  5549  5595 I jxcore-log: 
09-28 07:50:06.307  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.307  5549  5595 I jxcore-log: 
09-28 07:50:06.307  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.307  5549  5595 I jxcore-log: 
09-28 07:50:06.308  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.308  5549  5595 I jxcore-log: 
09-28 07:50:06.308  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.308  5549  5595 I jxcore-log: 
09-28 07:50:06.308  5549  5595 I jxcore-log: 2016-09-28 11:50:06 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:06.308  5549  5595 I jxcore-log: 
,09-28 07:50:06.385  5549  5595 I jxcore-log: # teardown
09-28 07:50:06.385  5549  5595 I jxcore-log: 
,09-28 07:50:06.470  5549  5595 I jxcore-log: # setup
09-28 07:50:06.470  5549  5595 I jxcore-log: 
,09-28 07:50:06.505   929  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 07:50:06.537   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:07.539   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:08.491  5549  5595 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-28 07:50:08.491  5549  5595 I jxcore-log: 
,09-28 07:50:08.540   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:08.560  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:08.560  5549  5595 I jxcore-log: 
,09-28 07:50:08.565  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'listening 49086'
09-28 07:50:08.565  5549  5595 I jxcore-log: 
,09-28 07:50:08.577  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:08.577  5549  5595 I jxcore-log: 
09-28 07:50:08.579  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:08.579  5549  5595 I jxcore-log: 
,09-28 07:50:08.581  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new mux'
09-28 07:50:08.581  5549  5595 I jxcore-log: 
,09-28 07:50:08.590  5549  5595 I jxcore-log: ok 31 we should not have gotten an error
09-28 07:50:08.590  5549  5595 I jxcore-log: 
,09-28 07:50:08.600  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:08.600  5549  5595 I jxcore-log: 
,09-28 07:50:08.603  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:08.603  5549  5595 I jxcore-log: 
,09-28 07:50:08.613  5549  5595 I jxcore-log: ok 32 Buffers are identical
09-28 07:50:08.613  5549  5595 I jxcore-log: 
,09-28 07:50:08.614  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:08.614  5549  5595 I jxcore-log: 
,09-28 07:50:08.616  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'mux close'
09-28 07:50:08.616  5549  5595 I jxcore-log: 
,09-28 07:50:08.629  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:08.629  5549  5595 I jxcore-log: 
,09-28 07:50:08.630  5549  5595 I jxcore-log: ok 33 server should be fine
09-28 07:50:08.630  5549  5595 I jxcore-log: 
09-28 07:50:08.630  5549  5595 I jxcore-log: ok 34 server should be open
09-28 07:50:08.630  5549  5595 I jxcore-log: 
09-28 07:50:08.630  5549  5595 I jxcore-log: ok 35 incoming has been removed
09-28 07:50:08.630  5549  5595 I jxcore-log: 
09-28 07:50:08.631  5549  5595 I jxcore-log: ok 36 The mux object should be closed
09-28 07:50:08.631  5549  5595 I jxcore-log: 
09-28 07:50:08.631  5549  5595 I jxcore-log: ok 37 The mux stream should be closed
09-28 07:50:08.631  5549  5595 I jxcore-log: 
,09-28 07:50:08.636  5549  5595 I jxcore-log: # teardown
09-28 07:50:08.636  5549  5595 I jxcore-log: 
,09-28 07:50:08.705  5549  5595 I jxcore-log: # setup
09-28 07:50:08.705  5549  5595 I jxcore-log: 
,09-28 07:50:08.764  5549  5595 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-28 07:50:08.764  5549  5595 I jxcore-log: 
,09-28 07:50:08.828  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'creating native server'
09-28 07:50:08.828  5549  5595 I jxcore-log: 
,09-28 07:50:08.833  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'listening 45167'
09-28 07:50:08.833  5549  5595 I jxcore-log: 
,09-28 07:50:08.842  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new incoming socket'
09-28 07:50:08.842  5549  5595 I jxcore-log: 
,09-28 07:50:08.844  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'creating incoming mux'
09-28 07:50:08.844  5549  5595 I jxcore-log: 
,09-28 07:50:08.847  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new mux'
09-28 07:50:08.847  5549  5595 I jxcore-log: 
,09-28 07:50:08.850   929  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 07:50:08.859  5549  5595 I jxcore-log: ok 38 we should not have gotten an error
09-28 07:50:08.859  5549  5595 I jxcore-log: 
,09-28 07:50:08.867  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new stream: '
09-28 07:50:08.867  5549  5595 I jxcore-log: 
,09-28 07:50:08.869  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'new outgoing socket'
09-28 07:50:08.869  5549  5595 I jxcore-log: 
,09-28 07:50:08.876  5549  5595 I jxcore-log: ok 39 Buffers are identical
09-28 07:50:08.876  5549  5595 I jxcore-log: 
,09-28 07:50:08.881  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'incoming socket timeout'
09-28 07:50:08.881  5549  5595 I jxcore-log: 
,09-28 07:50:08.882  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'stream close:'
09-28 07:50:08.882  5549  5595 I jxcore-log: 
,09-28 07:50:08.884  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'mux close'
09-28 07:50:08.884  5549  5595 I jxcore-log: 
,09-28 07:50:08.888  5549  5595 I jxcore-log: 2016-09-28 11:50:08 - DEBUG createNativeListener: 'incoming socket close'
09-28 07:50:08.888  5549  5595 I jxcore-log: 
,09-28 07:50:08.889  5549  5595 I jxcore-log: ok 40 server should be fine
09-28 07:50:08.889  5549  5595 I jxcore-log: 
09-28 07:50:08.889  5549  5595 I jxcore-log: ok 41 server should be open
09-28 07:50:08.889  5549  5595 I jxcore-log: 
09-28 07:50:08.889  5549  5595 I jxcore-log: ok 42 incoming has been removed
09-28 07:50:08.889  5549  5595 I jxcore-log: 
09-28 07:50:08.889  5549  5595 I jxcore-log: ok 43 The mux object should be closed
09-28 07:50:08.889  5549  5595 I jxcore-log: 
09-28 07:50:08.890  5549  5595 I jxcore-log: ok 44 The mux stream should be closed
09-28 07:50:08.890  5549  5595 I jxcore-log: 
,09-28 07:50:08.895  5549  5595 I jxcore-log: # teardown
09-28 07:50:08.895  5549  5595 I jxcore-log: 
,09-28 07:50:08.973  5549  5595 I jxcore-log: # setup
09-28 07:50:08.973  5549  5595 I jxcore-log: 
,09-28 07:50:09.067  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-28 07:50:09.067  5549  5595 I jxcore-log: 
,09-28 07:50:09.212  5549  5595 I jxcore-log: 2016-09-28 11:50:09 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-28 07:50:09.212  5549  5595 I jxcore-log: 
,09-28 07:50:09.213  5549  5595 I jxcore-log: ok 45 Got right error
09-28 07:50:09.213  5549  5595 I jxcore-log: 
,09-28 07:50:09.217  5549  5595 I jxcore-log: # teardown
09-28 07:50:09.217  5549  5595 I jxcore-log: 
,09-28 07:50:09.280  5549  5595 I jxcore-log: # setup
09-28 07:50:09.280  5549  5595 I jxcore-log: 
,09-28 07:50:09.322  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-28 07:50:09.322  5549  5595 I jxcore-log: 
,09-28 07:50:09.476  5549  5595 I jxcore-log: 2016-09-28 11:50:09 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-28 07:50:09.476  5549  5595 I jxcore-log: 
,09-28 07:50:09.477  5549  5595 I jxcore-log: ok 46 Got socket hang up
09-28 07:50:09.477  5549  5595 I jxcore-log: 
,09-28 07:50:09.482  5549  5595 I jxcore-log: # teardown
09-28 07:50:09.482  5549  5595 I jxcore-log: 
,09-28 07:50:09.540   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:09.553  5549  5595 I jxcore-log: # setup
09-28 07:50:09.553  5549  5595 I jxcore-log: 
,09-28 07:50:09.626  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-28 07:50:09.626  5549  5595 I jxcore-log: 
,09-28 07:50:09.810  5549  5595 I jxcore-log: 2016-09-28 11:50:09 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-28 07:50:09.810  5549  5595 I jxcore-log: 
,09-28 07:50:09.811  5549  5595 I jxcore-log: ok 47 Got 500 as expected
09-28 07:50:09.811  5549  5595 I jxcore-log: 
,09-28 07:50:09.815  5549  5595 I jxcore-log: # teardown
09-28 07:50:09.815  5549  5595 I jxcore-log: 
,09-28 07:50:09.857  5549  5595 I jxcore-log: # setup
09-28 07:50:09.857  5549  5595 I jxcore-log: 
,09-28 07:50:09.922  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-28 07:50:09.922  5549  5595 I jxcore-log: 
,09-28 07:50:10.541   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:11.292  5549  5595 I jxcore-log: ok 48 should be equal
09-28 07:50:11.292  5549  5595 I jxcore-log: 
,09-28 07:50:11.292  5549  5595 I jxcore-log: ok 49 revs are equal
09-28 07:50:11.292  5549  5595 I jxcore-log: 
,09-28 07:50:11.297  5549  5595 I jxcore-log: # teardown
09-28 07:50:11.297  5549  5595 I jxcore-log: 
,09-28 07:50:11.393  5549  5595 I jxcore-log: # setup
09-28 07:50:11.393  5549  5595 I jxcore-log: 
,09-28 07:50:11.542   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-28 07:50:11.556  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-28 07:50:11.556  5549  5595 I jxcore-log: 
,09-28 07:50:12.329  5549  5595 I jxcore-log: ok 50 should be equal
09-28 07:50:12.329  5549  5595 I jxcore-log: 
,09-28 07:50:12.329  5549  5595 I jxcore-log: ok 51 revs are equal
09-28 07:50:12.329  5549  5595 I jxcore-log: 
,09-28 07:50:12.334  5549  5595 I jxcore-log: # teardown
09-28 07:50:12.334  5549  5595 I jxcore-log: 
,09-28 07:50:12.440  5549  5595 I jxcore-log: # setup
09-28 07:50:12.440  5549  5595 I jxcore-log: 
,09-28 07:50:12.497  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-28 07:50:12.497  5549  5595 I jxcore-log: 
,09-28 07:50:13.125  5549  5595 I jxcore-log: ok 52 should be equal
09-28 07:50:13.125  5549  5595 I jxcore-log: 
09-28 07:50:13.126  5549  5595 I jxcore-log: ok 53 revs are equal
09-28 07:50:13.126  5549  5595 I jxcore-log: 
,09-28 07:50:13.290  5549  5595 I jxcore-log: ok 54 should be equal
09-28 07:50:13.290  5549  5595 I jxcore-log: 
,09-28 07:50:13.291  5549  5595 I jxcore-log: ok 55 revs are equal
09-28 07:50:13.291  5549  5595 I jxcore-log: 
,09-28 07:50:13.432  5549  5595 I jxcore-log: ok 56 should be equal
09-28 07:50:13.432  5549  5595 I jxcore-log: 
,09-28 07:50:13.433  5549  5595 I jxcore-log: ok 57 revs are equal
09-28 07:50:13.433  5549  5595 I jxcore-log: 
,09-28 07:50:13.439  5549  5595 I jxcore-log: # teardown
09-28 07:50:13.439  5549  5595 I jxcore-log: 
,09-28 07:50:13.503  5549  5595 I jxcore-log: # setup
09-28 07:50:13.503  5549  5595 I jxcore-log: 
,09-28 07:50:14.021  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-28 07:50:14.021  5549  5595 I jxcore-log: 
,09-28 07:50:14.627  5549  5595 I jxcore-log: 2016-09-28 11:50:14 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-28 07:50:14.627  5549  5595 I jxcore-log: 
,09-28 07:50:14.628  5549  5595 I jxcore-log: ok 58 Our rev is old so we should fail
09-28 07:50:14.628  5549  5595 I jxcore-log: 
,09-28 07:50:14.631  5549  5595 I jxcore-log: # teardown
09-28 07:50:14.631  5549  5595 I jxcore-log: 
,09-28 07:50:14.713  5549  5595 I jxcore-log: # setup
09-28 07:50:14.713  5549  5595 I jxcore-log: 
,09-28 07:50:14.759  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-28 07:50:14.759  5549  5595 I jxcore-log: 
,09-28 07:50:14.859  5549  5595 I jxcore-log: ok 59 confirm stop caused failure
09-28 07:50:14.859  5549  5595 I jxcore-log: 
,09-28 07:50:14.871  5549  5595 I jxcore-log: # teardown
09-28 07:50:14.871  5549  5595 I jxcore-log: 
,09-28 07:50:14.962  5549  5595 I jxcore-log: # setup
09-28 07:50:14.962  5549  5595 I jxcore-log: 
,09-28 07:50:15.033  5549  5595 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-28 07:50:15.033  5549  5595 I jxcore-log: 
,09-28 07:50:15.370  5549  5595 I jxcore-log: 2016-09-28 11:50:15 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-28 07:50:15.370  5549  5595 I jxcore-log: 
,09-28 07:50:15.371  5549  5595 I jxcore-log: ok 60 stop caused us to fail
09-28 07:50:15.371  5549  5595 I jxcore-log: 
09-28 07:50:15.371  5549  5595 I jxcore-log: ok 61 We specifically failed on a stop before put
09-28 07:50:15.371  5549  5595 I jxcore-log: 
,09-28 07:50:15.375  5549  5595 I jxcore-log: # teardown
09-28 07:50:15.375  5549  5595 I jxcore-log: 
,09-28 07:50:15.510  5549  5595 I jxcore-log: # setup
09-28 07:50:15.510  5549  5595 I jxcore-log: 
,09-28 07:50:15.613  5549  5595 I jxcore-log: # #update - fail if stop is called
09-28 07:50:15.613  5549  5595 I jxcore-log: 
,09-28 07:50:15.708  5549  5595 I jxcore-log: ok 62 failed due to stop
09-28 07:50:15.708  5549  5595 I jxcore-log: 
,09-28 07:50:15.709  5549  5595 I jxcore-log: ok 63 failed due to stop
09-28 07:50:15.709  5549  5595 I jxcore-log: 
,09-28 07:50:15.719  5549  5595 I jxcore-log: # teardown
09-28 07:50:15.719  5549  5595 I jxcore-log: 
,09-28 07:50:15.828  5549  5595 I jxcore-log: # setup
09-28 07:50:15.828  5549  5595 I jxcore-log: 
,09-28 07:50:15.884  5549  5595 I jxcore-log: # #update - set seq for first time
09-28 07:50:15.884  5549  5595 I jxcore-log: 
,09-28 07:50:16.542   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:16.559  5549  5595 I jxcore-log: ok 64 should be equal
09-28 07:50:16.559  5549  5595 I jxcore-log: 
,09-28 07:50:16.565  5549  5595 I jxcore-log: # teardown
09-28 07:50:16.565  5549  5595 I jxcore-log: 
,09-28 07:50:16.616  5549  5595 I jxcore-log: # setup
09-28 07:50:16.616  5549  5595 I jxcore-log: 
,09-28 07:50:16.690  5549  5595 I jxcore-log: # #update - Fail on bad seq value
09-28 07:50:16.690  5549  5595 I jxcore-log: 
,09-28 07:50:17.080  5549  5595 I jxcore-log: 2016-09-28 11:50:17 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-28 07:50:17.080  5549  5595 I jxcore-log: 
,09-28 07:50:17.082  5549  5595 I jxcore-log: ok 65 Expected bad seq error
09-28 07:50:17.082  5549  5595 I jxcore-log: 
,09-28 07:50:17.085  5549  5595 I jxcore-log: # teardown
09-28 07:50:17.085  5549  5595 I jxcore-log: 
,09-28 07:50:17.137  5549  5595 I jxcore-log: # setup
09-28 07:50:17.137  5549  5595 I jxcore-log: 
,09-28 07:50:17.298  5549  5595 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-28 07:50:17.298  5549  5595 I jxcore-log: 
,09-28 07:50:17.543   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:17.772  5549  5595 I jxcore-log: ok 66 Different promises
09-28 07:50:17.772  5549  5595 I jxcore-log: 
,09-28 07:50:17.775  5549  5595 I jxcore-log: ok 67 Timer was cancelled
09-28 07:50:17.775  5549  5595 I jxcore-log: 
,09-28 07:50:18.250  5549  5595 I jxcore-log: ok 68 should be equal
09-28 07:50:18.250  5549  5595 I jxcore-log: 
,09-28 07:50:18.257  5549  5595 I jxcore-log: # teardown
09-28 07:50:18.257  5549  5595 I jxcore-log: 
,09-28 07:50:18.300  5549  5595 I jxcore-log: # setup
09-28 07:50:18.300  5549  5595 I jxcore-log: 
,09-28 07:50:18.544   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:18.847  5549  5595 I jxcore-log: # #update - do we wait for blocked update
09-28 07:50:18.847  5549  5595 I jxcore-log: 
,09-28 07:50:18.998  5549  5595 I jxcore-log: ok 69 One go and one blocked
09-28 07:50:18.998  5549  5595 I jxcore-log: 
,09-28 07:50:18.999  5549  5595 I jxcore-log: ok 70 All blocked
09-28 07:50:18.999  5549  5595 I jxcore-log: 
09-28 07:50:18.999  5549  5595 I jxcore-log: ok 71 Still blocked
09-28 07:50:18.999  5549  5595 I jxcore-log: 
,09-28 07:50:19.463  5549  5595 I jxcore-log: ok 72 should be equal
09-28 07:50:19.463  5549  5595 I jxcore-log: 
,09-28 07:50:19.471  5549  5595 I jxcore-log: # teardown
09-28 07:50:19.471  5549  5595 I jxcore-log: 
,09-28 07:50:19.544   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:19.630  5549  5595 I jxcore-log: # setup
09-28 07:50:19.630  5549  5595 I jxcore-log: 
,09-28 07:50:19.689  5549  5595 I jxcore-log: # #update - test that we wait long enough
09-28 07:50:19.689  5549  5595 I jxcore-log: 
,09-28 07:50:20.545   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:20.919  5549  5595 I jxcore-log: ok 73 We waited long enough
09-28 07:50:20.919  5549  5595 I jxcore-log: 
,09-28 07:50:21.028  5549  5595 I jxcore-log: ok 74 should be equal
09-28 07:50:21.028  5549  5595 I jxcore-log: 
,09-28 07:50:21.034  5549  5595 I jxcore-log: # teardown
09-28 07:50:21.034  5549  5595 I jxcore-log: 
,09-28 07:50:21.195  5549  5595 I jxcore-log: # setup
09-28 07:50:21.195  5549  5595 I jxcore-log: 
,09-28 07:50:21.233  5549  5595 I jxcore-log: # #update - test that we pick up new sequences while we wait
09-28 07:50:21.233  5549  5595 I jxcore-log: 
,09-28 07:50:21.546   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-28 07:50:21.727  5549  5595 I jxcore-log: ok 75 Should have gotten same timer promise
09-28 07:50:21.727  5549  5595 I jxcore-log: 
,09-28 07:50:21.728  5549  5595 I jxcore-log: ok 76 Still same timer promise
09-28 07:50:21.728  5549  5595 I jxcore-log: 
,09-28 07:50:22.455  5549  5595 I jxcore-log: ok 77 We waited long enough
09-28 07:50:22.455  5549  5595 I jxcore-log: 
,09-28 07:50:22.531  5549  5595 I jxcore-log: ok 78 should be equal
09-28 07:50:22.531  5549  5595 I jxcore-log: 
,09-28 07:50:22.537  5549  5595 I jxcore-log: # teardown
09-28 07:50:22.537  5549  5595 I jxcore-log: 
,09-28 07:50:22.588  5549  5595 I jxcore-log: # setup
09-28 07:50:22.588  5549  5595 I jxcore-log: 
,09-28 07:50:22.723  5549  5595 I jxcore-log: # Coordinated seq test
09-28 07:50:22.723  5549  5595 I jxcore-log: 
,09-28 07:50:22.731  5549  5595 I jxcore-log: 2016-09-28 11:50:22 - INFO CoordinatedClient: 'test was skipped, name: 'Coordinated seq test''
09-28 07:50:22.731  5549  5595 I jxcore-log: 
,09-28 07:50:22.788  5549  5595 I jxcore-log: # teardown
09-28 07:50:22.788  5549  5595 I jxcore-log: 
,09-28 07:50:22.865  5549  5595 D io.jxcore.node.JXcoreExtension: stopAdvertisingAndListening
,09-28 07:50:22.865  5549  5595 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-28 07:50:22.865  5549  5595 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-28 07:50:22.865  5549  5595 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-28 07:50:22.874  5549  5595 I jxcore-log: # setup
09-28 07:50:22.874  5549  5595 I jxcore-log: 
,09-28 07:50:22.958  5549  5595 I jxcore-log: # closeAll can close even when connections open
09-28 07:50:22.958  5549  5595 I jxcore-log: 
,09-28 07:50:23.146  5549  5595 I jxcore-log: ok 79 not possible to connect to the server anymore
09-28 07:50:23.146  5549  5595 I jxcore-log: 
,09-28 07:50:23.152  5549  5595 I jxcore-log: # teardown
09-28 07:50:23.152  5549  5595 I jxcore-log: 
,09-28 07:50:23.246  5549  5595 I jxcore-log: # setup
09-28 07:50:23.246  5549  5595 I jxcore-log: 
,09-28 07:50:23.354  5549  5595 I jxcore-log: # closeAll with promise
09-28 07:50:23.354  5549  5595 I jxcore-log: 
,09-28 07:50:23.587  5549  5595 I jxcore-log: ok 80 not possible to connect to the server anymore
09-28 07:50:23.587  5549  5595 I jxcore-log: 
,09-28 07:50:23.595  5549  5595 I jxcore-log: # teardown
09-28 07:50:23.595  5549  5595 I jxcore-log: 
,09-28 07:50:23.638  5549  5595 I jxcore-log: # setup
09-28 07:50:23.638  5549  5595 I jxcore-log: 
,09-28 07:50:23.703  5549  5595 I jxcore-log: # closeAll properly throws when closing a non open server with eatNotRunning set to false
09-28 07:50:23.703  5549  5595 I jxcore-log: 
,09-28 07:50:23.860  5549  5595 I jxcore-log: ok 81 Got the right error
09-28 07:50:23.860  5549  5595 I jxcore-log: 
,09-28 07:50:23.873  5549  5595 I jxcore-log: # teardown
09-28 07:50:23.873  5549  5595 I jxcore-log: 
,09-28 07:50:23.925  5549  5595 I jxcore-log: # setup
09-28 07:50:23.925  5549  5595 I jxcore-log: 
,09-28 07:50:24.002  5549  5595 I jxcore-log: # closeAll works even with a server that is not listening yet witheatNotRunning set to true
09-28 07:50:24.002  5549  5595 I jxcore-log: 
,09-28 07:50:24.174  5549  5595 I jxcore-log: # teardown
09-28 07:50:24.174  5549  5595 I jxcore-log: 
,09-28 07:50:24.225  5549  5595 I jxcore-log: # setup
09-28 07:50:24.225  5549  5595 I jxcore-log: 
,09-28 07:50:24.374  5549  5595 I jxcore-log: # onPeerLost calls jxcore
09-28 07:50:24.374  5549  5595 I jxcore-log: 
,09-28 07:50:24.455  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 07:50:24.455  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@54b5a5d added. We now have 3 listener(s)
09-28 07:50:24.457  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:50:24.457  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:50:24.457  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:50:24.458  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:50:24.458  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78bffd2 added. We now have 4 listener(s)
09-28 07:50:24.458  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-28 07:50:24.459  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 07:50:24.464  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:50:24.472  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:50:24.475  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-28 07:50:24.475  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:50:24.476  5549  5595 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
09-28 07:50:24.476  5549  5595 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
,09-28 07:50:24.479  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:50:24.482  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:50:26.479  5549  5595 I jxcore-log: onPeerLost
09-28 07:50:26.479  5549  5595 I jxcore-log: 
,09-28 07:50:26.483  5549  5595 I jxcore-log: 2016-09-28 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:50:26.483  5549  5595 I jxcore-log: 
,09-28 07:50:26.501  5549  5595 I jxcore-log: # teardown
09-28 07:50:26.501  5549  5595 I jxcore-log: 
,09-28 07:50:26.506  5549  5595 I jxcore-log: ok 82 check if callback was fired by onPeerLost
09-28 07:50:26.506  5549  5595 I jxcore-log: 
,09-28 07:50:26.506  5549  5595 I jxcore-log: ok 83 check if peerAvailable is false
09-28 07:50:26.506  5549  5595 I jxcore-log: 
,09-28 07:50:26.577  5549  5595 I jxcore-log: 2016-09-28 11:50:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 07:50:26.577  5549  5595 I jxcore-log: 
,09-28 07:50:26.583  5549  5595 I jxcore-log: 2016-09-28 11:50:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 07:50:26.583  5549  5595 I jxcore-log: 
,09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:50:26.592  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:50:26.596  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:50:26.598  5549  5595 I jxcore-log: 2016-09-28 11:50:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 07:50:26.598  5549  5595 I jxcore-log: 
,09-28 07:50:26.602  5549  5595 I jxcore-log: 2016-09-28 11:50:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 07:50:26.602  5549  5595 I jxcore-log: 
09-28 07:50:26.606  5549  5595 I jxcore-log: 2016-09-28 11:50:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:50:26.606  5549  5595 I jxcore-log: 
,09-28 07:50:26.610  5549  5595 I jxcore-log: # setup
09-28 07:50:26.610  5549  5595 I jxcore-log: 
,09-28 07:50:26.687  5549  5595 I jxcore-log: # onPeerDiscovered calls jxcore
09-28 07:50:26.687  5549  5595 I jxcore-log: 
,09-28 07:50:26.749  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-28 07:50:26.750  5549  5595 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1057a0 added. We now have 4 listener(s)
09-28 07:50:26.751  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-28 07:50:26.751  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-28 07:50:26.751  5549  5595 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-28 07:50:26.751  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-28 07:50:26.752  5549  5595 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6683f59 added. We now have 5 listener(s)
09-28 07:50:26.752  5549  5595 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-28 07:50:26.753  5549  5595 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-28 07:50:26.758  5549  5595 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:50:26.763  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:50:26.765  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:50:26.765  5549  5595 D io.jxcore.node.ConnectivityMonitor: start: OK
09-28 07:50:26.766  5549  5595 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,09-28 07:50:26.769  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:50:26.771  5549  5549 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-28 07:50:28.768  5549  5595 I jxcore-log: onPeerDiscovered
09-28 07:50:28.768  5549  5595 I jxcore-log: 
,09-28 07:50:28.772  5549  5595 I jxcore-log: 2016-09-28 11:50:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:50:28.772  5549  5595 I jxcore-log: 
,09-28 07:50:28.791  5549  5595 I jxcore-log: # teardown
09-28 07:50:28.791  5549  5595 I jxcore-log: 
,09-28 07:50:28.798  5549  5595 I jxcore-log: ok 84 check if callback was fired by onPeerDiscovered
09-28 07:50:28.798  5549  5595 I jxcore-log: 
09-28 07:50:28.799  5549  5595 I jxcore-log: ok 85 check if peerAvailable is true
09-28 07:50:28.799  5549  5595 I jxcore-log: 
,09-28 07:50:28.851   929  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 07:50:28.892  5549  5595 I jxcore-log: 2016-09-28 11:50:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-28 07:50:28.892  5549  5595 I jxcore-log: 
,09-28 07:50:28.896  5549  5595 I jxcore-log: 2016-09-28 11:50:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-28 07:50:28.896  5549  5595 I jxcore-log: 
,09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-28 07:50:28.914  5549  5595 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-28 07:50:28.917  5549  5595 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-28 07:50:28.921  5549  5595 I jxcore-log: 2016-09-28 11:50:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-28 07:50:28.921  5549  5595 I jxcore-log: 
,09-28 07:50:28.926  5549  5595 I jxcore-log: 2016-09-28 11:50:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-28 07:50:28.926  5549  5595 I jxcore-log: 
,09-28 07:50:28.932  5549  5595 I jxcore-log: 2016-09-28 11:50:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-28 07:50:28.932  5549  5595 I jxcore-log: 
,09-28 07:50:28.936  5549  5595 I jxcore-log: # setup
09-28 07:50:28.936  5549  5595 I jxcore-log: 
,09-28 07:50:29.057  5549  5595 I jxcore-log: # Call of onCheckpointReached handler on a single db change
09-28 07:50:29.057  5549  5595 I jxcore-log: 
,09-28 07:50:29.408  5549  5595 I jxcore-log: # teardown
09-28 07:50:29.408  5549  5595 I jxcore-log: 
,09-28 07:50:29.549  5549  5595 I jxcore-log: # setup
09-28 07:50:29.549  5549  5595 I jxcore-log: 
,09-28 07:50:29.607  5549  5595 I jxcore-log: # Call of multiple onCheckpointReached handlers on a single db change
09-28 07:50:29.607  5549  5595 I jxcore-log: 
,09-28 07:50:29.930  5549  5595 I jxcore-log: # teardown
09-28 07:50:29.930  5549  5595 I jxcore-log: 
,09-28 07:50:30.058  5549  5595 I jxcore-log: # setup
09-28 07:50:30.058  5549  5595 I jxcore-log: 
,09-28 07:50:30.160  5549  5595 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
09-28 07:50:30.160  5549  5595 I jxcore-log: 
,09-28 07:50:31.532  5549  5595 I jxcore-log: ok 86 the checkpointReached handler should be called once. Called 1 time(s)
09-28 07:50:31.532  5549  5595 I jxcore-log: 
,09-28 07:50:31.543  5549  5595 I jxcore-log: # teardown
09-28 07:50:31.543  5549  5595 I jxcore-log: 
,09-28 07:50:31.547   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:31.636  5549  5595 I jxcore-log: # setup
09-28 07:50:31.636  5549  5595 I jxcore-log: 
,09-28 07:50:31.693  5549  5595 I jxcore-log: # Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
09-28 07:50:31.693  5549  5595 I jxcore-log: 
,09-28 07:50:32.272  5549  5595 I jxcore-log: # teardown
09-28 07:50:32.272  5549  5595 I jxcore-log: 
,09-28 07:50:32.385  5549  5595 I jxcore-log: # setup
09-28 07:50:32.385  5549  5595 I jxcore-log: 
,09-28 07:50:32.426  5549  5595 I jxcore-log: # test defaultDirectory
09-28 07:50:32.426  5549  5595 I jxcore-log: 
,09-28 07:50:32.484  5549  5595 I jxcore-log: ok 87 should be equal
09-28 07:50:32.484  5549  5595 I jxcore-log: 
,09-28 07:50:32.489  5549  5595 I jxcore-log: ok 88 should be equal
09-28 07:50:32.489  5549  5595 I jxcore-log: 
,09-28 07:50:32.494  5549  5595 I jxcore-log: ok 89 should be equal
09-28 07:50:32.494  5549  5595 I jxcore-log: 
,09-28 07:50:32.512  5549  5595 I jxcore-log: # teardown
09-28 07:50:32.512  5549  5595 I jxcore-log: 
,09-28 07:50:32.548   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:32.611  5549  5595 I jxcore-log: # setup
09-28 07:50:32.611  5549  5595 I jxcore-log: 
,09-28 07:50:32.675  5549  5595 I jxcore-log: # test defaultAdapter
09-28 07:50:32.675  5549  5595 I jxcore-log: 
,09-28 07:50:32.728  5549  5595 I jxcore-log: ok 90 should be equal
09-28 07:50:32.728  5549  5595 I jxcore-log: 
,09-28 07:50:32.729  5549  5595 I jxcore-log: ok 91 should be equal
09-28 07:50:32.729  5549  5595 I jxcore-log: 
,09-28 07:50:32.733  5549  5595 I jxcore-log: ok 92 should be equal
09-28 07:50:32.733  5549  5595 I jxcore-log: 
,09-28 07:50:32.749  5549  5595 I jxcore-log: ok 93 should be equal
09-28 07:50:32.749  5549  5595 I jxcore-log: 
,09-28 07:50:32.753  5549  5595 I jxcore-log: ok 94 should be equal
09-28 07:50:32.753  5549  5595 I jxcore-log: 
09-28 07:50:32.754  5549  5595 I jxcore-log: ok 95 should be equal
09-28 07:50:32.754  5549  5595 I jxcore-log: 
,09-28 07:50:32.907  5549  5595 I jxcore-log: ok 96 should be equal
09-28 07:50:32.907  5549  5595 I jxcore-log: 
,09-28 07:50:32.907  5549  5595 I jxcore-log: ok 97 should be equal
09-28 07:50:32.907  5549  5595 I jxcore-log: 
,09-28 07:50:32.914  5549  5595 I jxcore-log: # teardown
09-28 07:50:32.914  5549  5595 I jxcore-log: 
,09-28 07:50:33.031  5549  5595 I jxcore-log: # setup
09-28 07:50:33.031  5549  5595 I jxcore-log: 
,09-28 07:50:33.092  5549  5595 I jxcore-log: # enqueue and run in order
09-28 07:50:33.092  5549  5595 I jxcore-log: 
,09-28 07:50:33.254  5549  5595 I jxcore-log: ok 98 firstPromise setTimeout
09-28 07:50:33.254  5549  5595 I jxcore-log: 
,09-28 07:50:33.256  5549  5595 I jxcore-log: ok 99 firstPromise result
09-28 07:50:33.256  5549  5595 I jxcore-log: 
09-28 07:50:33.257  5549  5595 I jxcore-log: ok 100 firstPromise testValue
09-28 07:50:33.257  5549  5595 I jxcore-log: 
,09-28 07:50:33.361  5549  5595 I jxcore-log: ok 101 secondPromise setTimeout
09-28 07:50:33.361  5549  5595 I jxcore-log: 
,09-28 07:50:33.363  5549  5595 I jxcore-log: ok 102 secondPromise result
09-28 07:50:33.363  5549  5595 I jxcore-log: 
,09-28 07:50:33.364  5549  5595 I jxcore-log: ok 103 secondPromise testValue
09-28 07:50:33.364  5549  5595 I jxcore-log: 
,09-28 07:50:33.369  5549  5595 I jxcore-log: ok 104 thirdPromise in promise
09-28 07:50:33.369  5549  5595 I jxcore-log: 
,09-28 07:50:33.372  5549  5595 I jxcore-log: ok 105 thirdPromise result
09-28 07:50:33.372  5549  5595 I jxcore-log: 
,09-28 07:50:33.374  5549  5595 I jxcore-log: ok 106 thirdPromise testValue
09-28 07:50:33.374  5549  5595 I jxcore-log: 
,09-28 07:50:33.382  5549  5595 I jxcore-log: # teardown
09-28 07:50:33.382  5549  5595 I jxcore-log: 
,09-28 07:50:33.485  5549  5595 I jxcore-log: # setup
09-28 07:50:33.485  5549  5595 I jxcore-log: 
,09-28 07:50:33.545  5549  5595 I jxcore-log: # enqueueAtTop and run backwards
09-28 07:50:33.545  5549  5595 I jxcore-log: 
,09-28 07:50:33.549   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:33.618  5549  5595 I jxcore-log: ok 107 thirdPromise - first to run
09-28 07:50:33.618  5549  5595 I jxcore-log: 
,09-28 07:50:33.620  5549  5595 I jxcore-log: ok 108 thirdPromise - in resolve
09-28 07:50:33.620  5549  5595 I jxcore-log: 
09-28 07:50:33.624  5549  5595 I jxcore-log: ok 109 secondPromise - second to run
09-28 07:50:33.624  5549  5595 I jxcore-log: 
,09-28 07:50:33.626  5549  5595 I jxcore-log: ok 110 secondPromise - in catch
09-28 07:50:33.626  5549  5595 I jxcore-log: 
,09-28 07:50:33.627  5549  5595 I jxcore-log: ok 111 firstPromise - third to run
09-28 07:50:33.627  5549  5595 I jxcore-log: 
09-28 07:50:33.629  5549  5595 I jxcore-log: ok 112 firstPromise - in then
09-28 07:50:33.629  5549  5595 I jxcore-log: 
,09-28 07:50:33.630  5549  5595 I jxcore-log: ok 113 testing promises
09-28 07:50:33.630  5549  5595 I jxcore-log: 
,09-28 07:50:33.637  5549  5595 I jxcore-log: # teardown
09-28 07:50:33.637  5549  5595 I jxcore-log: 
,09-28 07:50:33.679  5549  5595 I jxcore-log: # setup
09-28 07:50:33.679  5549  5595 I jxcore-log: 
,09-28 07:50:33.744  5549  5595 I jxcore-log: # mix enqueue and enqueueAtTop
09-28 07:50:33.744  5549  5595 I jxcore-log: 
,09-28 07:50:33.852  5549  5595 I jxcore-log: ok 114 fourth
09-28 07:50:33.852  5549  5595 I jxcore-log: 
,09-28 07:50:33.855  5549  5595 I jxcore-log: ok 115 fourth
09-28 07:50:33.855  5549  5595 I jxcore-log: 
,09-28 07:50:33.857  5549  5595 I jxcore-log: ok 116 second
09-28 07:50:33.857  5549  5595 I jxcore-log: 
,09-28 07:50:33.859  5549  5595 I jxcore-log: ok 117 secondPromise - in then
09-28 07:50:33.859  5549  5595 I jxcore-log: 
,09-28 07:50:33.966  5549  5595 I jxcore-log: ok 118 first
09-28 07:50:33.966  5549  5595 I jxcore-log: 
,09-28 07:50:33.968  5549  5595 I jxcore-log: ok 119 firstPromise - in catch
09-28 07:50:33.968  5549  5595 I jxcore-log: 
,09-28 07:50:33.970  5549  5595 I jxcore-log: ok 120 third
09-28 07:50:33.970  5549  5595 I jxcore-log: 
09-28 07:50:33.973  5549  5595 I jxcore-log: ok 121 thirdPromise - in then
09-28 07:50:33.973  5549  5595 I jxcore-log: 
,09-28 07:50:33.976  5549  5595 I jxcore-log: ok 122 testingPromises
09-28 07:50:33.976  5549  5595 I jxcore-log: 
,09-28 07:50:33.987  5549  5595 I jxcore-log: # teardown
09-28 07:50:33.987  5549  5595 I jxcore-log: 
,09-28 07:50:34.027  5549  5595 I jxcore-log: # setup
09-28 07:50:34.027  5549  5595 I jxcore-log: 
,09-28 07:50:34.186  5549  5595 I jxcore-log: # queues handled independently
09-28 07:50:34.186  5549  5595 I jxcore-log: 
,09-28 07:50:34.271  5549  5595 I jxcore-log: ok 123 all short operations completed before the long resolves
09-28 07:50:34.271  5549  5595 I jxcore-log: 
,09-28 07:50:34.280  5549  5595 I jxcore-log: # teardown
09-28 07:50:34.280  5549  5595 I jxcore-log: 
,09-28 07:50:34.402  5549  5595 I jxcore-log: # setup
09-28 07:50:34.402  5549  5595 I jxcore-log: 
,09-28 07:50:34.497  5549  5595 I jxcore-log: # basic
09-28 07:50:34.497  5549  5595 I jxcore-log: 
,09-28 07:50:34.541  5549  5595 I jxcore-log: ok 124 sane
09-28 07:50:34.541  5549  5595 I jxcore-log: 
,09-28 07:50:34.547  5549  5595 I jxcore-log: # teardown
09-28 07:50:34.547  5549  5595 I jxcore-log: 
,09-28 07:50:34.550   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:34.603  5549  5595 I jxcore-log: # setup
09-28 07:50:34.603  5549  5595 I jxcore-log: 
,09-28 07:50:34.653  5549  5595 I jxcore-log: # another
09-28 07:50:34.653  5549  5595 I jxcore-log: 
,09-28 07:50:34.751  5549  5595 I jxcore-log: ok 125 sane
09-28 07:50:34.751  5549  5595 I jxcore-log: 
,09-28 07:50:34.761  5549  5595 I jxcore-log: # teardown
09-28 07:50:34.761  5549  5595 I jxcore-log: 
,09-28 07:50:34.815  5549  5595 I jxcore-log: # setup
09-28 07:50:34.815  5549  5595 I jxcore-log: 
,09-28 07:50:34.879  5549  5595 I jxcore-log: # can pass data in setup
09-28 07:50:34.879  5549  5595 I jxcore-log: 
,09-28 07:50:34.929  5549  5595 I jxcore-log: ok 126 test participant has uuid
09-28 07:50:34.929  5549  5595 I jxcore-log: 
,09-28 07:50:34.930  5549  5595 I jxcore-log: ok 127 participant data matches
09-28 07:50:34.930  5549  5595 I jxcore-log: 
09-28 07:50:34.930  5549  5595 I jxcore-log: ok 128 test participant has uuid
09-28 07:50:34.930  5549  5595 I jxcore-log: 
09-28 07:50:34.931  5549  5595 I jxcore-log: ok 129 participant data matches
09-28 07:50:34.931  5549  5595 I jxcore-log: 
,09-28 07:50:34.932  5549  5595 I jxcore-log: ok 130 test participant has uuid
09-28 07:50:34.932  5549  5595 I jxcore-log: 
09-28 07:50:34.933  5549  5595 I jxcore-log: ok 131 participant data matches
09-28 07:50:34.933  5549  5595 I jxcore-log: 
,09-28 07:50:34.934  5549  5595 I jxcore-log: ok 132 own UUID is found from the participants list
09-28 07:50:34.934  5549  5595 I jxcore-log: 
,09-28 07:50:34.943  5549  5595 I jxcore-log: # teardown
09-28 07:50:34.943  5549  5595 I jxcore-log: 
,09-28 07:50:35.002  5549  5595 I jxcore-log: # setup
09-28 07:50:35.002  5549  5595 I jxcore-log: 
,09-28 07:50:35.060  5549  5595 I jxcore-log: # test thali manager spies
09-28 07:50:35.060  5549  5595 I jxcore-log: 
,09-28 07:50:35.228  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-28 07:50:35.228  5549  5595 I jxcore-log: 
,09-28 07:50:35.233  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-28 07:50:35.233  5549  5595 I jxcore-log: 
,09-28 07:50:35.235  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'creating express pouchdb instance'
09-28 07:50:35.235  5549  5595 I jxcore-log: 
,09-28 07:50:35.252  5549  5595 I jxcore-log: ok 133 expressPouchDB was called once
09-28 07:50:35.252  5549  5595 I jxcore-log: 
,09-28 07:50:35.252  5549  5595 I jxcore-log: ok 134 expressPouchDB was called with 2 arguments
09-28 07:50:35.252  5549  5595 I jxcore-log: 
09-28 07:50:35.252  5549  5595 I jxcore-log: ok 135 expressPouchDB was called with 'PouchDB' as 1-st argument
09-28 07:50:35.252  5549  5595 I jxcore-log: 
09-28 07:50:35.252  5549  5595 I jxcore-log: ok 136 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-28 07:50:35.252  5549  5595 I jxcore-log: 
09-28 07:50:35.253  5549  5595 I jxcore-log: ok 137 PouchDB was called once
09-28 07:50:35.253  5549  5595 I jxcore-log: 
09-28 07:50:35.253  5549  5595 I jxcore-log: ok 138 PouchDB was called with 1 arguments
09-28 07:50:35.253  5549  5595 I jxcore-log: 
09-28 07:50:35.253  5549  5595 I jxcore-log: ok 139 PouchDB was called with 'dbName' as 1-st argument
09-28 07:50:35.253  5549  5595 I jxcore-log: 
,09-28 07:50:35.253  5549  5595 I jxcore-log: ok 140 ThaliSendNotificationBasedOnReplication was called once
09-28 07:50:35.253  5549  5595 I jxcore-log: 
09-28 07:50:35.254  5549  5595 I jxcore-log: ok 141 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-28 07:50:35.254  5549  5595 I jxcore-log: 
09-28 07:50:35.254  5549  5595 I jxcore-log: ok 142 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-28 07:50:35.254  5549  5595 I jxcore-log: 
09-28 07:50:35.254  5549  5595 I jxcore-log: ok 143 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-28 07:50:35.254  5549  5595 I jxcore-log: 
09-28 07:50:35.254  5549  5595 I jxcore-log: ok 144 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-28 07:50:35.254  5549  5595 I jxcore-log: 
09-28 07:50:35.255  5549  5595 I jxcore-log: ok 145 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-28 07:50:35.255  5549  5595 I jxcore-log: 
09-28 07:50:35.255  5549  5595 I jxcore-log: ok 146 ThaliPullReplicationFromNotification was called once
09-28 07:50:35.255  5549  5595 I jxcore-log: 
,09-28 07:50:35.255  5549  5595 I jxcore-log: ok 147 ThaliPullReplicationFromNotification was called with 4 arguments
09-28 07:50:35.255  5549  5595 I jxcore-log: 
09-28 07:50:35.255  5549  5595 I jxcore-log: ok 148 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-28 07:50:35.255  5549  5595 I jxcore-log: 
09-28 07:50:35.256  5549  5595 I jxcore-log: ok 149 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-28 07:50:35.256  5549  5595 I jxcore-log: 
09-28 07:50:35.256  5549  5595 I jxcore-log: ok 150 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-28 07:50:35.256  5549  5595 I jxcore-log: 
09-28 07:50:35.256  5549  5595 I jxcore-log: ok 151 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-28 07:50:35.256  5549  5595 I jxcore-log: 
09-28 07:50:35.256  5549  5595 I jxcore-log: ok 152 Salti was called once
09-28 07:50:35.256  5549  5595 I jxcore-log: 
09-28 07:50:35.257  5549  5595 I jxcore-log: ok 153 Salti was called with 4 arguments
09-28 07:50:35.257  5549  5595 I jxcore-log: 
09-28 07:50:35.257  5549  5595 I jxcore-log: ok 154 Salti was called with 'dbName' as 1-st argument
09-28 07:50:35.257  5549  5595 I jxcore-log: 
,09-28 07:50:35.257  5549  5595 I jxcore-log: ok 155 Salti was called with 'acl' as 2-st argument
09-28 07:50:35.257  5549  5595 I jxcore-log: 
,09-28 07:50:35.257  5549  5595 I jxcore-log: ok 156 Salti was called with 'thaliIdCallback' as 3-st argument
09-28 07:50:35.257  5549  5595 I jxcore-log: 
09-28 07:50:35.258  5549  5595 I jxcore-log: ok 157 Salti was called with 'options' as 4-st argument
09-28 07:50:35.258  5549  5595 I jxcore-log: 
09-28 07:50:35.258  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 07:50:35.258  5549  5595 I jxcore-log: 
,09-28 07:50:35.260  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 07:50:35.260  5549  5595 I jxcore-log: 
,09-28 07:50:35.261  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 07:50:35.261  5549  5595 I jxcore-log: 
,09-28 07:50:35.263  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start listening for advertisements'
09-28 07:50:35.263  5549  5595 I jxcore-log: 
,09-28 07:50:35.268  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start update advertising and listening'
09-28 07:50:35.268  5549  5595 I jxcore-log: 
,09-28 07:50:35.295  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliWifiInfrastructure: 'listening 46108'
09-28 07:50:35.295  5549  5595 I jxcore-log: 
,09-28 07:50:35.297  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 07:50:35.297  5549  5595 I jxcore-log: 
,09-28 07:50:35.332  5549  5595 I jxcore-log: ok 158 ThaliMobile.start was called once
09-28 07:50:35.332  5549  5595 I jxcore-log: 
,09-28 07:50:35.332  5549  5595 I jxcore-log: ok 159 ThaliMobile.start was called with 2 arguments
09-28 07:50:35.332  5549  5595 I jxcore-log: 
09-28 07:50:35.333  5549  5595 I jxcore-log: ok 160 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-28 07:50:35.333  5549  5595 I jxcore-log: 
09-28 07:50:35.333  5549  5595 I jxcore-log: ok 161 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-28 07:50:35.333  5549  5595 I jxcore-log: 
09-28 07:50:35.334  5549  5595 I jxcore-log: ok 162 ThaliMobile.startListeningForAdvertisements was called once
09-28 07:50:35.334  5549  5595 I jxcore-log: 
,09-28 07:50:35.334  5549  5595 I jxcore-log: ok 163 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-28 07:50:35.334  5549  5595 I jxcore-log: 
09-28 07:50:35.334  5549  5595 I jxcore-log: ok 164 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-28 07:50:35.334  5549  5595 I jxcore-log: 
09-28 07:50:35.334  5549  5595 I jxcore-log: ok 165 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-28 07:50:35.334  5549  5595 I jxcore-log: 
09-28 07:50:35.335  5549  5595 I jxcore-log: ok 166 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-28 07:50:35.335  5549  5595 I jxcore-log: 
09-28 07:50:35.335  5549  5595 I jxcore-log: ok 167 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-28 07:50:35.335  5549  5595 I jxcore-log: 
,09-28 07:50:35.335  5549  5595 I jxcore-log: ok 168 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 07:50:35.335  5549  5595 I jxcore-log: 
09-28 07:50:35.335  5549  5595 I jxcore-log: ok 169 ThaliPullReplicationFromNotification.prototype.start was called once
09-28 07:50:35.335  5549  5595 I jxcore-log: 
09-28 07:50:35.335  5549  5595 I jxcore-log: ok 170 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-28 07:50:35.335  5549  5595 I jxcore-log: 
09-28 07:50:35.336  5549  5595 I jxcore-log: ok 171 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 07:50:35.336  5549  5595 I jxcore-log: 
09-28 07:50:35.336  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 07:50:35.336  5549  5595 I jxcore-log: 
,09-28 07:50:35.337  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 07:50:35.337  5549  5595 I jxcore-log: 
09-28 07:50:35.339  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 07:50:35.339  5549  5595 I jxcore-log: 
,09-28 07:50:35.340  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 07:50:35.340  5549  5595 I jxcore-log: 
,09-28 07:50:35.344  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 07:50:35.344  5549  5595 I jxcore-log: 
,09-28 07:50:35.346  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 07:50:35.346  5549  5595 I jxcore-log: 
,09-28 07:50:35.349  5549  5595 I jxcore-log: ok 172 ThaliMobile.stop was called once
09-28 07:50:35.349  5549  5595 I jxcore-log: 
,09-28 07:50:35.349  5549  5595 I jxcore-log: ok 173 ThaliMobile.stop was called with 0 arguments
09-28 07:50:35.349  5549  5595 I jxcore-log: 
09-28 07:50:35.350  5549  5595 I jxcore-log: ok 174 ThaliMobile.stopListeningForAdvertisements was called once
09-28 07:50:35.350  5549  5595 I jxcore-log: 
09-28 07:50:35.350  5549  5595 I jxcore-log: ok 175 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-28 07:50:35.350  5549  5595 I jxcore-log: 
09-28 07:50:35.350  5549  5595 I jxcore-log: ok 176 ThaliMobile.stopAdvertisingAndListening was called once
09-28 07:50:35.350  5549  5595 I jxcore-log: 
,09-28 07:50:35.350  5549  5595 I jxcore-log: ok 177 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-28 07:50:35.350  5549  5595 I jxcore-log: 
09-28 07:50:35.351  5549  5595 I jxcore-log: ok 178 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-28 07:50:35.351  5549  5595 I jxcore-log: 
09-28 07:50:35.351  5549  5595 I jxcore-log: ok 179 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-28 07:50:35.351  5549  5595 I jxcore-log: 
09-28 07:50:35.351  5549  5595 I jxcore-log: ok 180 ThaliPullReplicationFromNotification.prototype.stop was called once
09-28 07:50:35.351  5549  5595 I jxcore-log: 
,09-28 07:50:35.351  5549  5595 I jxcore-log: ok 181 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-28 07:50:35.351  5549  5595 I jxcore-log: 
,09-28 07:50:35.361  5549  5595 I jxcore-log: # teardown
09-28 07:50:35.361  5549  5595 I jxcore-log: 
,09-28 07:50:35.457  5549  5595 I jxcore-log: # setup
09-28 07:50:35.457  5549  5595 I jxcore-log: 
,09-28 07:50:35.551   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:35.576  5549  5595 I jxcore-log: # test thali manager multiple starts and stops
09-28 07:50:35.576  5549  5595 I jxcore-log: 
,09-28 07:50:35.694  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-28 07:50:35.694  5549  5595 I jxcore-log: 
,09-28 07:50:35.700  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-28 07:50:35.700  5549  5595 I jxcore-log: 
,09-28 07:50:35.702  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'creating express pouchdb instance'
09-28 07:50:35.702  5549  5595 I jxcore-log: 
,09-28 07:50:35.722  5549  5595 I jxcore-log: ok 182 expressPouchDB was called once
09-28 07:50:35.722  5549  5595 I jxcore-log: 
,09-28 07:50:35.722  5549  5595 I jxcore-log: ok 183 expressPouchDB was called with 2 arguments
09-28 07:50:35.722  5549  5595 I jxcore-log: 
09-28 07:50:35.722  5549  5595 I jxcore-log: ok 184 expressPouchDB was called with 'PouchDB' as 1-st argument
09-28 07:50:35.722  5549  5595 I jxcore-log: 
09-28 07:50:35.722  5549  5595 I jxcore-log: ok 185 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
09-28 07:50:35.722  5549  5595 I jxcore-log: 
09-28 07:50:35.723  5549  5595 I jxcore-log: ok 186 PouchDB was called once
09-28 07:50:35.723  5549  5595 I jxcore-log: 
09-28 07:50:35.723  5549  5595 I jxcore-log: ok 187 PouchDB was called with 1 arguments
09-28 07:50:35.723  5549  5595 I jxcore-log: 
09-28 07:50:35.723  5549  5595 I jxcore-log: ok 188 PouchDB was called with 'dbName' as 1-st argument
09-28 07:50:35.723  5549  5595 I jxcore-log: 
,09-28 07:50:35.723  5549  5595 I jxcore-log: ok 189 ThaliSendNotificationBasedOnReplication was called once
09-28 07:50:35.723  5549  5595 I jxcore-log: 
09-28 07:50:35.724  5549  5595 I jxcore-log: ok 190 ThaliSendNotificationBasedOnReplication was called with 4 arguments
09-28 07:50:35.724  5549  5595 I jxcore-log: 
09-28 07:50:35.724  5549  5595 I jxcore-log: ok 191 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
09-28 07:50:35.724  5549  5595 I jxcore-log: 
,09-28 07:50:35.724  5549  5595 I jxcore-log: ok 192 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
09-28 07:50:35.724  5549  5595 I jxcore-log: 
09-28 07:50:35.725  5549  5595 I jxcore-log: ok 193 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
09-28 07:50:35.725  5549  5595 I jxcore-log: 
,09-28 07:50:35.725  5549  5595 I jxcore-log: ok 194 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
09-28 07:50:35.725  5549  5595 I jxcore-log: 
09-28 07:50:35.725  5549  5595 I jxcore-log: ok 195 ThaliPullReplicationFromNotification was called once
09-28 07:50:35.725  5549  5595 I jxcore-log: 
09-28 07:50:35.725  5549  5595 I jxcore-log: ok 196 ThaliPullReplicationFromNotification was called with 4 arguments
09-28 07:50:35.725  5549  5595 I jxcore-log: 
09-28 07:50:35.725  5549  5595 I jxcore-log: ok 197 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
09-28 07:50:35.725  5549  5595 I jxcore-log: 
,09-28 07:50:35.726  5549  5595 I jxcore-log: ok 198 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
09-28 07:50:35.726  5549  5595 I jxcore-log: 
09-28 07:50:35.726  5549  5595 I jxcore-log: ok 199 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
09-28 07:50:35.726  5549  5595 I jxcore-log: 
09-28 07:50:35.726  5549  5595 I jxcore-log: ok 200 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
09-28 07:50:35.726  5549  5595 I jxcore-log: 
09-28 07:50:35.726  5549  5595 I jxcore-log: ok 201 Salti was called once
09-28 07:50:35.726  5549  5595 I jxcore-log: 
09-28 07:50:35.726  5549  5595 I jxcore-log: ok 202 Salti was called with 4 arguments
09-28 07:50:35.726  5549  5595 I jxcore-log: 
09-28 07:50:35.727  5549  5595 I jxcore-log: ok 203 Salti was called with 'dbName' as 1-st argument
09-28 07:50:35.727  5549  5595 I jxcore-log: 
09-28 07:50:35.727  5549  5595 I jxcore-log: ok 204 Salti was called with 'acl' as 2-st argument
09-28 07:50:35.727  5549  5595 I jxcore-log: 
09-28 07:50:35.727  5549  5595 I jxcore-log: ok 205 Salti was called with 'thaliIdCallback' as 3-st argument
09-28 07:50:35.727  5549  5595 I jxcore-log: 
09-28 07:50:35.727  5549  5595 I jxcore-log: ok 206 Salti was called with 'options' as 4-st argument
09-28 07:50:35.727  5549  5595 I jxcore-log: 
,09-28 07:50:35.728  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 07:50:35.728  5549  5595 I jxcore-log: 
,09-28 07:50:35.729  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 07:50:35.729  5549  5595 I jxcore-log: 
,09-28 07:50:35.730  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 07:50:35.730  5549  5595 I jxcore-log: 
,09-28 07:50:35.734  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start listening for advertisements'
09-28 07:50:35.734  5549  5595 I jxcore-log: 
,09-28 07:50:35.738  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start update advertising and listening'
09-28 07:50:35.738  5549  5595 I jxcore-log: 
,09-28 07:50:35.744  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliWifiInfrastructure: 'listening 47640'
09-28 07:50:35.744  5549  5595 I jxcore-log: 
,09-28 07:50:35.746  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 07:50:35.746  5549  5595 I jxcore-log: 
,09-28 07:50:35.784  5549  5595 I jxcore-log: ok 207 ThaliMobile.start was called once
09-28 07:50:35.784  5549  5595 I jxcore-log: 
,09-28 07:50:35.785  5549  5595 I jxcore-log: ok 208 ThaliMobile.start was called with 2 arguments
09-28 07:50:35.785  5549  5595 I jxcore-log: 
09-28 07:50:35.785  5549  5595 I jxcore-log: ok 209 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-28 07:50:35.785  5549  5595 I jxcore-log: 
09-28 07:50:35.785  5549  5595 I jxcore-log: ok 210 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-28 07:50:35.785  5549  5595 I jxcore-log: 
09-28 07:50:35.785  5549  5595 I jxcore-log: ok 211 ThaliMobile.startListeningForAdvertisements was called once
09-28 07:50:35.785  5549  5595 I jxcore-log: 
,09-28 07:50:35.786  5549  5595 I jxcore-log: ok 212 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-28 07:50:35.786  5549  5595 I jxcore-log: 
09-28 07:50:35.786  5549  5595 I jxcore-log: ok 213 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-28 07:50:35.786  5549  5595 I jxcore-log: 
09-28 07:50:35.786  5549  5595 I jxcore-log: ok 214 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-28 07:50:35.786  5549  5595 I jxcore-log: 
09-28 07:50:35.786  5549  5595 I jxcore-log: ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-28 07:50:35.786  5549  5595 I jxcore-log: 
09-28 07:50:35.786  5549  5595 I jxcore-log: ok 216 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-28 07:50:35.786  5549  5595 I jxcore-log: 
,09-28 07:50:35.786  5549  5595 I jxcore-log: ok 217 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 07:50:35.786  5549  5595 I jxcore-log: 
09-28 07:50:35.786  5549  5595 I jxcore-log: ok 218 ThaliPullReplicationFromNotification.prototype.start was called once
09-28 07:50:35.786  5549  5595 I jxcore-log: 
09-28 07:50:35.787  5549  5595 I jxcore-log: ok 219 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-28 07:50:35.787  5549  5595 I jxcore-log: 
09-28 07:50:35.787  5549  5595 I jxcore-log: ok 220 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 07:50:35.787  5549  5595 I jxcore-log: 
,09-28 07:50:35.788  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 07:50:35.788  5549  5595 I jxcore-log: 
,09-28 07:50:35.788  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 07:50:35.788  5549  5595 I jxcore-log: 
,09-28 07:50:35.790  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 07:50:35.790  5549  5595 I jxcore-log: 
,09-28 07:50:35.792  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 07:50:35.792  5549  5595 I jxcore-log: 
,09-28 07:50:35.796  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 07:50:35.796  5549  5595 I jxcore-log: 
,09-28 07:50:35.797  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 07:50:35.797  5549  5595 I jxcore-log: 
,09-28 07:50:35.803  5549  5595 I jxcore-log: ok 221 ThaliMobile.stop was called once
09-28 07:50:35.803  5549  5595 I jxcore-log: 
,09-28 07:50:35.803  5549  5595 I jxcore-log: ok 222 ThaliMobile.stop was called with 0 arguments
09-28 07:50:35.803  5549  5595 I jxcore-log: 
09-28 07:50:35.803  5549  5595 I jxcore-log: ok 223 ThaliMobile.stopListeningForAdvertisements was called once
09-28 07:50:35.803  5549  5595 I jxcore-log: 
,09-28 07:50:35.804  5549  5595 I jxcore-log: ok 224 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
09-28 07:50:35.804  5549  5595 I jxcore-log: 
09-28 07:50:35.804  5549  5595 I jxcore-log: ok 225 ThaliMobile.stopAdvertisingAndListening was called once
09-28 07:50:35.804  5549  5595 I jxcore-log: 
09-28 07:50:35.804  5549  5595 I jxcore-log: ok 226 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
09-28 07:50:35.804  5549  5595 I jxcore-log: 
09-28 07:50:35.804  5549  5595 I jxcore-log: ok 227 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
09-28 07:50:35.804  5549  5595 I jxcore-log: 
09-28 07:50:35.804  5549  5595 I jxcore-log: ok 228 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
09-28 07:50:35.804  5549  5595 I jxcore-log: 
,09-28 07:50:35.804  5549  5595 I jxcore-log: ok 229 ThaliPullReplicationFromNotification.prototype.stop was called once
09-28 07:50:35.804  5549  5595 I jxcore-log: 
09-28 07:50:35.804  5549  5595 I jxcore-log: ok 230 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
09-28 07:50:35.804  5549  5595 I jxcore-log: 
09-28 07:50:35.805  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 07:50:35.805  5549  5595 I jxcore-log: 
,09-28 07:50:35.805  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 07:50:35.805  5549  5595 I jxcore-log: 
,09-28 07:50:35.806  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 07:50:35.806  5549  5595 I jxcore-log: 
,09-28 07:50:35.809  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start listening for advertisements'
09-28 07:50:35.809  5549  5595 I jxcore-log: 
,09-28 07:50:35.812  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start update advertising and listening'
09-28 07:50:35.812  5549  5595 I jxcore-log: 
,09-28 07:50:35.817  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliWifiInfrastructure: 'listening 47920'
09-28 07:50:35.817  5549  5595 I jxcore-log: 
,09-28 07:50:35.820  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 07:50:35.820  5549  5595 I jxcore-log: 
,09-28 07:50:35.822  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 07:50:35.822  5549  5595 I jxcore-log: 
,09-28 07:50:35.823  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 07:50:35.823  5549  5595 I jxcore-log: 
,09-28 07:50:35.825  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 07:50:35.825  5549  5595 I jxcore-log: 
,09-28 07:50:35.826  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 07:50:35.826  5549  5595 I jxcore-log: 
,09-28 07:50:35.830  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 07:50:35.830  5549  5595 I jxcore-log: 
,09-28 07:50:35.832  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 07:50:35.832  5549  5595 I jxcore-log: 
,09-28 07:50:35.837  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 07:50:35.837  5549  5595 I jxcore-log: 
,09-28 07:50:35.838  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 07:50:35.838  5549  5595 I jxcore-log: 
,09-28 07:50:35.838  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 07:50:35.838  5549  5595 I jxcore-log: 
,09-28 07:50:35.841  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start listening for advertisements'
09-28 07:50:35.841  5549  5595 I jxcore-log: 
,09-28 07:50:35.843  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start update advertising and listening'
09-28 07:50:35.843  5549  5595 I jxcore-log: 
,09-28 07:50:35.848  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliWifiInfrastructure: 'listening 44771'
09-28 07:50:35.848  5549  5595 I jxcore-log: 
,09-28 07:50:35.851  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 07:50:35.851  5549  5595 I jxcore-log: 
,09-28 07:50:35.853  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 07:50:35.853  5549  5595 I jxcore-log: 
,09-28 07:50:35.854  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 07:50:35.854  5549  5595 I jxcore-log: 
,09-28 07:50:35.856  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 07:50:35.856  5549  5595 I jxcore-log: 
,09-28 07:50:35.857  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 07:50:35.857  5549  5595 I jxcore-log: 
,09-28 07:50:35.860  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 07:50:35.860  5549  5595 I jxcore-log: 
,09-28 07:50:35.862  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 07:50:35.862  5549  5595 I jxcore-log: 
,09-28 07:50:35.865  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 07:50:35.865  5549  5595 I jxcore-log: 
,09-28 07:50:35.865  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 07:50:35.865  5549  5595 I jxcore-log: 
,09-28 07:50:35.866  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 07:50:35.866  5549  5595 I jxcore-log: 
,09-28 07:50:35.867  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start listening for advertisements'
09-28 07:50:35.867  5549  5595 I jxcore-log: 
,09-28 07:50:35.869  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'start update advertising and listening'
09-28 07:50:35.869  5549  5595 I jxcore-log: 
,09-28 07:50:35.874  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliWifiInfrastructure: 'listening 46276'
09-28 07:50:35.874  5549  5595 I jxcore-log: 
,09-28 07:50:35.876  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 07:50:35.876  5549  5595 I jxcore-log: 
,09-28 07:50:35.879  5549  5595 I jxcore-log: ok 231 ThaliMobile.start was called once
09-28 07:50:35.879  5549  5595 I jxcore-log: 
,09-28 07:50:35.880  5549  5595 I jxcore-log: ok 232 ThaliMobile.start was called with 2 arguments
09-28 07:50:35.880  5549  5595 I jxcore-log: 
09-28 07:50:35.880  5549  5595 I jxcore-log: ok 233 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
09-28 07:50:35.880  5549  5595 I jxcore-log: 
,09-28 07:50:35.880  5549  5595 I jxcore-log: ok 234 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
09-28 07:50:35.880  5549  5595 I jxcore-log: 
09-28 07:50:35.880  5549  5595 I jxcore-log: ok 235 ThaliMobile.startListeningForAdvertisements was called once
09-28 07:50:35.880  5549  5595 I jxcore-log: 
09-28 07:50:35.880  5549  5595 I jxcore-log: ok 236 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
09-28 07:50:35.880  5549  5595 I jxcore-log: 
,09-28 07:50:35.881  5549  5595 I jxcore-log: ok 237 ThaliMobile.startUpdateAdvertisingAndListening was called once
09-28 07:50:35.881  5549  5595 I jxcore-log: 
09-28 07:50:35.881  5549  5595 I jxcore-log: ok 238 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
09-28 07:50:35.881  5549  5595 I jxcore-log: 
09-28 07:50:35.881  5549  5595 I jxcore-log: ok 239 ThaliSendNotificationBasedOnReplication.prototype.start was called once
09-28 07:50:35.881  5549  5595 I jxcore-log: 
09-28 07:50:35.881  5549  5595 I jxcore-log: ok 240 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
09-28 07:50:35.881  5549  5595 I jxcore-log: 
,09-28 07:50:35.881  5549  5595 I jxcore-log: ok 241 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 07:50:35.881  5549  5595 I jxcore-log: 
09-28 07:50:35.881  5549  5595 I jxcore-log: ok 242 ThaliPullReplicationFromNotification.prototype.start was called once
09-28 07:50:35.881  5549  5595 I jxcore-log: 
,09-28 07:50:35.882  5549  5595 I jxcore-log: ok 243 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
09-28 07:50:35.882  5549  5595 I jxcore-log: 
09-28 07:50:35.882  5549  5595 I jxcore-log: ok 244 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
09-28 07:50:35.882  5549  5595 I jxcore-log: 
09-28 07:50:35.882  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
09-28 07:50:35.882  5549  5595 I jxcore-log: 
,09-28 07:50:35.883  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
09-28 07:50:35.883  5549  5595 I jxcore-log: 
09-28 07:50:35.885  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
09-28 07:50:35.885  5549  5595 I jxcore-log: 
09-28 07:50:35.886  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping advertising and listening'
09-28 07:50:35.886  5549  5595 I jxcore-log: 
,09-28 07:50:35.890  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping listening for advertisements'
09-28 07:50:35.890  5549  5595 I jxcore-log: 
,09-28 07:50:35.892  5549  5595 I jxcore-log: 2016-09-28 11:50:35 - DEBUG thaliManager: 'stopping ThaliMobile'
09-28 07:50:35.892  5549  5595 I jxcore-log: 
,09-28 07:50:35.897  5549  5595 I jxcore-log: # teardown
09-28 07:50:35.897  5549  5595 I jxcore-log: 
,09-28 07:50:36.012  5549  5595 I jxcore-log: # setup
09-28 07:50:36.012  5549  5595 I jxcore-log: 
,09-28 07:50:36.089  5549  5595 I jxcore-log: # test write
09-28 07:50:36.089  5549  5595 I jxcore-log: 
,09-28 07:50:36.262  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
09-28 07:50:36.262  5549  5595 I jxcore-log: 
,09-28 07:50:36.266  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
09-28 07:50:36.266  5549  5595 I jxcore-log: 
09-28 07:50:36.268  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'creating express pouchdb instance'
09-28 07:50:36.268  5549  5595 I jxcore-log: 
,09-28 07:50:36.303  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
09-28 07:50:36.303  5549  5595 I jxcore-log: 
,09-28 07:50:36.305  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
09-28 07:50:36.305  5549  5595 I jxcore-log: 
09-28 07:50:36.305  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'starting ThaliMobile'
09-28 07:50:36.305  5549  5595 I jxcore-log: 
,09-28 07:50:36.307  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'start listening for advertisements'
09-28 07:50:36.307  5549  5595 I jxcore-log: 
,09-28 07:50:36.313  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'start update advertising and listening'
09-28 07:50:36.313  5549  5595 I jxcore-log: 
,09-28 07:50:36.320  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliWifiInfrastructure: 'listening 39620'
09-28 07:50:36.320  5549  5595 I jxcore-log: 
,09-28 07:50:36.324  5549  5595 I jxcore-log: 2016-09-28 11:50:36 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
09-28 07:50:36.324  5549  5595 I jxcore-log: 
,09-28 07:50:36.551   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-28 07:50:37.137  5549  5595 I jxcore-log: 2016-09-28 11:50:37 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-28 07:50:37.137  5549  5595 I jxcore-log: 
,09-28 07:50:37.170  5549  5595 I jxcore-log: 2016-09-28 11:50:37 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
09-28 07:50:37.170  5549  5595 I jxcore-log: 
,09-28 07:50:37.558  5549  5595 E jxcore-log: Error in .on("change", function): { [AssertionError: If beacons werepreviously updated then there has to be a refresh timer for them.]
09-28 07:50:37.558  5549  5595 E jxcore-log:   name: 'AssertionError',
09-28 07:50:37.558  5549  5595 E jxcore-log:   actual: null,
09-28 07:50:37.558  5549  5595 E jxcore-log:   expected: true,
09-28 07:50:37.558  5549  5595 E jxcore-log:   operator: '==',
09-28 07:50:37.558  5549  5595 E jxcore-log:   message: 'If beacons werepreviously updated then there has to be a refresh timer for them.',
09-28 07:50:37.558  5549  5595 E jxcore-log:   stack: 'ok@assert.js:126:1\nThaliSendNotificationBasedOnReplication.prototype._setUpChangeListener/this._replicationPromise</self._transientState.pouchDBChangesCancelObject<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js:358:9\nemit@events.js:82:1' }
09-28 07:50:37.558  5549  5595 E jxcore-log: 
,09-28 07:50:37.615  5549  5595 I jxcore-log: # teardown
09-28 07:50:37.615  5549  5595 I jxcore-log: 
,09-28 07:50:37.894  5549  5595 I jxcore-log: 2016-09-28 11:50:37 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-28 07:50:37.894  5549  5595 I jxcore-log: 
,09-28 07:50:38.001  5549  5595 I jxcore-log: 2016-09-28 11:50:38 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
09-28 07:50:38.001  5549  5595 I jxcore-log: 
,09-28 07:50:48.853   929  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 07:50:51.552   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:52.553   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:53.555   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:54.556   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:55.558   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:50:56.559   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-28 07:51:07.494  5549  5595 I jxcore-log: 2016-09-28 11:51:07 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
09-28 07:51:07.494  5549  5595 I jxcore-log: 
,09-28 07:51:07.525  5549  5595 I jxcore-log: 2016-09-28 11:51:07 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
09-28 07:51:07.525  5549  5595 I jxcore-log: 
,09-28 07:51:08.855   929  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 07:51:12.719   929  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-28 07:51:16.560   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:51:17.561   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:51:18.563   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:51:19.564   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:51:20.565   567   567 I ServiceManager: Waiting for service AtCmdFwd...
,09-28 07:51:21.566   567   567 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-28 07:51:21.652   929  5844 D NetlinkSocketObserver: NeighborEvent{elapsedMs=418850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-28 07:51:28.855   929  2925 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-28 07:51:37.636  5549  5595 I jxcore-log: 2016-09-28 11:51:37 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-28 07:51:37.636  5549  5595 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-28 07:51:37.636  5549  5595 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-28 07:51:37.636  5549  5595 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-28 07:51:37.636  5549  5595 I jxcore-log:     at $9@timers.js:120:1
09-28 07:51:37.636  5549  5595 I jxcore-log: ''
09-28 07:51:37.636  5549  5595 I jxcore-log: 
,09-28 07:51:37.641  5549  5595 I jxcore-log: 2016-09-28 11:51:37 - DEBUG CoordinatedClient: 'test client failed'
09-28 07:51:37.641  5549  5595 I jxcore-log: 
,09-28 07:51:37.653  5549  5595 I jxcore-log: 2016-09-28 11:51:37 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-28 07:51:37.653  5549  5595 I jxcore-log: 
,09-28 07:51:37.660  5549  5595 I jxcore-log: 2016-09-28 11:51:37 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
09-28 07:51:37.660  5549  5595 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-28 07:51:37.660  5549  5595 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-28 07:51:37.660  5549  5595 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-28 07:51:37.660  5549  5595 I jxcore-log:     at $9@timers.js:120:1
09-28 07:51:37.660  5549  5595 I jxcore-log: ''
09-28 07:51:37.660  5549  5595 I jxcore-log: 
,09-28 07:51:37.662  5549  5595 I jxcore-log: 2016-09-28 11:51:37 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-28 07:51:37.662  5549  5595 I jxcore-log: 
,09-28 07:51:38.261  5898  5898 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-28 07:51:38.283  5898  5898 D AndroidRuntime: CheckJNI is OFF
,09-28 07:51:38.307  5898  5898 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-28 07:51:38.335  5898  5898 I Radio-JNI: register_android_hardware_Radio DONE
,09-28 07:51:38.352  5898  5898 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-28 07:51:38.361   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-28 07:51:38.362   929   942 I ActivityManager: Killing 5549:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-28 07:51:38.473   929  3750 I WindowState: WIN DEATH: Window{26ee006 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-28 07:51:38.473   929  3360 D GraphicsStats: Buffer count: 2
09-28 07:51:38.473   929  2926 D WifiService: Client connection lost with reason: 4
,09-28 07:51:38.500   929   952 I art     : Starting a blocking GC Explicit
,09-28 07:51:38.499   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-28 07:51:38.502   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-28 07:51:38.503   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-28 07:51:38.503   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-28 07:51:38.503   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:51:38.503   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:51:38.503   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 07:51:38.503   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-28 07:51:38.503   929   942 I ActivityManager:   Force finishing activity ActivityRecord{60b670b u0 com.test.thalitest/.MainActivity t2}
,09-28 07:51:38.513   929  3359 W ActivityManager: Spurious death for ProcessRecord{23dda80 0:com.test.thalitest/u0a77}, curProc for 5549: null
,09-28 07:51:38.527   929   947 W WindowManager: Attempted to add application window with unknown token Token{9c269e8 ActivityRecord{60b670b u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-28 07:51:38.527   929   947 W WindowManager: Token{9c269e8 ActivityRecord{60b670b u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{9c269e8 ActivityRecord{60b670b u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-28 07:51:38.527   929   947 W WindowManager: view not successfully added to wm, removing view
09-28 07:51:38.527   929   947 W WindowManager: Exception when adding starting window
09-28 07:51:38.527   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{43a277b V.E...... R.....ID 0,0-0,0} not attached to window manager
09-28 07:51:38.527   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-28 07:51:38.527   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-28 07:51:38.527   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-28 07:51:38.527   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-28 07:51:38.527   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-28 07:51:38.527   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:51:38.527   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:51:38.527   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-28 07:51:38.527   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-28 07:51:38.594   929   952 I art     : Explicit concurrent mark sweep GC freed 92871(6MB) AllocSpace objects, 50(2MB) LOS objects, 33% free, 29MB/43MB, paused 1.735ms total 92.542ms
,09-28 07:51:38.613   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-28 07:51:38.616  5898  5898 I art     : System.exit called, status: 0
,09-28 07:51:38.616  5898  5898 I AndroidRuntime: VM exiting with result code 0.
,09-28 07:51:38.620   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-28 07:51:38.626   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-28 07:51:38.630  5787  5787 D BluetoothMapAppObserver: onReceive
,09-28 07:51:38.630  5787  5787 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-28 07:51:38.641  3597  3597 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-28 07:51:38.641   929  2888 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-28 07:51:38.647  3696  4023 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-28 07:51:38.694  3761  3761 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-28 07:51:38.705  3597  5909 I Keyboard.Facilitator.DecoderInitializer: run()
,09-28 07:51:38.708  3345  5910 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-28 07:51:38.709   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-28 07:51:38.713  3528  3528 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-28 07:51:38.713  3528  3528 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-28 07:51:38.724  3597  5909 I Decoder : createOrResetDecoder
,09-28 07:51:38.726    13    13 W kworker/1:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 07:51:38.733    13    13 W kworker/1:0: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 07:51:38.727  3951  5915 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-28 07:51:38.750  3951  5915 D AccountUtils: Clearing selected account for com.test.thalitest
09-28 07:51:38.746    13    13 W kworker/1:0: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-28 07:51:38.770  4775  4784 W art     : Suspending all threads took: 8.340ms
,09-28 07:51:38.779  3345  3371 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
09-28 07:51:38.779  3345  3371 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj0E03E292B) - 
,09-28 07:51:38.790  3528  3528 I ConfigService: onCreate
,09-28 07:51:38.794  3528  5918 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-28 07:51:38.794  3528  5918 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-28 07:51:38.794  3528  5918 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-28 07:51:38.796  3528  5918 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-28 07:51:38.806  3951  5915 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-28 07:51:38.820  3597  5909 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-28 07:51:38.832  3951  5915 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:51:38.832  3951  5915 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:51:38.832  3951  5915 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,--------- beginning of crash
09-28 07:51:38.841  3345  3371 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-28 07:51:38.841  3345  3371 E AndroidRuntime: Process: android.process.acore, PID: 3345
09-28 07:51:38.841  3345  3371 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-28 07:51:38.841  3345  3371 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-28 07:51:38.833  3951  5915 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-28 07:51:38.897  3345  3371 I Process : Sending signal. PID: 3345 SIG: 9
,09-28 07:51:38.932  3951  5923 I GMPM-SVC: App measurement is starting up
,09-28 07:51:38.938  3951  5923 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-28 07:51:38.939  3951  5923 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-28 07:51:39.146   384   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
