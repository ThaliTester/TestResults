#### Test 85067679b83ffc4_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-14 06:35:52.477   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-14 06:35:52.477   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:35:53.001  5487  5487 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-14 06:35:53.006  5487  5487 D AndroidRuntime: CheckJNI is OFF
09-14 06:35:53.038  5487  5487 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-14 06:35:53.078  5487  5487 I Radio-JNI: register_android_hardware_Radio DONE
09-14 06:35:53.093  5487  5487 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-14 06:35:53.103   931   941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-14 06:35:53.140   931   941 I ActivityManager: Start proc 5496:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-14 06:35:53.145  5487  5487 D AndroidRuntime: Shutting down VM
09-14 06:35:53.251  5496  5496 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-14 06:35:53.280  5496  5496 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-14 06:35:53.302  5496  5496 I LibraryLoader: Time to load native libraries: 17 ms (timestamps 125-142)
09-14 06:35:53.302  5496  5496 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 06:35:53.320  5496  5496 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e777a16}
09-14 06:35:53.321  5496  5496 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 06:35:53.321  5496  5496 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-14 06:35:53.325  5496  5496 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-14 06:35:53.327  5496  5496 E SysUtils: ApplicationContext is null in ApplicationStatus
09-14 06:35:53.364  5496  5496 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-14 06:35:53.389  5496  5496 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-14 06:35:53.390  5496  5496 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 06:35:53.390  5496  5496 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-14 06:35:53.390  5496  5496 I Adreno  : Build Date                       : 12/06/15
09-14 06:35:53.390  5496  5496 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 06:35:53.390  5496  5496 I Adreno  : Local Branch                     : mybranch17112971
09-14 06:35:53.390  5496  5496 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-14 06:35:53.390  5496  5496 I Adreno  : Remote Branch                    : NONE
09-14 06:35:53.390  5496  5496 I Adreno  : Reconstruct Branch               : NOTHING
,09-14 06:35:53.446   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b92986c:true
,09-14 06:35:53.480  3675  3675 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14073]" dev="sockfs" ino=14073 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:35:53.480  3675  3675 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[14073]" dev="sockfs" ino=14073 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:35:53.493  5496  5496 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-14 06:35:53.502  5496  5496 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-14 06:35:53.587  3675  3675 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[28618]" dev="sockfs" ino=28618 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:35:53.587  3675  3675 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[28618]" dev="sockfs" ino=28618 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-14 06:35:53.588  5496  5533 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-14 06:35:53.590  3551  3551 W Binder_A: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[14084]" dev="sockfs" ino=14084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:35:53.590  3551  3551 W Binder_A: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[14084]" dev="sockfs" ino=14084 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:35:53.596  5496  5520 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-14 06:35:53.639  5496  5533 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 06:35:53.710   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +524ms (total +594ms)
,09-14 06:35:53.733  5496  5496 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5496
,09-14 06:35:53.824  5496  5496 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-14 06:35:54.011  5496  5536 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -604243664
,09-14 06:35:54.018  5496  5536 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-14 06:35:54.018  5496  5536 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-14 06:35:54.018  5496  5536 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-14 06:35:54.018  5496  5536 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-14 06:35:54.018  5496  5536 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-14 06:35:54.018  5496  5536 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab97e4f added. We now have 1 listener(s)
,09-14 06:35:54.022  5496  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-14 06:35:54.023  5496  5536 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:35:54.024  5496  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 06:35:54.024  5496  5536 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-14 06:35:54.029  5496  5536 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17f79ba added. We now have 1 listener(s)
09-14 06:35:54.029  5496  5536 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:35:54.033   931  2970 D WifiService: New client listening to asynchronous messages
,09-14 06:35:54.034  5496  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 06:35:54.034  5496  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-14 06:35:54.034  5496  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-14 06:35:54.034  5496  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-14 06:35:54.034  5496  5536 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-14 06:35:54.037  5496  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:35:54.037  5496  5536 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-14 06:35:54.044  5496  5536 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:35:54.044  5496  5536 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:35:54.044  5496  5536 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-14 06:35:54.044  5496  5536 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:35:54.047  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:35:54.047  5496  5536 I io.jxcore.node.LifeCycleMonitor: start: OK
09-14 06:35:54.049  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:35:54.075  5496  5496 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-14 06:35:54.483  5496  5505 I art     : Background sticky concurrent mark sweep GC freed 80576(7MB) AllocSpace objects, 18(1676KB) LOS objects, 26% free, 24MB/32MB, paused 1.570ms total 229.691ms
,09-14 06:35:55.937  5496  5542 W jxcore-log: Initializing JXcore engine
,09-14 06:35:55.937  5496  5542 W jxcore-log: JXcore engine is ready
,09-14 06:35:55.970  5542  5542 W Thread-57: type=1400 audit(0.0:116): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1165 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-14 06:35:55.970  5542  5542 W Thread-57: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[16391]" dev="sockfs" ino=16391 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-14 06:35:55.970  5542  5542 W Thread-57: type=1400 audit(0.0:118): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-14 06:35:55.970  5542  5542 W Thread-57: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31490]" dev="sockfs" ino=31490 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-14 06:35:55.979  5496  5542 W jxcore-log: Starting JXcore engine
,09-14 06:35:56.030  5496  5542 W jxcore-log: Platform android
09-14 06:35:56.030  5496  5542 W jxcore-log: 
,09-14 06:35:56.031  5496  5542 W jxcore-log: Process ARCH arm
09-14 06:35:56.031  5496  5542 W jxcore-log: 
,09-14 06:35:56.153  5496  5542 I jxcore-log: JXcore Cordova bridge is ready!
09-14 06:35:56.153  5496  5542 I jxcore-log: 
,09-14 06:35:56.154  5496  5542 W jxcore-log: JXcore engine is started
,09-14 06:35:56.176  5496  5536 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-14 06:35:56.182  5496  5496 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-14 06:36:02.478   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:03.480   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:04.481   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:05.482   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:05.846  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 06:36:05.846  5496  5542 I jxcore-log: 
,09-14 06:36:05.848  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 06:36:05.848  5496  5542 I jxcore-log: 
,09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:36:05.852  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 06:36:05.854  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 06:36:05.855  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 06:36:05.855  5496  5542 I jxcore-log: 
,09-14 06:36:05.857  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 06:36:05.857  5496  5542 I jxcore-log: 
,09-14 06:36:06.101  5496  5542 D ExecuteNativeTests: Running unit tests
,09-14 06:36:06.137  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 06:36:06.137  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 added. We now have 2 listener(s)
,09-14 06:36:06.138  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-14 06:36:06.138  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:06.138  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:06.138  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 06:36:06.138  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 added. We now have 2 listener(s)
09-14 06:36:06.138  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:36:06.139  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:36:06.140  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:36:06.142  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:36:06.143  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.143  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:36:06.144  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 06:36:06.145  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:36:06.145  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:36:06.145  5496  5542 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-14 06:36:06.145  5496  5542 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 06:36:06.145  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 06:36:06.145  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:36:06.145  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:36:06.146  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.146  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.146  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.146  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.146  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.146  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:06.146  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:06.147  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 removed from the list
09-14 06:36:06.147  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.147  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 removed from the list
09-14 06:36:06.149  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.155  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.155  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.156  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.156  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.156  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.156  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.156  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.157  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.157  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.157  5496  5542 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-14 06:36:06.158  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.158  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.158  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.158  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 06:36:06.158  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.158  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.158  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.158  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.158  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.158  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.158  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:06.158  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.158  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.158  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.159  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.159  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.159  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.159  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 06:36:06.161  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 06:36:06.162  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 06:36:06.163  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.163  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.163  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.163  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.163  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.163  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.163  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.163  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.163  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.163  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.163  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.163  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.163  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.163  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.164  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.164  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.164  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.164  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.164  5496  5542 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 06:36:06.165  5496  5542 I org.thaliproject.p2p.btconnect,orlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:36:06.167  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:36:06.168  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.168  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:36:06.168  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:36:06.168  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:36:06.168  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:36:06.168  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.169  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.170  5496  5542 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:06.170  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:36:06.171  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.173  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:36:06.174  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.174  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:06.174  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:36:06.175  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-14 06:36:06.177  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-14 06:36:06.177  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 06:36:06.178  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:36:06.178  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:36:06.178  5496  5542 D BluetoothAdapter: STATE_ON
,09-14 06:36:06.181  4472  4718 D BtGatt.GattService: registerClient() - UUID=d9fa59d2-4010-4d0e-b376-324f121ac12c
,09-14 06:36:06.181  4472  4546 D BtGatt.GattService: onClientRegistered() - UUID=d9fa59d2-4010-4d0e-b376-324f121ac12c, clientIf=5
,09-14 06:36:06.182  5496  5506 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:36:06.183  4472  4492 D BtGatt.GattService: start scan with filters
,09-14 06:36:06.187  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 06:36:06.187  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:36:06.187  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:36:06.187  4472  4551 D BtGatt.ScanManager: handling starting scan
09-14 06:36:06.187  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:36:06.188  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:36:06.188  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:36:06.189  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:06.189  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 06:36:06.190  4472  4551 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:06.191  5496  5542 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 06:36:06.192  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.192  5496  5542 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 06:36:06.192  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:36:06.192  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:36:06.192  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.192  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:06.192  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:36:06.192  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:36:06.192  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:36:06.192  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:36:06.192  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:36:06.192  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:36:06.193  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.193  4472  4719 D BtGatt.GattService: stopScan() - queue size =1
09-14 06:36:06.193  4472  4702 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:36:06.193  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 06:36:06.193  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:36:06.193  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:36:06.193  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:36:06.193  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 06:36:06.195  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 06:36:06.195  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.195  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:36:06.195  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.195  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.196  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.196  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.196  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.196  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.196  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.196  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:36:06.196  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.196  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.196  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.196  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.196  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.196  5496  5542 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 06:36:06.196  4472  4546 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:36:06.197  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.197  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.197  4472  4551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:36:06.199  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 06:36:06.201  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 06:36:06.201  5496  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:36:06.202  4472  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:36:06.202  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.202  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.203  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:36:06.203  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:36:06.203  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:36:06.203  4472  4551 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:36:06.203  4472  4551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 06:36:06.209  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:36:06.210  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:06.210  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:36:06.211  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.211  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:06.213  4472  4546 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:36:06.213  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:06.214  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:36:06.214  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.214  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.216  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:06.216  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.217  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:06.218  4472  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:36:06.218  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.218  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:06.219  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:36:06.219  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.219  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 06:36:06.221  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:06.223  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.223  5496  5542 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 06:36:06.225  4472  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 06:36:06.225  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.225  4472  4551 D BtGatt.ScanManager: stopping BLe Batch
09-14 06:36:06.225  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 06:36:06.225  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:36:06.225  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:36:06.226  5496  5542 D BluetoothAdapter: STATE_ON
,09-14 06:36:06.228  4472  4488 D BtGatt.GattService: registerClient() - UUID=d1af563e-36ab-43b8-b743-95c6c9755b8e
,09-14 06:36:06.228  4472  4546 D BtGatt.GattService: onClientRegistered() - UUID=d1af563e-36ab-43b8-b743-95c6c9755b8e, clientIf=5
,09-14 06:36:06.229  5496  5507 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 06:36:06.229  4472  4702 D BtGatt.GattService: start scan with filters
09-14 06:36:06.229  4472  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:36:06.229  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.230  4472  4551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 06:36:06.231  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 06:36:06.231  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:36:06.231  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-14 06:36:06.231  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:36:06.233  4472  4546 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 06:36:06.233  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.234  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:06.234  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:36:06.234  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:06.234  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 06:36:06.234  4472  4551 D BtGatt.ScanManager: handling starting scan
,09-14 06:36:06.235  5496  5542 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 06:36:06.237  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:36:06.237  5496  5542 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 06:36:06.237  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.237  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:36:06.237  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.237  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:06.237  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:36:06.237  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:36:06.237  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:36:06.237  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:36:06.237  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:36:06.237  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-14 06:36:06.238  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.238  4472  4492 D BtGatt.GattService: stopScan() - queue size =1
09-14 06:36:06.238  4472  4546 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:36:06.238  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.238  4472  4551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 06:36:06.239  4472  4488 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:36:06.239  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.239  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:36:06.239  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:36:06.239  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:36:06.239  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 06:36:06.240  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:06.240  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 06:36:06.241  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:36:06.241  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 06:36:06.241  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.242  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:06.242  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.242  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.242  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.242  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.242  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:06.242  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.243  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:06.243  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.243  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.243  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.243  4472  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:36:06.243  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.243  4472  4551 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:36:06.244  4472  4551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 06:36:06.245  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 06:36:06.245  5496  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:36:06.248  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:36:06.249  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:06.249  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:36:06.249  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.249  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.251  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:36:06.251  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.251  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.252  4472  4546 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:36:06.252  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.255  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:06.255  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.255  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.256  4472  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-14 06:36:06.256  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.257  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:06.257  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.257  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.258  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.258  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.258  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.259  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.259  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.259  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.259  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.259  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.259  5496  5542 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 06:36:06.261  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:06.262  4472  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 06:36:06.262  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.262  4472  4551 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:36:06.264  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:36:06.266  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.267  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 06:36:06.267  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 06:36:06.267  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:36:06.267  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:36:06.267  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.267  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.268  4472  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:36:06.268  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:06.268  4472  4551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 06:36:06.269  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.270  5496  5542 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 06:36:06.271  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:06.273  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 06:36:06.273  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-14 06:36:06.273  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:36:06.273  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.274  4472  4546 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 06:36:06.274  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.275  4472  4492 D BtGatt.GattService: registerClient() - UUID=0a901ecf-6f1d-45cb-b63f-184c0f2c3d5c
,09-14 06:36:06.275  4472  4546 D BtGatt.GattService: onClientRegistered() - UUID=0a901ecf-6f1d-45cb-b63f-184c0f2c3d5c, clientIf=5
,09-14 06:36:06.275  5496  5507 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:36:06.276  4472  4488 D BtGatt.GattService: start scan with filters
,09-14 06:36:06.278  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 06:36:06.278  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-14 06:36:06.278  4472  4551 D BtGatt.ScanManager: handling starting scan
,09-14 06:36:06.278  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:36:06.278  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:36:06.280  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:06.280  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:36:06.281  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 06:36:06.282  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:06.283  5496  5542 I io.jxcore.node.ConnectionHelper: start: OK
09-14 06:36:06.283  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.283  5496  5542 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 06:36:06.283  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.283  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-14 06:36:06.283  4472  4546 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:36:06.283  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.283  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:06.283  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.283  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-14 06:36:06.283  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:36:06.283  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:36:06.283  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:36:06.283  4472  4551 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 06:36:06.283  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:36:06.283  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-14 06:36:06.284  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.285  4472  4492 D BtGatt.GattService: stopScan() - queue size =1
09-14 06:36:06.285  4472  4488 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:36:06.285  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.285  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:36:06.285  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:36:06.285  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:36:06.286  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 06:36:06.287  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:06.287  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 06:36:06.287  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:36:06.287  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.288  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.288  4472  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:36:06.288  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.288  4472  4551 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:36:06.288  4472  4551 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 06:36:06.288  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:06.288  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.289  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 06:36:06.289  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.289  5496  5542 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 06:36:06.289  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.289  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.289  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.289  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.289  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:06.289  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.289  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:06.289  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.289  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.289  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:06.292  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 06:36:06.292  5496  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:36:06.295  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:36:06.295  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 06:36:06.295  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:36:06.295  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.296  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.297  4472  4546 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:36:06.297  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:06.298  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:36:06.298  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.298  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.300  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:06.300  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.301  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.302  4472  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:36:06.302  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:06.303  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:06.303  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.303  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:06.304  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.304  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 06:36:06.305  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.305  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.305  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.305  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.305  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.305  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.306  5496  5542 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-14 06:36:06.306  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.306  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.306  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 06:36:06.306  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.306  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.307  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.307  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.307  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.307  4472  4546 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 06:36:06.307  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.307  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.307  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.307  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.307  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.307  4472  4551 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:36:06.307  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.307  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.309  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.309  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.309  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.310  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.310  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.310  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.310  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.310  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.311  4472  4546 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:36:06.311  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.311  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 06:36:06.311  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.311  4472  4551 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-14 06:36:06.311  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.311  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.311  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.311  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.311  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.312  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.312  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.312  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.312  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.312  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.312  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.312  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.312  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.313  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.313  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.313  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.314  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.314  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.314  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.314  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:06.314  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.315  5496  5542 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-14 06:36:06.315  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.315  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.315  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.315  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.316  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.316  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.316  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.316  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:06.316  4472  4546 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 06:36:06.316  4472  4546 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:06.316  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.316  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.316  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.316  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.316  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.316  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.317  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:36:06.317  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.317  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.317  5496  5542 D BluetoothAdapter: STATE_ON
,09-14 06:36:06.318  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.318  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.318  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.318  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.318  5496  5542 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-14 06:36:06.319  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.319  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.319  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.319  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.319  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:06.319  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.319  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.319  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.319  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.319  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.319  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.319  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.319  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.319  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:06.320  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.321  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.321  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.321  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.321  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.321  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.321  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.321  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.322  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 06:36:06.322  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:36:06.322  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-14 06:36:06.322  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:36:06.322  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 06:36:06.322  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 06:36:06.322  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.322  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.322  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.322  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.322  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.322  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.322  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
,09-14 06:36:06.322  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.322  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.322  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.323  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.323  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.323  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.323  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.324  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.324  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 06:36:06.324  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.325  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.325  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.325  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.325  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.325  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.326  5496  5542 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:36:06.326  5496  5542 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 06:36:06.326  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-14 06:36:06.330  5496  5542 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-14 06:36:06.330  5496  5542 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-14 06:36:06.330  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 06:36:06.330  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 06:36:06.330  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 06:36:06.330  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 06:36:06.330  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 06:36:06.330  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 06:36:06.331  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 06:36:06.332  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-14 06:36:06.332  5496  5542 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-14 06:36:06.333  5496  5542 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 06:36:06.333  5496  5542 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-14 06:36:06.333  5496  5542 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:36:06.333  5496  5542 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 06:36:06.333  5496  5542 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-14 06:36:06.333  5496  5542 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:36:06.333  5496  5542 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 06:36:06.333  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-14 06:36:06.338  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-14 06:36:06.338  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-14 06:36:06.338  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-14 06:36:06.339  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-14 06:36:06.339  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-14 06:36:06.339  5496  5542 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-14 06:36:06.339  5496  5542 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 06:36:06.340  5496  5542 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-14 06:36:06.340  5496  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-14 06:36:06.341  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.341  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.341  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.341  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.341  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.341  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.341  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-14 06:36:06.342  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
,09-14 06:36:06.342  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.342  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.342  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.342  5496  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-14 06:36:06.342  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:06.342  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.343  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.343  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.344  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.344  5496  5543 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:06.344  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.344  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.345  5496  5542 D BluetoothAdapter: STATE_ON
,09-14 06:36:06.345  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.345  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.345  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.345  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.346  5496  5542 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-14 06:36:06.347  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.347  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:36:06.347  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 06:36:06.347  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.347  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.347  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.348  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.348  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.348  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.343  4488  4488 W Binder_1: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[28645]" dev="sockfs" ino=28645 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:06.348  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.348  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.348  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.348  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.348  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:06.343  4488  4488 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[28645]" dev="sockfs" ino=28645 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:06.351  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.351  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.351  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.351  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.351  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.351  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.351  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.351  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.352  5496  5542 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-14 06:36:06.352  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.352  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.352  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.352  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.352  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.352  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.352  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.352  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:06.353  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.353  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.353  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.353  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.353  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.353  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.354  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.354  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.354  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.354  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.355  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.355  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.355  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:06.355  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.355  5496  5542 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-14 06:36:06.356  5496  5542 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-14 06:36:06.356  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 06:36:06.356  5496  5542 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-14 06:36:06.356  5496  5542 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 06:36:06.356  5496  5542 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-14 06:36:06.356  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 06:36:06.356  5496  5542 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-14 06:36:06.356  5496  5542 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 06:36:06.356  5496  5542 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 06:36:06.356  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 06:36:06.356  5496  5542 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-14 06:36:06.356  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:36:06.356  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.356  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.356  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.357  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.357  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.357  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.357  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.357  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.357  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.357  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:06.357  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.357  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.357  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:06.358  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.358  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.358  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.359  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.359  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.359  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.359  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.359  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.359  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.359  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.360  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.360  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.360  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.360  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.360  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.360  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.360  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.361  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.361  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.361  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.361  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.361  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.361  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.361  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.361  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.361  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.361  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.361  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.361  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.361  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.361  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.362  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.362  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.362  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.362  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.362  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.362  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.363  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.363  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.363  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.363  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.363  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.363  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 06:36:06.363  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.363  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.364  5496  5542 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 06:36:06.365  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:06.365  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-14 06:36:06.366  5496  5542 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 06:36:06.366  5496  5542 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-14 06:36:06.366  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 06:36:06.366  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:36:06.366  5496  5496 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 06:36:06.366  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.366  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 06:36:06.366  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 06:36:06.366  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 06:36:06.367  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:06.367  5496  5542 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 06:36:06.367  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.367  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.367  5496  5496 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 06:36:06.367  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:36:06.367  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:36:06.367  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:36:06.367  5496  5545 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:06.367  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 06:36:06.368  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.368  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.368  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.368  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.368  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:36:06.368  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.368  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.369  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 06:36:06.369  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.369  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.369  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:06.367  4702  4702 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32291]" dev="sockfs" ino=32291 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:06.367  4702  4702 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32291]" dev="sockfs" ino=32291 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:06.369  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.369  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.369  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.369  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 06:36:06.369  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.369  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.369  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.370  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.370  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.370  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.370  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.370  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.370  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:06.370  5496  5545 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 06:36:06.370  5496  5545 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 06:36:06.370  5496  5545 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 06:36:06.372  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:06.372  5496  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:36:06.376  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:36:06.376  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:06.376  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:36:06.376  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.377  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.378  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:06.378  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:06.378  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:06.380  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:06.380  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:06.380  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.382  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:06.382  5496  5496 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 06:36:06.382  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.382  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:06.383  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.383  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.383  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.384  5496  5542 D BluetoothAdapter: STATE_ON
,09-14 06:36:06.384  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.384  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.384  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.384  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.385  5496  5542 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-14 06:36:06.385  5496  5542 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 06:36:06.385  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 06:36:06.385  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 06:36:06.386  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:36:06.386  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.386  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.386  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.386  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.386  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.386  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.386  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.386  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.386  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:36:06.386  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.386  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.386  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.386  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:06.388  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.388  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.388  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.390  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.390  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.390  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.390  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.390  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.394  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.394  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.394  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.394  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.394  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.394  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.394  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.394  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:06.394  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
09-14 06:36:06.394  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.394  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.394  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.394  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.394  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.395  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.395  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.395  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:06.396  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.396  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.396  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.396  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.397  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.398  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:06.398  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:06.398  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:06.398  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:06.398  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.398  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.398  5496  5542 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e123a3 not in the list
09-14 06:36:06.398  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.398  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.398  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:06.398  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.398  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.398  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:06.398  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:06.399  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:06.399  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:06.399  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:06.400  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:06.400  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:06.400  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:06.400  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:06.400  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca06a0 not in the list
,09-14 06:36:06.401  5496  5542 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-14 06:36:06.401  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 06:36:06.402  5496  5542 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-14 06:36:06.402  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 06:36:06.402  5496  5542 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-14 06:36:06.402  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-14 06:36:06.404  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 06:36:06.404  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-14 06:36:06.407  5496  5542 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-14 06:36:06.407  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 06:36:06.407  5496  5542 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-14 06:36:06.407  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 06:36:06.408  5496  5542 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-14 06:36:06.408  5496  5542 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-14 06:36:06.408  5496  5542 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-14 06:36:06.408  5496  5542 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-14 06:36:06.409  5496  5542 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-14 06:36:06.409  5496  5542 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-14 06:36:06.409  5496  5542 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-14 06:36:06.409  5496  5542 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-14 06:36:06.410  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:06.410  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@623d5a6 added. We now have 2 listener(s)
09-14 06:36:06.411  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:36:06.412  5496  5542 D BluetoothAdapter: enable(): BT is already enabled..!
09-14 06:36:06.413   931  3543 D WifiService: setWifiEnabled: true pid=5496, uid=10077
09-14 06:36:06.413   931  3543 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:36:06.414  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:06.414  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cbebbe7 added. We now have 3 listener(s)
09-14 06:36:06.414  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:36:06.421  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:06.421  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6209394 added. We now have 4 listener(s)
09-14 06:36:06.421  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:36:06.423  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:06.423  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14e1e3d added. We now have 5 listener(s)
09-14 06:36:06.423  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:36:06.438   931  3416 D WifiService: setWifiEnabled: false pid=5496, uid=10077
09-14 06:36:06.438   931  3416 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:36:06.441   931  2969 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-14 06:36:06.441   931  2969 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-14 06:36:06.441   931  2969 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 06:36:06.441   931  2969 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 06:36:06.446  4472  4542 D BluetoothAdapterState: Current state: ON, message: 23
09-14 06:36:06.446  4472  4542 D BluetoothAdapterProperties: Setting state to 13
09-14 06:36:06.446  4472  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-14 06:36:06.447  4472  4542 D BluetoothAdapterProperties: onBluetoothDisable()
09-14 06:36:06.448  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:06.449  4472  4542 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:36:06.452   931  2969 E native  : do suspend true
09-14 06:36:06.452  4472  4472 D BluetoothMapService: onReceive
09-14 06:36:06.452  4472  4472 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 06:36:06.452  4472  4472 D BluetoothMapService: STATE_TURNING_OFF
09-14 06:36:06.452  4472  4472 D BluetoothMapService: MAP Service closeService in
09-14 06:36:06.452  4472  4472 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 06:36:06.453  4472  4472 D ObexServerSockets0: shutdown(block = true)
,09-14 06:36:06.453  4472  4472 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-14 06:36:06.453  4472  4721 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,09-14 06:36:06.453  4472  4472 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 06:36:06.453  4472  4722 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 06:36:06.453  4472  4696 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 06:36:06.454  4472  4472 I BtOppRfcommListener: stopping Accept Thread
09-14 06:36:06.454  4472  5109 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 06:36:06.455  4472  5109 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-14 06:36:06.458  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:36:06.458  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 06:36:06.458  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.459  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.459  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 06:36:06.461  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:06.464  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:06.468  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 06:36:06.468  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 06:36:06.469  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:36:06.469  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 06:36:06.471  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.472   931   944 I ActivityManager: Start proc 5548:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-14 06:36:06.472  4472  4546 D BluetoothAdapterProperties: Scan Mode:20
,09-14 06:36:06.473  4472  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-14 06:36:06.475  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.476  4472  4472 D HeadsetService: Received stop request...Stopping profile...
09-14 06:36:06.477   510   930 D CommandListener: Clearing all IP addresses on wlan0
09-14 06:36:06.477   931  5169 D DhcpClient: Clearing IP address
09-14 06:36:06.478  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:06.479  3111  3392 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:06.479   931   931 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:06.479  3111  3111 D HeadsetProfile: Bluetooth service disconnected
09-14 06:36:06.479  3504  3532 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:06.480   931   931 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:06.480  4472  4472 D A2dpService: Received stop request...Stopping profile...
09-14 06:36:06.480   931   931 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:06.480  4472  4713 D A2dpStateMachine: Exit Disconnected: -1
09-14 06:36:06.481   931   931 D BluetoothA2dp: Proxy object disconnected
,09-14 06:36:06.482  3111  3111 D BluetoothA2dp: Proxy object disconnected
,09-14 06:36:06.483  4472  4472 D HidService: Received stop request...Stopping profile...
,09-14 06:36:06.483  4472  4472 D HidService: Stopping Bluetooth HidService
09-14 06:36:06.483   538   538 I ServiceManager: Waiting for service AtCmdFwd...
09-14 06:36:06.484  3111  3111 D BluetoothInputDevice: Proxy object disconnected
09-14 06:36:06.484  3111  3111 D HidProfile: Bluetooth service disconnected
09-14 06:36:06.484  4472  4472 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:06.484  4472  4472 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:06.484  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:06.484  4472  4472 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:36:06.485   510   930 D CommandListener: Setting iface cfg
09-14 06:36:06.485  4472  4472 D HealthService: Received stop request...Stopping profile...
09-14 06:36:06.485  3585  5222 V NativeCrypto: Read error: ssl=0x7f8e254f80: I/O error during system call, Connection timed out
09-14 06:36:06.487  3585  5222 V NativeCrypto: SSL shutdown failed: ssl=0x7f8e254f80: I/O error during system call, Broken pipe
09-14 06:36:06.487  4472  4472 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 06:36:06.487  4472  4472 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 06:36:06.488  4472  4546 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 06:36:06.488  4472  4472 D PanService: Received stop request...Stopping profile...
09-14 06:36:06.488  4472  4668 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:06.488  4472  4668 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:06.488  4472  4668 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:06.489   931  3523 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-14 06:36:06.489  4472  4546 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 06:36:06.489   931  5167 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-14 06:36:06.490  4472  4472 D BluetoothMapService: Received stop request...Stopping profile...
09-14 06:36:06.490  4472  4472 D BluetoothMapService: stop()
09-14 06:36:06.491  3111  3111 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 06:36:06.491  3111  3111 D PanProfile: Bluetooth service disconnected
,09-14 06:36:06.492  4472  4472 D BluetoothMapAppObserver: deinitObservers()
09-14 06:36:06.492  4472  4472 D BluetoothMapAppObserver: removeReceiver()
09-14 06:36:06.493   931  5167 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-14 06:36:06.493   931  2971 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-14 06:36:06.493   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-14 06:36:06.494   931  2971 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-14 06:36:06.494  3111  3111 D BluetoothMap: Proxy object disconnected
09-14 06:36:06.495  3111  3111 D MapProfile: Bluetooth service disconnected
09-14 06:36:06.495  4472  4472 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:06.495  4472  4472 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:06.495  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:06.495  4472  4472 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:06.496  4472  4668 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:06.496  4472  4472 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:06.496  4472  4472 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:06.496   931  2971 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-14 06:36:06.496  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:06.496  4472  4668 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:06.496  4472  4472 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:06.496   931  2971 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-14 06:36:06.496  4472  4546 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-14 06:36:06.496  4472  4668 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:36:06.496  4472  4668 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 06:36:06.496  4472  4668 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:36:06.496  4472  4668 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 06:36:06.497  4472  4472 D SapService: Received stop request...Stopping profile...
09-14 06:36:06.497  4472  4472 V SapService: stop()
09-14 06:36:06.498   536   536 E Parcel  : Reading a NULL string not supported here.
09-14 06:36:06.499  4472  4472 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 06:36:06.499  4472  4472 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 06:36:06.499  4472  4546 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 06:36:06.499  4472  4472 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:06.499  4472  4472 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:06.499  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:36:06.499  4472  4472 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:06.499  4472  4472 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 06:36:06.499  4472  4546 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 06:36:06.500  4472  4472 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-14 06:36:06.500  4472  4472 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:06.500  4472  4472 V BluetoothAdapterState: isTurningOn()=false
,09-14 06:36:06.500  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:06.500  4472  4472 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:06.500  4472  4472 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 06:36:06.500  4472  4472 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-14 06:36:06.502  4472  4472 D BluetoothMapService: MAP Service closeService in
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:36:06.502   931  2971 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-14 06:36:06.502  4472  4472 D BluetoothMapService: cleanup()
09-14 06:36:06.502  4472  4472 D BluetoothMapService: MAP Service closeService in
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:06.502  4472  4472 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:06.503  4472  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 06:36:06.503  4472  4542 D BluetoothAdapterProperties: Setting state to 15
09-14 06:36:06.503  4472  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 06:36:06.503  4472  4542 I BluetoothAdapterState: Entering BleOnState
09-14 06:36:06.504   931   931 D RttService: SCAN_AVAILABLE : 1
,09-14 06:36:06.504   931  3077 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-14 06:36:06.504  3478  3674 W QCNEJ   : |CORE| network lost: 100
09-14 06:36:06.505  3478  3674 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-14 06:36:06.508  3504  3521 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:06.509   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:06.509  3111  3724 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:06.509   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:06.509  3111  3392 D BluetoothPan: onBluetoothStateChange on: false
09-14 06:36:06.510  3111  3124 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 06:36:06.510   931  5170 D DhcpClient: Receive thread stopped
09-14 06:36:06.511  3111  3129 D BluetoothMap: onBluetoothStateChange: up=false
09-14 06:36:06.511  3111  3724 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 06:36:06.512   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 06:36:06.512  3111  3392 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:36:06.512   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:36:06.513  4472  4542 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 06:36:06.513  4472  4542 D BluetoothAdapterProperties: Setting state to 16
09-14 06:36:06.513  4472  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-14 06:36:06.514  4472  4542 D BluetoothAdapterProperties: onBleDisable
,09-14 06:36:06.515  4472  4542 I BluetoothAdapterState: Entering PendingCommandState
09-14 06:36:06.515  4472  4543 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 06:36:06.516  4472  4546 D BluetoothAdapterProperties: Scan Mode:20
,09-14 06:36:06.516  4472  4668 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 06:36:06.516  4472  4668 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:06.517  5496  5543 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-14 06:36:06.517  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:06.517  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:06.519  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:36:06.519  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:06.522  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:06.522  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:06.523  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.523  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:06.525   931  2969 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 06:36:06.526  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.527  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:06.531  5548  5548 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-14 06:36:06.537   510   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 06:36:06.542   931  2969 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 06:36:06.542   931  2969 E native  : do suspend true
,09-14 06:36:06.547  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 06:36:06.552   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c50ce30:true
,09-14 06:36:06.554  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:36:06.567   931  3523 I ActivityManager: Start proc 5566:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-14 06:36:06.572   510   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 06:36:06.573   510   930 D CommandListener: Clearing all IP addresses on wlan0
,09-14 06:36:06.575   931  2971 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-14 06:36:06.575   931  2971 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:36:06.577   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-14 06:36:06.577   931  2969 D DhcpClient: doQuit
,09-14 06:36:06.577   931  2969 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-14 06:36:06.578   931  5169 D DhcpClient: onQuitting
,09-14 06:36:06.578  3607  3607 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-14 06:36:06.582  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:06.582  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:06.583  4882  4897 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-14 06:36:06.583  4882  4897 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 06:36:06.583  4882  4897 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-14 06:36:06.583  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.583  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:06.583  4882  4897 E SarControlService: no key has been found,reset the power
09-14 06:36:06.583  4882  4923 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 06:36:06.583  4882  4923 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-14 06:36:06.584  4882  4923 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 06:36:06.584  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:36:06.584  4911  4911 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-14 06:36:06.585  4882  4923 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-14 06:36:06.585  4882  4923 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 06:36:06.585  4882  4923 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 06:36:06.586  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:06.586  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:06.586  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:06.586  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:06.588  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:36:06.588  4911  4911 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-14 06:36:06.589  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.591  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.592  4911  4925 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2cee3d8 HexData = [00000000ea03000000000000ffffffff]
09-14 06:36:06.595  4911  4925 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:36:06.595  4911  4925 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-14 06:36:06.595  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-14 06:36:06.595  4882  4894 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-14 06:36:06.597  5548  5548 D LocalBluetoothProfileManager: Adding local MAP profile
,09-14 06:36:06.599  4911  4925 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2cee3d8 HexData = [00000000eb03000000000000ffffffff]
,09-14 06:36:06.599  4911  4925 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:36:06.599  4911  4925 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-14 06:36:06.600  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:36:06.600  4882  4895 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-14 06:36:06.602  3607  3607 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-14 06:36:06.604  5548  5548 D BluetoothMap: Create BluetoothMap proxy object
,09-14 06:36:06.607  3607  3607 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-14 06:36:06.619  5566  5566 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
09-14 06:36:06.620  5548  5548 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-14 06:36:06.627  3607  3607 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-14 06:36:06.630  5548  5548 D DockEventReceiver: finishStartingService: stopping service
,09-14 06:36:06.633  3607  3607 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-14 06:36:06.634   510   930 E Netd    : netlink response contains error (No such file or directory)
,09-14 06:36:06.635   931  2971 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-14 06:36:06.635   931  2971 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-14 06:36:06.638   931  2969 D wifi    : In wifi stop Hal
09-14 06:36:06.638   931  2969 D wifi    : halHandle = 0x7f84a65f40, mVM = 0x7f8f54d140, mCls = 0x100ae6
09-14 06:36:06.638   931  3602 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-14 06:36:06.638   931  3602 D WifiHAL : Got a signal to exit!!!
09-14 06:36:06.638   931  3602 I WifiHAL : Exit wifi_event_loop
,09-14 06:36:06.639   931  2969 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-14 06:36:06.639  4295  4295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 06:36:06.639   931  2969 E WifiHAL : Event processing terminated
09-14 06:36:06.639   931  2969 D wifi    : In wifi cleaned up handler
09-14 06:36:06.639   931  2969 I WifiHAL : Internal cleanup completed
09-14 06:36:06.640  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:06.641  3623  4035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:36:06.643  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:06.645   931   942 I ActivityManager: Killing 5209:com.android.chrome/u0a39 (adj 15): empty #17
,09-14 06:36:06.664   931  3602 D wifi    : set interface wlan0 flags (DOWN)
,09-14 06:36:06.664   931  2969 D WifiNative-HAL: HAL event thread stopped successfully
,09-14 06:36:06.723  4472  4546 I bt_hci  : shut_down
,09-14 06:36:06.725   510   930 E Netd    : netlink response contains error (No such file or directory)
,09-14 06:36:06.728  4472  4553 I bt_vendor: low_power_mode_cb
09-14 06:36:06.730  4472  4553 D bt_hwcfg: hw_epilog_process
09-14 06:36:06.732  4472  4553 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 06:36:06.732  4472  4553 I bt_vendor: epilog_cb
09-14 06:36:06.733  4472  4553 I bt_hci  : epilog_finished_callback
09-14 06:36:06.734  4472  4546 I bt_hci_h4: hal_close
,09-14 06:36:06.735  4472  4546 I bt_userial_vendor: device fd = 54 close
,09-14 06:36:06.846  4472  4543 D bt_stack_manager: event_shut_down_stack finished.
,09-14 06:36:06.846  4472  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 06:36:06.848  4472  4542 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-14 06:36:06.848  4472  4472 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 06:36:06.848  4472  4472 D BtGatt.GattService: Received stop request...Stopping profile...
,09-14 06:36:06.848  4472  4472 D BtGatt.GattService: stop()
09-14 06:36:06.848  4472  4472 D BtGatt.AdvertiseManager: advertise clients cleared
09-14 06:36:06.850  4472  4472 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:06.850  4472  4472 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:06.850  4472  4472 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:06.850  4472  4472 V BluetoothAdapterState: isBleTurningOff()=true
09-14 06:36:06.850  4472  4542 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-14 06:36:06.850  4472  4542 D BluetoothAdapterProperties: Setting state to 10
09-14 06:36:06.850  4472  4542 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-14 06:36:06.851  4472  4542 I BluetoothAdapterState: Entering OffState
,09-14 06:36:06.851   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-14 06:36:06.858  4472  4472 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 06:36:06.858  4472  4472 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-14 06:36:06.858  4472  4472 I BluetoothServiceJni: cleanupNative: return from cleanup
09-14 06:36:06.859  4472  4543 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-14 06:36:06.867   931   948 D Tethering: InitialState.processMessage what=4
09-14 06:36:06.869  4472  4543 D bt_stack_manager: event_clean_up_stack finished.
09-14 06:36:06.869   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-14 06:36:06.876  5566  5566 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-14 06:36:06.876  5566  5566 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:36:06.876  5566  5566 D StrictMode: StrictMode policy violation; ~duration=147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:36:06.876  5566  5566 D StrictMode: StrictMode policy violation; ~duration=145 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:36:06.876  5566  5566 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.k.d(PG:583)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.876  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:36:06.877  5566  5566 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:36:06.877  5566  5566 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:36:06.877  5566  5566 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 06:36:06.877  5566  5566 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 06:36:06.882  5496  5496 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-14 06:36:06.884  4472  4472 I art     : System.exit called, status: 0
09-14 06:36:06.884  4472  4472 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-14 06:36:06.905  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 06:36:06.908   931  3738 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
09-14 06:36:06.908   931  3738 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1904)
09-14 06:36:06.909   931  3738 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
09-14 06:36:06.909   931  3738 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-14 06:36:06.909   931  3738 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-14 06:36:06.936   931  3738 I ActivityManager: Start proc 5608:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-14 06:36:06.938   931   942 W ActivityManager: Spurious death for ProcessRecord{d309c6b 5608:com.android.bluetooth/1002}, curProc for 4472: null
09-14 06:36:06.938  5548  5548 D DockEventReceiver: finishStartingService: stopping service
09-14 06:36:06.941   931  3417 I ActivityManager: Killing 5226:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-14 06:36:07.021  5608  5608 D AdapterServiceConfig: Adding HeadsetService
,09-14 06:36:07.022  5608  5608 D AdapterServiceConfig: Adding A2dpService
09-14 06:36:07.022  5608  5608 D AdapterServiceConfig: Adding HidService
09-14 06:36:07.022  5608  5608 D AdapterServiceConfig: Adding HealthService
09-14 06:36:07.022  5608  5608 D AdapterServiceConfig: Adding PanService
09-14 06:36:07.022  5608  5608 D AdapterServiceConfig: Adding GattService
09-14 06:36:07.022  5608  5608 D AdapterServiceConfig: Adding BluetoothMapService
,09-14 06:36:07.022  5608  5608 D AdapterServiceConfig: Adding SapService
09-14 06:36:07.025   931   941 I ActivityManager: Killing 5282:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-14 06:36:07.053  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:36:07.069  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-14 06:36:07.075  3900  5193 I iu.UploadsManager: num queued entries: 0
,09-14 06:36:07.075  3900  5193 I iu.UploadsManager: num updated entries: 0
09-14 06:36:07.076  3900  5193 I iu.SyncManager: NEXT; no task
,09-14 06:36:07.077  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 06:36:07.079  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 06:36:07.091   931  3149 I ActivityManager: Start proc 5621:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-14 06:36:07.125  5621  5621 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-14 06:36:07.135  5621  5621 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:36:07.141  5621  5621 D SprintDMHelper: simOperator: 
,09-14 06:36:07.141  5621  5621 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 06:36:07.153   931   941 I ActivityManager: Start proc 5633:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-14 06:36:07.154   931   941 I ActivityManager: Killing 3418:android.process.acore/u0a2 (adj 15): empty #17
,09-14 06:36:07.221  5566  5590 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-14 06:36:07.246  4295  5647 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-14 06:36:07.255   931  3738 I ActivityManager: Start proc 5649:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-14 06:36:07.258   931  3151 I ActivityManager: Killing 5302:com.google.android.partnersetup/u0a18 (adj 15): empty #17
,09-14 06:36:07.271   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@75efe78:true
,09-14 06:36:07.312  5649  5649 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-14 06:36:07.479   931   942 I ActivityManager: Killing 5319:com.android.musicfx/u0a21 (adj 15): empty #17
,09-14 06:36:07.484   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:36:07.511   931  3551 I ActivityManager: Start proc 5662:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-14 06:36:07.541  5662  5662 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-14 06:36:07.548   931  3551 I ActivityManager: Killing 5124:com.google.android.gms.wearable/u0a12 (adj 15): empty #17
,09-14 06:36:09.461   931  3151 D WifiService: setWifiEnabled: true pid=5496, uid=10077
,09-14 06:36:09.462   931  3151 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:36:09.470   510   930 D SoftapController: Softap fwReload - Ok
,09-14 06:36:09.474   510   930 D CommandListener: Setting iface cfg
09-14 06:36:09.475   510   930 D CommandListener: Trying to bring down wlan0
09-14 06:36:09.476   510   930 D CommandListener: Clearing all IP addresses on wlan0
09-14 06:36:09.481   931  2969 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-14 06:36:10.092   931  2969 D wifi    : set interface wlan0 flags (UP)
,09-14 06:36:10.097   931  2969 I WifiHAL : Initializing wifi
09-14 06:36:10.098   931  2969 I WifiHAL : Creating socket
,09-14 06:36:10.103   931  2969 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-14 06:36:10.104   931  2969 D wifi    : Did set static halHandle = 0x7f84a65f40
09-14 06:36:10.104   931  2969 D wifi    : halHandle = 0x7f84a65f40, mVM = 0x7f8f54d140, mCls = 0x152e
,09-14 06:36:10.104   931  2969 D wifi    : array field set
,09-14 06:36:10.104   931  2969 I WifiNative-HAL: interface[0] = wlan0
09-14 06:36:10.105   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-14 06:36:10.111   931  5681 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547686342464
,09-14 06:36:10.111   931  5681 D wifi    : waitForHalEvents called, vm = 0x7f8f54d140, obj = 0x152e, env = 0x7f704ba400
,09-14 06:36:10.178  5682  5682 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-14 06:36:10.192  5682  5682 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:36:10.194   510   930 E FrameworkListener: read() failed (Connection reset by peer)
,09-14 06:36:10.208   931  2969 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-14 06:36:10.211  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:10.212  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:10.239  5682  5682 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:36:10.239  5682  5682 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-14 06:36:10.255   931  2969 D WifiConfigStore: Loading config and enabling all networks 
,09-14 06:36:10.255  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:10.255  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:10.255  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:10.255  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:10.256  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:10.257  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:10.257  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:36:10.257  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:10.260   931  2969 D WifiConfigStore: loaded 0 passpoint configs
,09-14 06:36:10.261   931  2969 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 06:36:10.261   931  2969 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-14 06:36:10.262   931  2969 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-14 06:36:10.262   931  2969 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
09-14 06:36:10.262   931  2969 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 06:36:10.265   931  2969 D WifiNative-HAL: Setting external_sim to 1
,09-14 06:36:10.266  4295  4295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:36:10.266   931  2969 D wifi    : setting dfs flag to true, 0x7f76437a60
09-14 06:36:10.267   931  2969 D WifiStateMachine: Setting OUI to DA-A1-19
,09-14 06:36:10.267   931  2969 D wifi    : setting scan oui 0x7f76437a60
09-14 06:36:10.267   931  2969 D WifiHAL : Sending mac address OUI
,09-14 06:36:10.281   931  2969 E native  : do suspend true
,09-14 06:36:10.286   931  2969 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-14 06:36:10.286   510   930 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-14 06:36:10.287   931   931 D RttService: SCAN_AVAILABLE : 3
09-14 06:36:10.287   931  3077 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 06:36:10.288   510   930 D CommandListener: Setting iface cfg
,09-14 06:36:10.292   931  2968 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-14 06:36:10.292   931  2968 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 06:36:10.303   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=237143 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,09-14 06:36:10.304   931  2968 D WifiNative-HAL: p2pGetDeviceAddress
,09-14 06:36:10.304   931  2968 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-14 06:36:12.467   931  3416 D WifiService: setWifiEnabled: false pid=5496, uid=10077
,09-14 06:36:12.467   931  3416 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:36:12.480   931   931 D RttService: SCAN_AVAILABLE : 1
,09-14 06:36:12.481   931  3077 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-14 06:36:12.485   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:12.494   931  2969 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 06:36:12.495   510   930 D CommandListener: Clearing all IP addresses on wlan0
,09-14 06:36:12.498   931  2969 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-14 06:36:12.500  5682  5682 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-14 06:36:12.507  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:12.507  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:12.507  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:12.507  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:12.509  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:12.510  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:12.510  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:12.510  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:12.522  5682  5682 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-14 06:36:12.532  5682  5682 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-14 06:36:12.537  5682  5682 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-14 06:36:12.645  4295  4295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:36:12.647   931  2969 D wifi    : In wifi stop Hal
,09-14 06:36:12.648   931  2969 D wifi    : halHandle = 0x7f84a65f40, mVM = 0x7f8f54d140, mCls = 0x152e
,09-14 06:36:12.648   931  5681 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-14 06:36:12.649   931  5681 D WifiHAL : Got a signal to exit!!!
09-14 06:36:12.649   931  5681 I WifiHAL : Exit wifi_event_loop
09-14 06:36:12.650   931  2969 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-14 06:36:12.651   931  2969 E WifiHAL : Event processing terminated
09-14 06:36:12.655  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:12.656   931  2969 D wifi    : In wifi cleaned up handler
09-14 06:36:12.658  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:12.659   931  2969 I WifiHAL : Internal cleanup completed
09-14 06:36:12.661  3623  4035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:36:12.687   931  5681 D wifi    : set interface wlan0 flags (DOWN)
,09-14 06:36:12.688   931  2969 D WifiNative-HAL: HAL event thread stopped successfully
,09-14 06:36:12.766   510   930 E Netd    : netlink response contains error (No such file or directory)
,09-14 06:36:12.893   931   948 D Tethering: InitialState.processMessage what=4
,09-14 06:36:12.899   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-14 06:36:13.486   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:14.487   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:15.488   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:15.515   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4c65ffd:true
,09-14 06:36:15.516  5608  5608 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 06:36:15.520  5608  5608 I bt_bluedroid: init
,09-14 06:36:15.521  5608  5703 I BluetoothAdapterState: Entering OffState
,09-14 06:36:15.524  5608  5704 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-14 06:36:15.524  5608  5704 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 06:36:15.524  5608  5704 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 06:36:15.524  5608  5704 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-14 06:36:15.525  5608  5608 I bt_bluedroid: get_profile_interface socket
,09-14 06:36:15.528  5608  5608 I bt_bluedroid: get_profile_interface sdp
,09-14 06:36:15.528  5608  5707 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-14 06:36:15.530  5608  5707 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 06:36:15.536  5608  5618 I bt_bluedroid: config_hci_snoop_log
,09-14 06:36:15.538   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 06:36:15.545  5608  5703 D BluetoothAdapterState: Current state: OFF, message: 0
09-14 06:36:15.545  5608  5703 D BluetoothAdapterProperties: Setting state to 14
09-14 06:36:15.545  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-14 06:36:15.547  5608  5703 D BluetoothBondStateMachine: make
,09-14 06:36:15.549  5608  5708 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 06:36:15.551  5608  5703 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:36:15.552  5608  5608 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 06:36:15.555  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:15.555  5608  5608 D BtGatt.DebugUtils: handleDebugAction() action=null
09-14 06:36:15.556  5608  5608 D BtGatt.GattService: Received start request. Starting profile...
09-14 06:36:15.556  5608  5608 D BtGatt.GattService: start()
09-14 06:36:15.556  5608  5608 I bt_bluedroid: get_profile_interface gatt
,09-14 06:36:15.557  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:15.557  5608  5608 D BtGatt.AdvertiseManager: advertise manager created
,09-14 06:36:15.563  5608  5608 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:36:15.563  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:15.563  5608  5608 V BluetoothAdapterState: isBleTurningOn()=true
09-14 06:36:15.563  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:15.563  5608  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-14 06:36:15.565  5608  5703 I bt_bluedroid: bt_bluedroid
09-14 06:36:15.565  5608  5704 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-14 06:36:15.565  5608  5704 I bt_hci  : start_up
,09-14 06:36:15.571  5608  5704 I bt_vendor: alloc value 0xf3b38871
09-14 06:36:15.571  5608  5704 I bt_vendor: init
09-14 06:36:15.571  5608  5704 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 06:36:15.571  5608  5704 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 06:36:15.680  5608  5704 D bt_hci  : start_up starting async portion
,09-14 06:36:15.681  5608  5711 I bt_hci  : event_finish_startup
,09-14 06:36:15.681  5608  5711 I bt_hci_h4: hal_open
09-14 06:36:15.681  5608  5711 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-14 06:36:15.680  5712  5712 W irq/448-msm_hs_: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-14 06:36:15.684  5608  5711 I bt_userial_vendor: device fd = 54 open
,09-14 06:36:15.699  5608  5711 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 06:36:15.701  5608  5711 D bt_hwcfg: Chipset BCM4358A3
,09-14 06:36:15.702  5608  5711 D bt_hwcfg: Target name = [BCM4358A3]
09-14 06:36:15.702  5608  5711 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-14 06:36:16.111  5608  5711 I bt_hwcfg: bt vendor lib: set UART baud 115200
09-14 06:36:16.111  5608  5711 D bt_hwcfg: Settlement delay -- 100 ms
,09-14 06:36:16.111  5608  5711 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 06:36:16.244  5608  5711 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 06:36:16.245  5608  5711 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-14 06:36:16.246  5608  5711 I bt_hwcfg: vendor lib fwcfg completed
,09-14 06:36:16.247  5608  5711 I bt_vendor: firmware callback
09-14 06:36:16.247  5608  5711 I bt_hci  : firmware_config_callback
09-14 06:36:16.256   931   931 E WifiNative-wlan0: set PNO failure
,09-14 06:36:16.260  5608  5714 I bt_btu  : btu_task pending for preload complete event
,09-14 06:36:16.260  5608  5714 I bt_btu_task: Bluetooth chip preload is complete
09-14 06:36:16.260  5608  5714 I bt_btu  : btu_task received preload complete event
,09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_A2D
09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_BNEP
09-14 06:36:16.266  5608  5714 I         : BTE_InitTraceLevels -- TRC_BTM
,09-14 06:36:16.267  5608  5714 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 06:36:16.267  5608  5714 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 06:36:16.267  5608  5714 I         : BTE_InitTraceLevels -- TRC_SDP
,09-14 06:36:16.267  5608  5714 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 06:36:16.267  5608  5714 I         : BTE_InitTraceLevels -- TRC_SMP
,09-14 06:36:16.267  5608  5714 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 06:36:16.267  5608  5714 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 06:36:16.350  5608  5714 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ab6549
09-14 06:36:16.350  5608  5714 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ab6549 
,09-14 06:36:16.370  5608  5707 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 06:36:16.371  5608  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 06:36:16.372  5608  5707 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-14 06:36:16.375  5608  5707 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 06:36:16.378  5608  5707 D BluetoothAdapterProperties: Scan Mode:20
09-14 06:36:16.379  5608  5707 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 06:36:16.379  5608  5707 D bt_hci  : do_postload posting postload work item
09-14 06:36:16.379  5608  5711 I bt_hci  : event_postload
09-14 06:36:16.379  5608  5711 I bt_vendor: sco_config_cb
09-14 06:36:16.379  5608  5711 I bt_hci  : sco_config_callback postload finished.
,09-14 06:36:16.383  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:16.386  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:16.386  5608  5711 I bt_vendor: low_power_mode_cb
,09-14 06:36:16.390  5608  5707 D bt_bte_conf: Device ID record 1 : primary
,09-14 06:36:16.390  5608  5707 D bt_bte_conf:   vendorId            = 000f
09-14 06:36:16.391  5608  5707 D bt_bte_conf:   vendorIdSource      = 0001
09-14 06:36:16.391  5608  5707 D bt_bte_conf:   product             = 1200
09-14 06:36:16.391  5608  5707 D bt_bte_conf:   version             = 1436
,09-14 06:36:16.391  5608  5707 D bt_bte_conf:   clientExecutableURL = 
09-14 06:36:16.391  5608  5707 D bt_bte_conf:   serviceDescription  = 
09-14 06:36:16.391  5608  5707 D bt_bte_conf:   documentationURL    = 
,09-14 06:36:16.392  5608  5707 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 06:36:16.392  5608  5704 D bt_stack_manager: event_start_up_stack finished
,09-14 06:36:16.393  5608  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-14 06:36:16.394  5608  5703 D BluetoothAdapterProperties: Setting state to 15
09-14 06:36:16.394  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-14 06:36:16.395  5608  5703 I BluetoothAdapterState: Entering BleOnState
,09-14 06:36:16.398  5608  5703 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 06:36:16.398  5608  5703 D BluetoothAdapterProperties: Setting state to 11
09-14 06:36:16.398  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-14 06:36:16.404  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:16.407  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:16.408  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:16.410  5608  5608 D HeadsetService: Received start request. Starting profile...
,09-14 06:36:16.413  5608  5608 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-14 06:36:16.413  5608  5608 D HeadsetStateMachine: make
,09-14 06:36:16.418  5608  5703 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:36:16.423  5608  5608 D HeadsetStateMachine: max_hf_connections = 1
,09-14 06:36:16.423  5608  5608 I bt_bluedroid: get_profile_interface handsfree
09-14 06:36:16.423  5608  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 06:36:16.424  5608  5707 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-14 06:36:16.428  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:36:16.428  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:16.429  5608  5608 D A2dpService: Received start request. Starting profile...
09-14 06:36:16.430  5608  5608 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-14 06:36:16.430  5608  5608 I bt_bluedroid: get_profile_interface avrcp
,09-14 06:36:16.436  5608  5608 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 06:36:16.436  5608  5608 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 06:36:16.436  5608  5608 D A2dpStateMachine: make
09-14 06:36:16.437  5608  5608 I bt_bluedroid: get_profile_interface a2dp
,09-14 06:36:16.438  5608  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 06:36:16.439  5608  5723 D A2dpStateMachine: Enter Disconnected: -2
,09-14 06:36:16.440  5608  5608 I BluetoothHidServiceJni: classInitNative: succeeds
,09-14 06:36:16.441  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:16.442  5608  5608 D HidService: Received start request. Starting profile...
09-14 06:36:16.442  5548  5548 D BluetoothInputDevice: Proxy object connected
09-14 06:36:16.442  5608  5608 I bt_bluedroid: get_profile_interface hidhost
09-14 06:36:16.442  5608  5707 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3a9756d
09-14 06:36:16.442  5608  5608 D HidService: setHidService(): set to: null
09-14 06:36:16.442  5608  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-14 06:36:16.443  5548  5548 D HidProfile: Bluetooth service connected
09-14 06:36:16.443  5608  5608 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 06:36:16.444  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
09-14 06:36:16.444  5608  5608 D HealthService: Received start request. Starting profile...
,09-14 06:36:16.446  5608  5608 I bt_bluedroid: get_profile_interface health
09-14 06:36:16.446  5608  5608 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-14 06:36:16.447  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:16.448  5548  5548 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 06:36:16.449  5548  5548 D PanProfile: Bluetooth service connected
09-14 06:36:16.450  5608  5608 D PanService: Received start request. Starting profile...
09-14 06:36:16.450  5608  5608 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 06:36:16.450  5608  5608 I bt_bluedroid: get_profile_interface pan
09-14 06:36:16.451  5608  5707 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 06:36:16.452  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
09-14 06:36:16.454  5548  5548 D BluetoothMap: Proxy object connected
,09-14 06:36:16.454  5608  5608 D BluetoothMapService: Received start request. Starting profile...
09-14 06:36:16.454  5608  5608 D BluetoothMapService: start()
09-14 06:36:16.454  5548  5548 D MapProfile: Bluetooth service connected
09-14 06:36:16.454  5548  5548 D BluetoothMap: getConnectedDevices()
09-14 06:36:16.455  5548  5548 D BluetoothMap: Bluetooth is Not enabled
,09-14 06:36:16.457  5608  5608 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-14 06:36:16.458  5608  5608 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 06:36:16.458  5608  5608 D BluetoothMapAppObserver: createReceiver()
09-14 06:36:16.459  5608  5608 D BluetoothMapAppObserver: initObservers()
09-14 06:36:16.459  5608  5608 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 06:36:16.466  5608  5608 V SapService: SapBinder()
,09-14 06:36:16.466  5608  5608 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
09-14 06:36:16.466  5608  5608 D SapService: Received start request. Starting profile...
09-14 06:36:16.467  5608  5608 V SapService: start()
,09-14 06:36:16.470  5608  5608 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:36:16.470  5608  5608 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:16.470  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:16.471  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:16.472  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:16.473  5608  5608 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:16.473  5608  5608 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:16.473  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:16.473  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:36:16.473  5608  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 06:36:16.473  5608  5703 D BluetoothAdapterProperties: ScanMode =  20
09-14 06:36:16.473  5608  5703 D BluetoothAdapterProperties: State =  11
09-14 06:36:16.474  5608  5703 D BluetoothAdapterProperties: Setting state to 12
09-14 06:36:16.474  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 06:36:16.474  5608  5703 I BluetoothAdapterState: Entering OnState
09-14 06:36:16.474  3504  3788 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:16.475  5548  5560 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 06:36:16.476   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:16.477  3111  3724 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:16.477   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:16.478  5608  5707 D BluetoothAdapterProperties: Scan Mode:21
09-14 06:36:16.478  3111  3129 D BluetoothPan: onBluetoothStateChange on: true
09-14 06:36:16.478  5608  5707 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 06:36:16.480  5548  5558 D BluetoothPan: onBluetoothStateChange on: true
09-14 06:36:16.480  3111  3111 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 06:36:16.480  3111  3111 D PanProfile: Bluetooth service connected
09-14 06:36:16.480  3111  3124 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:16.482  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:16.482  3111  3724 D BluetoothMap: onBluetoothStateChange: up=true
09-14 06:36:16.484  3111  3111 D BluetoothMap: Proxy object connected
09-14 06:36:16.484  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:16.484  3111  3111 D MapProfile: Bluetooth service connected
09-14 06:36:16.484  3111  3111 D BluetoothMap: getConnectedDevices()
09-14 06:36:16.484  3111  3124 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 06:36:16.485  5608  5608 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 06:36:16.486  5608  5608 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:16.487  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:16.488  5608  5608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:16.488  3111  3111 D BluetoothInputDevice: Proxy object connected
09-14 06:36:16.488   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:16.488  3111  3111 D HidProfile: Bluetooth service connected
09-14 06:36:16.489  3111  3129 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:36:16.489   538   538 I ServiceManager: Waiting for service AtCmdFwd...
09-14 06:36:16.490  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:16.490  5608  5608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:16.491   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:36:16.491  5548  5561 D BluetoothMap: onBluetoothStateChange: up=true
09-14 06:36:16.492  5548  5560 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:36:16.492  5608  5608 D ObexServerSockets: Succeed to create listening sockets 
09-14 06:36:16.492  5608  5608 D ObexServerSockets0: startAccept()
09-14 06:36:16.492  5608  5608 D ObexServerSockets0: prepareForNewConnect()
09-14 06:36:16.494   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
09-14 06:36:16.494  5608  5608 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 06:36:16.494  5608  5608 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 06:36:16.496  5608  5729 D ObexServerSockets0: Accepting socket connection...
09-14 06:36:16.496  5548  5548 D LocalBluetoothProfileManager: Adding local A2DP profile
09-14 06:36:16.496  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:16.497   931   931 D BluetoothA2dp: Proxy object connected
09-14 06:36:16.497  5608  5728 D ObexServerSockets0: Accepting socket connection...
09-14 06:36:16.497  5608  5608 D BluetoothMapService: onReceive
09-14 06:36:16.497  5608  5608 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 06:36:16.498  5608  5608 D BluetoothMapService: STATE_ON
09-14 06:36:16.498  3111  3111 D BluetoothA2dp: Proxy object connected
09-14 06:36:16.499  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:16.501  5548  5548 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-14 06:36:16.503  5608  5731 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:16.505  5608  5731 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-14 06:36:16.505  5608  5731 D BluetoothSdpJni: SDP Create record success - handle: 1
09-14 06:36:16.510  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 06:36:16.512  5548  5548 D BluetoothA2dp: Proxy object connected
,09-14 06:36:16.516  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 06:36:16.519  5548  5548 D DockEventReceiver: finishStartingService: stopping service
09-14 06:36:16.522  5608  5608 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 06:36:16.523  5608  5608 D ObexServerSockets0: prepareForNewConnect()
09-14 06:36:16.523  5548  5548 D BluetoothPbap: Proxy object connected
09-14 06:36:16.523  5548  5548 D PbapServerProfile: Bluetooth service connected
09-14 06:36:16.524  3111  3111 D BluetoothPbap: Proxy object connected
09-14 06:36:16.524  3111  3111 D PbapServerProfile: Bluetooth service connected
09-14 06:36:16.530  5608  5735 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:16.542  5608  5739 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:16.544  5608  5739 I BtOppRfcommListener: Accept thread started.
,09-14 06:36:16.576  3111  3724 D BluetoothHeadset: Proxy object connected
,09-14 06:36:16.576  3111  3111 D HeadsetProfile: Bluetooth service connected
09-14 06:36:16.576   931   931 D BluetoothHeadset: Proxy object connected
09-14 06:36:16.576  3504  3786 D BluetoothHeadset: Proxy object connected
09-14 06:36:16.577   931   931 D BluetoothHeadset: Proxy object connected
09-14 06:36:16.577   931   931 D BluetoothHeadset: Proxy object connected
09-14 06:36:16.577   931   948 D BluetoothHeadset: Proxy object connected
09-14 06:36:16.577  3111  3124 D BluetoothHeadset: Proxy object connected
09-14 06:36:16.577   931   948 D BluetoothHeadset: Proxy object connected
,09-14 06:36:16.578  3111  3111 D HeadsetProfile: Bluetooth service connected
,09-14 06:36:16.589   931   948 D BluetoothHeadset: Proxy object connected
,09-14 06:36:16.607  5548  5560 D BluetoothHeadset: Proxy object connected
,09-14 06:36:16.608  5548  5548 D HeadsetProfile: Bluetooth service connected
,09-14 06:36:17.489   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:36:18.489  5608  5703 D BluetoothAdapterState: Current state: ON, message: 23
,09-14 06:36:18.489  5608  5703 D BluetoothAdapterProperties: Setting state to 13
,09-14 06:36:18.489  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-14 06:36:18.491  5608  5703 D BluetoothAdapterProperties: onBluetoothDisable()
09-14 06:36:18.492  5608  5703 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:36:18.498  5608  5608 D BluetoothMapService: onReceive
,09-14 06:36:18.498  5608  5608 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 06:36:18.498  5608  5608 D BluetoothMapService: STATE_TURNING_OFF
09-14 06:36:18.499  5608  5608 D BluetoothMapService: MAP Service closeService in
09-14 06:36:18.499  5608  5608 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 06:36:18.499  5608  5608 D ObexServerSockets0: shutdown(block = true)
09-14 06:36:18.502  5608  5728 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-14 06:36:18.504  5608  5707 D BluetoothAdapterProperties: Scan Mode:20
09-14 06:36:18.506  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:18.506  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:18.506  5608  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-14 06:36:18.506  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 06:36:18.507  5608  5608 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 06:36:18.507  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:18.508  5608  5608 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 06:36:18.508  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:18.509  5608  5716 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 06:36:18.509  5608  5729 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 06:36:18.510  5608  5608 I BtOppRfcommListener: stopping Accept Thread
09-14 06:36:18.511  5608  5739 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 06:36:18.511  5608  5739 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-14 06:36:18.512  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:18.513  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:18.514  5496  5496 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 06:36:18.514  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:18.520  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:18.521  5608  5608 D HeadsetService: Received stop request...Stopping profile...
09-14 06:36:18.523  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:18.526  3111  3124 D BluetoothHeadset: Proxy object disconnected
,09-14 06:36:18.526   931   931 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:18.527  3504  3521 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:18.528  5608  5608 D A2dpService: Received stop request...Stopping profile...
09-14 06:36:18.528  5548  5561 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:18.529  5608  5723 D A2dpStateMachine: Exit Disconnected: -1
09-14 06:36:18.529   931   931 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:18.529   931   931 D BluetoothHeadset: Proxy object disconnected
09-14 06:36:18.529  5548  5548 D DockEventReceiver: finishStartingService: stopping service
09-14 06:36:18.530   931   931 D BluetoothA2dp: Proxy object disconnected
,09-14 06:36:18.531  5548  5548 D HeadsetProfile: Bluetooth service disconnected
,09-14 06:36:18.531  5548  5548 D BluetoothA2dp: Proxy object disconnected
09-14 06:36:18.534  5608  5608 D HidService: Received stop request...Stopping profile...
09-14 06:36:18.534  5608  5608 D HidService: Stopping Bluetooth HidService
09-14 06:36:18.534  3111  3111 D HeadsetProfile: Bluetooth service disconnected
09-14 06:36:18.534  3111  3111 D BluetoothA2dp: Proxy object disconnected
09-14 06:36:18.535  3111  3111 D BluetoothInputDevice: Proxy object disconnected
,09-14 06:36:18.535  3111  3111 D HidProfile: Bluetooth service disconnected
09-14 06:36:18.535  5548  5548 D BluetoothInputDevice: Proxy object disconnected
09-14 06:36:18.535  5548  5548 D HidProfile: Bluetooth service disconnected
09-14 06:36:18.536  5608  5608 D HealthService: Received stop request...Stopping profile...
09-14 06:36:18.538  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:36:18.538  5608  5608 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:18.538  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.538  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:18.539  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:18.540  5608  5608 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-14 06:36:18.541  5608  5608 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 06:36:18.541  5608  5714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:18.541  5608  5714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:18.541  5608  5714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:18.541  5608  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 06:36:18.541  5608  5707 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 06:36:18.541  5608  5608 D PanService: Received stop request...Stopping profile...
09-14 06:36:18.542  3111  3111 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 06:36:18.542  3111  3111 D PanProfile: Bluetooth service disconnected
09-14 06:36:18.543  5608  5608 D BluetoothMapService: Received stop request...Stopping profile...
09-14 06:36:18.543  5608  5608 D BluetoothMapService: stop()
09-14 06:36:18.543  5608  5608 D BluetoothMapAppObserver: deinitObservers()
09-14 06:36:18.544  5608  5608 D BluetoothMapAppObserver: removeReceiver()
09-14 06:36:18.543  5548  5548 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 06:36:18.544  5548  5548 D PanProfile: Bluetooth service disconnected
09-14 06:36:18.545  5548  5548 D BluetoothMap: Proxy object disconnected
09-14 06:36:18.545  5548  5548 D MapProfile: Bluetooth service disconnected
09-14 06:36:18.545  3111  3111 D BluetoothMap: Proxy object disconnected
09-14 06:36:18.545  3111  3111 D MapProfile: Bluetooth service disconnected
09-14 06:36:18.546  5608  5608 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:18.546  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.546  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:18.546  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:18.547  5608  5714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:18.548  5608  5714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:18.548  5608  5608 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:18.548  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.548  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:18.548  5608  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-14 06:36:18.548  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:18.548  5608  5714 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:36:18.548  5608  5714 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 06:36:18.548  5608  5714 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 06:36:18.548  5608  5714 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 06:36:18.548  5608  5608 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-14 06:36:18.548  5608  5608 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 06:36:18.549  5608  5608 D SapService: Received stop request...Stopping profile...
09-14 06:36:18.549  5608  5608 V SapService: stop()
09-14 06:36:18.550  5608  5707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 06:36:18.551  3111  3111 D BluetoothPbap: Proxy object disconnected
09-14 06:36:18.551  3111  3111 D PbapServerProfile: Bluetooth service disconnected
,09-14 06:36:18.552  5608  5608 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:18.552  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.552  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:18.552  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:18.553  5608  5608 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 06:36:18.553  5608  5707 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 06:36:18.553  5608  5608 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 06:36:18.553  5608  5608 V BluetoothAdapterState: isTurningOff()=true
,09-14 06:36:18.553  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.553  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:18.553  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:18.553  5548  5548 D BluetoothPbap: Proxy object disconnected
09-14 06:36:18.553  5548  5548 D PbapServerProfile: Bluetooth service disconnected
09-14 06:36:18.554  5608  5608 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 06:36:18.554  5608  5608 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-14 06:36:18.555  5608  5608 D BluetoothMapService: MAP Service closeService in
,09-14 06:36:18.555  5608  5608 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:18.555  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.555  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:18.555  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:18.555  5608  5608 D BluetoothMapService: cleanup()
09-14 06:36:18.555  5608  5608 D BluetoothMapService: MAP Service closeService in
09-14 06:36:18.556  5608  5608 V BluetoothAdapterState: isTurningOff()=true
09-14 06:36:18.556  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.556  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:18.556  5608  5608 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:18.556  5608  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 06:36:18.556  5608  5703 D BluetoothAdapterProperties: Setting state to 15
09-14 06:36:18.556  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-14 06:36:18.557  3504  3532 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:18.557  5608  5703 I BluetoothAdapterState: Entering BleOnState
,09-14 06:36:18.557  5548  5561 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-14 06:36:18.567   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 06:36:18.568  3111  3724 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:18.568   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:18.568  3111  3124 D BluetoothPan: onBluetoothStateChange on: false
09-14 06:36:18.569  5548  5558 D BluetoothPan: onBluetoothStateChange on: false
09-14 06:36:18.569  3111  3392 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 06:36:18.570  3111  3129 D BluetoothMap: onBluetoothStateChange: up=false
09-14 06:36:18.570  3111  3724 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 06:36:18.570   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:18.571  5548  5560 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:36:18.571  3111  3124 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 06:36:18.571  5548  5561 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 06:36:18.572   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-14 06:36:18.572  5548  5558 D BluetoothMap: onBluetoothStateChange: up=false
09-14 06:36:18.572  5548  5560 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 06:36:18.573  5608  5703 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 06:36:18.573  5608  5703 D BluetoothAdapterProperties: Setting state to 16
09-14 06:36:18.573  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-14 06:36:18.573  5608  5703 D BluetoothAdapterProperties: onBleDisable
09-14 06:36:18.574  5608  5703 I BluetoothAdapterState: Entering PendingCommandState
09-14 06:36:18.574  5608  5704 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 06:36:18.575  5608  5707 D BluetoothAdapterProperties: Scan Mode:20
09-14 06:36:18.576  5608  5714 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 06:36:18.576  5608  5714 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 06:36:18.577  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 06:36:18.579  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:18.582  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:18.583  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:18.584  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:18.585  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:36:18.589  5548  5548 D DockEventReceiver: finishStartingService: stopping service
,09-14 06:36:18.786  5608  5707 I bt_hci  : shut_down
,09-14 06:36:18.796  5608  5711 D bt_hwcfg: hw_epilog_process
,09-14 06:36:18.796  5608  5711 I bt_vendor: low_power_mode_cb
,09-14 06:36:18.799  5608  5711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-14 06:36:18.799  5608  5711 I bt_vendor: epilog_cb
09-14 06:36:18.799  5608  5711 I bt_hci  : epilog_finished_callback
,09-14 06:36:18.803  5608  5707 I bt_hci_h4: hal_close
,09-14 06:36:18.805  5608  5707 I bt_userial_vendor: device fd = 54 close
,09-14 06:36:18.928  5608  5704 D bt_stack_manager: event_shut_down_stack finished.
,09-14 06:36:18.929  5608  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 06:36:18.933  5608  5703 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-14 06:36:18.934  5608  5608 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 06:36:18.935  5608  5608 D BtGatt.GattService: Received stop request...Stopping profile...
,09-14 06:36:18.935  5608  5608 D BtGatt.GattService: stop()
09-14 06:36:18.935  5608  5608 D BtGatt.AdvertiseManager: advertise clients cleared
09-14 06:36:18.939  5608  5608 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:18.939  5608  5608 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:18.939  5608  5608 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:36:18.939  5608  5608 V BluetoothAdapterState: isBleTurningOff()=true
,09-14 06:36:18.940  5608  5703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-14 06:36:18.940  5608  5703 D BluetoothAdapterProperties: Setting state to 10
09-14 06:36:18.940  5608  5703 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-14 06:36:18.942  5608  5703 I BluetoothAdapterState: Entering OffState
09-14 06:36:18.943   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-14 06:36:18.958  5608  5608 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 06:36:18.958  5608  5608 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-14 06:36:18.958  5608  5608 I BluetoothServiceJni: cleanupNative: return from cleanup
09-14 06:36:18.960  5608  5704 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 06:36:18.968  5608  5608 I art     : System.exit called, status: 0
09-14 06:36:18.968  5608  5608 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 06:36:19.000   931  3523 I ActivityManager: Process com.android.bluetooth (pid 5608) has died
,09-14 06:36:21.487  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 06:36:21.488  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:24.494  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:24.495  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7b12f83 added. We now have 6 listener(s)
,09-14 06:36:24.495  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:36:24.502  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 06:36:24.502  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@53d5500 added. We now have 7 listener(s)
,09-14 06:36:24.502  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:24.504  5496  5542 I System.out: IsBluetoothEnabled
,09-14 06:36:24.511  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:24.538   931   948 I ActivityManager: Start proc 5748:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-14 06:36:24.613  5748  5748 D AdapterServiceConfig: Adding HeadsetService
,09-14 06:36:24.613  5748  5748 D AdapterServiceConfig: Adding A2dpService
09-14 06:36:24.613  5748  5748 D AdapterServiceConfig: Adding HidService
,09-14 06:36:24.614  5748  5748 D AdapterServiceConfig: Adding HealthService
09-14 06:36:24.614  5748  5748 D AdapterServiceConfig: Adding PanService
09-14 06:36:24.614  5748  5748 D AdapterServiceConfig: Adding GattService
09-14 06:36:24.614  5748  5748 D AdapterServiceConfig: Adding BluetoothMapService
09-14 06:36:24.614  5748  5748 D AdapterServiceConfig: Adding SapService
,09-14 06:36:24.625   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@95ad1bd:true
,09-14 06:36:24.625  5748  5748 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 06:36:24.628  5748  5748 I bt_bluedroid: init
09-14 06:36:24.628  5748  5760 I BluetoothAdapterState: Entering OffState
,09-14 06:36:24.630  5748  5761 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-14 06:36:24.630  5748  5761 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 06:36:24.630  5748  5761 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 06:36:24.630  5748  5761 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-14 06:36:24.631  5748  5748 I bt_bluedroid: get_profile_interface socket
,09-14 06:36:24.632  5748  5764 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-14 06:36:24.632  5748  5748 I bt_bluedroid: get_profile_interface sdp
,09-14 06:36:24.634  5748  5764 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-14 06:36:24.637  5748  5759 I bt_bluedroid: config_hci_snoop_log
,09-14 06:36:24.638   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 06:36:24.642  5748  5760 D BluetoothAdapterState: Current state: OFF, message: 0
,09-14 06:36:24.642  5748  5760 D BluetoothAdapterProperties: Setting state to 14
09-14 06:36:24.642  5748  5760 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-14 06:36:24.644  5748  5760 D BluetoothBondStateMachine: make
,09-14 06:36:24.646  5748  5765 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 06:36:24.648  5748  5760 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:36:24.649  5748  5748 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 06:36:24.652  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:24.653  5748  5748 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 06:36:24.653  5748  5748 D BtGatt.GattService: Received start request. Starting profile...
09-14 06:36:24.654  5748  5748 D BtGatt.GattService: start()
09-14 06:36:24.654  5748  5748 I bt_bluedroid: get_profile_interface gatt
,09-14 06:36:24.655  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
09-14 06:36:24.655  5748  5748 D BtGatt.AdvertiseManager: advertise manager created
,09-14 06:36:24.659  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:24.660  5748  5748 V BluetoothAdapterState: isTurningOn()=false
09-14 06:36:24.660  5748  5748 V BluetoothAdapterState: isBleTurningOn()=true
09-14 06:36:24.660  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:24.660  5748  5760 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-14 06:36:24.661  5748  5760 I bt_bluedroid: bt_bluedroid
,09-14 06:36:24.661  5748  5761 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-14 06:36:24.662  5748  5761 I bt_hci  : start_up
,09-14 06:36:24.666  5748  5761 I bt_vendor: alloc value 0xf3bab871
,09-14 06:36:24.666  5748  5761 I bt_vendor: init
09-14 06:36:24.666  5748  5761 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 06:36:24.666  5748  5761 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 06:36:24.777  5748  5761 D bt_hci  : start_up starting async portion
,09-14 06:36:24.777  5748  5768 I bt_hci  : event_finish_startup
09-14 06:36:24.778  5748  5768 I bt_hci_h4: hal_open
09-14 06:36:24.778  5748  5768 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-14 06:36:24.777  5769  5769 W irq/448-msm_hs_: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-14 06:36:24.781  5748  5768 I bt_userial_vendor: device fd = 54 open
,09-14 06:36:24.795  5748  5768 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 06:36:24.798  5748  5768 D bt_hwcfg: Chipset BCM4358A3
,09-14 06:36:24.798  5748  5768 D bt_hwcfg: Target name = [BCM4358A3]
09-14 06:36:24.799  5748  5768 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-14 06:36:25.205  5748  5768 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 06:36:25.205  5748  5768 D bt_hwcfg: Settlement delay -- 100 ms
09-14 06:36:25.205  5748  5768 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 06:36:25.338  5748  5768 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 06:36:25.339  5748  5768 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-14 06:36:25.340  5748  5768 I bt_hwcfg: vendor lib fwcfg completed
,09-14 06:36:25.341  5748  5768 I bt_vendor: firmware callback
,09-14 06:36:25.341  5748  5768 I bt_hci  : firmware_config_callback
,09-14 06:36:25.349  5748  5771 I bt_btu  : btu_task pending for preload complete event
,09-14 06:36:25.350  5748  5771 I bt_btu_task: Bluetooth chip preload is complete
09-14 06:36:25.350  5748  5771 I bt_btu  : btu_task received preload complete event
,09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_A2D
09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-14 06:36:25.358  5748  5771 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 06:36:25.359  5748  5771 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 06:36:25.359  5748  5771 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 06:36:25.359  5748  5771 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 06:36:25.359  5748  5771 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 06:36:25.359  5748  5771 I         : BTE_InitTraceLevels -- TRC_SMP
,09-14 06:36:25.359  5748  5771 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 06:36:25.359  5748  5771 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 06:36:25.440  5748  5771 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b29549
09-14 06:36:25.441  5748  5771 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b29549 
,09-14 06:36:25.457  5748  5764 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 06:36:25.458  5748  5764 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 06:36:25.459  5748  5764 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-14 06:36:25.462  5748  5764 D BluetoothAdapterProperties: Name is: Nexus 6P
09-14 06:36:25.465  5748  5764 D BluetoothAdapterProperties: Scan Mode:20
09-14 06:36:25.465  5748  5764 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 06:36:25.466  5748  5764 D bt_hci  : do_postload posting postload work item
09-14 06:36:25.466  5748  5768 I bt_hci  : event_postload
,09-14 06:36:25.466  5748  5768 I bt_vendor: sco_config_cb
09-14 06:36:25.466  5748  5768 I bt_hci  : sco_config_callback postload finished.
09-14 06:36:25.469  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:25.471  5748  5764 D bt_bte_conf: Device ID record 1 : primary
09-14 06:36:25.471  5748  5764 D bt_bte_conf:   vendorId            = 000f
,09-14 06:36:25.471  5748  5764 D bt_bte_conf:   vendorIdSource      = 0001
,09-14 06:36:25.472  5748  5764 D bt_bte_conf:   product             = 1200
,09-14 06:36:25.472  5748  5764 D bt_bte_conf:   version             = 1436
,09-14 06:36:25.472  5748  5764 D bt_bte_conf:   clientExecutableURL = 
,09-14 06:36:25.472  5748  5764 D bt_bte_conf:   serviceDescription  = 
09-14 06:36:25.472  5748  5764 D bt_bte_conf:   documentationURL    = 
,09-14 06:36:25.472  5748  5764 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 06:36:25.472  5748  5761 D bt_stack_manager: event_start_up_stack finished
09-14 06:36:25.473  5748  5760 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-14 06:36:25.474  5748  5760 D BluetoothAdapterProperties: Setting state to 15
09-14 06:36:25.474  5748  5760 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-14 06:36:25.475  5748  5760 I BluetoothAdapterState: Entering BleOnState
09-14 06:36:25.476  5748  5768 I bt_vendor: low_power_mode_cb
09-14 06:36:25.481  5748  5760 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 06:36:25.482  5748  5760 D BluetoothAdapterProperties: Setting state to 11
09-14 06:36:25.482  5748  5760 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-14 06:36:25.490  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:25.492  5748  5748 D HeadsetService: Received start request. Starting profile...
09-14 06:36:25.495  5748  5748 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-14 06:36:25.495  5748  5748 D HeadsetStateMachine: make
09-14 06:36:25.497  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:25.505  5748  5760 I BluetoothAdapterState: Entering PendingCommandState
,09-14 06:36:25.508  5748  5748 D HeadsetStateMachine: max_hf_connections = 1
,09-14 06:36:25.508  5748  5748 I bt_bluedroid: get_profile_interface handsfree
09-14 06:36:25.508  5748  5764 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 06:36:25.509  5748  5764 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-14 06:36:25.511  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:25.512  5748  5748 D A2dpService: Received start request. Starting profile...
09-14 06:36:25.513  5748  5748 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-14 06:36:25.513  5748  5748 I bt_bluedroid: get_profile_interface avrcp
,09-14 06:36:25.519  5748  5748 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 06:36:25.519  5748  5748 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 06:36:25.519  5748  5748 D A2dpStateMachine: make
,09-14 06:36:25.521  5748  5748 I bt_bluedroid: get_profile_interface a2dp
09-14 06:36:25.522  5748  5764 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-14 06:36:25.523  5748  5779 D A2dpStateMachine: Enter Disconnected: -2
,09-14 06:36:25.523  5748  5748 I BluetoothHidServiceJni: classInitNative: succeeds
09-14 06:36:25.524  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:25.525  5748  5748 D HidService: Received start request. Starting profile...
09-14 06:36:25.525  5748  5748 I bt_bluedroid: get_profile_interface hidhost
09-14 06:36:25.525  5748  5748 D HidService: setHidService(): set to: null
09-14 06:36:25.525  5748  5764 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b0a56d
09-14 06:36:25.525  5748  5764 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-14 06:36:25.527  5748  5748 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 06:36:25.528  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
09-14 06:36:25.528  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:36:25.529  5748  5748 D HealthService: Received start request. Starting profile...
,09-14 06:36:25.531  5748  5748 I bt_bluedroid: get_profile_interface health
,09-14 06:36:25.531  5748  5748 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-14 06:36:25.532  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:25.533  5748  5748 D PanService: Received start request. Starting profile...
09-14 06:36:25.533  5748  5748 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 06:36:25.533  5748  5748 I bt_bluedroid: get_profile_interface pan
09-14 06:36:25.534  5748  5764 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-14 06:36:25.535  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:25.536  5748  5748 D BluetoothMapService: Received start request. Starting profile...
09-14 06:36:25.536  5748  5748 D BluetoothMapService: start()
,09-14 06:36:25.539  5748  5748 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-14 06:36:25.539  5748  5748 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 06:36:25.540  5748  5748 D BluetoothMapAppObserver: createReceiver()
,09-14 06:36:25.541  5748  5748 D BluetoothMapAppObserver: initObservers()
09-14 06:36:25.541  5748  5748 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 06:36:25.547  5748  5748 V SapService: SapBinder()
,09-14 06:36:25.547  5748  5748 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
09-14 06:36:25.548  5748  5748 D SapService: Received start request. Starting profile...
09-14 06:36:25.548  5748  5748 V SapService: start()
,09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isTurningOff()=false
,09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:25.551  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:25.552  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
09-14 06:36:25.553  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:25.554  5748  5748 V BluetoothAdapterState: isTurningOff()=false
09-14 06:36:25.554  5748  5748 V BluetoothAdapterState: isTurningOn()=true
09-14 06:36:25.554  5748  5748 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 06:36:25.554  5748  5748 V BluetoothAdapterState: isBleTurningOff()=false
09-14 06:36:25.554  5748  5760 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 06:36:25.554  5748  5760 D BluetoothAdapterProperties: ScanMode =  20
09-14 06:36:25.555  5748  5760 D BluetoothAdapterProperties: State =  11
,09-14 06:36:25.555  5748  5760 D BluetoothAdapterProperties: Setting state to 12
09-14 06:36:25.555  5748  5760 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 06:36:25.555  3504  3521 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:25.556  5748  5760 I BluetoothAdapterState: Entering OnState
09-14 06:36:25.556  5548  5560 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 06:36:25.557  5748  5764 D BluetoothAdapterProperties: Scan Mode:21
,09-14 06:36:25.558  5748  5764 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 06:36:25.559   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:25.559  3111  3129 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:25.560   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 06:36:25.560  3111  3724 D BluetoothPan: onBluetoothStateChange on: true
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:25.561  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:25.562  5548  5558 D BluetoothPan: onBluetoothStateChange on: true
09-14 06:36:25.562  5548  5548 D BluetoothInputDevice: Proxy object connected
09-14 06:36:25.562  5548  5548 D HidProfile: Bluetooth service connected
09-14 06:36:25.563  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:25.564  3111  3124 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:36:25.565  3111  3129 D BluetoothMap: onBluetoothStateChange: up=true
09-14 06:36:25.566  5748  5748 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 06:36:25.566  3111  3724 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 06:36:25.567  5748  5748 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 06:36:25.568   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:25.568  5548  5561 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 06:36:25.568  5748  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:25.569  3111  3111 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 06:36:25.569  3111  3111 D PanProfile: Bluetooth service connected
09-14 06:36:25.569  3111  3111 D BluetoothInputDevice: Proxy object connected
09-14 06:36:25.569  3111  3111 D HidProfile: Bluetooth service connected
09-14 06:36:25.569  3111  3124 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:36:25.570  5748  5748 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:25.571  5748  5748 D ObexServerSockets: Succeed to create listening sockets 
09-14 06:36:25.571  5748  5748 D ObexServerSockets0: startAccept()
09-14 06:36:25.571  5748  5748 D ObexServerSockets0: prepareForNewConnect()
09-14 06:36:25.572  5548  5560 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 06:36:25.572   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 06:36:25.573  5548  5558 D BluetoothMap: onBluetoothStateChange: up=true
09-14 06:36:25.573  5748  5748 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 06:36:25.573  5748  5748 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 06:36:25.574  5748  5784 D ObexServerSockets0: Accepting socket connection...
09-14 06:36:25.574  5748  5785 D ObexServerSockets0: Accepting socket connection...
09-14 06:36:25.574  5548  5548 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 06:36:25.574  5548  5548 D PanProfile: Bluetooth service connected
09-14 06:36:25.574  3111  3111 D BluetoothMap: Proxy object connected
09-14 06:36:25.574  3111  3111 D MapProfile: Bluetooth service connected
09-14 06:36:25.575  3111  3111 D BluetoothMap: getConnectedDevices()
09-14 06:36:25.575   931   931 D BluetoothA2dp: Proxy object connected
09-14 06:36:25.575  5548  5548 D BluetoothMap: Proxy object connected
09-14 06:36:25.575  5548  5548 D MapProfile: Bluetooth service connected
09-14 06:36:25.575  5548  5548 D BluetoothMap: getConnectedDevices()
09-14 06:36:25.576  5548  5561 D BluetoothPbap: onBluetoothStateChange: up=true
09-14 06:36:25.576  3111  3111 D BluetoothA2dp: Proxy object connected
09-14 06:36:25.578  5548  5548 D BluetoothA2dp: Proxy object connected
09-14 06:36:25.579   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
09-14 06:36:25.581  5748  5748 D BluetoothMapService: onReceive
09-14 06:36:25.581  5748  5748 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 06:36:25.581  5748  5748 D BluetoothMapService: STATE_ON
09-14 06:36:25.582  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:25.584  5748  5788 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:25.585  5748  5788 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-14 06:36:25.585  5748  5788 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-14 06:36:25.587  5548  5548 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 06:36:25.594  3585  3585 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 06:36:25.594  5548  5548 D DockEventReceiver: finishStartingService: stopping service
,09-14 06:36:25.600  5548  5548 D BluetoothPbap: Proxy object connected
,09-14 06:36:25.600  5548  5548 D PbapServerProfile: Bluetooth service connected
,09-14 06:36:25.605  5748  5748 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-14 06:36:25.605  5748  5748 D ObexServerSockets0: prepareForNewConnect()
09-14 06:36:25.606  5748  5792 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 06:36:25.610  3111  3111 D BluetoothPbap: Proxy object connected
09-14 06:36:25.610  3111  3111 D PbapServerProfile: Bluetooth service connected
,09-14 06:36:25.623  5748  5796 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 06:36:25.624  5748  5796 I BtOppRfcommListener: Accept thread started.
,09-14 06:36:25.657  3111  3724 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.657  3111  3111 D HeadsetProfile: Bluetooth service connected
09-14 06:36:25.657   931   931 D BluetoothHeadset: Proxy object connected
09-14 06:36:25.657  3504  3532 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.658  5548  5560 D BluetoothHeadset: Proxy object connected
09-14 06:36:25.658   931   931 D BluetoothHeadset: Proxy object connected
09-14 06:36:25.658   931   931 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.658  5548  5548 D HeadsetProfile: Bluetooth service connected
09-14 06:36:25.660   931   948 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.660  3111  3392 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.661  3111  3111 D HeadsetProfile: Bluetooth service connected
09-14 06:36:25.661   931   948 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.667   931   948 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.672  5548  5561 D BluetoothHeadset: Proxy object connected
,09-14 06:36:25.672  5548  5548 D HeadsetProfile: Bluetooth service connected
,09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:26.526  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:26.532  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:26.534  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:26.535  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9036139 added. We now have 8 listener(s)
,09-14 06:36:26.535  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 06:36:26.539   931  3551 D WifiService: setWifiEnabled: false pid=5496, uid=10077
,09-14 06:36:26.539   931  3551 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:36:26.543  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:26.544   931   942 D WifiService: setWifiEnabled: true pid=5496, uid=10077
09-14 06:36:26.544   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 06:36:26.548   510   930 D SoftapController: Softap fwReload - Ok
,09-14 06:36:26.552   510   930 D CommandListener: Setting iface cfg
,09-14 06:36:26.552   510   930 D CommandListener: Trying to bring down wlan0
,09-14 06:36:26.553   510   930 D CommandListener: Clearing all IP addresses on wlan0
,09-14 06:36:26.557   931  2969 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-14 06:36:27.168   931  2969 D wifi    : set interface wlan0 flags (UP)
,09-14 06:36:27.174   931  2969 I WifiHAL : Initializing wifi
09-14 06:36:27.174   931  2969 I WifiHAL : Creating socket
09-14 06:36:27.177   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-14 06:36:27.182   931  2969 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-14 06:36:27.183   931  2969 D wifi    : Did set static halHandle = 0x7f84a65f40
09-14 06:36:27.183   931  2969 D wifi    : halHandle = 0x7f84a65f40, mVM = 0x7f8f54d140, mCls = 0x113a
09-14 06:36:27.183   931  2969 D wifi    : array field set
09-14 06:36:27.183   931  2969 I WifiNative-HAL: interface[0] = wlan0
09-14 06:36:27.185   931  5802 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547686342464
09-14 06:36:27.186   931  5802 D wifi    : waitForHalEvents called, vm = 0x7f8f54d140, obj = 0x113a, env = 0x7f704b9380
,09-14 06:36:27.237  5803  5803 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-14 06:36:27.257  5803  5803 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:36:27.285   931  2969 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-14 06:36:27.290  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:27.291  5803  5803 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-14 06:36:27.291  5803  5803 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-14 06:36:27.308   931  2969 D WifiConfigStore: Loading config and enabling all networks 
,09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:27.311  5496  5496 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 06:36:27.313  5496  5496 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:27.315   931  2969 D WifiConfigStore: loaded 0 passpoint configs
09-14 06:36:27.316   931  2969 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-14 06:36:27.316   931  2969 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-14 06:36:27.317   931  2969 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-14 06:36:27.317   931  2969 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
,09-14 06:36:27.317   931  2969 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 06:36:27.321  4295  4295 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 06:36:27.321   931  2969 D WifiNative-HAL: Setting external_sim to 1
09-14 06:36:27.322   931  2969 D wifi    : setting dfs flag to true, 0x7f75fc3160
09-14 06:36:27.322   931  2969 D WifiStateMachine: Setting OUI to DA-A1-19
09-14 06:36:27.322   931  2969 D wifi    : setting scan oui 0x7f75fc3160
09-14 06:36:27.322   931  2969 D WifiHAL : Sending mac address OUI
,09-14 06:36:27.337   931  2969 E native  : do suspend true
,09-14 06:36:27.342   931  2969 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-14 06:36:27.342   931   931 D RttService: SCAN_AVAILABLE : 3
09-14 06:36:27.343   931  3077 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-14 06:36:27.343   510   930 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-14 06:36:27.344   510   930 D CommandListener: Setting iface cfg
,09-14 06:36:27.347   931  2968 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
09-14 06:36:27.348   931  2968 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 06:36:27.354   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=254193 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=5 mControllerEnergyUsed=19 }
09-14 06:36:27.354   931  2968 D WifiNative-HAL: p2pGetDeviceAddress
09-14 06:36:27.354   931  2968 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-14 06:36:27.490   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:27.558  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:27.564  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:27.572  5496  5542 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-14 06:36:27.573  5496  5542 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-14 06:36:27.576  5496  5542 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@206e11c Bundle[{}]
,09-14 06:36:27.577  5496  5542 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 06:36:27.578  5496  5542 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-14 06:36:27.578  5496  5542 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-14 06:36:27.579  5496  5542 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-14 06:36:27.579  5496  5542 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-14 06:36:27.581  5496  5542 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-14 06:36:27.587  5496  5542 I System.out: Running OutgoingSocketThread
,09-14 06:36:27.589  5496  5814 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,09-14 06:36:27.592  5496  5814 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 49031
,09-14 06:36:27.592  5496  5814 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 06:36:28.491   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:28.590  5496  5542 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,09-14 06:36:28.591  5496  5542 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,09-14 06:36:28.597  5496  5542 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,09-14 06:36:28.601  5496  5542 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-14 06:36:28.601  5496  5542 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-14 06:36:28.606  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 06:36:28.606  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@925f37e added. We now have 2 listener(s)
,09-14 06:36:28.609  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.609  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.609  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.609  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.610  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd40df added. We now have 9 listener(s)
09-14 06:36:28.610  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.611  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:36:28.615  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:28.619  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:28.622  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:28.623  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:36:28.623  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.623  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22fd7f5 added. We now have 3 listener(s)
09-14 06:36:28.625  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:28.625  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.625  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.625  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.625  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.625  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea9c98a added. We now have 10 listener(s)
09-14 06:36:28.626  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.626  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:28.626  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:36:28.626  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:28.626  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.626  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.626  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:28.626  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.626  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@925f37e removed from the list
09-14 06:36:28.626  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.626  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd40df removed from the list
09-14 06:36:28.627  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:28.627  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:28.627  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.628  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:28.628  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.630  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.630  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.630  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.630  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6cd40df not in the list
09-14 06:36:28.630  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.630  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:28.632  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:28.632  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.632  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.632  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ea9c98a removed from the list
09-14 06:36:28.632  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.632  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.632  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.632  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.632  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22fd7f5 removed from the list
09-14 06:36:28.633  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 06:36:28.633  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46f0bfb added. We now have 2 listener(s)
09-14 06:36:28.635  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.635  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.635  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.635  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.635  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810c418 added. We now have 9 listener(s)
09-14 06:36:28.635  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.636  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:36:28.640  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:28.643  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:28.646  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:28.646  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:36:28.646  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.646  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2f456 added. We now have 3 listener(s)
09-14 06:36:28.648  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:28.648  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.648  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.648  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.648  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.649  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a986cd7 added. We now have 10 listener(s)
09-14 06:36:28.649  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.649  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 06:36:28.649  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:36:28.649  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:36:28.649  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.649  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.649  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:28.653  5496  5542 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.653  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:36:28.657  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:36:28.658  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:28.658  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:36:28.662  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 06:36:28.662  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:36:28.663  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:36:28.663  5496  5542 D BluetoothAdapter: STATE_ON
,09-14 06:36:28.667  5748  5786 D BtGatt.GattService: registerClient() - UUID=608bdc49-0f6d-4277-ab69-094e53fabcb1
,09-14 06:36:28.668  5748  5764 D BtGatt.GattService: onClientRegistered() - UUID=608bdc49-0f6d-4277-ab69-094e53fabcb1, clientIf=5
,09-14 06:36:28.669  5496  5507 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:36:28.670  5748  5759 D BtGatt.GattService: start scan with filters
09-14 06:36:28.673  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 06:36:28.673  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:36:28.673  5748  5767 D BtGatt.ScanManager: handling starting scan
09-14 06:36:28.673  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:36:28.674  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:36:28.675  5748  5767 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c25e769
,09-14 06:36:28.677  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:36:28.677  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:36:28.677  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:28.678  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 06:36:28.681  5496  5542 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-14 06:36:28.681  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:28.681  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 06:36:28.681  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.681  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:28.682  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 06:36:28.682  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:36:28.682  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:36:28.682  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:36:28.682  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:36:28.682  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:36:28.682  5748  5764 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:36:28.682  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:28.682  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:28.683  5748  5786 D BtGatt.GattService: stopScan() - queue size =1
,09-14 06:36:28.683  5748  5767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 06:36:28.684  5748  5759 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:36:28.685  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:28.685  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:36:28.685  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:36:28.685  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:36:28.685  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 06:36:28.687  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:28.687  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:28.687  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:36:28.687  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 06:36:28.688  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:28.689  5748  5764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:36:28.689  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.690  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:28.690  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.690  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 06:36:28.690  5748  5767 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:36:28.690  5748  5767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 06:36:28.692  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:28.692  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:28.693  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:28.693  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.693  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.693  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:28.693  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.693  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46f0bfb removed from the list
09-14 06:36:28.693  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.693  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810c418 removed from the list
09-14 06:36:28.693  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:28.693  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:28.696  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:28.696  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-14 06:36:28.696  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.696  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:28.698  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 06:36:28.698  5496  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:36:28.698  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.698  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.698  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.699  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@810c418 not in the list
09-14 06:36:28.701  5748  5764 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:36:28.701  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:28.702  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:36:28.703  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:28.703  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:36:28.703  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:28.703  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:28.706  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:28.706  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.706  5748  5764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:36:28.706  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.707  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.707  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:28.707  5496  5542 D BluetoothLeScanner: could not find callback wrapper
09-14 06:36:28.707  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:28.707  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:36:28.707  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:28.707  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.707  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:28.708  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a986cd7 removed from the list
09-14 06:36:28.708  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.708  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.708  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.708  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.708  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:28.708  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.708  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fe2f456 removed from the list
09-14 06:36:28.708  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.709  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e1fcf added. We now have 2 listener(s)
,09-14 06:36:28.710  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.710  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.710  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.710  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.710  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ecd5c added. We now have 9 listener(s)
09-14 06:36:28.710  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.710  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.710  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:28.711  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.712  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 06:36:28.713  5748  5764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 06:36:28.713  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:28.713  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.714  5748  5767 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:36:28.717  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:28.719  5748  5764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 06:36:28.719  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.719  5748  5767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:28.720  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:28.722  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:28.722  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 06:36:28.723  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.723  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0fa93a added. We now have 3 listener(s)
09-14 06:36:28.724  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:28.724  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.724  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.724  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.724  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.724  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c16e9eb added. We now have 10 listener(s)
09-14 06:36:28.724  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.724  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:36:28.725  5748  5764 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 06:36:28.725  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.725  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:36:28.725  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:36:28.725  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:36:28.725  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.725  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.726  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 06:36:28.728  5496  5542 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.728  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:36:28.731  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:36:28.731  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 06:36:28.732  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:36:28.734  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 06:36:28.734  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:36:28.734  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:36:28.735  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:28.736  5748  5777 D BtGatt.GattService: registerClient() - UUID=e9253f2a-ca06-478f-b74c-54a1e924be9d
09-14 06:36:28.737  5748  5764 D BtGatt.GattService: onClientRegistered() - UUID=e9253f2a-ca06-478f-b74c-54a1e924be9d, clientIf=5
,09-14 06:36:28.737  5496  5506 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 06:36:28.737  5748  5759 D BtGatt.GattService: start scan with filters
09-14 06:36:28.739  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 06:36:28.740  5748  5767 D BtGatt.ScanManager: handling starting scan
,09-14 06:36:28.740  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:36:28.740  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:36:28.740  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 06:36:28.742  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:36:28.742  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:36:28.742  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:28.743  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 06:36:28.745  5748  5764 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:36:28.746  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.746  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:36:28.746  5496  5542 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 06:36:28.746  5748  5767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 06:36:28.746  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:28.746  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:28.746  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:28.746  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.746  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.746  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:28.746  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.746  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e1fcf removed from the list
,09-14 06:36:28.746  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.746  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ecd5c removed from the list
09-14 06:36:28.746  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:28.746  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:28.747  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.747  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-14 06:36:28.747  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.747  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:28.748  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.748  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.748  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 06:36:28.748  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a6ecd5c not in the list
09-14 06:36:28.748  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:36:28.748  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:36:28.748  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:36:28.748  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:36:28.748  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:36:28.750  5748  5764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:36:28.750  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.750  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:28.751  5748  5767 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:36:28.751  5748  5767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 06:36:28.751  5748  5787 D BtGatt.GattService: stopScan() - queue size =1
09-14 06:36:28.752  5748  5758 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 06:36:28.752  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:28.752  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:36:28.752  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-14 06:36:28.752  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:36:28.752  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 06:36:28.753  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:28.753  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:28.753  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:36:28.753  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 06:36:28.754  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:28.756  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 06:36:28.756  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.756  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.756  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:28.756  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c16e9eb removed from the list
09-14 06:36:28.756  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.756  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.756  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.756  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.756  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:28.756  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.756  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0fa93a removed from the list
09-14 06:36:28.757  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.757  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b56bf4 added. We now have 2 listener(s)
09-14 06:36:28.758  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.758  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.758  5496  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:36:28.758  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.758  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.759  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.759  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4db7f1d added. We now have 9 listener(s)
09-14 06:36:28.759  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.759  5748  5764 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:36:28.759  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.759  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 06:36:28.762  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 06:36:28.763  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:28.763  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:36:28.763  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 06:36:28.764  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:28.764  5748  5764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:36:28.764  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:28.765  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:28.765  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:28.765  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.768  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.768  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:28.768  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.768  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:28.770  5748  5764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-14 06:36:28.770  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.770  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:28.770  5748  5767 D BtGatt.ScanManager: stopping BLe Batch
,09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:28.772  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:28.775  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 06:36:28.775  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 06:36:28.775  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.775  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b75360 added. We now have 3 listener(s)
09-14 06:36:28.776  5748  5764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:36:28.776  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.776  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:28.776  5748  5767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 06:36:28.776  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.776  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.776  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.776  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 06:36:28.776  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db5f019 added. We now have 10 listener(s)
09-14 06:36:28.776  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.776  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:36:28.777  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 06:36:28.777  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 06:36:28.777  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.777  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.777  5496  5496 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 06:36:28.779  5496  5542 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.779  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 06:36:28.780  5748  5764 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 06:36:28.780  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:28.782  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:36:28.782  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:28.782  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 06:36:28.784  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 06:36:28.784  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 06:36:28.784  5496  5542 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 06:36:28.785  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:28.786  5748  5758 D BtGatt.GattService: registerClient() - UUID=60263edc-ced0-4244-b7c6-89de2117be6e
09-14 06:36:28.787  5748  5764 D BtGatt.GattService: onClientRegistered() - UUID=60263edc-ced0-4244-b7c6-89de2117be6e, clientIf=5
09-14 06:36:28.787  5496  5506 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 06:36:28.787  5748  5777 D BtGatt.GattService: start scan with filters
,09-14 06:36:28.790  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 06:36:28.790  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 06:36:28.790  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 06:36:28.790  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 06:36:28.790  5748  5767 D BtGatt.ScanManager: handling starting scan
,09-14 06:36:28.792  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 06:36:28.792  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 06:36:28.792  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 06:36:28.793  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 06:36:28.795  5748  5764 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 06:36:28.795  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.795  5748  5767 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 06:36:28.797  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 06:36:28.797  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:28.797  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:28.797  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.797  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.797  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:28.797  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-14 06:36:28.797  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6b56bf4 removed from the list
09-14 06:36:28.797  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.797  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4db7f1d removed from the list
09-14 06:36:28.797  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:28.797  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:28.798  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-14 06:36:28.798  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-14 06:36:28.798  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.798  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:28.799  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.799  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.799  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.799  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4db7f1d not in the list
,09-14 06:36:28.799  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 06:36:28.799  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 06:36:28.799  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 06:36:28.799  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 06:36:28.799  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 06:36:28.799  5748  5764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-14 06:36:28.799  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.799  5748  5767 D BtGatt.ScanManager: Starting BLE batch scan
09-14 06:36:28.799  5748  5767 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 06:36:28.799  5496  5542 D BluetoothAdapter: STATE_ON
09-14 06:36:28.800  5748  5758 D BtGatt.GattService: stopScan() - queue size =1
,09-14 06:36:28.800  5748  5777 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 06:36:28.801  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 06:36:28.801  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 06:36:28.801  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 06:36:28.801  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 06:36:28.801  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 06:36:28.802  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:28.802  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 06:36:28.802  5496  5542 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 06:36:28.802  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:28.803  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 06:36:28.804  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.804  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 06:36:28.804  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.804  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 06:36:28.805  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@db5f019 removed from the list
09-14 06:36:28.805  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.805  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.805  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.805  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.805  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:28.805  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.805  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b75360 removed from the list
,09-14 06:36:28.805  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.805  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44d4ea added. We now have 2 listener(s)
09-14 06:36:28.807  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.807  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.807  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.807  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.807  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a23db added. We now have 9 listener(s)
09-14 06:36:28.807  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.807  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.807  5496  5496 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 06:36:28.807  5748  5764 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 06:36:28.808  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:28.808  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 06:36:28.810  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 06:36:28.813  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 06:36:28.814  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 06:36:28.814  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 06:36:28.814  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:28.814  5748  5764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 06:36:28.814  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 06:36:28.814  5496  5542 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 06:36:28.815  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 06:36:28.817  5496  5542 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 06:36:28.817  5496  5542 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 06:36:28.817  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 06:36:28.817  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4c8951 added. We now have 3 listener(s)
09-14 06:36:28.818  5496  5496 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 06:36:28.818  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 06:36:28.818  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 06:36:28.818  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-14 06:36:28.819  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 06:36:28.819  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 06:36:28.819  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 06:36:28.819  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1d22b7 added. We now have 10 listener(s)
09-14 06:36:28.819  5496  5542 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 06:36:28.819  5496  5542 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 06:36:28.819  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 06:36:28.819  5496  5542 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 06:36:28.819  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.819  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.819  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 06:36:28.819  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.819  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44d4ea removed from the list
09-14 06:36:28.819  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.819  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a23db removed from the list
09-14 06:36:28.819  5496  5542 D io.jxcore.node.ConnectivityMonitor: stop
09-14 06:36:28.819  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 06:36:28.820  5748  5764 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-14 06:36:28.820  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.820  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.820  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-14 06:36:28.820  5748  5767 D BtGatt.ScanManager: stopping BLe Batch
09-14 06:36:28.820  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.820  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 lis,tener(s) left
09-14 06:36:28.821  5496  5496 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 06:36:28.821  5496  5496 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 06:36:28.821  5496  5496 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.822  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.822  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.822  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.822  5496  5542 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d2a23db not in the list
09-14 06:36:28.822  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.822  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.823  5496  5496 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 06:36:28.824  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 06:36:28.824  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 06:36:28.824  5496  5542 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 06:36:28.824  5496  5542 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f1d22b7 removed from the list
,09-14 06:36:28.824  5496  5542 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 06:36:28.824  5496  5542 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 06:36:28.824  5496  5542 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 06:36:28.824  5496  5542 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 06:36:28.824  5496  5542 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4c8951 removed from the list
09-14 06:36:28.825  5748  5764 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 06:36:28.825  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 06:36:28.825  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-14 06:36:28.825  5748  5767 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 06:36:28.825  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 06:36:28.825  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-14 06:36:28.825  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 06:36:28.826  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 06:36:28.826  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:36:28.830  5748  5764 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 06:36:28.830  5748  5764 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 06:36:28.831  5496  5815 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
,09-14 06:36:28.831  5496  5815 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
09-14 06:36:28.831  5496  5815 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-14 06:36:28.833  5496  5816 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
09-14 06:36:28.833  5496  5816 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
09-14 06:36:28.833  5496  5816 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-14 06:36:28.834  5496  5542 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-14 06:36:28.834  5496  5542 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-14 06:36:28.834  5496  5542 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-14 06:36:28.834  5496  5542 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-14 06:36:28.834  5496  5542 D com.test.thalitest.ThaliTestRunner: Total duration: 22698 ms
09-14 06:36:28.836  5496  5542 I jxcore-log: Total number of executed tests:  80
09-14 06:36:28.836  5496  5542 I jxcore-log: 
09-14 06:36:28.836  5496  5542 I jxcore-log: Number of passed tests:  80
09-14 06:36:28.836  5496  5542 I jxcore-log: 
09-14 06:36:28.836  5496  5542 I jxcore-log: Number of failed tests:  0
09-14 06:36:28.836  5496  5542 I jxcore-log: 
09-14 06:36:28.836  5496  5542 I jxcore-log: Number of ignored tests:  0
09-14 06:36:28.836  5496  5542 I jxcore-log: 
09-14 06:36:28.836  5496  5542 I jxcore-log: Total duration:  22698
09-14 06:36:28.836  5496  5542 I jxcore-log: 
09-14 06:36:28.838  5496  5542 I jxcore-log: Unit Test app is loaded
09-14 06:36:28.838  5496  5542 I jxcore-log: 
,09-14 06:36:28.844  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:36:28.844  5496  5542 I jxcore-log: 
,09-14 06:36:28.847  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:36:28.847  5496  5542 I jxcore-log: 
,09-14 06:36:28.848  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:36:28.848  5496  5542 I jxcore-log: 
09-14 06:36:28.849  5496  5496 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
09-14 06:36:28.849  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:36:28.849  5496  5542 I jxcore-log: 
09-14 06:36:28.850  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:36:28.850  5496  5542 I jxcore-log: 
,09-14 06:36:28.852  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:36:28.852  5496  5542 I jxcore-log: 
,09-14 06:36:28.855  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 06:36:28.855  5496  5542 I jxcore-log: 
,09-14 06:36:28.856  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.856  5496  5542 I jxcore-log: 
,09-14 06:36:28.857  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.857  5496  5542 I jxcore-log: 
,09-14 06:36:28.858  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.858  5496  5542 I jxcore-log: 
,09-14 06:36:28.859  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.859  5496  5542 I jxcore-log: 
,09-14 06:36:28.860  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:36:28.860  5496  5542 I jxcore-log: 
,09-14 06:36:28.861  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.861  5496  5542 I jxcore-log: 
,09-14 06:36:28.862  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.862  5496  5542 I jxcore-log: 
,09-14 06:36:28.862  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.862  5496  5542 I jxcore-log: 
,09-14 06:36:28.863  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.863  5496  5542 I jxcore-log: 
,09-14 06:36:28.864  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.864  5496  5542 I jxcore-log: 
,09-14 06:36:28.874  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.874  5496  5542 I jxcore-log: 
,09-14 06:36:28.874  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.874  5496  5542 I jxcore-log: 
09-14 06:36:28.875  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.875  5496  5542 I jxcore-log: 
,09-14 06:36:28.875  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.875  5496  5542 I jxcore-log: 
09-14 06:36:28.875  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 06:36:28.875  5496  5542 I jxcore-log: 
09-14 06:36:28.876  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.876  5496  5542 I jxcore-log: 
,09-14 06:36:28.876  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.876  5496  5542 I jxcore-log: 
09-14 06:36:28.876  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.876  5496  5542 I jxcore-log: 
09-14 06:36:28.877  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.877  5496  5542 I jxcore-log: 
,09-14 06:36:28.877  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.877  5496  5542 I jxcore-log: 
09-14 06:36:28.878  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.878  5496  5542 I jxcore-log: 
09-14 06:36:28.878  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 06:36:28.878  5496  5542 I jxcore-log: 
,09-14 06:36:28.880  5496  5542 I jxcore-log: My device name is: Huawei-Nexus 6P
09-14 06:36:28.880  5496  5542 I jxcore-log: 
,09-14 06:36:28.976  5496  5542 W jxcore-log: !!! js_ReportOverRecursed called !!!
,09-14 06:36:29.214  5496  5496 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:36:29.219  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:36:29.219  5496  5542 I jxcore-log: 
,09-14 06:36:29.270  5496  5496 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:36:29.277  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:36:29.277  5496  5542 I jxcore-log: 
,09-14 06:36:29.323  5496  5496 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 06:36:29.328  5496  5542 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 06:36:29.328  5496  5542 I jxcore-log: 
,09-14 06:36:29.492   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:30.493   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:31.494   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:31.691  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 06:36:31.691  5496  5542 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,09-14 06:36:31.796  5496  5542 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 06:36:31.796  5496  5542 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-14 06:36:32.495   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 06:36:39.101  3900  5817 I EventLogService: Aggregate from 1473847907710 (log), 1473847598953 (data)
,09-14 06:36:42.378   931  2935 I PowerManagerService: Waking up from dozing (uid 1000)...
09-14 06:36:42.379   931   931 V KeyguardServiceDelegate: onStartedWakingUp()
,09-14 06:36:42.386   931   951 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
09-14 06:36:42.386   931   951 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@9dd360d)
09-14 06:36:42.390   931   931 I sensors : batch
09-14 06:36:42.391   931   931 I sensors : activate
09-14 06:36:42.392   515  3364 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-14 06:36:42.393   931   951 I sensors : batch
09-14 06:36:42.393   931   951 I sensors : activate
,09-14 06:36:42.397   384   384 D SurfaceFlinger: Set power mode=2, type=0 flinger=0x7f91f43c00
09-14 06:36:42.398   384   384 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
,09-14 06:36:42.399   931  2969 E native  : do suspend false
,09-14 06:36:42.401   931   949 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
09-14 06:36:42.402   931  3417 V KeyguardServiceDelegate: **** SHOWN CALLED ****
09-14 06:36:42.402   931  2694 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
09-14 06:36:42.397  5823  5823 W mdss_fb0: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-14 06:36:42.405   931  2694 I hubconnection: sensorhub said: 'activate 31 enable:1'
09-14 06:36:42.407   931  2694 I hubconnection: sensorhub said: 'batch 7 flags:0, sampling_rate_Hz:4.00, max_report_latency_us:0'
09-14 06:36:42.409   931  2694 I hubconnection: sensorhub said: 'activate 7 enable:1'
,09-14 06:36:42.422   931  2969 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 06:36:42.429  3111  3111 W PathParser: Points are too far apart 4.030360828967057
09-14 06:36:42.429  3111  3111 W PathParser: Points are too far apart 4.030360538880159
,09-14 06:36:42.454  3504  4570 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 1
,09-14 06:36:42.454  3504  4570 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-14 06:36:42.454  3504  4570 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-14 06:36:42.454   528  1258 D         : oem-qmi: Connection accepted
09-14 06:36:42.454   528  1258 D         : oem-qmi: Waiting to accept connection
,09-14 06:36:42.461  3504  4570 D         : oem_qmi_lib:output 0
,09-14 06:36:42.462  3504  4570 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-14 06:36:42.467   931   951 I DisplayPowerController: Unblocked screen on after 81 ms
,09-14 06:36:42.468   931   951 V KeyguardServiceDelegate: onScreenTurnedOn()
,09-14 06:36:42.469   931   951 I DreamManagerService: Gently waking up from dream.
09-14 06:36:42.470   931  3416 I DreamManagerService: Leaving dreamland.
,09-14 06:36:42.470   931   946 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
09-14 06:36:42.471   931   942 I sensors : activate
,09-14 06:36:42.474   931  2694 I hubconnection: sensorhub said: 'activate 21 enable:0'
,09-14 06:36:42.492  3111  3111 W PathParser: Points are too far apart 4.030360828967057
,09-14 06:36:42.493  3111  3111 W PathParser: Points are too far apart 4.030360538880159
,09-14 06:36:42.562   384   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,09-14 06:36:42.563  5827  5827 W irq/504-synapti: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-14 06:36:42.565   384   384 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
09-14 06:36:42.565   931  3080 D SurfaceControl: Excessive delay in setPowerMode(): 168ms
,09-14 06:36:43.451  3111  3111 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME RECENT clock SEARCH quick_settings >
,09-14 06:36:43.464  5496  5496 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-14 06:36:43.465  5496  5496 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
09-14 06:36:43.466  5496  5496 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-14 06:36:43.466  5496  5496 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-14 06:36:43.484   515  2981 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-14 06:36:43.486  3111  3111 D PhoneStatusBar: disable: < expand icons* alerts system_info* back HOME RECENT clock SEARCH quick_settings >
,09-14 06:36:43.497   515  2981 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
,09-14 06:36:43.497   515  2981 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
09-14 06:36:43.499   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-14 06:36:43.507  3523  3523 W Binder_8: type=1400 audit(0.0:128): avc: denied { ioctl } for path="socket:[26391]" dev="sockfs" ino=26391 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:43.510  3523  3523 W Binder_8: type=1400 audit(0.0:129): avc: denied { ioctl } for path="socket:[26391]" dev="sockfs" ino=26391 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:43.512  3111  3111 D PhoneStatusBar: disable: < expand icons alerts system_info back home* recent* clock search* quick_settings >
,09-14 06:36:43.513   515  2981 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-14 06:36:43.516   515  2981 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
09-14 06:36:43.516  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:36:43.513  3551  3551 W Binder_A: type=1400 audit(0.0:130): avc: denied { ioctl } for path="socket:[26390]" dev="sockfs" ino=26390 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:43.513  3551  3551 W Binder_A: type=1400 audit(0.0:131): avc: denied { ioctl } for path="socket:[26390]" dev="sockfs" ino=26390 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:43.521  3623  3623 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,09-14 06:36:44.257   515  2981 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-14 06:36:44.259   515  2981 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-14 06:36:44.270   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-14 06:36:44.574   931  2934 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10200000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (has extras)} from uid 1000 on display 0
,09-14 06:36:44.585   515  2981 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-14 06:36:44.593  5496  5496 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-14 06:36:44.593  5496  5496 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-14 06:36:44.598   515  2981 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
09-14 06:36:44.598   515  2981 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
,09-14 06:36:44.598   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-14 06:36:44.608   515  2981 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-14 06:36:44.611  3534  3534 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10600000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (has extras) })
,09-14 06:36:44.611   515  2981 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-14 06:36:44.630   942   942 W Binder_2: type=1400 audit(0.0:132): avc: denied { ioctl } for path="socket:[16037]" dev="sockfs" ino=16037 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:44.630   942   942 W Binder_2: type=1400 audit(0.0:133): avc: denied { ioctl } for path="socket:[16037]" dev="sockfs" ino=16037 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:44.630   941   941 W Binder_1: type=1400 audit(0.0:134): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:44.630   941   941 W Binder_1: type=1400 audit(0.0:135): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:44.633  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:36:44.652   515  2981 D AudioFlinger: mixer(0xf4500000) throttle end: throttle time(12)
,09-14 06:36:44.874  4824  4824 W LocationOracleImpl: Best location was null
,09-14 06:36:44.876  4824  4824 I VS.Container: create_recognizer
,09-14 06:36:44.890  5496  5496 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@206e11c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@f771742, 16908290=android.view.AbsSavedState$1@f771742}, android:focusedViewId=100}]}]
09-14 06:36:44.890  5496  5496 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-14 06:36:44.890  5496  5496 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-14 06:36:44.890  5496  5496 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-14 06:36:44.953  4824  5879 I MicroRecognitionRnrImpl: Starting detection.
,09-14 06:36:44.955  4824  5880 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@ae36477
,09-14 06:36:44.957   515  2992 D PermissionCache: checking android.permission.CAPTURE_AUDIO_HOTWORD for uid=10029 => granted (225 us)
,09-14 06:36:44.957   515  5882 I AudioFlinger: AudioFlinger's thread 0xf2200000 ready to run
,09-14 06:36:44.961   515  2991 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-14 06:36:44.963  4824  5880 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@ae36477
,09-14 06:36:44.973   515  5882 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,09-14 06:36:44.973   515  5882 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
09-14 06:36:44.974   515  5882 I ACDB-LOADER: ACDB AFE returned = -19
09-14 06:36:44.974   515  5882 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
09-14 06:36:44.974   515  5882 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
09-14 06:36:44.974   515  5882 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,09-14 06:36:44.978   515  5882 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-14 06:36:45.004  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:45.014  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:45.026  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:45.041  3900  4979 W Icing   : Received bad json for section weights override -- ignoring.
,09-14 06:36:45.041  3900  4979 W Icing   : Received bad json for corpus scoring config -- ignoring.
09-14 06:36:45.041  3900  4979 W Icing   : Received bad json for corpus context scoring override -- ignoring.
09-14 06:36:45.042  3900  4979 W Icing   : Received bad json for section weights override -- ignoring.
09-14 06:36:45.042  3900  4979 W Icing   : Received bad json for corpus scoring config -- ignoring.
09-14 06:36:45.042  3900  4979 W Icing   : Received bad json for corpus context scoring override -- ignoring.
,09-14 06:36:45.045  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:45.053  4824  4824 I HotwordWorkerImpl: onReady
,09-14 06:36:45.123   515  2981 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-14 06:36:45.124   515  2981 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-14 06:36:45.137   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-14 06:36:45.152  3534  3835 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,09-14 06:36:45.283   931  3415 I ActivityManager: START u0 {act=com.android.systemui.recents.SHOW_RECENTS flg=0x10804000 cmp=com.android.systemui/.recents.RecentsActivity} from uid 10027 on display 0
,09-14 06:36:45.293   515  2981 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
09-14 06:36:45.294  4824  4834 W SearchService: Abort, client detached.
,09-14 06:36:45.297  4824  4824 I HotwordDetector: Closing mic
09-14 06:36:45.297  4824  5877 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@ae36477
,09-14 06:36:45.297  4824  5880 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-14 06:36:45.367  3551  3551 W Binder_A: type=1400 audit(0.0:136): avc: denied { ioctl } for path="socket:[16055]" dev="sockfs" ino=16055 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:45.367  3551  3551 W Binder_A: type=1400 audit(0.0:137): avc: denied { ioctl } for path="socket:[16055]" dev="sockfs" ino=16055 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:45.373   515  5882 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-14 06:36:45.374   515  5882 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,09-14 06:36:45.380   515  5882 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,09-14 06:36:45.380   515  5882 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
09-14 06:36:45.380   515  2991 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-14 06:36:45.380   515  2981 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
09-14 06:36:45.380   515  2981 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
09-14 06:36:45.380   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-14 06:36:45.384  4824  5879 I MicroRecognitionRnrImpl: Detection finished
09-14 06:36:45.385  4824  5878 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-14 06:36:45.390   515  2981 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-14 06:36:45.392   515  2981 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-14 06:36:45.403  3551  3551 W Binder_A: type=1400 audit(0.0:138): avc: denied { ioctl } for path="socket:[16771]" dev="sockfs" ino=16771 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:45.403  3551  3551 W Binder_A: type=1400 audit(0.0:139): avc: denied { ioctl } for path="socket:[16771]" dev="sockfs" ino=16771 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:45.410  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:36:45.407  3415  3415 W Binder_5: type=1400 audit(0.0:140): avc: denied { ioctl } for path="socket:[16770]" dev="sockfs" ino=16770 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:45.407  3415  3415 W Binder_5: type=1400 audit(0.0:141): avc: denied { ioctl } for path="socket:[16770]" dev="sockfs" ino=16770 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:45.411   931   949 I ActivityManager: Displayed com.android.systemui/.recents.RecentsActivity: +121ms
,09-14 06:36:45.433   515  2981 D AudioFlinger: mixer(0xf4500000) throttle end: throttle time(12)
,09-14 06:36:45.923   515  2981 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-14 06:36:45.925   515  2981 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-14 06:36:45.936   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-14 06:36:46.086  5803  5803 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 06:36:46.087  5803  5803 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 06:36:46.089  5803  5803 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 06:36:46.096   931  3415 I ActivityManager: Killing 5496:com.test.thalitest/u0a77 (adj 9): remove task
,09-14 06:36:46.096  5496  5496 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-14 06:36:46.097  5496  5496 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,09-14 06:36:46.130   931  2969 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-14 06:36:46.161   931  3149 I WindowState: WIN DEATH: Window{ba2f49c u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-14 06:36:46.162   931  3523 D GraphicsStats: Buffer count: 2
09-14 06:36:46.162   931  2970 D WifiService: Client connection lost with reason: 4
,09-14 06:36:46.176   931  2969 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-14 06:36:46.176   931  2969 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 06:36:46.184   931  2969 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-14 06:36:46.212   931  2969 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-14 06:36:46.213  5803  5803 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 06:36:46.496   931  3551 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10200000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 10027 on display 0
,09-14 06:36:46.502   931  3417 I ActivityManager: Killing 5548:com.android.settings/1000 (adj 9): remove task
,09-14 06:36:46.535  3534  3534 I GEL     : handleIntent(Intent { act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10600000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL })
,09-14 06:36:46.557   941   941 W Binder_1: type=1400 audit(0.0:142): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:46.557   941   941 W Binder_1: type=1400 audit(0.0:143): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:46.558  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:36:46.579  4824  4824 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,09-14 06:36:46.597  4824  4824 W LocationOracleImpl: Best location was null
,09-14 06:36:46.606  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:46.621  4824  5919 I MicroRecognitionRnrImpl: Starting detection.
,09-14 06:36:46.622  4824  5920 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@3264fd2
,09-14 06:36:46.623   515  5922 I AudioFlinger: AudioFlinger's thread 0xf2200000 ready to run
,09-14 06:36:46.627  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:46.628   515  2991 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-14 06:36:46.629  4824  5920 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@3264fd2
,09-14 06:36:46.639   515  5922 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
,09-14 06:36:46.640   515  5922 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
09-14 06:36:46.640   515  5922 I ACDB-LOADER: ACDB AFE returned = -19
09-14 06:36:46.640   515  5922 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
09-14 06:36:46.640   515  5922 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
09-14 06:36:46.640   515  5922 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,09-14 06:36:46.643  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:46.647   515  5922 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-14 06:36:46.649  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:46.665  5803  5803 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 06:36:46.687  5803  5803 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-14 06:36:46.687  5803  5803 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-14 06:36:46.690   931  2969 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-14 06:36:46.690   931  2969 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 06:36:46.691   931  2971 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-14 06:36:46.715   931  2969 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 06:36:46.722   510   930 D CommandListener: Setting iface cfg
09-14 06:36:46.725   931  2969 D WifiStateMachine: Start Dhcp Watchdog 2
09-14 06:36:46.725  4824  4824 I HotwordWorkerImpl: onReady
,09-14 06:36:46.729   931  5928 D DhcpClient: Receive thread started
,09-14 06:36:46.732   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-14 06:36:46.732   931  2969 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-14 06:36:46.733   931  2971 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-14 06:36:46.811   931  2969 E native  : do suspend false
,09-14 06:36:46.819   931  5927 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 06:36:46.832   931  5928 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172567, domain null
,09-14 06:36:46.832   931  5927 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172567 seconds
09-14 06:36:46.833   931  5927 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-14 06:36:46.845   931  5928 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-14 06:36:46.845   931  5927 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-14 06:36:46.846   510   930 D CommandListener: Setting iface cfg
,09-14 06:36:46.847   931  2969 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 06:36:46.849   931  5927 D DhcpClient: Scheduling renewal in 86399s
,09-14 06:36:46.855   931  2969 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-14 06:36:46.855   931  2969 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 06:36:46.855   931  2971 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-14 06:36:46.856   931  2969 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-14 06:36:46.856   931  2971 D ConnectivityService: Adding iface wlan0 to network 101
,09-14 06:36:46.884   931  2971 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-14 06:36:46.884   931  2971 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-14 06:36:46.885   931  2971 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-14 06:36:46.886   931  2971 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-14 06:36:46.887   931  2971 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-14 06:36:46.892   931  2971 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:36:46.894   931  2971 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-14 06:36:46.895   931  2971 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-14 06:36:46.895   931  2971 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-14 06:36:46.895   931  2969 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-14 06:36:46.895   931  2971 D ConnectivityService:    accepting network in place of null
09-14 06:36:46.895   931  2969 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 06:36:46.895   931  2971 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 06:36:46.901   931  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273741, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 06:36:46.914   510   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 06:36:46.932   510   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 06:36:46.935   931  2971 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-14 06:36:46.935   931  2971 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:36:46.935  3478  3674 W QCNEJ   : |CORE| network available: 101
09-14 06:36:46.936  3478  3674 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-14 06:36:46.936   931  2971 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-14 06:36:46.936   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-14 06:36:46.937  3478  3674 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-14 06:36:46.937  3478  3674 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-14 06:36:46.945  4882  4897 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-14 06:36:46.945  4882  4897 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-14 06:36:46.946  4882  4897 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,09-14 06:36:46.946  4882  4897 E SarControlService: no key has been found,reset the power
,09-14 06:36:46.949  4882  4923 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-14 06:36:46.949  4882  4923 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-14 06:36:46.949  4882  4923 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-14 06:36:46.950  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:36:46.950  4911  4911 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-14 06:36:46.952  4882  4923 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-14 06:36:46.952  4882  4923 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-14 06:36:46.952  4882  4923 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-14 06:36:46.952  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-14 06:36:46.952  4911  4911 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-14 06:36:46.959  3900  3900 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-14 06:36:46.960  3900  5193 I iu.UploadsManager: num queued entries: 0
,09-14 06:36:46.961  4911  4925 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2cee3d8 HexData = [00000000ec03000000000000ffffffff]
09-14 06:36:46.961  4911  4925 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:36:46.961  4911  4925 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-14 06:36:46.961  3900  5193 I iu.UploadsManager: num updated entries: 0
09-14 06:36:46.961  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:36:46.961  4911  4925 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2cee3d8 HexData = [00000000ed03000000000000ffffffff]
09-14 06:36:46.961  4911  4925 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-14 06:36:46.961  4911  4925 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,09-14 06:36:46.962  4882  4894 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-14 06:36:46.962  4911  4911 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-14 06:36:46.962  3900  5193 I iu.SyncManager: NEXT; no task
09-14 06:36:46.962  4882  4895 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-14 06:36:46.966  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 06:36:46.967  3900  3900 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-14 06:36:46.969  5621  5621 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 06:36:46.973  5621  5621 D SprintDMHelper: simOperator: 
09-14 06:36:46.973  5621  5621 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 06:36:46.978   931  5925 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-14 06:36:46.994   931  3151 I ActivityManager: Start proc 5944:com.test.thalitest/u0a77 for broadcast com.test.thalitest/io.jxcore.node.ConnectivityChangeListener
,09-14 06:36:47.047   931  5925 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 14 Sep 2016 10:36:47 GMT], X-Android-Received-Millis=[1473849407046], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473849407016]}
,09-14 06:36:47.047   931  2971 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-14 06:36:47.047   931  2971 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-14 06:36:47.048   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-14 06:36:47.048   931  2971 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 06:36:47.071  3534  3835 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,09-14 06:36:47.077  4295  5941 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
,09-14 06:36:47.093  4824  4824 I HotwordDetector: Closing mic
,09-14 06:36:47.093  4824  5877 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3264fd2
09-14 06:36:47.093  4824  5920 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-14 06:36:47.106   515  2981 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-14 06:36:47.139  5944  5944 D jxcore_app_log: JniHelper::setJavaVM(0xf4efc000), pthread_self() = -150197452
,09-14 06:36:47.140  5944  5944 E JX-Cordova: JXcore wasn't initialized yet
,09-14 06:36:47.143  3416  3416 W Binder_6: type=1400 audit(0.0:144): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:47.143  3416  3416 W Binder_6: type=1400 audit(0.0:145): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:47.145  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:36:47.158   515  5922 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-14 06:36:47.159   515  5922 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,09-14 06:36:47.162   515  5922 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,09-14 06:36:47.162   515  5922 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
,09-14 06:36:47.164   515  2991 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-14 06:36:47.167   515  2981 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
,09-14 06:36:47.167   515  2981 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
09-14 06:36:47.167   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
09-14 06:36:47.168  4824  5919 I MicroRecognitionRnrImpl: Detection finished
09-14 06:36:47.168  4824  5878 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-14 06:36:47.178   515  2981 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-14 06:36:47.181   515  2981 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-14 06:36:47.495   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:47.710   515  2981 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-14 06:36:47.712   515  2981 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-14 06:36:47.721   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-14 06:36:47.936   931  2971 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-14 06:36:48.496   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:48.630   931  2969 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{4}, ntable=[192.168.1.1/NUD_REACHABLE]
,09-14 06:36:48.635   931  2971 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:36:48.640  3478  3674 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-14 06:36:48.641  3478  3674 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [192.168.1.113/24,fe80::6283:34ff:fe25:d762/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-14 06:36:49.496   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:49.737   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:36:49.819  3534  3835 W OpenGLRenderer: Incorrectly called buildLayer on View: FrameLayout, destroying layer...
,09-14 06:36:50.497   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:50.566   931  3417 I ActivityManager: START u0 {act=android.intent.action.DELETE dat=package:com.test.thalitest flg=0x10800000 cmp=com.google.android.packageinstaller/com.android.packageinstaller.UninstallerActivity (has extras)} from uid 10029 on display 0
,09-14 06:36:50.609   931  3543 I ActivityManager: Start proc 5989:com.google.android.packageinstaller/u0a17 for activity com.google.android.packageinstaller/com.android.packageinstaller.UninstallerActivity
,09-14 06:36:50.646  5989  5989 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
,09-14 06:36:50.717   714   714 W Binder_3: type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[26490]" dev="sockfs" ino=26490 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:50.717   714   714 W Binder_3: type=1400 audit(0.0:147): avc: denied { ioctl } for path="socket:[26490]" dev="sockfs" ino=26490 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:50.723  5989  6001 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-14 06:36:50.720   407   407 W Binder_2: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[33460]" dev="sockfs" ino=33460 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:50.720   407   407 W Binder_2: type=1400 audit(0.0:149): avc: denied { ioctl } for path="socket:[33460]" dev="sockfs" ino=33460 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:50.727  3523  3523 W Binder_8: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[26495]" dev="sockfs" ino=26495 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:50.727  3523  3523 W Binder_8: type=1400 audit(0.0:151): avc: denied { ioctl } for path="socket:[26495]" dev="sockfs" ino=26495 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:50.733  3415  3415 W Binder_5: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[26497]" dev="sockfs" ino=26497 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:50.733  3415  3415 W Binder_5: type=1400 audit(0.0:153): avc: denied { ioctl } for path="socket:[26497]" dev="sockfs" ino=26497 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:50.756  5989  6001 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-14 06:36:50.756  5989  6001 I Adreno  : Build Date                       : 12/06/15
09-14 06:36:50.756  5989  6001 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 06:36:50.756  5989  6001 I Adreno  : Local Branch                     : mybranch17112971
09-14 06:36:50.756  5989  6001 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-14 06:36:50.756  5989  6001 I Adreno  : Remote Branch                    : NONE
09-14 06:36:50.756  5989  6001 I Adreno  : Reconstruct Branch               : NOTHING
,09-14 06:36:50.761  5989  6001 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 06:36:50.808   931   949 I ActivityManager: Displayed com.google.android.packageinstaller/com.android.packageinstaller.UninstallerActivity: +210ms
,09-14 06:36:50.955  3534  3835 W OpenGLRenderer: Incorrectly called buildLayer on View: FrameLayout, destroying layer...
,09-14 06:36:51.498   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:36:52.498   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 06:36:53.506   515  2981 D audio_hw_primary: out_set_parameters: enter: usecase(1: low-latency-playback) kvpairs: routing=2
,09-14 06:36:53.509   931  3415 I ActivityManager: START u0 {act=android.intent.action.VIEW cmp=com.google.android.packageinstaller/com.android.packageinstaller.UninstallAppProgress (has extras)} from uid 10017 on display 0
09-14 06:36:53.519   515  2981 D audio_hw_primary: select_devices: out_snd_device(2: speaker) in_snd_device(0: none)
,09-14 06:36:53.519   515  2981 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(2) acdb_id(15)
,09-14 06:36:53.520   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 1
,09-14 06:36:53.533   515  2981 D audio_hw_primary: enable_snd_device: snd_device(2: speaker)
,09-14 06:36:53.537   515  2981 D audio_hw_primary: enable_audio_route: apply and update mixer path: low-latency-playback speaker
,09-14 06:36:53.561   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-14 06:36:53.562   931   944 I ActivityManager: Killing 5944:com.test.thalitest/u0a77 (adj 11): stop com.test.thalitest
09-14 06:36:53.560   942   942 W Binder_2: type=1400 audit(0.0:154): avc: denied { ioctl } for path="socket:[14161]" dev="sockfs" ino=14161 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:53.560   942   942 W Binder_2: type=1400 audit(0.0:155): avc: denied { ioctl } for path="socket:[14161]" dev="sockfs" ino=14161 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:53.586   931  3543 W ActivityManager: Spurious death for ProcessRecord{935136e 0:com.test.thalitest/u0a77}, curProc for 5944: null
,09-14 06:36:53.667   931   954 I art     : Starting a blocking GC Explicit
,09-14 06:36:53.700  3417  3417 W Binder_7: type=1400 audit(0.0:156): avc: denied { ioctl } for path="socket:[35387]" dev="sockfs" ino=35387 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:53.700  3417  3417 W Binder_7: type=1400 audit(0.0:157): avc: denied { ioctl } for path="socket:[35387]" dev="sockfs" ino=35387 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:53.702   931   949 I ActivityManager: Displayed com.google.android.packageinstaller/com.android.packageinstaller.UninstallAppProgress: +176ms
,09-14 06:36:53.703  3543  3543 W Binder_9: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[35386]" dev="sockfs" ino=35386 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:53.703  3543  3543 W Binder_9: type=1400 audit(0.0:159): avc: denied { ioctl } for path="socket:[35386]" dev="sockfs" ino=35386 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:53.708  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:36:53.741   931   954 I art     : Explicit concurrent mark sweep GC freed 15041(952KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.500ms total 74.141ms
,09-14 06:36:53.762   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-14 06:36:53.779   931   954 I ActivityManager: Start proc 6009:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-14 06:36:53.779   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-14 06:36:53.785  5748  5748 D BluetoothMapAppObserver: onReceive
09-14 06:36:53.786  5748  5748 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-14 06:36:53.791  3623  3950 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-14 06:36:53.794  3397  3397 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-14 06:36:53.801   931  2935 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-14 06:36:53.811   931   944 I ActivityManager: Start proc 6023:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-14 06:36:53.814  3504  3504 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-14 06:36:53.824  3397  6021 I Keyboard.Facilitator.DecoderInitializer: run()
,09-14 06:36:53.830  3397  6021 I Decoder : createOrResetDecoder
,09-14 06:36:53.833   942   942 W Binder_2: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[34040]" dev="sockfs" ino=34040 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:36:53.833   942   942 W Binder_2: type=1400 audit(0.0:161): avc: denied { ioctl } for path="socket:[34040]" dev="sockfs" ino=34040 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:53.843   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-14 06:36:53.871  3585  3585 I ConfigService: onCreate
,09-14 06:36:53.885  6023  6023 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,09-14 06:36:53.897  3397  6021 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-14 06:36:53.899  5989  6001 V RenderScript: 0x7f8dd10000 Launching thread(s), CPUs 8
,09-14 06:36:53.903  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:36:53.903  4824  4833 I art     : Background partial concurrent mark sweep GC freed 6486(379KB) AllocSpace objects, 6(1384KB) LOS objects, 40% free, 23MB/39MB, paused 1.431ms total 111.970ms
09-14 06:36:53.900  3417  3417 W Binder_7: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:53.900  3417  3417 W Binder_7: type=1400 audit(0.0:163): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:36:53.923  4824  4824 W ThreadPoolDumper: Queue length for executor AudioRouter with 1 threads is now 8. Perhaps some tasks are too long, or the pool is too small.
,09-14 06:36:53.934  4824  4824 W LocationOracleImpl: Best location was null
,09-14 06:36:53.949  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:53.961  4824  6052 I MicroRecognitionRnrImpl: Starting detection.
,09-14 06:36:53.961  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:53.962  4824  6053 I MicrophoneInputStream: mic_starting com.google.android.apps.gsa.speech.audio.x@417d377
,09-14 06:36:53.963   515  6056 I AudioFlinger: AudioFlinger's thread 0xf2200000 ready to run
,09-14 06:36:53.966   515  2991 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-14 06:36:53.967  3623  3923 W GCoreFlp: No location to return for getLastLocation()
09-14 06:36:53.968  4824  6053 I MicrophoneInputStream: mic_started com.google.android.apps.gsa.speech.audio.x@417d377
,09-14 06:36:53.976  3397  6021 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-14 06:36:53.979  3397  6021 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-14 06:36:53.979  3397  6021 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-14 06:36:53.979  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:53.986  3397  6021 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-14 06:36:53.986  3397  6021 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-14 06:36:53.986  3397  6021 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-14 06:36:53.986  3397  6021 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-14 06:36:53.991  3397  6021 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-14 06:36:53.991  3397  6021 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-14 06:36:53.991  3397  6021 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-14 06:36:53.992  3397  6021 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-14 06:36:53.992  3397  6021 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-14 06:36:53.992  3397  6021 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-14 06:36:54.021  6023  6023 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm64
,09-14 06:36:54.035  6023  6060 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-14 06:36:54.044   931   942 I ActivityManager: Start proc 6061:com.android.musicfx/u0a21 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-14 06:36:54.059   515  2981 D audio_hw_primary: disable_audio_route: reset and update mixer path: low-latency-playback speaker
,09-14 06:36:54.060   515  2981 D audio_hw_primary: disable_snd_device: snd_device(2: speaker)
,09-14 06:36:54.069   515  2981 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x2 of type 0 for Event 0
,09-14 06:36:54.069   515  6056 D audio_hw_primary: select_devices: out_snd_device(0: none) in_snd_device(63: voice-rec-mic)
09-14 06:36:54.069   515  6056 D msm8974_platform: platform_send_audio_calibration: sending audio calibration for snd_device(63) acdb_id(62)
09-14 06:36:54.069   515  6056 I ACDB-LOADER: ACDB AFE returned = -19
09-14 06:36:54.069   515  6056 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 1
09-14 06:36:54.069   515  6056 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 1, rx 0, concurrency session_allowed 0
09-14 06:36:54.069   515  6056 D audio_hw_primary: enable_snd_device: snd_device(63: voice-rec-mic)
,09-14 06:36:54.075   515  6056 D audio_hw_primary: enable_audio_route: apply and update mixer path: audio-record
,09-14 06:36:54.081  6061  6061 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm64
,09-14 06:36:54.097  3585  3585 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-14 06:36:54.097  3585  3585 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-14 06:36:54.108  3900  6076 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-14 06:36:54.109  3900  6076 D AccountUtils: Clearing selected account for com.test.thalitest
,09-14 06:36:54.119  3900  6076 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-14 06:36:54.122  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-14 06:36:54.122  3900  3900 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-14 06:36:54.129  3900  3900 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-14 06:36:54.129  3900  3900 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-14 06:36:54.135  3900  6081 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
,09-14 06:36:54.135  3900  6081 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
09-14 06:36:54.136  3900  6081 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
09-14 06:36:54.136  3900  6081 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,09-14 06:36:54.141  3900  6081 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 1
,09-14 06:36:54.141  3900  6081 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 2
,09-14 06:36:54.141  3900  6081 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db: 1
,09-14 06:36:54.142   931  3738 I ActivityManager: Start proc 6084:com.google.android.gms.wearable/u0a12 for service com.google.android.gms/.wearable.service.WearableControlService
09-14 06:36:54.147  3900  6081 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
09-14 06:36:54.147  3900  6081 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 2
09-14 06:36:54.148  3900  6081 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db: 1
09-14 06:36:54.149  3900  6081 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 0
09-14 06:36:54.149  3900  6081 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/help_responses.db, release reference: 0
09-14 06:36:54.149  3900  6081 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/user/0/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,09-14 06:36:54.152  4824  6091 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-14 06:36:54.155  6023  6058 I ContactLocale: AddressBook Labels [en-US]: [, A, B, C, D, E, F, G, H, I, J, K, L, M, N, O, P, Q, R, S, T, U, V, W, X, Y, Z, Α, Β, Γ, Δ, Ε, Ζ, Η, Θ, Ι, Κ, Λ, Μ, Ν, Ξ, Ο, Π, Ρ, Σ, Τ, Υ, Φ, Χ, Ψ, Ω, , А, Б, В, Г, Д, Ђ, Е, Є, Ж, З, И, І, Й, Ј, К, Л, Љ, М, Н, Њ, О, П, Р, С, Т, Ћ, У, Ф, Х, Ц, Ч, Џ, Ш, Щ, Ю, Я, , א, ב, ג, ד, ה, ו, ז, ח, ט, י, כ, ל, מ, נ, ס, ע, פ, צ, ק, ר, ש, ת, , ا, ب, ت, ث, ج, ح, خ, د, ذ, ر, ز, س, ش, ص, ض, ط, ظ, ع, غ, ف, ق, ك, ل, م, ن, ه, و, ي, , ก, ข, ฃ, ค, ฅ, ฆ, ง, จ, ฉ, ช, ซ, ฌ, ญ, ฎ, ฏ, ฐ, ฑ, ฒ, ณ, ด, ต, ถ, ท, ธ, น, บ, ป, ผ, ฝ, พ, ฟ, ภ, ม, ย, ร, ฤ, ล, ฦ, ว, ศ, ษ, ส, ห, ฬ, อ, ฮ, , ㄱ, ㄴ, ㄷ, ㄹ, ㅁ, ㅂ, ㅅ, ㅇ, ㅈ, ㅊ, ㅋ, ㅌ, ㅍ, ㅎ, , あ, か, さ, た, な, は, ま, や, ら, わ, #, ]
09-14 06:36:54.158  4824  4824 I HotwordWorkerImpl: onReady
09-14 06:36:54.176   931  3416 I ActivityManager: Start proc 6098:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-14 06:36:54.190  3900  6082 W BaseAppContext: Using Auth Proxy for data requests.
09-14 06:36:54.195  3900  6082 W BaseAppContext: Using Auth Proxy for data requests.
09-14 06:36:54.198  3900  6112 I GMPM-SVC: App measurement is starting up
09-14 06:36:54.201  6084  6084 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
09-14 06:36:54.202  3900  6112 E GMPM-SVC: AppMeasurementService not registered/enabled
09-14 06:36:54.202  3900  3900 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
09-14 06:36:54.203  3900  6112 E GMPM-SVC: Uploading is not possible. App measurement disabled
09-14 06:36:54.210  6098  6098 W System  : ClassLoader referenced unknown path: /system/app/KeyChain/lib/arm64
09-14 06:36:54.213  6084  6084 I MultiDex: VM with version 2.1.0 has multidex support
09-14 06:36:54.213  6084  6084 I MultiDex: install
09-14 06:36:54.213  6084  6084 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-14 06:36:54.214  6098  6098 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2725 
09-14 06:36:54.217   931  3415 D ConnectivityService: listenForNetwork for Listen from uid/pid:10012/3900 for NetworkRequest [ id=5, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-14 06:36:54.228  3900  3900 I ConfigFetchService: service connected
09-14 06:36:54.228  3900  6121 I PeopleContactsSync: CP2 sync disabled
09-14 06:36:54.230   931   931 I ActivityManager: Start proc 6119:com.android.documentsui/u0a42 for broadcast com.android.documentsui/.PackageReceiver
09-14 06:36:54.234  3900  4795 I Icing   : doRemovePackageData com.test.thalitest
09-14 06:36:54.261  4824  6091 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,09-14 06:36:54.266  6119  6119 W System  : ClassLoader referenced unknown path: /system/app/DocumentsUI/lib/arm64
,09-14 06:36:54.271  6084  6084 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,09-14 06:36:54.283  3900  6080 W DriveInitializer: Awaiting to be initialized
,09-14 06:36:54.284  3900  6133 W DriveInitializer: Background init thread started
,09-14 06:36:54.290  6084  6084 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-14 06:36:54.310   931  3415 I ActivityManager: Killing 4863:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-14 06:36:54.338  6084  6134 D NativeLibraryUtils: Install completed successfully. count=17 extracted=0
,09-14 06:36:54.342   931  3415 I ActivityManager: Killing 5394:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-14 06:36:54.382   931   942 I ActivityManager: Start proc 6143:com.android.externalstorage/u0a10 for content provider com.android.externalstorage/.ExternalStorageProvider
,09-14 06:36:54.394  3585  6158 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,09-14 06:36:54.401   931  3543 I ActivityManager: Killing 5411:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-14 06:36:54.416  3900  6133 W DriveInitializer: Background init thread ended
,09-14 06:36:54.418  3534  3835 W OpenGLRenderer: Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,09-14 06:36:54.433  3585  3585 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-14 06:36:54.441  3585  3585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 06:36:54.443  3585  3585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-14 06:36:54.444  3900  3900 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-14 06:36:54.450  6143  6143 W System  : ClassLoader referenced unknown path: /system/priv-app/ExternalStorageProvider/lib/arm64
,09-14 06:36:54.473  6143  6143 D ExternalStorage: After updating volumes, found 1 active roots
,09-14 06:36:54.480  6084  6084 D WearableService: callingUid 10012, callindPid: 6084
,09-14 06:36:54.490  3900  6166 D LocationInitializer: Restart initialization of location
,09-14 06:36:54.503  3623  6163 E MDM     : [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-14 06:36:54.510  3623  3923 W GCoreFlp: No location to return for getLastLocation()
,09-14 06:36:54.510  3585  6167 W FusedLocationProvider: location=null
,09-14 06:36:54.531  6023  6058 D ContactDirectoryManager: Found com.google.contacts.gal.provider
,09-14 06:36:54.531  6023  6058 D ContactDirectoryManager: Found com.google.android.gm.exchange.directory.provider
,09-14 06:36:54.536   931   941 I ActivityManager: Start proc 6170:com.android.shell/2000 for content provider com.android.shell/.BugreportStorageProvider
,09-14 06:36:54.549   931  3149 I ActivityManager: Start proc 6182:com.google.android.gm.exchange/u0a67 for content provider com.google.android.gm.exchange/com.android.exchange.provider.ExchangeDirectoryProvider
,09-14 06:36:54.569  6170  6170 W System  : ClassLoader referenced unknown path: /system/priv-app/Shell/lib/arm64
,09-14 06:36:54.570   931  3551 I ActivityManager: Killing 4556:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-14 06:36:54.603  6182  6182 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltExchange3Google/lib/arm64
,09-14 06:36:54.635   931  3151 I ActivityManager: Start proc 6196:com.google.android.gm/u0a68 for content provider com.google.android.gm/com.android.email.provider.EmailProvider
,09-14 06:36:54.655   931  3417 I ActivityManager: Start proc 6208:com.google.process.gapps/u0a46 for content provider com.google.android.syncadapters.contacts/.GalProvider
,09-14 06:36:54.659   931  3415 I ActivityManager: Killing 5566:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,09-14 06:36:54.689   931   941 I ActivityManager: Killing 5662:com.google.android.apps.gcs/u0a11 (adj 15): empty #17
,09-14 06:36:54.708  6196  6196 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltGmail/lib/arm64
,09-14 06:36:54.726  6119  6132 D Documents: Update found 7 roots in 438ms
,09-14 06:36:54.742  6208  6208 W System  : ClassLoader referenced unknown path: /system/app/GoogleContactsSyncAdapter/lib/arm64
,09-14 06:36:54.778  6208  6208 I GoogleHttpClient: GMS http client unavailable, use old client
,09-14 06:36:54.805  6023  6058 I ContactDirectoryManager: deleted 0 stale rows which don't have any relevant directory
,09-14 06:36:54.814  6196  6227 D ActivityThread: Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,09-14 06:36:54.823  6119  6165 D Documents: Update found 7 roots in 337ms
,09-14 06:36:54.857  6023  6058 I ContactDirectoryManager: Discovered 0 contact directories in 445ms
,09-14 06:36:54.895   931  2971 D ConnectivityService: handlePromptUnvalidated 101
,09-14 06:36:54.928  6196  6196 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-14 06:36:54.945  6196  6226 I Gmail   : getAccountsCursor
,09-14 06:36:54.969  6196  6237 E Gmail   : Error finding the version of the Email provider.....
09-14 06:36:54.969  6196  6237 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
09-14 06:36:54.969  6196  6237 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
09-14 06:36:54.969  6196  6237 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1280)
09-14 06:36:54.969  6196  6237 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
09-14 06:36:54.969  6196  6237 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-14 06:36:54.969  6196  6237 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 06:36:54.969  6196  6237 E Gmail   : 	at android.os.Looper.loop(Looper.java:148)
09-14 06:36:54.969  6196  6237 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-14 06:36:54.969  6196  6237 W EmailMigration: We do not support migrating this version of the Email provider.
,09-14 06:36:54.979  3585  3585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 06:36:55.055  3585  3585 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 06:36:55.092   931  3523 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,09-14 06:36:55.129  6182  6182 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-14 06:36:55.148  6182  6182 I Exchange: EasService.onCreate
,09-14 06:36:55.151  6196  6244 I Gmail   : Observing account changes for notifications
,09-14 06:36:55.161  6182  6247 I Exchange: RestartPingTask
,09-14 06:36:55.175  6182  6182 I Exchange: RestartPingsTask did not start any pings.
,09-14 06:36:55.175  6182  6182 I Exchange: PSS stopIfIdle
09-14 06:36:55.175  6182  6182 I Exchange: PSS has no active accounts; stopping service.
,09-14 06:36:55.179  6182  6182 I Exchange: onDestroy
,09-14 06:36:55.262  3900  4795 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
,09-14 06:36:55.339  3900  4795 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,09-14 06:36:57.900   931  2969 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 14 -> obsolete
,09-14 06:36:58.796   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:36:59.253  3585  3585 I ConfigService: onDestroy
,09-14 06:36:59.965  6196  6232 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-14 06:37:00.150  6182  6246 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-14 06:37:01.833   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:09.206  4680  4741 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,09-14 06:37:09.207  4680  4680 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,09-14 06:37:10.616  5803  5803 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-14 06:37:12.499   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:37:13.501   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:37:13.934   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:14.502   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:37:15.504   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:37:16.505   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:37:16.968   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:17.506   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 06:37:23.024   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:26.862   931  2969 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-14 06:37:30.938   931  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=317777, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 06:37:32.102   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:38.173   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:42.507   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 06:37:42.507   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:37:47.267   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:53.904  3397  6021 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-14 06:37:53.904  3397  6021 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-14 06:37:53.934   931  3738 I ActivityManager: Killing 5633:com.android.chrome/u0a39 (adj 15): empty #17
,09-14 06:37:53.967   931  3738 I ActivityManager: Killing 5621:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #18
,09-14 06:37:53.986  3585  3585 I ConfigService: onCreate
,09-14 06:37:56.332   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:37:57.509   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:37:58.185   931  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=345024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 06:37:58.510   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:37:59.011  3585  3585 I ConfigService: onDestroy
,09-14 06:37:59.511   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:00.513   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:01.514   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:02.515   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:38:05.423   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:38:06.866   931  2969 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-14 06:38:07.516   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:08.452   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:38:08.518   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:09.519   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:10.520   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:11.521   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:12.522   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:38:22.523   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:23.525   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:24.528   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:25.529   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:26.530   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:26.868   931  2969 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-14 06:38:27.531   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 06:38:35.733   931  2971 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 06:38:41.692   931  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=388530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 06:38:42.533   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:43.532  3623  5836 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-14 06:38:43.534   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:44.535   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:45.537   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:46.539   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:38:47.540   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 06:38:56.972   931  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=403811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 06:38:58.878   931   951 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
09-14 06:38:58.883  3543  3543 W Binder_9: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:38:58.883  3543  3543 W Binder_9: type=1400 audit(0.0:165): avc: denied { ioctl } for path="socket:[16036]" dev="sockfs" ino=16036 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:38:58.886  3397  3397 I Keyboard.Facilitator: onFinishInput()
,09-14 06:38:59.386  4824  4835 W SearchService: Abort, client detached.
,09-14 06:38:59.391  4824  4824 I HotwordDetector: Closing mic
,09-14 06:38:59.392  4824  5877 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@417d377
09-14 06:38:59.392  4824  6053 E AudioRecord-JNI: Error -4 during AudioRecord native read
,09-14 06:38:59.424   931   951 I sensors : batch
,09-14 06:38:59.425   931   951 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-14 06:38:59.430   931   951 I sensors : activate
09-14 06:38:59.432   931  2694 I hubconnection: sensorhub said: 'batch 31 flags:0, sampling_rate_Hz:15.00, max_report_latency_us:0'
,09-14 06:38:59.432   384   384 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x7f91f43c00
09-14 06:38:59.432   931   949 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-14 06:38:59.432   384   384 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-14 06:38:59.436   931  2694 I hubconnection: sensorhub said: 'activate 7 enable:0'
,09-14 06:38:59.460   515  6056 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
,09-14 06:38:59.461   515  6056 D audio_hw_primary: disable_snd_device: snd_device(63: voice-rec-mic)
,09-14 06:38:59.464   515  6056 I soundtrigger: audio_extn_sound_trigger_update_device_status: device 0x3f of type 1 for Event 0
,09-14 06:38:59.464   515  6056 D sound_trigger_platform: platform_stdev_check_and_update_concurrency: concurrency active 0, tx 0, rx 0, concurrency session_allowed 1
09-14 06:38:59.465   515  2991 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
,09-14 06:38:59.469  4824  6052 I MicroRecognitionRnrImpl: Detection finished
,09-14 06:38:59.470  4824  5878 I MicroRecognitionRnrImpl: Stopping hotword detection.
,09-14 06:38:59.478   931  3523 I ActivityManager: Killing 4295:com.google.android.talk/u0a53 (adj 15): empty #17
,09-14 06:38:59.500   931  3523 I ActivityManager: Killing 5649:com.google.android.apps.photos/u0a62 (adj 15): empty #18
,09-14 06:38:59.747   384   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-14 06:38:59.751   384   384 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-14 06:38:59.753   931  3080 D SurfaceControl: Excessive delay in setPowerMode(): 321ms
,09-14 06:38:59.761   931   951 I DreamManagerService: Entering dreamland.
,09-14 06:38:59.761   931   951 I PowerManagerService: Dozing...
,09-14 06:38:59.762   931   946 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-14 06:38:59.783   942   942 W Binder_2: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[37013]" dev="sockfs" ino=37013 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-14 06:38:59.783   942   942 W Binder_2: type=1400 audit(0.0:167): avc: denied { ioctl } for path="socket:[37013]" dev="sockfs" ino=37013 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-14 06:38:59.784   931  3151 I sensors : batch
09-14 06:38:59.785   931  3151 I sensors : activate
,09-14 06:38:59.788   931  2694 I hubconnection: sensorhub said: 'batch 21 flags:0, sampling_rate_Hz:1000.00, max_report_latency_us:0'
,09-14 06:38:59.791   931  2694 I hubconnection: sensorhub said: 'activate 21 enable:1'
,09-14 06:38:59.793   931   931 I sensors : activate
,09-14 06:38:59.795   515  3364 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-14 06:38:59.800   931  2694 I hubconnection: sensorhub said: 'activate 31 enable:0'
,09-14 06:38:59.804   931  2969 E native  : do suspend true
,09-14 06:38:59.823  3504  4570 D ScreenStateRecorder : ScreenStateRecorderHandler, handleMessage msg.what = 2
,09-14 06:38:59.823  3504  4570 D         : oem_qmi_lib:come into oem_qmi_common_stream_from_modem_len --->modem 
09-14 06:38:59.823  3504  4570 D         : oem_qmi_lib:oem_qmi_cmd: Send to server  passed!!
09-14 06:38:59.823   528  1258 D         : oem-qmi: Connection accepted
09-14 06:38:59.824   528  1258 D         : oem-qmi: Waiting to accept connection
,09-14 06:38:59.830  3504  4570 D         : oem_qmi_lib:output 0
,09-14 06:38:59.830  3504  4570 D         : oem_qmi_lib:rapi_event_type=10057, qmi_ret=0, return_status=1. 
,09-14 06:39:03.926  3111  3111 D PhoneStatusBar: disable: < expand ICONS* alerts SYSTEM_INFO* back home recent clock search quick_settings >
,09-14 06:39:03.982  3111  3111 D PhoneStatusBar: disable: < expand ICONS alerts SYSTEM_INFO back HOME* RECENT* clock SEARCH* quick_settings >
,09-14 06:39:03.998  3111  3111 W PathParser: Points are too far apart 4.030360828967057
,09-14 06:39:03.999  3111  3111 W PathParser: Points are too far apart 4.030360538880159
,09-14 06:39:06.877   931  2969 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 20, 21 -> obsolete
,09-14 06:39:07.541   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:39:08.542   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:39:09.544   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:39:10.545   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:39:11.547   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:39:12.548   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-14 06:39:21.806   931  2970 D WifiService: New client listening to asynchronous messages
,09-14 06:39:21.810  4824  6272 W CronetSyncConnectionRcs: Upload content type not set.
,09-14 06:39:37.549   538   538 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-14 06:39:37.550   538   538 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-14 06:39:57.552   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:39:58.553   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:39:58.887  3397  6021 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-14 06:39:58.887  3397  6021 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-14 06:39:58.924  3585  3585 I ConfigService: onCreate
,09-14 06:39:59.554   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:00.555   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:01.556   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:02.557   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-14 06:40:03.958  3585  3585 I ConfigService: onDestroy
,09-14 06:40:07.558   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:08.560   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:09.561   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:10.563   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:11.564   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:12.565   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-14 06:40:13.212   931  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=480051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 06:40:22.566   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:23.568   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:24.570   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:25.571   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:26.573   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:27.573   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-14 06:40:42.576   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:43.578   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:44.580   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:45.582   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:46.584   538   538 I ServiceManager: Waiting for service AtCmdFwd...
,09-14 06:40:47.586   538   538 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-14 06:40:52.211   931  5926 D NetlinkSocketObserver: NeighborEvent{elapsedMs=519050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}

```
