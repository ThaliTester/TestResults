#### Test 8326889394d960a_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of system
09-16 09:08:59.651   924  2932 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,--------- beginning of main
09-16 09:09:00.770  5374  5374 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-16 09:09:00.775  5374  5374 D AndroidRuntime: CheckJNI is OFF
09-16 09:09:00.803  5374  5374 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-16 09:09:00.835  5374  5374 I Radio-JNI: register_android_hardware_Radio DONE
09-16 09:09:00.851  5374  5374 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-16 09:09:00.858   924  3518 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-16 09:09:00.913   924  3518 I ActivityManager: Start proc 5384:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-16 09:09:00.925  5374  5374 D AndroidRuntime: Shutting down VM
,09-16 09:09:01.259   924  3379 I WindowManager: Screenshot max retries 4 of Token{1c43c90 ActivityRecord{68bbb53 u0 com.test.thalitest/.MainActivity t4}} appWin=Window{f541cb u0 Starting com.test.thalitest} drawState=4
,09-16 09:09:01.327  5384  5384 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-16 09:09:01.364  5384  5384 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-16 09:09:01.386  5384  5384 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 5245-5263)
,09-16 09:09:01.386  5384  5384 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 09:09:01.404  5384  5384 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {bdc9537}
09-16 09:09:01.404  5384  5384 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-16 09:09:01.404  5384  5384 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-16 09:09:01.408  5384  5384 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-16 09:09:01.409  5384  5384 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-16 09:09:01.442  5384  5384 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-16 09:09:01.455  5384  5384 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-16 09:09:01.455  5384  5384 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-16 09:09:01.455  5384  5384 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-16 09:09:01.455  5384  5384 I Adreno  : Build Date                       : 12/06/15
09-16 09:09:01.455  5384  5384 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-16 09:09:01.455  5384  5384 I Adreno  : Local Branch                     : mybranch17112971
09-16 09:09:01.455  5384  5384 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-16 09:09:01.455  5384  5384 I Adreno  : Remote Branch                    : NONE
09-16 09:09:01.455  5384  5384 I Adreno  : Reconstruct Branch               : NOTHING
,09-16 09:09:01.495   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@818763e:true
,09-16 09:09:01.527  3981  3981 W Binder_5: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22423]" dev="sockfs" ino=22423 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 09:09:01.527  3981  3981 W Binder_5: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22423]" dev="sockfs" ino=22423 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 09:09:01.539  5384  5384 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-16 09:09:01.547  5384  5384 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-16 09:09:01.567  3981  3981 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32039]" dev="sockfs" ino=32039 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-16 09:09:01.567  3981  3981 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32039]" dev="sockfs" ino=32039 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-16 09:09:01.572  5384  5421 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-16 09:09:01.571  3518  3518 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22428]" dev="sockfs" ino=22428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 09:09:01.571  3518  3518 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[22428]" dev="sockfs" ino=22428 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-16 09:09:01.578  5384  5408 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-16 09:09:01.606  5384  5421 I OpenGLRenderer: Initialized EGL, version 1.4
,09-16 09:09:01.673   924   942 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +412ms (total +789ms)
,09-16 09:09:01.700  5384  5384 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5384
,09-16 09:09:01.795  5384  5384 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-16 09:09:01.969  5384  5424 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -581957328
,09-16 09:09:01.974  5384  5424 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-16 09:09:01.974  5384  5424 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-16 09:09:01.974  5384  5424 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-16 09:09:01.974  5384  5424 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-16 09:09:01.974  5384  5424 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-16 09:09:01.974  5384  5424 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f5fd85 added. We now have 1 listener(s)
,09-16 09:09:01.976  5384  5424 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-16 09:09:01.977  5384  5424 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 09:09:01.978  5384  5424 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:01.978  5384  5424 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-16 09:09:01.980  5384  5424 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@90f12e8 added. We now have 1 listener(s)
09-16 09:09:01.980  5384  5424 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 09:09:01.985   924  2931 D WifiService: New client listening to asynchronous messages
,09-16 09:09:01.986  5384  5424 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 09:09:01.986  5384  5424 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-16 09:09:01.986  5384  5424 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-16 09:09:01.986  5384  5424 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-16 09:09:01.986  5384  5424 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-16 09:09:01.988  5384  5424 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:01.989  5384  5424 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-16 09:09:01.997  5384  5424 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:01.997  5384  5424 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 09:09:01.997  5384  5424 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-16 09:09:01.997  5384  5424 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:01.998  5384  5424 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 09:09:02.000  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:02.005  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:02.125  5384  5384 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-16 09:09:02.278  5384  5430 W jxcore-log: Initializing JXcore engine
,09-16 09:09:02.278  5384  5430 W jxcore-log: JXcore engine is ready
,09-16 09:09:02.297  5430  5430 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11803 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-16 09:09:02.297  5430  5430 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15551]" dev="sockfs" ino=15551 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-16 09:09:02.297  5430  5430 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-16 09:09:02.297  5430  5430 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31028]" dev="sockfs" ino=31028 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-16 09:09:02.310  5384  5430 W jxcore-log: Starting JXcore engine
,09-16 09:09:02.362  5384  5430 W jxcore-log: Platform android
09-16 09:09:02.362  5384  5430 W jxcore-log: 
09-16 09:09:02.362  5384  5430 W jxcore-log: Process ARCH arm
09-16 09:09:02.362  5384  5430 W jxcore-log: 
,09-16 09:09:02.460  5384  5430 I jxcore-log: JXcore Cordova bridge is ready!
09-16 09:09:02.460  5384  5430 I jxcore-log: 
,09-16 09:09:02.461  5384  5430 W jxcore-log: JXcore engine is started
,09-16 09:09:02.467  5384  5424 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-16 09:09:02.470  5384  5384 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-16 09:09:02.685   924  2932 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-16 09:09:05.468   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:06.468   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:07.470   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:08.471   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:09.108  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-16 09:09:09.108  5384  5430 I jxcore-log: 
,09-16 09:09:09.110  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-16 09:09:09.110  5384  5430 I jxcore-log: 
,09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:09.114  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 09:09:09.115  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 09:09:09.117  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-16 09:09:09.117  5384  5430 I jxcore-log: 
,09-16 09:09:09.118  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-16 09:09:09.118  5384  5430 I jxcore-log: 
,09-16 09:09:09.472   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:09.483  5384  5430 D executeNativeTests: Running unit tests
,09-16 09:09:09.523  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 09:09:09.523  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a added. We now have 2 listener(s)
09-16 09:09:09.524  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:09.524  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-16 09:09:09.524  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:09.524  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:09.524  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b added. We now have 2 listener(s)
09-16 09:09:09.524  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:09.525  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 09:09:09.527  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:09.530  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 09:09:09.531  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.531  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 09:09:09.533  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-16 09:09:09.533  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 09:09:09.533  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 09:09:09.534  5384  5430 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-16 09:09:09.534  5384  5430 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 09:09:09.534  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 09:09:09.535  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 09:09:09.535  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 09:09:09.535  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 09:09:09.535  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.535  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.536  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.536  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.536  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:09.536  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:09.536  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a removed from the list
09-16 09:09:09.536  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.536  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b removed from the list
09-16 09:09:09.538  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.538  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.538  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.539  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.539  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.540  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 09:09:09.540  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.540  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.540  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.541  5384  5430 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-16 09:09:09.542  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.542  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.542  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.542  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.542  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.542  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.542  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
,09-16 09:09:09.542  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.542  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.547  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.547  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.547  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 09:09:09.547  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.547  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.547  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.548  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.548  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 09:09:09.548  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.548  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 09:09:09.550  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 09:09:09.551  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.551  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.551  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 09:09:09.551  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.551  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.551  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.551  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.551  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.551  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.551  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.551  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.551  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.551  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 09:09:09.552  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.552  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.552  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.552  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.552  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.552  5384  5430 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-16 09:09:09.553  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:09.555  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 09:09:09.556  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.556  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:09.556  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:09.557  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 09:09:09.557  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 09:09:09.557  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:09.557  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 09:09:09.559  5384  5430 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 09:09:09.559  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 09:09:09.561  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 09:09:09.562  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.562  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 09:09:09.563  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 09:09:09.566  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.566  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-16 09:09:09.567  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-16 09:09:09.568  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 09:09:09.568  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 09:09:09.568  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 09:09:09.568  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:09.570  4408  4419 D BtGatt.GattService: registerClient() - UUID=606ded25-29a1-47b9-a8d2-6b9d2b28f29f
,09-16 09:09:09.571  4408  4470 D BtGatt.GattService: onClientRegistered() - UUID=606ded25-29a1-47b9-a8d2-6b9d2b28f29f, clientIf=5
,09-16 09:09:09.572  5384  5394 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 09:09:09.573  4408  4640 D BtGatt.GattService: start scan with filters
,09-16 09:09:09.576  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 09:09:09.576  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 09:09:09.577  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 09:09:09.577  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 09:09:09.577  4408  4476 D BtGatt.ScanManager: handling starting scan
09-16 09:09:09.578  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 09:09:09.578  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 09:09:09.578  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:09.578  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 09:09:09.579  4408  4476 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:09.580  5384  5430 I io.jxcore.node.ConnectionHelper: start: OK
09-16 09:09:09.581  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.581  5384  5430 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 09:09:09.581  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.581  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 09:09:09.581  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.581  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 09:09:09.581  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 09:09:09.581  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 09:09:09.581  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 09:09:09.581  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 09:09:09.581  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 09:09:09.581  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 09:09:09.582  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:09.582  4408  4419 D BtGatt.GattService: stopScan() - queue size =1
09-16 09:09:09.582  4408  4640 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 09:09:09.583  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 09:09:09.583  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-16 09:09:09.583  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 09:09:09.583  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 09:09:09.583  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 09:09:09.584  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.584  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 09:09:09.584  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 09:09:09.584  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 09:09:09.584  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:09.585  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.585  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.585  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-16 09:09:09.585  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.585  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.585  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.585  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.585  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.585  5384  5430 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 09:09:09.586  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:09.586  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:09.586  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.586  4408  4470 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 09:09:09.586  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:09.586  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 09:09:09.586  4408  4476 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:09.588  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-16 09:09:09.589  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-16 09:09:09.589  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:09.590  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:09.590  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 09:09:09.590  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 09:09:09.590  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:09.590  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 09:09:09.590  4408  4470 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 09:09:09.590  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.591  4408  4476 D BtGatt.ScanManager: Starting BLE batch scan
09-16 09:09:09.591  4408  4476 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 09:09:09.591  5384  5430 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 09:09:09.591  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 09:09:09.593  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:09.594  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:09.594  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 09:09:09.595  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 09:09:09.595  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 09:09:09.596  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 09:09:09.596  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 09:09:09.596  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 09:09:09.596  5384  5430 D BluetoothAdapter: STATE_ON
,09-16 09:09:09.598  4408  4470 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-16 09:09:09.598  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.599  4408  4421 D BtGatt.GattService: registerClient() - UUID=ab392451-060d-4d53-b022-186c53da1647
09-16 09:09:09.599  4408  4470 D BtGatt.GattService: onClientRegistered() - UUID=ab392451-060d-4d53-b022-186c53da1647, clientIf=5
,09-16 09:09:09.599  5384  5394 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 09:09:09.600  4408  4632 D BtGatt.GattService: start scan with filters
09-16 09:09:09.602  4408  4470 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 09:09:09.602  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 09:09:09.604  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 09:09:09.604  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 09:09:09.605  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 09:09:09.605  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 09:09:09.606  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:09.606  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 09:09:09.606  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:09.606  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 09:09:09.607  5384  5430 I io.jxcore.node.ConnectionHelper: start: OK
,09-16 09:09:09.608  4408  4470 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 09:09:09.608  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.608  4408  4476 D BtGatt.ScanManager: stopping BLe Batch
09-16 09:09:09.608  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.608  5384  5430 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 09:09:09.609  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.609  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 09:09:09.609  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.609  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 09:09:09.609  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 09:09:09.609  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 09:09:09.609  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 09:09:09.609  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 09:09:09.609  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 09:09:09.609  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 09:09:09.609  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:09.609  4408  4421 D BtGatt.GattService: stopScan() - queue size =0
09-16 09:09:09.610  4408  4632 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 09:09:09.610  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 09:09:09.610  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 09:09:09.610  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 09:09:09.610  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 09:09:09.610  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 09:09:09.610  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.610  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 09:09:09.610  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 09:09:09.610  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 09:09:09.611  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:09.611  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.611  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.611  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start disc,overy: false, start advertiser: false
09-16 09:09:09.611  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:09.611  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.611  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.611  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:09.611  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.611  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.611  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.611  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.612  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.612  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.613  4408  4470 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 09:09:09.613  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.613  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.613  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.613  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.613  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.613  4408  4476 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 09:09:09.613  5384  5430 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-16 09:09:09.614  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:09.617  4408  4470 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 09:09:09.617  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:09.617  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 09:09:09.618  4408  4476 D BtGatt.ScanManager: handling starting scan
09-16 09:09:09.619  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.619  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:09.619  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:09.619  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 09:09:09.620  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 09:09:09.620  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:09.620  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 09:09:09.621  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.622  5384  5430 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 09:09:09.622  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 09:09:09.625  4408  4470 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 09:09:09.625  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.625  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.625  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 09:09:09.625  4408  4476 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 09:09:09.626  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 09:09:09.626  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 09:09:09.629  4408  4470 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 09:09:09.629  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.629  4408  4476 D BtGatt.ScanManager: Starting BLE batch scan
09-16 09:09:09.629  4408  4476 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 09:09:09.632  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 09:09:09.632  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 09:09:09.632  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 09:09:09.632  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:09.633  4408  4632 D BtGatt.GattService: registerClient() - UUID=f8326275-ec6d-4bca-a61f-68bcd4bdb5b7
09-16 09:09:09.634  4408  4470 D BtGatt.GattService: onClientRegistered() - UUID=f8326275-ec6d-4bca-a61f-68bcd4bdb5b7, clientIf=5
09-16 09:09:09.634  5384  5394 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 09:09:09.634  4408  4421 D BtGatt.GattService: start scan with filters
09-16 09:09:09.636  4408  4470 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 09:09:09.636  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.637  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 09:09:09.637  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 09:09:09.637  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 09:09:09.637  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-16 09:09:09.638  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:09.638  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 09:09:09.638  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:09.639  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 09:09:09.640  4408  4470 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 09:09:09.640  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.640  5384  5430 I io.jxcore.node.ConnectionHelper: start: OK
09-16 09:09:09.640  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.640  5384  5430 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 09:09:09.640  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.640  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-16 09:09:09.640  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.640  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 09:09:09.640  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 09:09:09.640  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 09:09:09.640  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 09:09:09.640  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 09:09:09.640  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 09:09:09.640  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 09:09:09.641  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:09.641  4408  4419 D BtGatt.GattService: stopScan() - queue size =0
09-16 09:09:09.641  4408  4640 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 09:09:09.641  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 09:09:09.641  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 09:09:09.641  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 09:09:09.642  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 09:09:09.642  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 09:09:09.642  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.642  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 09:09:09.642  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 09:09:09.642  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 09:09:09.642  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:09.643  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:09.643  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.643  5384  5430 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 09:09:09.643  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:09.643  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.643  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.643  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.643  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.643  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.643  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:09.643  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.643  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.643  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.643  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.643  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.644  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.644  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.644  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.644  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.644  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.644  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.644  5384  5430 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-16 09:09:09.645  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.645  4408  4470 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 09:09:09.645  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 09:09:09.645  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.645  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.645  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.645  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.645  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.645  4408  4476 D BtGatt.ScanManager: stopping BLe Batch
09-16 09:09:09.645  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.645  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.645  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.645  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.645  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.645  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.645  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.645  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.645  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.645  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.646  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.646  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.646  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 09:09:09.646  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.646  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.646  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.646  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.646  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.646  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.646  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.646  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.646  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.646  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.646  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.646  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.646  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.646  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.649  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.649  4408  4470 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 09:09:09.649  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.649  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.649  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.649  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.649  4408  4476 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 09:09:09.649  5384  5430 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-16 09:09:09.650  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.650  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.650  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.650  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.650  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.650  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.650  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.650  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.650  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.650  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.650  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.650  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.650  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.650  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.651  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.651  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.651  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.651  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.651  5384  5430 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-16 09:09:09.651  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.651  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.651  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.651  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.651  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.651  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.651  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.651  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.651  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.651  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.651  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.651  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.651  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.651  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.652  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.652  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.652  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.652  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.652  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 09:09:09.652  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 09:09:09.652  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 09:09:09.652  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 09:09:09.652  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-16 09:09:09.652  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-16 09:09:09.652  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.652  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.652  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.653  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.653  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.653  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.653  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.653  4408  4470 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 09:09:09.653  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.653  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.653  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.653  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.653  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.653  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.653  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.653  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.653  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.653  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.653  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.653  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.654  5384  5430 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 09:09:09.654  5384  5430 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 09:09:09.654  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-16 09:09:09.655  5384  5430 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 09:09:09.655  4408  4476 D BtGatt.ScanManager: handling starting scan
09-16 09:09:09.655  5384  5430 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-16 09:09:09.655  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-16 09:09:09.656  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-16 09:09:09.656  5384  5430 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-16 09:09:09.656  5384  5430 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 09:09:09.656  5384  5430 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-16 09:09:09.656  5384  5430 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 09:09:09.656  5384  5430 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 09:09:09.656  5384  5430 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-16 09:09:09.656  5384  5430 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 09:09:09.656  5384  5430 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-16 09:09:09.656  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-16 09:09:09.659  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-16 09:09:09.659  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-16 09:09:09.659  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-16 09:09:09.660  4408  4470 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 09:09:09.660  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-16 09:09:09.660  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.660  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-16 09:09:09.660  5384  5430 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-16 09:09:09.660  5384  5430 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-16 09:09:09.660  4408  4476 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-16 09:09:09.660  5384  5430 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-16 09:09:09.660  5384  5431 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-16 09:09:09.660  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.660  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.660  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.660  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.661  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.661  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.661  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-16 09:09:09.661  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.661  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.661  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.661  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.661  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.661  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.661  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.661  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.661  5384  5432 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-16 09:09:09.662  5384  5431 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 09:09:09.662  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.662  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.662  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.662  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.662  5384  5430 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-16 09:09:09.662  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.662  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.662  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.662  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.663  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.663  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.663  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.663  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.663  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.663  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.663  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.663  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.663  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.663  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.663  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.663  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.663  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.663  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.664  5384  5430 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-16 09:09:09.664  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.664  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.661  4632  4632 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28512]" dev="sockfs" ino=28512 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 09:09:09.664  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.664  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.664  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.664  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.664  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.664  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.664  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.664  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.664  4408  4470 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 09:09:09.664  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.664  4408  4476 D BtGatt.ScanManager: Starting BLE batch scan
09-16 09:09:09.661  4632  4632 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28512]" dev="sockfs" ino=28512 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-16 09:09:09.665  4408  4476 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 09:09:09.664  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.666  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.666  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.666  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.667  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.667  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.667  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.667  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.667  5384  5430 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-16 09:09:09.667  5384  5430 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-16 09:09:09.667  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 09:09:09.667  5384  5430 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-16 09:09:09.667  5384  5430 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 09:09:09.667  5384  5430 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-16 09:09:09.667  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 09:09:09.667  5384  5430 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-16 09:09:09.667  5384  5430 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-16 09:09:09.667  5384  5430 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-16 09:09:09.667  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 09:09:09.667  5384  5430 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-16 09:09:09.668  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.668  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.668  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.668  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.668  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.668  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.668  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.668  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.668  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.668  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.668  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.668  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.668  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.668  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.668  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.668  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.668  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.669  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.669  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.669  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.669  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.669  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.669  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.669  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.669  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.669  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.669  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.670  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.670  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.670  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.670  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.670  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.670  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.670  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.670  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.670  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.670  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.670  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.670  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.670  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.670  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.670  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.670  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.670  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.670  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.670  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.670  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.673  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.673  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.673  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.673  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.674  5384  5430 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-16 09:09:09.674  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:09.674  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-16 09:09:09.675  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-16 09:09:09.675  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 09:09:09.675  5384  5384 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-16 09:09:09.675  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.675  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-16 09:09:09.675  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-16 09:09:09.675  4408  4470 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 09:09:09.675  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.675  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.675  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.675  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 09:09:09.675  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.675  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.675  5384  5384 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-16 09:09:09.676  5384  5433 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-16 09:09:09.676  5384  5433 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-16 09:09:09.676  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.678  4408  4470 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 09:09:09.678  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.678  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.678  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.678  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:09.678  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 09:09:09.678  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.678  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.678  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:09.678  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.678  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.678  5384  5384 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-16 09:09:09.678  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.678  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.678  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:09.678  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.678  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.678  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.678  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.678  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.678  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.679  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.679  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.679  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.679  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.680  5384  5430 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-16 09:09:09.680  5384  5430 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-16 09:09:09.680  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-16 09:09:09.680  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-16 09:09:09.680  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.680  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.680  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.680  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.680  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.680  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.680  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.680  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.680  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.680  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.680  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.680  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.680  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.680  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.681  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.681  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.681  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.681  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.682  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.682  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.682  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.682  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.683  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.683  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.683  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.683  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.683  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.683  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.683  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.683  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.683  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.683  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.683  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.683  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.683  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.683  4408  4470 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 09:09:09.683  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.683  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.683  4408  4476 D BtGatt.ScanManager: stopping BLe Batch
09-16 09:09:09.684  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:09.684  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:09.684  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:09.684  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:09.684  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.684  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.684  5384  5430 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b0bd42a not in the list
09-16 09:09:09.684  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.684  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.684  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:09.684  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.684  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.684  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:09.684  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:09.684  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:09.684  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:09.684  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:09.685  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12a521b not in the list
09-16 09:09:09.685  5384  5430 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-16 09:09:09.685  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 09:09:09.685  5384  5430 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-16 09:09:09.685  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-16 09:09:09.685  5384  5430 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-16 09:09:09.685  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-16 09:09:09.686  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-16 09:09:09.686  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-16 09:09:09.686  5384  5430 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-16 09:09:09.686  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 09:09:09.686  5384  5430 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-16 09:09:09.686  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-16 09:09:09.686  5384  5430 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-16 09:09:09.686  5384  5430 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-16 09:09:09.686  5384  5430 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-16 09:09:09.686  5384  5430 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-16 09:09:09.687  5384  5430 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-16 09:09:09.687  5384  5430 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-16 09:09:09.687  5384  5430 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-16 09:09:09.687  5384  5430 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-16 09:09:09.687  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:09.687  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1ed4185 added. We now have 2 listener(s)
09-16 09:09:09.687  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:09.687  4408  4470 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 09:09:09.687  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.688  4408  4476 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 09:09:09.688  5384  5430 D BluetoothAdapter: enable(): BT is already enabled..!
09-16 09:09:09.688   924  3429 D WifiService: setWifiEnabled: true pid=5384, uid=10077
09-16 09:09:09.688   924  3429 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-16 09:09:09.688  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:09.688  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd99bda added. We now have 3 listener(s)
09-16 09:09:09.689  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:09.692  4408  4470 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 09:09:09.692  4408  4470 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:09.693  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:09.693  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7bff80b added. We now have 4 listener(s)
09-16 09:09:09.693  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:09.694  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:09.694  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd226e8 added. We now have 5 listener(s)
09-16 09:09:09.694  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:09.695   924   935 D WifiService: setWifiEnabled: false pid=5384, uid=10077
09-16 09:09:09.695   924   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-16 09:09:09.696   924  2930 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-16 09:09:09.696   924  2930 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-16 09:09:09.697   924  2930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 09:09:09.697   924  2930 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-16 09:09:09.699  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:09.699  4408  4466 D BluetoothAdapterState: Current state: ON, message: 23
09-16 09:09:09.699  4408  4466 D BluetoothAdapterProperties: Setting state to 13
09-16 09:09:09.700  4408  4466 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-16 09:09:09.700  4408  4466 D BluetoothAdapterProperties: onBluetoothDisable()
09-16 09:09:09.700  4408  4466 I BluetoothAdapterState: Entering PendingCommandState
09-16 09:09:09.701  4408  4408 D BluetoothMapService: onReceive
09-16 09:09:09.701  4408  4408 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 09:09:09.701  4408  4408 D BluetoothMapService: STATE_TURNING_OFF
09-16 09:09:09.701  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.701  4408  4408 D BluetoothMapService: MAP Service closeService in
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:09.701  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 09:09:09.701  4408  4408 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 09:09:09.701  4408  4408 D ObexServerSockets0: shutdown(block = true)
09-16 09:09:09.702  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.702  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.702  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:09.702  4408  4408 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 09:09:09.702  4408  4408 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 09:09:09.702  4408  4642 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-16 09:09:09.702  4408  4643 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 09:09:09.706  4408  4628 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-16 09:09:09.706  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.707   924  5137 D DhcpClient: Clearing IP address
09-16 09:09:09.707   508   918 D CommandListener: Clearing all IP addresses on wlan0
09-16 09:09:09.708  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.711  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-16 09:09:09.711  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-16 09:09:09.712  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.712  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-16 09:09:09.714   924   937 I ActivityManager: Start proc 5436:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-16 09:09:09.715  4408  4470 D BluetoothAdapterProperties: Scan Mode:20
09-16 09:09:09.715   508   918 D CommandListener: Setting iface cfg
09-16 09:09:09.715  4408  4466 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 09:09:09.715  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.715  3558  5190 V NativeCrypto: Read error: ssl=0x7f5daeea00: I/O error during system call, Connection timed out
09-16 09:09:09.717  3558  5190 V NativeCrypto: SSL shutdown failed: ssl=0x7f5daeea00: I/O error during system call, Broken pipe
09-16 09:09:09.717  4408  4408 I BtOppRfcommListener: stopping Accept Thread
09-16 09:09:09.718  4408  5092 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 09:09:09.718  4408  5092 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 09:09:09.719   924  3429 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-16 09:09:09.720   924  5135 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-16 09:09:09.720  4408  4408 D HeadsetService: Received stop request...Stopping profile...
09-16 09:09:09.721   924  5135 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-16 09:09:09.722   924  2932 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,09-16 09:09:09.722   924  2932 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-16 09:09:09.722  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.723   924  2932 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-16 09:09:09.724  3497  3516 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:09.724   924   924 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:09.724   924   924 D BluetoothHeadset: Proxy object disconnected
,09-16 09:09:09.724   924   924 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:09.725  3072  3093 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:09.725  4408  4408 D A2dpService: Received stop request...Stopping profile...
09-16 09:09:09.725  3072  3072 D HeadsetProfile: Bluetooth service disconnected
09-16 09:09:09.725  4408  4635 D A2dpStateMachine: Exit Disconnected: -1
09-16 09:09:09.726  3072  3072 D BluetoothA2dp: Proxy object disconnected
09-16 09:09:09.726  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.726   924   924 D BluetoothA2dp: Proxy object disconnected
09-16 09:09:09.726  4408  4408 D HidService: Received stop request...Stopping profile...
09-16 09:09:09.726  4408  4408 D HidService: Stopping Bluetooth HidService
09-16 09:09:09.728  3072  3072 D BluetoothInputDevice: Proxy object disconnected
09-16 09:09:09.728  3072  3072 D HidProfile: Bluetooth service disconnected
09-16 09:09:09.728  4408  4408 D HealthService: Received stop request...Stopping profile...
09-16 09:09:09.729  4408  4408 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:09.729  4408  4408 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:09.730  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:09.730  4408  4408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:09.730   924  2932 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-16 09:09:09.730   924  2932 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-16 09:09:09.733   534   534 E Parcel  : Reading a NULL string not supported here.
,09-16 09:09:09.734  4408  4408 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-16 09:09:09.734  4408  4408 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 09:09:09.734  4408  4616 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:09.734  4408  4408 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:09.734  4408  4616 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:09.734  4408  4408 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:09.734  4408  4616 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:09.734  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:09.734  4408  4408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:09.735  4408  4470 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 09:09:09.735  4408  4470 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 09:09:09.735   924   924 D RttService: SCAN_AVAILABLE : 1
,09-16 09:09:09.735   924  3037 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-16 09:09:09.735  4408  4470 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 09:09:09.736  4408  4616 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:09.736  4408  4408 D PanService: Received stop request...Stopping profile...
09-16 09:09:09.736  4408  4616 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:09.736  4408  4616 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 09:09:09.736  4408  4616 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 09:09:09.736  4408  4616 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-16 09:09:09.736  4408  4616 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-16 09:09:09.737   924  5138 D DhcpClient: Receive thread stopped
09-16 09:09:09.738   924  2932 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-16 09:09:09.738  4408  4408 V BluetoothAdapterState: isTurningOff()=true
,09-16 09:09:09.738  4408  4408 V BluetoothAdapterState: isTurningOn()=false
,09-16 09:09:09.738  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 09:09:09.738  4408  4408 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:09.738  4408  4408 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-16 09:09:09.738  4408  4408 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-16 09:09:09.738  4408  4470 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 09:09:09.739  3453  3577 W QCNEJ   : |CORE| network lost: 100
,09-16 09:09:09.739  3453  3577 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-16 09:09:09.740  4408  4408 D BluetoothMapService: Received stop request...Stopping profile...
09-16 09:09:09.740  4408  4408 D BluetoothMapService: stop()
,09-16 09:09:09.741  4408  4408 D BluetoothMapAppObserver: deinitObservers()
,09-16 09:09:09.741  4408  4408 D BluetoothMapAppObserver: removeReceiver()
09-16 09:09:09.742  4408  4408 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:09.742  4408  4408 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:09.742  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:09.742  4408  4408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:09.743  4408  4408 D SapService: Received stop request...Stopping profile...
09-16 09:09:09.743  4408  4408 V SapService: stop()
09-16 09:09:09.743  3072  3072 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 09:09:09.743  3072  3072 D PanProfile: Bluetooth service disconnected
09-16 09:09:09.746  4408  4408 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 09:09:09.747  3072  3072 D BluetoothMap: Proxy object disconnected
09-16 09:09:09.747  3072  3072 D MapProfile: Bluetooth service disconnected
,09-16 09:09:09.747  4408  4408 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 09:09:09.747  4408  4408 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:09.747  4408  4408 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:09.747  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:09.747  4408  4408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:09.747  4408  4408 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 09:09:09.747  4408  4408 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-16 09:09:09.747  4408  4470 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 09:09:09.748  4408  4408 D BluetoothMapService: MAP Service closeService in
,09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:09.749  4408  4408 D BluetoothMapService: cleanup()
09-16 09:09:09.749  4408  4408 D BluetoothMapService: MAP Service closeService in
09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:09.749  4408  4408 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:09.750  4408  4466 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-16 09:09:09.750  4408  4466 D BluetoothAdapterProperties: Setting state to 15
09-16 09:09:09.750  4408  4466 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 09:09:09.750  4408  4466 I BluetoothAdapterState: Entering BleOnState
09-16 09:09:09.750  3072  3679 D BluetoothMap: onBluetoothStateChange: up=false
09-16 09:09:09.751  3072  3089 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 09:09:09.752   924  2930 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-16 09:09:09.753  3497  3909 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:09.753  3072  3093 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 09:09:09.754   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 09:09:09.754  3072  5383 D BluetoothPan: onBluetoothStateChange on: false
09-16 09:09:09.754   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:09.754   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 09:09:09.754   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:09.755  3072  3679 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:09.755  3072  3089 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 09:09:09.756  4408  4466 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 09:09:09.756  4408  4466 D BluetoothAdapterProperties: Setting state to 16
09-16 09:09:09.756  4408  4466 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 09:09:09.757  4408  4466 D BluetoothAdapterProperties: onBleDisable
,09-16 09:09:09.758  4408  4466 I BluetoothAdapterState: Entering PendingCommandState
09-16 09:09:09.758  4408  4467 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 09:09:09.758  4408  4470 D BluetoothAdapterProperties: Scan Mode:20
09-16 09:09:09.759  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:09.759  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:09.760  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.760  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:09.761  5384  5431 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-16 09:09:09.761  4408  4616 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-16 09:09:09.761  4408  4616 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:09.762   924  2930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 09:09:09.763  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:09.763  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:09.764  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.764  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:09.765  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.767  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.767   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-16 09:09:09.785  5436  5436 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-16 09:09:09.793   508   918 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-16 09:09:09.794   508   918 D CommandListener: Clearing all IP addresses on wlan0
,09-16 09:09:09.794   924  2932 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-16 09:09:09.795   924  2932 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-16 09:09:09.795   508   918 D TetherController: Setting IP forward enable = 0
,09-16 09:09:09.796   924   941 D Tethering: MasterInitialState.processMessage what=3
,09-16 09:09:09.798  4197  4197 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@d282d42 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-16 09:09:09.799   924  2930 D DhcpClient: doQuit
09-16 09:09:09.799  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.799   924  2930 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-16 09:09:09.799   924  5137 D DhcpClient: onQuitting
09-16 09:09:09.800  3588  3588 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 09:09:09.803  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:09.803  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:09.804  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.804  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:09.806  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:09.807  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:09.807  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:09.807  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:09.809  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:09.810  4752  4752 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-16 09:09:09.813  4837  4857 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-16 09:09:09.813  4837  4857 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-16 09:09:09.813  4837  4857 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-16 09:09:09.813  4837  ,4857 E SarControlService: no key has been found,reset the power
09-16 09:09:09.813  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-16 09:09:09.813  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-16 09:09:09.813  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-16 09:09:09.814  4865  4865 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-16 09:09:09.814  4865  4865 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-16 09:09:09.815  4837  4875 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-16 09:09:09.816  4837  4875 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-16 09:09:09.816  4837  4875 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-16 09:09:09.817  4865  4865 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-16 09:09:09.817  4865  4865 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-16 09:09:09.823  4865  4879 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@4d34fb8 HexData = [00000000ea03000000000000ffffffff]
09-16 09:09:09.823  4865  4879 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 09:09:09.823  4865  4879 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-16 09:09:09.824  4865  4865 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 09:09:09.824  4837  4848 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-16 09:09:09.824  3588  3588 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-16 09:09:09.828  4865  4879 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@4d34fb8 HexData = [00000000eb03000000000000ffffffff]
,09-16 09:09:09.828  4865  4879 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-16 09:09:09.828  4865  4879 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-16 09:09:09.829  4865  4865 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-16 09:09:09.829  4837  4847 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-16 09:09:09.831  5436  5436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 09:09:09.831  3588  3588 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-16 09:09:09.832   508   911 W SocketClient: write error (Broken pipe)
09-16 09:09:09.832   508   911 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-16 09:09:09.832   508   911 W SocketListener: Error sending broadcast (Broken pipe)
,09-16 09:09:09.837  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 09:09:09.837   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@427318b:true
,09-16 09:09:09.851   924  3429 I ActivityManager: Start proc 5466:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-16 09:09:09.851   508   918 E Netd    : netlink response contains error (No such file or directory)
09-16 09:09:09.852   508   918 D TetherController: Setting IP forward enable = 0
09-16 09:09:09.853   924  2932 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-16 09:09:09.853   924  2932 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-16 09:09:09.854  3588  3588 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 09:09:09.863  3588  3588 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 09:09:09.867  5436  5436 D LocalBluetoothProfileManager: Adding local MAP profile
,09-16 09:09:09.868   924  2930 D wifi    : In wifi stop Hal
09-16 09:09:09.869   924  2930 D wifi    : halHandle = 0x7f5d0b1a80, mVM = 0x7f788cd140, mCls = 0x100b8e
09-16 09:09:09.869   924  3584 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 09:09:09.869   924  3584 D WifiHAL : Got a signal to exit!!!
,09-16 09:09:09.869   924  3584 I WifiHAL : Exit wifi_event_loop
09-16 09:09:09.869   924  2930 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-16 09:09:09.869   924  2930 E WifiHAL : Event processing terminated
09-16 09:09:09.870   924  2930 D wifi    : In wifi cleaned up handler
09-16 09:09:09.870   924  2930 I WifiHAL : Internal cleanup completed
09-16 09:09:09.870  5436  5436 D BluetoothMap: Create BluetoothMap proxy object
,09-16 09:09:09.874  4254  4254 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 09:09:09.874  3431  3987 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-16 09:09:09.875  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:09.877  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:09.889  5436  5436 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-16 09:09:09.892   924  3584 D wifi    : set interface wlan0 flags (DOWN)
,09-16 09:09:09.892   924  2930 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 09:09:09.898  5466  5466 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-16 09:09:09.911  5436  5436 D DockEventReceiver: finishStartingService: stopping service
,09-16 09:09:09.914   924  3525 I ActivityManager: Killing 4811:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-16 09:09:09.969  4408  4470 I bt_hci  : shut_down
,09-16 09:09:09.972  4408  4477 D bt_hwcfg: hw_epilog_process
,09-16 09:09:09.973  4408  4477 I bt_vendor: low_power_mode_cb
,09-16 09:09:09.975  4408  4477 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 09:09:09.975  4408  4477 I bt_vendor: epilog_cb
09-16 09:09:09.975  4408  4477 I bt_hci  : epilog_finished_callback
,09-16 09:09:09.977  4408  4470 I bt_hci_h4: hal_close
09-16 09:09:09.977  4408  4470 I bt_userial_vendor: device fd = 54 close
,09-16 09:09:10.085  4408  4467 D bt_stack_manager: event_shut_down_stack finished.
,09-16 09:09:10.086  4408  4466 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 09:09:10.087  4408  4466 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 09:09:10.087  4408  4408 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 09:09:10.088  4408  4408 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 09:09:10.088  4408  4408 D BtGatt.GattService: stop()
09-16 09:09:10.088  4408  4408 D BtGatt.AdvertiseManager: advertise clients cleared
09-16 09:09:10.090  4408  4408 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:10.090  4408  4408 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:10.090  4408  4408 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:10.090  4408  4408 V BluetoothAdapterState: isBleTurningOff()=true
09-16 09:09:10.090  4408  4466 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-16 09:09:10.091  4408  4466 D BluetoothAdapterProperties: Setting state to 10
09-16 09:09:10.091  4408  4466 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 09:09:10.092  4408  4466 I BluetoothAdapterState: Entering OffState
,09-16 09:09:10.093   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-16 09:09:10.099   924   941 D Tethering: InitialState.processMessage what=4
,09-16 09:09:10.101   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 09:09:10.105  4408  4408 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-16 09:09:10.106  4408  4408 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 09:09:10.106  4408  4408 I BluetoothServiceJni: cleanupNative: return from cleanup
09-16 09:09:10.107  4408  4467 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-16 09:09:10.113  4408  4408 I art     : System.exit called, status: 0
,09-16 09:09:10.114  4408  4408 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 09:09:10.131  5466  5466 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-16 09:09:10.131  5466  5466 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:10.131  5466  5466 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:10.131  5466  5466 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.131  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:10.132  5466  5466 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.r.k.d(PG:583)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:170)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:10.132  5466  5466 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:10.132  5466  5466 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.File.exists(File.java:361)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:10.132  5466  5466 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:10.132  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:10.142  5436  5436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 09:09:10.154  5436  5436 D DockEventReceiver: finishStartingService: stopping service
09-16 09:09:10.155   924  3525 I ActivityManager: Killing 4197:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-16 09:09:10.179  5384  5384 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 09:09:10.247   924  3429 I ActivityManager: Process com.android.bluetooth (pid 4408) has died
,09-16 09:09:10.250  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 09:09:10.263   924  3506 I ActivityManager: Start proc 5500:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-16 09:09:10.334  5500  5500 D AdapterServiceConfig: Adding HeadsetService
09-16 09:09:10.334  5500  5500 D AdapterServiceConfig: Adding A2dpService
09-16 09:09:10.335  5500  5500 D AdapterServiceConfig: Adding HidService
09-16 09:09:10.335  5500  5500 D AdapterServiceConfig: Adding HealthService
09-16 09:09:10.335  5500  5500 D AdapterServiceConfig: Adding PanService
09-16 09:09:10.335  5500  5500 D AdapterServiceConfig: Adding GattService
09-16 09:09:10.335  5500  5500 D AdapterServiceConfig: Adding BluetoothMapService
,09-16 09:09:10.335  5500  5500 D AdapterServiceConfig: Adding SapService
,09-16 09:09:10.341   924   935 I ActivityManager: Killing 5164:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-16 09:09:10.379  3838  3838 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-16 09:09:10.387  3838  5162 I iu.UploadsManager: num queued entries: 0
,09-16 09:09:10.387  3838  5162 I iu.UploadsManager: num updated entries: 0
09-16 09:09:10.388  3838  5162 I iu.SyncManager: NEXT; no task
,09-16 09:09:10.394  3838  3838 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-16 09:09:10.396  3838  3838 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-16 09:09:10.408   924  3112 I ActivityManager: Start proc 5513:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-16 09:09:10.444  5513  5513 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-16 09:09:10.447  5513  5513 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-16 09:09:10.453  5513  5513 D SprintDMHelper: simOperator: 
,09-16 09:09:10.453  5513  5513 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-16 09:09:10.467  4254  5525 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-16 09:09:10.472   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-16 09:09:10.478   924  3112 I ActivityManager: Start proc 5526:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-16 09:09:10.479   924  3686 I ActivityManager: Killing 4481:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-16 09:09:10.497  5466  5485 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-16 09:09:10.509   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c78e29:true
,09-16 09:09:10.531  5526  5526 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-16 09:09:10.539   924  3387 I ActivityManager: Killing 5245:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-16 09:09:12.703   924  3379 D WifiService: setWifiEnabled: true pid=5384, uid=10077
,09-16 09:09:12.704   924  3379 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 09:09:12.713   508   918 D SoftapController: Softap fwReload - Ok
,09-16 09:09:12.719   508   918 D CommandListener: Setting iface cfg
09-16 09:09:12.719   508   918 D CommandListener: Trying to bring down wlan0
,09-16 09:09:12.721   508   918 D CommandListener: Clearing all IP addresses on wlan0
,09-16 09:09:12.726   924  2930 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 09:09:13.338   924  2930 D wifi    : set interface wlan0 flags (UP)
,09-16 09:09:13.342   924  2930 I WifiHAL : Initializing wifi
09-16 09:09:13.342   924  2930 I WifiHAL : Creating socket
09-16 09:09:13.347   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 09:09:13.348   924  2930 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-16 09:09:13.348   924  2930 D wifi    : Did set static halHandle = 0x7f5d0b1a80
,09-16 09:09:13.348   924  2930 D wifi    : halHandle = 0x7f5d0b1a80, mVM = 0x7f788cd140, mCls = 0x1018fa
09-16 09:09:13.348   924  2930 D wifi    : array field set
09-16 09:09:13.349   924  2930 I WifiNative-HAL: interface[0] = wlan0
,09-16 09:09:13.351   924  5543 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547021855360
09-16 09:09:13.351   924  5543 D wifi    : waitForHalEvents called, vm = 0x7f788cd140, obj = 0x1018fa, env = 0x7f58c26200
,09-16 09:09:13.420  5544  5544 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 09:09:13.442  5544  5544 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 09:09:13.452   924  2930 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-16 09:09:13.457  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:13.458  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:13.470  5544  5544 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 09:09:13.470  5544  5544 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 09:09:13.485   924  2930 D WifiConfigStore: Loading config and enabling all networks 
,09-16 09:09:13.486  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:13.486  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:13.486  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:13.486  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:13.488  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:13.488  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:13.488  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:13.488  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 09:09:13.494   924  2930 D WifiConfigStore: loaded 0 passpoint configs
09-16 09:09:13.494   924  2930 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-16 09:09:13.495   924  2930 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-16 09:09:13.496   924  2930 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 09:09:13.497   924  2930 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-16 09:09:13.497   924  2930 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 09:09:13.497   924  2930 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-16 09:09:13.497   924  2930 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 09:09:13.500   924  2930 D WifiNative-HAL: Setting external_sim to 1
,09-16 09:09:13.500  4254  4254 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 09:09:13.501   924  2930 D wifi    : setting dfs flag to true, 0x7f5cbceda0
,09-16 09:09:13.502   924  2930 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 09:09:13.502   924  2930 D wifi    : setting scan oui 0x7f5cbceda0
09-16 09:09:13.502   924  2930 D WifiHAL : Sending mac address OUI
,09-16 09:09:13.506   924  2930 E native  : do suspend false
,09-16 09:09:13.513   924   924 D RttService: SCAN_AVAILABLE : 3
,09-16 09:09:13.513   924  2930 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 09:09:13.513   508   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-16 09:09:13.513   924  3037 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 09:09:13.514   508   918 D CommandListener: Setting iface cfg
,09-16 09:09:13.518   924  2929 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
09-16 09:09:13.518   924  2929 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 09:09:13.526   924  2929 D WifiNative-HAL: p2pGetDeviceAddress
09-16 09:09:13.527   924  2929 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 09:09:13.532   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=237409 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-16 09:09:15.473   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:15.715   924   935 D WifiService: setWifiEnabled: false pid=5384, uid=10077
09-16 09:09:15.715   924   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 09:09:15.722   924   924 D RttService: SCAN_AVAILABLE : 1
,09-16 09:09:15.723   924  3037 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-16 09:09:15.740   924  2930 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-16 09:09:15.741   508   918 D CommandListener: Clearing all IP addresses on wlan0
,09-16 09:09:15.750   924  2930 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 09:09:15.752  5544  5544 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-16 09:09:15.758  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:15.758  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:15.758  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-16 09:09:15.758  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:15.761  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:15.761  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:15.761  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:15.761  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 09:09:15.768  5544  5544 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-16 09:09:15.781  5544  5544 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-16 09:09:15.783  5544  5544 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-16 09:09:15.888   924  2930 D wifi    : In wifi stop Hal
,09-16 09:09:15.888   924  2930 D wifi    : halHandle = 0x7f5d0b1a80, mVM = 0x7f788cd140, mCls = 0x1018fa
09-16 09:09:15.889   924  5543 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-16 09:09:15.889   924  5543 D WifiHAL : Got a signal to exit!!!
09-16 09:09:15.889   924  5543 I WifiHAL : Exit wifi_event_loop
09-16 09:09:15.888  4254  4254 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 09:09:15.891   924  2930 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-16 09:09:15.894   924  2930 E WifiHAL : Event processing terminated
,09-16 09:09:15.895   924  2930 D wifi    : In wifi cleaned up handler
09-16 09:09:15.895   924  2930 I WifiHAL : Internal cleanup completed
09-16 09:09:15.899  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:15.902  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:15.903  3431  3987 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 09:09:15.922   924  5543 D wifi    : set interface wlan0 flags (DOWN)
09-16 09:09:15.922   924  2930 D WifiNative-HAL: HAL event thread stopped successfully
,09-16 09:09:16.129   924   941 D Tethering: InitialState.processMessage what=4
,09-16 09:09:16.137   924   941 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-16 09:09:16.473   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:17.474   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:18.475   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:18.757   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9d56a3f:true
,09-16 09:09:18.758  5500  5500 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 09:09:18.763  5500  5500 I bt_bluedroid: init
,09-16 09:09:18.763  5500  5550 I BluetoothAdapterState: Entering OffState
,09-16 09:09:18.766  5500  5551 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-16 09:09:18.766  5500  5551 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 09:09:18.767  5500  5551 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 09:09:18.767  5500  5551 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-16 09:09:18.767  5500  5500 I bt_bluedroid: get_profile_interface socket
,09-16 09:09:18.770  5500  5554 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-16 09:09:18.770  5500  5500 I bt_bluedroid: get_profile_interface sdp
,09-16 09:09:18.773  5500  5554 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 09:09:18.779  5500  5510 I bt_bluedroid: config_hci_snoop_log
,09-16 09:09:18.781   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-16 09:09:18.787  5500  5550 D BluetoothAdapterState: Current state: OFF, message: 0
,09-16 09:09:18.787  5500  5550 D BluetoothAdapterProperties: Setting state to 14
09-16 09:09:18.787  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 09:09:18.789  5500  5550 D BluetoothBondStateMachine: make
,09-16 09:09:18.792  5500  5555 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 09:09:18.796  5500  5550 I BluetoothAdapterState: Entering PendingCommandState
,09-16 09:09:18.797  5500  5500 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 09:09:18.801  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:18.802  5500  5500 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 09:09:18.804  5500  5500 D BtGatt.GattService: Received start request. Starting profile...
,09-16 09:09:18.804  5500  5500 D BtGatt.GattService: start()
09-16 09:09:18.804  5500  5500 I bt_bluedroid: get_profile_interface gatt
09-16 09:09:18.805  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:18.805  5500  5500 D BtGatt.AdvertiseManager: advertise manager created
,09-16 09:09:18.810  5500  5500 V BluetoothAdapterState: isTurningOff()=false
,09-16 09:09:18.810  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:18.810  5500  5500 V BluetoothAdapterState: isBleTurningOn()=true
09-16 09:09:18.810  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:18.811  5500  5550 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 09:09:18.812  5500  5550 I bt_bluedroid: bt_bluedroid
09-16 09:09:18.812  5500  5551 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 09:09:18.813  5500  5551 I bt_hci  : start_up
,09-16 09:09:18.819  5500  5551 I bt_vendor: alloc value 0xf3db8871
,09-16 09:09:18.819  5500  5551 I bt_vendor: init
09-16 09:09:18.819  5500  5551 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 09:09:18.820  5500  5551 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 09:09:18.930  5500  5551 D bt_hci  : start_up starting async portion
,09-16 09:09:18.930  5500  5558 I bt_hci  : event_finish_startup
09-16 09:09:18.930  5500  5558 I bt_hci_h4: hal_open
09-16 09:09:18.931  5500  5558 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 09:09:18.927  5559  5559 W irq/448-msm_hs_: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 09:09:18.934  5500  5558 I bt_userial_vendor: device fd = 54 open
,09-16 09:09:18.948  5500  5558 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 09:09:18.951  5500  5558 D bt_hwcfg: Chipset BCM4358A3
,09-16 09:09:18.951  5500  5558 D bt_hwcfg: Target name = [BCM4358A3]
09-16 09:09:18.951  5500  5558 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 09:09:19.355  5500  5558 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 09:09:19.356  5500  5558 D bt_hwcfg: Settlement delay -- 100 ms
,09-16 09:09:19.356  5500  5558 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 09:09:19.477   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:19.490  5500  5558 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-16 09:09:19.490  5500  5558 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-16 09:09:19.492  5500  5558 I bt_hwcfg: vendor lib fwcfg completed
09-16 09:09:19.492  5500  5558 I bt_vendor: firmware callback
09-16 09:09:19.492  5500  5558 I bt_hci  : firmware_config_callback
09-16 09:09:19.501  5500  5561 I bt_btu  : btu_task pending for preload complete event
09-16 09:09:19.501  5500  5561 I bt_btu_task: Bluetooth chip preload is complete
09-16 09:09:19.501  5500  5561 I bt_btu  : btu_task received preload complete event
09-16 09:09:19.508  5500  5561 I         : BTE_InitTraceLevels -- TRC_HCI
09-16 09:09:19.509  5500  5561 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 09:09:19.509  5500  5561 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 09:09:19.509  5500  5561 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 09:09:19.509  5500  5561 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 09:09:19.509  5500  5561 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 09:09:19.509  5500  5561 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 09:09:19.509  5500  5561 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 09:09:19.510  5500  5561 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 09:09:19.510  5500  5561 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 09:09:19.510  5500  5561 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 09:09:19.510  5500  5561 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 09:09:19.510  5500  5561 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 09:09:19.510  5500  5561 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 09:09:19.510  5500  5561 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 09:09:19.594  5500  5561 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d36549
,09-16 09:09:19.594  5500  5561 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d36549 
,09-16 09:09:19.613  5500  5554 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-16 09:09:19.615  5500  5554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-16 09:09:19.615  5500  5554 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 09:09:19.619  5500  5554 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 09:09:19.621  5500  5554 D BluetoothAdapterProperties: Scan Mode:20
,09-16 09:09:19.622  5500  5554 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-16 09:09:19.622  5500  5554 D bt_hci  : do_postload posting postload work item
09-16 09:09:19.622  5500  5558 I bt_hci  : event_postload
09-16 09:09:19.622  5500  5558 I bt_vendor: sco_config_cb
09-16 09:09:19.622  5500  5558 I bt_hci  : sco_config_callback postload finished.
09-16 09:09:19.627  5500  5554 D bt_bte_conf: Device ID record 1 : primary
,09-16 09:09:19.628  5500  5554 D bt_bte_conf:   vendorId            = 000f
09-16 09:09:19.628  5500  5554 D bt_bte_conf:   vendorIdSource      = 0001
09-16 09:09:19.628  5500  5554 D bt_bte_conf:   product             = 1200
09-16 09:09:19.628  5500  5554 D bt_bte_conf:   version             = 1436
09-16 09:09:19.628  5500  5554 D bt_bte_conf:   clientExecutableURL = 
09-16 09:09:19.628  5500  5554 D bt_bte_conf:   serviceDescription  = 
09-16 09:09:19.628  5500  5554 D bt_bte_conf:   documentationURL    = 
09-16 09:09:19.628  5500  5554 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-16 09:09:19.629  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:19.629  5500  5551 D bt_stack_manager: event_start_up_stack finished
,09-16 09:09:19.630  5500  5558 I bt_vendor: low_power_mode_cb
09-16 09:09:19.631  5500  5550 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-16 09:09:19.632  5500  5550 D BluetoothAdapterProperties: Setting state to 15
09-16 09:09:19.632  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-16 09:09:19.634  5500  5550 I BluetoothAdapterState: Entering BleOnState
09-16 09:09:19.635  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:19.637  5500  5550 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-16 09:09:19.638  5500  5550 D BluetoothAdapterProperties: Setting state to 11
09-16 09:09:19.638  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 09:09:19.643  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:19.647  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:19.647  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:19.648  5500  5500 D HeadsetService: Received start request. Starting profile...
09-16 09:09:19.651  5500  5500 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 09:09:19.651  5500  5500 D HeadsetStateMachine: make
,09-16 09:09:19.660  5500  5550 I BluetoothAdapterState: Entering PendingCommandState
,09-16 09:09:19.661  5500  5500 D HeadsetStateMachine: max_hf_connections = 1
09-16 09:09:19.661  5500  5500 I bt_bluedroid: get_profile_interface handsfree
,09-16 09:09:19.661  5500  5554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 09:09:19.662  5500  5554 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-16 09:09:19.666  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:19.666  5500  5500 D A2dpService: Received start request. Starting profile...
,09-16 09:09:19.666  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-16 09:09:19.667  5500  5500 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-16 09:09:19.667  5500  5500 I bt_bluedroid: get_profile_interface avrcp
,09-16 09:09:19.672  5500  5500 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 09:09:19.673  5500  5500 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 09:09:19.673  5500  5500 D A2dpStateMachine: make
,09-16 09:09:19.674  5500  5500 I bt_bluedroid: get_profile_interface a2dp
,09-16 09:09:19.676  5500  5569 D A2dpStateMachine: Enter Disconnected: -2
09-16 09:09:19.676  5500  5554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-16 09:09:19.677  5500  5500 I BluetoothHidServiceJni: classInitNative: succeeds
,09-16 09:09:19.678  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:19.679  5500  5500 D HidService: Received start request. Starting profile...
09-16 09:09:19.679  5436  5436 D BluetoothInputDevice: Proxy object connected
,09-16 09:09:19.680  5500  5500 I bt_bluedroid: get_profile_interface hidhost
,09-16 09:09:19.680  5500  5554 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d1756d
09-16 09:09:19.680  5500  5500 D HidService: setHidService(): set to: null
09-16 09:09:19.680  5500  5554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-16 09:09:19.680  5436  5436 D HidProfile: Bluetooth service connected
09-16 09:09:19.680  5500  5500 I BluetoothHealthServiceJni: classInitNative: succeeds
09-16 09:09:19.681  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:19.682  5500  5500 D HealthService: Received start request. Starting profile...
,09-16 09:09:19.683  5500  5500 I bt_bluedroid: get_profile_interface health
,09-16 09:09:19.684  5500  5500 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-16 09:09:19.684  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:19.686  5436  5436 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 09:09:19.686  5436  5436 D PanProfile: Bluetooth service connected
09-16 09:09:19.687  5500  5500 D PanService: Received start request. Starting profile...
09-16 09:09:19.687  5500  5500 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-16 09:09:19.687  5500  5500 I bt_bluedroid: get_profile_interface pan
09-16 09:09:19.688  5500  5554 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-16 09:09:19.689  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:19.690  5436  5436 D BluetoothMap: Proxy object connected
09-16 09:09:19.691  5436  5436 D MapProfile: Bluetooth service connected
09-16 09:09:19.691  5436  5436 D BluetoothMap: getConnectedDevices()
09-16 09:09:19.692  5436  5436 D BluetoothMap: Bluetooth is Not enabled
09-16 09:09:19.692  5500  5500 D BluetoothMapService: Received start request. Starting profile...
09-16 09:09:19.692  5500  5500 D BluetoothMapService: start()
,09-16 09:09:19.695  5500  5500 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 09:09:19.695  5500  5500 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-16 09:09:19.696  5500  5500 D BluetoothMapAppObserver: createReceiver()
,09-16 09:09:19.697  5500  5500 D BluetoothMapAppObserver: initObservers()
,09-16 09:09:19.697  5500  5500 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 09:09:19.703  5500  5500 V SapService: SapBinder()
09-16 09:09:19.703  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:19.704  5500  5500 D SapService: Received start request. Starting profile...
09-16 09:09:19.704  5500  5500 V SapService: start()
,09-16 09:09:19.705  5500  5500 V BluetoothAdapterState: isTurningOff()=false
,09-16 09:09:19.705  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:19.705  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:19.705  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:19.706  5500  5567 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:19.706  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isTurningOn()=true
,09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:19.707  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:19.708  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:19.708  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:19.708  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:19.708  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:19.708  5500  5550 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 09:09:19.708  5500  5550 D BluetoothAdapterProperties: ScanMode =  20
09-16 09:09:19.708  5500  5550 D BluetoothAdapterProperties: State =  11
,09-16 09:09:19.709  5500  5554 D BluetoothAdapterProperties: Scan Mode:21
09-16 09:09:19.709  5500  5550 D BluetoothAdapterProperties: Setting state to 12
09-16 09:09:19.709  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-16 09:09:19.709  5500  5554 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 09:09:19.710  5500  5550 I BluetoothAdapterState: Entering OnState
09-16 09:09:19.710  3072  3679 D BluetoothMap: onBluetoothStateChange: up=true
09-16 09:09:19.713  3072  3072 D BluetoothMap: Proxy object connected
09-16 09:09:19.713  3072  3072 D MapProfile: Bluetooth service connected
09-16 09:09:19.713  3072  3072 D BluetoothMap: getConnectedDevices()
09-16 09:09:19.714  5436  5447 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-16 09:09:19.714  3072  5383 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:19.714  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:19.716  3497  3517 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:19.716  3072  3089 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 09:09:19.717  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:19.718   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:19.718  3072  3679 D BluetoothPan: onBluetoothStateChange on: true
09-16 09:09:19.719  3072  3072 D BluetoothA2dp: Proxy object connected
09-16 09:09:19.720  5436  5448 D BluetoothPan: onBluetoothStateChange on: true
09-16 09:09:19.720   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 09:09:19.720   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 09:09:19.721   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:19.721   924   924 D BluetoothA2dp: Proxy object connected
,09-16 09:09:19.721  3072  3072 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 09:09:19.721  3072  3072 D PanProfile: Bluetooth service connected
09-16 09:09:19.721  3072  5383 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:19.721  5436  5447 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:19.722  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:19.722  5500  5500 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-16 09:09:19.723  5436  5448 D BluetoothMap: onBluetoothStateChange: up=true
09-16 09:09:19.723  5500  5500 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 09:09:19.723  3072  3089 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-16 09:09:19.723  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:19.724  5500  5500 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 09:09:19.724  3072  3072 D BluetoothInputDevice: Proxy object connected
09-16 09:09:19.724  3072  3072 D HidProfile: Bluetooth service connected
,09-16 09:09:19.726   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 09:09:19.727  5500  5500 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 09:09:19.728  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:19.728  5436  5436 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-16 09:09:19.729  5500  5500 D ObexServerSockets: Succeed to create listening sockets 
09-16 09:09:19.729  5500  5500 D ObexServerSockets0: startAccept()
09-16 09:09:19.729  5500  5500 D ObexServerSockets0: prepareForNewConnect()
09-16 09:09:19.730  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:19.731  5500  5500 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 09:09:19.731  5500  5500 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 09:09:19.732  5500  5500 D BluetoothMapService: onReceive
09-16 09:09:19.732  5500  5575 D ObexServerSockets0: Accepting socket connection...
09-16 09:09:19.732  5500  5500 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 09:09:19.733  5500  5576 D ObexServerSockets0: Accepting socket connection...
,09-16 09:09:19.733  5500  5500 D BluetoothMapService: STATE_ON
09-16 09:09:19.733  5436  5436 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-16 09:09:19.736  5500  5577 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 09:09:19.738  5500  5577 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-16 09:09:19.738  5500  5577 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-16 09:09:19.741  5436  5436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 09:09:19.744  5436  5436 D BluetoothA2dp: Proxy object connected
,09-16 09:09:19.747  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 09:09:19.750  5436  5436 D DockEventReceiver: finishStartingService: stopping service
,09-16 09:09:19.754  3072  3072 D BluetoothPbap: Proxy object connected
09-16 09:09:19.754  5436  5436 D BluetoothPbap: Proxy object connected
,09-16 09:09:19.755  3072  3072 D PbapServerProfile: Bluetooth service connected
,09-16 09:09:19.755  5436  5436 D PbapServerProfile: Bluetooth service connected
,09-16 09:09:19.761  5500  5500 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-16 09:09:19.761  5500  5500 D ObexServerSockets0: prepareForNewConnect()
,09-16 09:09:19.765  5500  5581 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 09:09:19.777  5500  5585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 09:09:19.778  5500  5585 I BtOppRfcommListener: Accept thread started.
,09-16 09:09:19.817  3497  3824 D BluetoothHeadset: Proxy object connected
,09-16 09:09:19.818   924   924 D BluetoothHeadset: Proxy object connected
09-16 09:09:19.818   924   924 D BluetoothHeadset: Proxy object connected
09-16 09:09:19.818   924   924 D BluetoothHeadset: Proxy object connected
09-16 09:09:19.818  3072  3093 D BluetoothHeadset: Proxy object connected
09-16 09:09:19.818  3072  3072 D HeadsetProfile: Bluetooth service connected
09-16 09:09:19.819   924   941 D BluetoothHeadset: Proxy object connected
,09-16 09:09:19.821   924   941 D BluetoothHeadset: Proxy object connected
09-16 09:09:19.821   924   941 D BluetoothHeadset: Proxy object connected
,09-16 09:09:19.821  3072  5383 D BluetoothHeadset: Proxy object connected
09-16 09:09:19.821  3072  3072 D HeadsetProfile: Bluetooth service connected
,09-16 09:09:19.837  5436  5447 D BluetoothHeadset: Proxy object connected
,09-16 09:09:19.838  5436  5436 D HeadsetProfile: Bluetooth service connected
,09-16 09:09:20.477   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-16 09:09:21.730  5500  5550 D BluetoothAdapterState: Current state: ON, message: 23
,09-16 09:09:21.730  5500  5550 D BluetoothAdapterProperties: Setting state to 13
09-16 09:09:21.730  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-16 09:09:21.732  5500  5550 D BluetoothAdapterProperties: onBluetoothDisable()
,09-16 09:09:21.734  5500  5550 I BluetoothAdapterState: Entering PendingCommandState
,09-16 09:09:21.739  5500  5500 D BluetoothMapService: onReceive
,09-16 09:09:21.742  5500  5554 D BluetoothAdapterProperties: Scan Mode:20
09-16 09:09:21.742  5500  5500 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 09:09:21.742  5500  5500 D BluetoothMapService: STATE_TURNING_OFF
09-16 09:09:21.742  5500  5550 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-16 09:09:21.742  5500  5500 D BluetoothMapService: MAP Service closeService in
09-16 09:09:21.742  5500  5500 D BluetoothMapMasInstance0: MAP Service shutdown
09-16 09:09:21.742  5500  5500 D ObexServerSockets0: shutdown(block = true)
09-16 09:09:21.743  5500  5500 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 09:09:21.744  5500  5576 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-16 09:09:21.745  5500  5500 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-16 09:09:21.745  5500  5563 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-16 09:09:21.745  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:21.745  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:21.745  5500  5575 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-16 09:09:21.746  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:21.746  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:21.747  5500  5500 I BtOppRfcommListener: stopping Accept Thread
09-16 09:09:21.747  5500  5585 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-16 09:09:21.747  5500  5585 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-16 09:09:21.749  5436  5436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-16 09:09:21.749  5500  5500 D HeadsetService: Received stop request...Stopping profile...
09-16 09:09:21.751  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:21.752  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:21.753  5384  5384 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-16 09:09:21.753  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:21.755  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:21.75,7  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:21.758  3497  3516 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:21.758   924   924 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:21.758   924   924 D BluetoothHeadset: Proxy object disconnected
,09-16 09:09:21.758   924   924 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:21.759  5500  5500 D A2dpService: Received stop request...Stopping profile...
,09-16 09:09:21.760  5500  5569 D A2dpStateMachine: Exit Disconnected: -1
,09-16 09:09:21.762  5436  5448 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:21.763  5500  5500 D HidService: Received stop request...Stopping profile...
09-16 09:09:21.763  5500  5500 D HidService: Stopping Bluetooth HidService
09-16 09:09:21.763  3072  3093 D BluetoothHeadset: Proxy object disconnected
09-16 09:09:21.764   924   924 D BluetoothA2dp: Proxy object disconnected
09-16 09:09:21.765  5500  5500 D HealthService: Received stop request...Stopping profile...
09-16 09:09:21.766  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 09:09:21.767  3072  3072 D BluetoothA2dp: Proxy object disconnected
09-16 09:09:21.768  3072  3072 D BluetoothInputDevice: Proxy object disconnected
09-16 09:09:21.768  3072  3072 D HidProfile: Bluetooth service disconnected
09-16 09:09:21.768  3072  3072 D HeadsetProfile: Bluetooth service disconnected
,09-16 09:09:21.769  5436  5436 D DockEventReceiver: finishStartingService: stopping service
,09-16 09:09:21.769  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:21.769  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:21.769  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:21.769  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:21.770  5500  5500 D PanService: Received stop request...Stopping profile...
09-16 09:09:21.770  5436  5436 D HeadsetProfile: Bluetooth service disconnected
09-16 09:09:21.771  5436  5436 D BluetoothInputDevice: Proxy object disconnected
09-16 09:09:21.771  5436  5436 D HidProfile: Bluetooth service disconnected
09-16 09:09:21.771  5436  5436 D BluetoothA2dp: Proxy object disconnected
09-16 09:09:21.771  5436  5436 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 09:09:21.771  5436  5436 D PanProfile: Bluetooth service disconnected
09-16 09:09:21.771  3072  3072 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-16 09:09:21.771  3072  3072 D PanProfile: Bluetooth service disconnected
,09-16 09:09:21.773  5500  5500 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-16 09:09:21.774  5500  5500 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-16 09:09:21.774  5500  5554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-16 09:09:21.774  5500  5500 D BluetoothMapService: Received stop request...Stopping profile...
09-16 09:09:21.774  5500  5500 D BluetoothMapService: stop()
,09-16 09:09:21.774  5500  5561 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:21.774  5500  5561 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:21.774  5500  5561 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:21.774  5500  5554 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-16 09:09:21.775  5500  5500 D BluetoothMapAppObserver: deinitObservers()
09-16 09:09:21.775  5500  5500 D BluetoothMapAppObserver: removeReceiver()
09-16 09:09:21.776  3072  3072 D BluetoothMap: Proxy object disconnected
09-16 09:09:21.776  3072  3072 D MapProfile: Bluetooth service disconnected
09-16 09:09:21.776  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:21.776  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:21.776  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:21.776  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:21.778  5500  5561 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:21.778  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:21.778  5500  5561 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:21.778  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:21.778  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:21.778  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:21.778  5500  5561 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 09:09:21.778  5500  5561 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 09:09:21.779  5500  5561 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-16 09:09:21.779  5500  5500 D SapService: Received stop request...Stopping profile...
09-16 09:09:21.779  5500  5561 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-16 09:09:21.779  5500  5500 V SapService: stop()
09-16 09:09:21.779  5500  5554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-16 09:09:21.779  5436  5436 D BluetoothMap: Proxy object disconnected
09-16 09:09:21.779  5436  5436 D MapProfile: Bluetooth service disconnected
09-16 09:09:21.780  5500  5500 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-16 09:09:21.780  5500  5500 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-16 09:09:21.781  5500  5554 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 09:09:21.782  5436  5436 D BluetoothPbap: Proxy object disconnected
09-16 09:09:21.782  3072  3072 D BluetoothPbap: Proxy object disconnected
09-16 09:09:21.782  3072  3072 D PbapServerProfile: Bluetooth service disconnected
09-16 09:09:21.782  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:21.782  5436  5436 D PbapServerProfile: Bluetooth service disconnected
09-16 09:09:21.782  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:21.782  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:21.782  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:21.782  5500  5500 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-16 09:09:21.783  5500  5554 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-16 09:09:21.783  5500  5500 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-16 09:09:21.783  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:21.783  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:21.783  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:21.783  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:21.784  5500  5500 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-16 09:09:21.784  5500  5500 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-16 09:09:21.785  5500  5500 D BluetoothMapService: MAP Service closeService in
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:21.785  5500  5500 D BluetoothMapService: cleanup()
09-16 09:09:21.785  5500  5500 D BluetoothMapService: MAP Service closeService in
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:21.785  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:21.786  5500  5550 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-16 09:09:21.787  5500  5550 D BluetoothAdapterProperties: Setting state to 15
09-16 09:09:21.787  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-16 09:09:21.787  5500  5550 I BluetoothAdapterState: Entering BleOnState
09-16 09:09:21.788  3072  3679 D BluetoothMap: onBluetoothStateChange: up=false
09-16 09:09:21.791  5436  5447 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 09:09:21.792  3072  3093 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 09:09:21.792  5436  5589 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-16 09:09:21.793  3497  3909 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:21.793  3072  5383 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 09:09:21.794   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:21.794  3072  3089 D BluetoothPan: onBluetoothStateChange on: false
09-16 09:09:21.795  5436  5448 D BluetoothPan: onBluetoothStateChange on: false
09-16 09:09:21.795   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:21.795   924   941 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 09:09:21.796   924   941 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:21.796  3072  3679 D BluetoothHeadset: onBluetoothStateChange: up=false
09-16 09:09:21.796  5436  5447 D BluetoothPbap: onBluetoothStateChange: up=false
09-16 09:09:21.797  5436  5589 D BluetoothMap: onBluetoothStateChange: up=false
09-16 09:09:21.798  3072  3093 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-16 09:09:21.798  5436  5448 D BluetoothA2dp: onBluetoothStateChange: up=false
09-16 09:09:21.799  5500  5550 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-16 09:09:21.799  5500  5550 D BluetoothAdapterProperties: Setting state to 16
09-16 09:09:21.799  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-16 09:09:21.799  5500  5550 D BluetoothAdapterProperties: onBleDisable
09-16 09:09:21.800  5500  5550 I BluetoothAdapterState: Entering PendingCommandState
09-16 09:09:21.800  5500  5551 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-16 09:09:21.801  5500  5561 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-16 09:09:21.801  5500  5561 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-16 09:09:21.801  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:21.802  5500  5554 D BluetoothAdapterProperties: Scan Mode:20
09-16 09:09:21.803  5436  5436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 09:09:21.803  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:21.805  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:21.806  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:21.813  5436  5436 D DockEventReceiver: finishStartingService: stopping service
09-16 09:09:21.817  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 09:09:22.013  5500  5554 I bt_hci  : shut_down
,09-16 09:09:22.017  5500  5558 D bt_hwcfg: hw_epilog_process
,09-16 09:09:22.017  5500  5558 I bt_vendor: low_power_mode_cb
,09-16 09:09:22.019  5500  5558 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-16 09:09:22.019  5500  5558 I bt_vendor: epilog_cb
09-16 09:09:22.019  5500  5558 I bt_hci  : epilog_finished_callback
09-16 09:09:22.021  5500  5554 I bt_hci_h4: hal_close
,09-16 09:09:22.021  5500  5554 I bt_userial_vendor: device fd = 54 close
,09-16 09:09:22.139  5500  5551 D bt_stack_manager: event_shut_down_stack finished.
,09-16 09:09:22.141  5500  5550 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-16 09:09:22.144  5500  5550 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-16 09:09:22.144  5500  5500 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-16 09:09:22.145  5500  5500 D BtGatt.GattService: Received stop request...Stopping profile...
09-16 09:09:22.145  5500  5500 D BtGatt.GattService: stop()
09-16 09:09:22.145  5500  5500 D BtGatt.AdvertiseManager: advertise clients cleared
,09-16 09:09:22.147  5500  5500 V BluetoothAdapterState: isTurningOff()=false
,09-16 09:09:22.147  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:22.147  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 09:09:22.147  5500  5500 V BluetoothAdapterState: isBleTurningOff()=true
,09-16 09:09:22.148  5500  5550 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-16 09:09:22.148  5500  5550 D BluetoothAdapterProperties: Setting state to 10
09-16 09:09:22.148  5500  5550 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-16 09:09:22.149  5500  5550 I BluetoothAdapterState: Entering OffState
09-16 09:09:22.149   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-16 09:09:22.159  5500  5500 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-16 09:09:22.159  5500  5500 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-16 09:09:22.161  5500  5551 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-16 09:09:22.163  5500  5500 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-16 09:09:22.167  5500  5500 I art     : System.exit called, status: 0
,09-16 09:09:22.167  5500  5500 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-16 09:09:22.190   924  3506 I ActivityManager: Process com.android.bluetooth (pid 5500) has died
,09-16 09:09:24.728  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:24.729  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 09:09:27.737  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 09:09:27.737  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9459ba6 added. We now have 6 listener(s)
09-16 09:09:27.738  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 09:09:27.743  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 09:09:27.744  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7409e7 added. We now have 7 listener(s)
09-16 09:09:27.744  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:27.746  5384  5430 I System.out: IsBluetoothEnabled
,09-16 09:09:27.754  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:27.784   924   941 I ActivityManager: Start proc 5594:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-16 09:09:27.870  5594  5594 D AdapterServiceConfig: Adding HeadsetService
,09-16 09:09:27.871  5594  5594 D AdapterServiceConfig: Adding A2dpService
09-16 09:09:27.871  5594  5594 D AdapterServiceConfig: Adding HidService
09-16 09:09:27.871  5594  5594 D AdapterServiceConfig: Adding HealthService
09-16 09:09:27.871  5594  5594 D AdapterServiceConfig: Adding PanService
09-16 09:09:27.872  5594  5594 D AdapterServiceConfig: Adding GattService
,09-16 09:09:27.872  5594  5594 D AdapterServiceConfig: Adding BluetoothMapService
09-16 09:09:27.872  5594  5594 D AdapterServiceConfig: Adding SapService
,09-16 09:09:27.886   924   941 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36937cc:true
,09-16 09:09:27.886  5594  5594 D BluetoothAdapterState: make() - Creating AdapterState
,09-16 09:09:27.890  5594  5594 I bt_bluedroid: init
,09-16 09:09:27.890  5594  5606 I BluetoothAdapterState: Entering OffState
,09-16 09:09:27.892  5594  5607 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-16 09:09:27.893  5594  5607 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-16 09:09:27.893  5594  5607 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-16 09:09:27.893  5594  5607 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-16 09:09:27.893  5594  5594 I bt_bluedroid: get_profile_interface socket
,09-16 09:09:27.895  5594  5610 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 09:09:27.896  5594  5594 I bt_bluedroid: get_profile_interface sdp
09-16 09:09:27.897  5594  5610 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 09:09:27.901  5594  5604 I bt_bluedroid: config_hci_snoop_log
,09-16 09:09:27.902   924   941 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-16 09:09:27.907  5594  5606 D BluetoothAdapterState: Current state: OFF, message: 0
,09-16 09:09:27.907  5594  5606 D BluetoothAdapterProperties: Setting state to 14
09-16 09:09:27.907  5594  5606 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-16 09:09:27.909  5594  5606 D BluetoothBondStateMachine: make
,09-16 09:09:27.911  5594  5611 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-16 09:09:27.914  5594  5606 I BluetoothAdapterState: Entering PendingCommandState
,09-16 09:09:27.915  5594  5594 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-16 09:09:27.918  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:27.918  5594  5594 D BtGatt.DebugUtils: handleDebugAction() action=null
09-16 09:09:27.919  5594  5594 D BtGatt.GattService: Received start request. Starting profile...
09-16 09:09:27.919  5594  5594 D BtGatt.GattService: start()
09-16 09:09:27.919  5594  5594 I bt_bluedroid: get_profile_interface gatt
09-16 09:09:27.920  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:27.920  5594  5594 D BtGatt.AdvertiseManager: advertise manager created
,09-16 09:09:27.925  5594  5594 V BluetoothAdapterState: isTurningOff()=false
,09-16 09:09:27.925  5594  5594 V BluetoothAdapterState: isTurningOn()=false
09-16 09:09:27.925  5594  5594 V BluetoothAdapterState: isBleTurningOn()=true
09-16 09:09:27.926  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:27.926  5594  5606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-16 09:09:27.928  5594  5606 I bt_bluedroid: bt_bluedroid
09-16 09:09:27.928  5594  5607 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-16 09:09:27.928  5594  5607 I bt_hci  : start_up
,09-16 09:09:27.933  5594  5607 I bt_vendor: alloc value 0xf3e0b871
09-16 09:09:27.934  5594  5607 I bt_vendor: init
,09-16 09:09:27.934  5594  5607 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-16 09:09:27.934  5594  5607 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-16 09:09:28.046  5594  5607 D bt_hci  : start_up starting async portion
09-16 09:09:28.047  5594  5614 I bt_hci  : event_finish_startup
,09-16 09:09:28.047  5594  5614 I bt_hci_h4: hal_open
09-16 09:09:28.047  5594  5614 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-16 09:09:28.044  5615  5615 W irq/448-msm_hs_: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-16 09:09:28.050  5594  5614 I bt_userial_vendor: device fd = 54 open
,09-16 09:09:28.064  5594  5614 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-16 09:09:28.067  5594  5614 D bt_hwcfg: Chipset BCM4358A3
,09-16 09:09:28.067  5594  5614 D bt_hwcfg: Target name = [BCM4358A3]
09-16 09:09:28.067  5594  5614 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-16 09:09:28.475  5594  5614 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-16 09:09:28.475  5594  5614 D bt_hwcfg: Settlement delay -- 100 ms
,09-16 09:09:28.475  5594  5614 I bt_hwcfg: Setting fw settlement delay to 100 
,09-16 09:09:28.609  5594  5614 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-16 09:09:28.610  5594  5614 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-16 09:09:28.611  5594  5614 I bt_hwcfg: vendor lib fwcfg completed
09-16 09:09:28.611  5594  5614 I bt_vendor: firmware callback
09-16 09:09:28.611  5594  5614 I bt_hci  : firmware_config_callback
,09-16 09:09:28.621  5594  5617 I bt_btu  : btu_task pending for preload complete event
,09-16 09:09:28.621  5594  5617 I bt_btu_task: Bluetooth chip preload is complete
09-16 09:09:28.621  5594  5617 I bt_btu  : btu_task received preload complete event
,09-16 09:09:28.627  5594  5617 I         : BTE_InitTraceLevels -- TRC_HCI
09-16 09:09:28.628  5594  5617 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-16 09:09:28.628  5594  5617 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-16 09:09:28.628  5594  5617 I         : BTE_InitTraceLevels -- TRC_AVDT
09-16 09:09:28.628  5594  5617 I         : BTE_InitTraceLevels -- TRC_AVRC
09-16 09:09:28.628  5594  5617 I         : BTE_InitTraceLevels -- TRC_A2D
09-16 09:09:28.628  5594  5617 I         : BTE_InitTraceLevels -- TRC_BNEP
09-16 09:09:28.629  5594  5617 I         : BTE_InitTraceLevels -- TRC_BTM
09-16 09:09:28.629  5594  5617 I         : BTE_InitTraceLevels -- TRC_GAP
09-16 09:09:28.629  5594  5617 I         : BTE_InitTraceLevels -- TRC_PAN
09-16 09:09:28.629  5594  5617 I         : BTE_InitTraceLevels -- TRC_SDP
09-16 09:09:28.629  5594  5617 I         : BTE_InitTraceLevels -- TRC_GATT
09-16 09:09:28.629  5594  5617 I         : BTE_InitTraceLevels -- TRC_SMP
09-16 09:09:28.629  5594  5617 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-16 09:09:28.630  5594  5617 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-16 09:09:28.712  5594  5617 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d89549
09-16 09:09:28.713  5594  5617 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d89549 
,09-16 09:09:28.735  5594  5610 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-16 09:09:28.735  5594  5610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-16 09:09:28.736  5594  5610 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-16 09:09:28.738  5594  5610 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-16 09:09:28.741  5594  5610 D BluetoothAdapterProperties: Scan Mode:20
,09-16 09:09:28.741  5594  5610 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 09:09:28.741  5594  5610 D bt_hci  : do_postload posting postload work item
09-16 09:09:28.741  5594  5614 I bt_hci  : event_postload
09-16 09:09:28.741  5594  5614 I bt_vendor: sco_config_cb
,09-16 09:09:28.741  5594  5614 I bt_hci  : sco_config_callback postload finished.
09-16 09:09:28.744  5594  5610 D bt_bte_conf: Device ID record 1 : primary
09-16 09:09:28.744  5594  5610 D bt_bte_conf:   vendorId            = 000f
,09-16 09:09:28.744  5594  5610 D bt_bte_conf:   vendorIdSource      = 0001
09-16 09:09:28.747  5594  5610 D bt_bte_conf:   product             = 1200
09-16 09:09:28.747  5594  5610 D bt_bte_conf:   version             = 1436
09-16 09:09:28.747  5594  5610 D bt_bte_conf:   clientExecutableURL = 
09-16 09:09:28.747  5594  5610 D bt_bte_conf:   serviceDescription  = 
09-16 09:09:28.747  5594  5610 D bt_bte_conf:   documentationURL    = 
09-16 09:09:28.747  5594  5610 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-16 09:09:28.748  5594  5607 D bt_stack_manager: event_start_up_stack finished
09-16 09:09:28.749  5594  5606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-16 09:09:28.749  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:28.749  5594  5606 D BluetoothAdapterProperties: Setting state to 15
09-16 09:09:28.749  5594  5606 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-16 09:09:28.751  5594  5614 I bt_vendor: low_power_mode_cb
09-16 09:09:28.751  5594  5606 I BluetoothAdapterState: Entering BleOnState
,09-16 09:09:28.756  5594  5606 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-16 09:09:28.756  5594  5606 D BluetoothAdapterProperties: Setting state to 11
09-16 09:09:28.756  5594  5606 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-16 09:09:28.760  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:28.761  5594  5594 D HeadsetService: Received start request. Starting profile...
,09-16 09:09:28.764  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:28.764  5594  5594 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-16 09:09:28.764  5594  5594 D HeadsetStateMachine: make
,09-16 09:09:28.775  5594  5594 D HeadsetStateMachine: max_hf_connections = 1
09-16 09:09:28.775  5594  5594 I bt_bluedroid: get_profile_interface handsfree
,09-16 09:09:28.775  5594  5610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-16 09:09:28.775  5594  5610 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-16 09:09:28.779  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:28.779  5594  5606 I BluetoothAdapterState: Entering PendingCommandState
09-16 09:09:28.780  5594  5594 D A2dpService: Received start request. Starting profile...
,09-16 09:09:28.781  5594  5594 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-16 09:09:28.781  5594  5594 I bt_bluedroid: get_profile_interface avrcp
,09-16 09:09:28.787  5594  5594 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-16 09:09:28.787  5594  5594 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-16 09:09:28.787  5594  5594 D A2dpStateMachine: make
09-16 09:09:28.788  5594  5594 I bt_bluedroid: get_profile_interface a2dp
09-16 09:09:28.788  5594  5610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-16 09:09:28.790  5594  5624 D A2dpStateMachine: Enter Disconnected: -2
,09-16 09:09:28.791  5594  5594 I BluetoothHidServiceJni: classInitNative: succeeds
09-16 09:09:28.791  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:28.792  5594  5594 D HidService: Received start request. Starting profile...
09-16 09:09:28.792  5594  5594 I bt_bluedroid: get_profile_interface hidhost
09-16 09:09:28.792  5594  5594 D HidService: setHidService(): set to: null
09-16 09:09:28.792  5594  5610 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d6a56d
,09-16 09:09:28.793  5594  5610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-16 09:09:28.794  5594  5594 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-16 09:09:28.795  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:28.795  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 09:09:28.795  5594  5594 D HealthService: Received start request. Starting profile...
,09-16 09:09:28.798  5594  5594 I bt_bluedroid: get_profile_interface health
,09-16 09:09:28.800  5594  5594 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-16 09:09:28.800  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
09-16 09:09:28.801  5594  5594 D PanService: Received start request. Starting profile...
09-16 09:09:28.801  5594  5594 D BluetoothPanServiceJni: initializeNative(L110): pan
09-16 09:09:28.801  5594  5594 I bt_bluedroid: get_profile_interface pan
09-16 09:09:28.801  5594  5610 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-16 09:09:28.804  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:28.804  5594  5594 D BluetoothMapService: Received start request. Starting profile...
,09-16 09:09:28.804  5594  5594 D BluetoothMapService: start()
,09-16 09:09:28.807  5594  5594 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-16 09:09:28.808  5594  5594 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-16 09:09:28.808  5594  5594 D BluetoothMapAppObserver: createReceiver()
09-16 09:09:28.810  5594  5594 D BluetoothMapAppObserver: initObservers()
09-16 09:09:28.810  5594  5594 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-16 09:09:28.815  5594  5594 V BluetoothAdapterState: isTurningOff()=false
,09-16 09:09:28.815  5594  5594 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:28.815  5594  5594 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:28.815  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:28.816  5594  5622 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-16 09:09:28.817  5594  5594 V SapService: SapBinder()
09-16 09:09:28.817  5594  5594 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:28.817  5594  5594 D SapService: Received start request. Starting profile...
09-16 09:09:28.817  5594  5594 V SapService: start()
,09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isTurningOff()=false
,09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:28.819  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
,09-16 09:09:28.820  5594  5594 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:28.820  5594  5594 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:28.820  5594  5594 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:28.820  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:28.820  5594  5594 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:28.820  5594  5594 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:28.820  5594  5594 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:28.821  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:28.821  5594  5594 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:28.821  5594  5594 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:28.821  5594  5594 V BluetoothAdapterState: isBleTurningOn()=false
,09-16 09:09:28.821  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:28.823  5594  5594 V BluetoothAdapterState: isTurningOff()=false
09-16 09:09:28.823  5594  5594 V BluetoothAdapterState: isTurningOn()=true
09-16 09:09:28.823  5594  5594 V BluetoothAdapterState: isBleTurningOn()=false
09-16 09:09:28.823  5594  5594 V BluetoothAdapterState: isBleTurningOff()=false
09-16 09:09:28.823  5594  5606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-16 09:09:28.823  5594  5606 D BluetoothAdapterProperties: ScanMode =  20
09-16 09:09:28.823  5594  5606 D BluetoothAdapterProperties: State =  11
09-16 09:09:28.824  5594  5610 D BluetoothAdapterProperties: Scan Mode:21
09-16 09:09:28.824  5594  5610 D BluetoothAdapterProperties: Discoverable Timeout:120
09-16 09:09:28.824  5594  5606 D BluetoothAdapterProperties: Setting state to 12
09-16 09:09:28.824  5594  5606 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-16 09:09:28.825  3072  5383 D BluetoothMap: onBluetoothStateChange: up=true
09-16 09:09:28.827  5594  5606 I BluetoothAdapterState: Entering OnState
09-16 09:09:28.828  5436  5448 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 09:09:28.828  3072  3072 D BluetoothMap: Proxy object connected
09-16 09:09:28.828  3072  3072 D MapProfile: Bluetooth service connected
09-16 09:09:28.828  3072  3072 D BluetoothMap: getConnectedDevices()
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:28.829  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:28.830  3072  3089 D BluetoothPbap: onBluetoothStateChange: up=true
,09-16 09:09:28.831  5436  5436 D BluetoothInputDevice: Proxy object connected
09-16 09:09:28.832  5436  5436 D HidProfile: Bluetooth service connected
09-16 09:09:28.832  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:28.833  5436  5589 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:28.834  3497  3824 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:28.835  3072  3093 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 09:09:28.836  5594  5594 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-16 09:09:28.836   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 09:09:28.837  3072  5383 D BluetoothPan: onBluetoothStateChange on: true
09-16 09:09:28.837  5594  5594 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-16 09:09:28.838  5594  5594 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 09:09:28.839  5436  5448 D BluetoothPan: onBluetoothStateChange on: true
09-16 09:09:28.839  5594  5594 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 09:09:28.840   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-16 09:09:28.840   924   941 D BluetoothA2dp: onBluetoothStateChange: up=true
09-16 09:09:28.841  5594  5594 D ObexServerSockets: Succeed to create listening sockets 
09-16 09:09:28.841  5594  5594 D ObexServerSockets0: startAccept()
09-16 09:09:28.841  5594  5594 D ObexServerSockets0: prepareForNewConnect()
09-16 09:09:28.841   924   941 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:28.841  3072  3679 D BluetoothHeadset: onBluetoothStateChange: up=true
09-16 09:09:28.841  5436  5447 D BluetoothPbap: onBluetoothStateChange: up=true
09-16 09:09:28.843  5594  5594 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-16 09:09:28.843  5594  5594 D BluetoothSdpJni: SDP Create record success - handle: 0
09-16 09:09:28.843  5436  5589 D BluetoothMap: onBluetoothStateChange: up=true
09-16 09:09:28.843  5594  5633 D ObexServerSockets0: Accepting socket connection...
09-16 09:09:28.843  5594  5632 D ObexServerSockets0: Accepting socket connection...
09-16 09:09:28.844   924   924 D BluetoothA2dp: Proxy object connected
09-16 09:09:28.844  3072  3072 D BluetoothA2dp: Proxy object connected
,09-16 09:09:28.845  5436  5436 D BluetoothPan: BluetoothPAN Proxy object connected
,09-16 09:09:28.846  5436  5436 D PanProfile: Bluetooth service connected
09-16 09:09:28.846  5436  5436 D BluetoothMap: Proxy object connected
09-16 09:09:28.846  5436  5436 D MapProfile: Bluetooth service connected
09-16 09:09:28.846  5436  5436 D BluetoothMap: getConnectedDevices()
09-16 09:09:28.846  3072  5383 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-16 09:09:28.847  3072  3072 D BluetoothPan: BluetoothPAN Proxy object connected
09-16 09:09:28.847  3072  3072 D PanProfile: Bluetooth service connected
09-16 09:09:28.848  5436  5448 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-16 09:09:28.848  3072  3072 D BluetoothInputDevice: Proxy object connected
,09-16 09:09:28.849  3072  3072 D HidProfile: Bluetooth service connected
,09-16 09:09:28.851  5436  5436 D BluetoothA2dp: Proxy object connected
,09-16 09:09:28.851   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
09-16 09:09:28.851  5594  5594 D BluetoothMapService: onReceive
09-16 09:09:28.852  5594  5594 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-16 09:09:28.852  5594  5594 D BluetoothMapService: STATE_ON
,09-16 09:09:28.853  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:28.855  5594  5634 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-16 09:09:28.856  5594  5634 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-16 09:09:28.856  5594  5634 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-16 09:09:28.858  5436  5436 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-16 09:09:28.864  3558  3558 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-16 09:09:28.865  5436  5436 D DockEventReceiver: finishStartingService: stopping service
,09-16 09:09:28.872  5436  5436 D BluetoothPbap: Proxy object connected
,09-16 09:09:28.872  5436  5436 D PbapServerProfile: Bluetooth service connected
,09-16 09:09:28.876  5594  5594 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-16 09:09:28.876  5594  5594 D ObexServerSockets0: prepareForNewConnect()
,09-16 09:09:28.878  5594  5638 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 09:09:28.880  3072  3072 D BluetoothPbap: Proxy object connected
,09-16 09:09:28.880  3072  3072 D PbapServerProfile: Bluetooth service connected
,09-16 09:09:28.892  5594  5642 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-16 09:09:28.894  5594  5642 I BtOppRfcommListener: Accept thread started.
,09-16 09:09:28.937  3497  3516 D BluetoothHeadset: Proxy object connected
09-16 09:09:28.937   924   924 D BluetoothHeadset: Proxy object connected
09-16 09:09:28.937   924   924 D BluetoothHeadset: Proxy object connected
,09-16 09:09:28.937   924   924 D BluetoothHeadset: Proxy object connected
09-16 09:09:28.938  5436  5447 D BluetoothHeadset: Proxy object connected
09-16 09:09:28.938  3072  3089 D BluetoothHeadset: Proxy object connected
,09-16 09:09:28.938  3072  3072 D HeadsetProfile: Bluetooth service connected
09-16 09:09:28.939  5436  5436 D HeadsetProfile: Bluetooth service connected
,09-16 09:09:28.941   924   941 D BluetoothHeadset: Proxy object connected
09-16 09:09:28.941   924   941 D BluetoothHeadset: Proxy object connected
09-16 09:09:28.941  3072  3093 D BluetoothHeadset: Proxy object connected
,09-16 09:09:28.941  3072  3072 D HeadsetProfile: Bluetooth service connected
,09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:29.771  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:29.777  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-16 09:09:29.780  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 09:09:29.780  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c16c994 added. We now have 8 listener(s)
09-16 09:09:29.781  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 09:09:29.785   924  3686 D WifiService: setWifiEnabled: false pid=5384, uid=10077
09-16 09:09:29.785   924  3686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 09:09:29.793  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:29.793   924   935 D WifiService: setWifiEnabled: true pid=5384, uid=10077
09-16 09:09:29.794   924   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-16 09:09:29.800   508   918 D SoftapController: Softap fwReload - Ok
,09-16 09:09:29.802   508   918 D CommandListener: Setting iface cfg
,09-16 09:09:29.802   508   918 D CommandListener: Trying to bring down wlan0
,09-16 09:09:29.803   508   918 D CommandListener: Clearing all IP addresses on wlan0
,09-16 09:09:29.806   924  2930 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-16 09:09:30.420   924  2930 D wifi    : set interface wlan0 flags (UP)
,09-16 09:09:30.424   924  2930 I WifiHAL : Initializing wifi
09-16 09:09:30.425   924  2930 I WifiHAL : Creating socket
,09-16 09:09:30.426   924   941 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-16 09:09:30.433   924  2930 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-16 09:09:30.434   924  2930 D wifi    : Did set static halHandle = 0x7f5d0b1a80
09-16 09:09:30.434   924  2930 D wifi    : halHandle = 0x7f5d0b1a80, mVM = 0x7f788cd140, mCls = 0x199a
09-16 09:09:30.434   924  2930 D wifi    : array field set
09-16 09:09:30.434   924  2930 I WifiNative-HAL: interface[0] = wlan0
09-16 09:09:30.436   924  5647 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547021855360
09-16 09:09:30.437   924  5647 D wifi    : waitForHalEvents called, vm = 0x7f788cd140, obj = 0x199a, env = 0x7f58c26f80
09-16 09:09:30.440   924  2930 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
09-16 09:09:30.442   924  2930 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-16 09:09:30.446  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:30.478   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:30.500  5648  5648 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-16 09:09:30.522  5648  5648 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 09:09:30.529  5648  5648 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-16 09:09:30.529  5648  5648 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-16 09:09:31.462   924  2930 D WifiConfigStore: Loading config and enabling all networks 
,09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:31.468  5384  5384 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-16 09:09:31.472  5384  5384 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 09:09:31.478   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:31.487   924  2930 D WifiConfigStore: loaded 0 passpoint configs
,09-16 09:09:31.487   924  2930 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-16 09:09:31.488   924  2930 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-16 09:09:31.489   924  2930 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-16 09:09:31.491   924  2930 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-16 09:09:31.491   924  2930 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-16 09:09:31.491   924  2930 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
,09-16 09:09:31.491   924  2930 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-16 09:09:31.496   924  2930 D WifiNative-HAL: Setting external_sim to 1
,09-16 09:09:31.496  4254  4254 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-16 09:09:31.496   924  2930 D wifi    : setting dfs flag to true, 0x7f59e95e20
09-16 09:09:31.497   924  2930 D WifiStateMachine: Setting OUI to DA-A1-19
09-16 09:09:31.497   924  2930 D wifi    : setting scan oui 0x7f59e95e20
,09-16 09:09:31.498   924  2930 D WifiHAL : Sending mac address OUI
,09-16 09:09:31.503   924  2930 E native  : do suspend false
,09-16 09:09:31.514   924   924 D RttService: SCAN_AVAILABLE : 3
,09-16 09:09:31.514   924  2930 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-16 09:09:31.514   924  3037 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-16 09:09:31.514   508   918 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-16 09:09:31.516   508   918 D CommandListener: Setting iface cfg
,09-16 09:09:31.520   924  2929 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,09-16 09:09:31.520   924  2929 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-16 09:09:31.530   924  2929 D WifiNative-HAL: p2pGetDeviceAddress
,09-16 09:09:31.535   924  2929 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-16 09:09:31.536   924   939 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=255413 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:31.812  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:31.817  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 09:09:31.827  5384  5430 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-16 09:09:31.829  5384  5430 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-16 09:09:31.834  5384  5430 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@360511a Bundle[{}]
,09-16 09:09:31.835  5384  5430 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-16 09:09:31.835  5384  5430 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-16 09:09:31.836  5384  5430 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-16 09:09:31.837  5384  5430 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-16 09:09:31.838  5384  5430 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-16 09:09:31.840  5384  5430 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-16 09:09:31.846  5384  5430 I System.out: Running OutgoingSocketThread
,09-16 09:09:31.848  5384  5650 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,09-16 09:09:31.850  5384  5650 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44699
09-16 09:09:31.850  5384  5650 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-16 09:09:32.479   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:32.850  5384  5430 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,09-16 09:09:32.850  5384  5430 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,09-16 09:09:32.858  5384  5430 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,09-16 09:09:32.859  5384  5430 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-16 09:09:32.859  5384  5430 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-16 09:09:32.864  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 09:09:32.864  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3971c3d added. We now have 2 listener(s)
,09-16 09:09:32.868  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 09:09:32.868  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:32.868  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:32.868  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-16 09:09:32.868  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61fcc32 added. We now have 9 listener(s)
09-16 09:09:32.868  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:32.869  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 09:09:32.872  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:32.877  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:32.879  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 09:09:32.880  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:32.880  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 09:09:32.880  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360eb00 added. We now have 3 listener(s)
09-16 09:09:32.881  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:32.882  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 09:09:32.882  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:32.882  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:32.882  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:32.882  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de3f39 added. We now have 10 listener(s)
09-16 09:09:32.882  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 09:09:32.883  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:32.883  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:32.883  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:32.883  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 09:09:32.883  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:32.883  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.883  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:32.883  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:32.883  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3971c3d removed from the list
,09-16 09:09:32.884  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.884  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61fcc32 removed from the list
09-16 09:09:32.884  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:32.884  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 09:09:32.885  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.885  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 09:09:32.887  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:32.887  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:32.887  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.888  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61fcc32 not in the list
09-16 09:09:32.888  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.888  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 09:09:32.890  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-16 09:09:32.891  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:32.891  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.891  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9de3f39 removed from the list
09-16 09:09:32.891  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:32.891  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.891  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:32.891  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:32.891  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@360eb00 removed from the list
,09-16 09:09:32.892  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 09:09:32.892  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fa797e added. We now have 2 listener(s)
,09-16 09:09:32.894  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-16 09:09:32.894  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:32.894  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:32.894  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:32.894  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61e4edf added. We now have 9 listener(s)
09-16 09:09:32.894  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:32.895  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 09:09:32.898  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:32.901  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:32.902  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:32.903  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 09:09:32.903  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 09:09:32.903  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8da95f5 added. We now have 3 listener(s)
,09-16 09:09:32.904  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:32.905  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:32.905  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:32.905  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:32.905  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:32.905  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f40af8a added. We now have 10 listener(s)
09-16 09:09:32.905  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:32.905  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:32.905  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 09:09:32.905  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 09:09:32.905  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:32.905  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 09:09:32.906  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:32.909  5384  5430 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 09:09:32.909  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 09:09:32.913  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 09:09:32.914  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 09:09:32.914  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-16 09:09:32.916  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 09:09:32.916  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 09:09:32.916  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 09:09:32.917  5384  5430 D BluetoothAdapter: STATE_ON
,09-16 09:09:32.919  5594  5604 D BtGatt.GattService: registerClient() - UUID=312a501c-d325-4d48-a23c-169a75ae23ea
09-16 09:09:32.920  5594  5610 D BtGatt.GattService: onClientRegistered() - UUID=312a501c-d325-4d48-a23c-169a75ae23ea, clientIf=5
,09-16 09:09:32.921  5384  5394 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 09:09:32.921  5594  5630 D BtGatt.GattService: start scan with filters
,09-16 09:09:32.924  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 09:09:32.924  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-16 09:09:32.924  5594  5613 D BtGatt.ScanManager: handling starting scan
09-16 09:09:32.924  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 09:09:32.924  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 09:09:32.927  5594  5613 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@fc0220e
,09-16 09:09:32.927  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:32.927  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 09:09:32.927  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 09:09:32.928  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-16 09:09:32.930  5384  5430 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-16 09:09:32.930  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:32.930  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-16 09:09:32.931  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.931  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 09:09:32.931  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-16 09:09:32.931  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 09:09:32.931  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 09:09:32.931  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 09:09:32.931  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 09:09:32.931  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 09:09:32.932  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:32.932  5594  5630 D BtGatt.GattService: stopScan() - queue size =1
,09-16 09:09:32.933  5594  5610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 09:09:32.933  5594  5629 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 09:09:32.933  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.933  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 09:09:32.933  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 09:09:32.933  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 09:09:32.933  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 09:09:32.933  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 09:09:32.933  5594  5613 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 09:09:32.934  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 09:09:32.934  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 09:09:32.934  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 09:09:32.935  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-16 09:09:32.935  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:32.936  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:32.936  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:32.936  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-16 09:09:32.938  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:32.938  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 09:09:32.938  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:32.938  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:32.938  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.938  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:32.938  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:32.938  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9fa797e removed from the list
09-16 09:09:32.938  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.938  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61e4edf removed from the list
,09-16 09:09:32.938  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:32.938  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:32.939  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.939  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:32.939  5594  5610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 09:09:32.939  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.939  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:32.939  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:32.939  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.940  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@61e4edf not in the list
09-16 09:09:32.940  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.940  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:32.940  5594  5613 D BtGatt.ScanManager: Starting BLE batch scan
09-16 09:09:32.940  5594  5613 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 09:09:32.940  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:32.940  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:32.940  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.941  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f40af8a removed from the list
09-16 09:09:32.941  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:32.941  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.941  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:32.941  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:32.941  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8da95f5 removed from the list
,09-16 09:09:32.941  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 09:09:32.942  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a023a56 added. We now have 2 listener(s)
09-16 09:09:32.943  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:32.943  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:32.943  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:32.943  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:32.944  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d3ad7 added. We now have 9 listener(s)
09-16 09:09:32.944  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:32.944  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-16 09:09:32.947  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:32.950  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:32.950  5594  5610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 09:09:32.950  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 09:09:32.952  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:32.952  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-16 09:09:32.953  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 09:09:32.953  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c8ead added. We now have 3 listener(s)
09-16 09:09:32.954  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:32.955  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:32.955  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:32.955  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:32.955  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:32.955  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7fa5e2 added. We now have 10 listener(s)
09-16 09:09:32.955  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 09:09:32.955  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:32.955  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:32.956  5594  5610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 09:09:32.956  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:32.956  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 09:09:32.956  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.956  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-16 09:09:32.956  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:32.956  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-16 09:09:32.959  5384  5430 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-16 09:09:32.959  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-16 09:09:32.962  5594  5610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-16 09:09:32.963  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.963  5594  5613 D BtGatt.ScanManager: stopping BLe Batch
09-16 09:09:32.964  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-16 09:09:32.964  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 09:09:32.964  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 09:09:32.968  5594  5610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 09:09:32.968  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.968  5594  5613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-16 09:09:32.968  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-16 09:09:32.968  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 09:09:32.968  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-16 09:09:32.969  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:32.971  5594  5605 D BtGatt.GattService: registerClient() - UUID=b1be6b74-3009-4019-91ee-cac31d98839b
09-16 09:09:32.971  5594  5610 D BtGatt.GattService: onClientRegistered() - UUID=b1be6b74-3009-4019-91ee-cac31d98839b, clientIf=5
09-16 09:09:32.971  5384  5394 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-16 09:09:32.972  5594  5610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 09:09:32.972  5594  5604 D BtGatt.GattService: start scan with filters
09-16 09:09:32.972  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 09:09:32.974  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-16 09:09:32.974  5594  5613 D BtGatt.ScanManager: handling starting scan
09-16 09:09:32.974  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 09:09:32.974  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 09:09:32.974  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 09:09:32.976  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:32.976  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-16 09:09:32.976  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-16 09:09:32.977  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 09:09:32.978  5594  5610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 09:09:32.978  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.978  5594  5613 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 09:09:32.979  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:32.979  5384  5430 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-16 09:09:32.979  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:32.979  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:32.979  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-16 09:09:32.979  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:32.979  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.979  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 09:09:32.980  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:32.980  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a023a56 removed from the list
09-16 09:09:32.980  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.980  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d3ad7 removed from the list
09-16 09:09:32.980  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:32.980  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:32.980  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.980  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-16 09:09:32.980  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.980  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:32.981  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:32.981  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:32.981  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.982  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53d3ad7 not in the list
09-16 09:09:32.982  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 09:09:32.982  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 09:09:32.982  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 09:09:32.982  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-16 09:09:32.982  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-16 09:09:32.982  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:32.983  5594  5610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-16 09:09:32.983  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.983  5594  5613 D BtGatt.ScanManager: Starting BLE batch scan
09-16 09:09:32.983  5594  5613 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-16 09:09:32.983  5594  5604 D BtGatt.GattService: stopScan() - queue size =1
09-16 09:09:32.983  5594  5630 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-16 09:09:32.984  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-16 09:09:32.984  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 09:09:32.984  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 09:09:32.984  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 09:09:32.984  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-16 09:09:32.987  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:32.987  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 09:09:32.987  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 09:09:32.987  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 09:09:32.988  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-16 09:09:32.989  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:32.989  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-16 09:09:32.989  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:32.989  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7fa5e2 removed from the list
09-16 09:09:32.989  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:32.989  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:32.989  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:32.989  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:32.989  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:32.989  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:32.989  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:32.989  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@96c8ead removed from the list
,09-16 09:09:32.990  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 09:09:32.990  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e763e2e added. We now have 2 listener(s)
09-16 09:09:32.990  5594  5610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 09:09:32.990  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.991  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:32.991  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:32.991  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:32.991  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:32.992  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4deadcf added. We now have 9 listener(s)
09-16 09:09:32.992  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-16 09:09:32.992  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 09:09:32.994  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:32.995  5594  5610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-16 09:09:32.995  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:32.997  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:32.998  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-16 09:09:32.999  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:32.999  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-16 09:09:32.999  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde665 added. We now have 3 listener(s)
,09-16 09:09:33.000  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:33.000  5594  5610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 09:09:33.000  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:33.000  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.000  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:33.000  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:33.000  5594  5613 D BtGatt.ScanManager: stopping BLe Batch
09-16 09:09:33.000  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:33.000  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2c0f3a added. We now have 10 listener(s)
09-16 09:09:33.001  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:33.001  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:33.001  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-16 09:09:33.001  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-16 09:09:33.001  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-16 09:09:33.001  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-16 09:09:33.001  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:33.004  5384  5430 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-16 09:09:33.004  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-16 09:09:33.005  5594  5610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-16 09:09:33.005  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.005  5594  5613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 09:09:33.009  5594  5610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-16 09:09:33.009  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.009  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-16 09:09:33.010  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-16 09:09:33.010  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-16 09:09:33.013  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-16 09:09:33.013  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-16 09:09:33.013  5384  5430 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-16 09:09:33.014  5384  5430 D BluetoothAdapter: STATE_ON
,09-16 09:09:33.015  5594  5630 D BtGatt.GattService: registerClient() - UUID=2b8bdbe0-0275-4187-88f5-23662d316031
,09-16 09:09:33.016  5594  5610 D BtGatt.GattService: onClientRegistered() - UUID=2b8bdbe0-0275-4187-88f5-23662d316031, clientIf=5
,09-16 09:09:33.016  5384  5395 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-16 09:09:33.016  5594  5604 D BtGatt.GattService: start scan with filters
09-16 09:09:33.018  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-16 09:09:33.018  5594  5613 D BtGatt.ScanManager: handling starting scan
09-16 09:09:33.018  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-16 09:09:33.018  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-16 09:09:33.018  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-16 09:09:33.020  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:33.020  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-16 09:09:33.020  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-16 09:09:33.021  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-16 09:09:33.022  5594  5610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-16 09:09:33.022  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.023  5594  5613 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-16 09:09:33.025  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-16 09:09:33.025  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-16 09:09:33.025  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:33.025  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:33.025  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:33.025  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-16 09:09:33.026  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:33.026  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e763e2e removed from the list
09-16 09:09:33.026  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:33.026  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4deadcf removed from the list
09-16 09:09:33.026  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:33.026  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:33.026  5594  5610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-16 09:09:33.026  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.026  5594  5613 D BtGatt.ScanManager: Starting BLE batch scan
09-16 09:09:33.026  5594  5613 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-16 09:09:33.026  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:33.027  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-16 09:09:33.027  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-16 09:09:33.027  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:33.028  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:33.028  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:33.028  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:33.028  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4deadcf not in the list
09-16 09:09:33.028  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-16 09:09:33.028  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-16 09:09:33.028  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-16 09:09:33.028  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-16 09:09:33.028  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-16 09:09:33.029  5384  5430 D BluetoothAdapter: STATE_ON
09-16 09:09:33.029  5594  5631 D BtGatt.GattService: stopScan() - queue size =1
09-16 09:09:33.030  5594  5630 D BtGatt.GattService: unregisterClient() - clientIf=5
09-16 09:09:33.030  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-16 09:09:33.030  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-16 09:09:33.030  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-16 09:09:33.030  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-16 09:09:33.030  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-16 09:09:33.031  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:33.031  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-16 09:09:33.031  5384  5430 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-16 09:09:33.031  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-16 09:09:33.031  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:33.032  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:33.032  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:33.032  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:33.032  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:33.032  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e2c0f3a removed from the list
09-16 09:09:33.032  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:33.032  5384  5384 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-16 09:09:33.032  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:33.032  5384  5384 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-16 09:09:33.032  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:33.032  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:33.032  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2bde665 removed from the list
09-16 09:09:33.033  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 09:09:33.033  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3be506 added. We now have 2 listener(s)
09-16 09:09:33.033  5594  5610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-16 09:09:33.033  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.034  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:33.034  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:33.034  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:33.034  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:33.034  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ec87c7 added. We now have 9 listener(s)
09-16 09:09:33.034  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:33.035  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-16 09:09:33.037  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-16 09:09:33.039  5594  5610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-16 09:09:33.039  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-16 09:09:33.040  5384  5430 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-16 09:09:33.042  5384  5430 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-16 09:09:33.042  5384  5430 D io.jxcore.node.ConnectivityMonitor: start: OK
09-16 09:09:33.042  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-16 09:09:33.042  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37b7d1d added. We now have 3 listener(s)
,09-16 09:09:33.043  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-16 09:09:33.043  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-16 09:09:33.043  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-16 09:09:33.043  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-16 09:09:33.043  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-16 09:09:33.044  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d214b92 added. We now have 10 listener(s)
09-16 09:09:33.044  5384  5430 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-16 09:09:33.044  5384  5430 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-16 09:09:33.044  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-16 09:09:33.044  5384  5430 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-16 09:09:33.044  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:33.044  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:33.044  5594  5610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-16 09:09:33.044  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-16 09:09:33.044  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.044  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:33.044  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a3be506 removed from the list
09-16 09:09:33.044  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:33.044  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ec87c7 removed from the list
09-16 09:09:33.045  5384  5384 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-16 09:09:33.045  5384  5430 D io.jxcore.node.ConnectivityMonitor: stop
09-16 09:09:33.045  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:33.045  5594  5613 D BtGatt.ScanManager: stopping BLe Batch
09-16 09:09:33.045  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:33.045  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:33.046  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:33.046  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:33.046  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:33.046  5384  5430 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ec87c7 not in the list
09-16 09:09:33.046  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:33.046  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:33.047  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-16 09:09:33.047  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-16 09:09:33.047  5384  5430 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-16 09:09:33.047  5384  5430 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d214b92 removed from the list
09-16 09:09:33.047  5384  5430 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-16 09:09:33.048  5384  5430 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-16 09:09:33.048  5384  5430 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-16 09:09:33.048  5384  5430 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-16 09:09:33.048  5384  5430 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37b7d1d removed from the list
09-16 09:09:33.048  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-16 09:09:33.048  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-16 09:09:33.048  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-16 09:09:33.049  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-16 09:09:33.049  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-16 09:09:33.049  5384  5430 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-16 09:09:33.049  5594  5610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-16 09:09:33.049  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-16 09:09:33.049  5594  5613 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-16 09:09:33.052  5384  5651 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
,09-16 09:09:33.052  5384  5651 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
09-16 09:09:33.052  5384  5651 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-16 09:09:33.054  5594  5610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-16 09:09:33.054  5384  5652 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
09-16 09:09:33.054  5594  5610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-16 09:09:33.054  5384  5652 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
09-16 09:09:33.054  5384  5652 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-16 09:09:33.056  5384  5430 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-16 09:09:33.056  5384  5430 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-16 09:09:33.056  5384  5430 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-16 09:09:33.056  5384  5430 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-16 09:09:33.056  5384  5430 D com.test.thalitest.ThaliTestRunner: Total duration: 23533 ms
,09-16 09:09:33.057  5384  5430 I jxcore-log: *Native tests were executed*
09-16 09:09:33.057  5384  5430 I jxcore-log: 
,09-16 09:09:33.057  5384  5430 I jxcore-log: Total number of executed tests:  80
09-16 09:09:33.057  5384  5430 I jxcore-log: 
09-16 09:09:33.057  5384  5430 I jxcore-log: Number of passed tests:  80
09-16 09:09:33.057  5384  5430 I jxcore-log: 
09-16 09:09:33.058  5384  5430 I jxcore-log: Number of failed tests:  0
09-16 09:09:33.058  5384  5430 I jxcore-log: 
09-16 09:09:33.058  5384  5430 I jxcore-log: Number of ignored tests:  0
09-16 09:09:33.058  5384  5430 I jxcore-log: 
,09-16 09:09:33.058  5384  5430 I jxcore-log: Total duration:  23533
09-16 09:09:33.058  5384  5430 I jxcore-log: 
09-16 09:09:33.058  5384  5430 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-16 09:09:33.058  5384  5430 I jxcore-log: 
,09-16 09:09:33.061  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 09:09:33.061  5384  5430 I jxcore-log: 
09-16 09:09:33.062  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 09:09:33.062  5384  5430 I jxcore-log: 
09-16 09:09:33.062  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 09:09:33.062  5384  5430 I jxcore-log: 
09-16 09:09:33.063  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 09:09:33.063  5384  5430 I jxcore-log: 
09-16 09:09:33.063  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 09:09:33.063  5384  5430 I jxcore-log: 
09-16 09:09:33.064  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 09:09:33.064  5384  5430 I jxcore-log: 
09-16 09:09:33.065  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-16 09:09:33.065  5384  5430 I jxcore-log: 
09-16 09:09:33.066  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.066  5384  5430 I jxcore-log: 
09-16 09:09:33.067  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.067  5384  5430 I jxcore-log: 
09-16 09:09:33.067  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.067  5384  5430 I jxcore-log: 
09-16 09:09:33.067  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.067  5384  5430 I jxcore-log: 
09-16 09:09:33.068  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 09:09:33.068  5384  5430 I jxcore-log: 
09-16 09:09:33.069  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.069  5384  5430 I jxcore-log: 
09-16 09:09:33.069  5384  5384 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-16 09:09:33.069  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.069  5384  5430 I jxcore-log: 
09-16 09:09:33.069  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.069  5384  5430 I jxcore-log: 
09-16 09:09:33.070  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.070  5384  5430 I jxcore-log: 
09-16 09:09:33.070  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.070  5384  5430 I jxcore-log: 
09-16 09:09:33.070  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.070  5384  5430 I jxcore-log: 
09-16 09:09:33.071  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.071  5384  5430 I jxcore-log: 
09-16 09:09:33.071  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.071  5384  5430 I jxcore-log: 
09-16 09:09:33.071  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.071  5384  5430 I jxcore-log: 
09-16 09:09:33.072  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-16 09:09:33.072  5384  5430 I jxcore-log: 
09-16 09:09:33.072  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.072  5384  5430 I jxcore-log: 
09-16 09:09:33.072  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.072  5384  5430 I jxcore-log: 
09-16 09:09:33.073  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.073  5384  5430 I jxcore-log: 
09-16 09:09:33.073  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.073  5384  5430 I jxcore-log: 
09-16 09:09:33.073  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.073  5384  5430 I jxcore-log: 
09-16 09:09:33.074  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.074  5384  5430 I jxcore-log: 
09-16 09:09:33.074  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-16 09:09:33.074  5384  5430 I jxcore-log: 
,09-16 09:09:33.437  5384  5384 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-16 09:09:33.441  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 09:09:33.441  5384  5430 I jxcore-log: 
,09-16 09:09:33.480   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-16 09:09:33.490  5384  5384 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 09:09:33.494  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 09:09:33.494  5384  5430 I jxcore-log: 
,09-16 09:09:33.503  5653  5653 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-16 09:09:33.508  5653  5653 D AndroidRuntime: CheckJNI is OFF
,09-16 09:09:33.532  5384  5384 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-16 09:09:33.536  5384  5430 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-16 09:09:33.536  5384  5430 I jxcore-log: 
,09-16 09:09:33.537  5653  5653 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-16 09:09:33.567  5653  5653 I Radio-JNI: register_android_hardware_Radio DONE
,09-16 09:09:33.583  5653  5653 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-16 09:09:33.590   924   937 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-16 09:09:33.591   924   937 I ActivityManager: Killing 5384:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-16 09:09:33.661   924   934 I WindowState: WIN DEATH: Window{56ceaee u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-16 09:09:33.662   924  3112 D GraphicsStats: Buffer count: 2
09-16 09:09:33.662   924  2931 D WifiService: Client connection lost with reason: 4
,09-16 09:09:33.717   924   937 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-16 09:09:33.717   924   937 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-16 09:09:33.717   924   948 I art     : Starting a blocking GC Explicit
,09-16 09:09:33.718   924   937 E ActivityManager: Failure starting process com.test.thalitest
09-16 09:09:33.718   924   937 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-16 09:09:33.718   924   937 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:33.718   924   937 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:33.718   924   937 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 09:09:33.718   924   937 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-16 09:09:33.719   924   937 I ActivityManager:   Force finishing activity ActivityRecord{68bbb53 u0 com.test.thalitest/.MainActivity t4}
,09-16 09:09:33.729   924  3525 W ActivityManager: Spurious death for ProcessRecord{3d4edf9 0:com.test.thalitest/u0a77}, curProc for 5384: null
,09-16 09:09:33.733   924   942 W WindowManager: Attempted to add application window with unknown token Token{1c43c90 ActivityRecord{68bbb53 u0 com.test.thalitest/.MainActivity t4 f}}.  Aborting.
,09-16 09:09:33.733   924   942 W WindowManager: Token{1c43c90 ActivityRecord{68bbb53 u0 com.test.thalitest/.MainActivity t4 f}} already running, starting window not displayed. Unable to add window -- token Token{1c43c90 ActivityRecord{68bbb53 u0 com.test.thalitest/.MainActivity t4 f}} is not valid; is your activity running?
09-16 09:09:33.733   924   942 W WindowManager: view not successfully added to wm, removing view
09-16 09:09:33.734   924   942 W WindowManager: Exception when adding starting window
09-16 09:09:33.734   924   942 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{28ac3d8 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-16 09:09:33.734   924   942 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-16 09:09:33.734   924   942 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-16 09:09:33.734   924   942 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-16 09:09:33.734   924   942 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-16 09:09:33.734   924   942 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-16 09:09:33.734   924   942 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:33.734   924   942 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:33.734   924   942 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 09:09:33.734   924   942 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-16 09:09:33.792   924   948 I art     : Explicit concurrent mark sweep GC freed 24408(1548KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.365ms total 73.950ms
,09-16 09:09:33.810   924   948 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-16 09:09:33.812  5653  5653 I art     : System.exit called, status: 0
09-16 09:09:33.812  5653  5653 I AndroidRuntime: VM exiting with result code 0.
,09-16 09:09:33.830   924   948 I ActivityManager: Start proc 5663:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-16 09:09:33.830   924   948 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-16 09:09:33.835   924   937 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-16 09:09:33.840  5594  5594 D BluetoothMapAppObserver: onReceive
,09-16 09:09:33.840  5594  5594 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-16 09:09:33.848  3354  3354 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-16 09:09:33.854  3431  3908 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-16 09:09:33.863   924  2895 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-16 09:09:33.873  3354  5675 I Keyboard.Facilitator.DecoderInitializer: run()
,09-16 09:09:33.899  3497  3497 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-16 09:09:33.900  3354  5675 I Decoder : createOrResetDecoder
,09-16 09:09:33.912   924   924 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-16 09:09:33.914    17    17 W kworker/2:0: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 09:09:33.905  3374  5676 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-16 09:09:33.921    17    17 W kworker/2:0: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 09:09:33.931   924   936 E PackageManager: Failed to write settings, restoring backup
09-16 09:09:33.931   924   936 E PackageManager: java.io.IOException: write failed: EBADF (Bad file descriptor)
09-16 09:09:33.931   924   936 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-16 09:09:33.931   924   936 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-16 09:09:33.931   924   936 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
09-16 09:09:33.931   924   936 E PackageManager: 	at java.io.OutputStreamWriter.flush(OutputStreamWriter.java:161)
09-16 09:09:33.931   924   936 E PackageManager: 	at java.io.BufferedWriter.flush(BufferedWriter.java:124)
09-16 09:09:33.931   924   936 E PackageManager: 	at org.kxml2.io.KXmlSerializer.flush(KXmlSerializer.java:477)
09-16 09:09:33.931   924   936 E PackageManager: 	at org.kxml2.io.KXmlSerializer.endDocument(KXmlSerializer.java:169)
09-16 09:09:33.931   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4650)
09-16 09:09:33.931   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-16 09:09:33.931   924   936 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-16 09:09:33.931   924   936 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:33.931   924   936 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:33.931   924   936 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 09:09:33.931   924   936 E PackageManager: Caused by: android.system.ErrnoException: write failed: EBADF (Bad file descriptor)
09-16 09:09:33.931   924   936 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
09-16 09:09:33.931   924   936 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
09-16 09:09:33.931   924   936 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-16 09:09:33.931   924   936 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-16 09:09:33.931   924   936 E PackageManager: 	... 12 more
,09-16 09:09:33.935  3523  3664 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-16 09:09:33.931    17    17 W kworker/2:0: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-16 09:09:33.941  3558  3558 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-16 09:09:33.942  3558  3558 D AndroidRuntime: Shutting down VM
--------- beginning of crash
09-16 09:09:33.942  3558  3558 E AndroidRuntime: FATAL EXCEPTION: main
09-16 09:09:33.942  3558  3558 E AndroidRuntime: Process: com.google.process.gapps, PID: 3558
09-16 09:09:33.942  3558  3558 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-16 09:09:33.942  3558  3558 E AndroidRuntime: 	... 8 more
,09-16 09:09:33.951   924  3108 I ActivityManager: Start proc 5682:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-16 09:09:33.951  3523  3664 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-16 09:09:33.951  3523  3664 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3523
09-16 09:09:33.951  3523  3664 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:33.951  3523  3664 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-16 09:09:33.955   924  5688 E DropBoxManagerService: Can't write: system_app_crash
09-16 09:09:33.955   924  5688 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 09:09:33.955   924  5688 E DropBoxManagerService: 	... 5 more
,09-16 09:09:33.960   924  3686 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-16 09:09:33.965   924  5694 E DropBoxManagerService: Can't write: system_app_crash
09-16 09:09:33.965   924  5694 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop119.tmp: open failed: EROFS (Read-only file system)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-16 09:09:33.965   924  5694 E DropBoxManagerService: 	... 5 more
09-16 09:09:33.966  3558  3558 I Process : Sending signal. PID: 3558 SIG: 9
,09-16 09:09:33.968   383   383 E lowmemorykiller: Error writing /proc/3558/oom_score_adj; errno=22
,09-16 09:09:33.968   924   937 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2708)
09-16 09:09:33.969   924   937 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.gms/com.google.android.gms.app.receiver.SystemBroadcastReceiver}
09-16 09:09:33.969   924   937 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:168)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-16 09:09:33.969   924   937 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-16 09:09:33.971  3374  3404 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj031DBD985) - 
09-16 09:09:33.972  3374  3404 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-16 09:09:33.972  3374  3404 E AndroidRuntime: Process: android.process.acore, PID: 3374
09-16 09:09:33.972  3374  3404 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-16 09:09:33.972  3374  3404 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-16 09:09:33.988  3374  5676 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,09-16 09:09:33.988  3374  5676 I Process : Sending signal. PID: 3374 SIG: 9
,09-16 09:09:33.998   924  2931 D WifiService: Client connection lost with reason: 4
,09-16 09:09:34.000   924   937 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
,09-16 09:09:34.001   924   937 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-16 09:09:34.001   924   937 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 20999ms
,09-16 09:09:34.021   924   937 I ActivityManager: Start proc 5698:com.google.process.gapps/u0a12 for broadcast com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,09-16 09:09:34.024   924  3525 I ActivityManager: Process android.process.acore (pid 3374) has died
,09-16 09:09:34.024   924  3525 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30976ms
09-16 09:09:34.026   924  3518 W ActivityManager: Spurious death for ProcessRecord{607977b 5698:com.google.process.gapps/u0a12}, curProc for 3558: null
09-16 09:09:34.028  3523  3664 I Process : Sending signal. PID: 3523 SIG: 9
09-16 09:09:34.029   924  3379 W ActivityManager: Can't find mystery application for Crash from pid=3374 uid=10002: android.os.BinderProxy@6140898
,09-16 09:09:34.066   924  3686 D GraphicsStats: Buffer count: 1
,09-16 09:09:34.066   924  3525 I WindowState: WIN DEATH: Window{1149f67 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-16 09:09:34.071   924   935 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3523) has died
,09-16 09:09:34.072   924   935 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-16 09:09:34.073   924   935 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-16 09:09:34.089   924   937 I ActivityManager: Start proc 5710:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-16 09:09:34.310   385   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
