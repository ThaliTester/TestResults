#### Test 8774869133360fe_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-14 06:47:28.306   537   537 I ServiceManager: Waiting for service AtCmdFwd...
10-14 06:47:29.308   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-14 06:47:30.582  5580  5580 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-14 06:47:30.588  5580  5580 D AndroidRuntime: CheckJNI is OFF
10-14 06:47:30.614  5580  5580 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-14 06:47:30.647  5580  5580 I Radio-JNI: register_android_hardware_Radio DONE
10-14 06:47:30.662  5580  5580 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-14 06:47:30.678   928  3834 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-14 06:47:30.729   928  3834 I ActivityManager: Start proc 5589:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-14 06:47:30.747  5580  5580 D AndroidRuntime: Shutting down VM
10-14 06:47:30.882   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:47:31.086   928  3844 I WindowManager: Screenshot max retries 4 of Token{e14ce66 ActivityRecord{fdab6c1 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{11e7cf9 u0 Starting com.test.thalitest} drawState=2
,10-14 06:47:31.170  5589  5589 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-14 06:47:31.196  5589  5589 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-14 06:47:31.218  5589  5589 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 6536-6554)
10-14 06:47:31.218  5589  5589 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-14 06:47:31.234  5589  5589 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3998c40}
,10-14 06:47:31.235  5589  5589 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-14 06:47:31.235  5589  5589 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-14 06:47:31.238  5589  5589 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-14 06:47:31.239  5589  5589 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-14 06:47:31.269  5589  5589 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-14 06:47:31.277  5589  5589 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-14 06:47:31.278  5589  5589 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 06:47:31.278  5589  5589 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-14 06:47:31.278  5589  5589 I Adreno  : Build Date                       : 12/06/15
10-14 06:47:31.278  5589  5589 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-14 06:47:31.278  5589  5589 I Adreno  : Local Branch                     : mybranch17112971
10-14 06:47:31.278  5589  5589 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-14 06:47:31.278  5589  5589 I Adreno  : Remote Branch                    : NONE
10-14 06:47:31.278  5589  5589 I Adreno  : Reconstruct Branch               : NOTHING
,10-14 06:47:31.327   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e22c084:true
,10-14 06:47:31.352   403   403 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32204]" dev="sockfs" ino=32204 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 06:47:31.352   403   403 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32204]" dev="sockfs" ino=32204 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 06:47:31.365  5589  5589 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-14 06:47:31.374  5589  5589 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-14 06:47:31.399   403   403 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34045]" dev="sockfs" ino=34045 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-14 06:47:31.399   403   403 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34045]" dev="sockfs" ino=34045 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 06:47:31.401  5589  5626 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-14 06:47:31.402   938   938 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[21078]" dev="sockfs" ino=21078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-14 06:47:31.402   938   938 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[21078]" dev="sockfs" ino=21078 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-14 06:47:31.407  5589  5613 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-14 06:47:31.427  5589  5626 I OpenGLRenderer: Initialized EGL, version 1.4
,10-14 06:47:31.501   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +413ms (total +805ms)
,10-14 06:47:31.542  5589  5589 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5589
,10-14 06:47:31.638  5589  5589 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-14 06:47:31.804  5589  5628 D jxcore_app_log: JniHelper::setJavaVM(0xf53fc000), pthread_self() = -580388560
,10-14 06:47:31.808  5589  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-14 06:47:31.808  5589  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-14 06:47:31.808  5589  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-14 06:47:31.808  5589  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-14 06:47:31.808  5589  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-14 06:47:31.808  5589  5628 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac8d271 added. We now have 1 listener(s)
,10-14 06:47:31.810  5589  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-14 06:47:31.810  5589  5628 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:47:31.811  5589  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:47:31.811  5589  5628 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-14 06:47:31.813  5589  5628 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac724ad added. We now have 1 listener(s)
10-14 06:47:31.813  5589  5628 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:47:31.818  5589  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 06:47:31.818   928  2961 D WifiService: New client listening to asynchronous messages
10-14 06:47:31.818  5589  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-14 06:47:31.818  5589  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-14 06:47:31.818  5589  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-14 06:47:31.818  5589  5628 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-14 06:47:31.819  5589  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:47:31.820  5589  5628 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-14 06:47:31.826  5589  5628 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:47:31.827  5589  5628 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:47:31.827  5589  5628 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,10-14 06:47:31.827  5589  5628 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 06:47:31.827  5589  5628 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-14 06:47:31.831  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:31.836  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:47:31.929  5589  5589 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-14 06:47:32.115  5589  5598 I art     : Background sticky concurrent mark sweep GC freed 85470(8MB) AllocSpace objects, 17(1308KB) LOS objects, 20% free, 26MB/32MB, paused 1.903ms total 104.073ms
,10-14 06:47:32.554  5589  5635 W jxcore-log: Initializing JXcore engine
10-14 06:47:32.554  5589  5635 W jxcore-log: JXcore engine is ready
,10-14 06:47:32.579  5635  5635 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11942 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-14 06:47:32.579  5635  5635 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16412]" dev="sockfs" ino=16412 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-14 06:47:32.579  5635  5635 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-14 06:47:32.579  5635  5635 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[34021]" dev="sockfs" ino=34021 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-14 06:47:32.587  5589  5635 W jxcore-log: Starting JXcore engine
,10-14 06:47:32.637  5589  5635 W jxcore-log: Platform android
10-14 06:47:32.637  5589  5635 W jxcore-log: 
10-14 06:47:32.638  5589  5635 W jxcore-log: Process ARCH arm
10-14 06:47:32.638  5589  5635 W jxcore-log: 
,10-14 06:47:32.816  5589  5635 I jxcore-log: JXcore Cordova bridge is ready!
10-14 06:47:32.816  5589  5635 I jxcore-log: 
,10-14 06:47:32.816  5589  5635 W jxcore-log: JXcore engine is started
,10-14 06:47:32.829  5589  5628 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-14 06:47:32.837  5589  5589 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-14 06:47:34.109   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:47:34.309   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:35.310   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:36.311   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:37.312   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:38.313   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:39.314   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-14 06:47:42.668  5589  5635 I jxcore-log: 2016-10-14 10:47:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-14 06:47:42.668  5589  5635 I jxcore-log: 
,10-14 06:47:42.670  5589  5635 I jxcore-log: 2016-10-14 10:47:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-14 06:47:42.670  5589  5635 I jxcore-log: 
,10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:47:42.674  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 06:47:42.676  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:47:42.677  5589  5635 I jxcore-log: 2016-10-14 10:47:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-14 06:47:42.677  5589  5635 I jxcore-log: 
,10-14 06:47:42.679  5589  5635 I jxcore-log: 2016-10-14 10:47:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-14 06:47:42.679  5589  5635 I jxcore-log: 
,10-14 06:47:42.927  5589  5635 I jxcore-log: 2016-10-14 10:47:42 - DEBUG UnitTest_app: 'Running unit tests'
10-14 06:47:42.927  5589  5635 I jxcore-log: 
,10-14 06:47:42.928  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:47:42.928  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41b78a7 added. We now have 2 listener(s)
10-14 06:47:42.929  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:47:42.929  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-14 06:47:42.929  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:47:42.929  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 06:47:42.929  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@69f7154 added. We now have 2 listener(s)
10-14 06:47:42.929  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:47:42.930  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 06:47:42.932  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:47:42.935  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 06:47:42.936  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:42.936  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:47:42.936  5589  5635 D executeNativeTests: Running unit tests
,10-14 06:47:42.944  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:47:42.949  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:47:42.975  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-14 06:47:42.975  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 added. We now have 3 listener(s)
10-14 06:47:42.976  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:47:42.976  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:47:42.976  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:47:42.976  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:47:42.976  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 added. We now have 3 listener(s)
10-14 06:47:42.976  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:47:42.977  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 06:47:42.978  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:47:42.980  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:47:42.981  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:42.981  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 06:47:42.982  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 06:47:42.982  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 06:47:42.982  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 06:47:42.983  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 06:47:42.983  5589  5635 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-14 06:47:42.983  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 06:47:42.983  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 06:47:42.983  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 06:47:42.983  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 06:47:42.983  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 06:47:42.984  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:47:42.984  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:47:42.984  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:47:42.985  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:47:42.985  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:42.985  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:47:42.985  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:47:42.985  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:47:42.985  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 removed from the list
10-14 06:47:42.985  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:42.985  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 removed from the list
10-14 06:47:42.986  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:42.986  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:47:42.986  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:42.987  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:47:42.987  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:42.988  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:47:42.989  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:47:42.989  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:42.989  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:47:42.991  5589  5635 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-14 06:47:42.991  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:47:42.991  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:47:42.991  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:47:42.991  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:47:42.991  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:42.991  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:42.991  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:47:42.991  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
,10-14 06:47:42.991  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:42.991  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:47:42.994  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:47:42.995  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:47:42.995  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:42.995  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:42.995  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:42.995  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:47:42.995  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:47:42.995  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:47:42.995  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:42.995  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-14 06:47:42.998  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-14 06:47:42.999  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:47:42.999  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:47:42.999  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:47:,42.999  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:47:42.999  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:42.999  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:42.999  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:47:42.999  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:47:42.999  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:42.999  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:47:42.999  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:47:42.999  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:42.999  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:42.999  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:43.000  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:43.000  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:47:43.000  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:47:43.000  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:43.000  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:47:43.001  5589  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-14 06:47:43.001  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:47:43.004  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:47:43.004  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:43.005  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:47:43.005  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:47:43.005  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 06:47:43.005  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 06:47:43.005  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:47:43.005  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 06:47:43.011  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:43.011  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 06:47:43.011  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 06:47:43.014  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:43.015  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 06:47:43.016  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 06:47:43.016  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 06:47:43.017  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-14 06:47:43.018  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-14 06:47:43.019  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 06:47:43.019  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 06:47:43.019  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 06:47:43.019  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 06:47:43.020  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 06:47:43.020  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:47:43.022  4574  4819 D BtGatt.GattService: registerClient() - UUID=0d8f2064-a39b-4293-adf6-37c59349b102
10-14 06:47:43.023  4574  4661 D BtGatt.GattService: onClientRegistered() - UUID=0d8f2064-a39b-4293-adf6-37c59349b102, clientIf=5
10-14 06:47:43.023  5589  5599 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 06:47:43.024  4574  4592 D BtGatt.GattService: start scan with filters
10-14 06:47:43.029  4574  4664 D BtGatt.ScanManager: handling starting scan
10-14 06:47:43.029  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 06:47:43.029  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 06:47:43.029  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:47:43.029  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 06:47:43.029  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 06:47:43.029  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 06:47:43.030  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 06:47:43.031  4574  4664 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:47:43.034  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:47:43.034  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 06:47:43.034  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:47:43.034  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 06:47:43.035  5589  5635 I io.jxcore.node.ConnectionHelper: start: OK
10-14 06:47:43.041  4574  4661 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 06:47:43.041  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 06:47:43.041  4574  4664 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 06:47:43.049  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 06:47:43.049  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:43.049  4574  4664 D BtGatt.ScanManager: Starting BLE batch scan
10-14 06:47:43.049  4574  4664 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 06:47:43.061  4574  4661 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 06:47:43.061  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:43.068  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 06:47:43.069  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 06:47:43.180   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:47:43.536  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-14 06:47:43.537  5589  5589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:47:43.537  5589  5589 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 06:47:46.211   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:47:48.040  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 06:47:48.040  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 06:47:48.040  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 06:47:48.040  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:47:48.040  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 06:47:48.040  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:47:48.040  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 06:47:48.041  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 06:47:48.041  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-14 06:47:48.041  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 06:47:48.041  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 06:47:48.042  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-14 06:47:48.042  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:47:48.043  4574  4592 D BtGatt.GattService: stopScan() - queue size =1
10-14 06:47:48.045  4574  4588 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 06:47:48.046  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 06:47:48.046  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-14 06:47:48.046  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 06:47:48.046  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:47:48.047  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 06:47:48.047  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 06:47:48.047  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 06:47:48.047  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-14 06:47:48.048  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:47:48.049  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 06:47:48.049  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 06:47:48.049  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 06:47:48.049  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 06:47:48.052  4574  4574 D BtGatt.ScanManager: awakened up at time 253388
,10-14 06:47:48.052  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:47:48.056  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:47:48.056  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:48.056  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:47:48.056  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-14 06:47:48.057  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:47:48.057  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:47:48.057  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:47:48.057  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:48.057  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 06:47:48.057  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:47:48.057  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:47:48.057  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:48.061  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 06:47:48.061  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 06:47:48.061  4574  4664 D BtGatt.ScanManager: stopping BLe Batch
,10-14 06:47:48.072  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-14 06:47:48.072  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:48.072  4574  4664 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 06:47:48.098  4574  4661 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-14 06:47:48.098  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:48.098  4574  4661 D BtGatt.GattService: current time is 253434974979
10-14 06:47:48.099  4574  4661 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -84, 99, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -88, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -80, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -81, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -81, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0]
,10-14 06:47:48.101  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,10-14 06:47:48.102  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-14 06:47:48.103  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-14 06:47:48.103  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 06:47:48.103  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
,10-14 06:47:48.558  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 06:47:49.315   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:50.317   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:51.318   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:52.319   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:53.060  5589  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-14 06:47:53.065  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:47:53.076  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 06:47:53.079  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:47:53.080  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-14 06:47:53.080  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-14 06:47:53.080  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-14 06:47:53.080  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-14 06:47:53.080  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:47:53.080  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 06:47:53.084  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 06:47:53.085  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 06:47:53.085  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:53.089  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:53.090  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-14 06:47:53.091  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 06:47:53.091  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 06:47:53.095  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 06:47:53.095  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-14 06:47:53.095  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 06:47:53.095  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 06:47:53.095  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 06:47:53.096  5589  5635 D BluetoothAdapter: STATE_ON
,10-14 06:47:53.099  4574  4588 D BtGatt.GattService: registerClient() - UUID=dd3c5ba3-195a-4f61-8cd1-c5cacc3b863e
10-14 06:47:53.099  4574  4661 D BtGatt.GattService: onClientRegistered() - UUID=dd3c5ba3-195a-4f61-8cd1-c5cacc3b863e, clientIf=5
,10-14 06:47:53.100  5589  5600 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 06:47:53.101  4574  4592 D BtGatt.GattService: start scan with filters
,10-14 06:47:53.103  4574  4664 D BtGatt.ScanManager: handling starting scan
,10-14 06:47:53.103  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 06:47:53.104  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 06:47:53.104  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:47:53.104  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 06:47:53.104  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 06:47:53.104  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 06:47:53.104  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-14 06:47:53.107  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 06:47:53.107  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 06:47:53.107  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:47:53.108  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 06:47:53.111  5589  5635 I io.jxcore.node.ConnectionHelper: start: OK
10-14 06:47:53.112  4574  4661 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 06:47:53.112  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.112  4574  4664 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 06:47:53.115  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 06:47:53.115  5589  5635 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-14 06:47:53.115  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 06:47:53.115  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 06:47:53.115  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:53.115  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 06:47:53.115  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:47:53.115  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 06:47:53.115  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 06:47:53.115  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 06:47:53.115  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 06:47:53.115  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 06:47:53.115  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 06:47:53.116  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:47:53.117  4574  4588 D BtGatt.GattService: stopScan() - queue size =1
,10-14 06:47:53.118  4574  4806 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 06:47:53.118  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-14 06:47:53.119  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 06:47:53.119  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 06:47:53.119  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:47:53.119  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 06:47:53.119  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 06:47:53.119  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 06:47:53.119  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 06:47:53.120  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:47:53.120  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 06:47:53.120  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 06:47:53.120  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-14 06:47:53.120  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 06:47:53.120  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.120  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 06:47:53.121  4574  4664 D BtGatt.ScanManager: Starting BLE batch scan
10-14 06:47:53.121  4574  4664 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 06:47:53.121  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:47:53.122  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:47:53.122  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:47:53.123  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:47:53.123  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 06:47:53.123  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:47:53.123  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:47:53.123  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:53.123  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:47:53.123  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:47:53.123  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:47:53.123  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:47:53.123  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:47:53.127  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:47:53.127  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:47:53.128  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:47:53.129  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:47:53.129  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:47:53.129  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:47:53.129  5589  5635 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-14 06:47:53.132  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 06:47:53.135  4574  4661 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 06:47:53.135  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:47:53.136  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 06:47:53.142  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-14 06:47:53.142  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:47:53.142  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.142  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:47:53.142  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-14 06:47:53.142  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,10-14 06:47:53.142  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 06:47:53.143  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:47:53.143  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 06:47:53.146  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 06:47:53.146  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 06:47:53.147  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:53.150  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:47:53.150  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 06:47:53.151  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 06:47:53.151  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 06:47:53.153  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-14 06:47:53.153  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.153  4574  4664 D BtGatt.ScanManager: stopping BLe Batch
10-14 06:47:53.154  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 06:47:53.155  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 06:47:53.155  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 06:47:53.155  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 06:47:53.155  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 06:47:53.156  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:47:53.159  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-14 06:47:53.159  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.159  4574  4664 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 06:47:53.160  4574  4806 D BtGatt.GattService: registerClient() - UUID=a29bfe85-ef1e-43c6-86e7-46b0788a2912
,10-14 06:47:53.160  4574  4661 D BtGatt.GattService: onClientRegistered() - UUID=a29bfe85-ef1e-43c6-86e7-46b0788a2912, clientIf=5
,10-14 06:47:53.161  5589  5600 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 06:47:53.161  4574  4819 D BtGatt.GattService: start scan with filters
,10-14 06:47:53.164  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 06:47:53.164  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 06:47:53.164  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-14 06:47:53.165  4574  4661 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 06:47:53.165  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 06:47:53.165  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.165  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 06:47:53.165  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 06:47:53.165  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 06:47:53.166  4574  4664 D BtGatt.ScanManager: handling starting scan
10-14 06:47:53.167  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:47:53.167  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 06:47:53.168  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-14 06:47:53.169  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-14 06:47:53.171  5589  5635 I io.jxcore.node.ConnectionHelper: start: OK
,10-14 06:47:53.173  4574  4661 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 06:47:53.173  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.173  4574  4664 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-14 06:47:53.178  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-14 06:47:53.178  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:53.179  4574  4664 D BtGatt.ScanManager: Starting BLE batch scan
10-14 06:47:53.179  4574  4664 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-14 06:47:53.188  4574  4661 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 06:47:53.188  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 06:47:53.193  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 06:47:53.193  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-14 06:47:53.320   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:47:53.669  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-14 06:47:53.669  5589  5589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:47:53.669  5589  5589 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 06:47:54.321   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-14 06:47:55.302   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:47:55.311   928  2962 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,10-14 06:47:57.094   928  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 06:47:58.172  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 06:47:58.172  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 06:47:58.172  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-14 06:47:58.172  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:47:58.172  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 06:47:58.173  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:47:58.173  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 06:47:58.173  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 06:47:58.173  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 06:47:58.173  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-14 06:47:58.174  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 06:47:58.174  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 06:47:58.177  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:47:58.178  4574  4819 D BtGatt.GattService: stopScan() - queue size =1
10-14 06:47:58.181  4574  4592 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-14 06:47:58.182  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 06:47:58.182  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-14 06:47:58.182  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 06:47:58.182  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:47:58.183  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 06:47:58.183  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 06:47:58.183  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 06:47:58.183  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 06:47:58.187  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:47:58.187  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 06:47:58.187  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 06:47:58.188  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 06:47:58.188  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-14 06:47:58.189  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-14 06:47:58.190  4574  4574 D BtGatt.ScanManager: awakened up at time 263526
10-14 06:47:58.191  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:47:58.192  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:47:58.192  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-14 06:47:58.196  4574  4661 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-14 06:47:58.197  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:58.197  4574  4664 D BtGatt.ScanManager: stopping BLe Batch
,10-14 06:47:58.207  4574  4661 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-14 06:47:58.207  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:58.208  4574  4664 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 06:47:58.234  4574  4661 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-14 06:47:58.234  4574  4661 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:47:58.234  4574  4661 D BtGatt.GattService: current time is 263571439379
10-14 06:47:58.235  4574  4661 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -87, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -80, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -81, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 83, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -84, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -82, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-14 06:47:58.235  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 92, -13, 112, 116, -42, 103, 48, 117, 18, -41, 74, -25, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,10-14 06:47:58.236  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-14 06:47:58.236  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-14 06:47:58.236  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-14 06:47:58.236  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-14 06:47:58.236  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-14 06:47:58.237  4574  4661 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-14 06:47:58.332   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-14 06:47:58.334   928  2962 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-14 06:47:58.693  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 06:47:58.693  5589  5589 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:47:58.693  5589  5589 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-14 06:48:03.193  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 06:48:03.194  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:03.194  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.194  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.194  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.194  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:03.194  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 06:48:03.195  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.195  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.195  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.195  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.195  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.198  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.198  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:03.202  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 06:48:03.202  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.203  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.203  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.204  5589  5635 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-14 06:48:03.206  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.206  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 06:48:03.206  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.207  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.207  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.207  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.207  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.207  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.207  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.208  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:48:03.208  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.208  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.208  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.208  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.208  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.211  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:03.211  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-14 06:48:03.212  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.212  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.213  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-14 06:48:03.213  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.213  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 06:48:03.213  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.213  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.213  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.213  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.214  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.214  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.214  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:03.214  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.214  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.214  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.214  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:03.214  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.214  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.216  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:03.216  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.216  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.216  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:48:03.217  5589  5635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,10-14 06:48:03.217  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.217  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:03.217  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.217  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.217  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.218  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.218  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 06:48:03.218  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.218  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.218  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.218  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.218  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.218  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.218  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.218  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.219  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 06:48:03.219  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.219  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.219  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.220  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-14 06:48:03.220  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.221  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:03.221  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.221  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.221  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.221  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.221  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.221  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.221  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.221  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:48:03.221  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.221  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.221  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.221  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.221  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.223  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:03.223  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.223  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.223  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.224  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 06:48:03.224  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 06:48:03.224  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 06:48:03.224  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-14 06:48:03.224  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 06:48:03.224  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 06:48:03.224  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-14 06:48:03.225  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 06:48:03.225  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-14 06:48:03.225  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.225  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:03.225  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.225  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.225  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.225  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.225  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 06:48:03.225  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.225  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.225  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.225  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.225  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.226  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.226  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.226  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.228  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:03.228  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.228  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.228  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:48:03.229  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 06:48:03.229  5589  5635 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-14 06:48:03.229  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-14 06:48:03.232  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 06:48:03.232  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-14 06:48:03.232  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-14 06:48:03.232  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-14 06:48:03.232  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-14 06:48:03.232  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-14 06:48:03.232  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-14 06:48:03.232  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-14 06:48:03.233  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-14 06:48:03.234  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-14 06:48:03.234  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-14 06:48:03.234  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-14 06:48:03.234  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-14 06:48:03.234  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-14 06:48:03.234  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-14 06:48:03.234  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-14 06:48:03.234  5589  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-14 06:48:03.235  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-14 06:48:03.235  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 06:48:03.235  5589  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-14 06:48:03.235  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-14 06:48:03.235  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-14 06:48:03.235  5589  5635 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,10-14 06:48:03.235  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,10-14 06:48:03.242  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-14 06:48:03.243  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,10-14 06:48:03.243  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-14 06:48:03.244  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-14 06:48:03.244  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-14 06:48:03.244  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-14 06:48:03.244  5589  5635 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,10-14 06:48:03.244  5589  5635 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-14 06:48:03.245  5589  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
10-14 06:48:03.245  5589  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-14 06:48:03.245  5589  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
,10-14 06:48:03.245  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.245  5589  5636 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,10-14 06:48:03.245  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 06:48:03.245  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.246  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.246  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.246  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.246  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.246  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-14 06:48:03.247  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.247  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.247  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.247  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.247  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.247  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.247  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.247  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.248  5589  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
,10-14 06:48:03.249  4819  4819 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32888]" dev="sockfs" ino=32888 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-14 06:48:03.249  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:03.249  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.249  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:03.249  5589  5636 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-14 06:48:03.249  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.249  5589  5636 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 06:48:03.250  5589  5635 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-14 06:48:03.251  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.249  4819  4819 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32888]" dev="sockfs" ino=32888 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 06:48:03.251  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:03.251  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.251  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.251  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.251  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.251  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.251  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.251  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:03.251  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.251  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.251  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.251  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.251  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.251  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.252  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:03.252  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.252  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.253  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.253  5589  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-14 06:48:03.254  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 06:48:03.254  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:03.254  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.254  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.254  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.254  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.254  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.254  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.254  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.254  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.254  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.254  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.254  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.254  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.254  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.255  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 06:48:03.255  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.255  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.255  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.256  5589  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-14 06:48:03.256  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-14 06:48:03.256  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 06:48:03.257  5589  5635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-14 06:48:03.257  5589  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-14 06:48:03.257  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-14 06:48:03.257  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 06:48:03.257  5589  5635 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-14 06:48:03.257  5589  5635 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,10-14 06:48:03.257  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-14 06:48:03.257  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-14 06:48:03.257  5589  5635 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-14 06:48:03.257  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:03.257  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:03.257  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:03.257  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.257  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.257  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.258  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.258  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
,10-14 06:48:03.258  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.258  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.258  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.258  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.258  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.258  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.258  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.259  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:03.259  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:03.259  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.259  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.260  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:03.260  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:48:03.260  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:03.260  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:03.260  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:03.260  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:03.260  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:03.260  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:03.260  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:03.260  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:04.387   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:48:07.417   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:48:08.261  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:08.261  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.262  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:08.262  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.262  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:08.262  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:08.262  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:08.263  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:08.263  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:08.263  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:08.263  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:08.263  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.264  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:08.264  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:08.264  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:08.264  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.264  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.264  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 06:48:08.264  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:48:08.265  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.265  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.265  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:08.268  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:08.268  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-14 06:48:08.268  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.269  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.273  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-14 06:48:08.273  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:08.276  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-14 06:48:08.278  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-14 06:48:08.278  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-14 06:48:08.279  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-14 06:48:08.279  5589  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-14 06:48:08.279  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-14 06:48:08.279  5589  5589 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-14 06:48:08.279  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 06:48:08.280  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:08.281  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-14 06:48:08.281  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-14 06:48:08.281  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-14 06:48:08.281  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.281  5589  5638 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 06:48:08.281  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-14 06:48:08.281  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-14 06:48:08.282  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:08.282  5589  5589 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-14 06:48:08.282  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.282  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 06:48:08.282  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 06:48:08.282  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-14 06:48:08.283  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.283  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.282  4592  4592 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34076]" dev="sockfs" ino=34076 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 06:48:08.282  4592  4592 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34076]" dev="sockfs" ino=34076 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-14 06:48:08.285  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:08.285  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:48:08.285  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:08.285  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:08.285  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:08.285  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:08.285  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:08.285  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:08.285  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:08.285  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.286  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.286  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-14 06:48:08.286  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:08.286  5589  5638 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-14 06:48:08.286  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.286  5589  5638 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-14 06:48:08.286  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
,10-14 06:48:08.286  5589  5638 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-14 06:48:08.286  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:08.286  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.286  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.286  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.287  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.287  5589  5589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-14 06:48:08.287  5589  5589 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:08.289  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:08.289  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:08.289  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.289  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.291  5589  5635 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-14 06:48:08.291  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-14 06:48:08.291  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-14 06:48:08.292  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 06:48:08.292  5589  5635 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-14 06:48:08.292  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:08.292  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:08.292  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:08.292  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:08.292  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:48:08.292  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.292  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:08.293  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:08.293  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.293  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.293  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:08.293  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.293  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.293  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.293  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.295  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:08.295  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:08.295  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.296  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.303  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:08.303  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-14 06:48:08.303  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:08.304  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-14 06:48:08.304  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.304  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.304  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:08.304  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:08.304  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.304  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.304  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:08.304  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:48:08.304  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.304  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.304  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.306  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:08.306  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:08.306  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.306  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.307  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-14 06:48:08.307  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:08.307  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:08.307  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:08.308  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.308  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.308  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:08.308  5589  5635 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@804e3a2 not in the list
10-14 06:48:08.308  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:08.308  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.308  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:08.308  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.308  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.308  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:08.308  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:08.310  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-14 06:48:08.310  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:08.310  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:08.310  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8bc7833 not in the list
10-14 06:48:08.311  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-14 06:48:08.312  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 06:48:08.312  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-14 06:48:08.312  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-14 06:48:08.312  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,10-14 06:48:08.312  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-14 06:48:08.315  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-14 06:48:08.315  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-14 06:48:08.315  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-14 06:48:08.316  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-14 06:48:08.317  5589  5635 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,10-14 06:48:08.317  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-14 06:48:08.317  5589  5635 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-14 06:48:08.317  5589  5635 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-14 06:48:08.318  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-14 06:48:08.318  5589  5635 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-14 06:48:08.318  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-14 06:48:08.318  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-14 06:48:08.319  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-14 06:48:08.319  5589  5635 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-14 06:48:08.320  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:08.320  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cc9dd added. We now have 3 listener(s)
10-14 06:48:08.320  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:08.322  5589  5635 D BluetoothAdapter: enable(): BT is already enabled..!
,10-14 06:48:08.322   928  3401 D WifiService: setWifiEnabled: true pid=5589, uid=10077
10-14 06:48:08.322   928  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 06:48:08.379  4574  4777 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-14 06:48:08.379  4574  4797 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
10-14 06:48:08.379  5589  5636 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-14 06:48:08.380  5589  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-14 06:48:08.380  5589  5636 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,10-14 06:48:08.787  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 06:48:09.322   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:10.323   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:10.448   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-14 06:48:11.324   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:12.325   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:13.326   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:13.329  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 06:48:13.329  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d517952 added. We now have 4 listener(s)
10-14 06:48:13.329  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:13.342  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:13.343  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d517952 removed from the list
10-14 06:48:13.343  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:13.343  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:13.343  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:13.345  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:13.345  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@613d423 added. We now have 4 listener(s)
10-14 06:48:13.345  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:13.348  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:13.348  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@613d423 removed from the list
10-14 06:48:13.348  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:13.348  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:13.348  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:13.350  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:13.350  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7262d20 added. We now have 4 listener(s)
10-14 06:48:13.350  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:13.355   928  3142 D WifiService: setWifiEnabled: false pid=5589, uid=10077
,10-14 06:48:13.355   928  3142 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 06:48:13.362   928  2960 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-14 06:48:13.362   928  2960 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-14 06:48:13.362   928  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 06:48:13.362   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 06:48:13.366  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:13.367  4574  4657 D BluetoothAdapterState: Current state: ON, message: 23
10-14 06:48:13.367  4574  4657 D BluetoothAdapterProperties: Setting state to 13
10-14 06:48:13.367  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-14 06:48:13.368  4574  4657 D BluetoothAdapterProperties: onBluetoothDisable()
10-14 06:48:13.370  4574  4657 I BluetoothAdapterState: Entering PendingCommandState
10-14 06:48:13.376  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:13.376  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:13.379  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.379  4574  4574 D BluetoothMapService: onReceive
10-14 06:48:13.379  4574  4574 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 06:48:13.379  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:13.379  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:48:13.379  4574  4574 D BluetoothMapService: STATE_TURNING_OFF
10-14 06:48:13.379  4574  4574 D BluetoothMapService: MAP Service closeService in
10-14 06:48:13.379  4574  4574 D BluetoothMapMasInstance0: MAP Service shutdown
,10-14 06:48:13.379  4574  4574 D ObexServerSockets0: shutdown(block = true)
,10-14 06:48:13.380  4574  4574 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 06:48:13.380  4574  4821 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-14 06:48:13.380  4574  4574 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 06:48:13.380  4574  4797 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-14 06:48:13.381  4574  4822 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 06:48:13.383   509   922 D CommandListener: Clearing all IP addresses on wlan0
10-14 06:48:13.383   928  5342 D DhcpClient: Clearing IP address
10-14 06:48:13.384  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:13.386   509   922 D CommandListener: Setting iface cfg
10-14 06:48:13.387  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:13.390  4574  4574 I BtOppRfcommListener: stopping Accept Thread
10-14 06:48:13.390  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:13.390  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:13.390  4574  5254 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-14 06:48:13.390  4574  5254 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-14 06:48:13.391  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.391  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:13.393  3555  5398 V NativeCrypto: Read error: ssl=0x7f68b16600: I/O error during system call, Connection timed out
10-14 06:48:13.395  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.395   928   941 I ActivityManager: Start proc 5642:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:13.395  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:13.397  4574  4661 D BluetoothAdapterProperties: Scan Mode:20
10-14 06:48:13.397   928  5343 D DhcpClient: Receive thread stopped
10-14 06:48:13.398  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, me,ssage: 21
10-14 06:48:13.398  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.398  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:13.400  3555  5398 V NativeCrypto: SSL shutdown failed: ssl=0x7f68b16600: I/O error during system call, Broken pipe
,10-14 06:48:13.401  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:13.405   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-14 06:48:13.405   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-14 06:48:13.408  4574  4574 D HeadsetService: Received stop request...Stopping profile...
10-14 06:48:13.408   535   535 E Parcel  : Reading a NULL string not supported here.
,10-14 06:48:13.411   928  2962 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-14 06:48:13.412  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.411   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:13.412  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:13.412  3103  3959 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:13.412  3103  3103 D HeadsetProfile: Bluetooth service disconnected
10-14 06:48:13.413  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.413  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:13.414  4574  4574 D A2dpService: Received stop request...Stopping profile...
10-14 06:48:13.414  4574  4814 D A2dpStateMachine: Exit Disconnected: -1
10-14 06:48:13.414  3731  3897 W QCNEJ   : |CORE| network lost: 100
10-14 06:48:13.415  3731  3897 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-14 06:48:13.415  3766  3788 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:13.416   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:13.416   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:13.416   928   928 D RttService: SCAN_AVAILABLE : 1
,10-14 06:48:13.417  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.418   928   928 D BluetoothA2dp: Proxy object disconnected
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:13.418  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:13.418   928  3069 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-14 06:48:13.418  4574  4574 D HidService: Received stop request...Stopping profile...
10-14 06:48:13.418  4574  4574 D HidService: Stopping Bluetooth HidService
,10-14 06:48:13.418  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.419  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:13.419  4574  4574 V BluetoothAdapterState: isTurningOff()=true
,10-14 06:48:13.419  4574  4574 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:13.419  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.419  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:13.420  4574  4574 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-14 06:48:13.421  4574  4574 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-14 06:48:13.421  4574  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-14 06:48:13.421  4574  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:13.421  4574  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:13.421  4574  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:13.421  4574  4574 D HealthService: Received stop request...Stopping profile...
10-14 06:48:13.422  4574  4661 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-14 06:48:13.422  4574  4574 D PanService: Received stop request...Stopping profile...
10-14 06:48:13.425  4574  4574 D BluetoothMapService: Received stop request...Stopping profile...
10-14 06:48:13.425  4574  4574 D BluetoothMapService: stop()
10-14 06:48:13.425  4574  4574 D BluetoothMapAppObserver: deinitObservers()
10-14 06:48:13.425  4574  4574 D BluetoothMapAppObserver: removeReceiver()
10-14 06:48:13.427  4574  4574 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:13.426  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.427  4574  4574 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:13.427  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:13.427  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:13.427  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:13.428  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.428  4574  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:13.428  4574  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:13.428  4574  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-14 06:48:13.428  4574  4777 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 06:48:13.428  4574  4574 D SapService: Received stop request...Stopping profile...
10-14 06:48:13.428  4574  4777 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 06:48:13.428  4574  4574 V SapService: stop()
,10-14 06:48:13.428  4574  4777 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 06:48:13.428  4574  4777 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 06:48:13.429  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:13.430   928  2960 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-14 06:48:13.430  4574  4574 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:13.430  4574  4574 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:13.430  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.430  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:13.431  4574  4574 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-14 06:48:13.431  4574  4574 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-14 06:48:13.431  4574  4661 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 06:48:13.431  4574  4574 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:13.431  4574  4574 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:13.431  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.431  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:13.431  4574  4574 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-14 06:48:13.432  4574  4661 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-14 06:48:13.433  4574  4574 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 06:48:13.433  4574  4574 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:13.433  4574  4574 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:13.433  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.433  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:13.433  4574  4574 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-14 06:48:13.434  4574  4574 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-14 06:48:13.434  3103  3103 D BluetoothA2dp: Proxy object disconnected
10-14 06:48:13.434  3103  3103 D BluetoothInputDevice: Proxy object disconnected
10-14 06:48:13.434  3103  3103 D HidProfile: Bluetooth service disconnected
10-14 06:48:13.434  3103  3103 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 06:48:13.434  3103  3103 D PanProfile: Bluetooth service disconnected
10-14 06:48:13.434  3103  3103 D BluetoothMap: Proxy object disconnected
10-14 06:48:13.434  3103  3103 D MapProfile: Bluetooth service disconnected
10-14 06:48:13.435  4574  4574 D BluetoothMapService: MAP Service closeService in
10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:13.435  4574  4574 D BluetoothMapService: cleanup()
10-14 06:48:13.435  4574  4574 D BluetoothMapService: MAP Service closeService in
,10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.435  4574  4574 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:13.436  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 06:48:13.437  4574  4657 D BluetoothAdapterProperties: Setting state to 15
10-14 06:48:13.437  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 06:48:13.438  4574  4657 I BluetoothAdapterState: Entering BleOnState
10-14 06:48:13.438  3103  3121 D BluetoothMap: onBluetoothStateChange: up=false
10-14 06:48:13.439  3766  3784 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:13.439  3103  3115 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 06:48:13.440  3103  3959 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 06:48:13.440   928  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 06:48:13.442   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:13.442   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:13.442  3103  3121 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 06:48:13.443   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:13.443  3103  3115 D BluetoothPan: onBluetoothStateChange on: false
10-14 06:48:13.444  3103  3959 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:13.444   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 06:48:13.444  4574  4657 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-14 06:48:13.444  4574  4657 D BluetoothAdapterProperties: Setting state to 16
10-14 06:48:13.444  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-14 06:48:13.447  4574  4657 D BluetoothAdapterProperties: onBleDisable
10-14 06:48:13.447  4574  4657 I BluetoothAdapterState: Entering PendingCommandState
10-14 06:48:13.447  4574  4658 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 06:48:13.448  4574  4661 D BluetoothAdapterProperties: Scan Mode:20
10-14 06:48:13.448  4574  4777 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 06:48:13.448  4574  4777 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:13.449  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:13.449  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:13.450  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:13.451  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:13.456  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:13.457   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 06:48:13.459  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:13.461  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:13.475   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 06:48:13.475   509   922 D CommandListener: Clearing all IP addresses on wlan0
10-14 06:48:13.476   509   922 D TetherController: Setting IP forward enable = 0
10-14 06:48:13.475  5642  5642 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
10-14 06:48:13.477   928  2962 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,10-14 06:48:13.477   928  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-14 06:48:13.480   928  2960 D DhcpClient: doQuit
,10-14 06:48:13.481   928  2960 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-14 06:48:13.481   928  5342 D DhcpClient: onQuitting
10-14 06:48:13.481  3436  3436 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-14 06:48:13.482  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:13.482  5241  5241 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@19252c and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-14 06:48:13.483   928   945 D Tethering: MasterInitialState.processMessage what=3
10-14 06:48:13.484  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:13.484  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:13.485  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.485  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:13.487  5007  5030 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-14 06:48:13.487  5007  5030 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 06:48:13.487  5007  5030 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-14 06:48:13.488  5007  5030 E SarControlService: no key has been found,reset the power
10-14 06:48:13.488  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 06:48:13.488  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 06:48:13.488  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 06:48:13.488  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:13.488  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:13.488  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:13.488  5032  5032 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 06:48:13.489  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.489  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 06:48:13.489  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:13.489  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,10-14 06:48:13.489  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 06:48:13.490  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:13.491  5032  5032 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 06:48:13.491  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:13.491  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:13.492  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 06:48:13.492  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:13.494  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:13.496  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:13.496  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000ea03000000000000ffffffff]
10-14 06:48:13.496  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:13.496  5032  5046 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-14 06:48:13.497  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:13.498  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-14 06:48:13.501  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000eb03000000000000ffffffff]
,10-14 06:48:13.501  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:13.501  5032  5046 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,10-14 06:48:13.502  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:13.502  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-14 06:48:13.504  3436  3436 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-14 06:48:13.509  3436  3436 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-14 06:48:13.511  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 06:48:13.517   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ec7d975:true
,10-14 06:48:13.517  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 06:48:13.530   928  3139 I ActivityManager: Start proc 5670:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-14 06:48:13.540  3436  3436 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 06:48:13.546  5642  5642 D LocalBluetoothProfileManager: Adding local MAP profile
,10-14 06:48:13.556  5642  5642 D BluetoothMap: Create BluetoothMap proxy object
,10-14 06:48:13.567  3436  3436 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-14 06:48:13.568  5670  5670 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-14 06:48:13.571  5642  5642 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-14 06:48:13.582  5642  5642 D DockEventReceiver: finishStartingService: stopping service
,10-14 06:48:13.595   928  3814 I ActivityManager: Killing 4946:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-14 06:48:13.655  4574  4661 I bt_hci  : shut_down
,10-14 06:48:13.659  4574  4666 D bt_hwcfg: hw_epilog_process
,10-14 06:48:13.659  4574  4666 I bt_vendor: low_power_mode_cb
,10-14 06:48:13.661  4574  4666 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-14 06:48:13.661  4574  4666 I bt_vendor: epilog_cb
10-14 06:48:13.661  4574  4666 I bt_hci  : epilog_finished_callback
,10-14 06:48:13.663  4574  4661 I bt_hci_h4: hal_close
,10-14 06:48:13.664  4574  4661 I bt_userial_vendor: device fd = 54 close
,10-14 06:48:13.669   928  2960 D wifi    : In wifi stop Hal
,10-14 06:48:13.669  4981  4981 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 06:48:13.669   928  2960 D wifi    : halHandle = 0x7f66d11b80, mVM = 0x7f8334d140, mCls = 0x100a02
,10-14 06:48:13.669   928  3434 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-14 06:48:13.669   928  3434 D WifiHAL : Got a signal to exit!!!
10-14 06:48:13.669   928  3434 I WifiHAL : Exit wifi_event_loop
10-14 06:48:13.670   928  2960 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-14 06:48:13.670   928  2960 E WifiHAL : Event processing terminated
10-14 06:48:13.670   928  2960 D wifi    : In wifi cleaned up handler
10-14 06:48:13.670   928  2960 I WifiHAL : Internal cleanup completed
10-14 06:48:13.671  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:13.673  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:13.674  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:13.676  4053  4204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-14 06:48:13.689   928  3434 D wifi    : set interface wlan0 flags (DOWN)
,10-14 06:48:13.689   928  2960 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 06:48:13.772  4574  4658 D bt_stack_manager: event_shut_down_stack finished.
,10-14 06:48:13.773  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-14 06:48:13.774  4574  4574 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-14 06:48:13.774  4574  4657 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-14 06:48:13.775  4574  4574 D BtGatt.GattService: Received stop request...Stopping profile...
10-14 06:48:13.775  4574  4574 D BtGatt.GattService: stop()
10-14 06:48:13.775  4574  4574 D BtGatt.AdvertiseManager: advertise clients cleared
10-14 06:48:13.776  4574  4574 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:13.776  4574  4574 V BluetoothAdapterState: isTurningOn()=false
,10-14 06:48:13.776  4574  4574 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:13.776  4574  4574 V BluetoothAdapterState: isBleTurningOff()=true
10-14 06:48:13.777  4574  4657 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 06:48:13.777  4574  4657 D BluetoothAdapterProperties: Setting state to 10
10-14 06:48:13.777  4574  4657 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-14 06:48:13.777  5670  5670 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.777  5670  5670 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.Contex,tImpl.openFileInput(ContextImpl.java:384)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.777  5670  5670 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.,app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.777  4574  4657 I BluetoothAdapterState: Entering OffState
10-14 06:48:13.777  5670  5670 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.777  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.778  5670  5670 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.r.k.d(PG:583)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:170)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.778  5670  5670 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.778  5670  5670 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.File.exists(File.java:361)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.778   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-14 06:48:13.778  5670  5670 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:48:13.778  5670  5670 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:48:13.783  4574  4574 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-14 06:48:13.783  4574  4574 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 06:48:13.783  4574  4574 I BluetoothServiceJni: cleanupNative: return from cleanup
10-14 06:48:13.785  4574  4658 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-14 06:48:13.795  4574  4574 I art     : System.exit called, status: 0
10-14 06:48:13.795  4574  4574 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 06:48:13.811  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 06:48:13.818  5642  5642 D DockEventReceiver: finishStartingService: stopping service
10-14 06:48:13.819   928  3142 I ActivityManager: Killing 5371:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
10-14 06:48:13.847   928  3400 I ActivityManager: Process com.android.bluetooth (pid 4574) has died
10-14 06:48:13.850  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 06:48:13.862   928  3767 I ActivityManager: Start proc 5703:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-14 06:48:13.892   928   945 D Tethering: InitialState.processMessage what=4
,10-14 06:48:13.895   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-14 06:48:13.931  5703  5703 D AdapterServiceConfig: Adding HeadsetService
,10-14 06:48:13.932  5703  5703 D AdapterServiceConfig: Adding A2dpService
10-14 06:48:13.932  5703  5703 D AdapterServiceConfig: Adding HidService
,10-14 06:48:13.932  5703  5703 D AdapterServiceConfig: Adding HealthService
,10-14 06:48:13.932  5703  5703 D AdapterServiceConfig: Adding PanService
10-14 06:48:13.932  5703  5703 D AdapterServiceConfig: Adding GattService
10-14 06:48:13.932  5703  5703 D AdapterServiceConfig: Adding BluetoothMapService
10-14 06:48:13.932  5703  5703 D AdapterServiceConfig: Adding SapService
10-14 06:48:13.936   928  3401 I ActivityManager: Killing 5384:com.android.chrome/u0a39 (adj 15): empty #17
,10-14 06:48:13.971  3854  3854 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-14 06:48:13.974  3854  3854 D SystemUpdateService: onCreate
,10-14 06:48:13.977  3854  3854 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 06:48:13.986  3854  3854 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-14 06:48:13.997  3854  3854 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 06:48:13.999  3854  3854 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 06:48:14.003  3854  5715 I SystemUpdateService: active receiver: enabled
,10-14 06:48:14.004  3854  5368 I iu.UploadsManager: num queued entries: 0
,10-14 06:48:14.004  3854  5368 I iu.UploadsManager: num updated entries: 0
10-14 06:48:14.005  3854  5368 I iu.SyncManager: NEXT; no task
,10-14 06:48:14.009  3854  5715 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 06:48:14.013   928  3139 I ActivityManager: Start proc 5717:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-14 06:48:14.027  3854  5715 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-14 06:48:14.028  3854  5715 I SystemUpdateService: now status is 0 (complete)
10-14 06:48:14.028  3854  5715 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 06:48:14.028  3854  5715 I SystemUpdateService: file has been verified
10-14 06:48:14.028  3854  5715 I SystemUpdateService: OTA package size = 21989297
,10-14 06:48:14.049  5717  5717 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-14 06:48:14.055  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-14 06:48:14.062  3854  5715 I SystemUpdateService: showing system update notification
,10-14 06:48:14.070  5717  5717 D SprintDMHelper: simOperator: 
,10-14 06:48:14.070  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 06:48:14.083   928  3142 I ActivityManager: Start proc 5729:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-14 06:48:14.102  3854  3854 D SystemUpdateService: onDestroy
,10-14 06:48:14.108   928  3814 I ActivityManager: Killing 5402:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-14 06:48:14.186  4981  5743 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-14 06:48:14.191   928  3832 I ActivityManager: Start proc 5744:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-14 06:48:14.193   928  3832 I ActivityManager: Killing 5241:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-14 06:48:14.206  5670  5695 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-14 06:48:14.251  5744  5744 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-14 06:48:14.284   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@846203f:true
,10-14 06:48:14.326   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-14 06:48:14.448   928  3767 I ActivityManager: Killing 4671:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-14 06:48:14.490   928  3814 I ActivityManager: Start proc 5758:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-14 06:48:14.522  5758  5758 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-14 06:48:14.530   928   939 I ActivityManager: Killing 5450:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-14 06:48:14.534   509   922 E Netd    : netlink response contains error (No such file or directory)
,10-14 06:48:14.535   928  2962 E NetdConnector: NDC Command {113 network destroy 100} took too long (1056ms)
,10-14 06:48:14.535   509   922 D TetherController: Setting IP forward enable = 0
10-14 06:48:14.535   928  2962 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,10-14 06:48:14.536   928  2958 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1052ms)
,10-14 06:48:14.536   928  2957 E NetdConnector: NDC Command {115 bandwidth gettetherstats} took too long (640ms)
,10-14 06:48:18.382   928  3142 D WifiService: setWifiEnabled: true pid=5589, uid=10077
10-14 06:48:18.382   928  3142 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 06:48:18.393   509   922 D SoftapController: Softap fwReload - Ok
,10-14 06:48:18.398   509   922 D CommandListener: Setting iface cfg
,10-14 06:48:18.399   509   922 D CommandListener: Trying to bring down wlan0
10-14 06:48:18.400   509   922 D CommandListener: Clearing all IP addresses on wlan0
,10-14 06:48:18.403   928  2960 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 06:48:18.978   928  2960 D wifi    : set interface wlan0 flags (UP)
,10-14 06:48:18.982   928  2960 I WifiHAL : Initializing wifi
10-14 06:48:18.982   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-14 06:48:18.982   928  2960 I WifiHAL : Creating socket
,10-14 06:48:18.988   928  2960 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-14 06:48:18.989   928  2960 D wifi    : Did set static halHandle = 0x7f66d11b80
10-14 06:48:18.989   928  2960 D wifi    : halHandle = 0x7f66d11b80, mVM = 0x7f8334d140, mCls = 0x2018c2
10-14 06:48:18.989   928  2960 D wifi    : array field set
10-14 06:48:18.989   928  2960 I WifiNative-HAL: interface[0] = wlan0
10-14 06:48:18.991   928  5780 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547185826688
,10-14 06:48:18.991   928  5780 D wifi    : waitForHalEvents called, vm = 0x7f8334d140, obj = 0x2018c2, env = 0x7f6440ab00
,10-14 06:48:19.069  5781  5781 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 06:48:19.090  5781  5781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 06:48:19.093   928  2960 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-14 06:48:19.096  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:19.096  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:19.098  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:19.115  5781  5781 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 06:48:19.115  5781  5781 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 06:48:19.131   928  2960 D WifiConfigStore: Loading config and enabling all networks 
,10-14 06:48:19.131  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:19.131  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:19.131  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 06:48:19.131  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:19.133  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:19.133  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:19.133  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:19.133  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:19.135  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:19.135  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:19.135  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 06:48:19.136  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:19.145   928  2960 D WifiConfigStore: loaded 0 passpoint configs
,10-14 06:48:19.146   928  2960 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-14 06:48:19.146   928  2960 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-14 06:48:19.147   928  2960 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-14 06:48:19.148   928  2960 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-14 06:48:19.149   928  2960 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-14 06:48:19.149   928  2960 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 06:48:19.149   928  2960 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-14 06:48:19.152   928  2960 D WifiNative-HAL: Setting external_sim to 1
,10-14 06:48:19.152  4981  4981 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 06:48:19.152   928  2960 D wifi    : setting dfs flag to true, 0x7f68ffdfc0
10-14 06:48:19.153   928  2960 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 06:48:19.153   928  2960 D wifi    : setting scan oui 0x7f68ffdfc0
,10-14 06:48:19.153   928  2960 D WifiHAL : Sending mac address OUI
,10-14 06:48:19.156   928  2960 E native  : do suspend false
,10-14 06:48:19.163   928  2960 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-14 06:48:19.163   928   928 D RttService: SCAN_AVAILABLE : 3
10-14 06:48:19.163   509   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-14 06:48:19.163   928  3069 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-14 06:48:19.164   509   922 D CommandListener: Setting iface cfg
,10-14 06:48:19.167   928  2959 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-14 06:48:19.167   928  2959 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 06:48:19.175   928  2959 D WifiNative-HAL: p2pGetDeviceAddress
,10-14 06:48:19.180   928  2959 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 06:48:19.180   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=284516 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-14 06:48:22.334  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:22.339  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:22.346  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:22.352  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:22.391   928  2960 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-14 06:48:22.392   928  2960 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-14 06:48:22.392   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 06:48:22.404   928  2960 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-14 06:48:22.437   928  2960 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-14 06:48:22.439  5781  5781 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-14 06:48:22.920  5781  5781 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 06:48:22.988  5781  5781 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 06:48:22.990  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-14 06:48:23.003   928  2960 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 06:48:23.003   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 06:48:23.003   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-14 06:48:23.022   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 06:48:23.037   509   922 D CommandListener: Setting iface cfg
,10-14 06:48:23.044   928  2960 D WifiStateMachine: Start Dhcp Watchdog 2
,10-14 06:48:23.050   928  5787 D DhcpClient: Receive thread started
,10-14 06:48:23.056   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-14 06:48:23.056   928  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-14 06:48:23.056   928  2962 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-14 06:48:23.137   928  2960 E native  : do suspend false
,10-14 06:48:23.153   928  5786 D DhcpClient: Broadcasting DHCPDISCOVER
,10-14 06:48:23.182   928  5787 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172554, domain null
,10-14 06:48:23.182   928  5786 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172554 seconds
,10-14 06:48:23.184   928  5786 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-14 06:48:23.202   928  5787 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-14 06:48:23.202   928  5786 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-14 06:48:23.206   509   922 D CommandListener: Setting iface cfg
,10-14 06:48:23.210   928  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-14 06:48:23.213   928  5786 D DhcpClient: Scheduling renewal in 86399s
,10-14 06:48:23.223   928  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-14 06:48:23.224   928  2960 D WifiConfigStore: No blacklist allowed without epno enabled
,10-14 06:48:23.225   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-14 06:48:23.227   928  2962 D ConnectivityService: Adding iface wlan0 to network 101
10-14 06:48:23.233   928  2960 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-14 06:48:23.272   928  2962 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-14 06:48:23.272   928  2962 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-14 06:48:23.274   928  2962 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-14 06:48:23.276   928  2962 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-14 06:48:23.277   928  2962 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-14 06:48:23.284   928  2962 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-14 06:48:23.288   928  2962 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-14 06:48:23.289   928  2962 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-14 06:48:23.289   928  2962 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-14 06:48:23.289   928  2960 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-14 06:48:23.289   928  2962 D ConnectivityService:    accepting network in place of null
10-14 06:48:23.289   928  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 06:48:23.290   928  2962 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -55]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 06:48:23.306   928  5785 D NetlinkSocketObserver: NeighborEvent{elapsedMs=288643, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-14 06:48:23.313   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 06:48:23.333   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 06:48:23.336   928  2962 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-14 06:48:23.337  3731  3897 W QCNEJ   : |CORE| network available: 101
10-14 06:48:23.337   928  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 06:48:23.338   928  2962 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,10-14 06:48:23.338   928   945 D Tethering: MasterInitialState.processMessage what=3
10-14 06:48:23.341  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:23.341  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:23.341  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.341  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:23.344  3731  3897 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-14 06:48:23.345  3731  3897 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-14 06:48:23.345  3731  3897 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-14 06:48:23.347  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:23.347  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:23.347  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.347  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:23.349  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:23.349  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:23.349  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.349  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:23.351  5007  5030 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-14 06:48:23.351  5007  5030 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 06:48:23.351  5007  5030 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-14 06:48:23.351  5007  5030 E SarControlService: no key has been found,reset the power
10-14 06:48:23.352  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 06:48:23.352  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 06:48:23.352  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 06:48:23.352  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:23.352  5032  5032 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 06:48:23.353  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 06:48:23.353  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 06:48:23.353  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 06:48:23.354  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:23.354  5032  5032 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-14 06:48:23.357  3854  3854 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-14 06:48:23.360  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000ec03000000000000ffffffff]
10-14 06:48:23.361  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:23.361  5032  5046 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-14 06:48:23.361  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000ed03000000000000ffffffff]
10-14 06:48:23.361  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:23.361  5032  5046 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-14 06:48:23.362  3854  3854 D SystemUpdateService: onCreate
10-14 06:48:23.362  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:23.363  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 06:48:23.363  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:23.363  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-14 06:48:23.366  3854  3854 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 06:48:23.376  3854  3854 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-14 06:48:23.380  3854  5368 I iu.UploadsManager: num queued entries: 0
,10-14 06:48:23.380  3854  5368 I iu.UploadsManager: num updated entries: 0
10-14 06:48:23.381  3854  5368 I iu.SyncManager: NEXT; no task
,10-14 06:48:23.384  3854  5797 I SystemUpdateService: active receiver: enabled
,10-14 06:48:23.388   928  5784 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.138,2a00:1450:400c:c0c::66
,10-14 06:48:23.388   928  3862 D WifiService: setWifiEnabled: false pid=5589, uid=10077
10-14 06:48:23.388   928  3862 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 06:48:23.389   928  2960 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-14 06:48:23.389   928  2960 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-14 06:48:23.389   928  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 06:48:23.389   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 06:48:23.390  3854  3854 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-14 06:48:23.393  3854  3854 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 06:48:23.395  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-14 06:48:23.397   928  5786 D DhcpClient: Clearing IP address
10-14 06:48:23.397   509   922 D CommandListener: Clearing all IP addresses on wlan0
10-14 06:48:23.398   509   922 D CommandListener: Setting iface cfg
10-14 06:48:23.399   928  5787 D DhcpClient: Receive thread stopped
10-14 06:48:23.400  5717  5717 D SprintDMHelper: simOperator: 
10-14 06:48:23.400  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 06:48:23.406   928  5784 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400c:c0c::66 (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,10-14 06:48:23.406   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
,10-14 06:48:23.407   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-14 06:48:23.408   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-14 06:48:23.412   535   535 E Parcel  : Reading a NULL string not supported here.
,10-14 06:48:23.413   928   928 D RttService: SCAN_AVAILABLE : 1
10-14 06:48:23.413   928  3069 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-14 06:48:23.416   928  2962 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-14 06:48:23.419  3731  3897 W QCNEJ   : |CORE| network lost: 101
10-14 06:48:23.419  3731  3897 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-14 06:48:23.422   928  2960 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-14 06:48:23.424   928  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-14 06:48:23.437  3854  5797 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 06:48:23.439  3854  5797 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-14 06:48:23.439  3854  5797 I SystemUpdateService: now status is 0 (complete)
10-14 06:48:23.439  3854  5797 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 06:48:23.439  3854  5797 I SystemUpdateService: file has been verified
10-14 06:48:23.440  3854  5797 I SystemUpdateService: OTA package size = 21989297
,10-14 06:48:23.442   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 06:48:23.449  3854  5797 I SystemUpdateService: showing system update notification
,10-14 06:48:23.460  3854  3854 D SystemUpdateService: onDestroy
,10-14 06:48:23.464   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-14 06:48:23.465   509   922 D CommandListener: Clearing all IP addresses on wlan0
10-14 06:48:23.465   928  2962 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-14 06:48:23.465   928  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 06:48:23.467   928   945 D Tethering: MasterInitialState.processMessage what=3
,10-14 06:48:23.469  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:23.469  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:23.469  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.469  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:23.471  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:23.471  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:23.471  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.471  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:23.472  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:23.473  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:23.473   928  2960 D DhcpClient: doQuit
10-14 06:48:23.473  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.473   928  2960 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-14 06:48:23.473   928  5786 D DhcpClient: onQuitting
10-14 06:48:23.473  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:23.474  5781  5781 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-14 06:48:23.474  5007  5030 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-14 06:48:23.474  5007  5030 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 06:48:23.474  5007  5030 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,10-14 06:48:23.474  5007  5030 E SarControlService: no key has been found,reset the power
10-14 06:48:23.475  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-14 06:48:23.475  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 06:48:23.476  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-14 06:48:23.476  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:23.476  5032  5032 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 06:48:23.477  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:23.478  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:23.478  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.478  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:23.479  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:23.479  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:23.479  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.479  3854  3854 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-14 06:48:23.479  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:23.480  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:23.480  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:23.480  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:23.480  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:23.482  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 06:48:23.482  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 06:48:23.482  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 06:48:23.483  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000ee03000000000000ffffffff]
10-14 06:48:23.483  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:23.483  5032  5046 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,10-14 06:48:23.484  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:23.484  5032  5032 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 06:48:23.485  3854  3854 D SystemUpdateService: onCreate
10-14 06:48:23.485  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:23.486  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 06:48:23.489  5781  5781 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-14 06:48:23.490  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000ef03000000000000ffffffff]
10-14 06:48:23.490  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:23.491  5032  5046 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,10-14 06:48:23.492  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:23.492  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-14 06:48:23.492  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-14 06:48:23.492  3854  3854 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-14 06:48:23.503  3854  3854 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-14 06:48:23.508  3854  5368 I iu.UploadsManager: num queued entries: 0
,10-14 06:48:23.508  3854  5368 I iu.UploadsManager: num updated entries: 0
10-14 06:48:23.509  3854  5368 I iu.SyncManager: NEXT; no task
,10-14 06:48:23.510  3854  5811 I SystemUpdateService: active receiver: enabled
,10-14 06:48:23.512  3854  3854 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-14 06:48:23.513  3854  3854 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-14 06:48:23.515  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-14 06:48:23.518  5717  5717 D SprintDMHelper: simOperator: 
,10-14 06:48:23.518  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-14 06:48:23.519   509   922 E Netd    : netlink response contains error (No such file or directory)
10-14 06:48:23.520   928  2962 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
10-14 06:48:23.520   928  2962 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-14 06:48:23.529  5781  5781 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-14 06:48:23.535  3854  5811 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-14 06:48:23.540  3854  5811 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-14 06:48:23.540  3854  5811 I SystemUpdateService: now status is 0 (complete)
10-14 06:48:23.540  3854  5811 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 06:48:23.540  3854  5811 I SystemUpdateService: file has been verified
10-14 06:48:23.541  3854  5811 I SystemUpdateService: OTA package size = 21989297
,10-14 06:48:23.547  5781  5781 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-14 06:48:23.549  3854  5811 I SystemUpdateService: showing system update notification
,10-14 06:48:23.557  3854  3854 D SystemUpdateService: onDestroy
,10-14 06:48:23.649   928  2960 D wifi    : In wifi stop Hal
10-14 06:48:23.649   928  2960 D wifi    : halHandle = 0x7f66d11b80, mVM = 0x7f8334d140, mCls = 0x2018c2
10-14 06:48:23.649   928  5780 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,10-14 06:48:23.650   928  5780 D WifiHAL : Got a signal to exit!!!
10-14 06:48:23.650   928  5780 I WifiHAL : Exit wifi_event_loop
10-14 06:48:23.650   928  2960 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-14 06:48:23.650   928  2960 E WifiHAL : Event processing terminated
10-14 06:48:23.650   928  2960 D wifi    : In wifi cleaned up handler
10-14 06:48:23.650   928  2960 I WifiHAL : Internal cleanup completed
10-14 06:48:23.651  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:23.652  4981  4981 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 06:48:23.652  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:23.652  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:23.653  4053  4204 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-14 06:48:23.677   928  5780 D wifi    : set interface wlan0 flags (DOWN)
,10-14 06:48:23.677   928  2960 D WifiNative-HAL: HAL event thread stopped successfully
,10-14 06:48:23.884   928   945 D Tethering: InitialState.processMessage what=4
,10-14 06:48:23.889   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-14 06:48:24.338   928  2962 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-14 06:48:28.427   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e91d0d0:true
,10-14 06:48:28.428  5703  5703 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 06:48:28.433  5703  5703 I bt_bluedroid: init
,10-14 06:48:28.433  5703  5818 I BluetoothAdapterState: Entering OffState
,10-14 06:48:28.437  5703  5819 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-14 06:48:28.437  5703  5819 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 06:48:28.437  5703  5819 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-14 06:48:28.438  5703  5819 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-14 06:48:28.439  5703  5703 I bt_bluedroid: get_profile_interface socket
10-14 06:48:28.442  5703  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 06:48:28.442  5703  5703 I bt_bluedroid: get_profile_interface sdp
,10-14 06:48:28.446  5703  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 06:48:28.451  5703  5714 I bt_bluedroid: config_hci_snoop_log
,10-14 06:48:28.452   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-14 06:48:28.459  5703  5818 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 06:48:28.459  5703  5818 D BluetoothAdapterProperties: Setting state to 14
,10-14 06:48:28.459  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-14 06:48:28.462  5703  5818 D BluetoothBondStateMachine: make
,10-14 06:48:28.465  5703  5823 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 06:48:28.469  5703  5818 I BluetoothAdapterState: Entering PendingCommandState
,10-14 06:48:28.470  5703  5703 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-14 06:48:28.474  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:28.475  5703  5703 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 06:48:28.477  5703  5703 D BtGatt.GattService: Received start request. Starting profile...
,10-14 06:48:28.477  5703  5703 D BtGatt.GattService: start()
10-14 06:48:28.477  5703  5703 I bt_bluedroid: get_profile_interface gatt
,10-14 06:48:28.478  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:28.479  5703  5703 D BtGatt.AdvertiseManager: advertise manager created
,10-14 06:48:28.487  5703  5703 V BluetoothAdapterState: isTurningOff()=false
,10-14 06:48:28.487  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:28.487  5703  5703 V BluetoothAdapterState: isBleTurningOn()=true
10-14 06:48:28.487  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:28.488  5703  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 06:48:28.490  5703  5818 I bt_bluedroid: bt_bluedroid
,10-14 06:48:28.490  5703  5819 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-14 06:48:28.491  5703  5819 I bt_hci  : start_up
,10-14 06:48:28.500  5703  5819 I bt_vendor: alloc value 0xf406c871
,10-14 06:48:28.501  5703  5819 I bt_vendor: init
10-14 06:48:28.501  5703  5819 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 06:48:28.501  5703  5819 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 06:48:28.614  5703  5819 D bt_hci  : start_up starting async portion
,10-14 06:48:28.615  5703  5826 I bt_hci  : event_finish_startup
10-14 06:48:28.615  5703  5826 I bt_hci_h4: hal_open
10-14 06:48:28.615  5703  5826 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-14 06:48:28.615  5827  5827 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-14 06:48:28.618  5703  5826 I bt_userial_vendor: device fd = 54 open
,10-14 06:48:28.633  5703  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 06:48:28.635  5703  5826 D bt_hwcfg: Chipset BCM4358A3
,10-14 06:48:28.635  5703  5826 D bt_hwcfg: Target name = [BCM4358A3]
10-14 06:48:28.636  5703  5826 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 06:48:29.009  5703  5826 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-14 06:48:29.010  5703  5826 D bt_hwcfg: Settlement delay -- 100 ms
10-14 06:48:29.010  5703  5826 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 06:48:29.143  5703  5826 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-14 06:48:29.144  5703  5826 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-14 06:48:29.145  5703  5826 I bt_hwcfg: vendor lib fwcfg completed
10-14 06:48:29.146  5703  5826 I bt_vendor: firmware callback
10-14 06:48:29.146  5703  5826 I bt_hci  : firmware_config_callback
,10-14 06:48:29.155  5703  5829 I bt_btu  : btu_task pending for preload complete event
,10-14 06:48:29.155  5703  5829 I bt_btu_task: Bluetooth chip preload is complete
10-14 06:48:29.155  5703  5829 I bt_btu  : btu_task received preload complete event
,10-14 06:48:29.163  5703  5829 I         : BTE_InitTraceLevels -- TRC_HCI
,10-14 06:48:29.163  5703  5829 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-14 06:48:29.163  5703  5829 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-14 06:48:29.163  5703  5829 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-14 06:48:29.164  5703  5829 I         : BTE_InitTraceLevels -- TRC_AVRC
10-14 06:48:29.164  5703  5829 I         : BTE_InitTraceLevels -- TRC_A2D
10-14 06:48:29.164  5703  5829 I         : BTE_InitTraceLevels -- TRC_BNEP
10-14 06:48:29.164  5703  5829 I         : BTE_InitTraceLevels -- TRC_BTM
10-14 06:48:29.164  5703  5829 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 06:48:29.165  5703  5829 I         : BTE_InitTraceLevels -- TRC_PAN
10-14 06:48:29.165  5703  5829 I         : BTE_InitTraceLevels -- TRC_SDP
10-14 06:48:29.165  5703  5829 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 06:48:29.165  5703  5829 I         : BTE_InitTraceLevels -- TRC_SMP
10-14 06:48:29.165  5703  5829 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-14 06:48:29.166  5703  5829 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 06:48:29.245  5703  5829 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fea549
,10-14 06:48:29.245  5703  5829 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fea549 
,10-14 06:48:29.258  5703  5822 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 06:48:29.260  5703  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 06:48:29.260  5703  5822 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 06:48:29.263  5703  5822 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 06:48:29.265  5703  5822 D BluetoothAdapterProperties: Scan Mode:20
10-14 06:48:29.266  5703  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 06:48:29.266  5703  5822 D bt_hci  : do_postload posting postload work item
10-14 06:48:29.266  5703  5826 I bt_hci  : event_postload
,10-14 06:48:29.266  5703  5826 I bt_vendor: sco_config_cb
10-14 06:48:29.267  5703  5826 I bt_hci  : sco_config_callback postload finished.
10-14 06:48:29.271  5703  5822 D bt_bte_conf: Device ID record 1 : primary
,10-14 06:48:29.271  5703  5822 D bt_bte_conf:   vendorId            = 000f
,10-14 06:48:29.271  5703  5822 D bt_bte_conf:   vendorIdSource      = 0001
10-14 06:48:29.271  5703  5822 D bt_bte_conf:   product             = 1200
10-14 06:48:29.271  5703  5822 D bt_bte_conf:   version             = 1436
10-14 06:48:29.271  5703  5822 D bt_bte_conf:   clientExecutableURL = 
,10-14 06:48:29.271  5703  5822 D bt_bte_conf:   serviceDescription  = 
10-14 06:48:29.271  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:29.271  5703  5822 D bt_bte_conf:   documentationURL    = 
10-14 06:48:29.272  5703  5822 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-14 06:48:29.272  5703  5819 D bt_stack_manager: event_start_up_stack finished
,10-14 06:48:29.275  5703  5826 I bt_vendor: low_power_mode_cb
10-14 06:48:29.275  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:29.278  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:29.279  5703  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 06:48:29.279  5703  5818 D BluetoothAdapterProperties: Setting state to 15
10-14 06:48:29.279  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-14 06:48:29.280  5703  5818 I BluetoothAdapterState: Entering BleOnState
,10-14 06:48:29.284  5703  5818 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-14 06:48:29.284  5703  5818 D BluetoothAdapterProperties: Setting state to 11
10-14 06:48:29.284  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-14 06:48:29.290  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:29.292  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:29.295  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:29.296  5703  5703 D HeadsetService: Received start request. Starting profile...
10-14 06:48:29.296  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:29.299  5703  5703 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-14 06:48:29.299  5703  5703 D HeadsetStateMachine: make
,10-14 06:48:29.308  5703  5818 I BluetoothAdapterState: Entering PendingCommandState
,10-14 06:48:29.311  5703  5703 D HeadsetStateMachine: max_hf_connections = 1
,10-14 06:48:29.311  5703  5703 I bt_bluedroid: get_profile_interface handsfree
10-14 06:48:29.311  5703  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-14 06:48:29.312  5703  5822 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-14 06:48:29.314  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:29.315  5703  5703 D A2dpService: Received start request. Starting profile...
,10-14 06:48:29.316  5703  5703 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-14 06:48:29.316  5703  5703 I bt_bluedroid: get_profile_interface avrcp
,10-14 06:48:29.321  5703  5703 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-14 06:48:29.322  5703  5703 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-14 06:48:29.322  5703  5703 D A2dpStateMachine: make
10-14 06:48:29.323  5703  5703 I bt_bluedroid: get_profile_interface a2dp
,10-14 06:48:29.323  5703  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-14 06:48:29.324  5703  5838 D A2dpStateMachine: Enter Disconnected: -2
,10-14 06:48:29.325  5703  5703 I BluetoothHidServiceJni: classInitNative: succeeds
,10-14 06:48:29.326  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:29.327  5642  5642 D BluetoothInputDevice: Proxy object connected
10-14 06:48:29.327  5703  5703 D HidService: Received start request. Starting profile...
10-14 06:48:29.328  5703  5703 I bt_bluedroid: get_profile_interface hidhost
10-14 06:48:29.328  5703  5703 D HidService: setHidService(): set to: null
10-14 06:48:29.328  5703  5822 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3fcb56d
10-14 06:48:29.328  5642  5642 D HidProfile: Bluetooth service connected
10-14 06:48:29.328  5703  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-14 06:48:29.329  5703  5703 I BluetoothHealthServiceJni: classInitNative: succeeds
10-14 06:48:29.330  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:29.331  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 06:48:29.331  5703  5703 D HealthService: Received start request. Starting profile...
,10-14 06:48:29.332  5703  5703 I bt_bluedroid: get_profile_interface health
,10-14 06:48:29.333  5703  5703 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-14 06:48:29.334  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:29.335  5642  5642 D BluetoothPan: BluetoothPAN Proxy object connected
,10-14 06:48:29.336  5642  5642 D PanProfile: Bluetooth service connected
10-14 06:48:29.336  5703  5703 D PanService: Received start request. Starting profile...
10-14 06:48:29.336  5703  5703 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 06:48:29.336  5703  5703 I bt_bluedroid: get_profile_interface pan
,10-14 06:48:29.338  5703  5822 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-14 06:48:29.340  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:29.342  5642  5642 D BluetoothMap: Proxy object connected
,10-14 06:48:29.342  5642  5642 D MapProfile: Bluetooth service connected
10-14 06:48:29.342  5642  5642 D BluetoothMap: getConnectedDevices()
10-14 06:48:29.343  5703  5703 D BluetoothMapService: Received start request. Starting profile...
10-14 06:48:29.343  5703  5703 D BluetoothMapService: start()
10-14 06:48:29.346  5703  5703 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-14 06:48:29.346  5703  5703 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 06:48:29.347  5703  5703 D BluetoothMapAppObserver: createReceiver()
,10-14 06:48:29.348  5703  5703 D BluetoothMapAppObserver: initObservers()
,10-14 06:48:29.348  5703  5703 D BluetoothMapAppObserver: getEnabledAccountItems()
10-14 06:48:29.354  5703  5703 V SapService: SapBinder()
10-14 06:48:29.354  5703  5703 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:29.355  5703  5703 D SapService: Received start request. Starting profile...
10-14 06:48:29.355  5703  5703 V SapService: start()
10-14 06:48:29.358  5703  5703 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:29.358  5703  5703 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:29.358  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:29.358  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isTurningOn()=true
,10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:29.359  5703  5836 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isTurningOn()=true
,10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:29.359  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:29.360  5703  5703 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:29.360  5703  5703 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:29.360  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:29.360  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:29.360  5703  5703 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:29.361  5703  5703 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:29.361  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 06:48:29.361  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 06:48:29.362  5703  5703 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:29.362  5703  5703 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:29.362  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:29.362  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:29.362  5703  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-14 06:48:29.362  5703  5818 D BluetoothAdapterProperties: ScanMode =  20
10-14 06:48:29.362  5703  5818 D BluetoothAdapterProperties: State =  11
10-14 06:48:29.364  5642  5642 D BluetoothMap: Bluetooth is Not enabled
10-14 06:48:29.365  5703  5822 D BluetoothAdapterProperties: Scan Mode:21
10-14 06:48:29.365  5703  5822 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 06:48:29.365  5703  5818 D BluetoothAdapterProperties: Setting state to 12
10-14 06:48:29.365  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 06:48:29.365  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-14 06:48:29.366  5703  5818 I BluetoothAdapterState: Entering OnState
10-14 06:48:29.366  5642  5655 D BluetoothPan: onBluetoothStateChange on: true
10-14 06:48:29.366  3103  3121 D BluetoothMap: onBluetoothStateChange: up=true
10-14 06:48:29.368  3103  3103 D BluetoothMap: Proxy object connected
10-14 06:48:29.369  3103  3103 D MapProfile: Bluetooth service connected
10-14 06:48:29.369  3766  3788 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:29.369  3103  3103 D BluetoothMap: getConnectedDevices()
10-14 06:48:29.369  3103  3959 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:29.369  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:29.371  3103  3103 D BluetoothInputDevice: Proxy object connected
10-14 06:48:29.371  5642  5658 D BluetoothMap: onBluetoothStateChange: up=true
10-14 06:48:29.371  3103  3103 D HidProfile: Bluetooth service connected
10-14 06:48:29.371  5642  5655 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 06:48:29.371  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:29.372  3103  3959 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 06:48:29.373   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-14 06:48:29.373   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:29.374  3103  3115 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 06:48:29.374  5703  5703 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 06:48:29.375  5703  5703 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-14 06:48:29.376   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:29.376  5642  5658 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:29.376  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:29.376  5703  5703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 06:48:29.377  3103  3121 D BluetoothPan: onBluetoothStateChange on: true
10-14 06:48:29.378  5703  5703 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 06:48:29.379  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:29.379  3103  3103 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 06:48:29.379  3103  3103 D PanProfile: Bluetooth service connected
10-14 06:48:29.379  3103  3115 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:29.380   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 06:48:29.380  5703  5703 D ObexServerSockets: Succeed to create listening sockets 
10-14 06:48:29.380  5703  5703 D ObexServerSockets0: startAccept()
,10-14 06:48:29.380  5703  5703 D ObexServerSockets0: prepareForNewConnect()
10-14 06:48:29.383   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 06:48:29.384  5642  5642 D LocalBluetoothProfileManager: Adding local A2DP profile
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:29.385  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:29.387  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:29.387  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 06:48:29.388  5642  5642 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-14 06:48:29.389  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:29.390  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:29.391  5703  5703 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-14 06:48:29.391  5703  5703 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-14 06:48:29.392  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:29.394  5703  5843 D ObexServerSockets0: Accepting socket connection...
10-14 06:48:29.394   928   928 D BluetoothA2dp: Proxy object connected
10-14 06:48:29.394  3103  3103 D BluetoothA2dp: Proxy object connected
,10-14 06:48:29.395  5703  5844 D ObexServerSockets0: Accepting socket connection...
,10-14 06:48:29.397  5703  5703 D BluetoothMapService: onReceive
10-14 06:48:29.397  5703  5703 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 06:48:29.397  5703  5703 D BluetoothMapService: STATE_ON
,10-14 06:48:29.397  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 06:48:29.400  5703  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 06:48:29.400  5642  5642 D BluetoothA2dp: Proxy object connected
,10-14 06:48:29.402  5703  5846 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-14 06:48:29.403  5703  5846 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-14 06:48:29.406  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 06:48:29.407  5642  5642 D DockEventReceiver: finishStartingService: stopping service
,10-14 06:48:29.413  5642  5642 D BluetoothPbap: Proxy object connected
,10-14 06:48:29.413  5642  5642 D PbapServerProfile: Bluetooth service connected
,10-14 06:48:29.415  3103  3103 D BluetoothPbap: Proxy object connected
,10-14 06:48:29.415  3103  3103 D PbapServerProfile: Bluetooth service connected
,10-14 06:48:29.422  5703  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 06:48:29.432  5703  5703 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-14 06:48:29.432  5703  5703 D ObexServerSockets0: prepareForNewConnect()
,10-14 06:48:29.436  5703  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 06:48:29.437  5703  5854 I BtOppRfcommListener: Accept thread started.
,10-14 06:48:29.470   928   928 D BluetoothHeadset: Proxy object connected
,10-14 06:48:29.470  3103  3121 D BluetoothHeadset: Proxy object connected
10-14 06:48:29.470  3103  3103 D HeadsetProfile: Bluetooth service connected
10-14 06:48:29.470  3766  3784 D BluetoothHeadset: Proxy object connected
10-14 06:48:29.471   928   928 D BluetoothHeadset: Proxy object connected
10-14 06:48:29.471   928   928 D BluetoothHeadset: Proxy object connected
,10-14 06:48:29.474   928   945 D BluetoothHeadset: Proxy object connected
,10-14 06:48:29.474   928   945 D BluetoothHeadset: Proxy object connected
10-14 06:48:29.475   928   945 D BluetoothHeadset: Proxy object connected
,10-14 06:48:29.480  3103  3959 D BluetoothHeadset: Proxy object connected
10-14 06:48:29.480  3103  3103 D HeadsetProfile: Bluetooth service connected
,10-14 06:48:29.491  5642  5655 D BluetoothHeadset: Proxy object connected
10-14 06:48:29.493  5642  5642 D HeadsetProfile: Bluetooth service connected
,10-14 06:48:31.296   928  2962 D ConnectivityService: handlePromptUnvalidated 101
,10-14 06:48:33.404  5703  5818 D BluetoothAdapterState: Current state: ON, message: 23
,10-14 06:48:33.404  5703  5818 D BluetoothAdapterProperties: Setting state to 13
10-14 06:48:33.404  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-14 06:48:33.405  5703  5818 D BluetoothAdapterProperties: onBluetoothDisable()
10-14 06:48:33.407  5703  5818 I BluetoothAdapterState: Entering PendingCommandState
,10-14 06:48:33.411  5703  5703 D BluetoothMapService: onReceive
10-14 06:48:33.411  5703  5703 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-14 06:48:33.411  5703  5703 D BluetoothMapService: STATE_TURNING_OFF
10-14 06:48:33.411  5703  5703 D BluetoothMapService: MAP Service closeService in
10-14 06:48:33.412  5703  5703 D BluetoothMapMasInstance0: MAP Service shutdown
10-14 06:48:33.412  5703  5703 D ObexServerSockets0: shutdown(block = true)
10-14 06:48:33.412  5703  5703 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 06:48:33.413  5703  5703 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-14 06:48:33.413  5703  5843 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-14 06:48:33.413  5703  5844 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-14 06:48:33.414  5703  5831 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-14 06:48:33.420  5703  5822 D BluetoothAdapterProperties: Scan Mode:20
10-14 06:48:33.421  5703  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-14 06:48:33.422  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:33.422  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:33.423  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 06:48:33.423  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:33.423  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:33.426  5703  5703 D HeadsetService: Received stop request...Stopping profile...
,10-14 06:48:33.428  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:33.429  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:33.430   928   928 D BluetoothHeadset: Proxy object disconnected
,10-14 06:48:33.431  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:33.431  5703  5703 I BtOppRfcommListener: stopping Accept Thread
,10-14 06:48:33.431  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:33.431  5703  5854 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-14 06:48:33.432  3103  3959 D BluetoothHeadset: Proxy object disconnected
,10-14 06:48:33.432  5703  5854 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-14 06:48:33.432  3766  3788 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:33.433   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:33.433   928   928 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:33.433  5642  5642 D DockEventReceiver: finishStartingService: stopping service
10-14 06:48:33.434  5642  5655 D BluetoothHeadset: Proxy object disconnected
10-14 06:48:33.435  5703  5703 D A2dpService: Received stop request...Stopping profile...
10-14 06:48:33.435  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:33.435  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:33.435  5703  5838 D A2dpStateMachine: Exit Disconnected: -1
10-14 06:48:33.436  5589  5589 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-14 06:48:33.436  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:33.437  5642  5642 D HeadsetProfile: Bluetooth service disconnected
10-14 06:48:33.438  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.439  5642  5642 D BluetoothA2dp: Proxy object disconnected
10-14 06:48:33.439   928   928 D BluetoothA2dp: Proxy object disconnected
10-14 06:48:33.439  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.440  5703  5703 D HidService: Received stop request...Stopping profile...
10-14 06:48:33.440  5703  5703 D HidService: Stopping Bluetooth HidService
,10-14 06:48:33.441  5703  5703 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:33.442  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:33.442  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:33.442  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:33.443  5642  5642 D BluetoothInputDevice: Proxy object disconnected
10-14 06:48:33.443  5642  5642 D HidProfile: Bluetooth service disconnected
10-14 06:48:33.445  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 06:48:33.445  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.445  3103  3103 D HeadsetProfile: Bluetooth service disconnected
10-14 06:48:33.445  3103  3103 D BluetoothA2dp: Proxy object disconnected
10-14 06:48:33.445  5703  5703 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-14 06:48:33.446  5703  5703 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-14 06:48:33.446  3103  3103 D BluetoothInputDevice: Proxy object disconnected
10-14 06:48:33.446  3103  3103 D HidProfile: Bluetooth service disconnected
10-14 06:48:33.446  5703  5703 D HealthService: Received stop request...Stopping profile...
10-14 06:48:33.446  5703  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:33.446  5703  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:33.446  5703  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:33.447  5703  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-14 06:48:33.447  5703  5822 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-14 06:48:33.449  5703  5703 D PanService: Received stop request...Stopping profile...
10-14 06:48:33.450  3103  3103 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 06:48:33.450  3103  3103 D PanProfile: Bluetooth service disconnected
10-14 06:48:33.450  5703  5703 D BluetoothMapService: Received stop request...Stopping profile...
10-14 06:48:33.451  5703  5703 D BluetoothMapService: stop()
,10-14 06:48:33.451  5703  5703 D BluetoothMapAppObserver: deinitObservers()
10-14 06:48:33.451  5703  5703 D BluetoothMapAppObserver: removeReceiver()
10-14 06:48:33.451  5642  5642 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-14 06:48:33.451  5642  5642 D PanProfile: Bluetooth service disconnected
10-14 06:48:33.452  5642  5642 D BluetoothMap: Proxy object disconnected
10-14 06:48:33.452  5642  5642 D MapProfile: Bluetooth service disconnected
,10-14 06:48:33.453  3103  3103 D BluetoothMap: Proxy object disconnected
10-14 06:48:33.453  3103  3103 D MapProfile: Bluetooth service disconnected
10-14 06:48:33.453  5703  5703 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:33.453  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:33.453  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 06:48:33.453  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:33.454  5703  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-14 06:48:33.454  5703  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:33.454  5703  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:33.455  5703  5829 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 06:48:33.455  5703  5829 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 06:48:33.455  5703  5829 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-14 06:48:33.455  5703  5829 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-14 06:48:33.455  5703  5703 D SapService: Received stop request...Stopping profile...
10-14 06:48:33.455  5703  5703 V SapService: stop()
10-14 06:48:33.457  5703  5703 V BluetoothAdapterState: isTurningOff()=true
,10-14 06:48:33.457  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:33.457  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:33.457  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:33.457  5703  5703 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-14 06:48:33.457  5703  5703 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-14 06:48:33.457  5703  5822 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-14 06:48:33.459  3103  3103 D BluetoothPbap: Proxy object disconnected
10-14 06:48:33.459  3103  3103 D PbapServerProfile: Bluetooth service disconnected
,10-14 06:48:33.459  5703  5703 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:33.459  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:33.459  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:33.459  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:33.460  5703  5703 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-14 06:48:33.461  5703  5822 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-14 06:48:33.461  5703  5703 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-14 06:48:33.461  5703  5703 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:33.461  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:33.461  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:33.461  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:33.461  5703  5703 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-14 06:48:33.461  5703  5703 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-14 06:48:33.462  5703  5703 D BluetoothMapService: MAP Service closeService in
10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:33.462  5703  5703 D BluetoothMapService: cleanup()
10-14 06:48:33.462  5703  5703 D BluetoothMapService: MAP Service closeService in
10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isTurningOff()=true
10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isTurningOn()=false
,10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:33.462  5703  5703 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:33.463  5703  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-14 06:48:33.463  5703  5818 D BluetoothAdapterProperties: Setting state to 15
10-14 06:48:33.463  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-14 06:48:33.463  5642  5655 D BluetoothPan: onBluetoothStateChange on: false
10-14 06:48:33.464  3103  3121 D BluetoothMap: onBluetoothStateChange: up=false
10-14 06:48:33.464  3766  3784 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:33.465  3103  3959 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 06:48:33.465  5703  5818 I BluetoothAdapterState: Entering BleOnState
10-14 06:48:33.465  5642  5658 D BluetoothMap: onBluetoothStateChange: up=false
10-14 06:48:33.466  5642  5655 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-14 06:48:33.466  3103  3115 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 06:48:33.467   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:33.467   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-14 06:48:33.467  3103  3121 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-14 06:48:33.467   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:33.468  5642  5658 D BluetoothPbap: onBluetoothStateChange: up=false
10-14 06:48:33.470  5642  5655 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:33.470  3103  3115 D BluetoothPan: onBluetoothStateChange on: false
10-14 06:48:33.471  3103  3959 D BluetoothHeadset: onBluetoothStateChange: up=false
10-14 06:48:33.471  5642  5658 D BluetoothA2dp: onBluetoothStateChange: up=false
10-14 06:48:33.472   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-14 06:48:33.472  5703  5818 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-14 06:48:33.472  5703  5818 D BluetoothAdapterProperties: Setting state to 16
10-14 06:48:33.472  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-14 06:48:33.472  5642  5642 D BluetoothPbap: Proxy object disconnected
10-14 06:48:33.472  5642  5642 D PbapServerProfile: Bluetooth service disconnected
10-14 06:48:33.473  5703  5818 D BluetoothAdapterProperties: onBleDisable
10-14 06:48:33.473  5703  5818 I BluetoothAdapterState: Entering PendingCommandState
10-14 06:48:33.473  5703  5819 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-14 06:48:33.474  5703  5829 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-14 06:48:33.474  5703  5829 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-14 06:48:33.475  5703  5822 D BluetoothAdapterProperties: Scan Mode:20
10-14 06:48:33.476  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-14 06:48:33.476  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.478  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.479  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.481  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.482  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:33.484  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:33.484  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 06:48:33.488  5642  5642 D DockEventReceiver: finishStartingService: stopping service
,10-14 06:48:33.679  5703  5822 I bt_hci  : shut_down
,10-14 06:48:33.682  5703  5826 D bt_hwcfg: hw_epilog_process
,10-14 06:48:33.682  5703  5826 I bt_vendor: low_power_mode_cb
,10-14 06:48:33.685  5703  5826 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-14 06:48:33.685  5703  5826 I bt_vendor: epilog_cb
10-14 06:48:33.685  5703  5826 I bt_hci  : epilog_finished_callback
,10-14 06:48:33.687  5703  5822 I bt_hci_h4: hal_close
10-14 06:48:33.687  5703  5822 I bt_userial_vendor: device fd = 54 close
,10-14 06:48:33.792  5703  5819 D bt_stack_manager: event_shut_down_stack finished.
,10-14 06:48:33.793  5703  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-14 06:48:33.797  5703  5703 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-14 06:48:33.797  5703  5818 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-14 06:48:33.798  5703  5703 D BtGatt.GattService: Received stop request...Stopping profile...
10-14 06:48:33.798  5703  5703 D BtGatt.GattService: stop()
10-14 06:48:33.798  5703  5703 D BtGatt.AdvertiseManager: advertise clients cleared
,10-14 06:48:33.802  5703  5703 V BluetoothAdapterState: isTurningOff()=false
,10-14 06:48:33.802  5703  5703 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:33.802  5703  5703 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:33.802  5703  5703 V BluetoothAdapterState: isBleTurningOff()=true
10-14 06:48:33.803  5703  5818 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-14 06:48:33.803  5703  5818 D BluetoothAdapterProperties: Setting state to 10
10-14 06:48:33.803  5703  5818 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-14 06:48:33.805  5703  5818 I BluetoothAdapterState: Entering OffState
,10-14 06:48:33.805   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-14 06:48:33.815  5703  5703 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-14 06:48:33.815  5703  5703 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-14 06:48:33.815  5703  5703 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-14 06:48:33.817  5703  5819 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-14 06:48:33.821  5703  5703 I art     : System.exit called, status: 0
,10-14 06:48:33.821  5703  5703 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-14 06:48:33.847   928  3401 I ActivityManager: Process com.android.bluetooth (pid 5703) has died
,10-14 06:48:34.327   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:35.328   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:36.329   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:37.330   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:38.331   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:48:38.401  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 06:48:38.401  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:38.406  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:38.407  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7262d20 removed from the list
10-14 06:48:38.407  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 06:48:38.407  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:48:38.407  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:38.409  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:38.409  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e9d89e added. We now have 4 listener(s)
10-14 06:48:38.410  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:38.412  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:38.412  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e9d89e removed from the list
10-14 06:48:38.413  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:38.413  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:38.413  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:38.415  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-14 06:48:38.415  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c58f7f added. We now have 4 listener(s)
10-14 06:48:38.415  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:39.331   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-14 06:48:43.428  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:43.463   928   945 I ActivityManager: Start proc 5862:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-14 06:48:43.541  5862  5862 D AdapterServiceConfig: Adding HeadsetService
,10-14 06:48:43.541  5862  5862 D AdapterServiceConfig: Adding A2dpService
10-14 06:48:43.541  5862  5862 D AdapterServiceConfig: Adding HidService
10-14 06:48:43.541  5862  5862 D AdapterServiceConfig: Adding HealthService
10-14 06:48:43.541  5862  5862 D AdapterServiceConfig: Adding PanService
10-14 06:48:43.542  5862  5862 D AdapterServiceConfig: Adding GattService
10-14 06:48:43.542  5862  5862 D AdapterServiceConfig: Adding BluetoothMapService
10-14 06:48:43.542  5862  5862 D AdapterServiceConfig: Adding SapService
,10-14 06:48:43.553   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@559689:true
,10-14 06:48:43.553  5862  5862 D BluetoothAdapterState: make() - Creating AdapterState
,10-14 06:48:43.556  5862  5862 I bt_bluedroid: init
10-14 06:48:43.556  5862  5874 I BluetoothAdapterState: Entering OffState
,10-14 06:48:43.559  5862  5875 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-14 06:48:43.559  5862  5875 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-14 06:48:43.559  5862  5875 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-14 06:48:43.559  5862  5875 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-14 06:48:43.560  5862  5862 I bt_bluedroid: get_profile_interface socket
,10-14 06:48:43.562  5862  5878 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-14 06:48:43.562  5862  5862 I bt_bluedroid: get_profile_interface sdp
,10-14 06:48:43.564  5862  5878 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 06:48:43.569  5862  5873 I bt_bluedroid: config_hci_snoop_log
10-14 06:48:43.570   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-14 06:48:43.574  5862  5874 D BluetoothAdapterState: Current state: OFF, message: 0
,10-14 06:48:43.575  5862  5874 D BluetoothAdapterProperties: Setting state to 14
,10-14 06:48:43.586  5862  5874 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-14 06:48:43.588  5862  5874 D BluetoothBondStateMachine: make
,10-14 06:48:43.594  5862  5879 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-14 06:48:43.599  5862  5874 I BluetoothAdapterState: Entering PendingCommandState
10-14 06:48:43.599  5862  5862 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-14 06:48:43.601  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:43.602  5862  5862 D BtGatt.DebugUtils: handleDebugAction() action=null
10-14 06:48:43.602  5862  5862 D BtGatt.GattService: Received start request. Starting profile...
10-14 06:48:43.602  5862  5862 D BtGatt.GattService: start()
10-14 06:48:43.602  5862  5862 I bt_bluedroid: get_profile_interface gatt
,10-14 06:48:43.603  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:43.603  5862  5862 D BtGatt.AdvertiseManager: advertise manager created
,10-14 06:48:43.610  5862  5862 V BluetoothAdapterState: isTurningOff()=false
,10-14 06:48:43.610  5862  5862 V BluetoothAdapterState: isTurningOn()=false
10-14 06:48:43.610  5862  5862 V BluetoothAdapterState: isBleTurningOn()=true
10-14 06:48:43.610  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:43.611  5862  5874 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-14 06:48:43.612  5862  5874 I bt_bluedroid: bt_bluedroid
10-14 06:48:43.612  5862  5875 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-14 06:48:43.613  5862  5875 I bt_hci  : start_up
,10-14 06:48:43.620  5862  5875 I bt_vendor: alloc value 0xf40bf871
10-14 06:48:43.621  5862  5875 I bt_vendor: init
,10-14 06:48:43.621  5862  5875 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-14 06:48:43.621  5862  5875 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-14 06:48:43.732  5862  5875 D bt_hci  : start_up starting async portion
10-14 06:48:43.732  5862  5882 I bt_hci  : event_finish_startup
,10-14 06:48:43.732  5862  5882 I bt_hci_h4: hal_open
10-14 06:48:43.732  5862  5882 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-14 06:48:43.732  5883  5883 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 06:48:43.735  5862  5882 I bt_userial_vendor: device fd = 54 open
,10-14 06:48:43.752  5862  5882 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 06:48:43.756  5862  5882 D bt_hwcfg: Chipset BCM4358A3
,10-14 06:48:43.756  5862  5882 D bt_hwcfg: Target name = [BCM4358A3]
10-14 06:48:43.757  5862  5882 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-14 06:48:44.170  5862  5882 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-14 06:48:44.171  5862  5882 D bt_hwcfg: Settlement delay -- 100 ms
10-14 06:48:44.171  5862  5882 I bt_hwcfg: Setting fw settlement delay to 100 
,10-14 06:48:44.305  5862  5882 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-14 06:48:44.305  5862  5882 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-14 06:48:44.307  5862  5882 I bt_hwcfg: vendor lib fwcfg completed
,10-14 06:48:44.307  5862  5882 I bt_vendor: firmware callback
,10-14 06:48:44.307  5862  5882 I bt_hci  : firmware_config_callback
,10-14 06:48:44.318  5862  5885 I bt_btu  : btu_task pending for preload complete event
,10-14 06:48:44.318  5862  5885 I bt_btu_task: Bluetooth chip preload is complete
,10-14 06:48:44.318  5862  5885 I bt_btu  : btu_task received preload complete event
,10-14 06:48:44.326  5862  5885 I         : BTE_InitTraceLevels -- TRC_HCI
10-14 06:48:44.326  5862  5885 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_AVDT
10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_AVRC
10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_A2D
,10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_BNEP
10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_BTM
10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_GAP
10-14 06:48:44.327  5862  5885 I         : BTE_InitTraceLevels -- TRC_PAN
,10-14 06:48:44.328  5862  5885 I         : BTE_InitTraceLevels -- TRC_SDP
10-14 06:48:44.328  5862  5885 I         : BTE_InitTraceLevels -- TRC_GATT
10-14 06:48:44.328  5862  5885 I         : BTE_InitTraceLevels -- TRC_SMP
10-14 06:48:44.328  5862  5885 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-14 06:48:44.328  5862  5885 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-14 06:48:44.410  5862  5885 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf403d549
,10-14 06:48:44.411  5862  5885 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf403d549 
,10-14 06:48:44.426  5862  5878 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-14 06:48:44.427  5862  5878 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-14 06:48:44.428  5862  5878 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-14 06:48:44.431  5862  5878 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-14 06:48:44.434  5862  5878 D BluetoothAdapterProperties: Scan Mode:20
,10-14 06:48:44.434  5862  5878 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 06:48:44.435  5862  5878 D bt_hci  : do_postload posting postload work item
10-14 06:48:44.435  5862  5882 I bt_hci  : event_postload
,10-14 06:48:44.435  5862  5882 I bt_vendor: sco_config_cb
10-14 06:48:44.435  5862  5882 I bt_hci  : sco_config_callback postload finished.
10-14 06:48:44.438  5862  5878 D bt_bte_conf: Device ID record 1 : primary
10-14 06:48:44.438  5862  5878 D bt_bte_conf:   vendorId            = 000f
10-14 06:48:44.438  5862  5878 D bt_bte_conf:   vendorIdSource      = 0001
10-14 06:48:44.439  5862  5878 D bt_bte_conf:   product             = 1200
10-14 06:48:44.439  5862  5878 D bt_bte_conf:   version             = 1436
10-14 06:48:44.439  5862  5878 D bt_bte_conf:   clientExecutableURL = 
10-14 06:48:44.439  5862  5878 D bt_bte_conf:   serviceDescription  = 
,10-14 06:48:44.439  5862  5878 D bt_bte_conf:   documentationURL    = 
10-14 06:48:44.439  5862  5878 D bt_bte_conf: bte_load_did_conf no section named DID2.
,10-14 06:48:44.440  5862  5875 D bt_stack_manager: event_start_up_stack finished
10-14 06:48:44.442  5862  5874 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-14 06:48:44.443  5862  5874 D BluetoothAdapterProperties: Setting state to 15
10-14 06:48:44.443  5862  5874 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-14 06:48:44.445  5862  5874 I BluetoothAdapterState: Entering BleOnState
,10-14 06:48:44.447  5862  5882 I bt_vendor: low_power_mode_cb
10-14 06:48:44.448  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:44.450  5862  5874 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-14 06:48:44.450  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:44.450  5862  5874 D BluetoothAdapterProperties: Setting state to 11
10-14 06:48:44.450  5862  5874 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-14 06:48:44.456  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:44.457  5862  5862 D HeadsetService: Received start request. Starting profile...
,10-14 06:48:44.460  5862  5862 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-14 06:48:44.460  5862  5862 D HeadsetStateMachine: make
,10-14 06:48:44.468  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:44.470  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:44.472  5862  5874 I BluetoothAdapterState: Entering PendingCommandState
,10-14 06:48:44.476  5862  5862 D HeadsetStateMachine: max_hf_connections = 1
,10-14 06:48:44.476  5862  5862 I bt_bluedroid: get_profile_interface handsfree
10-14 06:48:44.477  5862  5878 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-14 06:48:44.477  5862  5878 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-14 06:48:44.479  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:44.480  5862  5862 D A2dpService: Received start request. Starting profile...
10-14 06:48:44.480  5862  5862 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-14 06:48:44.481  5862  5862 I bt_bluedroid: get_profile_interface avrcp
,10-14 06:48:44.486  5862  5862 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-14 06:48:44.486  5862  5862 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-14 06:48:44.486  5862  5862 D A2dpStateMachine: make
10-14 06:48:44.487  5862  5862 I bt_bluedroid: get_profile_interface a2dp
,10-14 06:48:44.487  5862  5878 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-14 06:48:44.489  5862  5893 D A2dpStateMachine: Enter Disconnected: -2
,10-14 06:48:44.489  5862  5862 I BluetoothHidServiceJni: classInitNative: succeeds
,10-14 06:48:44.490  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:44.491  5862  5862 D HidService: Received start request. Starting profile...
,10-14 06:48:44.491  5862  5862 I bt_bluedroid: get_profile_interface hidhost
10-14 06:48:44.491  5862  5862 D HidService: setHidService(): set to: null
10-14 06:48:44.491  5862  5878 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf401e56d
10-14 06:48:44.491  5862  5878 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-14 06:48:44.492  5862  5862 I BluetoothHealthServiceJni: classInitNative: succeeds
10-14 06:48:44.493  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:44.493  5862  5862 D HealthService: Received start request. Starting profile...
,10-14 06:48:44.495  5862  5862 I bt_bluedroid: get_profile_interface health
10-14 06:48:44.495  5862  5862 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-14 06:48:44.496  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:44.497  5862  5862 D PanService: Received start request. Starting profile...
10-14 06:48:44.497  5862  5862 D BluetoothPanServiceJni: initializeNative(L110): pan
10-14 06:48:44.497  5862  5862 I bt_bluedroid: get_profile_interface pan
10-14 06:48:44.497  5862  5878 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-14 06:48:44.499  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:44.500  5862  5862 D BluetoothMapService: Received start request. Starting profile...
10-14 06:48:44.500  5862  5862 D BluetoothMapService: start()
,10-14 06:48:44.502  5862  5862 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-14 06:48:44.503  5862  5862 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-14 06:48:44.503  5862  5862 D BluetoothMapAppObserver: createReceiver()
,10-14 06:48:44.504  5862  5862 D BluetoothMapAppObserver: initObservers()
,10-14 06:48:44.504  5862  5862 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-14 06:48:44.511  5862  5862 V SapService: SapBinder()
,10-14 06:48:44.511  5862  5862 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
,10-14 06:48:44.512  5862  5862 D SapService: Received start request. Starting profile...
10-14 06:48:44.512  5862  5862 V SapService: start()
,10-14 06:48:44.514  5862  5862 V BluetoothAdapterState: isTurningOff()=false
,10-14 06:48:44.514  5862  5862 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isTurningOff()=false
,10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isTurningOn()=true
,10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:44.515  5862  5891 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:44.515  5862  5862 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:44.516  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:44.516  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:44.517  5862  5862 V BluetoothAdapterState: isTurningOff()=false
,10-14 06:48:44.517  5862  5862 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:44.517  5862  5862 V BluetoothAdapterState: isBleTurningOn()=false
,10-14 06:48:44.517  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
,10-14 06:48:44.518  5862  5862 V BluetoothAdapterState: isTurningOff()=false
10-14 06:48:44.518  5862  5862 V BluetoothAdapterState: isTurningOn()=true
10-14 06:48:44.518  5862  5862 V BluetoothAdapterState: isBleTurningOn()=false
10-14 06:48:44.518  5862  5862 V BluetoothAdapterState: isBleTurningOff()=false
10-14 06:48:44.518  5862  5874 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-14 06:48:44.518  5862  5874 D BluetoothAdapterProperties: ScanMode =  20
10-14 06:48:44.518  5862  5874 D BluetoothAdapterProperties: State =  11
10-14 06:48:44.519  5862  5874 D BluetoothAdapterProperties: Setting state to 12
,10-14 06:48:44.519  5862  5874 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-14 06:48:44.519  5862  5874 I BluetoothAdapterState: Entering OnState
,10-14 06:48:44.520  5642  5658 D BluetoothPan: onBluetoothStateChange on: true
,10-14 06:48:44.522  5862  5878 D BluetoothAdapterProperties: Scan Mode:21
,10-14 06:48:44.522  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 06:48:44.522  5862  5878 D BluetoothAdapterProperties: Discoverable Timeout:120
10-14 06:48:44.522  3103  3121 D BluetoothMap: onBluetoothStateChange: up=true
10-14 06:48:44.525  3766  3977 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:44.525  3103  3115 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 06:48:44.526  3103  3103 D BluetoothMap: Proxy object connected
10-14 06:48:44.526  3103  3103 D MapProfile: Bluetooth service connected
10-14 06:48:44.526  3103  3103 D BluetoothMap: getConnectedDevices()
10-14 06:48:44.527  5642  5658 D BluetoothMap: onBluetoothStateChange: up=true
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:44.527  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:44.529  5642  5655 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-14 06:48:44.530  5862  5862 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-14 06:48:44.530  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:44.530  5862  5862 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-14 06:48:44.531  3103  3115 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 06:48:44.531  3103  3103 D BluetoothInputDevice: Proxy object connected
10-14 06:48:44.531  3103  3103 D HidProfile: Bluetooth service connected
10-14 06:48:44.531  5862  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 06:48:44.532  5642  5642 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 06:48:44.533  5642  5642 D PanProfile: Bluetooth service connected
10-14 06:48:44.533  5642  5642 D BluetoothMap: Proxy object connected
10-14 06:48:44.533  5642  5642 D MapProfile: Bluetooth service connected
10-14 06:48:44.533  5642  5642 D BluetoothMap: getConnectedDevices()
,10-14 06:48:44.533   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:44.533   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:44.533  3103  3959 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:44.534  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:44.534  5862  5862 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 06:48:44.535   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:44.535  5642  5658 D BluetoothPbap: onBluetoothStateChange: up=true
10-14 06:48:44.535  5862  5862 D ObexServerSockets: Succeed to create listening sockets 
10-14 06:48:44.536  5862  5862 D ObexServerSockets0: startAccept()
10-14 06:48:44.536  5862  5862 D ObexServerSockets0: prepareForNewConnect()
10-14 06:48:44.536  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:44.537  5642  5655 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:44.537  3103  3121 D BluetoothPan: onBluetoothStateChange on: true
10-14 06:48:44.538  5862  5862 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,10-14 06:48:44.538  5862  5862 D BluetoothSdpJni: SDP Create record success - handle: 0
10-14 06:48:44.538  5862  5902 D ObexServerSockets0: Accepting socket connection...
10-14 06:48:44.539  5862  5903 D ObexServerSockets0: Accepting socket connection...
10-14 06:48:44.539  3103  3103 D BluetoothPan: BluetoothPAN Proxy object connected
10-14 06:48:44.539  3103  3103 D PanProfile: Bluetooth service connected
10-14 06:48:44.539  3103  3103 D BluetoothA2dp: Proxy object connected
10-14 06:48:44.539  3103  3115 D BluetoothHeadset: onBluetoothStateChange: up=true
10-14 06:48:44.539  5642  5658 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 06:48:44.541   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-14 06:48:44.542   928   928 D BluetoothA2dp: Proxy object connected
10-14 06:48:44.543  5862  5862 D BluetoothMapService: onReceive
10-14 06:48:44.543  5862  5862 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-14 06:48:44.543  5589  5589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-14 06:48:44.544  5862  5862 D BluetoothMapService: STATE_ON
10-14 06:48:44.545  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:44.545   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
10-14 06:48:44.546  5642  5642 D BluetoothInputDevice: Proxy object connected
10-14 06:48:44.546  5642  5642 D HidProfile: Bluetooth service connected
10-14 06:48:44.546  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:44.546  5862  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-14 06:48:44.547  5642  5642 D BluetoothA2dp: Proxy object connected
10-14 06:48:44.547  5862  5904 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-14 06:48:44.547  5862  5904 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-14 06:48:44.553  5642  5642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-14 06:48:44.558  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-14 06:48:44.560  5642  5642 D DockEventReceiver: finishStartingService: stopping service
,10-14 06:48:44.568  5642  5642 D BluetoothPbap: Proxy object connected
,10-14 06:48:44.568  5642  5642 D PbapServerProfile: Bluetooth service connected
,10-14 06:48:44.570  3103  3103 D BluetoothPbap: Proxy object connected
10-14 06:48:44.570  3103  3103 D PbapServerProfile: Bluetooth service connected
,10-14 06:48:44.572  5862  5862 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-14 06:48:44.572  5862  5862 D ObexServerSockets0: prepareForNewConnect()
10-14 06:48:44.575  5862  5908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 06:48:44.588  5862  5912 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-14 06:48:44.590  5862  5912 I BtOppRfcommListener: Accept thread started.
,10-14 06:48:44.627   928   928 D BluetoothHeadset: Proxy object connected
,10-14 06:48:44.627  3103  3121 D BluetoothHeadset: Proxy object connected
,10-14 06:48:44.627  3103  3103 D HeadsetProfile: Bluetooth service connected
,10-14 06:48:44.628  3766  3788 D BluetoothHeadset: Proxy object connected
10-14 06:48:44.628   928   928 D BluetoothHeadset: Proxy object connected
10-14 06:48:44.628   928   928 D BluetoothHeadset: Proxy object connected
10-14 06:48:44.628  5642  5901 D BluetoothHeadset: Proxy object connected
10-14 06:48:44.629  5642  5642 D HeadsetProfile: Bluetooth service connected
,10-14 06:48:44.634   928   945 D BluetoothHeadset: Proxy object connected
,10-14 06:48:44.634   928   945 D BluetoothHeadset: Proxy object connected
10-14 06:48:44.634   928   945 D BluetoothHeadset: Proxy object connected
,10-14 06:48:44.637  5642  5655 D BluetoothHeadset: Proxy object connected
,10-14 06:48:44.637  5642  5642 D HeadsetProfile: Bluetooth service connected
,10-14 06:48:44.639  3103  3115 D BluetoothHeadset: Proxy object connected
,10-14 06:48:44.639  3103  3103 D HeadsetProfile: Bluetooth service connected
,10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:48.443  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:48.449  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:48.449  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:48.450  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c58f7f removed from the list
10-14 06:48:48.450  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 06:48:48.450  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:48.450  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:48.453  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:48.454  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f10fb4c added. We now have 4 listener(s)
,10-14 06:48:48.454  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:48.460   928  3814 D WifiService: setWifiEnabled: false pid=5589, uid=10077
,10-14 06:48:48.460   928  3814 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 06:48:53.469  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:53.470   928  3401 D WifiService: setWifiEnabled: true pid=5589, uid=10077
10-14 06:48:53.470   928  3401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-14 06:48:53.477   509   922 D SoftapController: Softap fwReload - Ok
,10-14 06:48:53.482   509   922 D CommandListener: Setting iface cfg
10-14 06:48:53.483   509   922 D CommandListener: Trying to bring down wlan0
,10-14 06:48:53.485   509   922 D CommandListener: Clearing all IP addresses on wlan0
,10-14 06:48:53.491   928  2960 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-14 06:48:54.164   928  2960 D wifi    : set interface wlan0 flags (UP)
,10-14 06:48:54.166   928  2960 I WifiHAL : Initializing wifi
,10-14 06:48:54.166   928  2960 I WifiHAL : Creating socket
,10-14 06:48:54.172   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-14 06:48:54.175   928  2960 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-14 06:48:54.175   928  2960 D wifi    : Did set static halHandle = 0x7f66d11b80
10-14 06:48:54.175   928  2960 D wifi    : halHandle = 0x7f66d11b80, mVM = 0x7f8334d140, mCls = 0x2015be
10-14 06:48:54.176   928  2960 D wifi    : array field set
10-14 06:48:54.176   928  2960 I WifiNative-HAL: interface[0] = wlan0
10-14 06:48:54.179   928  5918 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547185826688
,10-14 06:48:54.179   928  5918 D wifi    : waitForHalEvents called, vm = 0x7f8334d140, obj = 0x2015be, env = 0x7f6440bc40
,10-14 06:48:54.226  5919  5919 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-14 06:48:54.248  5919  5919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 06:48:54.258  5919  5919 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-14 06:48:54.259  5919  5919 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-14 06:48:54.280   928  2960 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-14 06:48:54.286  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:54.295  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:54.295   928  2960 D WifiConfigStore: Loading config and enabling all networks 
,10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:54.300  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:54.302  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:54.304   928  2960 D WifiConfigStore: loaded 0 passpoint configs
10-14 06:48:54.304   928  2960 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:54.304  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-14 06:48:54.304   928  2960 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-14 06:48:54.305   928  2960 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-14 06:48:54.305  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-14 06:48:54.306   928  2960 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-14 06:48:54.306   928  2960 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,10-14 06:48:54.306   928  2960 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-14 06:48:54.306   928  2960 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-14 06:48:54.309   928  2960 D WifiNative-HAL: Setting external_sim to 1
10-14 06:48:54.309  4981  4981 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-14 06:48:54.309   928  2960 D wifi    : setting dfs flag to true, 0x7f68ffd500
,10-14 06:48:54.309   928  2960 D WifiStateMachine: Setting OUI to DA-A1-19
10-14 06:48:54.310   928  2960 D wifi    : setting scan oui 0x7f68ffd500
10-14 06:48:54.310   928  2960 D WifiHAL : Sending mac address OUI
,10-14 06:48:54.313   928  2960 E native  : do suspend false
,10-14 06:48:54.323   928  2960 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-14 06:48:54.324   928   928 D RttService: SCAN_AVAILABLE : 3
10-14 06:48:54.324   509   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-14 06:48:54.324   928  3069 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-14 06:48:54.325   509   922 D CommandListener: Setting iface cfg
,10-14 06:48:54.329   928  2959 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,10-14 06:48:54.329   928  2959 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-14 06:48:54.338   928  2959 D WifiNative-HAL: p2pGetDeviceAddress
,10-14 06:48:54.338   928  2959 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-14 06:48:54.344   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=319680 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-14 06:48:57.504  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:57.511  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:57.515  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:57.519  5919  5919 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-14 06:48:57.570   928  2960 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-14 06:48:57.571   928  2960 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,10-14 06:48:57.571   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 06:48:57.583   928  2960 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-14 06:48:57.619   928  2960 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-14 06:48:57.621  5919  5919 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-14 06:48:58.128  5919  5919 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-14 06:48:58.187  5919  5919 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-14 06:48:58.188  5919  5919 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-14 06:48:58.203   928  2960 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-14 06:48:58.203   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-14 06:48:58.204   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-14 06:48:58.219   928  2960 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-14 06:48:58.236   509   922 D CommandListener: Setting iface cfg
,10-14 06:48:58.242   928  2960 D WifiStateMachine: Start Dhcp Watchdog 3
,10-14 06:48:58.247   928  5925 D DhcpClient: Receive thread started
,10-14 06:48:58.253   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-14 06:48:58.253   928  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-14 06:48:58.253   928  2962 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-14 06:48:58.335   928  2960 E native  : do suspend false
,10-14 06:48:58.350   928  5924 D DhcpClient: Broadcasting DHCPDISCOVER
,10-14 06:48:58.375   928  5925 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,10-14 06:48:58.376   928  5924 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,10-14 06:48:58.378   928  5924 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-14 06:48:58.395   928  5925 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-14 06:48:58.395   928  5924 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-14 06:48:58.398   509   922 D CommandListener: Setting iface cfg
,10-14 06:48:58.403   928  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-14 06:48:58.407   928  5924 D DhcpClient: Scheduling renewal in 86399s
,10-14 06:48:58.415   928  2960 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-14 06:48:58.416   928  2960 D WifiConfigStore: No blacklist allowed without epno enabled
10-14 06:48:58.417   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-14 06:48:58.421   928  2962 D ConnectivityService: Adding iface wlan0 to network 102
,10-14 06:48:58.422   928  2960 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-14 06:48:58.463   928  2962 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-14 06:48:58.463   928  2962 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-14 06:48:58.467   928  2962 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-14 06:48:58.468   928  2962 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-14 06:48:58.470   928  2962 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-14 06:48:58.476   928  2962 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 06:48:58.481   928  2962 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-14 06:48:58.482   928  2962 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-14 06:48:58.482   928  2962 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-14 06:48:58.482   928  2962 D ConnectivityService:    accepting network in place of null
10-14 06:48:58.482   928  2960 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-14 06:48:58.482   928  2960 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-14 06:48:58.483   928  2962 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-14 06:48:58.484  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-14 06:48:58.487  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-14 06:48:58.487  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-14 06:48:58.487  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f10fb4c removed from the list
10-14 06:48:58.487  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:58.487  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.487  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:58.491  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-14 06:48:58.492  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-14 06:48:58.494  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@6860596 Bundle[{}]
10-14 06:48:58.495  5589  5635 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-14 06:48:58.495  5589  5635 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-14 06:48:58.495  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-14 06:48:58.496  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-14 06:48:58.497  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-14 06:48:58.497  5589  5635 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-14 06:48:58.502  5589  5635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
10-14 06:48:58.503  5589  5635 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-14 06:48:58.503  5589  5635 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,10-14 06:48:58.504   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 06:48:58.505  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.505  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f945795 added. We now have 3 listener(s)
,10-14 06:48:58.507  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-14 06:48:58.507  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.507  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.507  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.507  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@716e0aa added. We now have 4 listener(s)
10-14 06:48:58.507  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:58.508  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 06:48:58.511  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:58.515  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 06:48:58.517  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:58.517  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:48:58.517  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.517  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef88038 added. We now have 4 listener(s)
10-14 06:48:58.518  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.518  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.518  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.518  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.518  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2fd811 added. We now have 5 listener(s)
10-14 06:48:58.518  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:48:58.518  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:58.518  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.519  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:58.519  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:58.519  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.519  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.519  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.519  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.519  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.519  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f945795 removed from the list
10-14 06:48:58.519  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.519  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@716e0aa removed from the list
,10-14 06:48:58.521  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.521  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:58.521  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-14 06:48:58.522  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:48:58.522  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.522  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.523  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.523  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.523  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@716e0aa not in the list
10-14 06:48:58.523  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.523  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.523   509   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-14 06:48:58.524  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.524  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.524  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.524  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2fd811 removed from the list
10-14 06:48:58.524  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.524  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.524  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.524  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 06:48:58.524  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-14 06:48:58.524  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef88038 removed from the list
10-14 06:48:58.525  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.525  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85a5d76 added. We now have 3 listener(s)
10-14 06:48:58.526  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.526  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.526  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.526  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.526  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@637ef77 added. We now have 4 listener(s)
10-14 06:48:58.526  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:48:58.526  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 06:48:58.527   928  2962 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
10-14 06:48:58.527   928  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-14 06:48:58.527  3731  3897 W QCNEJ   : |CORE| network available: 102
10-14 06:48:58.528   928  2962 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-14 06:48:58.530   928   945 D Tethering: MasterInitialState.processMessage what=3
10-14 06:48:58.531  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:58.531  3731  3897 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-14 06:48:58.532  3731  3897 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-14 06:48:58.532  3731  3897 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:58.535  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:58.539  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-14 06:48:58.540  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:58.541  5007  5030 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-14 06:48:58.542  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:58.542  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:48:58.542  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.542  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e28e44d added. We now have 4 listener(s)
10-14 06:48:58.544  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.544  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.544  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.544  5007  5030 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-14 06:48:58.544  5007  5030 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-14 06:48:58.544  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.544  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d86db02 added. We now have 5 listener(s)
10-14 06:48:58.544  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:58.544  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:48:58.544  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 06:48:58.544  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 06:48:58.544  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:58.544  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:58.545  5589  5589 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:58.545  3854  3854 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-14 06:48:58.547  5589  5589 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.547  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 06:48:58.547  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 06:48:58.548  5007  5030 E SarControlService: no key has been found,reset the power
,10-14 06:48:58.548  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-14 06:48:58.548  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-14 06:48:58.548  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-14 06:48:58.548  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:58.548  5032  5032 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-14 06:48:58.549  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.549  5007  5044 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-14 06:48:58.549  5007  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-14 06:48:58.549  5007  5044 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-14 06:48:58.550  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-14 06:48:58.550  5032  5032 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-14 06:48:58.550  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 06:48:58.551  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.551  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 06:48:58.551  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 06:48:58.551  3854  3854 D SystemUpdateService: onCreate
10-14 06:48:58.554  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 06:48:58.554  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,10-14 06:48:58.554  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 06:48:58.554  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 06:48:58.554  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 06:48:58.554  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:48:58.555  3854  3854 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-14 06:48:58.556  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000f003000000000000ffffffff]
10-14 06:48:58.556  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:58.556  5032  5046 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-14 06:48:58.556  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:58.556  5007  5018 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-14 06:48:58.557  5032  5046 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@2fabb72 HexData = [00000000f103000000000000ffffffff]
10-14 06:48:58.557  5032  5046 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-14 06:48:58.557  5862  5900 D BtGatt.GattService: registerClient() - UUID=b59fc1b5-f837-4e36-9908-11d61f4b7d1e
10-14 06:48:58.557  5032  5046 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-14 06:48:58.558  5862  5878 D BtGatt.GattService: onClientRegistered() - UUID=b59fc1b5-f837-4e36-9908-11d61f4b7d1e, clientIf=5
10-14 06:48:58.558  5032  5032 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-14 06:48:58.558  5007  5017 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-14 06:48:58.558  5589  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 06:48:58.559  5862  5889 D BtGatt.GattService: start scan with filters
10-14 06:48:58.563  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 06:48:58.564  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 06:48:58.564  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:48:58.564  5862  5881 D BtGatt.ScanManager: handling starting scan
10-14 06:48:58.564  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 06:48:58.564  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 06:48:58.564  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 06:48:58.564  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 06:48:58.565  5862  5881 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@265e03b
10-14 06:48:58.566  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:48:58.566  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 06:48:58.566  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:48:58.568  3854  3854 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
10-14 ,06:48:58.568  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 06:48:58.571  5589  5635 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-14 06:48:58.571  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:58.571  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-14 06:48:58.571  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.571  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 06:48:58.571  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-14 06:48:58.572  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-14 06:48:58.572  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 06:48:58.572  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 06:48:58.572  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 06:48:58.572  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 06:48:58.572  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 06:48:58.573  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:48:58.573  5862  5878 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 06:48:58.573  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.573  5862  5872 D BtGatt.GattService: stopScan() - queue size =1
10-14 06:48:58.573  5862  5881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 06:48:58.574  5862  5900 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 06:48:58.574  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 06:48:58.574  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 06:48:58.574  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 06:48:58.574  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:48:58.575  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 06:48:58.575  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 06:48:58.575  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 06:48:58.575  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 06:48:58.576  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:58.576  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 06:48:58.576  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 06:48:58.576  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 06:48:58.576  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 06:48:58.577  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.578  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:58.578  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:58.578  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:58.578  5862  5878 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 06:48:58.578  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.579  5862  5881 D BtGatt.ScanManager: Starting B,LE batch scan
10-14 06:48:58.579  5862  5881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 06:48:58.579  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:58.579  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:58.579  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:58.580  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.580  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.580  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.580  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.580  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.580  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@85a5d76 removed from the list
10-14 06:48:58.580  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.580  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@637ef77 removed from the list
10-14 06:48:58.580  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:58.580  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.580  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.580  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.581  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.581  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.581  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.581  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@637ef77 not in the list
10-14 06:48:58.581  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.581  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.582  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.582  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.582  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.582  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d86db02 removed from the list
10-14 06:48:58.582  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.582  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.582  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetoot,h.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.582  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.582  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.582  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e28e44d removed from the list
10-14 06:48:58.583  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.583  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10ba54e added. We now have 3 listener(s)
10-14 06:48:58.585  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.585  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.585  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.585  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.585  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a7566f added. We now have 4 listener(s)
10-14 06:48:58.585  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:48:58.586  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 06:48:58.587  3854  5368 I iu.UploadsManager: num queued entries: 0
10-14 06:48:58.587  5862  5878 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 06:48:58.587  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.587  3854  5368 I iu.UploadsManager: num updated entries: 0
10-14 06:48:58.588  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:58.588  3854  5368 I iu.SyncManager: NEXT; no task
10-14 06:48:58.590  3854  3854 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-14 06:48:58.592  3854  3854 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-14 06:48:58.592  5862  5878 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 06:48:58.592  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.594  5717  5717 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:58.595  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:58.597  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.598  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:48:58.598  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.598  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bb5005 added. We now have 4 listener(s)
10-14 06:48:58.599  5862  5878 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 06:48:58.599  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.599  5862  5881 D BtGatt.ScanManager: stopping BLe Batch
10-14 06:48:58.599  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.599  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.599  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.599  5717  5717 D SprintDMHelper: simOperator: 
10-14 06:48:58.599  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.599  5717  5717 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-14 06:48:58.599  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@300c85a added. We now have 5 listener(s)
10-14 06:48:58.599  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:48:58.599  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:48:58.600  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:48:58.600  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 06:48:58.601  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 06:48:58.601  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:58.601  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 06:48:58.602  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.602  3854  5935 I SystemUpdateService: active receiver: enabled
10-14 06:48:58.605  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.607  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 06:48:58.607  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 06:48:58.607  5862  5878 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 06:48:58.607  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.607  5862  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 06:48:58.611  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 06:48:58.611  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-14 06:48:58.611  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 06:48:58.613  5862  5878 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 06:48:58.613  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.615  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 06:48:58.615  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 06:48:58.615  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 06:48:58.615  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 06:48:58.615  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 06:48:58.616  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:48:58.617  5862  5900 D BtGatt.GattService: registerClient() - UUID=4d6f366a-4ed7-413e-861c-e063addaffb7
10-14 06:48:58.617  5862  5878 D BtGatt.GattService: onClientRegistered() - UUID=4d6f366a-4ed7-413e-861c-e063addaffb7, clientIf=5
10-14 06:48:58.618  5589  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 06:48:58.618  5862  5898 D BtGatt.GattService: start scan with filters
10-14 06:48:58.620  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 06:48:58.620  5862  5881 D BtGatt.ScanManager: handling starting scan
10-14 06:48:58.620  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 06:48:58.620  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:48:58.620  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 06:48:58.620  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 06:48:58.620  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 06:48:58.620  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 06:48:58.622  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:48:58.622  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 06:48:58.623  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:48:58.624  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 06:48:58.626  5862  5878 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 06:48:58.626  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.626  5862  5881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 06:48:58.627  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:48:58.627  5589  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-14 06:48:58.627  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:58.627  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:58.627  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:58.627  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.627  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.627  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 06:48:58.627  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.627  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.628  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10ba54e removed from the list
10-14 06:48:58.628  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.628  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a7566f removed from the list
10-14 06:48:58.628  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:58.628  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.628  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.628  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-14 06:48:58.628  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.628  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.629  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.630  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.630  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.630  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6a7566f not in the list
10-14 06:48:58.630  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 06:48:58.630  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 06:48:58.630  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 06:48:58.630  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 06:48:58.630  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 06:48:58.631  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:48:58.631  5862  5898 D BtGatt.GattService: stopScan() - queue size =1
10-14 06:48:58.632  5862  5899 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 06:48:58.632  3854  5935 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-14 06:48:58.632  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 06:48:58.632  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 06:48:58.632  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 06:48:58.632  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:48:58.632  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 06:48:58.632  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 06:48:58.632  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 06:48:58.632  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 06:48:58.633  5862  5878 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 06:48:58.633  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.633  5862  5881 D BtGatt.ScanManager: Starting BLE batch scan
10-14 06:48:58.633  5862  5881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 06:48:58.633  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:58.633  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 06:48:58.633  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 06:48:58.633  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 06:48:58.633  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 06:48:58.636  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.637  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.637  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.637  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.637  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:58.637  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@300c85a removed from the list
10-14 06:48:58.637  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:58.637  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.637  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:58.637  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.637  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.637  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.637  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.637  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8bb5005 removed from the list
10-14 06:48:58.638  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.638  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af31026 added. We now have 3 listener(s)
10-14 06:48:58.639  3854  5935 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-14 06:48:58.640  3854  5935 I SystemUpdateService: now status is 0 (complete)
10-14 06:48:58.640  3854  5935 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-14 06:48:58.640  3854  5935 I SystemUpdateService: file has been verified
10-14 06:48:58.640  3854  5935 I SystemUpdateService: OTA package size = 21989297
10-14 06:48:58.640  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.640  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.640  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.641  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.641  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcda467 added. We now have 4 listener(s)
10-14 06:48:58.641  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:48:58.642  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-14 06:48:58.644  5862  5878 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 06:48:58.644  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.644  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:58.646  3854  5935 I SystemUpdateService: showing system update notification
10-14 06:48:58.648  5862  5878 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 06:48:58.649  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:58.651  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:58.653  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.653  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:48:58.653  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.653  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7487abd added. We now have 4 listener(s)
10-14 06:48:58.654  5862  5878 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 06:48:58.654  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.654  5862  5881 D BtGatt.ScanManager: stopping BLe Batch
10-14 06:48:58.654  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.654  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.655  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.655  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.655  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7008b2 added. We now have 5 listener(s)
10-14 06:48:58.655  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:48:58.655  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:48:58.655  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-14 06:48:58.655  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-14 06:48:58.655  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:58.655  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-14 06:48:58.655  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.657  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:58.658  5589  5635 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-14 06:48:58.658  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-14 06:48:58.659  5862  5878 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-14 06:48:58.659  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.659  5862  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-14 06:48:58.661  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-14 06:48:58.662  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-14 06:48:58.662  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-14 06:48:58.664  3854  3854 D SystemUpdateService: onDestroy
10-14 06:48:58.664  5862  5878 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 06:48:58.664  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.665  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-14 06:48:58.665  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-14 06:48:58.665  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-14 06:48:58.665  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-14 06:48:58.665  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-14 06:48:58.666  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:48:58.669  5862  5900 D BtGatt.GattService: registerClient() - UUID=95bf83f5-8c0c-425f-a882-69c866561c25
10-14 06:48:58.669  5862  5878 D BtGatt.GattService: onClientRegistered() - UUID=95bf83f5-8c0c-425f-a882-69c866561c25, clientIf=5
10-14 06:48:58.669  5589  5685 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-14 06:48:58.670  5862  5898 D BtGatt.GattService: start scan with filters
10-14 06:48:58.672  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-14 06:48:58.672  5862  5881 D BtGatt.ScanManager: handling starting scan
10-14 06:48:58.672  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-14 06:48:58.672  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:48:58.672  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-14 06:48:58.672  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-14 06:48:58.672  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-14 06:48:58.672  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-14 06:48:58.675  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:48:58.675  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-14 06:48:58.675  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-14 06:48:58.676  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-14 06:48:58.676  5862  5878 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-14 06:48:58.677  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.677  5862  5881 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-14 06:48:58.681  5862  5878 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-14 06:48:58.681  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.681  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:58.682  5862  5881 D BtGatt.ScanManager: Starting BLE batch scan
10-14 06:48:58.682  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:58.682  5862  5881 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-14 06:48:58.682  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:58.682  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.682  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.682  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-14 06:48:58.682  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.682  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.682  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af31026 removed from the list
10-14 06:48:58.682  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.683  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcda467 removed from the list
10-14 06:48:58.683  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
10-14 06:48:58.683  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.683  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.684  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-14 06:48:58.684  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.684  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.685  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.685  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.685  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.685  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bcda467 not in the list
10-14 06:48:58.685  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-14 06:48:58.685  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-14 06:48:58.685  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-14 06:48:58.685  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-14 06:48:58.685  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-14 06:48:58.686  5589  5635 D BluetoothAdapter: STATE_ON
10-14 06:48:58.687  5862  5872 D BtGatt.GattService: stopScan() - queue size =1
10-14 06:48:58.688  5862  5889 D BtGatt.GattService: unregisterClient() - clientIf=5
10-14 06:48:58.688  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-14 06:48:58.688  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-14 06:48:58.688  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-14 06:48:58.688  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-14 06:48:58.688  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-14 06:48:58.688  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-14 06:48:58.688  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
10-14 06:48:58.689  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-14 06:48:58.691  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:58.691  5862  5878 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-14 06:48:58.691  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.691  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-14 06:48:58.691  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
10-14 06:48:58.691  5589  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-14 06:48:58.691  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-14 06:48:58.691  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.693  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.694  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.694  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.694  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:58.694  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a7008b2 removed from the list
10-14 06:48:58.694  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.694  5589  5589 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-14 06:48:58.694  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.694  5589  5589 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-14 06:48:58.694  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.694  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.694  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.694  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7487abd removed from the list
10-14 06:48:58.694  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.694  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c51fdfe added. We now have 3 listener(s)
10-14 06:48:58.695  5862  5878 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-14 06:48:58.695  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.696  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.696  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.696  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.696  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.696  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac0b95f added. We now have 4 listener(s)
10-14 06:48:58.696  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-14 06:48:58.697  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-14 06:48:58.699  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-14 06:48:58.702  5862  5878 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-14 06:48:58.702  5589  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-14 06:48:58.703  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.703  5862  5881 D BtGatt.ScanManager: stopping BLe Batch
,10-14 06:48:58.707  5862  5878 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-14 06:48:58.707  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.707  5862  5881 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-14 06:48:58.707  5589  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-14 06:48:58.707  5589  5635 D io.jxcore.node.ConnectivityMonitor: start: OK
10-14 06:48:58.708  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-14 06:48:58.708  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8894475 added. We now have 4 listener(s)
10-14 06:48:58.709  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-14 06:48:58.709  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-14 06:48:58.709  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-14 06:48:58.709  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-14 06:48:58.709  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccbfc0a added. We now have 5 listener(s)
,10-14 06:48:58.709  5589  5635 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-14 06:48:58.709  5589  5635 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-14 06:48:58.709  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:48:58.709  5589  5635 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-14 06:48:58.709  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.709  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.709  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-14 06:48:58.709  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.709  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.709  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c51fdfe removed from the list
10-14 06:48:58.710  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.710  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac0b95f removed from the list
10-14 06:48:58.711  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-14 06:48:58.711  5589  5635 D io.jxcore.node.ConnectivityMonitor: stop
,10-14 06:48:58.711  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.711  5862  5878 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-14 06:48:58.711  5862  5878 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-14 06:48:58.711  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.712  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.713  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.713  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-14 06:48:58.713  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.713  5589  5635 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac0b95f not in the list
10-14 06:48:58.713  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-14 06:48:58.713  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.714  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-14 06:48:58.714  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-14 06:48:58.714  5589  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-14 06:48:58.714  5589  5635 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ccbfc0a removed from the list
10-14 06:48:58.714  5589  5635 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-14 06:48:58.714  5589  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-14 06:48:58.714  5589  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-14 06:48:58.714  5589  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-14 06:48:58.714  5589  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-14 06:48:58.714  5589  5635 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8894475 removed from the list
10-14 06:48:58.714  5589  5589 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-14 06:48:58.715  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,10-14 06:48:58.715  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-14 06:48:58.715  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-14 06:48:58.715  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:48:58.715  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-14 06:48:58.715  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-14 06:48:59.078  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 06:48:59.138  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 06:48:59.194  5589  5589 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-14 06:49:00.497   928  5923 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325833, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-14 06:49:00.849  5589  5944 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 06:49:00.849  5589  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 06:49:01.273   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 06:49:01.653  5589  5944 W !!      : call onHalfStreamCopied
,10-14 06:49:01.653  5589  5944 I testCopyDataAndClose: closing input stream
,10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-14 06:49:02.424  5589  5944 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 06:49:04.332   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-14 06:49:04.332   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-14 06:49:06.215  5589  5945 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:06.215  5589  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 06:49:06.487   928  2962 D ConnectivityService: handlePromptUnvalidated 102
,10-14 06:49:08.012   928  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=108.177.15.102,2a00:1450:400c:c0c::65
,10-14 06:49:08.215  5589  5635 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
10-14 06:49:08.215  5589  5635 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 06:49:08.216  5589  5635 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,10-14 06:49:08.311  5589  5945 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-14 06:49:08.311  5589  5945 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:08.311  5589  5945 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,10-14 06:49:08.372  5589  5946 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 06:49:08.372  5589  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 06:49:09.341   928  2960 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-14 06:49:09.988  5589  5946 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-14 06:49:12.342  4981  5940 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: java.net.SocketTimeoutException
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.read(PlainSocketImpl.java:484)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl.-wrap0(PlainSocketImpl.java)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at java.net.PlainSocketImpl$PlainSocketInputStream.read(PlainSocketImpl.java:237)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.Okio$2.read(Okio.java:135)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.AsyncTimeout$2.read(AsyncTimeout.java:211)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:306)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.indexOf(RealBufferedSource.java:300)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.okio.RealBufferedSource.readUtf8LineStrict(RealBufferedSource.java:196)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpConnection.readResponse(HttpConnection.java:191)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpTransport.readResponseHeaders(HttpTransport.java:80)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readNetworkResponse(HttpEngine.java:904)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.http.HttpEngine.readResponse(HttpEngine.java:788)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:443)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getResponse(HttpURLConnectionImpl.java:388)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.android.okhttp.internal.huc.HttpURLConnectionImpl.getInputStream(HttpURLConnectionImpl.java:231)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.a(SourceFile:129)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at com.google.android.apps.hangouts.service.NetworkConnectionCheckingService.onHandleIntent(SourceFile:1100)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:49:12.362  4981  5940 W Babel_NetworkConnectionCheckingService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 06:49:12.364  4981  5940 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-14 06:49:13.734  5589  5948 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:13.734  5589  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 06:49:13.734  5589  5948 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:13.734  5589  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:13.735  5589  5948 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-14 06:49:13.737  5589  5635 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-14 06:49:13.741  5589  5949 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:13.741  5589  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-14 06:49:13.743  5589  5949 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
,10-14 06:49:13.743  5589  5949 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:13.743  5589  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-14 06:49:13.743  5589  5949 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-14 06:49:13.743  5589  5949 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
10-14 06:49:13.743  5589  5949 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-14 06:49:13.747  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-14 06:49:13.747  5589  5635 I jxcore-log: 
,10-14 06:49:13.748  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-14 06:49:13.748  5589  5635 I jxcore-log: 
10-14 06:49:13.748  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-14 06:49:13.748  5589  5635 I jxcore-log: 
10-14 06:49:13.748  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-14 06:49:13.748  5589  5635 I jxcore-log: 
10-14 06:49:13.748  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'Total duration:  90771'
10-14 06:49:13.748  5589  5635 I jxcore-log: 
,10-14 06:49:13.751  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-14 06:49:13.751  5589  5635 I jxcore-log: 
,10-14 06:49:13.755  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.755  5589  5635 I jxcore-log: 
,10-14 06:49:13.756  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.756  5589  5635 I jxcore-log: 
10-14 06:49:13.756  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.756  5589  5635 I jxcore-log: 
10-14 06:49:13.756  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.756  5589  5635 I jxcore-log: 
10-14 06:49:13.757  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-14 06:49:13.757  5589  5635 I jxcore-log: 
,10-14 06:49:13.757  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 06:49:13.757  5589  5635 I jxcore-log: 
10-14 06:49:13.757  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.757  5589  5635 I jxcore-log: 
10-14 06:49:13.758  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.758  5589  5635 I jxcore-log: 
10-14 06:49:13.758  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-14 06:49:13.758  5589  5635 I jxcore-log: 
10-14 06:49:13.758  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 06:49:13.758  5589  5635 I jxcore-log: 
,10-14 06:49:13.758  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 06:49:13.758  5589  5635 I jxcore-log: 
10-14 06:49:13.759  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.759  5589  5635 I jxcore-log: 
,10-14 06:49:13.759  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.759  5589  5635 I jxcore-log: 
,10-14 06:49:13.759  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.759  5589  5635 I jxcore-log: 
10-14 06:49:13.759  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.759  5589  5635 I jxcore-log: 
10-14 06:49:13.760  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.760  5589  5635 I jxcore-log: 
10-14 06:49:13.760  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.760  5589  5635 I jxcore-log: 
10-14 06:49:13.760  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.760  5589  5635 I jxcore-log: 
10-14 06:49:13.760  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.760  5589  5635 I jxcore-log: 
,10-14 06:49:13.761  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.761  5589  5635 I jxcore-log: 
10-14 06:49:13.761  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.761  5589  5635 I jxcore-log: 
10-14 06:49:13.761  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.761  5589  5635 I jxcore-log: 
10-14 06:49:13.762  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.762  5589  5635 I jxcore-log: 
10-14 06:49:13.763  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.763  5589  5635 I jxcore-log: 
,10-14 06:49:13.764  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.764  5589  5635 I jxcore-log: 
10-14 06:49:13.764  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.764  5589  5635 I jxcore-log: 
10-14 06:49:13.764  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.764  5589  5635 I jxcore-log: 
10-14 06:49:13.764  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.764  5589  5635 I jxcore-log: 
10-14 06:49:13.765  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.765  5589  5635 I jxcore-log: 
,10-14 06:49:13.765  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.765  5589  5635 I jxcore-log: 
10-14 06:49:13.765  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.765  5589  5635 I jxcore-log: 
10-14 06:49:13.765  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.765  5589  5635 I jxcore-log: 
10-14 06:49:13.766  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.766  5589  5635 I jxcore-log: 
10-14 06:49:13.766  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.766  5589  5635 I jxcore-log: 
,10-14 06:49:13.766  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.766  5589  5635 I jxcore-log: 
10-14 06:49:13.766  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.766  5589  5635 I jxcore-log: 
10-14 06:49:13.767  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.767  5589  5635 I jxcore-log: 
10-14 06:49:13.767  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.767  5589  5635 I jxcore-log: 
,10-14 06:49:13.767  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.767  5589  5635 I jxcore-log: 
10-14 06:49:13.767  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.767  5589  5635 I jxcore-log: 
10-14 06:49:13.767  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-14 06:49:13.767  5589  5635 I jxcore-log: 
10-14 06:49:13.768  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.768  5589  5635 I jxcore-log: 
10-14 06:49:13.768  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.768  5589  5635 I jxcore-log: 
,10-14 06:49:13.768  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-14 06:49:13.768  5589  5635 I jxcore-log: 
10-14 06:49:13.768  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.768  5589  5635 I jxcore-log: 
10-14 06:49:13.769  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.769  5589  5635 I jxcore-log: 
10-14 06:49:13.769  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.769  5589  5635 I jxcore-log: 
10-14 06:49:13.769  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.769  5589  5635 I jxcore-log: 
10-14 06:49:13.769  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-14 06:49:13.769  5589  5635 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,10-14 06:49:13.770  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.770  5589  5635 I jxcore-log: 
10-14 06:49:13.770  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.770  5589  5635 I jxcore-log: 
10-14 06:49:13.770  5589  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-14 06:49:13.770  5589  5635 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
10-14 06:49:13.770  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-14 06:49:13.770  5589  5635 I jxcore-log: 
10-14 06:49:13.771  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 06:49:13.771  5589  5635 I jxcore-log: 
,10-14 06:49:13.771  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 06:49:13.771  5589  5635 I jxcore-log: 
10-14 06:49:13.771  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-14 06:49:13.771  5589  5635 I jxcore-log: 
10-14 06:49:13.777  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-14 06:49:13.777  5589  5635 I jxcore-log: 
10-14 06:49:13.777  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - WARN testUtils: 'myNameCallback not set!'
10-14 06:49:13.777  5589  5635 I jxcore-log: 
10-14 06:49:13.778  5589  5635 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-14 06:49:13.779  5589  5635 I jxcore-log: 2016-10-14 10:49:13 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-14 06:49:13.779  5589  5635 I jxcore-log: 
,10-14 06:49:13.780  5589  5589 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-14 06:49:14.172   928  5922 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 14 Oct 2016 10:49:12 GMT], X-Android-Received-Millis=[1476442154170], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476442152171]}
10-14 06:49:14.174   928  2962 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-14 06:49:14.174   928  2962 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-14 06:49:14.175   928  2962 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-14 06:49:14.181   928  2962 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-14 06:49:15.773  5589  5635 I jxcore-log: 2016-10-14 10:49:15 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-14 06:49:15.773  5589  5635 I jxcore-log: 
,10-14 06:49:16.102  5589  5635 I jxcore-log: 2016-10-14 10:49:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-14 06:49:16.102  5589  5635 I jxcore-log: 
,10-14 06:49:16.115  5589  5635 I jxcore-log: 2016-10-14 10:49:16 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-14 06:49:16.115  5589  5635 I jxcore-log: 
,10-14 06:49:17.207  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-14 06:49:17.207  5589  5635 I jxcore-log: 
,10-14 06:49:17.369  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-14 06:49:17.369  5589  5635 I jxcore-log: 
,10-14 06:49:17.374  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-14 06:49:17.374  5589  5635 I jxcore-log: 
,10-14 06:49:17.379  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-14 06:49:17.379  5589  5635 I jxcore-log: 
,10-14 06:49:17.849  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-14 06:49:17.849  5589  5635 I jxcore-log: 
,10-14 06:49:17.891  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-14 06:49:17.891  5589  5635 I jxcore-log: 
,10-14 06:49:17.904  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-14 06:49:17.904  5589  5635 I jxcore-log: 
,10-14 06:49:17.908  5589  5635 I jxcore-log: 2016-10-14 10:49:17 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-14 06:49:17.908  5589  5635 I jxcore-log: 
,10-14 06:49:18.181  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-14 06:49:18.181  5589  5635 I jxcore-log: 
,10-14 06:49:18.303  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-14 06:49:18.303  5589  5635 I jxcore-log: 
,10-14 06:49:18.679  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-14 06:49:18.679  5589  5635 I jxcore-log: 
,10-14 06:49:18.687  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-14 06:49:18.687  5589  5635 I jxcore-log: 
,10-14 06:49:18.690  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-14 06:49:18.690  5589  5635 I jxcore-log: 
,10-14 06:49:18.695  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-14 06:49:18.695  5589  5635 I jxcore-log: 
,10-14 06:49:18.700  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-14 06:49:18.700  5589  5635 I jxcore-log: 
,10-14 06:49:18.726  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-14 06:49:18.726  5589  5635 I jxcore-log: 
,10-14 06:49:18.760  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-14 06:49:18.760  5589  5635 I jxcore-log: 
,10-14 06:49:18.767  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-14 06:49:18.767  5589  5635 I jxcore-log: 
,10-14 06:49:18.772  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-14 06:49:18.772  5589  5635 I jxcore-log: 
,10-14 06:49:18.788  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-14 06:49:18.788  5589  5635 I jxcore-log: 
,10-14 06:49:18.792  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-14 06:49:18.792  5589  5635 I jxcore-log: 
,10-14 06:49:18.798  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-14 06:49:18.798  5589  5635 I jxcore-log: 
,10-14 06:49:18.803  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-14 06:49:18.803  5589  5635 I jxcore-log: 
,10-14 06:49:18.816  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-14 06:49:18.816  5589  5635 I jxcore-log: 
,10-14 06:49:18.838  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-14 06:49:18.838  5589  5635 I jxcore-log: 
,10-14 06:49:18.849  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-14 06:49:18.849  5589  5635 I jxcore-log: 
,10-14 06:49:18.861  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-14 06:49:18.861  5589  5635 I jxcore-log: 
,10-14 06:49:18.871  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-14 06:49:18.871  5589  5635 I jxcore-log: 
,10-14 06:49:18.884  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-14 06:49:18.884  5589  5635 I jxcore-log: 
,10-14 06:49:18.893  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-14 06:49:18.893  5589  5635 I jxcore-log: 
,10-14 06:49:18.898  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-14 06:49:18.898  5589  5635 I jxcore-log: 
,10-14 06:49:18.919  5589  5635 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-14 06:49:18.921  5589  5635 I jxcore-log: 2016-10-14 10:49:18 - INFO testUtils: 'BLE multiple advertisement supported'
10-14 06:49:18.921  5589  5635 I jxcore-log: 
,10-14 06:49:19.333   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:20.334   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:21.336   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:22.337   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:23.338   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:24.338   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-14 06:49:29.340   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:30.341   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:31.342   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:32.343   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:33.345   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:34.345   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-14 06:49:36.788  5589  5635 I jxcore-log: 2016-10-14 10:49:36 - DEBUG CoordinatedClient: 'connected to the test server'
10-14 06:49:36.788  5589  5635 I jxcore-log: 
,10-14 06:49:37.367  5589  5635 I jxcore-log: TAP version 13
10-14 06:49:37.367  5589  5635 I jxcore-log: 
,10-14 06:49:37.406  5589  5635 I jxcore-log: # setup
10-14 06:49:37.406  5589  5635 I jxcore-log: 
,10-14 06:49:38.466   928  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 06:49:38.599  5589  5635 I jxcore-log: # calling createNativeListener directly rejects
10-14 06:49:38.599  5589  5635 I jxcore-log: 
,10-14 06:49:38.692  5589  5635 I jxcore-log: 2016-10-14 10:49:38 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:38.692  5589  5635 I jxcore-log: 
,10-14 06:49:38.699  5589  5635 I jxcore-log: 2016-10-14 10:49:38 - DEBUG createNativeListener: 'listening 40995'
10-14 06:49:38.699  5589  5635 I jxcore-log: 
,10-14 06:49:38.709  5589  5635 I jxcore-log: ok 1 Should throw
10-14 06:49:38.709  5589  5635 I jxcore-log: 
,10-14 06:49:38.722  5589  5635 I jxcore-log: # teardown
10-14 06:49:38.722  5589  5635 I jxcore-log: 
,10-14 06:49:39.562  5589  5635 I jxcore-log: # setup
10-14 06:49:39.562  5589  5635 I jxcore-log: 
,10-14 06:49:40.270  5589  5635 I jxcore-log: # emits incomingConnectionState
10-14 06:49:40.270  5589  5635 I jxcore-log: 
,10-14 06:49:40.307  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:40.307  5589  5635 I jxcore-log: 
,10-14 06:49:40.311  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'listening 45108'
10-14 06:49:40.311  5589  5635 I jxcore-log: 
,10-14 06:49:40.320  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:40.320  5589  5635 I jxcore-log: 
,10-14 06:49:40.322  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:40.322  5589  5635 I jxcore-log: 
,10-14 06:49:40.331  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new mux'
10-14 06:49:40.331  5589  5635 I jxcore-log: 
,10-14 06:49:40.337  5589  5635 I jxcore-log: ok 2 initial connection state should be CONNECTED
10-14 06:49:40.337  5589  5635 I jxcore-log: 
,10-14 06:49:40.358  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:40.358  5589  5635 I jxcore-log: 
,10-14 06:49:40.359  5589  5635 I jxcore-log: ok 3 final connection state should be DISCONNECTED
10-14 06:49:40.359  5589  5635 I jxcore-log: 
,10-14 06:49:40.364  5589  5635 I jxcore-log: # teardown
10-14 06:49:40.364  5589  5635 I jxcore-log: 
,10-14 06:49:40.435  5589  5635 I jxcore-log: # setup
10-14 06:49:40.435  5589  5635 I jxcore-log: 
,10-14 06:49:40.471  5589  5635 I jxcore-log: # emits routerPortConnectionFailed
10-14 06:49:40.471  5589  5635 I jxcore-log: 
,10-14 06:49:40.519  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:40.519  5589  5635 I jxcore-log: 
,10-14 06:49:40.522  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'listening 38945'
10-14 06:49:40.522  5589  5635 I jxcore-log: 
,10-14 06:49:40.528  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:40.528  5589  5635 I jxcore-log: 
,10-14 06:49:40.530  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:40.530  5589  5635 I jxcore-log: 
,10-14 06:49:40.532  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new mux'
10-14 06:49:40.532  5589  5635 I jxcore-log: 
,10-14 06:49:40.562  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:40.562  5589  5635 I jxcore-log: 
,10-14 06:49:40.565  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:40.565  5589  5635 I jxcore-log: 
,10-14 06:49:40.570  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: ' $c@net.js:837:7
10-14 06:49:40.570  5589  5635 I jxcore-log: $09@net.js:829:13
10-14 06:49:40.570  5589  5635 I jxcore-log: '
10-14 06:49:40.570  5589  5635 I jxcore-log: 
,10-14 06:49:40.571  5589  5635 I jxcore-log: ok 4 tried to connect to right port
10-14 06:49:40.571  5589  5635 I jxcore-log: 
,10-14 06:49:40.573  5589  5635 I jxcore-log: ok 5 failed due to refused connection
10-14 06:49:40.573  5589  5635 I jxcore-log: 
10-14 06:49:40.573  5589  5635 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
10-14 06:49:40.573  5589  5635 I jxcore-log: 
,10-14 06:49:40.577  5589  5635 I jxcore-log: # teardown
10-14 06:49:40.577  5589  5635 I jxcore-log: 
,10-14 06:49:40.579  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:40.579  5589  5635 I jxcore-log: 
,10-14 06:49:40.638  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'mux close'
10-14 06:49:40.638  5589  5635 I jxcore-log: 
,10-14 06:49:40.646  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:40.646  5589  5635 I jxcore-log: 
,10-14 06:49:40.661  5589  5635 I jxcore-log: # setup
10-14 06:49:40.661  5589  5635 I jxcore-log: 
,10-14 06:49:40.734  5589  5635 I jxcore-log: # native server connections all up
10-14 06:49:40.734  5589  5635 I jxcore-log: 
,10-14 06:49:40.773  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:40.773  5589  5635 I jxcore-log: 
,10-14 06:49:40.776  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'listening 44151'
10-14 06:49:40.776  5589  5635 I jxcore-log: 
,10-14 06:49:40.784  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:40.784  5589  5635 I jxcore-log: 
,10-14 06:49:40.785  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:40.785  5589  5635 I jxcore-log: 
10-14 06:49:40.786  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new mux'
10-14 06:49:40.786  5589  5635 I jxcore-log: 
,10-14 06:49:40.812  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:40.812  5589  5635 I jxcore-log: 
,10-14 06:49:40.816  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:40.816  5589  5635 I jxcore-log: 
,10-14 06:49:40.819  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:40.819  5589  5635 I jxcore-log: 
,10-14 06:49:40.821  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:40.821  5589  5635 I jxcore-log: 
,10-14 06:49:40.847  5589  5635 I jxcore-log: ok 7 Send/recvd #1 should be equal length
10-14 06:49:40.847  5589  5635 I jxcore-log: 
,10-14 06:49:40.847  5589  5635 I jxcore-log: ok 8 Send/recvd #1 should be same
10-14 06:49:40.847  5589  5635 I jxcore-log: 
10-14 06:49:40.849  5589  5635 I jxcore-log: ok 9 Send/recvd #2 should be equal length
10-14 06:49:40.849  5589  5635 I jxcore-log: 
10-14 06:49:40.850  5589  5635 I jxcore-log: ok 10 Send/recvd #2 should be same
10-14 06:49:40.850  5589  5635 I jxcore-log: 
,10-14 06:49:40.853  5589  5635 I jxcore-log: ok 11 Should be exactly 2 client sockets
10-14 06:49:40.853  5589  5635 I jxcore-log: 
,10-14 06:49:40.860  5589  5635 I jxcore-log: # teardown
10-14 06:49:40.860  5589  5635 I jxcore-log: 
,10-14 06:49:40.903  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:40.903  5589  5635 I jxcore-log: 
,10-14 06:49:40.905  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:40.905  5589  5635 I jxcore-log: 
10-14 06:49:40.906  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'mux close'
10-14 06:49:40.906  5589  5635 I jxcore-log: 
,10-14 06:49:40.910  5589  5635 I jxcore-log: 2016-10-14 10:49:40 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:40.910  5589  5635 I jxcore-log: 
,10-14 06:49:40.922  5589  5635 I jxcore-log: # setup
10-14 06:49:40.922  5589  5635 I jxcore-log: 
,10-14 06:49:40.962  5589  5635 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
10-14 06:49:40.962  5589  5635 I jxcore-log: 
,10-14 06:49:41.026  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:41.026  5589  5635 I jxcore-log: 
,10-14 06:49:41.029  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'listening 44142'
10-14 06:49:41.029  5589  5635 I jxcore-log: 
,10-14 06:49:41.035  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:41.035  5589  5635 I jxcore-log: 
,10-14 06:49:41.036  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:41.036  5589  5635 I jxcore-log: 
10-14 06:49:41.039  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new mux'
10-14 06:49:41.039  5589  5635 I jxcore-log: 
,10-14 06:49:41.051  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:41.051  5589  5635 I jxcore-log: 
,10-14 06:49:41.053  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:41.053  5589  5635 I jxcore-log: 
,10-14 06:49:41.067  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:41.067  5589  5635 I jxcore-log: 
,10-14 06:49:41.081  5589  5635 I jxcore-log: ok 12 socket shouldn't close until after stream
10-14 06:49:41.081  5589  5635 I jxcore-log: 
,10-14 06:49:41.081  5589  5635 I jxcore-log: ok 13 incoming remains open
10-14 06:49:41.081  5589  5635 I jxcore-log: 
,10-14 06:49:41.091  5589  5635 I jxcore-log: # teardown
10-14 06:49:41.091  5589  5635 I jxcore-log: 
,10-14 06:49:41.132  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'mux close'
10-14 06:49:41.132  5589  5635 I jxcore-log: 
,10-14 06:49:41.137  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:41.137  5589  5635 I jxcore-log: 
,10-14 06:49:41.144  5589  5635 I jxcore-log: # setup
10-14 06:49:41.144  5589  5635 I jxcore-log: 
,10-14 06:49:41.198  5589  5635 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
10-14 06:49:41.198  5589  5635 I jxcore-log: 
,10-14 06:49:41.396  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:41.396  5589  5635 I jxcore-log: 
,10-14 06:49:41.402  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'listening 38992'
10-14 06:49:41.402  5589  5635 I jxcore-log: 
,10-14 06:49:41.410  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:41.410  5589  5635 I jxcore-log: 
,10-14 06:49:41.411  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:41.411  5589  5635 I jxcore-log: 
10-14 06:49:41.413  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new mux'
10-14 06:49:41.413  5589  5635 I jxcore-log: 
,10-14 06:49:41.427  5589  5635 I jxcore-log: ok 14 we should not have gotten an error
10-14 06:49:41.427  5589  5635 I jxcore-log: 
,10-14 06:49:41.433  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:41.433  5589  5635 I jxcore-log: 
,10-14 06:49:41.439  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:41.439  5589  5635 I jxcore-log: 
,10-14 06:49:41.449  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:41.449  5589  5635 I jxcore-log: 
,10-14 06:49:41.451  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:41.451  5589  5635 I jxcore-log: 
,10-14 06:49:41.460  5589  5635 I jxcore-log: ok 15 socket shouldn't close until after incoming
10-14 06:49:41.460  5589  5635 I jxcore-log: 
,10-14 06:49:41.461  5589  5635 I jxcore-log: ok 16 incoming is cleaned up
10-14 06:49:41.461  5589  5635 I jxcore-log: 
,10-14 06:49:41.472  5589  5635 I jxcore-log: # teardown
10-14 06:49:41.472  5589  5635 I jxcore-log: 
,10-14 06:49:41.565  5589  5635 I jxcore-log: # setup
10-14 06:49:41.565  5589  5635 I jxcore-log: 
,10-14 06:49:41.627  5589  5635 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
10-14 06:49:41.627  5589  5635 I jxcore-log: 
,10-14 06:49:41.689  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:41.689  5589  5635 I jxcore-log: 
,10-14 06:49:41.694  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'listening 42838'
10-14 06:49:41.694  5589  5635 I jxcore-log: 
,10-14 06:49:41.702  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:41.702  5589  5635 I jxcore-log: 
,10-14 06:49:41.704  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:41.704  5589  5635 I jxcore-log: 
,10-14 06:49:41.708  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new mux'
10-14 06:49:41.708  5589  5635 I jxcore-log: 
,10-14 06:49:41.722  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:41.722  5589  5635 I jxcore-log: 
,10-14 06:49:41.726  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:41.726  5589  5635 I jxcore-log: 
,10-14 06:49:41.740  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:41.740  5589  5635 I jxcore-log: 
,10-14 06:49:41.748  5589  5635 I jxcore-log: ok 17 stream was closed
10-14 06:49:41.748  5589  5635 I jxcore-log: 
,10-14 06:49:41.749  5589  5635 I jxcore-log: ok 18 incoming should survive
10-14 06:49:41.749  5589  5635 I jxcore-log: 
10-14 06:49:41.749  5589  5635 I jxcore-log: ok 19 mux should have no streams
10-14 06:49:41.749  5589  5635 I jxcore-log: 
,10-14 06:49:41.755  5589  5635 I jxcore-log: # teardown
10-14 06:49:41.755  5589  5635 I jxcore-log: 
,10-14 06:49:41.795  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'mux close'
10-14 06:49:41.795  5589  5635 I jxcore-log: 
,10-14 06:49:41.807  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:41.807  5589  5635 I jxcore-log: 
,10-14 06:49:41.819  5589  5635 I jxcore-log: # setup
10-14 06:49:41.819  5589  5635 I jxcore-log: 
,10-14 06:49:41.886  5589  5635 I jxcore-log: # native server - closing the whole server cleans everything up
10-14 06:49:41.886  5589  5635 I jxcore-log: 
,10-14 06:49:41.926  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:41.926  5589  5635 I jxcore-log: 
,10-14 06:49:41.931  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'listening 39227'
10-14 06:49:41.931  5589  5635 I jxcore-log: 
,10-14 06:49:41.938  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:41.938  5589  5635 I jxcore-log: 
,10-14 06:49:41.940  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:41.940  5589  5635 I jxcore-log: 
,10-14 06:49:41.943  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new mux'
10-14 06:49:41.943  5589  5635 I jxcore-log: 
,10-14 06:49:41.950  5589  5635 I jxcore-log: ok 20 we should not have gotten an error
10-14 06:49:41.950  5589  5635 I jxcore-log: 
,10-14 06:49:41.955  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:41.955  5589  5635 I jxcore-log: 
,10-14 06:49:41.957  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:41.957  5589  5635 I jxcore-log: 
,10-14 06:49:41.965  5589  5635 I jxcore-log: ok 21 Buffers are identical
10-14 06:49:41.965  5589  5635 I jxcore-log: 
,10-14 06:49:41.967  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:41.967  5589  5635 I jxcore-log: 
,10-14 06:49:41.969  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'mux close'
10-14 06:49:41.969  5589  5635 I jxcore-log: 
,10-14 06:49:41.971  5589  5635 I jxcore-log: ok 22 native server is nulled out
10-14 06:49:41.971  5589  5635 I jxcore-log: 
,10-14 06:49:41.972  5589  5635 I jxcore-log: ok 23 native server should be closed
10-14 06:49:41.972  5589  5635 I jxcore-log: 
,10-14 06:49:41.972  5589  5635 I jxcore-log: ok 24 incoming has been removed
10-14 06:49:41.972  5589  5635 I jxcore-log: 
10-14 06:49:41.972  5589  5635 I jxcore-log: ok 25 Incoming should be done
10-14 06:49:41.972  5589  5635 I jxcore-log: 
10-14 06:49:41.973  5589  5635 I jxcore-log: ok 26 The mux object should be closed
10-14 06:49:41.973  5589  5635 I jxcore-log: 
10-14 06:49:41.973  5589  5635 I jxcore-log: ok 27 The mux stream should be closed
10-14 06:49:41.973  5589  5635 I jxcore-log: 
10-14 06:49:41.974  5589  5635 I jxcore-log: 2016-10-14 10:49:41 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:41.974  5589  5635 I jxcore-log: 
,10-14 06:49:41.987  5589  5635 I jxcore-log: # teardown
10-14 06:49:41.987  5589  5635 I jxcore-log: 
,10-14 06:49:42.032  5589  5635 I jxcore-log: # setup
10-14 06:49:42.032  5589  5635 I jxcore-log: 
,10-14 06:49:42.075  5589  5635 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
10-14 06:49:42.075  5589  5635 I jxcore-log: 
,10-14 06:49:42.161  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:42.161  5589  5635 I jxcore-log: 
,10-14 06:49:42.169  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'listening 44079'
10-14 06:49:42.169  5589  5635 I jxcore-log: 
,10-14 06:49:42.204  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.204  5589  5635 I jxcore-log: 
,10-14 06:49:42.205  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.205  5589  5635 I jxcore-log: 
10-14 06:49:42.206  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.206  5589  5635 I jxcore-log: 
,10-14 06:49:42.210  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.210  5589  5635 I jxcore-log: 
,10-14 06:49:42.210  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.210  5589  5635 I jxcore-log: 
,10-14 06:49:42.212  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.212  5589  5635 I jxcore-log: 
,10-14 06:49:42.215  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.215  5589  5635 I jxcore-log: 
,10-14 06:49:42.215  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.215  5589  5635 I jxcore-log: 
10-14 06:49:42.216  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.216  5589  5635 I jxcore-log: 
10-14 06:49:42.219  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.219  5589  5635 I jxcore-log: 
,10-14 06:49:42.221  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.221  5589  5635 I jxcore-log: 
,10-14 06:49:42.222  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.222  5589  5635 I jxcore-log: 
,10-14 06:49:42.226  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.226  5589  5635 I jxcore-log: 
,10-14 06:49:42.227  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.227  5589  5635 I jxcore-log: 
,10-14 06:49:42.230  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.230  5589  5635 I jxcore-log: 
,10-14 06:49:42.239  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.239  5589  5635 I jxcore-log: 
,10-14 06:49:42.240  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.240  5589  5635 I jxcore-log: 
,10-14 06:49:42.241  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.241  5589  5635 I jxcore-log: 
,10-14 06:49:42.244  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.244  5589  5635 I jxcore-log: 
,10-14 06:49:42.244  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.244  5589  5635 I jxcore-log: 
10-14 06:49:42.245  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.245  5589  5635 I jxcore-log: 
,10-14 06:49:42.246  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.246  5589  5635 I jxcore-log: 
,10-14 06:49:42.246  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.246  5589  5635 I jxcore-log: 
10-14 06:49:42.247  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.247  5589  5635 I jxcore-log: 
,10-14 06:49:42.248  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.248  5589  5635 I jxcore-log: 
,10-14 06:49:42.248  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.248  5589  5635 I jxcore-log: 
10-14 06:49:42.249  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.249  5589  5635 I jxcore-log: 
,10-14 06:49:42.250  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.250  5589  5635 I jxcore-log: 
,10-14 06:49:42.250  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.250  5589  5635 I jxcore-log: 
10-14 06:49:42.251  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.251  5589  5635 I jxcore-log: 
,10-14 06:49:42.303  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.303  5589  5635 I jxcore-log: 
,10-14 06:49:42.305  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.305  5589  5635 I jxcore-log: 
,10-14 06:49:42.307  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.307  5589  5635 I jxcore-log: 
10-14 06:49:42.308  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.308  5589  5635 I jxcore-log: 
10-14 06:49:42.309  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.309  5589  5635 I jxcore-log: 
10-14 06:49:42.310  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.310  5589  5635 I jxcore-log: 
10-14 06:49:42.311  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.311  5589  5635 I jxcore-log: 
10-14 06:49:42.312  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.312  5589  5635 I jxcore-log: 
10-14 06:49:42.314  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.314  5589  5635 I jxcore-log: 
10-14 06:49:42.315  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.315  5589  5635 I jxcore-log: 
10-14 06:49:42.315  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.315  5589  5635 I jxcore-log: 
10-14 06:49:42.316  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.316  5589  5635 I jxcore-log: 
10-14 06:49:42.317  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.317  5589  5635 I jxcore-log: 
,10-14 06:49:42.318  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.318  5589  5635 I jxcore-log: 
,10-14 06:49:42.319  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.319  5589  5635 I jxcore-log: 
10-14 06:49:42.320  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.320  5589  5635 I jxcore-log: 
,10-14 06:49:42.321  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.321  5589  5635 I jxcore-log: 
10-14 06:49:42.322  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.322  5589  5635 I jxcore-log: 
,10-14 06:49:42.322  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.322  5589  5635 I jxcore-log: 
10-14 06:49:42.323  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.323  5589  5635 I jxcore-log: 
10-14 06:49:42.323  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.323  5589  5635 I jxcore-log: 
,10-14 06:49:42.324  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.324  5589  5635 I jxcore-log: 
,10-14 06:49:42.325  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.325  5589  5635 I jxcore-log: 
,10-14 06:49:42.326  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.326  5589  5635 I jxcore-log: 
,10-14 06:49:42.326  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.326  5589  5635 I jxcore-log: 
,10-14 06:49:42.327  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.327  5589  5635 I jxcore-log: 
10-14 06:49:42.328  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.328  5589  5635 I jxcore-log: 
,10-14 06:49:42.329  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.329  5589  5635 I jxcore-log: 
,10-14 06:49:42.329  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.329  5589  5635 I jxcore-log: 
,10-14 06:49:42.330  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.330  5589  5635 I jxcore-log: 
10-14 06:49:42.330  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.330  5589  5635 I jxcore-log: 
,10-14 06:49:42.331  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.331  5589  5635 I jxcore-log: 
,10-14 06:49:42.332  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.332  5589  5635 I jxcore-log: 
,10-14 06:49:42.333  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.333  5589  5635 I jxcore-log: 
,10-14 06:49:42.333  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.333  5589  5635 I jxcore-log: 
10-14 06:49:42.334  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.334  5589  5635 I jxcore-log: 
,10-14 06:49:42.335  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.335  5589  5635 I jxcore-log: 
,10-14 06:49:42.335  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.335  5589  5635 I jxcore-log: 
10-14 06:49:42.336  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.336  5589  5635 I jxcore-log: 
,10-14 06:49:42.336  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.336  5589  5635 I jxcore-log: 
,10-14 06:49:42.337  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.337  5589  5635 I jxcore-log: 
10-14 06:49:42.338  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.338  5589  5635 I jxcore-log: 
,10-14 06:49:42.339  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.339  5589  5635 I jxcore-log: 
,10-14 06:49:42.339  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.339  5589  5635 I jxcore-log: 
10-14 06:49:42.340  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.340  5589  5635 I jxcore-log: 
,10-14 06:49:42.341  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.341  5589  5635 I jxcore-log: 
10-14 06:49:42.341  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.341  5589  5635 I jxcore-log: 
,10-14 06:49:42.342  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.342  5589  5635 I jxcore-log: 
,10-14 06:49:42.348  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.348  5589  5635 I jxcore-log: 
,10-14 06:49:42.349  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.349  5589  5635 I jxcore-log: 
,10-14 06:49:42.349  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.349  5589  5635 I jxcore-log: 
,10-14 06:49:42.350  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.350  5589  5635 I jxcore-log: 
,10-14 06:49:42.351  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.351  5589  5635 I jxcore-log: 
,10-14 06:49:42.352  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.352  5589  5635 I jxcore-log: 
,10-14 06:49:42.352  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.352  5589  5635 I jxcore-log: 
10-14 06:49:42.353  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.353  5589  5635 I jxcore-log: 
,10-14 06:49:42.354  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.354  5589  5635 I jxcore-log: 
,10-14 06:49:42.354  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.354  5589  5635 I jxcore-log: 
,10-14 06:49:42.355  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.355  5589  5635 I jxcore-log: 
,10-14 06:49:42.356  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.356  5589  5635 I jxcore-log: 
10-14 06:49:42.356  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.356  5589  5635 I jxcore-log: 
,10-14 06:49:42.357  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.357  5589  5635 I jxcore-log: 
10-14 06:49:42.357  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.357  5589  5635 I jxcore-log: 
,10-14 06:49:42.358  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.358  5589  5635 I jxcore-log: 
,10-14 06:49:42.359  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.359  5589  5635 I jxcore-log: 
,10-14 06:49:42.360  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.360  5589  5635 I jxcore-log: 
,10-14 06:49:42.360  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.360  5589  5635 I jxcore-log: 
,10-14 06:49:42.361  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.361  5589  5635 I jxcore-log: 
10-14 06:49:42.362  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.362  5589  5635 I jxcore-log: 
,10-14 06:49:42.362  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.362  5589  5635 I jxcore-log: 
,10-14 06:49:42.363  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.363  5589  5635 I jxcore-log: 
10-14 06:49:42.364  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.364  5589  5635 I jxcore-log: 
,10-14 06:49:42.364  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.364  5589  5635 I jxcore-log: 
,10-14 06:49:42.365  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.365  5589  5635 I jxcore-log: 
,10-14 06:49:42.366  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.366  5589  5635 I jxcore-log: 
,10-14 06:49:42.366  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.366  5589  5635 I jxcore-log: 
10-14 06:49:42.367  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.367  5589  5635 I jxcore-log: 
,10-14 06:49:42.368  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.368  5589  5635 I jxcore-log: 
,10-14 06:49:42.368  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.368  5589  5635 I jxcore-log: 
,10-14 06:49:42.369  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.369  5589  5635 I jxcore-log: 
,10-14 06:49:42.414  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.414  5589  5635 I jxcore-log: 
,10-14 06:49:42.415  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.415  5589  5635 I jxcore-log: 
,10-14 06:49:42.415  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.415  5589  5635 I jxcore-log: 
,10-14 06:49:42.416  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.416  5589  5635 I jxcore-log: 
,10-14 06:49:42.417  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.417  5589  5635 I jxcore-log: 
,10-14 06:49:42.417  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.417  5589  5635 I jxcore-log: 
10-14 06:49:42.418  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.418  5589  5635 I jxcore-log: 
,10-14 06:49:42.418  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.418  5589  5635 I jxcore-log: 
10-14 06:49:42.419  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.419  5589  5635 I jxcore-log: 
,10-14 06:49:42.419  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.419  5589  5635 I jxcore-log: 
10-14 06:49:42.420  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.420  5589  5635 I jxcore-log: 
10-14 06:49:42.420  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.420  5589  5635 I jxcore-log: 
,10-14 06:49:42.420  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.420  5589  5635 I jxcore-log: 
10-14 06:49:42.421  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.421  5589  5635 I jxcore-log: 
10-14 06:49:42.422  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.422  5589  5635 I jxcore-log: 
,10-14 06:49:42.422  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.422  5589  5635 I jxcore-log: 
10-14 06:49:42.423  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.423  5589  5635 I jxcore-log: 
,10-14 06:49:42.423  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.423  5589  5635 I jxcore-log: 
10-14 06:49:42.424  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.424  5589  5635 I jxcore-log: 
10-14 06:49:42.424  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.424  5589  5635 I jxcore-log: 
,10-14 06:49:42.424  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.424  5589  5635 I jxcore-log: 
10-14 06:49:42.425  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.425  5589  5635 I jxcore-log: 
,10-14 06:49:42.425  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.425  5589  5635 I jxcore-log: 
10-14 06:49:42.426  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.426  5589  5635 I jxcore-log: 
10-14 06:49:42.426  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.426  5589  5635 I jxcore-log: 
10-14 06:49:42.427  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.427  5589  5635 I jxcore-log: 
,10-14 06:49:42.427  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.427  5589  5635 I jxcore-log: 
10-14 06:49:42.428  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.428  5589  5635 I jxcore-log: 
10-14 06:49:42.428  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.428  5589  5635 I jxcore-log: 
,10-14 06:49:42.429  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.429  5589  5635 I jxcore-log: 
10-14 06:49:42.429  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.429  5589  5635 I jxcore-log: 
,10-14 06:49:42.429  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.429  5589  5635 I jxcore-log: 
10-14 06:49:42.430  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.430  5589  5635 I jxcore-log: 
,10-14 06:49:42.430  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.430  5589  5635 I jxcore-log: 
10-14 06:49:42.431  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.431  5589  5635 I jxcore-log: 
,10-14 06:49:42.431  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.431  5589  5635 I jxcore-log: 
10-14 06:49:42.432  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.432  5589  5635 I jxcore-log: 
10-14 06:49:42.432  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.432  5589  5635 I jxcore-log: 
10-14 06:49:42.432  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.432  5589  5635 I jxcore-log: 
,10-14 06:49:42.433  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.433  5589  5635 I jxcore-log: 
10-14 06:49:42.433  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.433  5589  5635 I jxcore-log: 
10-14 06:49:42.434  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.434  5589  5635 I jxcore-log: 
,10-14 06:49:42.434  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.434  5589  5635 I jxcore-log: 
10-14 06:49:42.434  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.434  5589  5635 I jxcore-log: 
,10-14 06:49:42.436  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.436  5589  5635 I jxcore-log: 
,10-14 06:49:42.437  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.437  5589  5635 I jxcore-log: 
,10-14 06:49:42.439  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.439  5589  5635 I jxcore-log: 
,10-14 06:49:42.440  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.440  5589  5635 I jxcore-log: 
,10-14 06:49:42.440  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.440  5589  5635 I jxcore-log: 
10-14 06:49:42.441  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.441  5589  5635 I jxcore-log: 
,10-14 06:49:42.443  5589  5635 I jxcore-log: ok 28 native server is nulled out
10-14 06:49:42.443  5589  5635 I jxcore-log: 
,10-14 06:49:42.443  5589  5635 I jxcore-log: ok 29 native server should be closed
10-14 06:49:42.443  5589  5635 I jxcore-log: 
10-14 06:49:42.443  5589  5635 I jxcore-log: ok 30 incoming has been removed
10-14 06:49:42.443  5589  5635 I jxcore-log: 
,10-14 06:49:42.444  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.444  5589  5635 I jxcore-log: 
,10-14 06:49:42.444  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.444  5589  5635 I jxcore-log: 
10-14 06:49:42.445  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.445  5589  5635 I jxcore-log: 
,10-14 06:49:42.445  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.445  5589  5635 I jxcore-log: 
10-14 06:49:42.445  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.445  5589  5635 I jxcore-log: 
10-14 06:49:42.445  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.445  5589  5635 I jxcore-log: 
,10-14 06:49:42.446  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.446  5589  5635 I jxcore-log: 
10-14 06:49:42.446  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.446  5589  5635 I jxcore-log: 
10-14 06:49:42.446  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.446  5589  5635 I jxcore-log: 
10-14 06:49:42.446  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.446  5589  5635 I jxcore-log: 
,10-14 06:49:42.520  5589  5635 I jxcore-log: # teardown
10-14 06:49:42.520  5589  5635 I jxcore-log: 
,10-14 06:49:42.648  5589  5635 I jxcore-log: # setup
10-14 06:49:42.648  5589  5635 I jxcore-log: 
,10-14 06:49:42.705  5589  5635 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
10-14 06:49:42.705  5589  5635 I jxcore-log: 
,10-14 06:49:42.772  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:42.772  5589  5635 I jxcore-log: 
,10-14 06:49:42.776  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'listening 44470'
10-14 06:49:42.776  5589  5635 I jxcore-log: 
,10-14 06:49:42.784  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.784  5589  5635 I jxcore-log: 
,10-14 06:49:42.785  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.785  5589  5635 I jxcore-log: 
10-14 06:49:42.787  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:42.787  5589  5635 I jxcore-log: 
,10-14 06:49:42.796  5589  5635 I jxcore-log: ok 31 we should not have gotten an error
10-14 06:49:42.796  5589  5635 I jxcore-log: 
,10-14 06:49:42.800  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:42.800  5589  5635 I jxcore-log: 
,10-14 06:49:42.803  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:42.803  5589  5635 I jxcore-log: 
,10-14 06:49:42.810  5589  5635 I jxcore-log: ok 32 Buffers are identical
10-14 06:49:42.810  5589  5635 I jxcore-log: 
10-14 06:49:42.811  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:42.811  5589  5635 I jxcore-log: 
10-14 06:49:42.812  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'mux close'
10-14 06:49:42.812  5589  5635 I jxcore-log: 
,10-14 06:49:42.822  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:42.822  5589  5635 I jxcore-log: 
10-14 06:49:42.823  5589  5635 I jxcore-log: ok 33 server should be fine
10-14 06:49:42.823  5589  5635 I jxcore-log: 
10-14 06:49:42.823  5589  5635 I jxcore-log: ok 34 server should be open
10-14 06:49:42.823  5589  5635 I jxcore-log: 
10-14 06:49:42.823  5589  5635 I jxcore-log: ok 35 incoming has been removed
10-14 06:49:42.823  5589  5635 I jxcore-log: 
10-14 06:49:42.824  5589  5635 I jxcore-log: ok 36 The mux object should be closed
10-14 06:49:42.824  5589  5635 I jxcore-log: 
,10-14 06:49:42.824  5589  5635 I jxcore-log: ok 37 The mux stream should be closed
10-14 06:49:42.824  5589  5635 I jxcore-log: 
,10-14 06:49:42.829  5589  5635 I jxcore-log: # teardown
10-14 06:49:42.829  5589  5635 I jxcore-log: 
,10-14 06:49:42.887  5589  5635 I jxcore-log: # setup
10-14 06:49:42.887  5589  5635 I jxcore-log: 
,10-14 06:49:42.939  5589  5635 I jxcore-log: # native server - timing out the incoming connection cleans everything up
10-14 06:49:42.939  5589  5635 I jxcore-log: 
,10-14 06:49:42.985  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating native server'
10-14 06:49:42.985  5589  5635 I jxcore-log: 
,10-14 06:49:42.990  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'listening 41899'
10-14 06:49:42.990  5589  5635 I jxcore-log: 
,10-14 06:49:42.997  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new incoming socket'
10-14 06:49:42.997  5589  5635 I jxcore-log: 
,10-14 06:49:42.998  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'creating incoming mux'
10-14 06:49:42.998  5589  5635 I jxcore-log: 
10-14 06:49:43.000  5589  5635 I jxcore-log: 2016-10-14 10:49:42 - DEBUG createNativeListener: 'new mux'
10-14 06:49:43.000  5589  5635 I jxcore-log: 
,10-14 06:49:43.007  5589  5635 I jxcore-log: ok 38 we should not have gotten an error
10-14 06:49:43.007  5589  5635 I jxcore-log: 
,10-14 06:49:43.010  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG createNativeListener: 'new stream: '
10-14 06:49:43.010  5589  5635 I jxcore-log: 
,10-14 06:49:43.013  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG createNativeListener: 'new outgoing socket'
10-14 06:49:43.013  5589  5635 I jxcore-log: 
,10-14 06:49:43.019  5589  5635 I jxcore-log: ok 39 Buffers are identical
10-14 06:49:43.019  5589  5635 I jxcore-log: 
,10-14 06:49:43.022  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG createNativeListener: 'incoming socket timeout'
10-14 06:49:43.022  5589  5635 I jxcore-log: 
,10-14 06:49:43.024  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG createNativeListener: 'stream close:'
10-14 06:49:43.024  5589  5635 I jxcore-log: 
,10-14 06:49:43.025  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG createNativeListener: 'mux close'
10-14 06:49:43.025  5589  5635 I jxcore-log: 
,10-14 06:49:43.029  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG createNativeListener: 'incoming socket close'
10-14 06:49:43.029  5589  5635 I jxcore-log: 
,10-14 06:49:43.030  5589  5635 I jxcore-log: ok 40 server should be fine
10-14 06:49:43.030  5589  5635 I jxcore-log: 
10-14 06:49:43.030  5589  5635 I jxcore-log: ok 41 server should be open
10-14 06:49:43.030  5589  5635 I jxcore-log: 
,10-14 06:49:43.031  5589  5635 I jxcore-log: ok 42 incoming has been removed
10-14 06:49:43.031  5589  5635 I jxcore-log: 
10-14 06:49:43.031  5589  5635 I jxcore-log: ok 43 The mux object should be closed
10-14 06:49:43.031  5589  5635 I jxcore-log: 
10-14 06:49:43.031  5589  5635 I jxcore-log: ok 44 The mux stream should be closed
10-14 06:49:43.031  5589  5635 I jxcore-log: 
,10-14 06:49:43.038  5589  5635 I jxcore-log: # teardown
10-14 06:49:43.038  5589  5635 I jxcore-log: 
,10-14 06:49:43.074  5589  5635 I jxcore-log: # setup
10-14 06:49:43.074  5589  5635 I jxcore-log: 
,10-14 06:49:43.103  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
10-14 06:49:43.103  5589  5635 I jxcore-log: 
,10-14 06:49:43.274  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
10-14 06:49:43.274  5589  5635 I jxcore-log: 
,10-14 06:49:43.275  5589  5635 I jxcore-log: ok 45 Got right error
10-14 06:49:43.275  5589  5635 I jxcore-log: 
,10-14 06:49:43.280  5589  5635 I jxcore-log: # teardown
10-14 06:49:43.280  5589  5635 I jxcore-log: 
,10-14 06:49:43.363  5589  5635 I jxcore-log: # setup
10-14 06:49:43.363  5589  5635 I jxcore-log: 
,10-14 06:49:43.408  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
10-14 06:49:43.408  5589  5635 I jxcore-log: 
,10-14 06:49:43.505  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
10-14 06:49:43.505  5589  5635 I jxcore-log: 
,10-14 06:49:43.507  5589  5635 I jxcore-log: ok 46 Got socket hang up
10-14 06:49:43.507  5589  5635 I jxcore-log: 
,10-14 06:49:43.512  5589  5635 I jxcore-log: # teardown
10-14 06:49:43.512  5589  5635 I jxcore-log: 
,10-14 06:49:43.562  5589  5635 I jxcore-log: # setup
10-14 06:49:43.562  5589  5635 I jxcore-log: 
,10-14 06:49:43.624  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
10-14 06:49:43.624  5589  5635 I jxcore-log: 
,10-14 06:49:43.795  5589  5635 I jxcore-log: 2016-10-14 10:49:43 - DEBUG localSeqManager: 'Got an error trying to update seq []'
10-14 06:49:43.795  5589  5635 I jxcore-log: 
,10-14 06:49:43.795  5589  5635 I jxcore-log: ok 47 Got 500 as expected
10-14 06:49:43.795  5589  5635 I jxcore-log: 
,10-14 06:49:43.800  5589  5635 I jxcore-log: # teardown
10-14 06:49:43.800  5589  5635 I jxcore-log: 
,10-14 06:49:43.837  5589  5635 I jxcore-log: # setup
10-14 06:49:43.837  5589  5635 I jxcore-log: 
,10-14 06:49:43.876  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
10-14 06:49:43.876  5589  5635 I jxcore-log: 
,10-14 06:49:44.346   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:45.304  5589  5635 I jxcore-log: ok 48 should be equal
10-14 06:49:45.304  5589  5635 I jxcore-log: 
,10-14 06:49:45.304  5589  5635 I jxcore-log: ok 49 revs are equal
10-14 06:49:45.304  5589  5635 I jxcore-log: 
,10-14 06:49:45.309  5589  5635 I jxcore-log: # teardown
10-14 06:49:45.309  5589  5635 I jxcore-log: 
,10-14 06:49:45.347   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:45.913  5589  5635 I jxcore-log: # setup
10-14 06:49:45.913  5589  5635 I jxcore-log: 
,10-14 06:49:46.201  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
10-14 06:49:46.201  5589  5635 I jxcore-log: 
,10-14 06:49:46.348   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:47.349   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:47.992  5589  5635 I jxcore-log: ok 50 should be equal
10-14 06:49:47.992  5589  5635 I jxcore-log: 
,10-14 06:49:47.993  5589  5635 I jxcore-log: ok 51 revs are equal
10-14 06:49:47.993  5589  5635 I jxcore-log: 
,10-14 06:49:47.997  5589  5635 I jxcore-log: # teardown
10-14 06:49:47.997  5589  5635 I jxcore-log: 
,10-14 06:49:48.350   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:49:48.789  5589  5635 I jxcore-log: # setup
10-14 06:49:48.789  5589  5635 I jxcore-log: 
,10-14 06:49:48.962  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
10-14 06:49:48.962  5589  5635 I jxcore-log: 
,10-14 06:49:49.350   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-14 06:49:49.647  5589  5635 I jxcore-log: ok 52 should be equal
10-14 06:49:49.647  5589  5635 I jxcore-log: 
,10-14 06:49:49.648  5589  5635 I jxcore-log: ok 53 revs are equal
10-14 06:49:49.648  5589  5635 I jxcore-log: 
,10-14 06:49:49.783  5589  5635 I jxcore-log: ok 54 should be equal
10-14 06:49:49.783  5589  5635 I jxcore-log: 
,10-14 06:49:49.783  5589  5635 I jxcore-log: ok 55 revs are equal
10-14 06:49:49.783  5589  5635 I jxcore-log: 
,10-14 06:49:49.912  5589  5635 I jxcore-log: ok 56 should be equal
10-14 06:49:49.912  5589  5635 I jxcore-log: 
,10-14 06:49:49.913  5589  5635 I jxcore-log: ok 57 revs are equal
10-14 06:49:49.913  5589  5635 I jxcore-log: 
,10-14 06:49:49.920  5589  5635 I jxcore-log: # teardown
10-14 06:49:49.920  5589  5635 I jxcore-log: 
,10-14 06:49:49.985  5589  5635 I jxcore-log: # setup
10-14 06:49:49.985  5589  5635 I jxcore-log: 
,10-14 06:49:50.002  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
10-14 06:49:50.002  5589  5635 I jxcore-log: 
,10-14 06:49:50.794  5589  5635 I jxcore-log: 2016-10-14 10:49:50 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
10-14 06:49:50.794  5589  5635 I jxcore-log: 
,10-14 06:49:50.795  5589  5635 I jxcore-log: ok 58 Our rev is old so we should fail
10-14 06:49:50.795  5589  5635 I jxcore-log: 
,10-14 06:49:50.813  5589  5635 I jxcore-log: # teardown
10-14 06:49:50.813  5589  5635 I jxcore-log: 
,10-14 06:49:50.852  5589  5635 I jxcore-log: # setup
10-14 06:49:50.852  5589  5635 I jxcore-log: 
,10-14 06:49:50.896  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
10-14 06:49:50.896  5589  5635 I jxcore-log: 
,10-14 06:49:50.988  5589  5635 I jxcore-log: ok 59 confirm stop caused failure
10-14 06:49:50.988  5589  5635 I jxcore-log: 
,10-14 06:49:50.998  5589  5635 I jxcore-log: # teardown
10-14 06:49:50.998  5589  5635 I jxcore-log: 
,10-14 06:49:51.025  5589  5635 I jxcore-log: # setup
10-14 06:49:51.025  5589  5635 I jxcore-log: 
,10-14 06:49:51.129  5589  5635 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
10-14 06:49:51.129  5589  5635 I jxcore-log: 
,10-14 06:49:51.609  5589  5635 I jxcore-log: 2016-10-14 10:49:51 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
10-14 06:49:51.609  5589  5635 I jxcore-log: 
,10-14 06:49:51.610  5589  5635 I jxcore-log: ok 60 stop caused us to fail
10-14 06:49:51.610  5589  5635 I jxcore-log: 
,10-14 06:49:51.611  5589  5635 I jxcore-log: ok 61 We specifically failed on a stop before put
10-14 06:49:51.611  5589  5635 I jxcore-log: 
,10-14 06:49:51.627  5589  5635 I jxcore-log: # teardown
10-14 06:49:51.627  5589  5635 I jxcore-log: 
,10-14 06:49:51.663  5589  5635 I jxcore-log: # setup
10-14 06:49:51.663  5589  5635 I jxcore-log: 
,10-14 06:49:51.712  5589  5635 I jxcore-log: # #update - fail if stop is called
10-14 06:49:51.712  5589  5635 I jxcore-log: 
,10-14 06:49:51.781  5589  5635 I jxcore-log: ok 62 failed due to stop
10-14 06:49:51.781  5589  5635 I jxcore-log: 
,10-14 06:49:51.783  5589  5635 I jxcore-log: ok 63 failed due to stop
10-14 06:49:51.783  5589  5635 I jxcore-log: 
,10-14 06:49:51.791  5589  5635 I jxcore-log: # teardown
10-14 06:49:51.791  5589  5635 I jxcore-log: 
,10-14 06:49:51.883  5589  5635 I jxcore-log: # setup
10-14 06:49:51.883  5589  5635 I jxcore-log: 
,10-14 06:49:51.920  5589  5635 I jxcore-log: # #update - set seq for first time
10-14 06:49:51.920  5589  5635 I jxcore-log: 
,10-14 06:49:52.589  5589  5635 I jxcore-log: ok 64 should be equal
10-14 06:49:52.589  5589  5635 I jxcore-log: 
,10-14 06:49:52.612  5589  5635 I jxcore-log: # teardown
10-14 06:49:52.612  5589  5635 I jxcore-log: 
,10-14 06:49:52.678  5589  5635 I jxcore-log: # setup
10-14 06:49:52.678  5589  5635 I jxcore-log: 
,10-14 06:49:52.708  5589  5635 I jxcore-log: # #update - Fail on bad seq value
10-14 06:49:52.708  5589  5635 I jxcore-log: 
,10-14 06:49:53.289  5589  5635 I jxcore-log: 2016-10-14 10:49:53 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
10-14 06:49:53.289  5589  5635 I jxcore-log: 
,10-14 06:49:53.291  5589  5635 I jxcore-log: ok 65 Expected bad seq error
10-14 06:49:53.291  5589  5635 I jxcore-log: 
,10-14 06:49:53.312  5589  5635 I jxcore-log: # teardown
10-14 06:49:53.312  5589  5635 I jxcore-log: 
,10-14 06:49:53.695  5589  5635 I jxcore-log: # setup
10-14 06:49:53.695  5589  5635 I jxcore-log: 
,10-14 06:49:53.906  5589  5635 I jxcore-log: # #update - do we cancel timer properly on an immediate?
10-14 06:49:53.906  5589  5635 I jxcore-log: 
,10-14 06:49:54.679  5589  5635 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-14 06:49:54.679  5589  5635 E jxcore-log: 
,10-14 06:49:54.680  5589  5635 E jxcore-log: Trace: 
10-14 06:49:54.680  5589  5635 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-14 06:49:54.680  5589  5635 E jxcore-log:     at addListener@events.js:140:1
10-14 06:49:54.680  5589  5635 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:3
10-14 06:49:54.680  5589  5635 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-14 06:49:54.680  5589  5635 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-14 06:49:54.680  5589  5635 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-14 06:49:54.680  5589  5635 E jxcore-log: 
,10-14 06:49:55.213  5589  5635 I jxcore-log: ok 66 Different promises
10-14 06:49:55.213  5589  5635 I jxcore-log: 
,10-14 06:49:55.215  5589  5635 I jxcore-log: ok 67 Timer was cancelled
10-14 06:49:55.215  5589  5635 I jxcore-log: 
,10-14 06:49:55.425  5589  5635 I jxcore-log: ok 68 should be equal
10-14 06:49:55.425  5589  5635 I jxcore-log: 
,10-14 06:49:55.454  5589  5635 I jxcore-log: # teardown
10-14 06:49:55.454  5589  5635 I jxcore-log: 
,10-14 06:49:55.482  5589  5635 I jxcore-log: # setup
10-14 06:49:55.482  5589  5635 I jxcore-log: 
,10-14 06:49:56.330  5589  5635 I jxcore-log: # #update - do we wait for blocked update
10-14 06:49:56.330  5589  5635 I jxcore-log: 
,10-14 06:49:56.430  5589  5635 I jxcore-log: ok 69 One go and one blocked
10-14 06:49:56.430  5589  5635 I jxcore-log: 
10-14 06:49:56.431  5589  5635 I jxcore-log: ok 70 All blocked
10-14 06:49:56.431  5589  5635 I jxcore-log: 
,10-14 06:49:56.432  5589  5635 I jxcore-log: ok 71 Still blocked
10-14 06:49:56.432  5589  5635 I jxcore-log: 
,10-14 06:49:56.447  5589  5635 E jxcore-log: (node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
10-14 06:49:56.447  5589  5635 E jxcore-log: 
,10-14 06:49:56.449  5589  5635 E jxcore-log: Trace: 
10-14 06:49:56.449  5589  5635 E jxcore-log:     at $3.prototype.trace@console.js:139:8
10-14 06:49:56.449  5589  5635 E jxcore-log:     at addListener@events.js:140:1
10-14 06:49:56.449  5589  5635 E jxcore-log:     at module.exports@/data/data/com.test.thalitest/files/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:3
10-14 06:49:56.449  5589  5635 E jxcore-log:     at module.exports/<.start/<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:9
10-14 06:49:56.449  5589  5635 E jxcore-log:     at tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:16
10-14 06:49:56.449  5589  5635 E jxcore-log:     at module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:13
10-14 06:49:56.449  5589  5635 E jxcore-log: 
,10-14 06:49:57.084  5589  5635 I jxcore-log: ok 72 should be equal
10-14 06:49:57.084  5589  5635 I jxcore-log: 
,10-14 06:49:57.114  5589  5635 I jxcore-log: # teardown
10-14 06:49:57.114  5589  5635 I jxcore-log: 
,10-14 06:49:57.175  5589  5635 I jxcore-log: # setup
10-14 06:49:57.175  5589  5635 I jxcore-log: 
,10-14 06:49:57.222  5589  5635 I jxcore-log: # #update - test that we wait long enough
10-14 06:49:57.222  5589  5635 I jxcore-log: 
,10-14 06:49:58.424  5589  5635 I jxcore-log: ok 73 We waited long enough
10-14 06:49:58.424  5589  5635 I jxcore-log: 
,10-14 06:49:58.467   928  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 06:49:58.643  5589  5635 I jxcore-log: ok 74 should be equal
10-14 06:49:58.643  5589  5635 I jxcore-log: 
,10-14 06:49:58.699  5589  5635 I jxcore-log: # teardown
10-14 06:49:58.699  5589  5635 I jxcore-log: 
,10-14 06:49:59.841  5589  5635 I jxcore-log: # setup
10-14 06:49:59.841  5589  5635 I jxcore-log: 
,10-14 06:49:59.859  5589  5635 I jxcore-log: # #update - test that we pick up new sequences while we wait
10-14 06:49:59.859  5589  5635 I jxcore-log: 
,10-14 06:50:01.099  5589  5635 I jxcore-log: ok 75 Should have gotten same timer promise
10-14 06:50:01.099  5589  5635 I jxcore-log: 
,10-14 06:50:01.100  5589  5635 I jxcore-log: ok 76 Still same timer promise
10-14 06:50:01.100  5589  5635 I jxcore-log: 
,10-14 06:50:01.688  5589  5635 I jxcore-log: ok 77 We waited long enough
10-14 06:50:01.688  5589  5635 I jxcore-log: 
,10-14 06:50:01.820  5589  5635 I jxcore-log: ok 78 should be equal
10-14 06:50:01.820  5589  5635 I jxcore-log: 
,10-14 06:50:01.899  5589  5635 I jxcore-log: # teardown
10-14 06:50:01.899  5589  5635 I jxcore-log: 
,10-14 06:50:02.914  5589  5635 I jxcore-log: # setup
10-14 06:50:02.914  5589  5635 I jxcore-log: 
,10-14 06:50:02.969  5589  5635 I jxcore-log: # Coordinated seq test
10-14 06:50:02.969  5589  5635 I jxcore-log: 
,10-14 06:50:03.759  5589  5635 I jxcore-log: 2016-10-14 10:50:03 - DEBUG thaliWifiInfrastructure: 'listening 37124'
10-14 06:50:03.759  5589  5635 I jxcore-log: 
,10-14 06:50:04.351   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:05.352   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:06.354   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:07.354   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:07.649  5589  5635 I jxcore-log: 2016-10-14 10:50:07 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
10-14 06:50:07.649  5589  5635 I jxcore-log: 
,10-14 06:50:08.355   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:08.893  5589  5635 I jxcore-log: ok 79 should be equal
10-14 06:50:08.893  5589  5635 I jxcore-log: 
,10-14 06:50:09.356   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-14 06:50:09.693  5589  5635 I jxcore-log: ok 80 should be equal
10-14 06:50:09.693  5589  5635 I jxcore-log: 
,10-14 06:50:09.705  5589  5635 I jxcore-log: # teardown
10-14 06:50:09.705  5589  5635 I jxcore-log: 
,10-14 06:50:18.470   928  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 06:50:29.357   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:30.359   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:31.361   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:32.362   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:33.363   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,10-14 06:50:34.364   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-14 06:50:58.475   928  2960 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-14 06:50:59.365   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-14 06:50:59.365   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-14 06:51:09.723  5589  5635 I jxcore-log: 2016-10-14 10:51:09 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
10-14 06:51:09.723  5589  5635 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-14 06:51:09.723  5589  5635 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-14 06:51:09.723  5589  5635 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-14 06:51:09.723  5589  5635 I jxcore-log:     at $9@timers.js:120:1
10-14 06:51:09.723  5589  5635 I jxcore-log: ''
10-14 06:51:09.723  5589  5635 I jxcore-log: 
,10-14 06:51:09.725  5589  5635 I jxcore-log: 2016-10-14 10:51:09 - DEBUG CoordinatedClient: 'test client failed'
10-14 06:51:09.725  5589  5635 I jxcore-log: 
,10-14 06:51:09.734  5589  5635 I jxcore-log: 2016-10-14 10:51:09 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-14 06:51:09.734  5589  5635 I jxcore-log: 
,10-14 06:51:09.738  5589  5635 I jxcore-log: 2016-10-14 10:51:09 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
10-14 06:51:09.738  5589  5635 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
10-14 06:51:09.738  5589  5635 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
10-14 06:51:09.738  5589  5635 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
10-14 06:51:09.738  5589  5635 I jxcore-log:     at $9@timers.js:120:1
10-14 06:51:09.738  5589  5635 I jxcore-log: ''
10-14 06:51:09.738  5589  5635 I jxcore-log: 
,10-14 06:51:09.739  5589  5635 I jxcore-log: 2016-10-14 10:51:09 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-14 06:51:09.739  5589  5635 I jxcore-log: 
,10-14 06:51:09.811   928  2925 W InputDispatcher: channel '97952b4 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-14 06:51:09.811   928  2925 E InputDispatcher: channel '97952b4 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-14 06:51:09.820   928  3142 I WindowState: WIN DEATH: Window{97952b4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-14 06:51:09.820   928  3139 D GraphicsStats: Buffer count: 2
,10-14 06:51:09.821   928  3142 W InputDispatcher: Attempted to unregister already unregistered input channel '97952b4 com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-14 06:51:09.822   928  2961 D WifiService: Client connection lost with reason: 4
10-14 06:51:09.827   928   938 I ActivityManager: Process com.test.thalitest (pid 5589) has died
10-14 06:51:09.826   529   529 I Zygote  : Process 5589 exited cleanly (139)
,10-14 06:51:09.855   928   938 I ActivityManager: Start proc 5962:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-14 06:51:10.189   928  3767 I WindowManager: Screenshot max retries 4 of Token{e14ce66 ActivityRecord{fdab6c1 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{e05c83b u0 Starting com.test.thalitest} drawState=4
,10-14 06:51:10.267  5962  5962 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-14 06:51:10.284  5962  5962 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-14 06:51:10.291  5962  5962 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5624-5627)
,10-14 06:51:10.291  5962  5962 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-14 06:51:10.300  5962  5962 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {60abbc3}
,10-14 06:51:10.300  5962  5962 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-14 06:51:10.300  5962  5962 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-14 06:51:10.303  5962  5962 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-14 06:51:10.304  5962  5962 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-14 06:51:10.315  5962  5962 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-14 06:51:10.317  5960  5960 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-14 06:51:10.323  5962  5962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-14 06:51:10.323  5962  5962 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-14 06:51:10.323  5962  5962 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-14 06:51:10.323  5962  5962 I Adreno  : Build Date                       : 12/06/15
10-14 06:51:10.323  5962  5962 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-14 06:51:10.323  5962  5962 I Adreno  : Local Branch                     : mybranch17112971
10-14 06:51:10.323  5962  5962 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-14 06:51:10.323  5962  5962 I Adreno  : Remote Branch                    : NONE
10-14 06:51:10.323  5962  5962 I Adreno  : Reconstruct Branch               : NOTHING
,10-14 06:51:10.332  5960  5960 D AndroidRuntime: CheckJNI is OFF
,10-14 06:51:10.355   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@aff4d70:true
,10-14 06:51:10.357  5960  5960 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-14 06:51:10.372  4173  4173 W Binder_5: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32654]" dev="sockfs" ino=32654 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 06:51:10.372  4173  4173 W Binder_5: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32654]" dev="sockfs" ino=32654 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-14 06:51:10.385  5962  5962 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-14 06:51:10.385  5960  5960 I Radio-JNI: register_android_hardware_Radio DONE
,10-14 06:51:10.392  5962  5962 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-14 06:51:10.400  5960  5960 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-14 06:51:10.407   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-14 06:51:10.407   928   941 I ActivityManager: Killing 5962:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-14 06:51:10.451   928   941 I ActivityManager: Start proc 6005:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-14 06:51:10.452   928   941 I ActivityManager:   Force finishing activity ActivityRecord{fdab6c1 u0 com.test.thalitest/.MainActivity t2}
,10-14 06:51:10.466   928   946 W WindowManager: Failed looking up window
10-14 06:51:10.466   928   946 W WindowManager: java.lang.IllegalArgumentException: Requested window android.view.ViewRootImpl$W@30ceca does not exist
10-14 06:51:10.466   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8718)
10-14 06:51:10.466   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8709)
10-14 06:51:10.466   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService.removeWindow(WindowManagerService.java:2697)
10-14 06:51:10.466   928   946 W WindowManager: 	at com.android.server.wm.Session.remove(Session.java:187)
10-14 06:51:10.466   928   946 W WindowManager: 	at android.view.ViewRootImpl.dispatchDetachedFromWindow(ViewRootImpl.java:3107)
10-14 06:51:10.466   928   946 W WindowManager: 	at android.view.ViewRootImpl.doDie(ViewRootImpl.java:5616)
10-14 06:51:10.466   928   946 W WindowManager: 	at android.view.ViewRootImpl$ViewRootHandler.handleMessage(ViewRootImpl.java:3417)
10-14 06:51:10.466   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:10.466   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:10.466   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 06:51:10.466   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-14 06:51:10.468   928  3871 W ActivityManager: Spurious death for ProcessRecord{aac3e59 0:com.test.thalitest/u0a77}, curProc for 5962: null
,10-14 06:51:10.568   928   951 I art     : Starting a blocking GC Explicit
,10-14 06:51:10.593  6005  6005 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/cache
,10-14 06:51:10.593  6005  6005 V ActivityThread: Unable to initialize "java.io.tmpdir" property due to missing cache directory
10-14 06:51:10.593  6005  6005 W ContextImpl: Unable to create files subdir /data/user/0/com.test.thalitest/code_cache
10-14 06:51:10.593  6005  6005 E ActivityThread: Unable to setupGraphicsSupport due to missing code-cache directory
,10-14 06:51:10.616  6005  6005 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
10-14 06:51:10.617  6005  6005 E AndroidRuntime: FATAL EXCEPTION: main
10-14 06:51:10.617  6005  6005 E AndroidRuntime: Process: com.test.thalitest, PID: 6005
10-14 06:51:10.617  6005  6005 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application android.app.Application: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:578)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4685)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: Caused by: java.lang.IllegalStateException: Unable to get package info for com.test.thalitest; is package not installed?
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.app.LoadedApk.initializeJavaContextClassLoader(LoadedApk.java:424)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:570)
10-14 06:51:10.617  6005  6005 E AndroidRuntime: 	... 9 more
,10-14 06:51:10.622  6005  6005 I Process : Sending signal. PID: 6005 SIG: 9
,10-14 06:51:10.652   928  3832 I ActivityManager: Process com.test.thalitest (pid 6005) has died
,10-14 06:51:10.669   928   951 I art     : Explicit concurrent mark sweep GC freed 81323(5MB) AllocSpace objects, 43(1436KB) LOS objects, 33% free, 29MB/43MB, paused 2.088ms total 100.091ms
,10-14 06:51:10.688   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-14 06:51:10.691  5960  5960 I art     : System.exit called, status: 0
,10-14 06:51:10.691  5960  5960 I AndroidRuntime: VM exiting with result code 0.
,10-14 06:51:10.705   928   951 I ActivityManager: Start proc 6019:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
10-14 06:51:10.705   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-14 06:51:10.715  3642  3642 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-14 06:51:10.717  5862  5862 D BluetoothMapAppObserver: onReceive
10-14 06:51:10.717  5862  5862 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-14 06:51:10.718  4053  4172 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-14 06:51:10.726   928  2926 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-14 06:51:10.757  3642  6031 I Keyboard.Facilitator.DecoderInitializer: run()
,10-14 06:51:10.775    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 06:51:10.779    29    29 W kworker/3:1: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 06:51:10.782  3766  3766 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-14 06:51:10.794  3555  3555 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
10-14 06:51:10.795  3555  3555 D AndroidRuntime: Shutting down VM
,10-14 06:51:10.792    29    29 W kworker/3:1: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-14 06:51:10.797   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-14 06:51:10.798  3555  3555 E AndroidRuntime: FATAL EXCEPTION: main
10-14 06:51:10.798  3555  3555 E AndroidRuntime: Process: com.google.process.gapps, PID: 3555
10-14 06:51:10.798  3555  3555 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-14 06:51:10.798  3555  3555 E AndroidRuntime: 	... 8 more
,10-14 06:51:10.801  3642  6031 I Decoder : createOrResetDecoder
,10-14 06:51:10.802   928   940 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
10-14 06:51:10.802  3800  3943 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
10-14 06:51:10.802  3383  6034 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
10-14 06:51:10.803   928   940 E PackageManager: Failed to write settings, restoring backup
10-14 06:51:10.803   928   940 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
10-14 06:51:10.803   928   940 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
10-14 06:51:10.803   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
10-14 06:51:10.803   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
10-14 06:51:10.803   928   940 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
10-14 06:51:10.803   928   940 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:10.803   928   940 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:10.803   928   940 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 06:51:10.804  3555  3555 I Process : Sending signal. PID: 3555 SIG: 9
10-14 06:51:10.805   928  6039 E DropBoxManagerService: Can't write: system_app_crash
10-14 06:51:10.805   928  6039 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 06:51:10.805   928  6039 E DropBoxManagerService: 	... 5 more
10-14 06:51:10.806   928   941 E DropBoxManagerService: Can't write: system_server_wtf
10-14 06:51:10.806   928   941 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
10-14 06:51:10.806   928   941 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438,)
10-14 06:51:10.806   928   941 E DropBoxManagerService: 	... 13 more
,10-14 06:51:10.817   928  3139 I ActivityManager: Start proc 6040:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-14 06:51:10.818  3800  3943 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-14 06:51:10.818  3800  3943 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3800
10-14 06:51:10.818  3800  3943 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:10.818  3800  3943 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 06:51:10.822   928  3767 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 06:51:10.824   928  6046 E DropBoxManagerService: Can't write: system_app_crash
10-14 06:51:10.824   928  6046 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 06:51:10.824   928  6046 E DropBoxManagerService: 	... 5 more
,10-14 06:51:10.827  3800  3943 I Process : Sending signal. PID: 3800 SIG: 9
,10-14 06:51:10.843   928  2961 D WifiService: Client connection lost with reason: 4
,10-14 06:51:10.847  3383  3408 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjE0F57197B) - 
10-14 06:51:10.848   928  3834 I ActivityManager: Process com.google.process.gapps (pid 3555) has died
10-14 06:51:10.848  3383  3408 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-14 06:51:10.848  3383  3408 E AndroidRuntime: Process: android.process.acore, PID: 3383
10-14 06:51:10.848  3383  3408 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:10.848  3383  3408 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-14 06:51:10.849   928  3834 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
10-14 06:51:10.849   928  3834 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
10-14 06:51:10.849   928  3834 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,10-14 06:51:10.853   928  6054 E DropBoxManagerService: Can't write: system_app_crash
10-14 06:51:10.853   928  6054 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 06:51:10.853   928  6054 E DropBoxManagerService: 	... 5 more
,10-14 06:51:10.870   928  3871 I ActivityManager: Start proc 6056:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,10-14 06:51:10.882  3383  6034 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
10-14 06:51:10.883  3383  6034 I Process : Sending signal. PID: 3383 SIG: 9
,10-14 06:51:10.937   928  2925 W InputDispatcher: channel 'c45a077 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-14 06:51:10.938   928  2925 E InputDispatcher: channel 'c45a077 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-14 06:51:10.938   928  3871 I WindowState: WIN DEATH: Window{c45a077 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
10-14 06:51:10.938   928  3142 D GraphicsStats: Buffer count: 1
10-14 06:51:10.939   928  3871 W InputDispatcher: Attempted to unregister already unregistered input channel 'c45a077 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-14 06:51:10.954   928  3767 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3800) has died
10-14 06:51:10.955   928  3767 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,10-14 06:51:10.958   928  3767 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 06:51:10.973   928   941 I ActivityManager: Start proc 6069:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 06:51:10.973   928  3871 I ActivityManager: Process android.process.acore (pid 3383) has died
10-14 06:51:10.974   928  3871 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-14 06:51:11.015  6069  6069 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:51:11.015  6069  6069 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 06:51:11.015  6069  6069 D AndroidRuntime: Shutting down VM
,10-14 06:51:11.021  6069  6069 E AndroidRuntime: FATAL EXCEPTION: main
10-14 06:51:11.021  6069  6069 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6069
10-14 06:51:11.021  6069  6069 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 06:51:11.021  6069  6069 E AndroidRuntime: 	... 10 more
10-14 06:51:11.023   928  3832 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-14 06:51:11.023   928  6082 E DropBoxManagerService: Can't write: system_app_crash
10-14 06:51:11.023   928  6082 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 06:51:11.023   928  6082 E DropBoxManagerService: 	... 5 more
10-14 06:51:11.024  6069  6069 I Process : Sending signal. PID: 6069 SIG: 9
,10-14 06:51:11.034   928  3139 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6069) has died
10-14 06:51:11.035   928  3139 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 06:51:11.049   928   941 I ActivityManager: Start proc 6083:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 06:51:11.099  6083  6083 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:51:11.099  6083  6083 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-14 06:51:11.099  6083  6083 D AndroidRuntime: Shutting down VM
,10-14 06:51:11.107  6083  6083 E AndroidRuntime: FATAL EXCEPTION: main
10-14 06:51:11.107  6083  6083 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6083
10-14 06:51:11.107  6083  6083 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-14 06:51:11.107  6083  6083 E AndroidRuntime: 	... 10 more
10-14 06:51:11.109   928  3834 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-14 06:51:11.110   928  6095 E DropBoxManagerService: Can't write: system_app_crash
10-14 06:51:11.110   928  6095 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-14 06:51:11.110   928  6095 E DropBoxManagerService: 	... 5 more
10-14 06:51:11.111  6083  6083 I Process : Sending signal. PID: 6083 SIG: 9
,10-14 06:51:11.147   928  3871 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6083) has died
,10-14 06:51:11.148   928  3871 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-14 06:51:11.165   928   941 I ActivityManager: Start proc 6096:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-14 06:51:11.169   380   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
