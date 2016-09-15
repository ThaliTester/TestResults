#### Test 85202518dd4c7ab_thali04_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-15 08:18:56.939   929  5181 D NetlinkSocketObserver: NeighborEvent{elapsedMs=323038, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-15 08:18:57.402  5430  5430 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 08:18:57.407  5430  5430 D AndroidRuntime: CheckJNI is OFF
09-15 08:18:57.432  5430  5430 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 08:18:57.464  5430  5430 I Radio-JNI: register_android_hardware_Radio DONE
09-15 08:18:57.479  5430  5430 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-15 08:18:57.488   929  3576 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-15 08:18:57.528   929  3576 I ActivityManager: Start proc 5439:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-15 08:18:57.533  5430  5430 D AndroidRuntime: Shutting down VM
09-15 08:18:57.636  5439  5439 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
09-15 08:18:57.664  5439  5439 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-15 08:18:57.689  5439  5439 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 3770-3789)
09-15 08:18:57.690  5439  5439 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 08:18:57.708  5439  5439 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c366bd8}
09-15 08:18:57.709  5439  5439 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-15 08:18:57.709  5439  5439 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-15 08:18:57.714  5439  5439 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-15 08:18:57.715  5439  5439 E SysUtils: ApplicationContext is null in ApplicationStatus
09-15 08:18:57.751  5439  5439 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-15 08:18:57.764  5439  5439 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-15 08:18:57.764  5439  5439 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-15 08:18:57.764  5439  5439 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-15 08:18:57.764  5439  5439 I Adreno  : Build Date                       : 12/06/15
09-15 08:18:57.764  5439  5439 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-15 08:18:57.764  5439  5439 I Adreno  : Local Branch                     : mybranch17112971
09-15 08:18:57.764  5439  5439 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-15 08:18:57.764  5439  5439 I Adreno  : Remote Branch                    : NONE
09-15 08:18:57.764  5439  5439 I Adreno  : Reconstruct Branch               : NOTHING
,09-15 08:18:57.818   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c39882:true
,09-15 08:18:57.852  3985  3985 W Binder_5: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[14003]" dev="sockfs" ino=14003 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 08:18:57.852  3985  3985 W Binder_5: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[14003]" dev="sockfs" ino=14003 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 08:18:57.868  5439  5439 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-15 08:18:57.877  5439  5439 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-15 08:18:57.902  3985  3985 W Binder_5: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31284]" dev="sockfs" ino=31284 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-15 08:18:57.905  3985  3985 W Binder_5: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31284]" dev="sockfs" ino=31284 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-15 08:18:57.907  5439  5476 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-15 08:18:57.908  3416  3416 W Binder_5: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[14008]" dev="sockfs" ino=14008 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 08:18:57.908  3416  3416 W Binder_5: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[14008]" dev="sockfs" ino=14008 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-15 08:18:57.914  5439  5463 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-15 08:18:57.951  5439  5476 I OpenGLRenderer: Initialized EGL, version 1.4
,09-15 08:18:58.026   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +446ms (total +525ms)
,09-15 08:18:58.052  5439  5439 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5439
,09-15 08:18:58.137  5439  5439 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-15 08:18:58.304  5439  5479 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -582219472
,09-15 08:18:58.309  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-15 08:18:58.309  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-15 08:18:58.309  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-15 08:18:58.309  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-15 08:18:58.309  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-15 08:18:58.309  5439  5479 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a78d29 added. We now have 1 listener(s)
09-15 08:18:58.313  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-15 08:18:58.314  5439  5479 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:18:58.315  5439  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:18:58.315  5439  5479 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-15 08:18:58.319  5439  5479 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a11dc added. We now have 1 listener(s)
09-15 08:18:58.319  5439  5479 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:18:58.325   929  2958 D WifiService: New client listening to asynchronous messages
09-15 08:18:58.326  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 08:18:58.326  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-15 08:18:58.326  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-15 08:18:58.326  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-15 08:18:58.326  5439  5479 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-15 08:18:58.329  5439  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:18:58.329  5439  5479 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
09-15 08:18:58.336  5439  5479 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:18:58.336  5439  5479 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:18:58.336  5439  5479 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-15 08:18:58.336  5439  5479 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:18:58.337  5439  5479 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 08:18:58.341  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:18:58.344  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:18:58.359  5439  5439 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-15 08:18:58.812  5439  5448 I art     : Background sticky concurrent mark sweep GC freed 76926(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.621ms total 245.490ms
,09-15 08:18:59.444  5439  5485 W jxcore-log: Initializing JXcore engine
09-15 08:18:59.444  5439  5485 W jxcore-log: JXcore engine is ready
,09-15 08:18:59.498  5485  5485 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12546 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-15 08:18:59.498  5485  5485 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[13457]" dev="sockfs" ino=13457 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-15 08:18:59.498  5485  5485 W Thread-57: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-15 08:18:59.498  5485  5485 W Thread-57: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[29653]" dev="sockfs" ino=29653 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-15 08:18:59.516  5439  5485 W jxcore-log: Starting JXcore engine
,09-15 08:18:59.579  5439  5485 W jxcore-log: Platform android
09-15 08:18:59.579  5439  5485 W jxcore-log: 
,09-15 08:18:59.579  5439  5485 W jxcore-log: Process ARCH arm
09-15 08:18:59.579  5439  5485 W jxcore-log: 
,09-15 08:18:59.675  5439  5485 I jxcore-log: JXcore Cordova bridge is ready!
09-15 08:18:59.675  5439  5485 I jxcore-log: 
,09-15 08:18:59.675  5439  5485 W jxcore-log: JXcore engine is started
,09-15 08:18:59.682  5439  5479 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-15 08:18:59.686  5439  5439 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-15 08:19:03.499   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:19:03.499   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:19:09.316  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-15 08:19:09.316  5439  5485 I jxcore-log: 
,09-15 08:19:09.318  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-15 08:19:09.318  5439  5485 I jxcore-log: 
,09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:09.322  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:19:09.324  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.325  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-15 08:19:09.325  5439  5485 I jxcore-log: 
,09-15 08:19:09.327  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-15 08:19:09.327  5439  5485 I jxcore-log: 
,09-15 08:19:09.570  5439  5485 I jxcore-log: Running unit tests
09-15 08:19:09.570  5439  5485 I jxcore-log: 
,09-15 08:19:09.571  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:19:09.571  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@861c3a9 added. We now have 2 listener(s)
,09-15 08:19:09.571  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 08:19:09.572  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:19:09.572  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-15 08:19:09.572  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 08:19:09.572  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f3fd2e added. We now have 2 listener(s)
09-15 08:19:09.572  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:19:09.572  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 08:19:09.574  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:09.577  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:09.578  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.578  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:19:09.578  5439  5485 D executeNativeTests: Running unit tests
,09-15 08:19:09.587  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:09.591  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:09.614  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 08:19:09.614  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c added. We now have 3 listener(s)
09-15 08:19:09.615  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:19:09.615  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:19:09.615  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:19:09.615  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:19:09.615  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 added. We now have 3 listener(s)
09-15 08:19:09.615  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:19:09.615  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:19:09.619  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:09.624  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:19:09.625  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.625  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:19:09.626  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 08:19:09.626  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:19:09.626  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:19:09.626  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:19:09.627  5439  5485 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-15 08:19:09.627  5439  5485 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-15 08:19:09.627  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 08:19:09.627  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:19:09.627  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:19:09.627  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-15 08:19:09.628  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:09.628  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:09.628  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:09.628  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:09.628  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:19:09.628  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.628  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:19:09.629  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:19:09.629  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c removed from the list
09-15 08:19:09.629  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:09.629  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 removed from the list
,09-15 08:19:09.635  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:09.635  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:09.635  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:09.636  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.636  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:09.636  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:09.636  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:09.636  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:09.636  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:09.637  5439  5485 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-15 08:19:09.637  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:09.637  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:09.637  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:09.638  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:09.638  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.638  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:09.638  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:09.638  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:09.638  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:09.638  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:09.638  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.638  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:09.638  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.638  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:09.638  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:09.638  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:09.638  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:09.638  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 08:19:09.641  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 08:19:09.642  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:09.642  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:09.642  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:09.642  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:09.642  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.642  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:09.642  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:09.642  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:09.642  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:09.642  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:09.642  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.642  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:09.642  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:09.642  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:09.643  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:09.643  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:09.643  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:09.643  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:09.643  5439  5485 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-15 08:19:09.644  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:09.647  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:09.648  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:09.648  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:19:09.648  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:19:09.648  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:19:09.648  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:19:09.648  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:19:09.649  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:19:09.650  5439  5485 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 08:19:09.650  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 08:19:09.651  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:09.653  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 08:19:09.655  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:09.655  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 08:19:09.656  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 08:19:09.657  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-15 08:19:09.659  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-15 08:19:09.659  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 08:19:09.660  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:19:09.660  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:19:09.661  5439  5485 D BluetoothAdapter: STATE_ON
09-15 08:19:09.663  4375  4391 D BtGatt.GattService: registerClient() - UUID=b0c28957-7fea-4763-a156-3bc3fe72df1e
09-15 08:19:09.663  4375  4464 D BtGatt.GattService: onClientRegistered() - UUID=b0c28957-7fea-4763-a156-3bc3fe72df1e, clientIf=5
09-15 08:19:09.664  5439  5449 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 08:19:09.665  4375  5215 D BtGatt.GattService: start scan with filters
09-15 08:19:09.668  4375  4468 D BtGatt.ScanManager: handling starting scan
09-15 08:19:09.668  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:19:09.668  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:19:09.668  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:19:09.669  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 08:19:09.669  4375  4468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:19:09.670  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:19:09.670  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:19:09.670  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:19:09.670  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 08:19:09.673  5439  5485 I io.jxcore.node.ConnectionHelper: start: OK
09-15 08:19:09.676  4375  4464 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 08:19:09.676  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:09.677  4375  4468 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 08:19:09.681  4375  4464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:19:09.682  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:09.682  4375  4468 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:19:09.682  4375  4468 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 08:19:09.691  4375  4464 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 08:19:09.691  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:09.696  4375  4464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:19:09.696  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:19:10.172  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
09-15 08:19:10.172  5439  5439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:19:10.172  5439  5439 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 08:19:14.677  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:14.677  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:14.677  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:19:14.677  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:14.678  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 08:19:14.678  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:19:14.678  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:19:14.678  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-15 08:19:14.678  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:19:14.679  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:19:14.679  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 08:19:14.681  5439  5485 D BluetoothAdapter: STATE_ON
,09-15 08:19:14.682  4375  4620 D BtGatt.GattService: stopScan() - queue size =1
,09-15 08:19:14.684  4375  4391 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 08:19:14.685  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 08:19:14.685  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:19:14.685  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 08:19:14.686  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:19:14.686  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:19:14.688  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 08:19:14.689  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 08:19:14.689  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:19:14.691  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 08:19:14.692  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:19:14.695  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:14.695  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:19:14.695  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:14.695  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 08:19:14.695  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 08:19:14.695  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:19:14.695  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:14.695  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:14.696  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:14.696  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:14.696  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:14.703  4375  4464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:19:14.704  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:14.704  4375  4468 D BtGatt.ScanManager: stopping BLe Batch
09-15 08:19:14.709  4375  4375 D BtGatt.ScanManager: awakened up at time 340809
09-15 08:19:14.715  4375  4464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 08:19:14.715  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:14.715  4375  4468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 08:19:14.738  4375  4464 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,09-15 08:19:14.738  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:14.738  4375  4464 D BtGatt.GattService: current time is 340838683108
09-15 08:19:14.739  4375  4464 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -90, 80, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -100, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0, 37, -47, 14, -113, 116, -46, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -98, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-15 08:19:14.740  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-15 08:19:14.742  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
09-15 08:19:14.742  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-15 08:19:14.742  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
09-15 08:19:14.743  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-15 08:19:14.744  3923  5486 I EventLogService: Aggregate from 1473940088879 (log), 1473940088879 (data)
,09-15 08:19:15.197  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:19:16.351   929  5181 D NetlinkSocketObserver: NeighborEvent{elapsedMs=342451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-15 08:19:18.500   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:19.502   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:19.698  5439  5485 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-15 08:19:19.704  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:19.714  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:19:19.719  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 08:19:19.719  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:19:19.719  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 08:19:19.719  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-15 08:19:19.720  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:19:19.720  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:19:19.720  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:19:19.725  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:19.727  5439  5485 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 08:19:19.728  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 08:19:19.730  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:19.735  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:19:19.737  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 08:19:19.737  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:19:19.744  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-15 08:19:19.744  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:19:19.745  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:19:19.745  5439  5485 D BluetoothAdapter: STATE_ON
,09-15 08:19:19.749  4375  4389 D BtGatt.GattService: registerClient() - UUID=603b3edb-2e87-487a-880b-2f5b505f89bd
,09-15 08:19:19.750  4375  4464 D BtGatt.GattService: onClientRegistered() - UUID=603b3edb-2e87-487a-880b-2f5b505f89bd, clientIf=5
09-15 08:19:19.751  5439  5449 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-15 08:19:19.751  4375  4627 D BtGatt.GattService: start scan with filters
,09-15 08:19:19.758  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 08:19:19.758  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:19:19.759  4375  4468 D BtGatt.ScanManager: handling starting scan
09-15 08:19:19.759  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:19:19.759  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 08:19:19.762  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:19:19.762  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:19:19.762  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 08:19:19.764  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 08:19:19.768  5439  5485 I io.jxcore.node.ConnectionHelper: start: OK
,09-15 08:19:19.769  4375  4464 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 08:19:19.769  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.769  4375  4468 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 08:19:19.771  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:19.771  5439  5485 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 08:19:19.771  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:19.771  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:19:19.771  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:19.771  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 08:19:19.771  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:19:19.771  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:19:19.771  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:19:19.771  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:19:19.772  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:19:19.772  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-15 08:19:19.772  5439  5485 D BluetoothAdapter: STATE_ON
09-15 08:19:19.773  4375  4391 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:19:19.774  4375  5215 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:19:19.774  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:19:19.775  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:19:19.775  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:19:19.775  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:19:19.775  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:19:19.776  4375  4464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:19:19.776  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.776  4375  4468 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:19:19.776  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:19:19.776  4375  4468 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 08:19:19.776  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:19:19.776  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:19:19.776  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-15 08:19:19.777  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:19:19.779  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:19.779  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:19.779  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:19:19.779  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:19.779  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:19.779  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:19.779  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:19.779  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:19.780  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:19.780  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:19.781  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:19.781  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:19.781  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:19.781  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:19:19.781  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:19.781  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:19:19.782  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:19:19.782  5439  5485 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-15 08:19:19.785  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:19.789  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:19.790  4375  4464 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-15 08:19:19.790  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:19:19.791  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:19.792  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:19:19.792  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:19:19.792  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:19:19.792  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-15 08:19:19.792  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:19:19.792  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:19:19.794  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:19.796  4375  4464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:19:19.796  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.797  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:19.798  5439  5485 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 08:19:19.799  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 08:19:19.804  4375  4464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:19:19.804  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.804  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:19:19.804  4375  4468 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:19:19.805  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 08:19:19.805  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-15 08:19:19.810  4375  4464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 08:19:19.810  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.810  4375  4468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:19:19.810  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 08:19:19.810  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-15 08:19:19.811  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:19:19.811  5439  5485 D BluetoothAdapter: STATE_ON
,09-15 08:19:19.816  4375  4464 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-15 08:19:19.816  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.817  4375  5215 D BtGatt.GattService: registerClient() - UUID=9cb77c2b-a97e-48bb-aca4-a5afe3dabb2f
09-15 08:19:19.818  4375  4464 D BtGatt.GattService: onClientRegistered() - UUID=9cb77c2b-a97e-48bb-aca4-a5afe3dabb2f, clientIf=5
,09-15 08:19:19.818  5439  5450 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:19:19.818  4375  4627 D BtGatt.GattService: start scan with filters
,09-15 08:19:19.821  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:19:19.821  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:19:19.821  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-15 08:19:19.821  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-15 08:19:19.823  4375  4468 D BtGatt.ScanManager: handling starting scan
,09-15 08:19:19.825  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:19:19.825  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:19:19.825  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:19:19.826  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 08:19:19.828  5439  5485 I io.jxcore.node.ConnectionHelper: start: OK
09-15 08:19:19.830  4375  4464 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 08:19:19.830  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.830  4375  4468 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 08:19:19.835  4375  4464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 08:19:19.835  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:19.835  4375  4468 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:19:19.835  4375  4468 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 08:19:19.843  4375  4464 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 08:19:19.843  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:19:19.847  4375  4464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 08:19:19.847  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:19:20.327  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 08:19:20.327  5439  5439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:19:20.327  5439  5439 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 08:19:20.503   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:21.505   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:22.506   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:23.506   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:19:24.828  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:24.829  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:19:24.829  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-15 08:19:24.829  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:24.829  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 08:19:24.829  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:19:24.830  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:19:24.830  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:19:24.830  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:19:24.830  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:19:24.830  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 08:19:24.832  5439  5485 D BluetoothAdapter: STATE_ON
,09-15 08:19:24.835  4375  5215 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:19:24.839  4375  4627 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:19:24.840  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:19:24.840  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:19:24.840  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:19:24.840  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:19:24.841  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:19:24.843  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:19:24.844  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:19:24.844  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:19:24.844  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:19:24.845  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:19:24.846  4375  4375 D BtGatt.ScanManager: awakened up at time 350945
09-15 08:19:24.848  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:19:24.848  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:19:24.848  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 08:19:24.851  4375  4464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:19:24.851  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:24.851  4375  4468 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:19:24.857  4375  4464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 08:19:24.857  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:24.857  4375  4468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 08:19:24.874  4375  4464 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-15 08:19:24.874  4375  4464 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:19:24.874  4375  4464 D BtGatt.GattService: current time is 350974612034
09-15 08:19:24.875  4375  4464 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 72, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -78, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -83, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -89, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -76, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-15 08:19:24.875  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 08:19:24.875  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 08:19:24.875  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 08:19:24.876  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-15 08:19:24.876  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 08:19:24.876  4375  4464 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-15 08:19:25.349  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:19:25.349  5439  5439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:25.349  5439  5439 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 08:19:28.508   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:29.509   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:29.849  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:29.849  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:19:29.850  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.850  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.850  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.850  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:19:29.851  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
,09-15 08:19:29.851  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.851  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.851  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.851  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.853  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.853  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.856  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:19:29.856  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:29.856  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.857  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:29.858  5439  5485 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-15 08:19:29.860  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:29.860  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:29.860  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 08:19:29.860  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:19:29.861  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.861  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:29.861  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.861  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.861  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:29.861  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.861  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.861  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.862  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.862  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:29.865  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.865  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:29.865  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.865  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:29.867  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-15 08:19:29.868  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:29.868  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:19:29.868  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.868  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.868  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:29.868  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.868  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.868  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.869  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:29.869  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.869  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.869  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.869  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.869  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:29.871  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.872  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:29.872  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.872  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:29.873  5439  5485 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-15 08:19:29.873  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:29.873  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:19:29.874  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.874  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.874  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.874  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.874  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.874  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:29.874  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.874  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.875  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.875  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.875  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:29.875  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.877  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.877  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:29.877  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.877  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.878  5439  5485 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-15 08:19:29.878  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:29.879  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:29.879  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.879  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.879  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.879  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.879  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.879  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:29.879  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.879  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.880  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.880  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.880  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.880  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.882  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.882  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:29.882  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.882  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.883  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 08:19:29.883  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:19:29.884  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-15 08:19:29.884  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-15 08:19:29.884  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:19:29.884  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:19:29.884  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-15 08:19:29.884  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:19:29.884  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-15 08:19:29.884  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:29.885  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-15 08:19:29.885  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.885  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.885  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.885  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.885  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.885  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.885  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.885  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:19:29.886  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.886  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.886  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.886  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.888  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.888  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:29.888  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.888  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.889  5439  5485 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-15 08:19:29.889  5439  5485 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-15 08:19:29.889  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-15 08:19:29.894  5439  5485 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:19:29.895  5439  5485 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-15 08:19:29.895  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-15 08:19:29.895  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-15 08:19:29.895  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-15 08:19:29.895  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-15 08:19:29.896  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-15 08:19:29.896  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-15 08:19:29.896  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-15 08:19:29.896  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-15 08:19:29.898  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,09-15 08:19:29.898  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-15 08:19:29.898  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-15 08:19:29.898  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-15 08:19:29.898  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-15 08:19:29.899  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-15 08:19:29.900  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-15 08:19:29.900  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-15 08:19:29.900  5439  5485 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-15 08:19:29.900  5439  5485 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 08:19:29.900  5439  5485 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-15 08:19:29.901  5439  5485 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:19:29.901  5439  5485 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-15 08:19:29.901  5439  5485 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-15 08:19:29.901  5439  5485 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:19:29.901  5439  5485 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-15 08:19:29.901  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-15 08:19:29.905  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-15 08:19:29.906  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,09-15 08:19:29.906  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-15 08:19:29.907  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-15 08:19:29.907  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-15 08:19:29.907  5439  5485 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-15 08:19:29.907  5439  5485 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-15 08:19:29.908  5439  5485 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-15 08:19:29.908  5439  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
,09-15 08:19:29.909  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:29.909  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:29.909  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.909  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.909  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.909  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.909  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-15 08:19:29.910  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.910  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.910  5439  5488 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:19:29.911  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.911  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.911  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.911  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.911  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.911  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:29.908  4620  4620 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30246]" dev="sockfs" ino=30246 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 08:19:29.908  4620  4620 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30246]" dev="sockfs" ino=30246 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 08:19:29.912  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.912  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:19:29.912  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.912  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.914  5439  5485 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-15 08:19:29.914  5439  5489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-15 08:19:29.914  5439  5489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-15 08:19:29.914  5439  5489 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-15 08:19:29.914  4375  4617 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 5, channel: -1
09-15 08:19:29.914  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:29.915  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:29.915  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.915  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.915  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.915  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.915  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.915  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:29.915  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.915  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.915  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.915  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.915  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.915  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.917  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.917  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:19:29.917  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.917  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.918  5439  5485 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-15 08:19:29.918  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:29.918  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:29.918  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.919  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.919  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.919  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:29.919  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.919  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.919  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.919  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.919  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.919  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.919  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.919  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.919  5439  5488 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-15 08:19:29.921  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.921  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:19:29.921  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.921  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.922  5439  5485 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-15 08:19:29.922  5439  5485 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-15 08:19:29.922  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 08:19:29.922  5439  5485 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-15 08:19:29.922  5439  5485 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 08:19:29.922  5439  5485 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-15 08:19:29.922  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 08:19:29.922  5439  5485 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-15 08:19:29.922  5439  5485 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-15 08:19:29.923  5439  5485 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-15 08:19:29.923  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-15 08:19:29.923  5439  5485 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-15 08:19:29.923  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:29.923  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:29.923  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:29.923  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.923  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.923  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.923  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:29.923  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.924  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.924  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.924  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:29.924  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.924  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.924  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.925  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:29.925  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:29.926  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.926  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.926  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:29.927  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.927  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:29.927  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
,09-15 08:19:29.927  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:29.927  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:29.927  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:29.927  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:29.927  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:30.510   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:31.511   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:32.512   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:33.512   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:19:34.928  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:34.928  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.928  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:19:34.928  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.928  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.929  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
,09-15 08:19:34.929  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:34.929  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:34.929  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 08:19:34.930  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:19:34.930  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:34.930  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.930  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
,09-15 08:19:34.930  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:34.931  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.931  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:19:34.931  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.931  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.931  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.931  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:34.936  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:19:34.937  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:19:34.937  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:34.938  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:34.944  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-15 08:19:34.944  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:19:34.947  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 08:19:34.949  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-15 08:19:34.949  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 08:19:34.950  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 08:19:34.950  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-15 08:19:34.951  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:34.951  5439  5439 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 08:19:34.951  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 08:19:34.952  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-15 08:19:34.952  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-15 08:19:34.952  5439  5490 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:19:34.952  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.952  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-15 08:19:34.952  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:34.952  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:34.953  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:19:34.953  5439  5439 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 08:19:34.953  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:19:34.953  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:19:34.953  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:34.953  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.951  4627  4627 W Binder_4: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32160]" dev="sockfs" ino=32160 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 08:19:34.951  4627  4627 W Binder_4: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32160]" dev="sockfs" ino=32160 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 08:19:34.957  5439  5490 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 08:19:34.957  5439  5490 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-15 08:19:34.957  5439  5490 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 08:19:34.957  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:19:34.958  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.958  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:19:34.958  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:34.958  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:19:34.958  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:34.958  5439  5439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 08:19:34.958  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:34.958  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 08:19:34.958  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:34.958  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.958  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.958  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:34.959  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:34.959  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.959  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:34.959  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.959  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:34.959  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.959  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.962  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:34.962  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:34.962  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:34.963  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:34.967  5439  5485 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-15 08:19:34.967  5439  5485 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-15 08:19:34.968  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-15 08:19:34.968  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-15 08:19:34.968  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-15 08:19:34.969  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:34.969  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:34.969  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:34.969  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:34.969  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:34.969  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.969  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:34.969  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:34.970  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.971  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:34.971  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.971  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.972  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.972  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:34.976  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:34.976  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:34.976  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:34.976  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:34.981  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:19:34.981  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:34.981  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:34.981  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:19:34.981  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.981  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.982  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:34.982  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:34.982  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.982  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:34.982  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.982  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.982  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.982  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.983  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:19:34.983  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:34.983  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:34.983  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.985  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:19:34.985  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:19:34.985  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:19:34.985  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:19:34.985  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.985  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.985  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a5528c not in the list
09-15 08:19:34.985  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:19:34.985  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
09-15 08:19:34.985  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:34.985  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:34.985  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.986  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:34.986  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:34.987  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:19:34.987  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:19:34.987  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:34.987  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d2fdd5 not in the list
,09-15 08:19:34.989  5439  5485 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-15 08:19:34.989  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-15 08:19:34.989  5439  5485 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-15 08:19:34.989  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-15 08:19:34.989  5439  5485 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-15 08:19:34.989  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-15 08:19:34.992  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-15 08:19:34.992  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-15 08:19:34.993  5439  5485 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-15 08:19:34.993  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 08:19:34.993  5439  5485 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-15 08:19:34.993  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-15 08:19:34.993  5439  5485 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-15 08:19:34.993  5439  5485 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-15 08:19:34.994  5439  5485 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,09-15 08:19:34.994  5439  5485 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-15 08:19:34.995  5439  5485 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-15 08:19:34.995  5439  5485 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-15 08:19:34.995  5439  5485 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-15 08:19:34.996  5439  5485 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-15 08:19:34.997  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:19:34.997  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8912af added. We now have 3 listener(s)
09-15 08:19:34.998  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:19:35.000  5439  5485 D BluetoothAdapter: enable(): BT is already enabled..!
,09-15 08:19:35.000   929  3527 D WifiService: setWifiEnabled: true pid=5439, uid=10077
09-15 08:19:35.001   929  3527 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:19:35.040  4375  4587 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-15 08:19:35.041  4375  4587 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,09-15 08:19:35.459  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:19:40.007  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 08:19:40.007  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66876bc added. We now have 4 listener(s)
09-15 08:19:40.008  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:19:40.020  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:40.021  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66876bc removed from the list
,09-15 08:19:40.021  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:19:40.021  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:19:40.021  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:19:40.023  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 08:19:40.023  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@100645 added. We now have 4 listener(s)
,09-15 08:19:40.023  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:19:40.026  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:19:40.027  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@100645 removed from the list
09-15 08:19:40.027  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:19:40.027  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:19:40.027  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:19:40.029  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:19:40.029  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@719e19a added. We now have 4 listener(s)
09-15 08:19:40.029  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:19:40.035   929  3546 D WifiService: setWifiEnabled: false pid=5439, uid=10077
09-15 08:19:40.035   929  3546 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:19:40.045   929  2957 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-15 08:19:40.045   929  2957 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 08:19:40.045   929  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-15 08:19:40.045   929  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 08:19:40.053  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:19:40.052  4375  4460 D BluetoothAdapterState: Current state: ON, message: 23
09-15 08:19:40.053  4375  4460 D BluetoothAdapterProperties: Setting state to 13
09-15 08:19:40.054  4375  4460 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-15 08:19:40.055  4375  4460 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 08:19:40.056  4375  4460 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:19:40.058  4375  4464 D BluetoothAdapterProperties: Scan Mode:20
,09-15 08:19:40.058  4375  4460 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-15 08:19:40.059  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:40.059  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-15 08:19:40.060  4375  4375 D HeadsetService: Received stop request...Stopping profile...
09-15 08:19:40.060  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.061  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:40.061  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:19:40.064  3123  3137 D BluetoothHeadset: Proxy object disconnected
09-15 08:19:40.065  4375  4375 D A2dpService: Received stop request...Stopping profile...
09-15 08:19:40.065  3123  3123 D HeadsetProfile: Bluetooth service disconnected
09-15 08:19:40.065  4375  4622 D A2dpStateMachine: Exit Disconnected: -1
,09-15 08:19:40.065   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:19:40.065   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:19:40.066  3515  3769 D BluetoothHeadset: Proxy object disconnected
09-15 08:19:40.066  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.066   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:19:40.067   929  2957 E native  : do suspend true
,09-15 08:19:40.068   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 08:19:40.068  3123  3123 D BluetoothA2dp: Proxy object disconnected
09-15 08:19:40.069  4375  4375 D HidService: Received stop request...Stopping profile...
09-15 08:19:40.069  4375  4375 D HidService: Stopping Bluetooth HidService
09-15 08:19:40.070  3123  3123 D BluetoothInputDevice: Proxy object disconnected
09-15 08:19:40.070  3123  3123 D HidProfile: Bluetooth service disconnected
,09-15 08:19:40.071  4375  4375 V BluetoothAdapterState: isTurningOff()=true
09-15 08:19:40.071  4375  4375 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:40.071  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.071  4375  4375 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:40.072  4375  4375 D HealthService: Received stop request...Stopping profile...
,09-15 08:19:40.073  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:40.077  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:40.077  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:40.078  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.078  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:40.078  4375  4375 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-15 08:19:40.078  4375  4375 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-15 08:19:40.079  4375  4587 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:19:40.079  4375  4375 D PanService: Received stop request...Stopping profile...
09-15 08:19:40.079  4375  4587 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:19:40.079  4375  4587 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:19:40.080  3123  3123 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 08:19:40.080  3123  3123 D PanProfile: Bluetooth service disconnected
09-15 08:19:40.080  4375  4464 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,09-15 08:19:40.080  4375  4464 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 08:19:40.081  4375  4375 D BluetoothMapService: Received stop request...Stopping profile...
09-15 08:19:40.081  4375  4375 D BluetoothMapService: stop()
,09-15 08:19:40.082  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.082  4375  4375 D BluetoothMapAppObserver: deinitObservers()
,09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:40.082  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:40.082  4375  4375 D BluetoothMapAppObserver: removeReceiver()
09-15 08:19:40.083  4375  4375 V BluetoothAdapterState: isTurningOff()=true
09-15 08:19:40.083  3123  3123 D BluetoothMap: Proxy object disconnected
09-15 08:19:40.083  3123  3123 D MapProfile: Bluetooth service disconnected
09-15 08:19:40.083  4375  4375 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:40.083  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.083  4375  4375 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:40.083  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.083  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:40.084  4375  4587 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:19:40.084  4375  4375 V BluetoothAdapterState: isTurningOff()=true
09-15 08:19:40.084  4375  4375 V BluetoothAdapterState: isTurningOn()=false
,09-15 08:19:40.084  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.084  4375  4375 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:40.084  4375  4587 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:19:40.085  4375  4587 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 08:19:40.085  4375  4375 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 08:19:40.085  4375  4587 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:19:40.085  4375  4375 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 08:19:40.085  4375  4587 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 08:19:40.085  4375  4587 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:19:40.085  4375  4464 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 08:19:40.085  4375  4375 D SapService: Received stop request...Stopping profile...
09-15 08:19:40.085  4375  4375 V SapService: stop()
09-15 08:19:40.085  4375  4464 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 08:19:40.086  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.087  4375  4375 V BluetoothAdapterState: isTurningOff()=true
09-15 08:19:40.087  4375  4375 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:40.087  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.087  4375  4375 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:40.087  4375  4375 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 08:19:40.087  4375  4464 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 08:19:40.088  4375  4375 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-15 08:19:40.088  4375  4375 V BluetoothAdapterState: isTurningOff()=true
09-15 08:19:40.088  4375  4375 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:40.088  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.088  4375  4375 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:40.088  4375  4375 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 08:19:40.088  4375  4375 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 08:19:40.089   929  5182 D DhcpClient: Clearing IP address
09-15 08:19:40.089   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-15 08:19:40.090  4375  4375 D BluetoothMapService: MAP Service closeService in
09-15 08:19:40.090  4375  4375 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 08:19:40.090  4375  4375 D ObexServerSockets0: shutdown(block = true)
09-15 08:19:40.091  4375  4375 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 08:19:40.091  4375  4629 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-15 08:19:40.091  4375  4375 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 08:19:40.091  4375  4617 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-15 08:19:40.092  4375  4630 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-15 08:19:40.092  4375  4375 V BluetoothAdapterState: isTurningOff()=true
09-15 08:19:40.092  4375  4375 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:40.092  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.092  4375  4375 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:40.092  4375  4375 D BluetoothMapService: cleanup()
09-15 08:19:40.092  4375  4375 D BluetoothMapService: MAP Service closeService in
09-15 08:19:40.093  4375  4375 V BluetoothAdapterState: isTurningOff()=true
,09-15 08:19:40.093  4375  4375 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:40.093  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.093  4375  4375 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:40.094   509   923 D CommandListener: Setting iface cfg
09-15 08:19:40.096  4375  4460 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-15 08:19:40.096  4375  4460 D BluetoothAdapterProperties: Setting state to 15
09-15 08:19:40.096  4375  4460 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 08:19:40.096  4375  4460 I BluetoothAdapterState: Entering BleOnState
,09-15 08:19:40.104  3601  5249 V NativeCrypto: Read error: ssl=0x7f8ec89380: I/O error during system call, Connection timed out
,09-15 08:19:40.104  4375  4375 I BtOppRfcommListener: stopping Accept Thread
09-15 08:19:40.104  4375  5112 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 08:19:40.105  4375  5112 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 08:19:40.105  3601  5249 V NativeCrypto: SSL shutdown failed: ssl=0x7f8ec89380: I/O error during system call, Broken pipe
,09-15 08:19:40.108  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.110  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.112  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:40.116   929   942 I ActivityManager: Start proc 5494:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-15 08:19:40.118   929  3546 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-15 08:19:40.118   929  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-15 08:19:40.118   929  5180 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-15 08:19:40.118   929  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-15 08:19:40.119  3123  3727 D BluetoothPan: onBluetoothStateChange on: false
09-15 08:19:40.122   929  5183 D DhcpClient: Receive thread stopped
09-15 08:19:40.122   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:19:40.122   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:19:40.121   929  5180 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-15 08:19:40.123  3123  3137 D BluetoothMap: onBluetoothStateChange: up=false
09-15 08:19:40.125   929   929 D RttService: SCAN_AVAILABLE : 1
09-15 08:19:40.125   929  3064 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-15 08:19:40.125   535   535 E Parcel  : Reading a NULL string not supported here.
09-15 08:19:40.125   929  2959 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-15 08:19:40.126   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:19:40.126  3123  3727 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 08:19:40.128  3123  3140 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:19:40.128  3123  3137 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:19:40.129  3123  3727 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 08:19:40.129  3484  3598 W QCNEJ   : |CORE| network lost: 100
09-15 08:19:40.130  3515  3537 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 08:19:40.132   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 08:19:40.132  3484  3598 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-15 08:19:40.134  4375  4460 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 08:19:40.134  4375  4460 D BluetoothAdapterProperties: Setting state to 16
09-15 08:19:40.134  4375  4460 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 08:19:40.137  4375  4460 D BluetoothAdapterProperties: onBleDisable
09-15 08:19:40.137  4375  4460 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:19:40.137  4375  4461 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-15 08:19:40.138  4375  4464 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:19:40.138   929  2957 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-15 08:19:40.138  4375  4587 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-15 08:19:40.138  4375  4587 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:19:40.138   929  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 08:19:40.139   929  2957 E native  : do suspend true
,09-15 08:19:40.140  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:40.141  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:19:40.142  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.142  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:19:40.146  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:40.147  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:19:40.152  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:19:40.152  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:19:40.158  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:40.158  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:40.158  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.159  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:40.159   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:19:40.160  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:40.162  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.163  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:40.170  5494  5494 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-15 08:19:40.181   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:19:40.181  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:19:40.181   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-15 08:19:40.182   929  2959 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-15 08:19:40.182   509   923 D TetherController: Setting IP forward enable = 0
09-15 08:19:40.182   929  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 08:19:40.184   929  2957 D DhcpClient: doQuit
09-15 08:19:40.184   929  2957 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 08:19:40.184   929  5182 D DhcpClient: onQuitting
09-15 08:19:40.185  3663  3663 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 08:19:40.185  4246  4246 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@c5ee5f3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-15 08:19:40.186   929   946 D Tethering: MasterInitialState.processMessage what=3
09-15 08:19:40.191  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 08:19:40.191  4791  4807 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-15 08:19:40.191  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:40.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:40.191  4791  4807 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 08:19:40.191  4791  4807 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 08:19:40.191  4791  4807 E SarControlService: no key has been found,reset the power
09-15 08:19:40.192  4791  4832 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 08:19:40.192  4791  4832 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 08:19:40.192  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.192  4791  4832 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 08:19:40.192  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:40.193  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:19:40.193  4820  4820 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 08:19:40.194  4791  4832 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 08:19:40.194  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:40.195  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:40.195  4791  4832 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 08:19:40.195  4791  4832 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 08:19:40.195  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.195  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:40.196  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:19:40.196  4820  4820 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 08:19:40.197  4820  4835 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d1f331 HexData = [00000000ea03000000000000ffffffff]
09-15 08:19:40.197  4820  4835 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:19:40.197  4820  4835 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-15 08:19:40.197  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:19:40.198  4791  4803 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-15 08:19:40.198  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:40.198  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:40.199  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:40.199  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:40.201  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.202   929  3416 I ActivityManager: Start proc 5519:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-15 08:19:40.202   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e120951:true
09-15 08:19:40.203  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.205  4820  4835 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d1f331 HexData = [00000000eb03000000000000ffffffff]
09-15 08:19:40.205  4820  4835 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:19:40.205  4820  4835 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-15 08:19:40.206  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.206  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:19:40.207  3663  3663 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-15 08:19:40.207  4791  4802 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-15 08:19:40.211  3663  3663 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-15 08:19:40.223  5494  5494 D LocalBluetoothProfileManager: Adding local MAP profile
09-15 08:19:40.225  5494  5494 D BluetoothMap: Create BluetoothMap proxy object
09-15 08:19:40.238   509   923 E Netd    : netlink response contains error (No such file or directory)
09-15 08:19:40.239   929  2959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-15 08:19:40.240   509   923 D TetherController: Setting IP forward enable = 0
,09-15 08:19:40.247  3663  3663 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 08:19:40.252  5519  5519 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-15 08:19:40.253  5494  5494 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-15 08:19:40.263  3663  3663 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 08:19:40.264  5494  5494 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:19:40.274   929  3555 I ActivityManager: Killing 4771:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-15 08:19:40.344  4375  4464 I bt_hci  : shut_down
,09-15 08:19:40.347  4375  4471 D bt_hwcfg: hw_epilog_process
,09-15 08:19:40.347  4375  4471 I bt_vendor: low_power_mode_cb
,09-15 08:19:40.350  4375  4471 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-15 08:19:40.350  4375  4471 I bt_vendor: epilog_cb
09-15 08:19:40.350  4375  4471 I bt_hci  : epilog_finished_callback
,09-15 08:19:40.352  4375  4464 I bt_hci_h4: hal_close
,09-15 08:19:40.352  4375  4464 I bt_userial_vendor: device fd = 54 close
,09-15 08:19:40.365   929  2957 D wifi    : In wifi stop Hal
,09-15 08:19:40.365   929  2957 D wifi    : halHandle = 0x7f7c9eacc0, mVM = 0x7f98b4d140, mCls = 0x100bf6
,09-15 08:19:40.365   929  3662 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 08:19:40.366   929  3662 D WifiHAL : Got a signal to exit!!!
09-15 08:19:40.366   929  3662 I WifiHAL : Exit wifi_event_loop
09-15 08:19:40.366   929  2957 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 08:19:40.366   929  2957 E WifiHAL : Event processing terminated
09-15 08:19:40.366   929  2957 D wifi    : In wifi cleaned up handler
09-15 08:19:40.366   929  2957 I WifiHAL : Internal cleanup completed
09-15 08:19:40.367  4280  4280 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 08:19:40.369  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:40.369  3619  4023 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 08:19:40.370  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:40.372  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:40.389   929  3662 D wifi    : set interface wlan0 flags (DOWN)
,09-15 08:19:40.390   929  2957 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 08:19:40.439  5519  5519 D StrictMode: 	,at java.io.File.doAccess(File.java:281)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5,519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=92 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=91 m,s: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.k.d(PG:583)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.e.b(PG:170)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=58 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.File.exists(File.java:361)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.439  5519  5519 D StrictMode: StrictMode policy violation; ~duration=57 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-15 08:19:40.439  5519  5519 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-15 08:19:40.462  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:19:40.467  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 08:19:40.468  4375  4461 D bt_stack_manager: event_shut_down_stack finished.
09-15 08:19:40.468  4375  4460 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-15 08:19:40.470  4375  4460 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 08:19:40.470  4375  4375 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 08:19:40.471  4375  4375 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 08:19:40.471  4375  4375 D BtGatt.GattService: stop()
09-15 08:19:40.471  4375  4375 D BtGatt.AdvertiseManager: advertise clients cleared
09-15 08:19:40.472  5494  5494 D DockEventReceiver: finishStartingService: stopping service
09-15 08:19:40.475  4375  4375 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:40.475  4375  4375 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:40.475  4375  4375 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:40.475  4375  4375 V BluetoothAdapterState: isBleTurningOff()=true
09-15 08:19:40.475   929  3438 I ActivityManager: Killing 4246:com.google.android.music:main/u0a59 (adj 15): empty #17
09-15 08:19:40.475  4375  4460 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 08:19:40.475  4375  4460 D BluetoothAdapterProperties: Setting state to 10
09-15 08:19:40.475  4375  4460 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 08:19:40.475  4375  4460 I BluetoothAdapterState: Entering OffState
,09-15 08:19:40.476   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-15 08:19:40.564  4375  4375 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-15 08:19:40.564  4375  4375 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-15 08:19:40.564  4375  4375 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 08:19:40.565  4375  4461 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 08:19:40.569  4375  4375 I art     : System.exit called, status: 0
,09-15 08:19:40.569  4375  4375 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 08:19:40.574  3923  3923 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 08:19:40.578  3923  5219 I iu.UploadsManager: num queued entries: 0
,09-15 08:19:40.579  3923  5219 I iu.UploadsManager: num updated entries: 0
,09-15 08:19:40.584  3923  3923 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-15 08:19:40.585  3923  3923 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 08:19:40.588  5222  5222 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 08:19:40.591  5222  5222 D SprintDMHelper: simOperator: 
09-15 08:19:40.592  5222  5222 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-15 08:19:40.592   929   946 D Tethering: InitialState.processMessage what=4
,09-15 08:19:40.594   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 08:19:40.601   929  3162 I ActivityManager: Process com.android.bluetooth (pid 4375) has died
,09-15 08:19:40.606  3923  5219 I iu.SyncManager: NEXT; no task
,09-15 08:19:40.607  4280  5561 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 08:19:40.618   929  3576 I ActivityManager: Start proc 5562:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-15 08:19:40.651  5562  5562 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-15 08:19:40.659   929  3162 I ActivityManager: Killing 4479:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-15 08:19:40.741  5519  5545 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-15 08:19:40.751   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba1ce3e:true
,09-15 08:19:43.514   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:44.515   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:45.064   929  3416 D WifiService: setWifiEnabled: true pid=5439, uid=10077
,09-15 08:19:45.065   929  3416 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:19:45.071   509   923 D SoftapController: Softap fwReload - Ok
,09-15 08:19:45.076   509   923 D CommandListener: Setting iface cfg
09-15 08:19:45.076   509   923 D CommandListener: Trying to bring down wlan0
,09-15 08:19:45.078   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 08:19:45.084   929  2957 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 08:19:45.516   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:45.666   929  2957 D wifi    : set interface wlan0 flags (UP)
,09-15 08:19:45.666   929  2957 I WifiHAL : Initializing wifi
,09-15 08:19:45.667   929  2957 I WifiHAL : Creating socket
,09-15 08:19:45.671   929  2957 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 08:19:45.672   929  2957 D wifi    : Did set static halHandle = 0x7f7c9eacc0
,09-15 08:19:45.672   929  2957 D wifi    : halHandle = 0x7f7c9eacc0, mVM = 0x7f98b4d140, mCls = 0x10189a
09-15 08:19:45.672   929  2957 D wifi    : array field set
09-15 08:19:45.673   929  2957 I WifiNative-HAL: interface[0] = wlan0
09-15 08:19:45.675   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-15 08:19:45.680   929  5579 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547551620288
09-15 08:19:45.680   929  5579 D wifi    : waitForHalEvents called, vm = 0x7f98b4d140, obj = 0x10189a, env = 0x7f7e0ca9c0
,09-15 08:19:45.741  5580  5580 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 08:19:45.758  5580  5580 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:19:45.764  5580  5580 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:19:45.764  5580  5580 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 08:19:45.778   929  2957 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 08:19:45.781  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:45.781  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:45.781  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:45.781  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:45.783  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:45.783  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:45.783  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:45.783  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:45.783   929  2957 D WifiConfigStore: Loading config and enabling all networks 
,09-15 08:19:45.784  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:45.784  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:45.784  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:45.784  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:19:45.786  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:45.786  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:45.787  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:45.793   929  2957 D WifiConfigStore: loaded 0 passpoint configs
,09-15 08:19:45.794   929  2957 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:19:45.794   929  2957 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-15 08:19:45.795   929  2957 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 08:19:45.796   929  2957 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:19:45.797   929  2957 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 08:19:45.797   929  2957 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 08:19:45.797   929  2957 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 08:19:45.801   929  2957 D WifiNative-HAL: Setting external_sim to 1
09-15 08:19:45.801   929  2957 D wifi    : setting dfs flag to true, 0x7f7f35ed60
,09-15 08:19:45.802   929  2957 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 08:19:45.802   929  2957 D wifi    : setting scan oui 0x7f7f35ed60
09-15 08:19:45.802   929  2957 D WifiHAL : Sending mac address OUI
09-15 08:19:45.803  4280  4280 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 08:19:45.816   929  2957 E native  : do suspend true
,09-15 08:19:45.821   929  2957 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 08:19:45.821   929   929 D RttService: SCAN_AVAILABLE : 3
,09-15 08:19:45.821   929  3064 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 08:19:45.821   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-15 08:19:45.822   509   923 D CommandListener: Setting iface cfg
,09-15 08:19:45.827   929  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
,09-15 08:19:45.827   929  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 08:19:45.833   929  2956 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 08:19:45.837   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=371937 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=5 mControllerEnergyUsed=19 }
09-15 08:19:45.837   929  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 08:19:46.521   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:47.522   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:19:48.522   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:19:48.941  5580  5580 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-15 08:19:48.977   929  2957 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-15 08:19:48.982   929  2957 D WifiStateMachine: CMD_AUTO_CONNECT sup state DisconnectedState my state DisconnectedState nid=0 roam=3
,09-15 08:19:48.982   929  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 08:19:48.998   929  2957 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-15 08:19:49.038   929  2957 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-15 08:19:49.378  5580  5580 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-15 08:19:49.416  5580  5580 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-15 08:19:49.417  5580  5580 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-15 08:19:49.432   929  2957 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 08:19:49.433   929  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-15 08:19:49.434   929  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-15 08:19:49.449   929  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 08:19:49.459   509   923 D CommandListener: Setting iface cfg
,09-15 08:19:49.465   929  2957 D WifiStateMachine: Start Dhcp Watchdog 2
,09-15 08:19:49.468   929  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-15 08:19:49.482   929  5586 D DhcpClient: Receive thread started
,09-15 08:19:49.564   929  2957 E native  : do suspend false
,09-15 08:19:49.577   929  5585 D DhcpClient: Broadcasting DHCPDISCOVER
,09-15 08:19:49.598   929  5586 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172466, domain null
,09-15 08:19:49.599   929  5585 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172466 seconds
,09-15 08:19:49.600   929  5585 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-15 08:19:49.613   929  5586 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-15 08:19:49.614   929  5585 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
09-15 08:19:49.616   509   923 D CommandListener: Setting iface cfg
,09-15 08:19:49.621   929  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-15 08:19:49.624   929  2957 E native  : do suspend true
,09-15 08:19:49.624   929  5585 D DhcpClient: Scheduling renewal in 86399s
,09-15 08:19:49.644   929  2957 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-15 08:19:49.645   929  2957 D WifiConfigStore: No blacklist allowed without epno enabled
09-15 08:19:49.646   929  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-15 08:19:49.648   929  2959 D ConnectivityService: Adding iface wlan0 to network 101
,09-15 08:19:49.655   929  2957 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-15 08:19:49.694   929  2959 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-15 08:19:49.694   929  2959 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-15 08:19:49.696   929  2959 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-15 08:19:49.697   929  2959 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-15 08:19:49.699   929  2959 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-15 08:19:49.708   929  2959 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-15 08:19:49.712   929  2959 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-15 08:19:49.712   929  2959 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-15 08:19:49.713   929  2959 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-15 08:19:49.713   929  2959 D ConnectivityService:    accepting network in place of null
09-15 08:19:49.713   929  2957 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-15 08:19:49.713   929  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 08:19:49.713   929  2959 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-15 08:19:49.736   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:19:49.745   929  5584 D NetlinkSocketObserver: NeighborEvent{elapsedMs=375844, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-15 08:19:49.757   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:19:49.760   929  2959 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-15 08:19:49.760   929  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 08:19:49.761  3484  3598 W QCNEJ   : |CORE| network available: 101
,09-15 08:19:49.761   929  2959 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-15 08:19:49.762  3484  3598 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-15 08:19:49.764  3484  3598 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-15 08:19:49.764  3484  3598 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-15 08:19:49.764   929   946 D Tethering: MasterInitialState.processMessage what=3
09-15 08:19:49.767  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:49.767  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:49.767  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:19:49.767  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:49.770  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:49.770  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:49.770  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:49.770  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 08:19:49.773  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-15 08:19:49.773  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-15 08:19:49.773  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:49.773  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-15 08:19:49.774  4791  4807 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-15 08:19:49.775  4791  4807 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 08:19:49.775  4791  4807 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-15 08:19:49.775  4791  4807 E SarControlService: no key has been found,reset the power
09-15 08:19:49.775  4791  4832 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 08:19:49.775  4791  4832 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 08:19:49.775  4791  4832 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 08:19:49.776  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:19:49.776  4820  4820 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 08:19:49.777  4791  4832 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 08:19:49.777  4791  4832 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 08:19:49.777  4791  4832 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 08:19:49.778  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:19:49.778  4820  4820 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,09-15 08:19:49.782  4820  4835 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d1f331 HexData = [00000000ec03000000000000ffffffff]
09-15 08:19:49.782  4820  4835 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:19:49.782  4820  4835 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,09-15 08:19:49.784  4820  4835 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d1f331 HexData = [00000000ed03000000000000ffffffff]
09-15 08:19:49.784  4820  4835 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:19:49.784  4820  4835 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-15 08:19:49.784  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:19:49.784  4791  4803 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-15 08:19:49.785  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:19:49.785  4791  4802 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-15 08:19:49.792  3923  3923 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-15 08:19:49.801  3923  5219 I iu.UploadsManager: num queued entries: 0
,09-15 08:19:49.801  3923  5219 I iu.UploadsManager: num updated entries: 0
09-15 08:19:49.802  3923  5219 I iu.SyncManager: NEXT; no task
,09-15 08:19:49.803  3923  3923 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 08:19:49.805  3923  3923 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 08:19:49.807  5222  5222 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-15 08:19:49.810  5222  5222 D SprintDMHelper: simOperator: 
09-15 08:19:49.810  5222  5222 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 08:19:49.826   929  5583 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-15 08:19:49.873   929  5583 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 15 Sep 2016 12:19:49 GMT], X-Android-Received-Millis=[1473941989872], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473941989849]}
,09-15 08:19:49.873   929  2959 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-15 08:19:49.873   929  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-15 08:19:49.874   929  2959 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-15 08:19:49.875   929  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-15 08:19:49.907  4280  5600 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-15 08:19:50.069   929  3416 D WifiService: setWifiEnabled: false pid=5439, uid=10077
09-15 08:19:50.069   929  3416 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:19:50.073   929  2957 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-15 08:19:50.073   929  2957 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-15 08:19:50.073   929  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 08:19:50.074   929  2957 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-15 08:19:50.092   929  2957 E native  : do suspend true
,09-15 08:19:50.098   929  5585 D DhcpClient: Clearing IP address
,09-15 08:19:50.098   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 08:19:50.101   509   923 D CommandListener: Setting iface cfg
,09-15 08:19:50.103   929  5586 D DhcpClient: Receive thread stopped
,09-15 08:19:50.114  3601  5606 V NativeCrypto: Read error: ssl=0x7f7dac8500: I/O error during system call, Connection timed out
,09-15 08:19:50.116   929  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-15 08:19:50.116   929  2959 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-15 08:19:50.119   535   535 E Parcel  : Reading a NULL string not supported here.
09-15 08:19:50.119  3601  5606 V NativeCrypto: SSL shutdown failed: ssl=0x7f7dac8500: I/O error during system call, Broken pipe
09-15 08:19:50.124   929  2959 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-15 08:19:50.125   929   929 D RttService: SCAN_AVAILABLE : 1
09-15 08:19:50.125   929  3064 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-15 08:19:50.128   929  2957 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-15 08:19:50.128  3484  3598 W QCNEJ   : |CORE| network lost: 101
09-15 08:19:50.128  3484  3598 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-15 08:19:50.132   929  2957 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-15 08:19:50.132   929  2957 E native  : do suspend true
,09-15 08:19:50.153   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:19:50.176   509   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-15 08:19:50.177   509   923 D CommandListener: Clearing all IP addresses on wlan0
09-15 08:19:50.177   929  2959 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-15 08:19:50.177   929  2959 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-15 08:19:50.181   929   946 D Tethering: MasterInitialState.processMessage what=3
09-15 08:19:50.182  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:50.182  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:50.182  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.182  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:50.183   929  2957 D DhcpClient: doQuit
09-15 08:19:50.183   929  2957 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-15 08:19:50.183   929  5585 D DhcpClient: onQuitting
09-15 08:19:50.184  5580  5580 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-15 08:19:50.185  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:50.185  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:50.185  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.185  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:19:50.187  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:50.187  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:50.187  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.187  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:50.189  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:50.189  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:19:50.189  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.189  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:50.191  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:50.191  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:50.191  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:19:50.191  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:50.192  4791  4807 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-15 08:19:50.192  4791  4807 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-15 08:19:50.192  4791  4807 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-15 08:19:50.192  4791  4807 E SarControlService: no key has been found,reset the power
09-15 08:19:50.192  4791  4832 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-15 08:19:50.193  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:50.193  4791  4832 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-15 08:19:50.194  4791  4832 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-15 08:19:50.194  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:19:50.194  4820  4820 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-15 08:19:50.195  5580  5580 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-15 08:19:50.197  4791  4832 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-15 08:19:50.197  4791  4832 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-15 08:19:50.197  4791  4832 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-15 08:19:50.197  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-15 08:19:50.197  4820  4820 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-15 08:19:50.199  5580  5580 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-15 08:19:50.202  4820  4835 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d1f331 HexData = [00000000ee03000000000000ffffffff]
09-15 08:19:50.202  4820  4835 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:19:50.202  4820  4835 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
09-15 08:19:50.202  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:19:50.203  4791  4802 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-15 08:19:50.205  3923  3923 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-15 08:19:50.206  4820  4835 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2d1f331 HexData = [00000000ef03000000000000ffffffff]
09-15 08:19:50.206  4820  4835 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-15 08:19:50.206  4820  4835 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-15 08:19:50.207  4820  4820 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-15 08:19:50.207  4791  4803 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-15 08:19:50.212  3923  5219 I iu.UploadsManager: num queued entries: 0
,09-15 08:19:50.212  3923  5219 I iu.UploadsManager: num updated entries: 0
,09-15 08:19:50.214  3923  3923 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-15 08:19:50.216  3923  3923 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-15 08:19:50.217  3923  5219 I iu.SyncManager: NEXT; no task
,09-15 08:19:50.219  5222  5222 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-15 08:19:50.223  5222  5222 D SprintDMHelper: simOperator: 
,09-15 08:19:50.223  5222  5222 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-15 08:19:50.230  5580  5580 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-15 08:19:50.232   509   923 E Netd    : netlink response contains error (No such file or directory)
,09-15 08:19:50.233   929  2959 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-15 08:19:50.235  4280  5618 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-15 08:19:50.240  5580  5580 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-15 08:19:50.343   929  2957 D wifi    : In wifi stop Hal
,09-15 08:19:50.343   929  2957 D wifi    : halHandle = 0x7f7c9eacc0, mVM = 0x7f98b4d140, mCls = 0x10189a
09-15 08:19:50.343   929  5579 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-15 08:19:50.343   929  5579 D WifiHAL : Got a signal to exit!!!
09-15 08:19:50.343   929  5579 I WifiHAL : Exit wifi_event_loop
09-15 08:19:50.344   929  2957 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-15 08:19:50.344   929  2957 E WifiHAL : Event processing terminated
09-15 08:19:50.344   929  2957 D wifi    : In wifi cleaned up handler
09-15 08:19:50.345   929  2957 I WifiHAL : Internal cleanup completed
09-15 08:19:50.345  4280  4280 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 08:19:50.349  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:50.351  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:50.354  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:50.359  3619  4023 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-15 08:19:50.376   929  5579 D wifi    : set interface wlan0 flags (DOWN)
,09-15 08:19:50.376   929  2957 D WifiNative-HAL: HAL event thread stopped successfully
,09-15 08:19:50.579   929   946 D Tethering: InitialState.processMessage what=4
,09-15 08:19:50.584   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-15 08:19:50.761   929  2959 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-15 08:19:53.024   929   929 E WifiNative-wlan0: set PNO failure
,09-15 08:19:55.110   929   946 I ActivityManager: Start proc 5620:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 08:19:55.209  5620  5620 D AdapterServiceConfig: Adding HeadsetService
09-15 08:19:55.209  5620  5620 D AdapterServiceConfig: Adding A2dpService
09-15 08:19:55.209  5620  5620 D AdapterServiceConfig: Adding HidService
09-15 08:19:55.209  5620  5620 D AdapterServiceConfig: Adding HealthService
09-15 08:19:55.210  5620  5620 D AdapterServiceConfig: Adding PanService
09-15 08:19:55.210  5620  5620 D AdapterServiceConfig: Adding GattService
09-15 08:19:55.210  5620  5620 D AdapterServiceConfig: Adding BluetoothMapService
09-15 08:19:55.210  5620  5620 D AdapterServiceConfig: Adding SapService
,09-15 08:19:55.223   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a8f6b75:true
,09-15 08:19:55.224  5620  5620 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 08:19:55.227  5620  5620 I bt_bluedroid: init
,09-15 08:19:55.228  5620  5632 I BluetoothAdapterState: Entering OffState
,09-15 08:19:55.230  5620  5633 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-15 08:19:55.230  5620  5633 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 08:19:55.230  5620  5633 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 08:19:55.231  5620  5633 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-15 08:19:55.232  5620  5620 I bt_bluedroid: get_profile_interface socket
,09-15 08:19:55.233  5620  5636 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 08:19:55.233  5620  5620 I bt_bluedroid: get_profile_interface sdp
09-15 08:19:55.235  5620  5636 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:19:55.240  5620  5631 I bt_bluedroid: config_hci_snoop_log
,09-15 08:19:55.241   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 08:19:55.245  5620  5632 D BluetoothAdapterState: Current state: OFF, message: 0
09-15 08:19:55.245  5620  5632 D BluetoothAdapterProperties: Setting state to 14
09-15 08:19:55.245  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 08:19:55.248  5620  5632 D BluetoothBondStateMachine: make
,09-15 08:19:55.250  5620  5637 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 08:19:55.253  5620  5632 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:19:55.255  5620  5620 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 08:19:55.258  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:19:55.258  5620  5620 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 08:19:55.259  5620  5620 D BtGatt.GattService: Received start request. Starting profile...
09-15 08:19:55.259  5620  5620 D BtGatt.GattService: start()
09-15 08:19:55.259  5620  5620 I bt_bluedroid: get_profile_interface gatt
,09-15 08:19:55.260  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:19:55.260  5620  5620 D BtGatt.AdvertiseManager: advertise manager created
,09-15 08:19:55.266  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:55.266  5620  5620 V BluetoothAdapterState: isTurningOn()=false
09-15 08:19:55.266  5620  5620 V BluetoothAdapterState: isBleTurningOn()=true
,09-15 08:19:55.266  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:55.266  5620  5632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-15 08:19:55.268  5620  5632 I bt_bluedroid: bt_bluedroid
09-15 08:19:55.268  5620  5633 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-15 08:19:55.268  5620  5633 I bt_hci  : start_up
,09-15 08:19:55.274  5620  5633 I bt_vendor: alloc value 0xf41d9871
,09-15 08:19:55.274  5620  5633 I bt_vendor: init
09-15 08:19:55.274  5620  5633 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 08:19:55.274  5620  5633 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 08:19:55.387  5620  5633 D bt_hci  : start_up starting async portion
09-15 08:19:55.388  5620  5640 I bt_hci  : event_finish_startup
,09-15 08:19:55.388  5620  5640 I bt_hci_h4: hal_open
,09-15 08:19:55.388  5620  5640 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-15 08:19:55.388  5641  5641 W irq/448-msm_hs_: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-15 08:19:55.392  5620  5640 I bt_userial_vendor: device fd = 54 open
,09-15 08:19:55.408  5620  5640 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 08:19:55.412  5620  5640 D bt_hwcfg: Chipset BCM4358A3
,09-15 08:19:55.412  5620  5640 D bt_hwcfg: Target name = [BCM4358A3]
09-15 08:19:55.413  5620  5640 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 08:19:55.921  5620  5640 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 08:19:55.922  5620  5640 D bt_hwcfg: Settlement delay -- 100 ms
09-15 08:19:55.922  5620  5640 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 08:19:56.055  5620  5640 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-15 08:19:56.056  5620  5640 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 08:19:56.057  5620  5640 I bt_hwcfg: vendor lib fwcfg completed
,09-15 08:19:56.058  5620  5640 I bt_vendor: firmware callback
09-15 08:19:56.058  5620  5640 I bt_hci  : firmware_config_callback
09-15 08:19:56.067  5620  5643 I bt_btu  : btu_task pending for preload complete event
,09-15 08:19:56.067  5620  5643 I bt_btu_task: Bluetooth chip preload is complete
,09-15 08:19:56.067  5620  5643 I bt_btu  : btu_task received preload complete event
,09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_HCI
09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_AVDT
09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 08:19:56.075  5620  5643 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 08:19:56.076  5620  5643 I         : BTE_InitTraceLevels -- TRC_GAP
,09-15 08:19:56.076  5620  5643 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 08:19:56.076  5620  5643 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 08:19:56.076  5620  5643 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 08:19:56.076  5620  5643 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 08:19:56.076  5620  5643 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-15 08:19:56.076  5620  5643 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 08:19:56.169  5620  5643 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4157549
09-15 08:19:56.169  5620  5643 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4157549 
,09-15 08:19:56.190  5620  5636 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 08:19:56.193  5620  5636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 08:19:56.193  5620  5636 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 08:19:56.196  5620  5636 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:19:56.199  5620  5636 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:19:56.199  5620  5636 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 08:19:56.200  5620  5636 D bt_hci  : do_postload posting postload work item
09-15 08:19:56.200  5620  5640 I bt_hci  : event_postload
09-15 08:19:56.200  5620  5640 I bt_vendor: sco_config_cb
09-15 08:19:56.200  5620  5640 I bt_hci  : sco_config_callback postload finished.
09-15 08:19:56.203  5620  5636 D bt_bte_conf: Device ID record 1 : primary
09-15 08:19:56.203  5620  5636 D bt_bte_conf:   vendorId            = 000f
09-15 08:19:56.203  5620  5636 D bt_bte_conf:   vendorIdSource      = 0001
09-15 08:19:56.203  5620  5636 D bt_bte_conf:   product             = 1200
09-15 08:19:56.203  5620  5636 D bt_bte_conf:   version             = 1436
09-15 08:19:56.203  5620  5636 D bt_bte_conf:   clientExecutableURL = 
09-15 08:19:56.204  5620  5636 D bt_bte_conf:   serviceDescription  = 
09-15 08:19:56.204  5620  5636 D bt_bte_conf:   documentationURL    = 
09-15 08:19:56.204  5620  5636 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-15 08:19:56.204  5620  5633 D bt_stack_manager: event_start_up_stack finished
09-15 08:19:56.204  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.205  5620  5632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 08:19:56.206  5620  5632 D BluetoothAdapterProperties: Setting state to 15
09-15 08:19:56.206  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 08:19:56.208  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.214  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:19:56.220  5620  5640 I bt_vendor: low_power_mode_cb
,09-15 08:19:56.223  5620  5632 I BluetoothAdapterState: Entering BleOnState
,09-15 08:19:56.224  5620  5632 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-15 08:19:56.224  5620  5632 D BluetoothAdapterProperties: Setting state to 11
09-15 08:19:56.224  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 08:19:56.229  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:19:56.230  5620  5620 D HeadsetService: Received start request. Starting profile...
09-15 08:19:56.232  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.233  5620  5620 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 08:19:56.234  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.236  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.236  5620  5620 D HeadsetStateMachine: make
,09-15 08:19:56.243  5620  5632 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:19:56.246  5620  5620 D HeadsetStateMachine: max_hf_connections = 1
,09-15 08:19:56.246  5620  5620 I bt_bluedroid: get_profile_interface handsfree
09-15 08:19:56.246  5620  5636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 08:19:56.247  5620  5636 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-15 08:19:56.249  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:19:56.250  5620  5620 D A2dpService: Received start request. Starting profile...
,09-15 08:19:56.251  5620  5620 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 08:19:56.251  5620  5620 I bt_bluedroid: get_profile_interface avrcp
,09-15 08:19:56.257  5620  5620 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
09-15 08:19:56.257  5620  5620 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-15 08:19:56.257  5620  5620 D A2dpStateMachine: make
09-15 08:19:56.259  5620  5620 I bt_bluedroid: get_profile_interface a2dp
09-15 08:19:56.259  5620  5636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 08:19:56.261  5620  5652 D A2dpStateMachine: Enter Disconnected: -2
,09-15 08:19:56.262  5620  5620 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 08:19:56.263  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:19:56.264  5494  5494 D BluetoothInputDevice: Proxy object connected
09-15 08:19:56.265  5620  5620 D HidService: Received start request. Starting profile...
,09-15 08:19:56.265  5620  5620 I bt_bluedroid: get_profile_interface hidhost
09-15 08:19:56.265  5620  5620 D HidService: setHidService(): set to: null
09-15 08:19:56.265  5620  5636 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf413856d
09-15 08:19:56.265  5620  5636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 08:19:56.265  5494  5494 D HidProfile: Bluetooth service connected
,09-15 08:19:56.267  5620  5620 I BluetoothHealthServiceJni: classInitNative: succeeds
09-15 08:19:56.268  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:19:56.268  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 08:19:56.269  5620  5620 D HealthService: Received start request. Starting profile...
,09-15 08:19:56.270  5620  5620 I bt_bluedroid: get_profile_interface health
,09-15 08:19:56.271  5620  5620 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-15 08:19:56.272  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:19:56.273  5620  5620 D PanService: Received start request. Starting profile...
09-15 08:19:56.273  5494  5494 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 08:19:56.273  5620  5620 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 08:19:56.273  5620  5620 I bt_bluedroid: get_profile_interface pan
09-15 08:19:56.274  5620  5636 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-15 08:19:56.274  5494  5494 D PanProfile: Bluetooth service connected
,09-15 08:19:56.276  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:19:56.277  5494  5494 D BluetoothMap: Proxy object connected
09-15 08:19:56.277  5620  5620 D BluetoothMapService: Received start request. Starting profile...
09-15 08:19:56.277  5620  5620 D BluetoothMapService: start()
09-15 08:19:56.278  5494  5494 D MapProfile: Bluetooth service connected
,09-15 08:19:56.278  5494  5494 D BluetoothMap: getConnectedDevices()
09-15 08:19:56.279  5494  5494 D BluetoothMap: Bluetooth is Not enabled
,09-15 08:19:56.281  5620  5620 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 08:19:56.282  5620  5620 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-15 08:19:56.282  5620  5620 D BluetoothMapAppObserver: createReceiver()
,09-15 08:19:56.283  5620  5620 D BluetoothMapAppObserver: initObservers()
09-15 08:19:56.283  5620  5620 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 08:19:56.291  5620  5620 V SapService: SapBinder()
,09-15 08:19:56.291  5620  5620 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:19:56.291  5620  5620 D SapService: Received start request. Starting profile...
09-15 08:19:56.291  5620  5620 V SapService: start()
,09-15 08:19:56.294  5620  5620 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:19:56.294  5620  5620 V BluetoothAdapterState: isTurningOn()=true
09-15 08:19:56.294  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:56.294  5620  5650 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isTurningOn()=true
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isTurningOn()=true
,09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isTurningOn()=true
09-15 08:19:56.295  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isTurningOn()=true
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isTurningOn()=true
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:19:56.296  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:56.297  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:19:56.297  5620  5620 V BluetoothAdapterState: isTurningOn()=true
09-15 08:19:56.297  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 08:19:56.297  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:19:56.297  5620  5632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 08:19:56.297  5620  5632 D BluetoothAdapterProperties: ScanMode =  20
09-15 08:19:56.297  5620  5632 D BluetoothAdapterProperties: State =  11
09-15 08:19:56.300  5620  5636 D BluetoothAdapterProperties: Scan Mode:21
09-15 08:19:56.300  5620  5632 D BluetoothAdapterProperties: Setting state to 12
09-15 08:19:56.300  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 08:19:56.300  5620  5636 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 08:19:56.300  5620  5632 I BluetoothAdapterState: Entering OnState
09-15 08:19:56.300  3123  3137 D BluetoothPan: onBluetoothStateChange on: true
09-15 08:19:56.303  3123  3123 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 08:19:56.303   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:19:56.303  3123  3123 D PanProfile: Bluetooth service connected
09-15 08:19:56.303   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:19:56.303  3123  3140 D BluetoothMap: onBluetoothStateChange: up=true
,09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:56.304  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:19:56.305  3123  3123 D BluetoothMap: Proxy object connected
09-15 08:19:56.305  3123  3123 D MapProfile: Bluetooth service connected
09-15 08:19:56.305  3123  3123 D BluetoothMap: getConnectedDevices()
09-15 08:19:56.305   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 08:19:56.307  3123  3137 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 08:19:56.307   929   929 D BluetoothA2dp: Proxy object connected
09-15 08:19:56.307  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:56.309  5494  5507 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 08:19:56.309  5620  5620 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 08:19:56.309  5620  5620 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 08:19:56.310  3123  3727 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:19:56.311  5620  5620 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:19:56.311  3123  3140 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:56.312  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:56.313  5620  5620 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:19:56.313  3123  3123 D BluetoothA2dp: Proxy object connected
09-15 08:19:56.313  3123  3727 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 08:19:56.315  5620  5620 D ObexServerSockets: Succeed to create listening sockets 
09-15 08:19:56.315  5620  5620 D ObexServerSockets0: startAccept()
09-15 08:19:56.315  5620  5620 D ObexServerSockets0: prepareForNewConnect()
,09-15 08:19:56.315  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:56.315  3123  3123 D BluetoothInputDevice: Proxy object connected
09-15 08:19:56.315  3123  3123 D HidProfile: Bluetooth service connected
,09-15 08:19:56.316  3515  3543 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:19:56.316  5494  5506 D BluetoothPan: onBluetoothStateChange on: true
09-15 08:19:56.317  5494  5507 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 08:19:56.317  5494  5506 D BluetoothMap: onBluetoothStateChange: up=true
09-15 08:19:56.317   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:19:56.318  5620  5658 D ObexServerSockets0: Accepting socket connection...
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:19:56.318  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:19:56.318   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 08:19:56.320  5620  5620 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 08:19:56.320  5620  5620 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 08:19:56.320  5620  5659 D ObexServerSockets0: Accepting socket connection...
09-15 08:19:56.320  5620  5620 D BluetoothMapService: onReceive
09-15 08:19:56.321  5620  5620 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 08:19:56.321  5620  5620 D BluetoothMapService: STATE_ON
09-15 08:19:56.321  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:19:56.321  5494  5494 D LocalBluetoothProfileManager: Adding local A2DP profile
09-15 08:19:56.323  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.323  5620  5660 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:19:56.325  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.327  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:19:56.328  5620  5660 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 08:19:56.328  5620  5660 D BluetoothSdpJni: SDP Create record success - handle: 1
09-15 08:19:56.329  5494  5494 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-15 08:19:56.335  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-15 08:19:56.337  5494  5494 D BluetoothA2dp: Proxy object connected
,09-15 08:19:56.341  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:19:56.345  5494  5494 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:19:56.347  5494  5494 D BluetoothPbap: Proxy object connected
,09-15 08:19:56.348  5620  5620 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 08:19:56.348  5620  5620 D ObexServerSockets0: prepareForNewConnect()
09-15 08:19:56.348  5494  5494 D PbapServerProfile: Bluetooth service connected
,09-15 08:19:56.350  3123  3123 D BluetoothPbap: Proxy object connected
09-15 08:19:56.351  3123  3123 D PbapServerProfile: Bluetooth service connected
,09-15 08:19:56.356  5620  5664 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:19:56.370  5620  5668 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:19:56.372  5620  5668 I BtOppRfcommListener: Accept thread started.
,09-15 08:19:56.406  3123  3137 D BluetoothHeadset: Proxy object connected
09-15 08:19:56.406  3123  3123 D HeadsetProfile: Bluetooth service connected
09-15 08:19:56.406   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:19:56.406   929   929 D BluetoothHeadset: Proxy object connected
,09-15 08:19:56.406  3515  3769 D BluetoothHeadset: Proxy object connected
09-15 08:19:56.406   929   929 D BluetoothHeadset: Proxy object connected
,09-15 08:19:56.412  3123  3727 D BluetoothHeadset: Proxy object connected
09-15 08:19:56.412  3123  3123 D HeadsetProfile: Bluetooth service connected
,09-15 08:19:56.417  3515  3537 D BluetoothHeadset: Proxy object connected
09-15 08:19:56.417   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:19:56.433  5494  5506 D BluetoothHeadset: Proxy object connected
,09-15 08:19:56.434  5494  5494 D HeadsetProfile: Bluetooth service connected
,09-15 08:19:57.720   929  2959 D ConnectivityService: handlePromptUnvalidated 101
,09-15 08:20:00.085  5620  5632 D BluetoothAdapterState: Current state: ON, message: 23
,09-15 08:20:00.085  5620  5632 D BluetoothAdapterProperties: Setting state to 13
09-15 08:20:00.086  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-15 08:20:00.087  5620  5632 D BluetoothAdapterProperties: onBluetoothDisable()
09-15 08:20:00.091  5620  5632 I BluetoothAdapterState: Entering PendingCommandState
09-15 08:20:00.094  5620  5620 D BluetoothMapService: onReceive
09-15 08:20:00.094  5620  5620 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-15 08:20:00.094  5620  5620 D BluetoothMapService: STATE_TURNING_OFF
09-15 08:20:00.095  5620  5620 D BluetoothMapService: MAP Service closeService in
09-15 08:20:00.095  5620  5620 D BluetoothMapMasInstance0: MAP Service shutdown
09-15 08:20:00.095  5620  5620 D ObexServerSockets0: shutdown(block = true)
09-15 08:20:00.096  5620  5636 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:20:00.096  5620  5620 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-15 08:20:00.096  5620  5620 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-15 08:20:00.097  5620  5645 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-15 08:20:00.097  5620  5659 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-15 08:20:00.097  5620  5632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-15 08:20:00.098  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:00.098  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:20:00.097  5620  5658 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-15 08:20:00.099  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:20:00.100  5620  5620 I BtOppRfcommListener: stopping Accept Thread
09-15 08:20:00.100  5620  5668 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-15 08:20:00.101  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:20:00.101  5620  5668 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-15 08:20:00.101  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:20:00.107  5620  5620 D HeadsetService: Received stop request...Stopping profile...
09-15 08:20:00.111  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:00.111  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:20:00.112  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:20:00.112  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:20:00.114  3123  3140 D BluetoothHeadset: Proxy object disconnected
,09-15 08:20:00.116  5494  5506 D BluetoothHeadset: Proxy object disconnected
,09-15 08:20:00.116   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:20:00.116   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:20:00.116  3515  3543 D BluetoothHeadset: Proxy object disconnected
09-15 08:20:00.117   929   929 D BluetoothHeadset: Proxy object disconnected
09-15 08:20:00.119  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:00.119  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:00.119  5494  5494 D DockEventReceiver: finishStartingService: stopping service
09-15 08:20:00.120  5439  5439 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-15 08:20:00.120  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:00.122  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:00.123  5620  5620 D A2dpService: Received stop request...Stopping profile...
,09-15 08:20:00.123  5620  5652 D A2dpStateMachine: Exit Disconnected: -1
09-15 08:20:00.124  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:00.125  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-15 08:20:00.125  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:00.126  5494  5494 D HeadsetProfile: Bluetooth service disconnected
09-15 08:20:00.127   929   929 D BluetoothA2dp: Proxy object disconnected
09-15 08:20:00.127  5494  5494 D BluetoothA2dp: Proxy object disconnected
09-15 08:20:00.127  5620  5620 V BluetoothAdapterState: isTurningOff()=true
09-15 08:20:00.128  5620  5620 V BluetoothAdapterState: isTurningOn()=false
09-15 08:20:00.128  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:00.128  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:00.129  3123  3123 D HeadsetProfile: Bluetooth service disconnected
09-15 08:20:00.130  3123  3123 D BluetoothA2dp: Proxy object disconnected
09-15 08:20:00.130  5620  5620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-15 08:20:00.130  5620  5620 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-15 08:20:00.130  5620  5643 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:20:00.130  5620  5643 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:20:00.131  5620  5643 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:20:00.131  5620  5636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-15 08:20:00.131  5620  5636 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-15 08:20:00.131  5620  5620 D HidService: Received stop request...Stopping profile...
09-15 08:20:00.131  5620  5620 D HidService: Stopping Bluetooth HidService
09-15 08:20:00.132  3123  3123 D BluetoothInputDevice: Proxy object disconnected
09-15 08:20:00.132  5494  5494 D BluetoothInputDevice: Proxy object disconnected
,09-15 08:20:00.132  3123  3123 D HidProfile: Bluetooth service disconnected
09-15 08:20:00.132  5494  5494 D HidProfile: Bluetooth service disconnected
09-15 08:20:00.133  5620  5620 D HealthService: Received stop request...Stopping profile...
,09-15 08:20:00.137  5620  5620 D PanService: Received stop request...Stopping profile...
,09-15 08:20:00.138  3123  3123 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 08:20:00.138  3123  3123 D PanProfile: Bluetooth service disconnected
,09-15 08:20:00.139  5494  5494 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-15 08:20:00.140  5494  5494 D PanProfile: Bluetooth service disconnected
,09-15 08:20:00.140  3123  3123 D BluetoothPbap: Proxy object disconnected
09-15 08:20:00.140  3123  3123 D PbapServerProfile: Bluetooth service disconnected
09-15 08:20:00.141  5620  5620 D BluetoothMapService: Received stop request...Stopping profile...
09-15 08:20:00.141  5620  5620 D BluetoothMapService: stop()
09-15 08:20:00.141  5494  5494 D BluetoothPbap: Proxy object disconnected
09-15 08:20:00.141  5494  5494 D PbapServerProfile: Bluetooth service disconnected
,09-15 08:20:00.143  5620  5620 D BluetoothMapAppObserver: deinitObservers()
,09-15 08:20:00.143  5620  5620 D BluetoothMapAppObserver: removeReceiver()
,09-15 08:20:00.146  3123  3123 D BluetoothMap: Proxy object disconnected
,09-15 08:20:00.146  3123  3123 D MapProfile: Bluetooth service disconnected
09-15 08:20:00.147  5620  5620 V BluetoothAdapterState: isTurningOff()=true
09-15 08:20:00.147  5620  5620 V BluetoothAdapterState: isTurningOn()=false
,09-15 08:20:00.147  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
,09-15 08:20:00.147  5494  5494 D BluetoothMap: Proxy object disconnected
09-15 08:20:00.147  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:00.147  5494  5494 D MapProfile: Bluetooth service disconnected
09-15 08:20:00.149  5620  5620 D SapService: Received stop request...Stopping profile...
09-15 08:20:00.149  5620  5620 V SapService: stop()
09-15 08:20:00.149  5620  5643 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:20:00.149  5620  5643 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-15 08:20:00.150  5620  5636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-15 08:20:00.150  5620  5643 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 08:20:00.150  5620  5643 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:20:00.150  5620  5643 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-15 08:20:00.151  5620  5643 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-15 08:20:00.151  5620  5620 V BluetoothAdapterState: isTurningOff()=true
09-15 08:20:00.151  5620  5620 V BluetoothAdapterState: isTurningOn()=false
,09-15 08:20:00.152  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:00.152  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:00.152  5620  5620 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-15 08:20:00.152  5620  5620 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-15 08:20:00.152  5620  5636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-15 08:20:00.153  5620  5620 V BluetoothAdapterState: isTurningOff()=true
09-15 08:20:00.153  5620  5620 V BluetoothAdapterState: isTurningOn()=false
09-15 08:20:00.153  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:00.153  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:00.153  5620  5620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-15 08:20:00.153  5620  5636 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-15 08:20:00.153  5620  5620 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-15 08:20:00.154  5620  5620 V BluetoothAdapterState: isTurningOff()=true
09-15 08:20:00.154  5620  5620 V BluetoothAdapterState: isTurningOn()=false
09-15 08:20:00.154  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:00.154  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:00.154  5620  5620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-15 08:20:00.154  5620  5620 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-15 08:20:00.155  5620  5620 D BluetoothMapService: MAP Service closeService in
09-15 08:20:00.155  5620  5620 V BluetoothAdapterState: isTurningOff()=true
09-15 08:20:00.155  5620  5620 V BluetoothAdapterState: isTurningOn()=false
,09-15 08:20:00.155  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:00.155  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:00.156  5620  5620 D BluetoothMapService: cleanup()
09-15 08:20:00.156  5620  5620 D BluetoothMapService: MAP Service closeService in
09-15 08:20:00.156  5620  5620 V BluetoothAdapterState: isTurningOff()=true
09-15 08:20:00.156  5620  5620 V BluetoothAdapterState: isTurningOn()=false
09-15 08:20:00.156  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:00.156  5620  5620 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:00.156  5620  5632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,09-15 08:20:00.156  5620  5632 D BluetoothAdapterProperties: Setting state to 15
09-15 08:20:00.156  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-15 08:20:00.157  5620  5632 I BluetoothAdapterState: Entering BleOnState
09-15 08:20:00.157  3123  3727 D BluetoothPan: onBluetoothStateChange on: false
09-15 08:20:00.158   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-15 08:20:00.158  5494  5672 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:20:00.159   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:20:00.160  3123  3140 D BluetoothMap: onBluetoothStateChange: up=false
09-15 08:20:00.161   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:20:00.161  3123  3137 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 08:20:00.162  5494  5507 D BluetoothPbap: onBluetoothStateChange: up=false
09-15 08:20:00.162  3123  3727 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:20:00.163  3123  3140 D BluetoothA2dp: onBluetoothStateChange: up=false
09-15 08:20:00.163  3123  3137 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 08:20:00.164  3515  3769 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:20:00.164  5494  5506 D BluetoothPan: onBluetoothStateChange on: false
09-15 08:20:00.164  5494  5672 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-15 08:20:00.165  5494  5507 D BluetoothMap: onBluetoothStateChange: up=false
09-15 08:20:00.165   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:20:00.165  5494  5506 D BluetoothHeadset: onBluetoothStateChange: up=false
09-15 08:20:00.166  5620  5632 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-15 08:20:00.166  5620  5632 D BluetoothAdapterProperties: Setting state to 16
09-15 08:20:00.166  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-15 08:20:00.166  5620  5632 D BluetoothAdapterProperties: onBleDisable
09-15 08:20:00.167  5620  5632 I BluetoothAdapterState: Entering PendingCommandState
09-15 08:20:00.167  5620  5633 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-15 08:20:00.169  5620  5643 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-15 08:20:00.169  5620  5643 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-15 08:20:00.169  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:00.170  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:00.171  5620  5636 D BluetoothAdapterProperties: Scan Mode:20
09-15 08:20:00.172  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:20:00.172  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:00.174  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:00.176  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:00.177  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:00.182  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:20:00.182  5494  5494 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:20:00.378  5620  5636 I bt_hci  : shut_down
,09-15 08:20:00.388  5620  5640 I bt_vendor: low_power_mode_cb
,09-15 08:20:00.392  5620  5640 D bt_hwcfg: hw_epilog_process
,09-15 08:20:00.395  5620  5640 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-15 08:20:00.395  5620  5640 I bt_vendor: epilog_cb
09-15 08:20:00.395  5620  5640 I bt_hci  : epilog_finished_callback
,09-15 08:20:00.398  5620  5636 I bt_hci_h4: hal_close
09-15 08:20:00.399  5620  5636 I bt_userial_vendor: device fd = 54 close
,09-15 08:20:00.512  5620  5633 D bt_stack_manager: event_shut_down_stack finished.
,09-15 08:20:00.513  5620  5632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-15 08:20:00.515  5620  5632 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-15 08:20:00.516  5620  5620 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 08:20:00.516  5620  5620 D BtGatt.GattService: Received stop request...Stopping profile...
09-15 08:20:00.516  5620  5620 D BtGatt.GattService: stop()
09-15 08:20:00.517  5620  5620 D BtGatt.AdvertiseManager: advertise clients cleared
,09-15 08:20:00.518  5620  5620 V BluetoothAdapterState: isTurningOff()=false
09-15 08:20:00.519  5620  5620 V BluetoothAdapterState: isTurningOn()=false
09-15 08:20:00.519  5620  5620 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:00.519  5620  5620 V BluetoothAdapterState: isBleTurningOff()=true
09-15 08:20:00.519  5620  5632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-15 08:20:00.519  5620  5632 D BluetoothAdapterProperties: Setting state to 10
09-15 08:20:00.519  5620  5632 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-15 08:20:00.520  5620  5632 I BluetoothAdapterState: Entering OffState
,09-15 08:20:00.521   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-15 08:20:00.530  5620  5620 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-15 08:20:00.530  5620  5620 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-15 08:20:00.531  5620  5620 I BluetoothServiceJni: cleanupNative: return from cleanup
09-15 08:20:00.532  5620  5633 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-15 08:20:00.539  5620  5620 I art     : System.exit called, status: 0
,09-15 08:20:00.539  5620  5620 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-15 08:20:00.564   929   939 I ActivityManager: Process com.android.bluetooth (pid 5620) has died
,09-15 08:20:03.524   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:04.525   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:05.082  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
,09-15 08:20:05.083  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:05.087  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:05.087  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@719e19a removed from the list
09-15 08:20:05.088  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:05.088  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:20:05.088  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:05.090  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:20:05.090  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a442a8 added. We now have 4 listener(s)
09-15 08:20:05.091  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:20:05.092  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:05.093  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6a442a8 removed from the list
,09-15 08:20:05.093  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:05.093  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:05.093  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:05.095  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:20:05.095  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@62fc1c1 added. We now have 4 listener(s)
,09-15 08:20:05.096  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:20:05.525   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:06.527   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:07.527   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:08.528   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:20:10.106  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:10.138   929   946 I ActivityManager: Start proc 5677:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-15 08:20:10.221  5677  5677 D AdapterServiceConfig: Adding HeadsetService
,09-15 08:20:10.222  5677  5677 D AdapterServiceConfig: Adding A2dpService
09-15 08:20:10.222  5677  5677 D AdapterServiceConfig: Adding HidService
09-15 08:20:10.222  5677  5677 D AdapterServiceConfig: Adding HealthService
09-15 08:20:10.222  5677  5677 D AdapterServiceConfig: Adding PanService
09-15 08:20:10.222  5677  5677 D AdapterServiceConfig: Adding GattService
09-15 08:20:10.223  5677  5677 D AdapterServiceConfig: Adding BluetoothMapService
09-15 08:20:10.223  5677  5677 D AdapterServiceConfig: Adding SapService
,09-15 08:20:10.233   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2755dca:true
,09-15 08:20:10.234  5677  5677 D BluetoothAdapterState: make() - Creating AdapterState
,09-15 08:20:10.236  5677  5677 I bt_bluedroid: init
,09-15 08:20:10.237  5677  5689 I BluetoothAdapterState: Entering OffState
,09-15 08:20:10.239  5677  5690 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-15 08:20:10.239  5677  5690 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-15 08:20:10.239  5677  5690 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-15 08:20:10.239  5677  5690 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-15 08:20:10.240  5677  5677 I bt_bluedroid: get_profile_interface socket
,09-15 08:20:10.242  5677  5693 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-15 08:20:10.243  5677  5677 I bt_bluedroid: get_profile_interface sdp
09-15 08:20:10.243  5677  5693 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:20:10.248  5677  5688 I bt_bluedroid: config_hci_snoop_log
,09-15 08:20:10.249   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-15 08:20:10.254  5677  5689 D BluetoothAdapterState: Current state: OFF, message: 0
09-15 08:20:10.254  5677  5689 D BluetoothAdapterProperties: Setting state to 14
09-15 08:20:10.254  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-15 08:20:10.256  5677  5689 D BluetoothBondStateMachine: make
,09-15 08:20:10.258  5677  5694 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-15 08:20:10.260  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:20:10.262  5677  5677 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-15 08:20:10.264  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:20:10.265  5677  5677 D BtGatt.DebugUtils: handleDebugAction() action=null
09-15 08:20:10.265  5677  5677 D BtGatt.GattService: Received start request. Starting profile...
09-15 08:20:10.266  5677  5677 D BtGatt.GattService: start()
09-15 08:20:10.266  5677  5677 I bt_bluedroid: get_profile_interface gatt
,09-15 08:20:10.267  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:20:10.267  5677  5677 D BtGatt.AdvertiseManager: advertise manager created
,09-15 08:20:10.273  5677  5677 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:20:10.273  5677  5677 V BluetoothAdapterState: isTurningOn()=false
09-15 08:20:10.273  5677  5677 V BluetoothAdapterState: isBleTurningOn()=true
09-15 08:20:10.273  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:10.273  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-15 08:20:10.274  5677  5689 I bt_bluedroid: bt_bluedroid
09-15 08:20:10.274  5677  5690 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-15 08:20:10.275  5677  5690 I bt_hci  : start_up
,09-15 08:20:10.280  5677  5690 I bt_vendor: alloc value 0xf41d9871
,09-15 08:20:10.281  5677  5690 I bt_vendor: init
09-15 08:20:10.281  5677  5690 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-15 08:20:10.281  5677  5690 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-15 08:20:10.390  5677  5690 D bt_hci  : start_up starting async portion
,09-15 08:20:10.391  5677  5697 I bt_hci  : event_finish_startup
09-15 08:20:10.391  5677  5697 I bt_hci_h4: hal_open
09-15 08:20:10.391  5677  5697 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-15 08:20:10.388  5698  5698 W irq/448-msm_hs_: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-15 08:20:10.395  5677  5697 I bt_userial_vendor: device fd = 54 open
,09-15 08:20:10.409  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-15 08:20:10.413  5677  5697 D bt_hwcfg: Chipset BCM4358A3
,09-15 08:20:10.413  5677  5697 D bt_hwcfg: Target name = [BCM4358A3]
09-15 08:20:10.413  5677  5697 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-15 08:20:10.921  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-15 08:20:10.921  5677  5697 D bt_hwcfg: Settlement delay -- 100 ms
09-15 08:20:10.922  5677  5697 I bt_hwcfg: Setting fw settlement delay to 100 
,09-15 08:20:11.055  5677  5697 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-15 08:20:11.055  5677  5697 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-15 08:20:11.057  5677  5697 I bt_hwcfg: vendor lib fwcfg completed
09-15 08:20:11.057  5677  5697 I bt_vendor: firmware callback
09-15 08:20:11.057  5677  5697 I bt_hci  : firmware_config_callback
,09-15 08:20:11.068  5677  5700 I bt_btu  : btu_task pending for preload complete event
09-15 08:20:11.068  5677  5700 I bt_btu_task: Bluetooth chip preload is complete
,09-15 08:20:11.068  5677  5700 I bt_btu  : btu_task received preload complete event
,09-15 08:20:11.076  5677  5700 I         : BTE_InitTraceLevels -- TRC_HCI
,09-15 08:20:11.077  5677  5700 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-15 08:20:11.077  5677  5700 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-15 08:20:11.077  5677  5700 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-15 08:20:11.077  5677  5700 I         : BTE_InitTraceLevels -- TRC_AVRC
09-15 08:20:11.077  5677  5700 I         : BTE_InitTraceLevels -- TRC_A2D
09-15 08:20:11.077  5677  5700 I         : BTE_InitTraceLevels -- TRC_BNEP
09-15 08:20:11.077  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTM
09-15 08:20:11.078  5677  5700 I         : BTE_InitTraceLevels -- TRC_GAP
,09-15 08:20:11.078  5677  5700 I         : BTE_InitTraceLevels -- TRC_PAN
09-15 08:20:11.078  5677  5700 I         : BTE_InitTraceLevels -- TRC_SDP
09-15 08:20:11.078  5677  5700 I         : BTE_InitTraceLevels -- TRC_GATT
09-15 08:20:11.078  5677  5700 I         : BTE_InitTraceLevels -- TRC_SMP
09-15 08:20:11.078  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-15 08:20:11.078  5677  5700 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-15 08:20:11.174  5677  5700 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4157549
09-15 08:20:11.174  5677  5700 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4157549 
,09-15 08:20:11.202  5677  5693 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-15 08:20:11.204  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-15 08:20:11.205  5677  5693 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-15 08:20:11.208  5677  5693 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-15 08:20:11.211  5677  5693 D BluetoothAdapterProperties: Scan Mode:20
,09-15 08:20:11.212  5677  5693 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 08:20:11.212  5677  5693 D bt_hci  : do_postload posting postload work item
09-15 08:20:11.213  5677  5697 I bt_hci  : event_postload
,09-15 08:20:11.213  5677  5697 I bt_vendor: sco_config_cb
09-15 08:20:11.213  5677  5697 I bt_hci  : sco_config_callback postload finished.
09-15 08:20:11.217  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:11.220  5677  5693 D bt_bte_conf: Device ID record 1 : primary
09-15 08:20:11.220  5677  5693 D bt_bte_conf:   vendorId            = 000f
09-15 08:20:11.220  5677  5693 D bt_bte_conf:   vendorIdSource      = 0001
09-15 08:20:11.220  5677  5693 D bt_bte_conf:   product             = 1200
09-15 08:20:11.220  5677  5693 D bt_bte_conf:   version             = 1436
09-15 08:20:11.220  5677  5693 D bt_bte_conf:   clientExecutableURL = 
09-15 08:20:11.220  5677  5693 D bt_bte_conf:   serviceDescription  = 
09-15 08:20:11.220  5677  5693 D bt_bte_conf:   documentationURL    = 
,09-15 08:20:11.221  5677  5693 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-15 08:20:11.221  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:11.221  5677  5690 D bt_stack_manager: event_start_up_stack finished
09-15 08:20:11.222  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-15 08:20:11.223  5677  5689 D BluetoothAdapterProperties: Setting state to 15
09-15 08:20:11.223  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-15 08:20:11.224  5677  5689 I BluetoothAdapterState: Entering BleOnState
,09-15 08:20:11.230  5677  5697 I bt_vendor: low_power_mode_cb
,09-15 08:20:11.230  5677  5689 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-15 08:20:11.230  5677  5689 D BluetoothAdapterProperties: Setting state to 11
,09-15 08:20:11.230  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-15 08:20:11.235  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:20:11.236  5677  5677 D HeadsetService: Received start request. Starting profile...
09-15 08:20:11.239  5677  5677 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-15 08:20:11.240  5677  5677 D HeadsetStateMachine: make
09-15 08:20:11.247  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:11.249  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:11.252  5677  5677 D HeadsetStateMachine: max_hf_connections = 1
,09-15 08:20:11.252  5677  5677 I bt_bluedroid: get_profile_interface handsfree
09-15 08:20:11.254  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-15 08:20:11.254  5677  5693 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-15 08:20:11.260  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:20:11.260  5677  5689 I BluetoothAdapterState: Entering PendingCommandState
,09-15 08:20:11.261  5677  5677 D A2dpService: Received start request. Starting profile...
09-15 08:20:11.262  5677  5677 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-15 08:20:11.262  5677  5677 I bt_bluedroid: get_profile_interface avrcp
,09-15 08:20:11.268  5677  5677 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-15 08:20:11.268  5677  5677 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-15 08:20:11.268  5677  5677 D A2dpStateMachine: make
09-15 08:20:11.269  5677  5677 I bt_bluedroid: get_profile_interface a2dp
,09-15 08:20:11.270  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-15 08:20:11.271  5677  5708 D A2dpStateMachine: Enter Disconnected: -2
,09-15 08:20:11.271  5677  5677 I BluetoothHidServiceJni: classInitNative: succeeds
,09-15 08:20:11.272  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:20:11.273  5677  5677 D HidService: Received start request. Starting profile...
09-15 08:20:11.273  5677  5677 I bt_bluedroid: get_profile_interface hidhost
09-15 08:20:11.273  5677  5693 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf413856d
09-15 08:20:11.273  5677  5677 D HidService: setHidService(): set to: null
09-15 08:20:11.273  5677  5693 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-15 08:20:11.274  5677  5677 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-15 08:20:11.274  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:20:11.275  5677  5677 D HealthService: Received start request. Starting profile...
,09-15 08:20:11.276  5677  5677 I bt_bluedroid: get_profile_interface health
,09-15 08:20:11.279  5677  5677 V BluetoothAdapterState: isTurningOff()=false
,09-15 08:20:11.279  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 08:20:11.279  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:11.279  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:11.279  5677  5677 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-15 08:20:11.280  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:20:11.281  5677  5677 D PanService: Received start request. Starting profile...
09-15 08:20:11.281  5677  5677 D BluetoothPanServiceJni: initializeNative(L110): pan
09-15 08:20:11.281  5677  5677 I bt_bluedroid: get_profile_interface pan
09-15 08:20:11.281  5677  5693 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-15 08:20:11.285  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:20:11.285  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:20:11.286  5677  5677 D BluetoothMapService: Received start request. Starting profile...
,09-15 08:20:11.286  5677  5677 D BluetoothMapService: start()
09-15 08:20:11.289  5677  5677 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-15 08:20:11.290  5677  5677 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-15 08:20:11.290  5677  5677 D BluetoothMapAppObserver: createReceiver()
09-15 08:20:11.292  5677  5677 D BluetoothMapAppObserver: initObservers()
09-15 08:20:11.292  5677  5677 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-15 08:20:11.298  5677  5705 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-15 08:20:11.299  5677  5677 V SapService: SapBinder()
,09-15 08:20:11.299  5677  5677 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
09-15 08:20:11.300  5677  5677 D SapService: Received start request. Starting profile...
09-15 08:20:11.300  5677  5677 V SapService: start()
,09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:11.301  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
09-15 08:20:11.302  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 08:20:11.302  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 08:20:11.302  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:11.302  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 08:20:11.302  5677  5677 V BluetoothAdapterState: isTurningOff()=false
09-15 08:20:11.302  5677  5677 V BluetoothAdapterState: isTurningOn()=true
09-15 08:20:11.303  5677  5677 V BluetoothAdapterState: isBleTurningOn()=false
09-15 08:20:11.303  5677  5677 V BluetoothAdapterState: isBleTurningOff()=false
,09-15 08:20:11.303  5677  5689 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-15 08:20:11.303  5677  5689 D BluetoothAdapterProperties: ScanMode =  20
09-15 08:20:11.303  5677  5689 D BluetoothAdapterProperties: State =  11
,09-15 08:20:11.305  5677  5693 D BluetoothAdapterProperties: Scan Mode:21
09-15 08:20:11.305  5677  5689 D BluetoothAdapterProperties: Setting state to 12
09-15 08:20:11.305  5677  5689 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-15 08:20:11.305  5677  5693 D BluetoothAdapterProperties: Discoverable Timeout:120
09-15 08:20:11.305  5677  5689 I BluetoothAdapterState: Entering OnState
09-15 08:20:11.305  3123  3727 D BluetoothPan: onBluetoothStateChange on: true
,09-15 08:20:11.308   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 08:20:11.309  5494  5507 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 08:20:11.309  3123  3123 D BluetoothPan: BluetoothPAN Proxy object connected
,09-15 08:20:11.309  3123  3123 D PanProfile: Bluetooth service connected
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:11.311  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:20:11.312   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:20:11.312  3123  3140 D BluetoothMap: onBluetoothStateChange: up=true
09-15 08:20:11.314  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:20:11.314   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-15 08:20:11.315  3123  3727 D BluetoothPbap: onBluetoothStateChange: up=true
,09-15 08:20:11.315   929   929 D BluetoothA2dp: Proxy object connected
09-15 08:20:11.317  3123  3123 D BluetoothMap: Proxy object connected
09-15 08:20:11.317  3123  3123 D MapProfile: Bluetooth service connected
09-15 08:20:11.317  3123  3123 D BluetoothMap: getConnectedDevices()
09-15 08:20:11.317  5494  5506 D BluetoothPbap: onBluetoothStateChange: up=true
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:11.317  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:20:11.318  5677  5677 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-15 08:20:11.318  3123  3140 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:20:11.318  5677  5677 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-15 08:20:11.319  3123  3137 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-15 08:20:11.319  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:20:11.320  3123  3123 D BluetoothA2dp: Proxy object connected
09-15 08:20:11.320  5677  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:20:11.321  5494  5494 D BluetoothA2dp: Proxy object connected
09-15 08:20:11.322  3123  3140 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 08:20:11.322  5677  5677 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:20:11.323  5677  5677 D ObexServerSockets: Succeed to create listening sockets 
09-15 08:20:11.323  5677  5677 D ObexServerSockets0: startAccept()
09-15 08:20:11.323  5677  5677 D ObexServerSockets0: prepareForNewConnect()
09-15 08:20:11.324  3515  3537 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-15 08:20:11.325  5494  5506 D BluetoothPan: onBluetoothStateChange on: true
,09-15 08:20:11.325  5677  5677 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-15 08:20:11.326  5677  5677 D BluetoothSdpJni: SDP Create record success - handle: 0
09-15 08:20:11.326  5677  5715 D ObexServerSockets0: Accepting socket connection...
09-15 08:20:11.326  5677  5716 D ObexServerSockets0: Accepting socket connection...
09-15 08:20:11.326  3123  3123 D BluetoothInputDevice: Proxy object connected
09-15 08:20:11.326  3123  3123 D HidProfile: Bluetooth service connected
09-15 08:20:11.327  5494  5672 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-15 08:20:11.329  5494  5506 D BluetoothMap: onBluetoothStateChange: up=true
09-15 08:20:11.330   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:20:11.330  5494  5672 D BluetoothHeadset: onBluetoothStateChange: up=true
09-15 08:20:11.331  5494  5494 D BluetoothPan: BluetoothPAN Proxy object connected
09-15 08:20:11.331  5494  5494 D PanProfile: Bluetooth service connected
09-15 08:20:11.331  5494  5494 D BluetoothInputDevice: Proxy object connected
09-15 08:20:11.331  5494  5494 D HidProfile: Bluetooth service connected
09-15 08:20:11.331   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-15 08:20:11.332  5677  5677 D BluetoothMapService: onReceive
09-15 08:20:11.332  5677  5677 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-15 08:20:11.332  5677  5677 D BluetoothMapService: STATE_ON
09-15 08:20:11.333  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:11.333  5494  5494 D BluetoothMap: Proxy object connected
,09-15 08:20:11.333  5494  5494 D MapProfile: Bluetooth service connected
09-15 08:20:11.333  5494  5494 D BluetoothMap: getConnectedDevices()
09-15 08:20:11.334  5677  5717 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-15 08:20:11.334  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:11.335  5677  5717 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-15 08:20:11.335  5677  5717 D BluetoothSdpJni: SDP Create record success - handle: 1
09-15 08:20:11.338  5494  5494 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-15 08:20:11.344  3601  3601 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-15 08:20:11.348  5494  5494 D DockEventReceiver: finishStartingService: stopping service
,09-15 08:20:11.350  5494  5494 D BluetoothPbap: Proxy object connected
,09-15 08:20:11.350  5494  5494 D PbapServerProfile: Bluetooth service connected
,09-15 08:20:11.355  5677  5721 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:20:11.359  3123  3123 D BluetoothPbap: Proxy object connected
,09-15 08:20:11.360  3123  3123 D PbapServerProfile: Bluetooth service connected
,09-15 08:20:11.367  5677  5677 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-15 08:20:11.367  5677  5677 D ObexServerSockets0: prepareForNewConnect()
,09-15 08:20:11.370  5677  5725 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:20:11.372  5677  5725 I BtOppRfcommListener: Accept thread started.
,09-15 08:20:11.411  3123  3140 D BluetoothHeadset: Proxy object connected
09-15 08:20:11.411  3123  3123 D HeadsetProfile: Bluetooth service connected
09-15 08:20:11.411   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:20:11.411  5494  5507 D BluetoothHeadset: Proxy object connected
,09-15 08:20:11.411   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:20:11.411   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:20:11.412  3515  3543 D BluetoothHeadset: Proxy object connected
09-15 08:20:11.412   929   929 D BluetoothHeadset: Proxy object connected
09-15 08:20:11.413  5494  5494 D HeadsetProfile: Bluetooth service connected
,09-15 08:20:11.418  3123  3727 D BluetoothHeadset: Proxy object connected
,09-15 08:20:11.418  3123  3123 D HeadsetProfile: Bluetooth service connected
,09-15 08:20:11.425  3515  3769 D BluetoothHeadset: Proxy object connected
,09-15 08:20:11.430   929   946 D BluetoothHeadset: Proxy object connected
,09-15 08:20:11.431  5494  5506 D BluetoothHeadset: Proxy object connected
,09-15 08:20:11.432  5494  5494 D HeadsetProfile: Bluetooth service connected
,09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:15.121  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:15.127  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:15.128  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:15.128  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@62fc1c1 removed from the list
,09-15 08:20:15.128  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:15.129  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:15.129  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:15.132  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-15 08:20:15.133  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba47d66 added. We now have 4 listener(s)
09-15 08:20:15.133  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:20:15.134   929  3532 D WifiService: setWifiEnabled: false pid=5439, uid=10077
09-15 08:20:15.135   929  3532 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:20:20.143  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:20.144   929  3527 D WifiService: setWifiEnabled: true pid=5439, uid=10077
09-15 08:20:20.145   929  3527 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-15 08:20:20.153   509   923 D SoftapController: Softap fwReload - Ok
,09-15 08:20:20.158   509   923 D CommandListener: Setting iface cfg
09-15 08:20:20.158   509   923 D CommandListener: Trying to bring down wlan0
09-15 08:20:20.160   509   923 D CommandListener: Clearing all IP addresses on wlan0
,09-15 08:20:20.165   929  2957 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-15 08:20:20.779   929  2957 D wifi    : set interface wlan0 flags (UP)
09-15 08:20:20.785   929  2957 I WifiHAL : Initializing wifi
09-15 08:20:20.785   929  2957 I WifiHAL : Creating socket
,09-15 08:20:20.788   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-15 08:20:20.791   929  2957 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-15 08:20:20.791   929  2957 D wifi    : Did set static halHandle = 0x7f7c9eacc0
09-15 08:20:20.792   929  2957 D wifi    : halHandle = 0x7f7c9eacc0, mVM = 0x7f98b4d140, mCls = 0x20156a
09-15 08:20:20.792   929  2957 D wifi    : array field set
09-15 08:20:20.793   929  2957 I WifiNative-HAL: interface[0] = wlan0
,09-15 08:20:20.795   929  5730 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547551620288
09-15 08:20:20.795   929  5730 D wifi    : waitForHalEvents called, vm = 0x7f98b4d140, obj = 0x20156a, env = 0x7f7e0cc100
,09-15 08:20:20.855  5731  5731 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-15 08:20:20.876  5731  5731 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:20:20.886  5731  5731 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-15 08:20:20.886  5731  5731 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-15 08:20:20.897   929  2957 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-15 08:20:20.903  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:20.910   929  2957 D WifiConfigStore: Loading config and enabling all networks 
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:20.912  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:20.914  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:20.917  5439  5439 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:20.919  5439  5439 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:20.921  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:20.925   929  2957 D WifiConfigStore: loaded 0 passpoint configs
09-15 08:20:20.925   929  2957 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:20:20.925   929  2957 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-15 08:20:20.926   929  2957 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-15 08:20:20.927   929  2957 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-15 08:20:20.928   929  2957 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-15 08:20:20.928   929  2957 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-15 08:20:20.928   929  2957 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-15 08:20:20.931   929  2957 D WifiNative-HAL: Setting external_sim to 1
,09-15 08:20:20.931  4280  4280 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-15 08:20:20.931   929  2957 D wifi    : setting dfs flag to true, 0x7f7ef48ac0
09-15 08:20:20.932   929  2957 D WifiStateMachine: Setting OUI to DA-A1-19
09-15 08:20:20.932   929  2957 D wifi    : setting scan oui 0x7f7ef48ac0
09-15 08:20:20.932   929  2957 D WifiHAL : Sending mac address OUI
,09-15 08:20:20.947   929  2957 E native  : do suspend true
,09-15 08:20:20.952   929  2957 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-15 08:20:20.952   509   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-15 08:20:20.953   929   929 D RttService: SCAN_AVAILABLE : 3
09-15 08:20:20.953   929  3064 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-15 08:20:20.954   509   923 D CommandListener: Setting iface cfg
,09-15 08:20:20.957   929  2956 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,09-15 08:20:20.957   929  2956 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-15 08:20:20.960   929  2956 D WifiNative-HAL: p2pGetDeviceAddress
,09-15 08:20:20.964   929  2956 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-15 08:20:20.964   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=407064 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=8 mControllerEnergyUsed=30 }
,09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:25.163  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:25.169  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:25.170  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:20:25.170  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ba47d66 removed from the list
,09-15 08:20:25.170  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:25.170  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:25.171  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:25.179  5439  5733 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-15 08:20:25.180  5439  5733 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 08:20:28.191  5439  5733 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-15 08:20:28.192  5439  5733 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-15 08:20:28.193  5439  5733 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 08:20:28.194  5439  5733 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 08:20:28.195  5439  5733 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-15 08:20:28.196  5439  5734 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-15 08:20:28.196  5439  5734 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-15 08:20:28.197  5439  5734 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 08:20:28.199  5439  5736 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 152, name: OutgoingSocketThread/Sender)
,09-15 08:20:28.200  5439  5737 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 153, name: OutgoingSocketThread/Receiver)
09-15 08:20:28.201  5439  5734 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 08:20:28.203  5439  5734 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-15 08:20:28.203  5439  5737 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 153, thread name: OutgoingSocketThread/Receiver)
09-15 08:20:28.204  5439  5737 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
,09-15 08:20:28.204  5439  5737 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 153, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-15 08:20:28.204  5439  5738 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 154, name: IncomingSocketThread/Sender)
09-15 08:20:28.205  5439  5739 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: IncomingSocketThread/Receiver)
,09-15 08:20:28.207  5439  5739 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: IncomingSocketThread/Receiver)
09-15 08:20:28.207  5439  5739 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-15 08:20:28.207  5439  5739 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-15 08:20:28.530   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:29.531   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:30.533   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:31.188  5439  5485 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-15 08:20:31.189  5439  5485 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-15 08:20:31.195  5439  5485 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9337dee Bundle[{}]
,09-15 08:20:31.197  5439  5485 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-15 08:20:31.198  5439  5485 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-15 08:20:31.198  5439  5485 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-15 08:20:31.199  5439  5485 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-15 08:20:31.200  5439  5485 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-15 08:20:31.201  5439  5485 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-15 08:20:31.208  5439  5485 I System.out: Running OutgoingSocketThread
,09-15 08:20:31.211  5439  5740 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-15 08:20:31.211  5439  5740 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-15 08:20:31.534   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:32.536   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:20:33.537   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:20:34.222  5439  5740 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-15 08:20:34.222  5439  5740 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-15 08:20:34.222  5439  5740 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 08:20:34.223  5439  5740 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 08:20:34.225  5439  5740 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-15 08:20:34.225  5439  5741 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-15 08:20:34.225  5439  5741 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-15 08:20:34.226  5439  5743 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: OutgoingSocketThread/Sender)
09-15 08:20:34.227  5439  5741 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-15 08:20:34.230  5439  5744 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: OutgoingSocketThread/Receiver)
,09-15 08:20:34.231  5439  5741 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 08:20:34.232  5439  5744 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: OutgoingSocketThread/Receiver)
,09-15 08:20:34.232  5439  5741 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-15 08:20:34.232  5439  5744 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-15 08:20:34.232  5439  5744 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-15 08:20:34.234  5439  5745 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 166, name: IncomingSocketThread/Sender)
,09-15 08:20:34.235  5439  5746 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: IncomingSocketThread/Receiver)
09-15 08:20:34.237  5439  5746 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: IncomingSocketThread/Receiver)
09-15 08:20:34.237  5439  5746 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-15 08:20:34.237  5439  5746 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-15 08:20:37.219  5439  5485 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,09-15 08:20:37.222  5439  5485 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-15 08:20:37.222  5439  5485 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,09-15 08:20:37.228  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:20:37.228  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@622a8a7 added. We now have 3 listener(s)
,09-15 08:20:37.232  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 08:20:37.232  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:20:37.233  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:20:37.233  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:20:37.233  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44ee154 added. We now have 4 listener(s)
09-15 08:20:37.233  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:20:37.234  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:20:37.240  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:37.246  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:37.250  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:37.250  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:20:37.251  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:20:37.251  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:20:37.251  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:20:37.251  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:37.251  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:20:37.251  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:20:37.251  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:20:37.251  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@622a8a7 removed from the list
09-15 08:20:37.251  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:37.251  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44ee154 removed from the list
09-15 08:20:37.252  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:37.254  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:37.255  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:37.255  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:37.256  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:37.256  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:37.257  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:37.257  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:20:37.257  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:37.257  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44ee154 not in the list
09-15 08:20:37.257  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:37.258  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:37.259  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:20:37.259  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:37.259  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:37.259  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44ee154 not in the list
09-15 08:20:37.259  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:37.259  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:37.259  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:37.259  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@622a8a7 not in the list
09-15 08:20:37.260  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:20:37.260  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aeb09f2 added. We now have 3 listener(s)
09-15 08:20:37.262  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-15 08:20:37.262  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:20:37.262  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:20:37.262  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:20:37.262  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6472843 added. We now have 4 listener(s)
09-15 08:20:37.262  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:20:37.264  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:20:37.267  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:37.271  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:20:37.273  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:37.274  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-15 08:20:37.274  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:20:37.274  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:20:37.274  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:20:37.274  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:20:37.274  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-15 08:20:37.276  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:37.278  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:37.279  5439  5485 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 08:20:37.279  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-15 08:20:37.284  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-15 08:20:37.285  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-15 08:20:37.285  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:20:37.289  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 08:20:37.289  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-15 08:20:37.289  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-15 08:20:37.290  5439  5485 D BluetoothAdapter: STATE_ON
09-15 08:20:37.294  5677  5713 D BtGatt.GattService: registerClient() - UUID=d4c11c82-bfa9-4e94-b364-5aa147df88e7
,09-15 08:20:37.295  5677  5693 D BtGatt.GattService: onClientRegistered() - UUID=d4c11c82-bfa9-4e94-b364-5aa147df88e7, clientIf=5
,09-15 08:20:37.296  5439  5449 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:20:37.297  5677  5714 D BtGatt.GattService: start scan with filters
,09-15 08:20:37.302  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-15 08:20:37.302  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-15 08:20:37.302  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:20:37.302  5677  5696 D BtGatt.ScanManager: handling starting scan
09-15 08:20:37.302  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 08:20:37.305  5677  5696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c6c8633
,09-15 08:20:37.306  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:20:37.306  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 08:20:37.306  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:20:37.309  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-15 08:20:37.313  5677  5693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-15 08:20:37.313  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:37.313  5439  5485 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-15 08:20:37.314  5677  5696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-15 08:20:37.314  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:20:37.314  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:20:37.314  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:37.314  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 08:20:37.314  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:20:37.314  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:20:37.314  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:20:37.314  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:20:37.314  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 08:20:37.314  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 08:20:37.315  5439  5485 D BluetoothAdapter: STATE_ON
09-15 08:20:37.316  5677  5714 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:20:37.318  5677  5688 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:20:37.318  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:20:37.318  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:20:37.318  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-15 08:20:37.318  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:20:37.318  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-15 08:20:37.320  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:20:37.321  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:20:37.321  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 08:20:37.321  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:20:37.321  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:20:37.321  5677  5693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-15 08:20:37.322  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:37.322  5677  5696 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:20:37.322  5677  5696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-15 08:20:37.323  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:20:37.323  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:20:37.324  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 08:20:37.336  5677  5693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 08:20:37.336  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:20:37.344  5677  5693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-15 08:20:37.344  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:20:37.352  5677  5693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:20:37.352  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:37.352  5677  5696 D BtGatt.ScanManager: stopping BLe Batch
,09-15 08:20:37.358  5677  5693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-15 08:20:37.358  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:37.358  5677  5696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-15 08:20:37.365  5677  5693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-15 08:20:37.365  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:20:37.825  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:20:37.825  5439  5439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:20:37.825  5439  5439 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 08:20:40.324  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:20:40.324  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:20:40.325  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-15 08:20:40.325  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:40.325  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:40.325  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:20:40.325  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:20:40.325  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aeb09f2 removed from the list
09-15 08:20:40.326  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:40.326  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6472843 removed from the list
09-15 08:20:40.326  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:40.326  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:40.329  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:40.329  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:40.334  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-15 08:20:40.334  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:20:40.334  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:40.335  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6472843 not in the list
09-15 08:20:40.335  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:40.335  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:40.338  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:20:40.338  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:40.338  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:40.339  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6472843 not in the list
,09-15 08:20:40.339  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:40.339  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:20:40.339  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:40.339  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@aeb09f2 not in the list
09-15 08:20:40.341  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-15 08:20:40.341  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31506ec added. We now have 3 listener(s)
,09-15 08:20:40.346  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:20:40.347  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-15 08:20:40.347  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:20:40.347  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:20:40.347  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e980ab5 added. We now have 4 listener(s)
09-15 08:20:40.347  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:20:40.349  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-15 08:20:40.352  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:40.356  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-15 08:20:40.359  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:20:40.359  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:20:40.359  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 08:20:40.361  5439  5485 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-15 08:20:40.361  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-15 08:20:40.361  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 08:20:40.361  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-15 08:20:40.361  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-15 08:20:40.361  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:20:40.363  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:40.365  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-15 08:20:40.366  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-15 08:20:40.366  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-15 08:20:40.366  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:40.366  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-15 08:20:40.367  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-15 08:20:40.367  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-15 08:20:40.367  5439  5439 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-15 08:20:40.367  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:20:40.368  5439  5747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-15 08:20:40.368  5706  5706 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31666]" dev="sockfs" ino=31666 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-15 08:20:40.372  5706  5706 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31666]" dev="sockfs" ino=31666 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-15 08:20:40.372  5439  5485 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-15 08:20:40.372  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 08:20:40.373  5439  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-15 08:20:40.376  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:20:40.389  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 08:20:40.389  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:20:40.392  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-15 08:20:40.392  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:20:40.393  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-15 08:20:40.393  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 08:20:40.394  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-15 08:20:40.394  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-15 08:20:40.395  5439  5485 D BluetoothAdapter: STATE_ON
,09-15 08:20:40.399  5677  5714 D BtGatt.GattService: registerClient() - UUID=121328c3-64e5-426c-a400-0aeea19fa21a
,09-15 08:20:40.399  5677  5693 D BtGatt.GattService: onClientRegistered() - UUID=121328c3-64e5-426c-a400-0aeea19fa21a, clientIf=5
09-15 08:20:40.400  5439  5450 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-15 08:20:40.403  5677  5695 D BtGatt.AdvertiseManager: message : 0
,09-15 08:20:40.404  5677  5695 D BtGatt.AdvertiseManager: starting multi advertising
,09-15 08:20:40.414  5677  5693 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-15 08:20:40.419  5677  5693 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-15 08:20:40.420  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-15 08:20:40.421  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-15 08:20:40.422  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 08:20:40.423  5439  5439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-15 08:20:40.423  5439  5439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-15 08:20:40.423  5439  5439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-15 08:20:40.423  5439  5439 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-15 08:20:40.423  5439  5439 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-15 08:20:40.423  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-15 08:20:40.424  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-15 08:20:40.426  5439  5439 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-15 08:20:40.426  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-15 08:20:40.927  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-15 08:20:40.927  5439  5439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-15 08:20:40.927  5439  5439 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 08:20:43.426  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-15 08:20:43.427  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-15 08:20:43.427  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:20:43.427  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-15 08:20:43.427  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-15 08:20:43.427  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-15 08:20:43.428  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 08:20:43.428  5439  5485 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-15 08:20:43.428  5439  5747 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-15 08:20:43.428  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:20:43.429  5439  5747 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-15 08:20:43.429  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-15 08:20:43.429  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:20:43.429  5439  5747 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-15 08:20:43.429  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:20:43.429  5439  5439 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-15 08:20:43.429  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-15 08:20:43.434  5439  5485 D BluetoothAdapter: STATE_ON
09-15 08:20:43.434  5439  5485 D BluetoothLeScanner: could not find callback wrapper
,09-15 08:20:43.434  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-15 08:20:43.434  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-15 08:20:43.437  5677  5695 D BtGatt.AdvertiseManager: message : 1
,09-15 08:20:43.438  5677  5695 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-15 08:20:43.451  5677  5693 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-15 08:20:43.452  5677  5693 D BtGatt.GattService: Client app is not null!
,09-15 08:20:43.454  5677  5688 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-15 08:20:43.455  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-15 08:20:43.455  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-15 08:20:43.455  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-15 08:20:43.455  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-15 08:20:43.455  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-15 08:20:43.458  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:20:43.458  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-15 08:20:43.458  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:20:43.459  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 08:20:43.461  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:20:43.461  5439  5439 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-15 08:20:43.461  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:20:43.462  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:20:43.462  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:20:43.462  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-15 08:20:43.462  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:20:43.462  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31506ec removed from the list
09-15 08:20:43.462  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:43.462  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 08:20:43.462  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e980ab5 removed from the list
09-15 08:20:43.463  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:43.463  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:43.464  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:43.465  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:43.468  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:43.468  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:20:43.468  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:43.468  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e980ab5 not in the list
,09-15 08:20:43.468  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:43.468  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:43.470  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:20:43.470  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:43.470  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:20:43.470  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e980ab5 not in the list
09-15 08:20:43.470  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:43.470  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:43.470  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:43.471  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31506ec not in the list
09-15 08:20:43.471  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:20:43.472  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbd0c16 added. We now have 3 listener(s)
,09-15 08:20:43.476  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:20:43.476  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:20:43.477  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:20:43.477  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:20:43.477  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2310997 added. We now have 4 listener(s)
09-15 08:20:43.478  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-15 08:20:43.479  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:20:43.484  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:43.489  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:43.492  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-15 08:20:43.493  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:20:43.493  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 08:20:43.493  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-15 08:20:43.493  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-15 08:20:43.493  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:20:43.493  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-15 08:20:43.496  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:43.497  5439  5485 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-15 08:20:43.498  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-15 08:20:43.498  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:43.503  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-15 08:20:43.504  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-15 08:20:43.504  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-15 08:20:43.509  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-15 08:20:43.509  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-15 08:20:43.509  5439  5485 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-15 08:20:43.510  5439  5485 D BluetoothAdapter: STATE_ON
,09-15 08:20:43.514  5677  5688 D BtGatt.GattService: registerClient() - UUID=c01ef839-b95f-418e-a990-7f654335c674
,09-15 08:20:43.515  5677  5693 D BtGatt.GattService: onClientRegistered() - UUID=c01ef839-b95f-418e-a990-7f654335c674, clientIf=5
09-15 08:20:43.515  5439  5449 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-15 08:20:43.516  5677  5714 D BtGatt.GattService: start scan with filters
,09-15 08:20:43.520  5677  5696 D BtGatt.ScanManager: handling starting scan
09-15 08:20:43.520  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-15 08:20:43.520  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-15 08:20:43.521  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-15 08:20:43.521  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-15 08:20:43.525  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-15 08:20:43.525  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-15 08:20:43.526  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-15 08:20:43.528  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-15 08:20:43.529  5677  5693 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-15 08:20:43.529  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:43.530  5677  5696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-15 08:20:43.538  5677  5693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-15 08:20:43.538  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:43.539  5677  5696 D BtGatt.ScanManager: Starting BLE batch scan
09-15 08:20:43.539  5677  5696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-15 08:20:43.553  5677  5693 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-15 08:20:43.553  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:20:43.560  5677  5693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-15 08:20:43.560  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-15 08:20:43.964  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:20:44.027  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-15 08:20:44.027  5439  5439 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-15 08:20:44.027  5439  5439 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-15 08:20:46.539  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:20:46.539  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:20:46.539  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-15 08:20:46.539  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:46.540  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-15 08:20:46.540  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-15 08:20:46.540  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-15 08:20:46.540  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-15 08:20:46.540  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-15 08:20:46.540  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-15 08:20:46.541  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-15 08:20:46.543  5439  5485 D BluetoothAdapter: STATE_ON
,09-15 08:20:46.545  5677  5706 D BtGatt.GattService: stopScan() - queue size =1
09-15 08:20:46.547  5677  5713 D BtGatt.GattService: unregisterClient() - clientIf=5
09-15 08:20:46.547  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-15 08:20:46.548  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-15 08:20:46.548  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-15 08:20:46.548  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-15 08:20:46.548  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-15 08:20:46.552  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-15 08:20:46.553  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-15 08:20:46.553  5439  5485 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-15 08:20:46.554  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-15 08:20:46.556  5677  5677 D BtGatt.ScanManager: awakened up at time 432656
,09-15 08:20:46.558  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-15 08:20:46.561  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-15 08:20:46.562  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:20:46.562  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:20:46.562  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:20:46.562  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-15 08:20:46.562  5439  5439 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-15 08:20:46.562  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbd0c16 removed from the list
,09-15 08:20:46.562  5439  5439 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-15 08:20:46.562  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-15 08:20:46.562  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2310997 removed from the list
09-15 08:20:46.562  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:46.562  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:46.563  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:46.563  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:46.565  5677  5693 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-15 08:20:46.565  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:46.565  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:46.566  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:20:46.566  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:46.566  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2310997 not in the list
09-15 08:20:46.566  5677  5696 D BtGatt.ScanManager: stopping BLe Batch
09-15 08:20:46.566  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:46.566  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:46.571  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:20:46.572  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:46.572  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:46.572  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2310997 not in the list
09-15 08:20:46.572  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:46.572  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:20:46.572  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:46.572  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dbd0c16 not in the list
09-15 08:20:46.573  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-15 08:20:46.574  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30357f0 added. We now have 3 listener(s)
09-15 08:20:46.576  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-15 08:20:46.576  5677  5693 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-15 08:20:46.576  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:46.576  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-15 08:20:46.576  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-15 08:20:46.576  5677  5696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-15 08:20:46.576  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-15 08:20:46.577  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c169 added. We now have 4 listener(s)
09-15 08:20:46.577  5439  5485 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-15 08:20:46.578  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-15 08:20:46.582  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-15 08:20:46.586  5439  5485 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-15 08:20:46.589  5439  5485 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-15 08:20:46.589  5439  5485 D io.jxcore.node.ConnectivityMonitor: start: OK
09-15 08:20:46.589  5439  5485 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-15 08:20:46.589  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-15 08:20:46.589  5439  5485 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-15 08:20:46.589  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:46.589  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:46.590  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-15 08:20:46.590  5439  5485 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-15 08:20:46.590  5439  5485 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30357f0 removed from the list
09-15 08:20:46.590  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:46.590  5439  5485 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c169 removed from the list
09-15 08:20:46.591  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-15 08:20:46.597  5439  5439 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-15 08:20:46.597  5439  5485 D io.jxcore.node.ConnectivityMonitor: stop
09-15 08:20:46.597  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:46.598  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:46.598  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-15 08:20:46.599  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:46.599  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-15 08:20:46.599  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:46.599  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c169 not in the list
09-15 08:20:46.599  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-15 08:20:46.599  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:46.600  5677  5693 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-15 08:20:46.600  5677  5693 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-15 08:20:46.600  5677  5693 D BtGatt.GattService: current time is 432700334033
09-15 08:20:46.601  5677  5693 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -78, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -89, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -87, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -76, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -79, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-15 08:20:46.602  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-15 08:20:46.602  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-15 08:20:46.602  5439  5485 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-15 08:20:46.602  5677  5693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-15 08:20:46.602  5439  5485 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d7c169 not in the list
09-15 08:20:46.602  5439  5485 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-15 08:20:46.602  5439  5485 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-15 08:20:46.602  5439  5485 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-15 08:20:46.602  5439  5485 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30357f0 not in the list
09-15 08:20:46.603  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-15 08:20:46.603  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-15 08:20:46.604  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-15 08:20:46.604  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-15 08:20:46.604  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-15 08:20:46.604  5677  5693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-15 08:20:46.604  5439  5485 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-15 08:20:46.604  5677  5693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-15 08:20:46.605  5677  5693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-15 08:20:46.605  5677  5693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-15 08:20:46.605  5677  5693 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-15 08:20:47.063  5439  5439 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-15 08:20:48.616  5439  5748 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 186, name: My test thread name)
,09-15 08:20:50.615  5439  5485 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 186
,09-15 08:20:50.615  5439  5485 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 186, name: My test thread name)
,09-15 08:20:50.620  5439  5749 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 187, name: My test thread name)
09-15 08:20:50.621  5439  5749 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 187, thread name: My test thread name)
,09-15 08:20:50.621  5439  5749 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-15 08:20:50.624  5439  5485 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-15 08:20:50.630  5439  5750 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 191, name: My test thread name)
,09-15 08:20:50.631  5439  5750 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 191, thread name: My test thread name): Test exception.
09-15 08:20:50.631  5439  5750 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 191, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-15 08:20:50.636  5439  5485 I jxcore-log: Total number of executed tests:  82
09-15 08:20:50.636  5439  5485 I jxcore-log: 
,09-15 08:20:50.637  5439  5485 I jxcore-log: Number of passed tests:  82
09-15 08:20:50.637  5439  5485 I jxcore-log: 
09-15 08:20:50.638  5439  5485 I jxcore-log: Number of failed tests:  0
09-15 08:20:50.638  5439  5485 I jxcore-log: 
,09-15 08:20:50.638  5439  5485 I jxcore-log: Number of ignored tests:  0
09-15 08:20:50.638  5439  5485 I jxcore-log: 
09-15 08:20:50.638  5439  5485 I jxcore-log: Total duration:  101019
09-15 08:20:50.638  5439  5485 I jxcore-log: 
,09-15 08:20:50.644  5439  5485 I jxcore-log: Unit Test app is loaded
09-15 08:20:50.644  5439  5485 I jxcore-log: 
,09-15 08:20:50.657  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.657  5439  5485 I jxcore-log: 
,09-15 08:20:50.663  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.663  5439  5485 I jxcore-log: 
,09-15 08:20:50.663  5439  5439 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-15 08:20:50.665  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.665  5439  5485 I jxcore-log: 
,09-15 08:20:50.666  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.666  5439  5485 I jxcore-log: 
,09-15 08:20:50.669  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 08:20:50.669  5439  5485 I jxcore-log: 
,09-15 08:20:50.671  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:20:50.671  5439  5485 I jxcore-log: 
,09-15 08:20:50.675  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.675  5439  5485 I jxcore-log: 
,09-15 08:20:50.678  5439  5748 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 165 and the total number of bytes written 165
09-15 08:20:50.678  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.678  5439  5485 I jxcore-log: 
,09-15 08:20:50.680  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 08:20:50.680  5439  5485 I jxcore-log: 
,09-15 08:20:50.682  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:20:50.682  5439  5485 I jxcore-log: 
09-15 08:20:50.683  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:20:50.683  5439  5485 I jxcore-log: 
09-15 08:20:50.684  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.684  5439  5485 I jxcore-log: 
09-15 08:20:50.685  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.685  5439  5485 I jxcore-log: 
09-15 08:20:50.685  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.685  5439  5485 I jxcore-log: 
09-15 08:20:50.686  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.686  5439  5485 I jxcore-log: 
,09-15 08:20:50.688  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.688  5439  5485 I jxcore-log: 
,09-15 08:20:50.690  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.690  5439  5485 I jxcore-log: 
,09-15 08:20:50.691  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.691  5439  5485 I jxcore-log: 
,09-15 08:20:50.692  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.692  5439  5485 I jxcore-log: 
,09-15 08:20:50.693  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.693  5439  5485 I jxcore-log: 
,09-15 08:20:50.695  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.695  5439  5485 I jxcore-log: 
,09-15 08:20:50.696  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.696  5439  5485 I jxcore-log: 
,09-15 08:20:50.697  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.697  5439  5485 I jxcore-log: 
,09-15 08:20:50.699  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.699  5439  5485 I jxcore-log: 
09-15 08:20:50.700  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.700  5439  5485 I jxcore-log: 
09-15 08:20:50.701  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-15 08:20:50.701  5439  5485 I jxcore-log: 
09-15 08:20:50.702  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.702  5439  5485 I jxcore-log: 
09-15 08:20:50.703  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.703  5439  5485 I jxcore-log: 
,09-15 08:20:50.703  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.703  5439  5485 I jxcore-log: 
09-15 08:20:50.705  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.705  5439  5485 I jxcore-log: 
,09-15 08:20:50.706  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.706  5439  5485 I jxcore-log: 
,09-15 08:20:50.707  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.707  5439  5485 I jxcore-log: 
,09-15 08:20:50.708  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.708  5439  5485 I jxcore-log: 
,09-15 08:20:50.709  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.709  5439  5485 I jxcore-log: 
,09-15 08:20:50.710  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.710  5439  5485 I jxcore-log: 
09-15 08:20:50.711  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.711  5439  5485 I jxcore-log: 
,09-15 08:20:50.713  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.713  5439  5485 I jxcore-log: 
,09-15 08:20:50.714  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.714  5439  5485 I jxcore-log: 
,09-15 08:20:50.715  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.715  5439  5485 I jxcore-log: 
09-15 08:20:50.716  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-15 08:20:50.716  5439  5485 I jxcore-log: 
,09-15 08:20:50.717  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.717  5439  5485 I jxcore-log: 
,09-15 08:20:50.718  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.718  5439  5485 I jxcore-log: 
,09-15 08:20:50.719  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.719  5439  5485 I jxcore-log: 
09-15 08:20:50.720  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.720  5439  5485 I jxcore-log: 
,09-15 08:20:50.721  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.721  5439  5485 I jxcore-log: 
,09-15 08:20:50.722  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:20:50.722  5439  5485 I jxcore-log: 
,09-15 08:20:50.723  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.723  5439  5485 I jxcore-log: 
,09-15 08:20:50.724  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-15 08:20:50.724  5439  5485 I jxcore-log: 
09-15 08:20:50.725  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.725  5439  5485 I jxcore-log: 
,09-15 08:20:50.726  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:20:50.726  5439  5485 I jxcore-log: 
,09-15 08:20:50.727  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-15 08:20:50.727  5439  5485 I jxcore-log: 
,09-15 08:20:50.728  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-15 08:20:50.728  5439  5485 I jxcore-log: 
09-15 08:20:50.729  5439  5485 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-15 08:20:50.729  5439  5485 I jxcore-log: 
,09-15 08:20:50.734  5439  5485 I jxcore-log: Network status after Unit Tests:  { bluetoothLowEnergy: 'on',
09-15 08:20:50.734  5439  5485 I jxcore-log:   bluetooth: 'on',
09-15 08:20:50.734  5439  5485 I jxcore-log:   wifi: 'on',
09-15 08:20:50.734  5439  5485 I jxcore-log:   cellular: 'doNotCare',
09-15 08:20:50.734  5439  5485 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
09-15 08:20:50.734  5439  5485 I jxcore-log: 
,09-15 08:20:50.740  5439  5485 I jxcore-log: Network status before Coordination Tests:  { bluetoothLowEnergy: 'on',
09-15 08:20:50.740  5439  5485 I jxcore-log:   bluetooth: 'on',
09-15 08:20:50.740  5439  5485 I jxcore-log:   wifi: 'on',
09-15 08:20:50.740  5439  5485 I jxcore-log:   cellular: 'doNotCare' }
09-15 08:20:50.740  5439  5485 I jxcore-log: 
,09-15 08:20:50.741  5439  5485 I jxcore-log: My device name is: Huawei-Nexus 6P
09-15 08:20:50.741  5439  5485 I jxcore-log: 
09-15 08:20:50.742  5439  5485 I jxcore-log: WARN testUtils: myNameCallback not set!
09-15 08:20:50.742  5439  5485 I jxcore-log: 
09-15 08:20:50.742  5439  5485 I jxcore-log: Running for WIFI network type
09-15 08:20:50.742  5439  5485 I jxcore-log: 
,09-15 08:20:52.480  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-15 08:20:52.480  5439  5485 I jxcore-log: 
,09-15 08:20:52.775  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-15 08:20:52.775  5439  5485 I jxcore-log: 
,09-15 08:20:52.800  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-15 08:20:52.800  5439  5485 I jxcore-log: 
,09-15 08:20:53.919  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-15 08:20:53.919  5439  5485 I jxcore-log: 
,09-15 08:20:53.923  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-15 08:20:53.923  5439  5485 I jxcore-log: 
,09-15 08:20:53.927  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-15 08:20:53.927  5439  5485 I jxcore-log: 
,09-15 08:20:53.970  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-15 08:20:53.970  5439  5485 I jxcore-log: 
,09-15 08:20:53.981  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-15 08:20:53.981  5439  5485 I jxcore-log: 
,09-15 08:20:53.984  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-15 08:20:53.984  5439  5485 I jxcore-log: 
,09-15 08:20:54.621  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-15 08:20:54.621  5439  5485 I jxcore-log: 
,09-15 08:20:54.843  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-15 08:20:54.843  5439  5485 I jxcore-log: 
,09-15 08:20:54.852  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-15 08:20:54.852  5439  5485 I jxcore-log: 
,09-15 08:20:54.857  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-15 08:20:54.857  5439  5485 I jxcore-log: 
,09-15 08:20:54.868  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-15 08:20:54.868  5439  5485 I jxcore-log: 
,09-15 08:20:54.893  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-15 08:20:54.893  5439  5485 I jxcore-log: 
,09-15 08:20:54.925  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-15 08:20:54.925  5439  5485 I jxcore-log: 
,09-15 08:20:54.930  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-15 08:20:54.930  5439  5485 I jxcore-log: 
,09-15 08:20:54.935  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-15 08:20:54.935  5439  5485 I jxcore-log: 
,09-15 08:20:54.948  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-15 08:20:54.948  5439  5485 I jxcore-log: 
,09-15 08:20:54.951  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-15 08:20:54.951  5439  5485 I jxcore-log: 
,09-15 08:20:54.955  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-15 08:20:54.955  5439  5485 I jxcore-log: 
,09-15 08:20:54.965  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-15 08:20:54.965  5439  5485 I jxcore-log: 
,09-15 08:20:54.983  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-15 08:20:54.983  5439  5485 I jxcore-log: 
,09-15 08:20:54.991  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-15 08:20:54.991  5439  5485 I jxcore-log: 
,09-15 08:20:55.000  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-15 08:20:55.000  5439  5485 I jxcore-log: 
,09-15 08:20:55.008  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-15 08:20:55.008  5439  5485 I jxcore-log: 
,09-15 08:20:55.018  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-15 08:20:55.018  5439  5485 I jxcore-log: 
,09-15 08:20:55.026  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-15 08:20:55.026  5439  5485 I jxcore-log: 
,09-15 08:20:55.029  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-15 08:20:55.029  5439  5485 I jxcore-log: 
,09-15 08:20:55.047  5439  5485 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-15 08:20:55.047  5439  5485 I jxcore-log: 
,09-15 08:20:55.054  5439  5485 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-15 08:20:55.055  5439  5485 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-15 08:20:55.055  5439  5485 I jxcore-log: 
,09-15 08:20:55.057  5439  5485 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-15 08:20:55.057  5439  5485 I jxcore-log: 
,09-15 08:20:55.058  5439  5485 I jxcore-log: ThaliTape :: Started ThaliTape
09-15 08:20:55.058  5439  5485 I jxcore-log: 
,09-15 08:20:55.061  5439  5485 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-15 08:20:55.061  5439  5485 I jxcore-log: 
,09-15 08:20:55.090  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:20:55.090  5439  5485 I jxcore-log: 
,09-15 08:20:55.091  5439  5485 I jxcore-log: websocket error
09-15 08:20:55.091  5439  5485 I jxcore-log: 
09-15 08:20:55.091  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:20:55.091  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:20:55.091  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:20:55.091  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:20:55.091  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:20:55.091  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:20:55.091  5439  5485 I jxcore-log: 
09-15 08:20:55.091  5439  5485 I jxcore-log: WARN testUtils: logCallback not set!
09-15 08:20:55.091  5439  5485 I jxcore-log: 
,09-15 08:20:56.324  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:20:56.324  5439  5485 I jxcore-log: 
,09-15 08:20:56.325  5439  5485 I jxcore-log: websocket error
09-15 08:20:56.325  5439  5485 I jxcore-log: 
09-15 08:20:56.325  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:20:56.325  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:20:56.325  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:20:56.325  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:20:56.325  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:20:56.325  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:20:56.325  5439  5485 I jxcore-log: 
,09-15 08:20:58.537   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 08:20:58.538   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:20:58.544  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:20:58.544  5439  5485 I jxcore-log: 
09-15 08:20:58.544  5439  5485 I jxcore-log: websocket error
09-15 08:20:58.544  5439  5485 I jxcore-log: 
09-15 08:20:58.545  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:20:58.545  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:20:58.545  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:20:58.545  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:20:58.545  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:20:58.545  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:20:58.545  5439  5485 I jxcore-log: 
,09-15 08:21:01.234  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:01.234  5439  5485 I jxcore-log: 
,09-15 08:21:01.234  5439  5485 I jxcore-log: websocket error
09-15 08:21:01.234  5439  5485 I jxcore-log: 
09-15 08:21:01.234  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:01.234  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:01.234  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:01.234  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:01.234  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:01.234  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:01.234  5439  5485 I jxcore-log: 
,09-15 08:21:06.266  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:06.266  5439  5485 I jxcore-log: 
09-15 08:21:06.267  5439  5485 I jxcore-log: websocket error
09-15 08:21:06.267  5439  5485 I jxcore-log: 
09-15 08:21:06.267  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:06.267  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:06.267  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:06.267  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:06.267  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:06.267  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:06.267  5439  5485 I jxcore-log: 
,09-15 08:21:11.302  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:11.302  5439  5485 I jxcore-log: 
,09-15 08:21:11.302  5439  5485 I jxcore-log: websocket error
09-15 08:21:11.302  5439  5485 I jxcore-log: 
09-15 08:21:11.302  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:11.302  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:11.302  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:11.302  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:11.302  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:11.302  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:11.302  5439  5485 I jxcore-log: 
,09-15 08:21:16.328  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:16.328  5439  5485 I jxcore-log: 
09-15 08:21:16.328  5439  5485 I jxcore-log: websocket error
09-15 08:21:16.328  5439  5485 I jxcore-log: 
09-15 08:21:16.329  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:16.329  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:16.329  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:16.329  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:16.329  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:16.329  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:16.329  5439  5485 I jxcore-log: 
,09-15 08:21:18.539   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:19.540   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:20.541   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:21.359  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:21.359  5439  5485 I jxcore-log: 
,09-15 08:21:21.359  5439  5485 I jxcore-log: websocket error
09-15 08:21:21.359  5439  5485 I jxcore-log: 
09-15 08:21:21.360  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:21.360  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:21.360  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:21.360  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:21.360  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:21.360  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:21.360  5439  5485 I jxcore-log: 
,09-15 08:21:21.542   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:22.543   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:23.544   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:21:26.387  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:26.387  5439  5485 I jxcore-log: 
,09-15 08:21:26.387  5439  5485 I jxcore-log: websocket error
09-15 08:21:26.387  5439  5485 I jxcore-log: 
,09-15 08:21:26.387  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:26.387  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:26.387  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:26.387  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:26.387  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:26.387  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:26.387  5439  5485 I jxcore-log: 
,09-15 08:21:28.546   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:29.547   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:30.549   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:31.413  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:31.413  5439  5485 I jxcore-log: 
,09-15 08:21:31.414  5439  5485 I jxcore-log: websocket error
09-15 08:21:31.414  5439  5485 I jxcore-log: 
09-15 08:21:31.414  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:31.414  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:31.414  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:31.414  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:31.414  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:31.414  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:31.414  5439  5485 I jxcore-log: 
,09-15 08:21:31.550   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:32.552   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:33.552   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:21:36.476  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:36.476  5439  5485 I jxcore-log: 
,09-15 08:21:36.476  5439  5485 I jxcore-log: websocket error
09-15 08:21:36.476  5439  5485 I jxcore-log: 
09-15 08:21:36.476  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:36.476  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:36.476  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:36.476  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:36.476  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:36.476  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:36.476  5439  5485 I jxcore-log: 
,09-15 08:21:41.506  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:41.506  5439  5485 I jxcore-log: 
,09-15 08:21:41.506  5439  5485 I jxcore-log: websocket error
09-15 08:21:41.506  5439  5485 I jxcore-log: 
09-15 08:21:41.506  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:41.506  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:41.506  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:41.506  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:41.506  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:41.506  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:41.506  5439  5485 I jxcore-log: 
,09-15 08:21:43.554   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:44.555   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:45.556   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:46.535  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:46.535  5439  5485 I jxcore-log: 
,09-15 08:21:46.535  5439  5485 I jxcore-log: websocket error
09-15 08:21:46.535  5439  5485 I jxcore-log: 
,09-15 08:21:46.536  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:46.536  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:46.536  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:46.536  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:46.536  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:46.536  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:46.536  5439  5485 I jxcore-log: 
,09-15 08:21:46.557   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:47.559   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:21:48.559   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:21:51.561  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:51.561  5439  5485 I jxcore-log: 
,09-15 08:21:51.561  5439  5485 I jxcore-log: websocket error
09-15 08:21:51.561  5439  5485 I jxcore-log: 
,09-15 08:21:51.561  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:51.561  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:51.561  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:51.561  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:51.561  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:51.561  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:51.561  5439  5485 I jxcore-log: 
,09-15 08:21:56.584  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:21:56.584  5439  5485 I jxcore-log: 
09-15 08:21:56.584  5439  5485 I jxcore-log: websocket error
09-15 08:21:56.584  5439  5485 I jxcore-log: 
09-15 08:21:56.584  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:21:56.584  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:21:56.584  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:21:56.584  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:56.584  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:21:56.584  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:21:56.584  5439  5485 I jxcore-log: 
,09-15 08:22:01.609  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:01.609  5439  5485 I jxcore-log: 
09-15 08:22:01.609  5439  5485 I jxcore-log: websocket error
09-15 08:22:01.609  5439  5485 I jxcore-log: 
,09-15 08:22:01.611  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:01.611  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:01.611  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:01.611  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:01.611  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:01.611  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:01.611  5439  5485 I jxcore-log: 
,09-15 08:22:03.561   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:04.562   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:05.563   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:06.564   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:06.635  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:06.635  5439  5485 I jxcore-log: 
,09-15 08:22:06.635  5439  5485 I jxcore-log: websocket error
09-15 08:22:06.635  5439  5485 I jxcore-log: 
09-15 08:22:06.636  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:06.636  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:06.636  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:06.636  5439  5485 I jxcore-log: emit@events.js:82:1
,09-15 08:22:06.636  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:06.636  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:06.636  5439  5485 I jxcore-log: 
,09-15 08:22:07.566   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:08.567   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:22:11.660  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:11.660  5439  5485 I jxcore-log: 
09-15 08:22:11.660  5439  5485 I jxcore-log: websocket error
09-15 08:22:11.660  5439  5485 I jxcore-log: 
09-15 08:22:11.661  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:11.661  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:11.661  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:11.661  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:11.661  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:11.661  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:11.661  5439  5485 I jxcore-log: 
,09-15 08:22:16.683  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:16.683  5439  5485 I jxcore-log: 
09-15 08:22:16.684  5439  5485 I jxcore-log: websocket error
09-15 08:22:16.684  5439  5485 I jxcore-log: 
09-15 08:22:16.684  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:16.684  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:16.684  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:16.684  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:16.684  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:16.684  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:16.684  5439  5485 I jxcore-log: 
,09-15 08:22:21.708  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:21.708  5439  5485 I jxcore-log: 
,09-15 08:22:21.709  5439  5485 I jxcore-log: websocket error
09-15 08:22:21.709  5439  5485 I jxcore-log: 
09-15 08:22:21.709  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:21.709  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:21.709  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:21.709  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:21.709  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:21.709  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:21.709  5439  5485 I jxcore-log: 
,09-15 08:22:26.733  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:26.733  5439  5485 I jxcore-log: 
,09-15 08:22:26.734  5439  5485 I jxcore-log: websocket error
09-15 08:22:26.734  5439  5485 I jxcore-log: 
,09-15 08:22:26.735  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:26.735  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:26.735  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:26.735  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:26.735  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:26.735  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:26.735  5439  5485 I jxcore-log: 
,09-15 08:22:28.568   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:29.569   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:30.570   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:31.572   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:31.758  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:31.758  5439  5485 I jxcore-log: 
,09-15 08:22:31.758  5439  5485 I jxcore-log: websocket error
09-15 08:22:31.758  5439  5485 I jxcore-log: 
,09-15 08:22:31.758  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:31.758  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:31.758  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:31.758  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:31.758  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:31.758  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:31.758  5439  5485 I jxcore-log: 
,09-15 08:22:32.573   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:22:33.574   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:22:36.785  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:36.785  5439  5485 I jxcore-log: 
09-15 08:22:36.786  5439  5485 I jxcore-log: websocket error
09-15 08:22:36.786  5439  5485 I jxcore-log: 
09-15 08:22:36.786  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:36.786  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:36.786  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:36.786  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:36.786  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:36.786  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:36.786  5439  5485 I jxcore-log: 
,09-15 08:22:41.816  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:41.816  5439  5485 I jxcore-log: 
09-15 08:22:41.817  5439  5485 I jxcore-log: websocket error
09-15 08:22:41.817  5439  5485 I jxcore-log: 
,09-15 08:22:41.817  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:41.817  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:41.817  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:41.817  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:41.817  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:41.817  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:41.817  5439  5485 I jxcore-log: 
,09-15 08:22:46.844  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:46.844  5439  5485 I jxcore-log: 
09-15 08:22:46.845  5439  5485 I jxcore-log: websocket error
09-15 08:22:46.845  5439  5485 I jxcore-log: 
,09-15 08:22:46.845  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:46.845  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:46.845  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:46.845  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:46.845  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:46.845  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:46.845  5439  5485 I jxcore-log: 
,09-15 08:22:51.869  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:51.869  5439  5485 I jxcore-log: 
,09-15 08:22:51.869  5439  5485 I jxcore-log: websocket error
09-15 08:22:51.869  5439  5485 I jxcore-log: 
09-15 08:22:51.870  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:51.870  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:51.870  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:51.870  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:51.870  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:51.870  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:51.870  5439  5485 I jxcore-log: 
,09-15 08:22:56.893  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:22:56.893  5439  5485 I jxcore-log: 
09-15 08:22:56.893  5439  5485 I jxcore-log: websocket error
09-15 08:22:56.893  5439  5485 I jxcore-log: 
09-15 08:22:56.893  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:22:56.893  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:22:56.893  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:22:56.893  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:56.893  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:22:56.893  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:22:56.893  5439  5485 I jxcore-log: 
,09-15 08:22:58.575   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:22:58.575   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:23:01.919  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:01.919  5439  5485 I jxcore-log: 
09-15 08:23:01.919  5439  5485 I jxcore-log: websocket error
09-15 08:23:01.919  5439  5485 I jxcore-log: 
09-15 08:23:01.919  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:01.919  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:01.919  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:01.919  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:01.919  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:01.919  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:01.919  5439  5485 I jxcore-log: 
,09-15 08:23:06.945  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:06.945  5439  5485 I jxcore-log: 
09-15 08:23:06.945  5439  5485 I jxcore-log: websocket error
09-15 08:23:06.945  5439  5485 I jxcore-log: 
09-15 08:23:06.945  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:06.945  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:06.945  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:06.945  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:06.945  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:06.945  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:06.945  5439  5485 I jxcore-log: 
,09-15 08:23:11.970  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:11.970  5439  5485 I jxcore-log: 
,09-15 08:23:11.970  5439  5485 I jxcore-log: websocket error
09-15 08:23:11.970  5439  5485 I jxcore-log: 
,09-15 08:23:11.971  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:11.971  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:11.971  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:11.971  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:11.971  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:11.971  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:11.971  5439  5485 I jxcore-log: 
,09-15 08:23:16.995  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:16.995  5439  5485 I jxcore-log: 
09-15 08:23:16.995  5439  5485 I jxcore-log: websocket error
09-15 08:23:16.995  5439  5485 I jxcore-log: 
09-15 08:23:16.996  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:16.996  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:16.996  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:16.996  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:16.996  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:16.996  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:16.996  5439  5485 I jxcore-log: 
,09-15 08:23:22.048  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:22.048  5439  5485 I jxcore-log: 
09-15 08:23:22.048  5439  5485 I jxcore-log: websocket error
09-15 08:23:22.048  5439  5485 I jxcore-log: 
09-15 08:23:22.048  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:22.048  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:22.048  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:22.048  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:22.048  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:22.048  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:22.048  5439  5485 I jxcore-log: 
,09-15 08:23:23.586   537  1348 E QC-QMI  : qmi_client [537] 9: failed to locate client data
,09-15 08:23:23.589   521   521 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
,09-15 08:23:23.589   521   521 E QC-QMI  : QMUX qmux_client_id=9 not found in qmux client list, unable to remove
,09-15 08:23:23.594   537   537 I Atfwd_Daemon: Stop the daemon....
,09-15 08:23:23.707  5753  5753 I libmdmdetect: ESOC framework not supported
,09-15 08:23:23.705  5753  5753 W ATFWD-daemon: type=1400 audit(0.0:120): avc: denied { read write } for name="diag" dev="tmpfs" ino=12486 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
09-15 08:23:23.708  5753  5753 I libmdmdetect: Found internal modem: modem
09-15 08:23:23.709  5753  5753 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,09-15 08:23:23.719  5753  5753 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
09-15 08:23:23.719  5753  5753 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-15 08:23:23.720  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:24.722  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:25.724  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:26.725  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:27.073  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:27.073  5439  5485 I jxcore-log: 
09-15 08:23:27.073  5439  5485 I jxcore-log: websocket error
09-15 08:23:27.073  5439  5485 I jxcore-log: 
09-15 08:23:27.074  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:27.074  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:27.074  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:27.074  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:27.074  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:27.074  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:27.074  5439  5485 I jxcore-log: 
,09-15 08:23:27.726  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:28.727  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:23:32.102  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:32.102  5439  5485 I jxcore-log: 
,09-15 08:23:32.103  5439  5485 I jxcore-log: websocket error
09-15 08:23:32.103  5439  5485 I jxcore-log: 
,09-15 08:23:32.103  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:32.103  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:32.103  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:32.103  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:32.103  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:32.103  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:32.103  5439  5485 I jxcore-log: 
,09-15 08:23:33.728  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:34.729  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:35.730  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:36.731  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:37.129  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:37.129  5439  5485 I jxcore-log: 
09-15 08:23:37.129  5439  5485 I jxcore-log: websocket error
09-15 08:23:37.129  5439  5485 I jxcore-log: 
,09-15 08:23:37.130  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:37.130  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:37.130  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:37.130  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:37.130  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:37.130  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:37.130  5439  5485 I jxcore-log: 
,09-15 08:23:37.732  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:38.733  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:23:42.155  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:42.155  5439  5485 I jxcore-log: 
,09-15 08:23:42.155  5439  5485 I jxcore-log: websocket error
09-15 08:23:42.155  5439  5485 I jxcore-log: 
09-15 08:23:42.156  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:42.156  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:42.156  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:42.156  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:42.156  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:42.156  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:42.156  5439  5485 I jxcore-log: 
,09-15 08:23:47.183  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:47.183  5439  5485 I jxcore-log: 
09-15 08:23:47.184  5439  5485 I jxcore-log: websocket error
09-15 08:23:47.184  5439  5485 I jxcore-log: 
09-15 08:23:47.184  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:47.184  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:47.184  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:47.184  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:47.184  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:47.184  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:47.184  5439  5485 I jxcore-log: 
,09-15 08:23:48.734  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:49.735  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:50.736  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:51.737  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:52.212  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:52.212  5439  5485 I jxcore-log: 
09-15 08:23:52.213  5439  5485 I jxcore-log: websocket error
09-15 08:23:52.213  5439  5485 I jxcore-log: 
09-15 08:23:52.213  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:52.213  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:52.213  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:52.213  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:52.213  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:52.213  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:52.213  5439  5485 I jxcore-log: 
,09-15 08:23:52.738  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:23:53.739  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:23:57.239  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:23:57.239  5439  5485 I jxcore-log: 
09-15 08:23:57.239  5439  5485 I jxcore-log: websocket error
09-15 08:23:57.239  5439  5485 I jxcore-log: 
09-15 08:23:57.240  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:23:57.240  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:23:57.240  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:23:57.240  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:57.240  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:23:57.240  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:23:57.240  5439  5485 I jxcore-log: 
,09-15 08:24:02.266  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:02.266  5439  5485 I jxcore-log: 
,09-15 08:24:02.267  5439  5485 I jxcore-log: websocket error
09-15 08:24:02.267  5439  5485 I jxcore-log: 
09-15 08:24:02.267  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:02.267  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:02.267  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:02.267  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:02.267  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:02.267  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:02.267  5439  5485 I jxcore-log: 
,09-15 08:24:07.294  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:07.294  5439  5485 I jxcore-log: 
,09-15 08:24:07.294  5439  5485 I jxcore-log: websocket error
09-15 08:24:07.294  5439  5485 I jxcore-log: 
,09-15 08:24:07.294  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:07.294  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:07.294  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:07.294  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:07.294  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:07.294  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:07.294  5439  5485 I jxcore-log: 
,09-15 08:24:08.740  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:09.742  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:10.743  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:11.744  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:12.322  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:12.322  5439  5485 I jxcore-log: 
,09-15 08:24:12.322  5439  5485 I jxcore-log: websocket error
09-15 08:24:12.322  5439  5485 I jxcore-log: 
09-15 08:24:12.323  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:12.323  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:12.323  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:12.323  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:12.323  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:12.323  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:12.323  5439  5485 I jxcore-log: 
,09-15 08:24:12.745  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:13.745  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:24:17.351  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:17.351  5439  5485 I jxcore-log: 
09-15 08:24:17.351  5439  5485 I jxcore-log: websocket error
09-15 08:24:17.351  5439  5485 I jxcore-log: 
09-15 08:24:17.351  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:17.351  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:17.351  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:17.351  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:17.351  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:17.351  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:17.351  5439  5485 I jxcore-log: 
,09-15 08:24:22.377  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:22.377  5439  5485 I jxcore-log: 
09-15 08:24:22.377  5439  5485 I jxcore-log: websocket error
09-15 08:24:22.377  5439  5485 I jxcore-log: 
09-15 08:24:22.378  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:22.378  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:22.378  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:22.378  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:22.378  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:22.378  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:22.378  5439  5485 I jxcore-log: 
,09-15 08:24:27.403  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:27.403  5439  5485 I jxcore-log: 
09-15 08:24:27.403  5439  5485 I jxcore-log: websocket error
09-15 08:24:27.403  5439  5485 I jxcore-log: 
09-15 08:24:27.404  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:27.404  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:27.404  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:27.404  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:27.404  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:27.404  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:27.404  5439  5485 I jxcore-log: 
,09-15 08:24:32.432  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:32.432  5439  5485 I jxcore-log: 
,09-15 08:24:32.432  5439  5485 I jxcore-log: websocket error
09-15 08:24:32.432  5439  5485 I jxcore-log: 
,09-15 08:24:32.432  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:32.432  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:32.432  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:32.432  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:32.432  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:32.432  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:32.432  5439  5485 I jxcore-log: 
,09-15 08:24:33.746  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:34.748  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:35.749  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:36.750  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:37.458  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:37.458  5439  5485 I jxcore-log: 
,09-15 08:24:37.458  5439  5485 I jxcore-log: websocket error
09-15 08:24:37.458  5439  5485 I jxcore-log: 
09-15 08:24:37.459  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:37.459  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:37.459  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:37.459  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:37.459  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:37.459  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:37.459  5439  5485 I jxcore-log: 
,09-15 08:24:37.751  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:24:38.751  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:24:42.488  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:42.488  5439  5485 I jxcore-log: 
,09-15 08:24:42.488  5439  5485 I jxcore-log: websocket error
09-15 08:24:42.488  5439  5485 I jxcore-log: 
09-15 08:24:42.488  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:42.488  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:42.488  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:42.488  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:42.488  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:42.488  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:42.488  5439  5485 I jxcore-log: 
,09-15 08:24:47.514  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:47.514  5439  5485 I jxcore-log: 
09-15 08:24:47.515  5439  5485 I jxcore-log: websocket error
09-15 08:24:47.515  5439  5485 I jxcore-log: 
09-15 08:24:47.515  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:47.515  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:47.515  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:47.515  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:47.515  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:47.515  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:47.515  5439  5485 I jxcore-log: 
,09-15 08:24:52.543  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:52.543  5439  5485 I jxcore-log: 
,09-15 08:24:52.543  5439  5485 I jxcore-log: websocket error
09-15 08:24:52.543  5439  5485 I jxcore-log: 
09-15 08:24:52.544  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:52.544  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:52.544  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:52.544  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:52.544  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:52.544  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:52.544  5439  5485 I jxcore-log: 
,09-15 08:24:57.572  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:24:57.572  5439  5485 I jxcore-log: 
,09-15 08:24:57.572  5439  5485 I jxcore-log: websocket error
09-15 08:24:57.572  5439  5485 I jxcore-log: 
09-15 08:24:57.573  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:24:57.573  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:24:57.573  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:24:57.573  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:57.573  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:24:57.573  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:24:57.573  5439  5485 I jxcore-log: 
,09-15 08:25:02.600  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:02.600  5439  5485 I jxcore-log: 
,09-15 08:25:02.601  5439  5485 I jxcore-log: websocket error
09-15 08:25:02.601  5439  5485 I jxcore-log: 
09-15 08:25:02.601  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:02.601  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:02.601  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:02.601  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:02.601  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:02.601  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:02.601  5439  5485 I jxcore-log: 
,09-15 08:25:03.752  5753  5753 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:25:03.752  5753  5753 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:25:07.628  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:07.628  5439  5485 I jxcore-log: 
09-15 08:25:07.628  5439  5485 I jxcore-log: websocket error
09-15 08:25:07.628  5439  5485 I jxcore-log: 
09-15 08:25:07.629  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:07.629  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:07.629  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:07.629  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:07.629  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:07.629  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:07.629  5439  5485 I jxcore-log: 
,09-15 08:25:08.753  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:09.754  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:10.755  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:11.756  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:12.657  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:12.657  5439  5485 I jxcore-log: 
,09-15 08:25:12.657  5439  5485 I jxcore-log: websocket error
09-15 08:25:12.657  5439  5485 I jxcore-log: 
,09-15 08:25:12.657  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:12.657  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:12.657  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:12.657  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:12.657  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:12.657  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:12.657  5439  5485 I jxcore-log: 
,09-15 08:25:12.757  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:13.757  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:25:17.695  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:17.695  5439  5485 I jxcore-log: 
,09-15 08:25:17.696  5439  5485 I jxcore-log: websocket error
09-15 08:25:17.696  5439  5485 I jxcore-log: 
09-15 08:25:17.696  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13,
09-15 08:25:17.696  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:17.696  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:17.696  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:17.696  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:17.696  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:17.696  5439  5485 I jxcore-log: 
,09-15 08:25:18.758  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:19.759  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:20.761  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:21.762  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:22.729  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:22.729  5439  5485 I jxcore-log: 
,09-15 08:25:22.729  5439  5485 I jxcore-log: websocket error
09-15 08:25:22.729  5439  5485 I jxcore-log: 
,09-15 08:25:22.730  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:22.730  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:22.730  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:22.730  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:22.730  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:22.730  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:22.730  5439  5485 I jxcore-log: 
,09-15 08:25:22.763  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:23.763  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:25:27.755  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:27.755  5439  5485 I jxcore-log: 
09-15 08:25:27.756  5439  5485 I jxcore-log: websocket error
09-15 08:25:27.756  5439  5485 I jxcore-log: 
,09-15 08:25:27.756  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:27.756  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:27.756  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:27.756  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:27.756  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:27.756  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:27.756  5439  5485 I jxcore-log: 
,09-15 08:25:32.784  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:32.784  5439  5485 I jxcore-log: 
09-15 08:25:32.784  5439  5485 I jxcore-log: websocket error
09-15 08:25:32.784  5439  5485 I jxcore-log: 
,09-15 08:25:32.785  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:32.785  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:32.785  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:32.785  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:32.785  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:32.785  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:32.785  5439  5485 I jxcore-log: 
,09-15 08:25:33.765  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:34.766  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:35.767  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:36.768  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:37.769  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:37.809  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:37.809  5439  5485 I jxcore-log: 
09-15 08:25:37.809  5439  5485 I jxcore-log: websocket error
09-15 08:25:37.809  5439  5485 I jxcore-log: 
09-15 08:25:37.809  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:37.809  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:37.809  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:37.809  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:37.809  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:37.809  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:37.809  5439  5485 I jxcore-log: 
,09-15 08:25:38.770  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:25:42.835  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:42.835  5439  5485 I jxcore-log: 
09-15 08:25:42.835  5439  5485 I jxcore-log: websocket error
09-15 08:25:42.835  5439  5485 I jxcore-log: 
09-15 08:25:42.835  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:42.835  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:42.835  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:42.835  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:42.835  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:42.835  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:42.835  5439  5485 I jxcore-log: 
,09-15 08:25:47.864  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:47.864  5439  5485 I jxcore-log: 
,09-15 08:25:47.864  5439  5485 I jxcore-log: websocket error
09-15 08:25:47.864  5439  5485 I jxcore-log: 
09-15 08:25:47.865  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:47.865  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:47.865  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:47.865  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:47.865  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:47.865  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:47.865  5439  5485 I jxcore-log: 
,09-15 08:25:52.888  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:52.888  5439  5485 I jxcore-log: 
09-15 08:25:52.889  5439  5485 I jxcore-log: websocket error
09-15 08:25:52.889  5439  5485 I jxcore-log: 
09-15 08:25:52.889  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:52.889  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:52.889  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:52.889  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:52.889  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:52.889  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:52.889  5439  5485 I jxcore-log: 
,09-15 08:25:53.771  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:54.772  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:55.773  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:56.774  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:57.775  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:25:57.918  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:25:57.918  5439  5485 I jxcore-log: 
09-15 08:25:57.918  5439  5485 I jxcore-log: websocket error
09-15 08:25:57.918  5439  5485 I jxcore-log: 
09-15 08:25:57.919  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:25:57.919  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:25:57.919  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:25:57.919  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:57.919  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:25:57.919  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:25:57.919  5439  5485 I jxcore-log: 
,09-15 08:25:58.776  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:26:02.957  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:02.957  5439  5485 I jxcore-log: 
09-15 08:26:02.957  5439  5485 I jxcore-log: websocket error
09-15 08:26:02.957  5439  5485 I jxcore-log: 
,09-15 08:26:02.958  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:02.958  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:02.958  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:02.958  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:02.958  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:02.958  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:02.958  5439  5485 I jxcore-log: 
,09-15 08:26:07.984  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:07.984  5439  5485 I jxcore-log: 
09-15 08:26:07.984  5439  5485 I jxcore-log: websocket error
09-15 08:26:07.984  5439  5485 I jxcore-log: 
09-15 08:26:07.985  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:07.985  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:07.985  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:07.985  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:07.985  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:07.985  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:07.985  5439  5485 I jxcore-log: 
,09-15 08:26:13.012  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:13.012  5439  5485 I jxcore-log: 
,09-15 08:26:13.012  5439  5485 I jxcore-log: websocket error
09-15 08:26:13.012  5439  5485 I jxcore-log: 
09-15 08:26:13.012  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:13.012  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:13.012  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:13.012  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:13.012  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:13.012  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:13.012  5439  5485 I jxcore-log: 
,09-15 08:26:18.039  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:18.039  5439  5485 I jxcore-log: 
09-15 08:26:18.039  5439  5485 I jxcore-log: websocket error
09-15 08:26:18.039  5439  5485 I jxcore-log: 
09-15 08:26:18.039  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:18.039  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:18.039  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:18.039  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:18.039  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:18.039  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:18.039  5439  5485 I jxcore-log: 
,09-15 08:26:18.777  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:26:19.778  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:26:20.779  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:26:21.781  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:26:22.782  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:26:23.065  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:23.065  5439  5485 I jxcore-log: 
,09-15 08:26:23.066  5439  5485 I jxcore-log: websocket error
09-15 08:26:23.066  5439  5485 I jxcore-log: 
,09-15 08:26:23.066  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:23.066  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:23.066  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:23.066  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:23.066  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:23.066  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:23.066  5439  5485 I jxcore-log: 
,09-15 08:26:23.783  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:26:28.093  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:28.093  5439  5485 I jxcore-log: 
,09-15 08:26:28.093  5439  5485 I jxcore-log: websocket error
09-15 08:26:28.093  5439  5485 I jxcore-log: 
09-15 08:26:28.094  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:28.094  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:28.094  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:28.094  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:28.094  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:28.094  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:28.094  5439  5485 I jxcore-log: 
,09-15 08:26:33.122  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:33.122  5439  5485 I jxcore-log: 
,09-15 08:26:33.122  5439  5485 I jxcore-log: websocket error
09-15 08:26:33.122  5439  5485 I jxcore-log: 
09-15 08:26:33.122  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:33.122  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:33.122  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:33.122  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:33.122  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:33.122  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:33.122  5439  5485 I jxcore-log: 
,09-15 08:26:38.151  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:38.151  5439  5485 I jxcore-log: 
,09-15 08:26:38.151  5439  5485 I jxcore-log: websocket error
09-15 08:26:38.151  5439  5485 I jxcore-log: 
09-15 08:26:38.152  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:38.152  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:38.152  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:38.152  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:38.152  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:38.152  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:38.152  5439  5485 I jxcore-log: 
,09-15 08:26:43.185  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:43.185  5439  5485 I jxcore-log: 
09-15 08:26:43.186  5439  5485 I jxcore-log: websocket error
09-15 08:26:43.186  5439  5485 I jxcore-log: 
,09-15 08:26:43.187  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:43.187  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:43.187  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:43.187  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:43.187  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:43.187  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:43.187  5439  5485 I jxcore-log: 
,09-15 08:26:48.213  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:48.213  5439  5485 I jxcore-log: 
09-15 08:26:48.214  5439  5485 I jxcore-log: websocket error
09-15 08:26:48.214  5439  5485 I jxcore-log: 
,09-15 08:26:48.214  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:48.214  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:48.214  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:48.214  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:48.214  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:48.214  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:48.214  5439  5485 I jxcore-log: 
,09-15 08:26:48.783  5753  5753 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:26:48.784  5753  5753 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:26:53.239  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:53.239  5439  5485 I jxcore-log: 
,09-15 08:26:53.240  5439  5485 I jxcore-log: websocket error
09-15 08:26:53.240  5439  5485 I jxcore-log: 
,09-15 08:26:53.240  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:53.240  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:53.240  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:53.240  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:53.240  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:53.240  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:53.240  5439  5485 I jxcore-log: 
,09-15 08:26:58.269  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:26:58.269  5439  5485 I jxcore-log: 
,09-15 08:26:58.269  5439  5485 I jxcore-log: websocket error
09-15 08:26:58.269  5439  5485 I jxcore-log: 
09-15 08:26:58.270  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:26:58.270  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:26:58.270  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:26:58.270  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:58.270  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:26:58.270  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:26:58.270  5439  5485 I jxcore-log: 
,09-15 08:26:58.785  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:26:59.786  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:00.786  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:01.787  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:02.789  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:03.294  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:03.294  5439  5485 I jxcore-log: 
,09-15 08:27:03.295  5439  5485 I jxcore-log: websocket error
09-15 08:27:03.295  5439  5485 I jxcore-log: 
09-15 08:27:03.295  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:03.295  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:03.295  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:03.295  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:03.295  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:03.295  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:03.295  5439  5485 I jxcore-log: 
,09-15 08:27:03.789  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:27:08.324  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:08.324  5439  5485 I jxcore-log: 
,09-15 08:27:08.325  5439  5485 I jxcore-log: websocket error
09-15 08:27:08.325  5439  5485 I jxcore-log: 
09-15 08:27:08.325  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:08.325  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:08.325  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:08.325  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:08.325  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:08.325  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:08.325  5439  5485 I jxcore-log: 
,09-15 08:27:08.791  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:09.792  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:10.793  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:11.795  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:12.796  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:13.350  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:13.350  5439  5485 I jxcore-log: 
,09-15 08:27:13.351  5439  5485 I jxcore-log: websocket error
09-15 08:27:13.351  5439  5485 I jxcore-log: 
09-15 08:27:13.351  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:13.351  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:13.351  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:13.351  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:13.351  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:13.351  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:13.351  5439  5485 I jxcore-log: 
,09-15 08:27:13.797  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:27:18.377  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:18.377  5439  5485 I jxcore-log: 
09-15 08:27:18.378  5439  5485 I jxcore-log: websocket error
09-15 08:27:18.378  5439  5485 I jxcore-log: 
09-15 08:27:18.378  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:18.378  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:18.378  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:18.378  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:18.378  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:18.378  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:18.378  5439  5485 I jxcore-log: 
,09-15 08:27:23.404  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:23.404  5439  5485 I jxcore-log: 
,09-15 08:27:23.404  5439  5485 I jxcore-log: websocket error
09-15 08:27:23.404  5439  5485 I jxcore-log: 
09-15 08:27:23.404  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:23.404  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:23.404  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:23.404  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:23.404  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:23.404  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:23.404  5439  5485 I jxcore-log: 
,09-15 08:27:23.798  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:24.799  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:25.800  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:26.801  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:27.802  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:28.433  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:28.433  5439  5485 I jxcore-log: 
,09-15 08:27:28.433  5439  5485 I jxcore-log: websocket error
09-15 08:27:28.433  5439  5485 I jxcore-log: 
09-15 08:27:28.434  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:28.434  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:28.434  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:28.434  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:28.434  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:28.434  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:28.434  5439  5485 I jxcore-log: 
,09-15 08:27:28.803  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:27:33.462  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:33.462  5439  5485 I jxcore-log: 
09-15 08:27:33.463  5439  5485 I jxcore-log: websocket error
09-15 08:27:33.463  5439  5485 I jxcore-log: 
09-15 08:27:33.464  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:33.464  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:33.464  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:33.464  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:33.464  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:33.464  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:33.464  5439  5485 I jxcore-log: 
,09-15 08:27:38.489  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:38.489  5439  5485 I jxcore-log: 
09-15 08:27:38.489  5439  5485 I jxcore-log: websocket error
09-15 08:27:38.489  5439  5485 I jxcore-log: 
09-15 08:27:38.489  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:38.489  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:38.489  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:38.489  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:38.489  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:38.489  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:38.489  5439  5485 I jxcore-log: 
,09-15 08:27:43.515  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:43.515  5439  5485 I jxcore-log: 
,09-15 08:27:43.515  5439  5485 I jxcore-log: websocket error
09-15 08:27:43.515  5439  5485 I jxcore-log: 
09-15 08:27:43.516  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:43.516  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:43.516  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:43.516  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:43.516  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:43.516  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:43.516  5439  5485 I jxcore-log: 
,09-15 08:27:43.804  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:44.805  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:45.806  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:46.808  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:47.809  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:27:48.545  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:48.545  5439  5485 I jxcore-log: 
,09-15 08:27:48.545  5439  5485 I jxcore-log: websocket error
09-15 08:27:48.545  5439  5485 I jxcore-log: 
09-15 08:27:48.546  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:48.546  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:48.546  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:48.546  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:48.546  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:48.546  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:48.546  5439  5485 I jxcore-log: 
,09-15 08:27:48.810  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:27:53.572  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:53.572  5439  5485 I jxcore-log: 
,09-15 08:27:53.572  5439  5485 I jxcore-log: websocket error
09-15 08:27:53.572  5439  5485 I jxcore-log: 
09-15 08:27:53.573  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:53.573  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:53.573  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:53.573  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:53.573  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:53.573  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:53.573  5439  5485 I jxcore-log: 
,09-15 08:27:58.600  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:27:58.600  5439  5485 I jxcore-log: 
,09-15 08:27:58.600  5439  5485 I jxcore-log: websocket error
09-15 08:27:58.600  5439  5485 I jxcore-log: 
09-15 08:27:58.601  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:27:58.601  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:27:58.601  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:27:58.601  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:58.601  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:27:58.601  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:27:58.601  5439  5485 I jxcore-log: 
,09-15 08:28:03.627  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:03.627  5439  5485 I jxcore-log: 
09-15 08:28:03.627  5439  5485 I jxcore-log: websocket error
09-15 08:28:03.627  5439  5485 I jxcore-log: 
09-15 08:28:03.627  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:03.627  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:03.627  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:03.627  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:03.627  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:03.627  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:03.627  5439  5485 I jxcore-log: 
,09-15 08:28:08.654  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:08.654  5439  5485 I jxcore-log: 
09-15 08:28:08.654  5439  5485 I jxcore-log: websocket error
09-15 08:28:08.654  5439  5485 I jxcore-log: 
09-15 08:28:08.655  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:08.655  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:08.655  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:08.655  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:08.655  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:08.655  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:08.655  5439  5485 I jxcore-log: 
,09-15 08:28:08.811  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:09.812  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:10.813  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:11.813  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:12.814  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:13.679  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:13.679  5439  5485 I jxcore-log: 
,09-15 08:28:13.679  5439  5485 I jxcore-log: websocket error
09-15 08:28:13.679  5439  5485 I jxcore-log: 
,09-15 08:28:13.679  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:13.679  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:13.679  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:13.679  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:13.679  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:13.679  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:13.679  5439  5485 I jxcore-log: 
,09-15 08:28:13.815  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:28:18.705  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:18.705  5439  5485 I jxcore-log: 
,09-15 08:28:18.707  5439  5485 I jxcore-log: websocket error
09-15 08:28:18.707  5439  5485 I jxcore-log: 
,09-15 08:28:18.707  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:18.707  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:18.707  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:18.707  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:18.707  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:18.707  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:18.707  5439  5485 I jxcore-log: 
,09-15 08:28:23.733  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:23.733  5439  5485 I jxcore-log: 
09-15 08:28:23.733  5439  5485 I jxcore-log: websocket error
09-15 08:28:23.733  5439  5485 I jxcore-log: 
09-15 08:28:23.734  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:23.734  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:23.734  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:23.734  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:23.734  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:23.734  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:23.734  5439  5485 I jxcore-log: 
,09-15 08:28:28.759  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:28.759  5439  5485 I jxcore-log: 
,09-15 08:28:28.759  5439  5485 I jxcore-log: websocket error
09-15 08:28:28.759  5439  5485 I jxcore-log: 
09-15 08:28:28.759  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:28.759  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:28.759  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:28.759  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:28.759  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:28.759  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:28.759  5439  5485 I jxcore-log: 
,09-15 08:28:33.785  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:33.785  5439  5485 I jxcore-log: 
,09-15 08:28:33.786  5439  5485 I jxcore-log: websocket error
09-15 08:28:33.786  5439  5485 I jxcore-log: 
09-15 08:28:33.786  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:33.786  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:33.786  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:33.786  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:33.786  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:33.786  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:33.786  5439  5485 I jxcore-log: 
,09-15 08:28:38.813  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:38.813  5439  5485 I jxcore-log: 
,09-15 08:28:38.813  5439  5485 I jxcore-log: websocket error
09-15 08:28:38.813  5439  5485 I jxcore-log: 
09-15 08:28:38.814  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:38.814  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:38.814  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:38.814  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:38.814  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:38.814  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:38.814  5439  5485 I jxcore-log: 
09-15 08:28:38.816  5753  5753 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 08:28:38.816  5753  5753 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:28:43.839  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:43.839  5439  5485 I jxcore-log: 
09-15 08:28:43.839  5439  5485 I jxcore-log: websocket error
09-15 08:28:43.839  5439  5485 I jxcore-log: 
09-15 08:28:43.840  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:43.840  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:43.840  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:43.840  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:43.840  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:43.840  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:43.840  5439  5485 I jxcore-log: 
,09-15 08:28:48.863  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:48.863  5439  5485 I jxcore-log: 
09-15 08:28:48.864  5439  5485 I jxcore-log: websocket error
09-15 08:28:48.864  5439  5485 I jxcore-log: 
,09-15 08:28:48.864  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:48.864  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:48.864  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:48.864  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:48.864  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:48.864  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:48.864  5439  5485 I jxcore-log: 
,09-15 08:28:53.817  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:53.890  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:53.890  5439  5485 I jxcore-log: 
09-15 08:28:53.890  5439  5485 I jxcore-log: websocket error
09-15 08:28:53.890  5439  5485 I jxcore-log: 
09-15 08:28:53.891  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:53.891  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:53.891  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:53.891  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:53.891  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:53.891  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:53.891  5439  5485 I jxcore-log: 
,09-15 08:28:54.818  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:55.819  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:56.820  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:57.822  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:28:58.822  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:28:58.915  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:28:58.915  5439  5485 I jxcore-log: 
,09-15 08:28:58.916  5439  5485 I jxcore-log: websocket error
09-15 08:28:58.916  5439  5485 I jxcore-log: 
09-15 08:28:58.916  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:28:58.916  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:28:58.916  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:28:58.916  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:58.916  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:28:58.916  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:28:58.916  5439  5485 I jxcore-log: 
,09-15 08:29:03.824  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:03.948  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:03.948  5439  5485 I jxcore-log: 
09-15 08:29:03.949  5439  5485 I jxcore-log: websocket error
09-15 08:29:03.949  5439  5485 I jxcore-log: 
09-15 08:29:03.949  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:03.949  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:03.949  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:03.949  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:03.949  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:03.949  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:03.949  5439  5485 I jxcore-log: 
,09-15 08:29:04.825  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:05.826  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:06.827  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:07.828  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:08.829  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:29:08.972  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:08.972  5439  5485 I jxcore-log: 
,09-15 08:29:08.972  5439  5485 I jxcore-log: websocket error
09-15 08:29:08.972  5439  5485 I jxcore-log: 
,09-15 08:29:08.973  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:08.973  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:08.973  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:08.973  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:08.973  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:08.973  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:08.973  5439  5485 I jxcore-log: 
,09-15 08:29:13.997  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:13.997  5439  5485 I jxcore-log: 
09-15 08:29:13.998  5439  5485 I jxcore-log: websocket error
09-15 08:29:13.998  5439  5485 I jxcore-log: 
09-15 08:29:13.998  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:13.998  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:13.998  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:13.998  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:13.998  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:13.998  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:13.998  5439  5485 I jxcore-log: 
,09-15 08:29:18.830  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:19.023  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:19.023  5439  5485 I jxcore-log: 
,09-15 08:29:19.024  5439  5485 I jxcore-log: websocket error
09-15 08:29:19.024  5439  5485 I jxcore-log: 
,09-15 08:29:19.024  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:19.024  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:19.024  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:19.024  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:19.024  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:19.024  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:19.024  5439  5485 I jxcore-log: 
,09-15 08:29:19.831  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:20.832  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:21.833  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:22.834  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:23.835  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:29:24.049  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:24.049  5439  5485 I jxcore-log: 
,09-15 08:29:24.050  5439  5485 I jxcore-log: websocket error
09-15 08:29:24.050  5439  5485 I jxcore-log: 
09-15 08:29:24.050  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:24.050  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:24.050  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:24.050  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:24.050  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:24.050  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:24.050  5439  5485 I jxcore-log: 
,09-15 08:29:29.075  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:29.075  5439  5485 I jxcore-log: 
,09-15 08:29:29.076  5439  5485 I jxcore-log: websocket error
09-15 08:29:29.076  5439  5485 I jxcore-log: 
09-15 08:29:29.076  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:29.076  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:29.076  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:29.076  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:29.076  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:29.076  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:29.076  5439  5485 I jxcore-log: 
,09-15 08:29:34.104  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:34.104  5439  5485 I jxcore-log: 
,09-15 08:29:34.105  5439  5485 I jxcore-log: websocket error
09-15 08:29:34.105  5439  5485 I jxcore-log: 
09-15 08:29:34.105  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:34.105  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:34.105  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:34.105  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:34.105  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:34.105  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:34.105  5439  5485 I jxcore-log: 
,09-15 08:29:38.836  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:39.130  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:39.130  5439  5485 I jxcore-log: 
09-15 08:29:39.131  5439  5485 I jxcore-log: websocket error
09-15 08:29:39.131  5439  5485 I jxcore-log: 
09-15 08:29:39.131  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:39.131  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:39.131  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:39.131  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:39.131  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:39.131  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:39.131  5439  5485 I jxcore-log: 
,09-15 08:29:39.837  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:40.838  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:41.840  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:42.841  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:29:43.842  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:29:44.155  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:44.155  5439  5485 I jxcore-log: 
09-15 08:29:44.155  5439  5485 I jxcore-log: websocket error
09-15 08:29:44.155  5439  5485 I jxcore-log: 
,09-15 08:29:44.155  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:44.155  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:44.155  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:44.155  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:44.155  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:44.155  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:44.155  5439  5485 I jxcore-log: 
,09-15 08:29:49.187  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:49.187  5439  5485 I jxcore-log: 
,09-15 08:29:49.189  5439  5485 I jxcore-log: websocket error
09-15 08:29:49.189  5439  5485 I jxcore-log: 
09-15 08:29:49.189  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:49.189  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:49.189  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:49.189  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:49.189  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:49.189  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:49.189  5439  5485 I jxcore-log: 
,09-15 08:29:54.212  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:54.212  5439  5485 I jxcore-log: 
,09-15 08:29:54.212  5439  5485 I jxcore-log: websocket error
09-15 08:29:54.212  5439  5485 I jxcore-log: 
,09-15 08:29:54.213  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:54.213  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:54.213  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:54.213  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:54.213  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:54.213  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:54.213  5439  5485 I jxcore-log: 
,09-15 08:29:59.244  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:29:59.244  5439  5485 I jxcore-log: 
,09-15 08:29:59.244  5439  5485 I jxcore-log: websocket error
09-15 08:29:59.244  5439  5485 I jxcore-log: 
09-15 08:29:59.245  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:29:59.245  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:29:59.245  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:29:59.245  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:59.245  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:29:59.245  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:29:59.245  5439  5485 I jxcore-log: 
,09-15 08:30:03.843  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:04.269  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:04.269  5439  5485 I jxcore-log: 
09-15 08:30:04.269  5439  5485 I jxcore-log: websocket error
09-15 08:30:04.269  5439  5485 I jxcore-log: 
09-15 08:30:04.269  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:04.269  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:04.269  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:04.269  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:04.269  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:04.269  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:04.269  5439  5485 I jxcore-log: 
,09-15 08:30:04.845  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:05.846  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:06.847  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:07.848  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:08.849  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:30:09.295  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:09.295  5439  5485 I jxcore-log: 
09-15 08:30:09.296  5439  5485 I jxcore-log: websocket error
09-15 08:30:09.296  5439  5485 I jxcore-log: 
09-15 08:30:09.296  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:09.296  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:09.296  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:09.296  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:09.296  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:09.296  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:09.296  5439  5485 I jxcore-log: 
,09-15 08:30:14.324  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:14.324  5439  5485 I jxcore-log: 
09-15 08:30:14.325  5439  5485 I jxcore-log: websocket error
09-15 08:30:14.325  5439  5485 I jxcore-log: 
09-15 08:30:14.325  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:14.325  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:14.325  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:14.325  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:14.325  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:14.325  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:14.325  5439  5485 I jxcore-log: 
,09-15 08:30:19.353  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:19.353  5439  5485 I jxcore-log: 
,09-15 08:30:19.353  5439  5485 I jxcore-log: websocket error
09-15 08:30:19.353  5439  5485 I jxcore-log: 
09-15 08:30:19.354  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:19.354  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:19.354  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:19.354  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:19.354  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:19.354  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:19.354  5439  5485 I jxcore-log: 
,09-15 08:30:24.382  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:24.382  5439  5485 I jxcore-log: 
,09-15 08:30:24.382  5439  5485 I jxcore-log: websocket error
09-15 08:30:24.382  5439  5485 I jxcore-log: 
,09-15 08:30:24.383  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:24.383  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:24.383  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:24.383  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:24.383  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:24.383  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:24.383  5439  5485 I jxcore-log: 
,09-15 08:30:29.408  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:29.408  5439  5485 I jxcore-log: 
09-15 08:30:29.408  5439  5485 I jxcore-log: websocket error
09-15 08:30:29.408  5439  5485 I jxcore-log: 
09-15 08:30:29.408  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:29.408  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:29.408  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:29.408  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:29.408  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:29.408  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:29.408  5439  5485 I jxcore-log: 
,09-15 08:30:33.850  5753  5753 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:30:33.850  5753  5753 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:30:34.433  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:34.433  5439  5485 I jxcore-log: 
,09-15 08:30:34.434  5439  5485 I jxcore-log: websocket error
09-15 08:30:34.434  5439  5485 I jxcore-log: 
,09-15 08:30:34.434  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:34.434  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:34.434  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:34.434  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:34.434  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:34.434  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:34.434  5439  5485 I jxcore-log: 
,09-15 08:30:39.459  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:39.459  5439  5485 I jxcore-log: 
09-15 08:30:39.459  5439  5485 I jxcore-log: websocket error
09-15 08:30:39.459  5439  5485 I jxcore-log: 
09-15 08:30:39.460  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:39.460  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:39.460  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:39.460  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:39.460  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:39.460  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:39.460  5439  5485 I jxcore-log: 
,09-15 08:30:44.485  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:44.485  5439  5485 I jxcore-log: 
,09-15 08:30:44.486  5439  5485 I jxcore-log: websocket error
09-15 08:30:44.486  5439  5485 I jxcore-log: 
09-15 08:30:44.486  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:44.486  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:44.486  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:44.486  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:44.486  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:44.486  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:44.486  5439  5485 I jxcore-log: 
,09-15 08:30:49.513  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:49.513  5439  5485 I jxcore-log: 
09-15 08:30:49.514  5439  5485 I jxcore-log: websocket error
09-15 08:30:49.514  5439  5485 I jxcore-log: 
,09-15 08:30:49.514  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:49.514  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:49.514  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:49.514  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:49.514  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:49.514  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:49.514  5439  5485 I jxcore-log: 
,09-15 08:30:53.851  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:54.538  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:54.538  5439  5485 I jxcore-log: 
09-15 08:30:54.539  5439  5485 I jxcore-log: websocket error
09-15 08:30:54.539  5439  5485 I jxcore-log: 
,09-15 08:30:54.539  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:54.539  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:54.539  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:54.539  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:54.539  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:54.539  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:54.539  5439  5485 I jxcore-log: 
,09-15 08:30:54.853  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:55.854  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:56.855  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:57.856  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:30:58.857  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:30:59.567  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:30:59.567  5439  5485 I jxcore-log: 
09-15 08:30:59.567  5439  5485 I jxcore-log: websocket error
09-15 08:30:59.567  5439  5485 I jxcore-log: 
,09-15 08:30:59.567  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:30:59.567  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:30:59.567  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:30:59.567  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:59.567  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:30:59.567  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:30:59.567  5439  5485 I jxcore-log: 
,09-15 08:31:03.858  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:04.592  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:04.592  5439  5485 I jxcore-log: 
,09-15 08:31:04.592  5439  5485 I jxcore-log: websocket error
09-15 08:31:04.592  5439  5485 I jxcore-log: 
,09-15 08:31:04.592  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:04.592  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:04.592  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:04.592  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:04.592  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:04.592  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:04.592  5439  5485 I jxcore-log: 
,09-15 08:31:04.859  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:05.861  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:06.862  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:07.863  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:08.864  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:31:09.620  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:09.620  5439  5485 I jxcore-log: 
09-15 08:31:09.620  5439  5485 I jxcore-log: websocket error
09-15 08:31:09.620  5439  5485 I jxcore-log: 
,09-15 08:31:09.622  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:09.622  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:09.622  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:09.622  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:09.622  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:09.622  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:09.622  5439  5485 I jxcore-log: 
,09-15 08:31:14.691  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:14.691  5439  5485 I jxcore-log: 
09-15 08:31:14.691  5439  5485 I jxcore-log: websocket error
09-15 08:31:14.691  5439  5485 I jxcore-log: 
09-15 08:31:14.691  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:14.691  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:14.691  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:14.691  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:14.691  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:14.691  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:14.691  5439  5485 I jxcore-log: 
,09-15 08:31:18.865  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:19.718  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:19.718  5439  5485 I jxcore-log: 
09-15 08:31:19.719  5439  5485 I jxcore-log: websocket error
09-15 08:31:19.719  5439  5485 I jxcore-log: 
09-15 08:31:19.719  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:19.719  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:19.719  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:19.719  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:19.719  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:19.719  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:19.719  5439  5485 I jxcore-log: 
,09-15 08:31:19.866  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:20.867  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:21.868  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:22.869  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:23.870  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:31:24.747  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:24.747  5439  5485 I jxcore-log: 
,09-15 08:31:24.748  5439  5485 I jxcore-log: websocket error
09-15 08:31:24.748  5439  5485 I jxcore-log: 
09-15 08:31:24.748  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:24.748  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:24.748  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:24.748  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:24.748  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:24.748  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:24.748  5439  5485 I jxcore-log: 
,09-15 08:31:29.773  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:29.773  5439  5485 I jxcore-log: 
09-15 08:31:29.774  5439  5485 I jxcore-log: websocket error
09-15 08:31:29.774  5439  5485 I jxcore-log: 
,09-15 08:31:29.774  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:29.774  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:29.774  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:29.774  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:29.774  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:29.774  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:29.774  5439  5485 I jxcore-log: 
,09-15 08:31:34.800  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:34.800  5439  5485 I jxcore-log: 
,09-15 08:31:34.801  5439  5485 I jxcore-log: websocket error
09-15 08:31:34.801  5439  5485 I jxcore-log: 
09-15 08:31:34.801  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:34.801  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:34.801  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:34.801  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:34.801  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:34.801  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:34.801  5439  5485 I jxcore-log: 
,09-15 08:31:38.871  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:39.825  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:39.825  5439  5485 I jxcore-log: 
,09-15 08:31:39.826  5439  5485 I jxcore-log: websocket error
09-15 08:31:39.826  5439  5485 I jxcore-log: 
09-15 08:31:39.826  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:39.826  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:39.826  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:39.826  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:39.826  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:39.826  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:39.826  5439  5485 I jxcore-log: 
,09-15 08:31:39.872  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:40.873  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:41.875  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:42.876  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:31:43.877  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:31:44.854  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:44.854  5439  5485 I jxcore-log: 
09-15 08:31:44.855  5439  5485 I jxcore-log: websocket error
09-15 08:31:44.855  5439  5485 I jxcore-log: 
09-15 08:31:44.855  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:44.855  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:44.855  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:44.855  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:44.855  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:44.855  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:44.855  5439  5485 I jxcore-log: 
,09-15 08:31:49.882  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:49.882  5439  5485 I jxcore-log: 
09-15 08:31:49.882  5439  5485 I jxcore-log: websocket error
09-15 08:31:49.882  5439  5485 I jxcore-log: 
,09-15 08:31:49.883  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:49.883  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:49.883  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:49.883  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:49.883  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:49.883  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:49.883  5439  5485 I jxcore-log: 
,09-15 08:31:54.908  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:54.908  5439  5485 I jxcore-log: 
,09-15 08:31:54.909  5439  5485 I jxcore-log: websocket error
09-15 08:31:54.909  5439  5485 I jxcore-log: 
09-15 08:31:54.909  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:54.909  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:54.909  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:54.909  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:54.909  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:54.909  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:54.909  5439  5485 I jxcore-log: 
,09-15 08:31:59.934  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:31:59.934  5439  5485 I jxcore-log: 
,09-15 08:31:59.935  5439  5485 I jxcore-log: websocket error
09-15 08:31:59.935  5439  5485 I jxcore-log: 
09-15 08:31:59.935  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:31:59.935  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:31:59.935  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:31:59.935  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:59.935  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:31:59.935  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:31:59.935  5439  5485 I jxcore-log: 
,09-15 08:32:03.879  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:32:04.881  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:32:04.963  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:04.963  5439  5485 I jxcore-log: 
,09-15 08:32:04.963  5439  5485 I jxcore-log: websocket error
09-15 08:32:04.963  5439  5485 I jxcore-log: 
09-15 08:32:04.964  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:04.964  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:04.964  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:04.964  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:04.964  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:04.964  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:04.964  5439  5485 I jxcore-log: 
,09-15 08:32:05.883  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:32:06.884  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:32:07.885  5753  5753 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:32:08.886  5753  5753 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:32:09.989  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:09.989  5439  5485 I jxcore-log: 
,09-15 08:32:09.989  5439  5485 I jxcore-log: websocket error
09-15 08:32:09.989  5439  5485 I jxcore-log: 
09-15 08:32:09.989  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:09.989  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:09.989  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:09.989  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:09.989  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:09.989  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:09.989  5439  5485 I jxcore-log: 
,09-15 08:32:15.017  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:15.017  5439  5485 I jxcore-log: 
09-15 08:32:15.017  5439  5485 I jxcore-log: websocket error
09-15 08:32:15.017  5439  5485 I jxcore-log: 
09-15 08:32:15.018  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:15.018  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:15.018  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:15.018  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:15.018  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:15.018  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:15.018  5439  5485 I jxcore-log: 
,09-15 08:32:20.048  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:20.048  5439  5485 I jxcore-log: 
,09-15 08:32:20.048  5439  5485 I jxcore-log: websocket error
09-15 08:32:20.048  5439  5485 I jxcore-log: 
09-15 08:32:20.048  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:20.048  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:20.048  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:20.048  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:20.048  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:20.048  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:20.048  5439  5485 I jxcore-log: 
,09-15 08:32:25.075  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:25.075  5439  5485 I jxcore-log: 
,09-15 08:32:25.075  5439  5485 I jxcore-log: websocket error
09-15 08:32:25.075  5439  5485 I jxcore-log: 
09-15 08:32:25.075  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:25.075  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:25.075  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:25.075  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:25.075  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:25.075  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:25.075  5439  5485 I jxcore-log: 
,09-15 08:32:30.103  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:30.103  5439  5485 I jxcore-log: 
09-15 08:32:30.103  5439  5485 I jxcore-log: websocket error
09-15 08:32:30.103  5439  5485 I jxcore-log: 
,09-15 08:32:30.103  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:30.103  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:30.103  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:30.103  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:30.103  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:30.103  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:30.103  5439  5485 I jxcore-log: 
,09-15 08:32:33.886  5753  5753 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 08:32:33.887  5753  5753 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:32:35.130  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:35.130  5439  5485 I jxcore-log: 
,09-15 08:32:35.131  5439  5485 I jxcore-log: websocket error
09-15 08:32:35.131  5439  5485 I jxcore-log: 
,09-15 08:32:35.131  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:35.131  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:35.131  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:35.131  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:35.131  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:35.131  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:35.131  5439  5485 I jxcore-log: 
,09-15 08:32:40.160  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:40.160  5439  5485 I jxcore-log: 
09-15 08:32:40.161  5439  5485 I jxcore-log: websocket error
09-15 08:32:40.161  5439  5485 I jxcore-log: 
,09-15 08:32:40.161  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:40.161  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:40.161  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:40.161  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:40.161  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:40.161  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:40.161  5439  5485 I jxcore-log: 
,09-15 08:32:45.188  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:45.188  5439  5485 I jxcore-log: 
,09-15 08:32:45.188  5439  5485 I jxcore-log: websocket error
09-15 08:32:45.188  5439  5485 I jxcore-log: 
09-15 08:32:45.189  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:45.189  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:45.189  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:45.189  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:45.189  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:45.189  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:45.189  5439  5485 I jxcore-log: 
,09-15 08:32:50.215  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:50.215  5439  5485 I jxcore-log: 
09-15 08:32:50.215  5439  5485 I jxcore-log: websocket error
09-15 08:32:50.215  5439  5485 I jxcore-log: 
09-15 08:32:50.215  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:50.215  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:50.215  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:50.215  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:50.215  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:50.215  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:50.215  5439  5485 I jxcore-log: 
,09-15 08:32:55.240  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:32:55.240  5439  5485 I jxcore-log: 
09-15 08:32:55.241  5439  5485 I jxcore-log: websocket error
09-15 08:32:55.241  5439  5485 I jxcore-log: 
09-15 08:32:55.241  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:32:55.241  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:32:55.241  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:32:55.241  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:55.241  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:32:55.241  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:32:55.241  5439  5485 I jxcore-log: 
,09-15 08:32:58.898  5753  5755 E QC-QMI  : qmi_client [5753] 1d: failed to locate client data
,09-15 08:32:58.901   521   521 E QC-QMI  : qmuxd: RX on fd=17 returned error=0 errno[2:No such file or directory]
09-15 08:32:58.901   521   521 E QC-QMI  : QMUX qmux_client_id=1d not found in qmux client list, unable to remove
,09-15 08:32:58.907  5753  5753 I Atfwd_Daemon: Stop the daemon....
,09-15 08:32:58.952  5768  5768 I libmdmdetect: ESOC framework not supported
,09-15 08:32:58.952  5768  5768 I libmdmdetect: Found internal modem: modem
09-15 08:32:58.953  5768  5768 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
09-15 08:32:58.948  5768  5768 W ATFWD-daemon: type=1400 audit(0.0:121): avc: denied { read write } for name="diag" dev="tmpfs" ino=12486 scontext=u:r:atfwd:s0 tcontext=u:object_r:diag_device:s0 tclass=chr_file permissive=0
,09-15 08:32:58.962  5768  5768 I Atfwd_Daemon: result : 255 	 ,Init step :0 	 ,qmiErrorCode: 0
,09-15 08:32:58.963  5768  5768 I Atfwd_Daemon: result : 0 	 ,Init step :1 	 ,qmiErrorCode: 0
,09-15 08:32:58.963  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:32:59.966  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:00.267  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:00.267  5439  5485 I jxcore-log: 
,09-15 08:33:00.268  5439  5485 I jxcore-log: websocket error
09-15 08:33:00.268  5439  5485 I jxcore-log: 
,09-15 08:33:00.268  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:00.268  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:00.268  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:00.268  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:00.268  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:00.268  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:00.268  5439  5485 I jxcore-log: 
,09-15 08:33:00.967  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:01.968  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:02.970  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:03.971  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:33:05.294  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:05.294  5439  5485 I jxcore-log: 
09-15 08:33:05.294  5439  5485 I jxcore-log: websocket error
09-15 08:33:05.294  5439  5485 I jxcore-log: 
,09-15 08:33:05.294  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:05.294  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:05.294  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:05.294  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:05.294  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:05.294  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:05.294  5439  5485 I jxcore-log: 
,09-15 08:33:08.972  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:09.973  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:10.320  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:10.320  5439  5485 I jxcore-log: 
,09-15 08:33:10.320  5439  5485 I jxcore-log: websocket error
09-15 08:33:10.320  5439  5485 I jxcore-log: 
09-15 08:33:10.321  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:10.321  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:10.321  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:10.321  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:10.321  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:10.321  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:10.321  5439  5485 I jxcore-log: 
,09-15 08:33:10.975  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:11.976  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:12.978  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:13.979  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:33:15.348  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:15.348  5439  5485 I jxcore-log: 
,09-15 08:33:15.348  5439  5485 I jxcore-log: websocket error
09-15 08:33:15.348  5439  5485 I jxcore-log: 
,09-15 08:33:15.349  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:15.349  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:15.349  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:15.349  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:15.349  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:15.349  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:15.349  5439  5485 I jxcore-log: 
,09-15 08:33:20.374  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:20.374  5439  5485 I jxcore-log: 
,09-15 08:33:20.374  5439  5485 I jxcore-log: websocket error
09-15 08:33:20.374  5439  5485 I jxcore-log: 
,09-15 08:33:20.375  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:20.375  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:20.375  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:20.375  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:20.375  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:20.375  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:20.375  5439  5485 I jxcore-log: 
,09-15 08:33:23.980  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:24.981  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:25.404  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:25.404  5439  5485 I jxcore-log: 
09-15 08:33:25.404  5439  5485 I jxcore-log: websocket error
09-15 08:33:25.404  5439  5485 I jxcore-log: 
,09-15 08:33:25.405  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:25.405  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:25.405  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:25.405  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:25.405  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:25.405  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:25.405  5439  5485 I jxcore-log: 
,09-15 08:33:25.982  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:26.983  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:27.985  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:28.985  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:33:30.431  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:30.431  5439  5485 I jxcore-log: 
,09-15 08:33:30.431  5439  5485 I jxcore-log: websocket error
09-15 08:33:30.431  5439  5485 I jxcore-log: 
09-15 08:33:30.431  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:30.431  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:30.431  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:30.431  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:30.431  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:30.431  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:30.431  5439  5485 I jxcore-log: 
,09-15 08:33:35.457  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:35.457  5439  5485 I jxcore-log: 
09-15 08:33:35.458  5439  5485 I jxcore-log: websocket error
09-15 08:33:35.458  5439  5485 I jxcore-log: 
09-15 08:33:35.458  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:35.458  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:35.458  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:35.458  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:35.458  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:35.458  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:35.458  5439  5485 I jxcore-log: 
,09-15 08:33:40.484  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:40.484  5439  5485 I jxcore-log: 
,09-15 08:33:40.484  5439  5485 I jxcore-log: websocket error
09-15 08:33:40.484  5439  5485 I jxcore-log: 
09-15 08:33:40.484  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:40.484  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:40.484  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:40.484  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:40.484  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:40.484  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:40.484  5439  5485 I jxcore-log: 
,09-15 08:33:43.987  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:44.988  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:45.511  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:45.511  5439  5485 I jxcore-log: 
,09-15 08:33:45.511  5439  5485 I jxcore-log: websocket error
09-15 08:33:45.511  5439  5485 I jxcore-log: 
09-15 08:33:45.512  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:45.512  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:45.512  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:45.512  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:45.512  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:45.512  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:45.512  5439  5485 I jxcore-log: 
,09-15 08:33:45.989  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:46.990  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:47.991  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:33:48.991  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:33:50.537  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:50.537  5439  5485 I jxcore-log: 
,09-15 08:33:50.537  5439  5485 I jxcore-log: websocket error
09-15 08:33:50.537  5439  5485 I jxcore-log: 
09-15 08:33:50.537  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:50.537  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:50.537  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:50.537  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:50.537  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:50.537  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:50.537  5439  5485 I jxcore-log: 
,09-15 08:33:53.466   929   941 I UsageStatsService: User[0] Flushing usage stats to disk
,09-15 08:33:55.565  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:33:55.565  5439  5485 I jxcore-log: 
,09-15 08:33:55.566  5439  5485 I jxcore-log: websocket error
09-15 08:33:55.566  5439  5485 I jxcore-log: 
09-15 08:33:55.566  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:33:55.566  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:33:55.566  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:33:55.566  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:55.566  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:33:55.566  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:33:55.566  5439  5485 I jxcore-log: 
,09-15 08:34:00.593  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:00.593  5439  5485 I jxcore-log: 
,09-15 08:34:00.594  5439  5485 I jxcore-log: websocket error
09-15 08:34:00.594  5439  5485 I jxcore-log: 
09-15 08:34:00.594  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:00.594  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:00.594  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:00.594  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:00.594  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:00.594  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:00.594  5439  5485 I jxcore-log: 
,09-15 08:34:05.621  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:05.621  5439  5485 I jxcore-log: 
09-15 08:34:05.621  5439  5485 I jxcore-log: websocket error
09-15 08:34:05.621  5439  5485 I jxcore-log: 
09-15 08:34:05.621  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:05.621  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:05.621  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:05.621  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:05.621  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:05.621  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:05.621  5439  5485 I jxcore-log: 
,09-15 08:34:08.993  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:09.994  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:10.649  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:10.649  5439  5485 I jxcore-log: 
,09-15 08:34:10.650  5439  5485 I jxcore-log: websocket error
09-15 08:34:10.650  5439  5485 I jxcore-log: 
,09-15 08:34:10.650  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:10.650  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:10.650  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:10.650  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:10.650  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:10.650  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:10.650  5439  5485 I jxcore-log: 
,09-15 08:34:10.996  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:11.998  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:12.999  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:14.000  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:34:15.675  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:15.675  5439  5485 I jxcore-log: 
,09-15 08:34:15.675  5439  5485 I jxcore-log: websocket error
09-15 08:34:15.675  5439  5485 I jxcore-log: 
09-15 08:34:15.676  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:15.676  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:15.676  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:15.676  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:15.676  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:15.676  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:15.676  5439  5485 I jxcore-log: 
,09-15 08:34:20.704  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:20.704  5439  5485 I jxcore-log: 
,09-15 08:34:20.704  5439  5485 I jxcore-log: websocket error
09-15 08:34:20.704  5439  5485 I jxcore-log: 
09-15 08:34:20.705  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:20.705  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:20.705  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:20.705  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:20.705  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:20.705  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:20.705  5439  5485 I jxcore-log: 
,09-15 08:34:25.737  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:25.737  5439  5485 I jxcore-log: 
,09-15 08:34:25.737  5439  5485 I jxcore-log: websocket error
09-15 08:34:25.737  5439  5485 I jxcore-log: 
09-15 08:34:25.738  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:25.738  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:25.738  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:25.738  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:25.738  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:25.738  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:25.738  5439  5485 I jxcore-log: 
,09-15 08:34:30.765  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:30.765  5439  5485 I jxcore-log: 
,09-15 08:34:30.765  5439  5485 I jxcore-log: websocket error
09-15 08:34:30.765  5439  5485 I jxcore-log: 
09-15 08:34:30.766  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:30.766  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:30.766  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:30.766  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:30.766  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:30.766  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:30.766  5439  5485 I jxcore-log: 
,09-15 08:34:35.791  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:35.791  5439  5485 I jxcore-log: 
09-15 08:34:35.791  5439  5485 I jxcore-log: websocket error
09-15 08:34:35.791  5439  5485 I jxcore-log: 
,09-15 08:34:35.792  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:35.792  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:35.792  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:35.792  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:35.792  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:35.792  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:35.792  5439  5485 I jxcore-log: 
,09-15 08:34:39.001  5768  5768 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:34:39.001  5768  5768 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:34:40.825  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:40.825  5439  5485 I jxcore-log: 
,09-15 08:34:40.825  5439  5485 I jxcore-log: websocket error
09-15 08:34:40.825  5439  5485 I jxcore-log: 
09-15 08:34:40.826  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:40.826  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:40.826  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:40.826  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:40.826  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:40.826  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:40.826  5439  5485 I jxcore-log: 
,09-15 08:34:44.002  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:45.004  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:45.867  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:45.867  5439  5485 I jxcore-log: 
,09-15 08:34:45.868  5439  5485 I jxcore-log: websocket error
09-15 08:34:45.868  5439  5485 I jxcore-log: 
,09-15 08:34:45.868  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:45.868  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:45.868  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:45.868  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:45.868  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:45.868  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:45.868  5439  5485 I jxcore-log: 
,09-15 08:34:46.005  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:47.006  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:48.007  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:49.008  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:34:50.893  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:50.893  5439  5485 I jxcore-log: 
,09-15 08:34:50.894  5439  5485 I jxcore-log: websocket error
09-15 08:34:50.894  5439  5485 I jxcore-log: 
09-15 08:34:50.894  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:50.894  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:50.894  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:50.894  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:50.894  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:50.894  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:50.894  5439  5485 I jxcore-log: 
,09-15 08:34:54.009  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:55.011  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:55.918  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:34:55.918  5439  5485 I jxcore-log: 
,09-15 08:34:55.919  5439  5485 I jxcore-log: websocket error
09-15 08:34:55.919  5439  5485 I jxcore-log: 
09-15 08:34:55.919  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:34:55.919  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:34:55.919  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:34:55.919  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:55.919  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:34:55.919  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:34:55.919  5439  5485 I jxcore-log: 
,09-15 08:34:56.012  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:57.013  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:58.014  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:34:59.015  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:35:00.947  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:00.947  5439  5485 I jxcore-log: 
,09-15 08:35:00.947  5439  5485 I jxcore-log: websocket error
09-15 08:35:00.947  5439  5485 I jxcore-log: 
09-15 08:35:00.948  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:00.948  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:00.948  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:00.948  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:00.948  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:00.948  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:00.948  5439  5485 I jxcore-log: 
,09-15 08:35:05.974  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:05.974  5439  5485 I jxcore-log: 
,09-15 08:35:05.974  5439  5485 I jxcore-log: websocket error
09-15 08:35:05.974  5439  5485 I jxcore-log: 
09-15 08:35:05.975  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:05.975  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:05.975  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:05.975  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:05.975  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:05.975  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:05.975  5439  5485 I jxcore-log: 
,09-15 08:35:09.016  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:10.017  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:11.000  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:11.000  5439  5485 I jxcore-log: 
,09-15 08:35:11.000  5439  5485 I jxcore-log: websocket error
09-15 08:35:11.000  5439  5485 I jxcore-log: 
,09-15 08:35:11.001  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:11.001  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:11.001  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:11.001  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:11.001  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:11.001  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:11.001  5439  5485 I jxcore-log: 
,09-15 08:35:11.018  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:12.022  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:13.023  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:14.024  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:35:16.025  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:16.025  5439  5485 I jxcore-log: 
09-15 08:35:16.026  5439  5485 I jxcore-log: websocket error
09-15 08:35:16.026  5439  5485 I jxcore-log: 
09-15 08:35:16.026  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:16.026  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:16.026  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:16.026  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:16.026  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:16.026  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:16.026  5439  5485 I jxcore-log: 
,09-15 08:35:21.051  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:21.051  5439  5485 I jxcore-log: 
,09-15 08:35:21.051  5439  5485 I jxcore-log: websocket error
09-15 08:35:21.051  5439  5485 I jxcore-log: 
09-15 08:35:21.051  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:21.051  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:21.051  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:21.051  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:21.051  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:21.051  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:21.051  5439  5485 I jxcore-log: 
,09-15 08:35:26.080  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:26.080  5439  5485 I jxcore-log: 
,09-15 08:35:26.081  5439  5485 I jxcore-log: websocket error
09-15 08:35:26.081  5439  5485 I jxcore-log: 
09-15 08:35:26.081  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:26.081  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:26.081  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:26.081  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:26.081  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:26.081  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:26.081  5439  5485 I jxcore-log: 
,09-15 08:35:29.025  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:30.027  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:31.028  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:31.109  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:31.109  5439  5485 I jxcore-log: 
,09-15 08:35:31.110  5439  5485 I jxcore-log: websocket error
09-15 08:35:31.110  5439  5485 I jxcore-log: 
09-15 08:35:31.110  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:31.110  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:31.110  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:31.110  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:31.110  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:31.110  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:31.110  5439  5485 I jxcore-log: 
,09-15 08:35:32.029  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:33.031  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:34.031  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:35:36.133  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:36.133  5439  5485 I jxcore-log: 
,09-15 08:35:36.133  5439  5485 I jxcore-log: websocket error
09-15 08:35:36.133  5439  5485 I jxcore-log: 
09-15 08:35:36.134  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:36.134  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:36.134  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:36.134  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:36.134  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:36.134  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:36.134  5439  5485 I jxcore-log: 
,09-15 08:35:41.162  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:41.162  5439  5485 I jxcore-log: 
09-15 08:35:41.162  5439  5485 I jxcore-log: websocket error
09-15 08:35:41.162  5439  5485 I jxcore-log: 
09-15 08:35:41.163  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:41.163  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:41.163  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:41.163  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:41.163  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:41.163  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:41.163  5439  5485 I jxcore-log: 
,09-15 08:35:46.189  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:46.189  5439  5485 I jxcore-log: 
,09-15 08:35:46.189  5439  5485 I jxcore-log: websocket error
09-15 08:35:46.189  5439  5485 I jxcore-log: 
09-15 08:35:46.190  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:46.190  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:46.190  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:46.190  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:46.190  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:46.190  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:46.190  5439  5485 I jxcore-log: 
,09-15 08:35:51.219  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:51.219  5439  5485 I jxcore-log: 
,09-15 08:35:51.219  5439  5485 I jxcore-log: websocket error
09-15 08:35:51.219  5439  5485 I jxcore-log: 
09-15 08:35:51.219  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:51.219  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:51.219  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:51.219  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:51.219  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:51.219  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:51.219  5439  5485 I jxcore-log: 
,09-15 08:35:54.032  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:55.034  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:56.035  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:56.245  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:35:56.245  5439  5485 I jxcore-log: 
,09-15 08:35:56.245  5439  5485 I jxcore-log: websocket error
09-15 08:35:56.245  5439  5485 I jxcore-log: 
,09-15 08:35:56.245  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:35:56.245  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:35:56.245  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:35:56.245  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:56.245  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:35:56.245  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:35:56.245  5439  5485 I jxcore-log: 
,09-15 08:35:57.037  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:58.038  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:35:59.039  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:36:01.289  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:01.289  5439  5485 I jxcore-log: 
,09-15 08:36:01.289  5439  5485 I jxcore-log: websocket error
09-15 08:36:01.289  5439  5485 I jxcore-log: 
09-15 08:36:01.289  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:01.289  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:01.289  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:01.289  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:01.289  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:01.289  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:01.289  5439  5485 I jxcore-log: 
,09-15 08:36:06.321  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:06.321  5439  5485 I jxcore-log: 
09-15 08:36:06.321  5439  5485 I jxcore-log: websocket error
09-15 08:36:06.321  5439  5485 I jxcore-log: 
09-15 08:36:06.321  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:06.321  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:06.321  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:06.321  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:06.321  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:06.321  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:06.321  5439  5485 I jxcore-log: 
,09-15 08:36:11.348  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:11.348  5439  5485 I jxcore-log: 
,09-15 08:36:11.348  5439  5485 I jxcore-log: websocket error
09-15 08:36:11.348  5439  5485 I jxcore-log: 
09-15 08:36:11.349  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:11.349  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:11.349  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:11.349  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:11.349  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:11.349  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:11.349  5439  5485 I jxcore-log: 
,09-15 08:36:16.377  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:16.377  5439  5485 I jxcore-log: 
09-15 08:36:16.378  5439  5485 I jxcore-log: websocket error
09-15 08:36:16.378  5439  5485 I jxcore-log: 
09-15 08:36:16.378  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:16.378  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:16.378  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:16.378  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:16.378  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:16.378  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:16.378  5439  5485 I jxcore-log: 
,09-15 08:36:21.406  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:21.406  5439  5485 I jxcore-log: 
,09-15 08:36:21.406  5439  5485 I jxcore-log: websocket error
09-15 08:36:21.406  5439  5485 I jxcore-log: 
09-15 08:36:21.406  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:21.406  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:21.406  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:21.406  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:21.406  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:21.406  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:21.406  5439  5485 I jxcore-log: 
,09-15 08:36:24.040  5768  5768 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:36:24.040  5768  5768 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:36:26.430  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:26.430  5439  5485 I jxcore-log: 
,09-15 08:36:26.431  5439  5485 I jxcore-log: websocket error
09-15 08:36:26.431  5439  5485 I jxcore-log: 
09-15 08:36:26.431  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:26.431  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:26.431  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:26.431  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:26.431  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:26.431  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:26.431  5439  5485 I jxcore-log: 
,09-15 08:36:31.460  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:31.460  5439  5485 I jxcore-log: 
09-15 08:36:31.461  5439  5485 I jxcore-log: websocket error
09-15 08:36:31.461  5439  5485 I jxcore-log: 
,09-15 08:36:31.461  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:31.461  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:31.461  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:31.461  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:31.461  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:31.461  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:31.461  5439  5485 I jxcore-log: 
,09-15 08:36:34.041  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:35.042  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:36.044  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:36.489  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:36.489  5439  5485 I jxcore-log: 
,09-15 08:36:36.489  5439  5485 I jxcore-log: websocket error
09-15 08:36:36.489  5439  5485 I jxcore-log: 
09-15 08:36:36.489  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:36.489  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:36.489  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:36.489  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:36.489  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:36.489  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:36.489  5439  5485 I jxcore-log: 
,09-15 08:36:37.045  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:38.046  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:39.046  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:36:41.516  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:41.516  5439  5485 I jxcore-log: 
,09-15 08:36:41.517  5439  5485 I jxcore-log: websocket error
09-15 08:36:41.517  5439  5485 I jxcore-log: 
,09-15 08:36:41.517  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:41.517  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:41.517  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:41.517  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:41.517  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:41.517  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:41.517  5439  5485 I jxcore-log: 
,09-15 08:36:44.048  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:45.049  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:46.050  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:46.549  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:46.549  5439  5485 I jxcore-log: 
09-15 08:36:46.550  5439  5485 I jxcore-log: websocket error
09-15 08:36:46.550  5439  5485 I jxcore-log: 
09-15 08:36:46.550  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:46.550  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:46.550  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:46.550  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:46.550  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:46.550  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:46.550  5439  5485 I jxcore-log: 
,09-15 08:36:47.051  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:48.053  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:36:49.053  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:36:51.575  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:51.575  5439  5485 I jxcore-log: 
,09-15 08:36:51.575  5439  5485 I jxcore-log: websocket error
09-15 08:36:51.575  5439  5485 I jxcore-log: 
09-15 08:36:51.576  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:51.576  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:51.576  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:51.576  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:51.576  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:51.576  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:51.576  5439  5485 I jxcore-log: 
,09-15 08:36:56.602  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:36:56.602  5439  5485 I jxcore-log: 
,09-15 08:36:56.602  5439  5485 I jxcore-log: websocket error
09-15 08:36:56.602  5439  5485 I jxcore-log: 
,09-15 08:36:56.603  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:36:56.603  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:36:56.603  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:36:56.603  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:56.603  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:36:56.603  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:36:56.603  5439  5485 I jxcore-log: 
,09-15 08:36:59.055  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:00.056  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:01.058  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:01.628  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:01.628  5439  5485 I jxcore-log: 
09-15 08:37:01.629  5439  5485 I jxcore-log: websocket error
09-15 08:37:01.629  5439  5485 I jxcore-log: 
09-15 08:37:01.629  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:01.629  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:01.629  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:01.629  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:01.629  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:01.629  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:01.629  5439  5485 I jxcore-log: 
,09-15 08:37:02.059  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:03.061  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:04.061  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:37:06.656  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:06.656  5439  5485 I jxcore-log: 
,09-15 08:37:06.657  5439  5485 I jxcore-log: websocket error
09-15 08:37:06.657  5439  5485 I jxcore-log: 
09-15 08:37:06.657  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:06.657  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:06.657  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:06.657  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:06.657  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:06.657  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:06.657  5439  5485 I jxcore-log: 
,09-15 08:37:11.685  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:11.685  5439  5485 I jxcore-log: 
,09-15 08:37:11.686  5439  5485 I jxcore-log: websocket error
09-15 08:37:11.686  5439  5485 I jxcore-log: 
09-15 08:37:11.686  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:11.686  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:11.686  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:11.686  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:11.686  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:11.686  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:11.686  5439  5485 I jxcore-log: 
,09-15 08:37:16.711  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:16.711  5439  5485 I jxcore-log: 
09-15 08:37:16.711  5439  5485 I jxcore-log: websocket error
09-15 08:37:16.711  5439  5485 I jxcore-log: 
09-15 08:37:16.711  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:16.711  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:16.711  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:16.711  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:16.711  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:16.711  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:16.711  5439  5485 I jxcore-log: 
,09-15 08:37:19.062  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:20.063  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:21.064  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:21.737  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:21.737  5439  5485 I jxcore-log: 
,09-15 08:37:21.737  5439  5485 I jxcore-log: websocket error
09-15 08:37:21.737  5439  5485 I jxcore-log: 
09-15 08:37:21.738  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:21.738  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:21.738  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:21.738  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:21.738  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:21.738  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:21.738  5439  5485 I jxcore-log: 
,09-15 08:37:22.066  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:23.067  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:24.068  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:37:26.767  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:26.767  5439  5485 I jxcore-log: 
,09-15 08:37:26.767  5439  5485 I jxcore-log: websocket error
09-15 08:37:26.767  5439  5485 I jxcore-log: 
09-15 08:37:26.768  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:26.768  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:26.768  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:26.768  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:26.768  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:26.768  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:26.768  5439  5485 I jxcore-log: 
,09-15 08:37:31.793  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:31.793  5439  5485 I jxcore-log: 
09-15 08:37:31.794  5439  5485 I jxcore-log: websocket error
09-15 08:37:31.794  5439  5485 I jxcore-log: 
09-15 08:37:31.794  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:31.794  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:31.794  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:31.794  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:31.794  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:31.794  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:31.794  5439  5485 I jxcore-log: 
,09-15 08:37:36.821  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:36.821  5439  5485 I jxcore-log: 
09-15 08:37:36.821  5439  5485 I jxcore-log: websocket error
09-15 08:37:36.821  5439  5485 I jxcore-log: 
,09-15 08:37:36.821  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:36.821  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:36.821  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:36.821  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:36.821  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:36.821  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:36.821  5439  5485 I jxcore-log: 
,09-15 08:37:41.849  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:41.849  5439  5485 I jxcore-log: 
,09-15 08:37:41.850  5439  5485 I jxcore-log: websocket error
09-15 08:37:41.850  5439  5485 I jxcore-log: 
09-15 08:37:41.850  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:41.850  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:41.850  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:41.850  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:41.850  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:41.850  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:41.850  5439  5485 I jxcore-log: 
,09-15 08:37:44.069  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:45.071  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:46.072  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:46.875  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:46.875  5439  5485 I jxcore-log: 
,09-15 08:37:46.875  5439  5485 I jxcore-log: websocket error
09-15 08:37:46.875  5439  5485 I jxcore-log: 
09-15 08:37:46.875  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:46.875  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:46.875  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:46.875  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:46.875  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:46.875  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:46.875  5439  5485 I jxcore-log: 
,09-15 08:37:47.073  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:48.075  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:37:49.075  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:37:51.904  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:51.904  5439  5485 I jxcore-log: 
09-15 08:37:51.904  5439  5485 I jxcore-log: websocket error
09-15 08:37:51.904  5439  5485 I jxcore-log: 
09-15 08:37:51.905  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:51.905  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:51.905  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:51.905  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:51.905  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:51.905  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:51.905  5439  5485 I jxcore-log: 
,09-15 08:37:56.929  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:37:56.929  5439  5485 I jxcore-log: 
09-15 08:37:56.929  5439  5485 I jxcore-log: websocket error
09-15 08:37:56.929  5439  5485 I jxcore-log: 
,09-15 08:37:56.930  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:37:56.930  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:37:56.930  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:37:56.930  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:56.930  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:37:56.930  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:37:56.930  5439  5485 I jxcore-log: 
,09-15 08:38:01.955  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:01.955  5439  5485 I jxcore-log: 
,09-15 08:38:01.956  5439  5485 I jxcore-log: websocket error
09-15 08:38:01.956  5439  5485 I jxcore-log: 
09-15 08:38:01.956  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:01.956  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:01.956  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:01.956  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:01.956  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:01.956  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:01.956  5439  5485 I jxcore-log: 
,09-15 08:38:06.982  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:06.982  5439  5485 I jxcore-log: 
,09-15 08:38:06.982  5439  5485 I jxcore-log: websocket error
09-15 08:38:06.982  5439  5485 I jxcore-log: 
09-15 08:38:06.982  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:06.982  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:06.982  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:06.982  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:06.982  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:06.982  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:06.982  5439  5485 I jxcore-log: 
,09-15 08:38:12.007  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:12.007  5439  5485 I jxcore-log: 
,09-15 08:38:12.008  5439  5485 I jxcore-log: websocket error
09-15 08:38:12.008  5439  5485 I jxcore-log: 
09-15 08:38:12.008  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:12.008  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:12.008  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:12.008  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:12.008  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:12.008  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:12.008  5439  5485 I jxcore-log: 
,09-15 08:38:14.076  5768  5768 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-15 08:38:14.076  5768  5768 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:38:17.035  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:17.035  5439  5485 I jxcore-log: 
,09-15 08:38:17.035  5439  5485 I jxcore-log: websocket error
09-15 08:38:17.035  5439  5485 I jxcore-log: 
,09-15 08:38:17.036  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:17.036  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:17.036  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:17.036  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:17.036  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:17.036  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:17.036  5439  5485 I jxcore-log: 
,09-15 08:38:22.061  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:22.061  5439  5485 I jxcore-log: 
09-15 08:38:22.061  5439  5485 I jxcore-log: websocket error
09-15 08:38:22.061  5439  5485 I jxcore-log: 
09-15 08:38:22.062  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:22.062  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:22.062  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:22.062  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:22.062  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:22.062  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:22.062  5439  5485 I jxcore-log: 
,09-15 08:38:27.088  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:27.088  5439  5485 I jxcore-log: 
,09-15 08:38:27.089  5439  5485 I jxcore-log: websocket error
09-15 08:38:27.089  5439  5485 I jxcore-log: 
09-15 08:38:27.089  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:27.089  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:27.089  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:27.089  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:27.089  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:27.089  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:27.089  5439  5485 I jxcore-log: 
,09-15 08:38:29.077  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:30.078  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:31.079  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:32.080  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:32.118  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:32.118  5439  5485 I jxcore-log: 
,09-15 08:38:32.118  5439  5485 I jxcore-log: websocket error
09-15 08:38:32.118  5439  5485 I jxcore-log: 
09-15 08:38:32.118  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:32.118  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:32.118  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:32.118  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:32.118  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:32.118  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:32.118  5439  5485 I jxcore-log: 
,09-15 08:38:33.081  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:34.082  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:38:37.142  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:37.142  5439  5485 I jxcore-log: 
,09-15 08:38:37.143  5439  5485 I jxcore-log: websocket error
09-15 08:38:37.143  5439  5485 I jxcore-log: 
,09-15 08:38:37.145  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:37.145  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:37.145  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:37.145  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:37.145  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:37.145  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:37.145  5439  5485 I jxcore-log: 
,09-15 08:38:39.084  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:40.085  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:41.087  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:42.088  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:42.170  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:42.170  5439  5485 I jxcore-log: 
09-15 08:38:42.171  5439  5485 I jxcore-log: websocket error
09-15 08:38:42.171  5439  5485 I jxcore-log: 
09-15 08:38:42.171  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:42.171  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:42.171  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:42.171  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:42.171  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:42.171  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:42.171  5439  5485 I jxcore-log: 
,09-15 08:38:43.089  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:44.090  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:38:47.197  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:47.197  5439  5485 I jxcore-log: 
09-15 08:38:47.198  5439  5485 I jxcore-log: websocket error
09-15 08:38:47.198  5439  5485 I jxcore-log: 
09-15 08:38:47.198  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:47.198  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:47.198  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:47.198  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:47.198  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:47.198  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:47.198  5439  5485 I jxcore-log: 
,09-15 08:38:52.223  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:52.223  5439  5485 I jxcore-log: 
09-15 08:38:52.224  5439  5485 I jxcore-log: websocket error
09-15 08:38:52.224  5439  5485 I jxcore-log: 
09-15 08:38:52.224  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:52.224  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:52.224  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:52.224  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:52.224  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:52.224  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:52.224  5439  5485 I jxcore-log: 
,09-15 08:38:54.092  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:55.093  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:56.094  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:57.095  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:57.252  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:38:57.252  5439  5485 I jxcore-log: 
09-15 08:38:57.252  5439  5485 I jxcore-log: websocket error
09-15 08:38:57.252  5439  5485 I jxcore-log: 
09-15 08:38:57.253  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:38:57.253  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:38:57.253  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:38:57.253  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:57.253  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:38:57.253  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:38:57.253  5439  5485 I jxcore-log: 
,09-15 08:38:58.096  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:38:59.097  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:39:02.277  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:02.277  5439  5485 I jxcore-log: 
,09-15 08:39:02.277  5439  5485 I jxcore-log: websocket error
09-15 08:39:02.277  5439  5485 I jxcore-log: 
09-15 08:39:02.278  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:02.278  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:02.278  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:02.278  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:02.278  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:02.278  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:02.278  5439  5485 I jxcore-log: 
,09-15 08:39:07.304  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:07.304  5439  5485 I jxcore-log: 
09-15 08:39:07.304  5439  5485 I jxcore-log: websocket error
09-15 08:39:07.304  5439  5485 I jxcore-log: 
,09-15 08:39:07.305  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:07.305  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:07.305  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:07.305  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:07.305  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:07.305  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:07.305  5439  5485 I jxcore-log: 
,09-15 08:39:12.330  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:12.330  5439  5485 I jxcore-log: 
,09-15 08:39:12.331  5439  5485 I jxcore-log: websocket error
09-15 08:39:12.331  5439  5485 I jxcore-log: 
,09-15 08:39:12.331  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:12.331  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:12.331  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:12.331  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:12.331  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:12.331  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:12.331  5439  5485 I jxcore-log: 
,09-15 08:39:14.098  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:15.099  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:16.100  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:17.101  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:17.357  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:17.357  5439  5485 I jxcore-log: 
09-15 08:39:17.357  5439  5485 I jxcore-log: websocket error
09-15 08:39:17.357  5439  5485 I jxcore-log: 
09-15 08:39:17.358  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:17.358  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:17.358  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:17.358  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:17.358  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:17.358  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:17.358  5439  5485 I jxcore-log: 
,09-15 08:39:18.103  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:19.103  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:39:22.384  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:22.384  5439  5485 I jxcore-log: 
,09-15 08:39:22.384  5439  5485 I jxcore-log: websocket error
09-15 08:39:22.384  5439  5485 I jxcore-log: 
09-15 08:39:22.384  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:22.384  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:22.384  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:22.384  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:22.384  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:22.384  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:22.384  5439  5485 I jxcore-log: 
,09-15 08:39:27.410  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:27.410  5439  5485 I jxcore-log: 
,09-15 08:39:27.410  5439  5485 I jxcore-log: websocket error
09-15 08:39:27.410  5439  5485 I jxcore-log: 
09-15 08:39:27.411  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:27.411  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:27.411  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:27.411  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:27.411  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:27.411  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:27.411  5439  5485 I jxcore-log: 
,09-15 08:39:32.434  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:32.434  5439  5485 I jxcore-log: 
09-15 08:39:32.435  5439  5485 I jxcore-log: websocket error
09-15 08:39:32.435  5439  5485 I jxcore-log: 
09-15 08:39:32.435  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:32.435  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:32.435  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:32.435  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:32.435  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:32.435  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:32.435  5439  5485 I jxcore-log: 
,09-15 08:39:37.462  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:37.462  5439  5485 I jxcore-log: 
09-15 08:39:37.463  5439  5485 I jxcore-log: websocket error
09-15 08:39:37.463  5439  5485 I jxcore-log: 
09-15 08:39:37.463  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:37.463  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:37.463  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:37.463  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:37.463  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:37.463  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:37.463  5439  5485 I jxcore-log: 
,09-15 08:39:39.105  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:40.106  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:41.107  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:42.109  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:42.491  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:42.491  5439  5485 I jxcore-log: 
,09-15 08:39:42.491  5439  5485 I jxcore-log: websocket error
09-15 08:39:42.491  5439  5485 I jxcore-log: 
09-15 08:39:42.491  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:42.491  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:42.491  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:42.491  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:42.491  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:42.491  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:42.491  5439  5485 I jxcore-log: 
,09-15 08:39:43.110  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:39:44.111  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:39:47.518  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:47.518  5439  5485 I jxcore-log: 
09-15 08:39:47.518  5439  5485 I jxcore-log: websocket error
09-15 08:39:47.518  5439  5485 I jxcore-log: 
09-15 08:39:47.518  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:47.518  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:47.518  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:47.518  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:47.518  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:47.518  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:47.518  5439  5485 I jxcore-log: 
,09-15 08:39:52.544  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:52.544  5439  5485 I jxcore-log: 
09-15 08:39:52.545  5439  5485 I jxcore-log: websocket error
09-15 08:39:52.545  5439  5485 I jxcore-log: 
09-15 08:39:52.545  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:52.545  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:52.545  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:52.545  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:52.545  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:52.545  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:52.545  5439  5485 I jxcore-log: 
,09-15 08:39:57.570  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:39:57.570  5439  5485 I jxcore-log: 
09-15 08:39:57.571  5439  5485 I jxcore-log: websocket error
09-15 08:39:57.571  5439  5485 I jxcore-log: 
09-15 08:39:57.571  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:39:57.571  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:39:57.571  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:39:57.571  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:57.571  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:39:57.571  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:39:57.571  5439  5485 I jxcore-log: 
,09-15 08:40:02.597  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:02.597  5439  5485 I jxcore-log: 
,09-15 08:40:02.597  5439  5485 I jxcore-log: websocket error
09-15 08:40:02.597  5439  5485 I jxcore-log: 
09-15 08:40:02.598  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:02.598  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:02.598  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:02.598  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:02.598  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:02.598  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:02.598  5439  5485 I jxcore-log: 
,09-15 08:40:07.623  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:07.623  5439  5485 I jxcore-log: 
09-15 08:40:07.624  5439  5485 I jxcore-log: websocket error
09-15 08:40:07.624  5439  5485 I jxcore-log: 
,09-15 08:40:07.624  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:07.624  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:07.624  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:07.624  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:07.624  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:07.624  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:07.624  5439  5485 I jxcore-log: 
,09-15 08:40:09.111  5768  5768 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:40:09.111  5768  5768 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:40:12.654  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:12.654  5439  5485 I jxcore-log: 
09-15 08:40:12.654  5439  5485 I jxcore-log: websocket error
09-15 08:40:12.654  5439  5485 I jxcore-log: 
09-15 08:40:12.655  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:12.655  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:12.655  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:12.655  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:12.655  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:12.655  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:12.655  5439  5485 I jxcore-log: 
,09-15 08:40:17.678  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:17.678  5439  5485 I jxcore-log: 
09-15 08:40:17.679  5439  5485 I jxcore-log: websocket error
09-15 08:40:17.679  5439  5485 I jxcore-log: 
09-15 08:40:17.679  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:17.679  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:17.679  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:17.679  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:17.679  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:17.679  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:17.679  5439  5485 I jxcore-log: 
,09-15 08:40:22.706  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:22.706  5439  5485 I jxcore-log: 
09-15 08:40:22.707  5439  5485 I jxcore-log: websocket error
09-15 08:40:22.707  5439  5485 I jxcore-log: 
09-15 08:40:22.707  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:22.707  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:22.707  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:22.707  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:22.707  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:22.707  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:22.707  5439  5485 I jxcore-log: 
,09-15 08:40:27.732  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:27.732  5439  5485 I jxcore-log: 
,09-15 08:40:27.732  5439  5485 I jxcore-log: websocket error
09-15 08:40:27.732  5439  5485 I jxcore-log: 
09-15 08:40:27.733  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:27.733  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:27.733  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:27.733  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:27.733  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:27.733  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:27.733  5439  5485 I jxcore-log: 
,09-15 08:40:29.112  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:30.114  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:31.115  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:32.116  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:32.760  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:32.760  5439  5485 I jxcore-log: 
,09-15 08:40:32.760  5439  5485 I jxcore-log: websocket error
09-15 08:40:32.760  5439  5485 I jxcore-log: 
09-15 08:40:32.761  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:32.761  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:32.761  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:32.761  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:32.761  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:32.761  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:32.761  5439  5485 I jxcore-log: 
,09-15 08:40:33.117  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:34.118  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-15 08:40:37.787  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:37.787  5439  5485 I jxcore-log: 
,09-15 08:40:37.788  5439  5485 I jxcore-log: websocket error
09-15 08:40:37.788  5439  5485 I jxcore-log: 
09-15 08:40:37.788  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:37.788  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:37.788  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:37.788  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:37.788  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:37.788  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:37.788  5439  5485 I jxcore-log: 
,09-15 08:40:39.119  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:40.121  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:41.122  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:42.123  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:42.816  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:42.816  5439  5485 I jxcore-log: 
,09-15 08:40:42.817  5439  5485 I jxcore-log: websocket error
09-15 08:40:42.817  5439  5485 I jxcore-log: 
09-15 08:40:42.817  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:42.817  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:42.817  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:42.817  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:42.817  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:42.817  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:42.817  5439  5485 I jxcore-log: 
,09-15 08:40:43.125  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:44.126  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-15 08:40:47.850  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:47.850  5439  5485 I jxcore-log: 
,09-15 08:40:47.851  5439  5485 I jxcore-log: websocket error
09-15 08:40:47.851  5439  5485 I jxcore-log: 
09-15 08:40:47.851  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:47.851  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:47.851  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:47.851  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:47.851  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:47.851  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:47.851  5439  5485 I jxcore-log: 
,09-15 08:40:52.875  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:52.875  5439  5485 I jxcore-log: 
,09-15 08:40:52.876  5439  5485 I jxcore-log: websocket error
09-15 08:40:52.876  5439  5485 I jxcore-log: 
,09-15 08:40:52.876  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:52.876  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:52.876  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:52.876  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:52.876  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:52.876  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:52.876  5439  5485 I jxcore-log: 
,09-15 08:40:54.127  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:55.128  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:56.129  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:57.130  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:57.906  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:40:57.906  5439  5485 I jxcore-log: 
09-15 08:40:57.907  5439  5485 I jxcore-log: websocket error
09-15 08:40:57.907  5439  5485 I jxcore-log: 
09-15 08:40:57.907  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:40:57.907  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:40:57.907  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:40:57.907  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:57.907  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:40:57.907  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:40:57.907  5439  5485 I jxcore-log: 
,09-15 08:40:58.131  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:40:59.132  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-15 08:41:02.932  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:02.932  5439  5485 I jxcore-log: 
,09-15 08:41:02.933  5439  5485 I jxcore-log: websocket error
09-15 08:41:02.933  5439  5485 I jxcore-log: 
,09-15 08:41:02.935  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:02.935  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:02.935  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:02.935  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:02.935  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:02.935  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:02.935  5439  5485 I jxcore-log: 
,09-15 08:41:07.960  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:07.960  5439  5485 I jxcore-log: 
09-15 08:41:07.961  5439  5485 I jxcore-log: websocket error
09-15 08:41:07.961  5439  5485 I jxcore-log: 
09-15 08:41:07.961  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:07.961  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:07.961  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:07.961  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:07.961  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:07.961  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:07.961  5439  5485 I jxcore-log: 
,09-15 08:41:12.987  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:12.987  5439  5485 I jxcore-log: 
09-15 08:41:12.988  5439  5485 I jxcore-log: websocket error
09-15 08:41:12.988  5439  5485 I jxcore-log: 
09-15 08:41:12.988  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:12.988  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:12.988  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:12.988  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:12.988  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:12.988  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:12.988  5439  5485 I jxcore-log: 
,09-15 08:41:14.133  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:15.134  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:16.136  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:17.138  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:18.015  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:18.015  5439  5485 I jxcore-log: 
,09-15 08:41:18.015  5439  5485 I jxcore-log: websocket error
09-15 08:41:18.015  5439  5485 I jxcore-log: 
,09-15 08:41:18.015  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:18.015  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:18.015  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:18.015  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:18.015  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:18.015  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:18.015  5439  5485 I jxcore-log: 
,09-15 08:41:18.138  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:19.139  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-15 08:41:23.043  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:23.043  5439  5485 I jxcore-log: 
09-15 08:41:23.043  5439  5485 I jxcore-log: websocket error
09-15 08:41:23.043  5439  5485 I jxcore-log: 
09-15 08:41:23.044  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:23.044  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:23.044  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:23.044  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:23.044  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:23.044  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:23.044  5439  5485 I jxcore-log: 
,09-15 08:41:28.069  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:28.069  5439  5485 I jxcore-log: 
,09-15 08:41:28.070  5439  5485 I jxcore-log: websocket error
09-15 08:41:28.070  5439  5485 I jxcore-log: 
09-15 08:41:28.070  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:28.070  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:28.070  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:28.070  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:28.070  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:28.070  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:28.070  5439  5485 I jxcore-log: 
,09-15 08:41:33.096  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:33.096  5439  5485 I jxcore-log: 
09-15 08:41:33.097  5439  5485 I jxcore-log: websocket error
09-15 08:41:33.097  5439  5485 I jxcore-log: 
09-15 08:41:33.097  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:33.097  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:33.097  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:33.097  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:33.097  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:33.097  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:33.097  5439  5485 I jxcore-log: 
,09-15 08:41:38.188  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:38.188  5439  5485 I jxcore-log: 
09-15 08:41:38.188  5439  5485 I jxcore-log: websocket error
09-15 08:41:38.188  5439  5485 I jxcore-log: 
09-15 08:41:38.188  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:38.188  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:38.188  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:38.188  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:38.188  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:38.188  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:38.188  5439  5485 I jxcore-log: 
,09-15 08:41:39.141  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:40.142  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:41.144  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:42.145  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:43.147  5768  5768 I ServiceManager: Waiting for service AtCmdFwd...
,09-15 08:41:43.229  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:43.229  5439  5485 I jxcore-log: 
,09-15 08:41:43.229  5439  5485 I jxcore-log: websocket error
09-15 08:41:43.229  5439  5485 I jxcore-log: 
,09-15 08:41:43.230  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:43.230  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:43.230  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:43.230  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:43.230  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:43.230  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:43.230  5439  5485 I jxcore-log: 
,09-15 08:41:44.147  5768  5768 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-15 08:41:48.275  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:48.275  5439  5485 I jxcore-log: 
,09-15 08:41:48.276  5439  5485 I jxcore-log: websocket error
09-15 08:41:48.276  5439  5485 I jxcore-log: 
09-15 08:41:48.276  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:48.276  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:48.276  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:48.276  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:48.276  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:48.276  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:48.276  5439  5485 I jxcore-log: 
,09-15 08:41:53.329  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:53.329  5439  5485 I jxcore-log: 
,09-15 08:41:53.329  5439  5485 I jxcore-log: websocket error
09-15 08:41:53.329  5439  5485 I jxcore-log: 
09-15 08:41:53.329  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:53.329  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:53.329  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:53.329  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:53.329  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:53.329  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:53.329  5439  5485 I jxcore-log: 
,09-15 08:41:58.356  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:41:58.356  5439  5485 I jxcore-log: 
09-15 08:41:58.357  5439  5485 I jxcore-log: websocket error
09-15 08:41:58.357  5439  5485 I jxcore-log: 
09-15 08:41:58.357  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:41:58.357  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:41:58.357  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:41:58.357  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:58.357  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:41:58.357  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:41:58.357  5439  5485 I jxcore-log: 
,09-15 08:42:03.381  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:42:03.381  5439  5485 I jxcore-log: 
,09-15 08:42:03.382  5439  5485 I jxcore-log: websocket error
09-15 08:42:03.382  5439  5485 I jxcore-log: 
,09-15 08:42:03.382  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:42:03.382  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:42:03.382  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:42:03.382  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:03.382  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:42:03.382  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:03.382  5439  5485 I jxcore-log: 
,09-15 08:42:08.407  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:42:08.407  5439  5485 I jxcore-log: 
,09-15 08:42:08.407  5439  5485 I jxcore-log: websocket error
09-15 08:42:08.407  5439  5485 I jxcore-log: 
09-15 08:42:08.407  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:42:08.407  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:42:08.407  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:42:08.407  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:08.407  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:42:08.407  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:08.407  5439  5485 I jxcore-log: 
,09-15 08:42:09.148  5768  5768 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-15 08:42:09.149  5768  5768 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-15 08:42:13.433  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:42:13.433  5439  5485 I jxcore-log: 
,09-15 08:42:13.433  5439  5485 I jxcore-log: websocket error
09-15 08:42:13.433  5439  5485 I jxcore-log: 
,09-15 08:42:13.434  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:42:13.434  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:42:13.434  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:42:13.434  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:13.434  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:42:13.434  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:13.434  5439  5485 I jxcore-log: 
,09-15 08:42:18.459  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:42:18.459  5439  5485 I jxcore-log: 
,09-15 08:42:18.459  5439  5485 I jxcore-log: websocket error
09-15 08:42:18.459  5439  5485 I jxcore-log: 
,09-15 08:42:18.460  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:42:18.460  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:42:18.460  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:42:18.460  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:18.460  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:42:18.460  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:18.460  5439  5485 I jxcore-log: 
,09-15 08:42:23.486  5439  5485 I jxcore-log: ThaliTape :: Error when connecting to the test server Error: websocket error
09-15 08:42:23.486  5439  5485 I jxcore-log: 
,09-15 08:42:23.487  5439  5485 I jxcore-log: websocket error
09-15 08:42:23.487  5439  5485 I jxcore-log: 
09-15 08:42:23.487  5439  5485 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:66:13
09-15 08:42:23.487  5439  5485 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:115:5
09-15 08:42:23.487  5439  5485 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:423:5
09-15 08:42:23.487  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:23.487  5439  5485 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:666:5
09-15 08:42:23.487  5439  5485 I jxcore-log: emit@events.js:82:1
09-15 08:42:23.487  5439  5485 I jxcore-log: 
,TIME-OUT KILL (timeout was 1400000ms),09-15 08:42:28.337  5779  5779 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-15 08:42:28.341  5779  5779 D AndroidRuntime: CheckJNI is OFF
09-15 08:42:28.365  5779  5779 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-15 08:42:28.398  5779  5779 I Radio-JNI: register_android_hardware_Radio DONE
09-15 08:42:28.414  5779  5779 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-15 08:42:28.427   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
09-15 08:42:28.428   929   942 I ActivityManager: Killing 5439:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
09-15 08:42:28.475   929  2948 W InputDispatcher: channel '5172632 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-15 08:42:28.475   929  2948 E InputDispatcher: channel '5172632 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
09-15 08:42:28.479   929  2958 D WifiService: Client connection lost with reason: 4
09-15 08:42:28.480   929   940 I WindowState: WIN DEATH: Window{5172632 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-15 08:42:28.480   929  3438 D GraphicsStats: Buffer count: 2
09-15 08:42:28.480   929   940 W InputDispatcher: Attempted to unregister already unregistered input channel '5172632 com.test.thalitest/com.test.thalitest.MainActivity (server)'
09-15 08:42:28.569   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-15 08:42:28.569   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-15 08:42:28.570   929   952 I art     : Starting a blocking GC Explicit
09-15 08:42:28.571   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-15 08:42:28.571   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-15 08:42:28.571   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:42:28.571   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:42:28.571   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 08:42:28.571   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 08:42:28.571   929   942 I ActivityManager:   Force finishing activity ActivityRecord{da9d6ff u0 com.test.thalitest/.MainActivity t2}
09-15 08:42:28.584   929  3779 W ActivityManager: Spurious death for ProcessRecord{700a9bf 0:com.test.thalitest/u0a77}, curProc for 5439: null
09-15 08:42:28.661   929   952 I art     : Explicit concurrent mark sweep GC freed 31566(1908KB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 2.011ms total 90.516ms
09-15 08:42:28.681   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-15 08:42:28.684  5779  5779 I art     : System.exit called, status: 0
09-15 08:42:28.684  5779  5779 I AndroidRuntime: VM exiting with result code 0.
09-15 08:42:28.696   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
09-15 08:42:28.703   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-15 08:42:28.707  5677  5677 D BluetoothMapAppObserver: onReceive
09-15 08:42:28.707  5677  5677 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-15 08:42:28.711  3424  3424 I Keyboard.Facilitator: resetDictionaries() : en_US
09-15 08:42:28.718   929  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-15 08:42:28.719  3619  3971 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-15 08:42:28.755  3424  5794 I Keyboard.Facilitator.DecoderInitializer: run()
09-15 08:42:28.756  3515  3515 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-15 08:42:28.759  3412  5795 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-15 08:42:28.772    28    28 W kworker/2:1: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-15 08:42:28.781  3601  3601 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-15 08:42:28.781  3601  3601 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-15 08:42:28.778    28    28 W kworker/2:1: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-15 08:42:28.795    28    28 W kworker/2:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-15 08:42:28.804   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-15 08:42:28.813  3923  5801 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-15 08:42:28.813  3923  5801 D AccountUtils: Clearing selected account for com.test.thalitest
09-15 08:42:28.816   929   941 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-15 08:42:28.816  3559  3671 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-15 08:42:28.817   929   941 E PackageManager: Failed to write settings, restoring backup
09-15 08:42:28.817   929   941 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-15 08:42:28.817   929   941 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-15 08:42:28.817   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-15 08:42:28.817   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-15 08:42:28.817   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-15 08:42:28.817   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-15 08:42:28.817   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:42:28.817   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 08:42:28.822   929   942 E DropBoxManagerService: Can't write: system_server_wtf
09-15 08:42:28.822   929   942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-15 08:42:28.822   929   942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 08:42:28.822   929   942 E DropBoxManagerService: 	... 13 more
09-15 08:42:28.830   929   939 I ActivityManager: Start proc 5804:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-15 08:42:28.831  3559  3671 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-15 08:42:28.831  3559  3671 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3559
09-15 08:42:28.831  3559  3671 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-15 08:42:28.831  3559  3671 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: Can't write: system_app_crash
09-15 08:42:28.834   929  5810 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-15 08:42:28.834   929  5810 E DropBoxManagerService: 	... 5 more
09-15 08:42:28.835   929   940 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-15 08:42:28.838  3559  3671 I Process : Sending signal. PID: 3559 SIG: 9
09-15 08:42:28.856  3412  3442 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj09A60C912) - 
09-15 08:42:28.856  3601  3601 I ConfigService: onCreate
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-15 08:42:28.859  3601  5817 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-15 08:42:28.859  3601  5817 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-15 08:42:28.861  3601  5817 W SQLiteOpenHelper: Opened config.db in read-only mode
09-15 08:42:28.868  3923  5801 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest

```
