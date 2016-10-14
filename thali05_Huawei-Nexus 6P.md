#### Test 88496963b6c922d_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-13 20:08:27.740   926  5370 D NetlinkSocketObserver: NeighborEvent{elapsedMs=205598, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-13 20:08:28.223  5604  5604 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-13 20:08:28.229  5604  5604 D AndroidRuntime: CheckJNI is OFF
10-13 20:08:28.252  5604  5604 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-13 20:08:28.281  5604  5604 I Radio-JNI: register_android_hardware_Radio DONE
10-13 20:08:28.296  5604  5604 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-13 20:08:28.300   926  3103 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-13 20:08:28.344   926  3103 I ActivityManager: Start proc 5613:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-13 20:08:28.361  5604  5604 D AndroidRuntime: Shutting down VM
,10-13 20:08:28.691   926   937 I WindowManager: Screenshot max retries 4 of Token{72e0d56 ActivityRecord{f06db71 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{5b487a9 u0 Starting com.test.thalitest} drawState=2
,10-13 20:08:28.756  5613  5613 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-13 20:08:28.789  5613  5613 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-13 20:08:28.812  5613  5613 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 6651-6670)
,10-13 20:08:28.812  5613  5613 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-13 20:08:28.831  5613  5613 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8a51057}
10-13 20:08:28.832  5613  5613 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-13 20:08:28.832  5613  5613 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
10-13 20:08:28.837  5613  5613 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-13 20:08:28.838  5613  5613 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-13 20:08:28.874  5613  5613 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-13 20:08:28.893  5613  5613 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-13 20:08:28.893  5613  5613 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-13 20:08:28.893  5613  5613 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-13 20:08:28.893  5613  5613 I Adreno  : Build Date                       : 12/06/15
10-13 20:08:28.893  5613  5613 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-13 20:08:28.893  5613  5613 I Adreno  : Local Branch                     : mybranch17112971
10-13 20:08:28.893  5613  5613 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-13 20:08:28.893  5613  5613 I Adreno  : Remote Branch                    : NONE
10-13 20:08:28.893  5613  5613 I Adreno  : Reconstruct Branch               : NOTHING
,10-13 20:08:28.936   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c5eecf4:true
,10-13 20:08:28.959  2916  2916 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[25307]" dev="sockfs" ino=25307 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:28.959  2916  2916 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[25307]" dev="sockfs" ino=25307 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:28.971  5613  5613 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-13 20:08:28.981  5613  5613 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-13 20:08:29.006  5613  5650 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
10-13 20:08:29.002   713   713 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31854]" dev="sockfs" ino=31854 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:29.002   713   713 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31854]" dev="sockfs" ino=31854 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:29.005  3802  3802 W Binder_7: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14179]" dev="sockfs" ino=14179 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:29.005  3802  3802 W Binder_7: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14179]" dev="sockfs" ino=14179 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:29.011  5613  5637 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-13 20:08:29.041  5613  5650 I OpenGLRenderer: Initialized EGL, version 1.4
,10-13 20:08:29.115   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +423ms (total +802ms)
,10-13 20:08:29.136  5613  5613 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5613
,10-13 20:08:29.218  5613  5613 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-13 20:08:29.336  5613  5653 D jxcore_app_log: JniHelper::setJavaVM(0xf55fc000), pthread_self() = -583792336
,10-13 20:08:29.339  5613  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-13 20:08:29.339  5613  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-13 20:08:29.339  5613  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-13 20:08:29.339  5613  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-13 20:08:29.339  5613  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-13 20:08:29.339  5613  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@961839c added. We now have 1 listener(s)
,10-13 20:08:29.341  5613  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-13 20:08:29.342  5613  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-13 20:08:29.342  5613  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-13 20:08:29.343  5613  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-13 20:08:29.344  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-13 20:08:29.345  5613  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c8c52b added. We now have 1 listener(s)
10-13 20:08:29.345  5613  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-13 20:08:29.349   926  2951 D WifiService: New client listening to asynchronous messages
10-13 20:08:29.349  5613  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-13 20:08:29.349  5613  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-13 20:08:29.349  5613  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-13 20:08:29.350  5613  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,10-13 20:08:29.350  5613  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
10-13 20:08:29.352  5613  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:08:29.352  5613  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-13 20:08:29.357  5613  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:08:29.357  5613  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:08:29.357  5613  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-13 20:08:29.357  5613  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-13 20:08:29.357  5613  5653 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-13 20:08:29.361  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:29.366  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:29.373  5613  5613 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-13 20:08:29.659  5613  5659 W jxcore-log: Initializing JXcore engine
,10-13 20:08:29.659  5613  5659 W jxcore-log: JXcore engine is ready
,10-13 20:08:29.679  5659  5659 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12585 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-13 20:08:29.679  5659  5659 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15490]" dev="sockfs" ino=15490 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-13 20:08:29.679  5659  5659 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-13 20:08:29.679  5659  5659 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31832]" dev="sockfs" ino=31832 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-13 20:08:29.691  5613  5659 W jxcore-log: Starting JXcore engine
,10-13 20:08:29.740  5613  5659 W jxcore-log: Platform android
10-13 20:08:29.740  5613  5659 W jxcore-log: 
,10-13 20:08:29.740  5613  5659 W jxcore-log: Process ARCH arm
10-13 20:08:29.740  5613  5659 W jxcore-log: 
,10-13 20:08:29.849  5613  5659 I jxcore-log: JXcore Cordova bridge is ready!
10-13 20:08:29.849  5613  5659 I jxcore-log: 
10-13 20:08:29.849  5613  5659 W jxcore-log: JXcore engine is started
,10-13 20:08:29.857  5613  5653 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-13 20:08:29.860  5613  5613 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-13 20:08:38.966   926  5370 D NetlinkSocketObserver: NeighborEvent{elapsedMs=216824, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-13 20:08:39.534  5613  5659 I jxcore-log: 2016-10-14 00:08:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-13 20:08:39.534  5613  5659 I jxcore-log: 
,10-13 20:08:39.536  5613  5659 I jxcore-log: 2016-10-14 00:08:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-13 20:08:39.536  5613  5659 I jxcore-log: 
,10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:08:39.541  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:08:39.542  5613  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:39.544  5613  5659 I jxcore-log: 2016-10-14 00:08:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-13 20:08:39.544  5613  5659 I jxcore-log: 
,10-13 20:08:39.545  5613  5659 I jxcore-log: 2016-10-14 00:08:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-13 20:08:39.545  5613  5659 I jxcore-log: 
,10-13 20:08:39.797  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-13 20:08:39.797  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@87ed13c added. We now have 2 listener(s)
10-13 20:08:39.798  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-13 20:08:39.798  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-13 20:08:39.798  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-13 20:08:39.798  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-13 20:08:39.799  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2278ec5 added. We now have 2 listener(s)
10-13 20:08:39.799  5613  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-13 20:08:39.799  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-13 20:08:39.801  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:08:39.804  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:08:39.805  5613  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:39.805  5613  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-13 20:08:39.806  5613  5659 D ExecuteNativeTests: Running unit tests
10-13 20:08:39.806  5613  5659 D BluetoothAdapter: enable(): BT is already enabled..!
,10-13 20:08:39.807   926  3549 D WifiService: setWifiEnabled: true pid=5613, uid=10077
10-13 20:08:39.807   926  3549 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-13 20:08:39.808  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:39.810  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:40.661   534   534 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-13 20:08:40.661   534   534 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-13 20:08:43.570   926  2950 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-13 20:08:49.813  5613  5659 I com.test.thalitest.ThaliTestRunner: Running UT
,10-13 20:08:49.877  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-13 20:08:49.877  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53f090f added. We now have 3 listener(s)
10-13 20:08:49.878  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-13 20:08:49.878  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-13 20:08:49.878  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-13 20:08:49.878  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-13 20:08:49.878  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1339d9c added. We now have 3 listener(s)
,10-13 20:08:49.878  5613  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-13 20:08:49.879  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-13 20:08:49.881  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:08:49.886  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:08:49.892  5613  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:08:49.892  5613  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-13 20:08:49.896  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
10-13 20:08:49.896  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-13 20:08:49.897  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-13 20:08:49.897  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:49.897  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:49.898  5613  5659 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-13 20:08:49.898  5613  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-13 20:08:49.898  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-13 20:08:49.898  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-13 20:08:49.898  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-13 20:08:49.898  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-13 20:08:49.899  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
10-13 20:08:49.899  5613  5659 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-13 20:08:49.900  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:49.900  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
10-13 20:08:49.902  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-13 20:08:49.902  5613  5659 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-13 20:08:49.905  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:49.906  5613  5659 V io.jxcore.node.ConnectivityMonitor: start: Already started
,10-13 20:08:49.906  5613  5659 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
10-13 20:08:49.906  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
10-13 20:08:49.906  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-13 20:08:49.906  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-13 20:08:49.906  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-13 20:08:49.906  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:08:49.907  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-13 20:08:49.907  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-13 20:08:49.908  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-13 20:08:49.908  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-13 20:08:49.908  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-13 20:08:49.908  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-13 20:08:49.908  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:08:49.908  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-13 20:08:49.908  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-13 20:08:49.909  5613  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-13 20:08:49.910  5613  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-13 20:08:49.910  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-13 20:08:49.913  5613  5663 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:08:49.909  4773  4773 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[14199]" dev="sockfs" ino=14199 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:49.914  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-13 20:08:49.909  4773  4773 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[14199]" dev="sockfs" ino=14199 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:08:49.916  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-13 20:08:49.916  5613  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-13 20:08:49.916  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-13 20:08:49.917  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-13 20:08:49.917  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-13 20:08:49.918  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
10-13 20:08:49.918  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:08:49.918  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
,10-13 20:08:49.918  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-13 20:08:49.918  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:08:49.919  5613  5659 D BluetoothAdapter: STATE_ON
,10-13 20:08:49.922  4561  4572 D BtGatt.GattService: registerClient() - UUID=060c3bed-e0cd-456b-8d62-9a31b2215cb6
,10-13 20:08:49.923  4561  4636 D BtGatt.GattService: onClientRegistered() - UUID=060c3bed-e0cd-456b-8d62-9a31b2215cb6, clientIf=5
,10-13 20:08:49.928  5613  5623 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-13 20:08:49.933  4561  4638 D BtGatt.AdvertiseManager: message : 0
,10-13 20:08:49.936  4561  4638 D BtGatt.AdvertiseManager: starting multi advertising
,10-13 20:08:49.953  4561  4636 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-13 20:08:49.962  4561  4636 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-13 20:08:49.963  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-13 20:08:49.964  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-13 20:08:49.964  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-13 20:08:49.964  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-13 20:08:49.964  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-13 20:08:49.965  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-13 20:08:49.967  5613  5659 I io.jxcore.node.ConnectionHelper: start: OK
,10-13 20:08:49.967  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-13 20:08:49.968  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-13 20:08:49.968  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-13 20:08:49.968  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-13 20:08:49.969  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-13 20:08:49.969  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:08:49.970  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-13 20:08:49.970  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-13 20:08:49.970  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-13 20:08:49.970  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-13 20:08:49.973  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-13 20:08:49.973  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-13 20:08:50.471  5613  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-13 20:08:50.471  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-13 20:08:50.471  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-13 20:08:50.471  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,10-13 20:08:50.471  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-13 20:08:50.471  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-13 20:08:50.471  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-13 20:08:50.471  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,10-13 20:08:50.472  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-13 20:08:50.472  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-13 20:08:50.472  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-13 20:08:50.472  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-13 20:08:50.472  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,10-13 20:08:50.472  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-13 20:08:50.472  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-13 20:08:50.473  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-13 20:08:50.474  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-13 20:08:50.474  5613  5659 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-13 20:08:50.475  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-13 20:08:50.475  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-13 20:08:50.475  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-13 20:08:50.475  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-13 20:08:50.475  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-13 20:08:50.475  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-13 20:08:50.476  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-13 20:08:50.476  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-13 20:08:50.476  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-13 20:08:50.476  5613  5663 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-13 20:08:50.476  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-13 20:08:50.476  5613  5663 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-13 20:08:50.476  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-13 20:08:50.476  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-13 20:08:50.476  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-13 20:08:50.476  5613  5663 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-13 20:08:50.478  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-13 20:08:50.479  5613  5659 D BluetoothAdapter: STATE_ON
,10-13 20:08:50.479  5613  5659 D BluetoothLeScanner: could not find callback wrapper
10-13 20:08:50.479  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-13 20:08:50.480  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-13 20:08:50.481  4561  4638 D BtGatt.AdvertiseManager: message : 1
10-13 20:08:50.483  4561  4638 D BtGatt.AdvertiseManager: stop advertise for client 5
10-13 20:08:50.495  4561  4636 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-13 20:08:50.495  4561  4636 D BtGatt.GattService: Client app is not null!
10-13 20:08:50.497  4561  4572 D BtGatt.GattService: unregisterClient() - clientIf=5
10-13 20:08:50.497  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-13 20:08:50.498  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-13 20:08:50.498  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-13 20:08:50.499  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-13 20:08:50.499  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:08:50.499  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-13 20:08:50.499  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-13 20:08:50.499  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-13 20:08:50.499  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-13 20:08:50.505  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-13 20:08:50.505  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-13 20:08:50.505  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-13 20:08:50.506  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-13 20:08:50.507  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-13 20:08:50.508  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-13 20:08:50.509  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-13 20:08:50.510  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:08:50.510  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-13 20:08:50.510  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-13 20:08:50.510  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:08:50.510  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-13 20:08:50.512  5613  5659 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-13 20:08:50.512  5613  5659 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-13 20:08:50.512  5613  5659 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-13 20:08:50.512  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-13 20:08:50.513  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-13 20:08:50.513  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-13 20:08:50.513  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-13 20:08:50.513  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:08:50.514  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-13 20:08:50.514  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-13 20:08:50.515  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-13 20:08:50.515  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-13 20:08:50.515  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-13 20:08:50.515  5613  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-13 20:08:50.515  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-13 20:08:50.515  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-13 20:08:50.515  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:08:50.515  4573  4573 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32859]" dev="sockfs" ino=32859 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:08:50.515  4573  4573 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32859]" dev="sockfs" ino=32859 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:08:50.515  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-13 20:08:50.516  5613  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:08:50.519  5613  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-13 20:08:50.521  5613  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-13 20:08:50.521  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-13 20:08:50.526  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-13 20:08:50.526  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-13 20:08:50.526  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-13 20:08:50.528  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-13 20:08:50.528  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-13 20:08:50.529  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
10-13 20:08:50.529  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-13 20:08:50.529  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-13 20:08:50.529  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-13 20:08:50.529  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-13 20:08:50.530  5613  5659 D BluetoothAdapter: STATE_ON
,10-13 20:08:50.534  4561  4573 D BtGatt.GattService: registerClient() - UUID=86ec54fa-89da-4544-ae67-484593836f20
,10-13 20:08:50.534  4561  4636 D BtGatt.GattService: onClientRegistered() - UUID=86ec54fa-89da-4544-ae67-484593836f20, clientIf=5
,10-13 20:08:50.535  5613  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-13 20:08:50.536  4561  4638 D BtGatt.AdvertiseManager: message : 0
,10-13 20:08:50.539  4561  4638 D BtGatt.AdvertiseManager: starting multi advertising
,10-13 20:08:50.551  4561  4636 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-13 20:08:50.557  4561  4636 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-13 20:08:50.558  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
,10-13 20:08:50.558  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-13 20:08:50.558  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-13 20:08:50.558  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-13 20:08:50.558  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-13 20:08:50.560  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-13 20:08:50.561  5613  5659 I io.jxcore.node.ConnectionHelper: start: OK
10-13 20:08:50.561  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-13 20:08:50.561  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,10-13 20:08:50.562  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-13 20:08:50.562  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-13 20:08:50.562  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-13 20:08:50.562  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:08:50.562  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-13 20:08:50.562  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-13 20:08:50.562  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-13 20:08:50.562  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-13 20:08:50.565  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-13 20:08:50.565  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-13 20:08:50.662   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:08:51.065  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,10-13 20:08:51.065  5613  5659 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-13 20:08:51.065  5613  5659 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-13 20:08:51.066  5613  5659 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-13 20:08:51.066  5613  5659 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
10-13 20:08:51.066  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-13 20:08:51.066  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-13 20:08:51.072  4561  4638 D BtGatt.AdvertiseManager: message : 1
10-13 20:08:51.073  4561  4638 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-13 20:08:51.087  4561  4636 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-13 20:08:51.087  4561  4636 D BtGatt.GattService: Client app is not null!
10-13 20:08:51.088  4561  4572 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-13 20:08:51.089  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-13 20:08:51.089  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
,10-13 20:08:51.089  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-13 20:08:51.089  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-13 20:08:51.090  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-13 20:08:51.090  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-13 20:08:51.090  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
10-13 20:08:51.090  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:08:51.090  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-13 20:08:51.091  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-13 20:08:51.091  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:08:51.092  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:08:51.099  4561  4573 D BtGatt.GattService: registerClient() - UUID=33ef9147-3218-4b10-99ee-94180bcafdf5
10-13 20:08:51.100  4561  4636 D BtGatt.GattService: onClientRegistered() - UUID=33ef9147-3218-4b10-99ee-94180bcafdf5, clientIf=5
10-13 20:08:51.100  5613  5623 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-13 20:08:51.102  4561  4638 D BtGatt.AdvertiseManager: message : 0
,10-13 20:08:51.106  4561  4638 D BtGatt.AdvertiseManager: starting multi advertising
,10-13 20:08:51.124  4561  4636 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-13 20:08:51.132  4561  4636 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-13 20:08:51.133  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-13 20:08:51.133  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-13 20:08:51.133  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-13 20:08:51.133  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-13 20:08:51.133  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-13 20:08:51.134  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-13 20:08:51.134  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-13 20:08:51.134  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-13 20:08:51.134  5613  5659 I io.jxcore.node.ConnectionHelper: start: OK
10-13 20:08:51.134  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-13 20:08:51.134  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
,10-13 20:08:51.134  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-13 20:08:51.134  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-13 20:08:51.134  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:08:51.135  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-13 20:08:51.135  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-13 20:08:51.135  5613  5659 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-13 20:08:51.135  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-13 20:08:51.136  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-13 20:08:51.136  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-13 20:08:51.136  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-13 20:08:51.136  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-13 20:08:51.136  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-13 20:08:51.136  5613  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-13 20:08:51.136  5613  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-13 20:08:51.136  5613  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-13 20:08:51.136  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-13 20:08:51.136  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-13 20:08:51.137  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-13 20:08:51.137  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-13 20:08:51.137  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-13 20:08:51.137  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-13 20:08:51.137  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-13 20:08:51.137  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-13 20:08:51.137  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-13 20:08:51.137  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-13 20:08:51.138  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:08:51.138  5613  5659 D BluetoothLeScanner: could not find callback wrapper
10-13 20:08:51.139  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-13 20:08:51.139  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-13 20:08:51.140  4561  4638 D BtGatt.AdvertiseManager: message : 1
10-13 20:08:51.140  4561  4638 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-13 20:08:51.148  4561  4636 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-13 20:08:51.148  4561  4636 D BtGatt.GattService: Client app is not null!
,10-13 20:08:51.150  4561  4773 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-13 20:08:51.151  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-13 20:08:51.151  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-13 20:08:51.151  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-13 20:08:51.151  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-13 20:08:51.151  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:08:51.152  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-13 20:08:51.152  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-13 20:08:51.152  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,10-13 20:08:51.152  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-13 20:08:51.153  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-13 20:08:51.153  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-13 20:08:51.153  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-13 20:08:51.154  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-13 20:08:51.156  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-13 20:08:51.156  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-13 20:08:51.156  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:08:51.156  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:08:51.156  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-13 20:08:51.160  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
10-13 20:08:51.160  5613  5659 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,10-13 20:08:51.162  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,10-13 20:08:51.162  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-13 20:08:51.163  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-13 20:08:51.163  5613  5659 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-13 20:08:51.164  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
,10-13 20:08:51.164  5613  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,10-13 20:08:51.166  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
10-13 20:08:51.166  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-13 20:08:51.166  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:51.167  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-13 20:08:51.167  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:51.167  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-13 20:08:51.168  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
10-13 20:08:51.169  5613  5659 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-13 20:08:51.170  5613  5659 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,10-13 20:08:51.175  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-13 20:08:51.175  5613  5659 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,10-13 20:08:51.177  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
,10-13 20:08:51.177  5613  5659 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-13 20:08:51.180  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
,10-13 20:08:51.180  5613  5659 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
10-13 20:08:51.180  5613  5659 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-13 20:08:51.180  5613  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-13 20:08:51.180  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-13 20:08:51.181  5613  5659 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-13 20:08:51.181  5613  5659 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-13 20:08:51.181  5613  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-13 20:08:51.181  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-13 20:08:51.181  5613  5659 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-13 20:08:51.181  5613  5659 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-13 20:08:51.181  5613  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-13 20:08:51.181  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-13 20:08:51.181  5613  5659 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,10-13 20:08:51.183  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-13 20:08:51.183  5613  5659 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-13 20:08:51.183  5613  5659 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-13 20:08:51.184  5613  5659 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-13 20:08:51.184  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
10-13 20:08:51.184  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-13 20:08:51.184  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-13 20:08:51.184  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-13 20:08:51.184  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-13 20:08:51.186  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-13 20:08:51.186  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-13 20:08:51.187  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-13 20:08:51.187  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-13 20:08:51.187  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-13 20:08:51.187  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-13 20:08:51.187  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-13 20:08:51.187  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:08:51.187  5613  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-13 20:08:51.187  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-13 20:08:51.188  5613  5670 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-13 20:08:51.191  5613  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-13 20:08:51.192  5613  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-13 20:08:51.192  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-13 20:08:51.185  4572  4572 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32870]" dev="sockfs" ino=32870 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:51.185  4572  4572 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32870]" dev="sockfs" ino=32870 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:51.196  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-13 20:08:51.196  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-13 20:08:51.197  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-13 20:08:51.198  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-13 20:08:51.199  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-13 20:08:51.199  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
10-13 20:08:51.199  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:08:51.199  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-13 20:08:51.199  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-13 20:08:51.199  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-13 20:08:51.200  5613  5659 D BluetoothAdapter: STATE_ON
,10-13 20:08:51.203  4561  4573 D BtGatt.GattService: registerClient() - UUID=815e871c-dd8e-4f51-836d-458c78add3ed
10-13 20:08:51.204  4561  4636 D BtGatt.GattService: onClientRegistered() - UUID=815e871c-dd8e-4f51-836d-458c78add3ed, clientIf=5
10-13 20:08:51.204  5613  5623 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-13 20:08:51.205  4561  4638 D BtGatt.AdvertiseManager: message : 0
10-13 20:08:51.207  4561  4638 D BtGatt.AdvertiseManager: starting multi advertising
,10-13 20:08:51.216  4561  4636 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-13 20:08:51.222  4561  4636 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-13 20:08:51.222  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-13 20:08:51.222  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
,10-13 20:08:51.222  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-13 20:08:51.223  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
,10-13 20:08:51.223  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-13 20:08:51.224  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-13 20:08:51.225  5613  5659 I io.jxcore.node.ConnectionHelper: start: OK
10-13 20:08:51.225  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-13 20:08:51.226  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-13 20:08:51.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-13 20:08:51.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-13 20:08:51.226  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,10-13 20:08:51.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:08:51.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-13 20:08:51.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-13 20:08:51.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-13 20:08:51.226  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-13 20:08:51.228  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-13 20:08:51.229  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-13 20:08:51.663   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:08:51.726  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-13 20:08:51.726  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-13 20:08:51.726  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-13 20:08:51.727  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-13 20:08:51.727  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-13 20:08:51.727  5613  5670 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-13 20:08:51.727  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-13 20:08:51.727  5613  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-13 20:08:51.727  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-13 20:08:51.727  5613  5670 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-13 20:08:51.728  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-13 20:08:51.728  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-13 20:08:51.728  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53f090f removed from the list
10-13 20:08:51.728  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-13 20:08:51.728  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-13 20:08:51.728  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-13 20:08:51.728  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-13 20:08:51.728  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-13 20:08:51.729  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-13 20:08:51.729  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-13 20:08:51.729  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-13 20:08:51.734  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:08:51.734  5613  5659 D BluetoothLeScanner: could not find callback wrapper
10-13 20:08:51.734  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-13 20:08:51.734  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-13 20:08:51.736  4561  4638 D BtGatt.AdvertiseManager: message : 1
10-13 20:08:51.738  4561  4638 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-13 20:08:51.750  4561  4636 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-13 20:08:51.751  4561  4636 D BtGatt.GattService: Client app is not null!
10-13 20:08:51.752  4561  4573 D BtGatt.GattService: unregisterClient() - clientIf=5
10-13 20:08:51.752  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-13 20:08:51.752  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-13 20:08:51.753  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-13 20:08:51.753  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-13 20:08:51.753  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:08:51.753  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-13 20:08:51.753  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-13 20:08:51.753  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-13 20:08:51.753  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-13 20:08:51.756  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-13 20:08:51.756  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-13 20:08:51.756  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-13 20:08:51.757  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-13 20:08:51.759  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1339d9c removed from the list
,10-13 20:08:51.759  5613  5659 D io.jxcore.node.ConnectivityMonitor: stop
10-13 20:08:51.759  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:08:51.759  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-13 20:08:51.759  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:08:51.760  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-13 20:08:52.261  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-13 20:08:52.664   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:08:53.665   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:08:54.666   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:08:55.667   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-13 20:08:56.763  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-13 20:08:56.766  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-13 20:08:56.766  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-13 20:08:56.768  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-13 20:08:56.769  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-13 20:08:56.770  5613  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-13 20:08:56.770  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-13 20:08:56.770  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-13 20:08:56.770  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-13 20:08:56.770  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-13 20:08:56.771  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-13 20:08:56.772  5613  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:08:56.773  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
10-13 20:08:56.774  5613  5659 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-13 20:08:56.774  5613  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-13 20:08:56.774  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,10-13 20:08:56.775  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-13 20:08:56.775  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-13 20:08:56.776  5613  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-13 20:08:56.777  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
10-13 20:08:56.772  4573  4573 W Binder_2: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[33842]" dev="sockfs" ino=33842 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:08:56.772  4573  4573 W Binder_2: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[33842]" dev="sockfs" ino=33842 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-13 20:08:56.787  5613  5659 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-13 20:08:56.787  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-13 20:08:56.787  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-13 20:08:56.787  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-13 20:08:56.788  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-13 20:08:56.788  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-13 20:08:56.788  5613  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-13 20:08:56.788  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-13 20:08:56.788  5613  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-13 20:08:56.788  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-13 20:08:56.788  5613  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-13 20:08:56.788  5613  5659 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53f090f not in the list
10-13 20:08:56.788  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-13 20:08:56.788  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-13 20:08:56.788  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-13 20:08:56.788  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-13 20:08:56.788  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-13 20:08:56.788  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-13 20:08:56.788  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-13 20:08:56.788  5613  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-13 20:08:56.789  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-13 20:08:56.790  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-13 20:08:56.791  5613  5659 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1339d9c not in the list
10-13 20:08:56.791  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-13 20:08:56.791  5613  5659 D io.jxcore.node.ConnectivityMonitor: stop
10-13 20:08:56.791  5613  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-13 20:08:56.791  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:08:56.791  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-13 20:08:56.791  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-13 20:08:56.792  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
10-13 20:08:56.792  5613  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,10-13 20:08:56.793  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-13 20:08:56.793  5613  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-13 20:08:56.793  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-13 20:08:56.793  5613  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-13 20:08:56.793  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-13 20:08:56.794  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,10-13 20:08:56.794  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,10-13 20:08:56.796  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
10-13 20:08:56.796  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-13 20:08:56.796  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-13 20:08:56.797  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
10-13 20:08:56.797  5613  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-13 20:08:56.798  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-13 20:08:56.798  5613  5659 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-13 20:08:56.798  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-13 20:08:56.798  5613  5659 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-13 20:08:56.799  5613  5659 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-13 20:08:56.799  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
10-13 20:08:56.799  5613  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-13 20:08:56.799  5613  5659 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-13 20:08:56.800  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
10-13 20:08:56.800  5613  5659 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-13 20:08:56.800  5613  5659 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-13 20:08:56.800  5613  5659 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-13 20:08:56.800  5613  5659 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-13 20:08:56.801  5613  5659 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
10-13 20:08:56.801  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-13 20:08:56.801  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e7a5cc added. We now have 3 listener(s)
,10-13 20:08:56.802  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-13 20:08:56.803  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-13 20:08:56.803  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-13 20:08:56.803  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-13 20:08:56.803  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9edf015 added. We now have 3 listener(s)
10-13 20:08:56.803  5613  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-13 20:08:56.803  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-13 20:08:56.806  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:08:56.810  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:08:56.812  5613  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:08:56.812  5613  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
10-13 20:08:56.813  5613  5659 D BluetoothAdapter: enable(): BT is already enabled..!
,10-13 20:08:56.813   926  3549 D WifiService: setWifiEnabled: true pid=5613, uid=10077
10-13 20:08:56.813   926  3549 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-13 20:08:56.814  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:56.816  5613  5659 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,10-13 20:08:56.818  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:56.819  5613  5659 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
10-13 20:08:56.819  5613  5659 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,10-13 20:08:56.823   926  3802 D WifiService: setWifiEnabled: false pid=5613, uid=10077
10-13 20:08:56.823   926  3802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:08:56.827   926  2950 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-13 20:08:56.827   926  2950 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-13 20:08:56.827   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-13 20:08:56.827   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-13 20:08:56.837   926  5371 D DhcpClient: Clearing IP address
10-13 20:08:56.837   506   919 D CommandListener: Clearing all IP addresses on wlan0
,10-13 20:08:56.845   506   919 D CommandListener: Setting iface cfg
,10-13 20:08:56.850  3555  5432 V NativeCrypto: Read error: ssl=0x7f78a42700: I/O error during system call, Connection timed out
,10-13 20:08:56.852  3555  5432 V NativeCrypto: SSL shutdown failed: ssl=0x7f78a42700: I/O error during system call, Broken pipe
,10-13 20:08:56.856   926  3549 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,10-13 20:08:56.857   926  5369 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,10-13 20:08:56.858   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-13 20:08:56.858   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
10-13 20:08:56.859   926  5369 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-13 20:08:56.865   532   532 E Parcel  : Reading a NULL string not supported here.
10-13 20:08:56.869   926   926 D RttService: SCAN_AVAILABLE : 1
10-13 20:08:56.869   926  3059 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-13 20:08:56.872   926  2952 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-13 20:08:56.872   926  5372 D DhcpClient: Receive thread stopped
10-13 20:08:56.874  3740  3883 W QCNEJ   : |CORE| network lost: 100
10-13 20:08:56.874  3740  3883 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-13 20:08:56.877   926  2950 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-13 20:08:56.888   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-13 20:08:56.908   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-13 20:08:56.919  3555  5687 I VacuumService: Vacuum at: now=1476403736919 tag=VacuumService
,10-13 20:08:56.932   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-13 20:08:56.932   506   919 D CommandListener: Clearing all IP addresses on wlan0
10-13 20:08:56.933   506   919 D TetherController: Setting IP forward enable = 0
10-13 20:08:56.935   926  2952 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,10-13 20:08:56.935   926  2950 D DhcpClient: doQuit
10-13 20:08:56.935   926  2950 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-13 20:08:56.935   926  2952 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-13 20:08:56.935   926  5371 D DhcpClient: onQuitting
10-13 20:08:56.936  3426  3426 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-13 20:08:56.939   926   943 D Tethering: MasterInitialState.processMessage what=3
,10-13 20:08:56.942  5272  5272 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@103b2b3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:56.946  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-13 20:08:56.949  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:08:56.950  4888  4888 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:56.954  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:08:56.954  5034  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-13 20:08:56.954  5034  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-13 20:08:56.954  5034  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-13 20:08:56.954  5034  5059 E SarControlService: no key has been found,reset the power
10-13 20:08:56.954  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-13 20:08:56.954  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-13 20:08:56.955  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-13 20:08:56.955  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-13 20:08:56.955  5061  5061 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-13 20:08:56.956  3426  3426 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-13 20:08:56.957  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-13 20:08:56.958  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-13 20:08:56.958  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-13 20:08:56.958  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:56.960  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:08:56.960  3856  3856 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-13 20:08:56.961  3426  3426 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-13 20:08:56.963  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:08:56.964  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-13 20:08:56.964  5061  5061 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-13 20:08:56.965  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:56.967  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000ea03000000000000ffffffff]
10-13 20:08:56.967  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-13 20:08:56.967  5061  5079 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-13 20:08:56.967  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:56.967  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:08:56.968  5034  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-13 20:08:56.969  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:56.969  3856  3856 D SystemUpdateService: onCreate
10-13 20:08:56.972  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000eb03000000000000ffffffff]
10-13 20:08:56.972  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-13 20:08:56.973  5061  5079 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-13 20:08:56.973  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:08:56.973  5034  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-13 20:08:56.976  3856  3856 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-13 20:08:56.982  3426  3426 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-13 20:08:56.983  3856  3856 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-13 20:08:56.986  3856  5679 I EventLogService: Aggregate from 1476401755969 (log), 1476401755969 (data)
,10-13 20:08:56.988  3856  5400 I iu.UploadsManager: num queued entries: 0
,10-13 20:08:56.989  3856  5400 I iu.UploadsManager: num updated entries: 0
10-13 20:08:56.989  3856  5400 I iu.SyncManager: NEXT; no task
,10-13 20:08:56.991  3856  5696 I SystemUpdateService: active receiver: enabled
,10-13 20:08:56.993  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-13 20:08:56.994  3856  3856 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-13 20:08:56.996  5404  5404 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-13 20:08:56.998  3426  3426 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-13 20:08:57.000  5404  5404 D SprintDMHelper: simOperator: 
10-13 20:08:57.000  5404  5404 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-13 20:08:57.012  5009  5698 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-13 20:08:57.015  3856  5696 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-13 20:08:57.016  3856  5696 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-13 20:08:57.016  3856  5696 I SystemUpdateService: now status is 0 (complete)
10-13 20:08:57.016  3856  5696 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-13 20:08:57.016  3856  5696 I SystemUpdateService: file has been verified
10-13 20:08:57.017  3856  5696 I SystemUpdateService: OTA package size = 21989297
,10-13 20:08:57.023   926  3802 I ActivityManager: Start proc 5699:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-13 20:08:57.033  3856  5696 I SystemUpdateService: showing system update notification
,10-13 20:08:57.056  5699  5699 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-13 20:08:57.073  3856  3856 D SystemUpdateService: onDestroy
,10-13 20:08:57.103   926  2950 D wifi    : In wifi stop Hal
,10-13 20:08:57.103   926  2950 D wifi    : halHandle = 0x7f62482c80, mVM = 0x7f7eb0d140, mCls = 0x100a02
10-13 20:08:57.103   926  3425 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-13 20:08:57.103   926  3425 D WifiHAL : Got a signal to exit!!!
10-13 20:08:57.104   926  3425 I WifiHAL : Exit wifi_event_loop
10-13 20:08:57.104   926  2950 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-13 20:08:57.104   926  2950 E WifiHAL : Event processing terminated
10-13 20:08:57.105   926  2950 D wifi    : In wifi cleaned up handler
10-13 20:08:57.106   926  2950 I WifiHAL : Internal cleanup completed
,10-13 20:08:57.106  4060  4199 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-13 20:08:57.106  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:57.108  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:57.109  5009  5009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-13 20:08:57.109  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:57.129   926  3425 D wifi    : set interface wlan0 flags (DOWN)
,10-13 20:08:57.129   926  2950 D WifiNative-HAL: HAL event thread stopped successfully
,10-13 20:08:57.291  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-13 20:08:57.329  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:57.334   926  3549 D WifiService: setWifiEnabled: true pid=5613, uid=10077
,10-13 20:08:57.334   926  3549 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:08:57.339   926   943 D Tethering: InitialState.processMessage what=4
,10-13 20:08:57.346   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-13 20:08:57.839   926  3935 D WifiService: setWifiEnabled: true pid=5613, uid=10077
,10-13 20:08:57.839   926  3935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:08:58.022   506   919 E Netd    : netlink response contains error (No such file or directory)
,10-13 20:08:58.023   926  2952 E NetdConnector: NDC Command {113 network destroy 100} took too long (1087ms)
10-13 20:08:58.023   926  2952 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-13 20:08:58.025   926  2948 E NetdConnector: NDC Command {114 bandwidth setglobalalert 2097152} took too long (1083ms)
10-13 20:08:58.025   506   919 D SoftapController: Softap fwReload - Ok
,10-13 20:08:58.026   926  2950 E NetdConnector: NDC Command {115 softap fwreload wlan0 STA} took too long (686ms)
,10-13 20:08:58.026   926  2947 E NetdConnector: NDC Command {116 bandwidth gettetherstats} took too long (678ms)
,10-13 20:08:58.027   506   919 D TetherController: Setting IP forward enable = 0
,10-13 20:08:58.028   506   919 D CommandListener: Setting iface cfg
10-13 20:08:58.029   506   919 D CommandListener: Trying to bring down wlan0
,10-13 20:08:58.031   506   919 D CommandListener: Clearing all IP addresses on wlan0
,10-13 20:08:58.036   926  2950 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-13 20:08:58.342   926   937 D WifiService: setWifiEnabled: true pid=5613, uid=10077
10-13 20:08:58.344   926   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:08:58.639   926  2950 D wifi    : set interface wlan0 flags (UP)
,10-13 20:08:58.640   926  2950 I WifiHAL : Initializing wifi
10-13 20:08:58.640   926  2950 I WifiHAL : Creating socket
,10-13 20:08:58.646   926  2950 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-13 20:08:58.646   926  2950 D wifi    : Did set static halHandle = 0x7f62482c80
10-13 20:08:58.646   926  2950 D wifi    : halHandle = 0x7f62482c80, mVM = 0x7f7eb0d140, mCls = 0x1342
,10-13 20:08:58.647   926  2950 D wifi    : array field set
10-13 20:08:58.647   926  2950 I WifiNative-HAL: interface[0] = wlan0
10-13 20:08:58.649   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-13 20:08:58.650   926  5719 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547109743744
,10-13 20:08:58.651   926  5719 D wifi    : waitForHalEvents called, vm = 0x7f7eb0d140, obj = 0x1342, env = 0x7f624fd780
,10-13 20:08:58.655   926  2950 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
10-13 20:08:58.657   926  2950 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
10-13 20:08:58.660  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:58.663  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:58.668  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:58.733  5720  5720 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-13 20:08:58.754  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-13 20:08:58.765  5720  5720 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-13 20:08:58.765  5720  5720 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-13 20:08:58.846   926  3935 D WifiService: setWifiEnabled: true pid=5613, uid=10077
10-13 20:08:58.846   926  3935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:08:59.349   926  3103 D WifiService: setWifiEnabled: true pid=5613, uid=10077
,10-13 20:08:59.349   926  3103 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:08:59.673   926  2950 D WifiConfigStore: Loading config and enabling all networks 
,10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:59.680  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-13 20:08:59.688  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:59.695  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:08:59.698  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:08:59.699   926  2950 D WifiConfigStore: loaded 0 passpoint configs
10-13 20:08:59.700   926  2950 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-13 20:08:59.701   926  2950 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-13 20:08:59.702   926  2950 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:59.703  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:08:59.704   926  2950 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-13 20:08:59.704   926  2950 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-13 20:08:59.704   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-13 20:08:59.704   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-13 20:08:59.707  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-13 20:08:59.710  5009  5009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-13 20:08:59.710   926  2950 D WifiNative-HAL: Setting external_sim to 1
10-13 20:08:59.710   926  2950 D wifi    : setting dfs flag to true, 0x7f6831ab60
10-13 20:08:59.711   926  2950 D WifiStateMachine: Setting OUI to DA-A1-19
,10-13 20:08:59.712   926  2950 D wifi    : setting scan oui 0x7f6831ab60
10-13 20:08:59.712   926  2950 D WifiHAL : Sending mac address OUI
,10-13 20:08:59.718   926  2950 E native  : do suspend false
,10-13 20:08:59.729   926   926 D RttService: SCAN_AVAILABLE : 3
10-13 20:08:59.729   926  2950 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-13 20:08:59.729   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-13 20:08:59.729   926  3059 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-13 20:08:59.730   506   919 D CommandListener: Setting iface cfg
,10-13 20:08:59.734   926  2949 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,10-13 20:08:59.734   926  2949 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-13 20:08:59.748   926  2949 D WifiNative-HAL: p2pGetDeviceAddress
,10-13 20:08:59.753   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=237611 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,10-13 20:08:59.753   926  2949 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-13 20:08:59.854  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:08:59.865  4561  4632 D BluetoothAdapterState: Current state: ON, message: 23
,10-13 20:08:59.865  4561  4632 D BluetoothAdapterProperties: Setting state to 13
,10-13 20:08:59.866  4561  4632 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-13 20:08:59.867  4561  4632 D BluetoothAdapterProperties: onBluetoothDisable()
10-13 20:08:59.869  4561  4632 I BluetoothAdapterState: Entering PendingCommandState
,10-13 20:08:59.870  4561  4561 D BluetoothMapService: onReceive
10-13 20:08:59.871  4561  4561 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-13 20:08:59.871  4561  4561 D BluetoothMapService: STATE_TURNING_OFF
10-13 20:08:59.871  4561  4561 D BluetoothMapService: MAP Service closeService in
10-13 20:08:59.871  4561  4561 D BluetoothMapMasInstance0: MAP Service shutdown
10-13 20:08:59.871  4561  4561 D ObexServerSockets0: shutdown(block = true)
,10-13 20:08:59.872  4561  4561 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-13 20:08:59.873  4561  4771 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-13 20:08:59.873  4561  4802 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-13 20:08:59.873  4561  4561 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-13 20:08:59.875  4561  4803 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-13 20:08:59.881  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:59.881  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:08:59.882  4561  4561 I BtOppRfcommListener: stopping Accept Thread
10-13 20:08:59.883  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:08:59.883  4561  5314 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-13 20:08:59.883  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-13 20:08:59.884  4561  5314 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-13 20:08:59.886  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:59.886  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:08:59.887  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:08:59.887  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-13 20:08:59.889  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will ,return stored value
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:08:59.890  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:08:59.890  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:08:59.891  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-13 20:08:59.903   926   939 I ActivityManager: Start proc 5725:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-13 20:08:59.904  4561  4636 D BluetoothAdapterProperties: Scan Mode:20
10-13 20:08:59.904  4561  4632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-13 20:08:59.908  4561  4561 D HeadsetService: Received stop request...Stopping profile...
10-13 20:08:59.909  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.910   926   926 D BluetoothHeadset: Proxy object disconnected
10-13 20:08:59.910   926   926 D BluetoothHeadset: Proxy object disconnected
10-13 20:08:59.910   926   926 D BluetoothHeadset: Proxy object disconnected
10-13 20:08:59.910  3784  3807 D BluetoothHeadset: Proxy object disconnected
10-13 20:08:59.911  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.912  3107  3953 D BluetoothHeadset: Proxy object disconnected
10-13 20:08:59.912  3107  3107 D HeadsetProfile: Bluetooth service disconnected
10-13 20:08:59.914  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.914  4561  4561 D A2dpService: Received stop request...Stopping profile...
10-13 20:08:59.914  4561  4776 D A2dpStateMachine: Exit Disconnected: -1
10-13 20:08:59.915   926   926 D BluetoothA2dp: Proxy object disconnected
10-13 20:08:59.915  3107  3107 D BluetoothA2dp: Proxy object disconnected
10-13 20:08:59.916  4561  4561 D HidService: Received stop request...Stopping profile...
10-13 20:08:59.916  4561  4561 D HidService: Stopping Bluetooth HidService
10-13 20:08:59.917  3107  3107 D BluetoothInputDevice: Proxy object disconnected
10-13 20:08:59.918  3107  3107 D HidProfile: Bluetooth service disconnected
10-13 20:08:59.918  4561  4561 D HealthService: Received stop request...Stopping profile...
10-13 20:08:59.920  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-13 20:08:59.920  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:08:59.920  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:08:59.920  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:08:59.922  4561  4561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-13 20:08:59.922  4561  4561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-13 20:08:59.922  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:08:59.923  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:08:59.923  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:08:59.923  4561  4636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-13 20:08:59.924  4561  4636 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,10-13 20:08:59.924  4561  4561 D PanService: Received stop request...Stopping profile...
10-13 20:08:59.925  3107  3107 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-13 20:08:59.925  3107  3107 D PanProfile: Bluetooth service disconnected
10-13 20:08:59.926  4561  4561 D BluetoothMapService: Received stop request...Stopping profile...
10-13 20:08:59.926  4561  4561 D BluetoothMapService: stop()
10-13 20:08:59.927  4561  4561 D BluetoothMapAppObserver: deinitObservers()
10-13 20:08:59.927  4561  4561 D BluetoothMapAppObserver: removeReceiver()
10-13 20:08:59.929  3107  3107 D BluetoothMap: Proxy object disconnected
10-13 20:08:59.929  3107  3107 D MapProfile: Bluetooth service disconnected
10-13 20:08:59.930  4561  4561 D SapService: Received stop request...Stopping profile...
10-13 20:08:59.930  4561  4561 V SapService: stop()
10-13 20:08:59.931  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-13 20:08:59.932  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:08:59.932  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:08:59.932  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:08:59.933  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:08:59.933  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-13 20:08:59.933  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:08:59.933  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:08:59.933  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:08:59.933  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:08:59.933  4561  4636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-13 20:08:59.933  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-13 20:08:59.933  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-13 20:08:59.933  4561  4561 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-13 20:08:59.933  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-13 20:08:59.933  4561  4561 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-13 20:08:59.933  4561  4768 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-13 20:08:59.933  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-13 20:08:59.933  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:08:59.933  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:08:59.934  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:08:59.934  4561  4561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-13 20:08:59.934  4561  4561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-13 20:08:59.934  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-13 20:08:59.934  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:08:59.934  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:08:59.934  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:08:59.935  4561  4561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-13 20:08:59.935  4561  4561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-13 20:08:59.935  4561  4636 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-13 20:08:59.935  4561  4561 D BluetoothMapService: MAP Service closeService in
10-13 20:08:59.935  4561  4636 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-13 20:08:59.936  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-13 20:08:59.936  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:08:59.936  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:08:59.936  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:08:59.936  4561  4561 D BluetoothMapService: cleanup()
10-13 20:08:59.936  4561  4561 D BluetoothMapService: MAP Service closeService in
10-13 20:08:59.938  4561  4561 V BluetoothAdapterState: isTurningOff()=true
10-13 20:08:59.938  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:08:59.938  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:08:59.939  4561  4561 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:08:59.939  4561  4632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-13 20:08:59.939  4561  4632 D BluetoothAdapterProperties: Setting state to 15
10-13 20:08:59.939  4561  4632 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-13 20:08:59.942  4561  4632 I BluetoothAdapterState: Entering BleOnState
10-13 20:08:59.943   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:08:59.943   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:08:59.943  3107  3119 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-13 20:08:59.944  3107  3120 D BluetoothPan: onBluetoothStateChange on: false
10-13 20:08:59.944  3107  3953 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:08:59.944  3107  3119 D BluetoothPbap: onBluetoothStateChange: up=false
10-13 20:08:59.945  3107  3120 D BluetoothA2dp: onBluetoothStateChange: up=false
10-13 20:08:59.946   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
10-13 20:08:59.946  3107  3953 D BluetoothMap: onBluetoothStateChange: up=false
10-13 20:08:59.947  3784  3976 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:08:59.947   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:08:59.947  4561  4632 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-13 20:08:59.947  4561  4632 D BluetoothAdapterProperties: Setting state to 16
10-13 20:08:59.947  4561  4632 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-13 20:08:59.949  4561  4632 D BluetoothAdapterProperties: onBleDisable
10-13 20:08:59.949  4561  4632 I BluetoothAdapterState: Entering PendingCommandState
10-13 20:08:59.949  4561  4633 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-13 20:08:59.950  4561  4636 D BluetoothAdapterProperties: Scan Mode:20
10-13 20:08:59.950  4561  4768 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-13 20:08:59.951  4561  4768 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:08:59.953  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.955  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.957  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.958  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.960  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.961  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:08:59.962  5725  5725 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-13 20:08:59.974  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-13 20:08:59.978   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bb7789b:true
10-13 20:08:59.979  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-13 20:08:59.991   926  3802 I ActivityManager: Start proc 5737:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
10-13 20:09:00.004  5725  5725 D LocalBluetoothProfileManager: Adding local MAP profile
,10-13 20:09:00.008  5725  5725 D BluetoothMap: Create BluetoothMap proxy object
,10-13 20:09:00.025  5725  5725 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-13 20:09:00.031  5737  5737 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-13 20:09:00.040  5725  5725 D DockEventReceiver: finishStartingService: stopping service
,10-13 20:09:00.046   926  3549 I ActivityManager: Killing 5154:com.google.android.youtube/u0a75 (adj 15): empty #17
,10-13 20:09:00.156  4561  4636 I bt_hci  : shut_down
,10-13 20:09:00.160  4561  4642 D bt_hwcfg: hw_epilog_process
,10-13 20:09:00.161  4561  4642 I bt_vendor: low_power_mode_cb
,10-13 20:09:00.163  4561  4642 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-13 20:09:00.163  4561  4642 I bt_vendor: epilog_cb
10-13 20:09:00.163  4561  4642 I bt_hci  : epilog_finished_callback
,10-13 20:09:00.165  4561  4636 I bt_hci_h4: hal_close
,10-13 20:09:00.166  4561  4636 I bt_userial_vendor: device fd = 54 close
,10-13 20:09:00.246  5737  5737 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.File.exists(File.java:361)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.246  5737  5737 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.246  5737  5737 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.246  5737  5737 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:170)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.246  5737  5737 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.k.d(PG:583)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:170)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.246  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.247  5737  5737 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.io.File.exists(File.java:361)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.247  5737  5737 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.io.File.exists(File.java:361)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.247  5737  5737 D StrictMode: StrictMode policy violation; ~duration=73 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-13 20:09:00.247  5737  5737 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-13 20:09:00.250  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-13 20:09:00.256  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-13 20:09:00.258  5725  5725 D DockEventReceiver: finishStartingService: stopping service
10-13 20:09:00.272  4561  4633 D bt_stack_manager: event_shut_down_stack finished.
10-13 20:09:00.272  4561  4632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-13 20:09:00.272   926   936 I ActivityManager: Killing 5272:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-13 20:09:00.306  4561  4561 D BtGatt.DebugUtils: handleDebugAction() action=null
10-13 20:09:00.306  4561  4561 D BtGatt.GattService: Received stop request...Stopping profile...
10-13 20:09:00.306  4561  4561 D BtGatt.GattService: stop()
10-13 20:09:00.307  4561  4561 D BtGatt.AdvertiseManager: advertise clients cleared
10-13 20:09:00.307  4561  4632 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-13 20:09:00.309  4561  4561 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:00.309  4561  4561 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:00.309  4561  4561 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:00.309  4561  4561 V BluetoothAdapterState: isBleTurningOff()=true
10-13 20:09:00.309  4561  4632 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-13 20:09:00.309  4561  4632 D BluetoothAdapterProperties: Setting state to 10
10-13 20:09:00.310  4561  4632 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-13 20:09:00.310  4561  4632 I BluetoothAdapterState: Entering OffState
10-13 20:09:00.311   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
10-13 20:09:00.318  4561  4561 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-13 20:09:00.318  4561  4561 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-13 20:09:00.319  4561  4633 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-13 20:09:00.320  4561  4561 I BluetoothServiceJni: cleanupNative: return from cleanup
10-13 20:09:00.324  4561  4561 I art     : System.exit called, status: 0
10-13 20:09:00.324  4561  4561 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-13 20:09:00.365  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:00.367   380   380 E lowmemorykiller: Error writing /proc/4561/oom_score_adj; errno=22
,10-13 20:09:00.367   926   943 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
10-13 20:09:00.367   926   943 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
10-13 20:09:00.368   926   943 W ActivityManager: Application dead when creating service ServiceRecord{aee2cb2 u0 com.android.bluetooth/.btservice.AdapterService}
,10-13 20:09:00.373   926   943 I ActivityManager: Process com.android.bluetooth (pid 4561) has died
,10-13 20:09:00.374   926   943 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
10-13 20:09:00.375   926   943 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
,10-13 20:09:00.375   926   943 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
10-13 20:09:00.375   926   943 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:00.375   926   943 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-13 20:09:00.375   926   943 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-13 20:09:00.376   926  3135 W ActivityManager: Spurious death for ProcessRecord{243b14b 0:com.android.bluetooth/1002}, curProc for 4561: null
,10-13 20:09:00.493  5737  5763 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-13 20:09:00.503   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3137f80:true
,10-13 20:09:00.668   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:01.669   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:01.929   926  3802 I ActivityManager: Killing 4656:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-13 20:09:02.670   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:02.909  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:02.914  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:02.918  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:02.923  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:02.975   926  2950 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-13 20:09:02.976   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-13 20:09:02.977   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-13 20:09:02.991   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-13 20:09:03.023   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-13 20:09:03.025  5720  5720 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-13 20:09:03.366   926   943 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,10-13 20:09:03.410   926   943 I ActivityManager: Start proc 5773:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-13 20:09:03.464  5720  5720 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-13 20:09:03.487  5773  5773 D AdapterServiceConfig: Adding HeadsetService
,10-13 20:09:03.488  5773  5773 D AdapterServiceConfig: Adding A2dpService
10-13 20:09:03.488  5773  5773 D AdapterServiceConfig: Adding HidService
10-13 20:09:03.488  5773  5773 D AdapterServiceConfig: Adding HealthService
,10-13 20:09:03.489  5773  5773 D AdapterServiceConfig: Adding PanService
10-13 20:09:03.489  5773  5773 D AdapterServiceConfig: Adding GattService
10-13 20:09:03.489  5773  5773 D AdapterServiceConfig: Adding BluetoothMapService
,10-13 20:09:03.489  5773  5773 D AdapterServiceConfig: Adding SapService
,10-13 20:09:03.502   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11ab2d6:true
,10-13 20:09:03.502  5773  5773 D BluetoothAdapterState: make() - Creating AdapterState
,10-13 20:09:03.505  5773  5773 I bt_bluedroid: init
10-13 20:09:03.505  5773  5785 I BluetoothAdapterState: Entering OffState
,10-13 20:09:03.508  5773  5786 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-13 20:09:03.508  5773  5786 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-13 20:09:03.508  5773  5786 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-13 20:09:03.508  5773  5786 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-13 20:09:03.509  5773  5773 I bt_bluedroid: get_profile_interface socket
,10-13 20:09:03.511  5773  5773 I bt_bluedroid: get_profile_interface sdp
,10-13 20:09:03.511  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-13 20:09:03.512  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-13 20:09:03.515  5773  5784 I bt_bluedroid: config_hci_snoop_log
10-13 20:09:03.516   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-13 20:09:03.519  5720  5720 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-13 20:09:03.519  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
10-13 20:09:03.521  5773  5785 D BluetoothAdapterState: Current state: OFF, message: 0
10-13 20:09:03.521  5773  5785 D BluetoothAdapterProperties: Setting state to 14
10-13 20:09:03.521  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-13 20:09:03.522  5773  5785 D BluetoothBondStateMachine: make
10-13 20:09:03.524   926  2950 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-13 20:09:03.524   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-13 20:09:03.524   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
10-13 20:09:03.525  5773  5791 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-13 20:09:03.528  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,10-13 20:09:03.529  5773  5773 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-13 20:09:03.531  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:03.531  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-13 20:09:03.532  5773  5773 D BtGatt.GattService: Received start request. Starting profile...
10-13 20:09:03.532  5773  5773 D BtGatt.GattService: start()
10-13 20:09:03.532  5773  5773 I bt_bluedroid: get_profile_interface gatt
,10-13 20:09:03.533  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:03.533  5773  5773 D BtGatt.AdvertiseManager: advertise manager created
,10-13 20:09:03.535   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-13 20:09:03.539  5773  5773 V BluetoothAdapterState: isTurningOff()=false
,10-13 20:09:03.539  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:03.539  5773  5773 V BluetoothAdapterState: isBleTurningOn()=true
10-13 20:09:03.540  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:03.540  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-13 20:09:03.542  5773  5785 I bt_bluedroid: bt_bluedroid
,10-13 20:09:03.542  5773  5786 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-13 20:09:03.543   506   919 D CommandListener: Setting iface cfg
10-13 20:09:03.543  5773  5786 I bt_hci  : start_up
,10-13 20:09:03.546   926  2950 D WifiStateMachine: Start Dhcp Watchdog 2
,10-13 20:09:03.549  5773  5786 I bt_vendor: alloc value 0xf42a9871
,10-13 20:09:03.549  5773  5786 I bt_vendor: init
10-13 20:09:03.549  5773  5786 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-13 20:09:03.549  5773  5786 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-13 20:09:03.554   926  2952 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-13 20:09:03.555   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-13 20:09:03.555   926  2952 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-13 20:09:03.556   926  5797 D DhcpClient: Receive thread started
,10-13 20:09:03.635   926  2950 E native  : do suspend false
,10-13 20:09:03.642   926  5795 D DhcpClient: Broadcasting DHCPDISCOVER
,10-13 20:09:03.658  5773  5786 D bt_hci  : start_up starting async portion
,10-13 20:09:03.655  5798  5798 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-13 20:09:03.658  5773  5796 I bt_hci  : event_finish_startup
10-13 20:09:03.658  5773  5796 I bt_hci_h4: hal_open
10-13 20:09:03.659  5773  5796 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-13 20:09:03.660  5773  5796 I bt_userial_vendor: device fd = 54 open
,10-13 20:09:03.664   926  5797 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172600, domain null
,10-13 20:09:03.664   926  5795 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172600 seconds
,10-13 20:09:03.666   926  5795 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-13 20:09:03.671   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:03.673  5773  5796 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-13 20:09:03.675  5773  5796 D bt_hwcfg: Chipset BCM4358A3
,10-13 20:09:03.675  5773  5796 D bt_hwcfg: Target name = [BCM4358A3]
10-13 20:09:03.675  5773  5796 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-13 20:09:03.685   926  5797 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-13 20:09:03.685   926  5795 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-13 20:09:03.687   506   919 D CommandListener: Setting iface cfg
,10-13 20:09:03.689   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-13 20:09:03.691   926  5795 D DhcpClient: Scheduling renewal in 86399s
,10-13 20:09:03.697   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-13 20:09:03.698   926  2950 D WifiConfigStore: No blacklist allowed without epno enabled
,10-13 20:09:03.698   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-13 20:09:03.702   926  2950 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-13 20:09:03.703   926  2952 D ConnectivityService: Adding iface wlan0 to network 101
,10-13 20:09:03.715   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,10-13 20:09:03.746   926  2952 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-13 20:09:03.747   926  2952 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-13 20:09:03.749   926  2952 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-13 20:09:03.752   926  2952 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-13 20:09:03.754   926  2952 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-13 20:09:03.765   926  2952 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-13 20:09:03.769   926  2952 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-13 20:09:03.770   926  2952 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-13 20:09:03.770   926  2952 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-13 20:09:03.770   926  2950 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-13 20:09:03.770   926  2952 D ConnectivityService:    accepting network in place of null
10-13 20:09:03.770   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-13 20:09:03.771   926  2952 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-13 20:09:03.795   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-13 20:09:03.799   926  5793 D NetlinkSocketObserver: NeighborEvent{elapsedMs=241657, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-13 20:09:03.820   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-13 20:09:03.826   926  2952 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-13 20:09:03.826  3740  3883 W QCNEJ   : |CORE| network available: 101
,10-13 20:09:03.826   926  2952 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-13 20:09:03.827   926  2952 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-13 20:09:03.827   926   943 D Tethering: MasterInitialState.processMessage what=3
10-13 20:09:03.832  3740  3883 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-13 20:09:03.834  3740  3883 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-13 20:09:03.834  3740  3883 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-13 20:09:03.836  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:03.836  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:03.837  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:09:03.838  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:03.840  5034  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-13 20:09:03.840  5034  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-13 20:09:03.840  5034  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-13 20:09:03.840  5034  5059 E SarControlService: no key has been found,reset the power
10-13 20:09:03.840  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,10-13 20:09:03.841  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-13 20:09:03.841  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-13 20:09:03.841  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-13 20:09:03.841  5061  5061 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-13 20:09:03.842  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:03.842  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:09:03.843  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:09:03.843  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:03.843  4888  4888 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-13 20:09:03.846  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-13 20:09:03.846  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-13 20:09:03.846  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-13 20:09:03.847  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:03.847  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:09:03.848  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:09:03.848  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-13 20:09:03.848  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:03.848  5061  5061 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-13 20:09:03.851  3856  3856 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-13 20:09:03.852  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000ec03000000000000ffffffff]
10-13 20:09:03.852  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-13 20:09:03.852  5061  5079 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,10-13 20:09:03.853  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000ed03000000000000ffffffff]
10-13 20:09:03.853  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-13 20:09:03.853  5061  5079 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-13 20:09:03.856  3856  3856 D SystemUpdateService: onCreate
10-13 20:09:03.856  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:09:03.857  5034  5045 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-13 20:09:03.857  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:09:03.857  5034  5044 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-13 20:09:03.860  3856  3856 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-13 20:09:03.869   926  5790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,10-13 20:09:03.873  3856  3856 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-13 20:09:03.878  3856  5400 I iu.UploadsManager: num queued entries: 0
,10-13 20:09:03.882  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-13 20:09:03.882  3856  5810 I SystemUpdateService: active receiver: enabled
,10-13 20:09:03.884  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-13 20:09:03.885  3856  3856 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-13 20:09:03.887  5404  5404 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-13 20:09:03.891  5404  5404 D SprintDMHelper: simOperator: 
,10-13 20:09:03.891  5404  5404 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-13 20:09:03.904  3856  5400 I iu.UploadsManager: num updated entries: 0
,10-13 20:09:03.920  3856  5810 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-13 20:09:03.924   926  5790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 14 Oct 2016 00:09:03 GMT], X-Android-Received-Millis=[1476403743924], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476403743898]}
,10-13 20:09:03.925   926  2952 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-13 20:09:03.925   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,10-13 20:09:03.925   926  2952 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-13 20:09:03.926  3856  5400 I iu.SyncManager: NEXT; no task
10-13 20:09:03.926   926  2952 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-13 20:09:03.928  3856  5810 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-13 20:09:03.929  3856  5810 I SystemUpdateService: now status is 0 (complete)
10-13 20:09:03.929  3856  5810 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-13 20:09:03.929  3856  5810 I SystemUpdateService: file has been verified
10-13 20:09:03.929  3856  5810 I SystemUpdateService: OTA package size = 21989297
,10-13 20:09:03.936  3856  5810 I SystemUpdateService: showing system update notification
,10-13 20:09:03.945  3856  3856 D SystemUpdateService: onDestroy
,10-13 20:09:04.015  5773  5796 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-13 20:09:04.015  5773  5796 D bt_hwcfg: Settlement delay -- 100 ms
10-13 20:09:04.015  5773  5796 I bt_hwcfg: Setting fw settlement delay to 100 
10-13 20:09:04.015  5009  5814 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-13 20:09:04.056  3555  5824 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,10-13 20:09:04.087  3555  5822 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,10-13 20:09:04.090  3555  5822 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,10-13 20:09:04.133  3555  5822 W Uploader:  no longer exists, so no auth token.
,10-13 20:09:04.138  5773  5796 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-13 20:09:04.138  5773  5796 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-13 20:09:04.139  5773  5796 I bt_hwcfg: vendor lib fwcfg completed
10-13 20:09:04.139  5773  5796 I bt_vendor: firmware callback
,10-13 20:09:04.139  5773  5796 I bt_hci  : firmware_config_callback
10-13 20:09:04.140  3555  5824 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-13 20:09:04.143  5773  5827 I bt_btu  : btu_task pending for preload complete event
10-13 20:09:04.144  5773  5827 I bt_btu_task: Bluetooth chip preload is complete
10-13 20:09:04.144  5773  5827 I bt_btu  : btu_task received preload complete event
,10-13 20:09:04.146  5773  5827 I         : BTE_InitTraceLevels -- TRC_HCI
,10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_AVDT
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_AVRC
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_A2D
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_BNEP
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_BTM
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_GAP
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_PAN
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_SDP
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_GATT
,10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_SMP
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-13 20:09:04.147  5773  5827 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-13 20:09:04.221  5773  5827 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4227549
10-13 20:09:04.221  5773  5827 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4227549 
,10-13 20:09:04.235  5773  5789 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-13 20:09:04.236  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-13 20:09:04.237  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-13 20:09:04.238  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-13 20:09:04.239  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
10-13 20:09:04.239  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
10-13 20:09:04.239  5773  5789 D bt_hci  : do_postload posting postload work item
10-13 20:09:04.239  5773  5796 I bt_hci  : event_postload
10-13 20:09:04.239  5773  5796 I bt_vendor: sco_config_cb
,10-13 20:09:04.239  5773  5796 I bt_hci  : sco_config_callback postload finished.
,10-13 20:09:04.241  5773  5789 D bt_bte_conf: Device ID record 1 : primary
,10-13 20:09:04.241  5773  5789 D bt_bte_conf:   vendorId            = 000f
,10-13 20:09:04.241  5773  5789 D bt_bte_conf:   vendorIdSource      = 0001
10-13 20:09:04.241  5773  5789 D bt_bte_conf:   product             = 1200
10-13 20:09:04.241  5773  5789 D bt_bte_conf:   version             = 1436
10-13 20:09:04.241  5773  5789 D bt_bte_conf:   clientExecutableURL = 
10-13 20:09:04.241  5773  5789 D bt_bte_conf:   serviceDescription  = 
10-13 20:09:04.241  5773  5789 D bt_bte_conf:   documentationURL    = 
10-13 20:09:04.241  5773  5789 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-13 20:09:04.241  5773  5786 D bt_stack_manager: event_start_up_stack finished
10-13 20:09:04.242  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-13 20:09:04.242  5773  5785 D BluetoothAdapterProperties: Setting state to 15
10-13 20:09:04.242  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-13 20:09:04.242  5773  5785 I BluetoothAdapterState: Entering BleOnState
10-13 20:09:04.243  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.245  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-13 20:09:04.245  5773  5785 D BluetoothAdapterProperties: Setting state to 11
10-13 20:09:04.245  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-13 20:09:04.245  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.248  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.248  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:04.249  5773  5796 I bt_vendor: low_power_mode_cb
10-13 20:09:04.249  5773  5773 D HeadsetService: Received start request. Starting profile...
10-13 20:09:04.252  5773  5773 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-13 20:09:04.252  5773  5773 D HeadsetStateMachine: make
,10-13 20:09:04.258  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.260  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.262  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
10-13 20:09:04.262  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.267  5773  5773 D HeadsetStateMachine: max_hf_connections = 1
,10-13 20:09:04.267  5773  5773 I bt_bluedroid: get_profile_interface handsfree
10-13 20:09:04.267  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-13 20:09:04.267  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-13 20:09:04.270  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:04.270  5773  5773 D A2dpService: Received start request. Starting profile...
,10-13 20:09:04.271  5773  5773 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-13 20:09:04.271  5773  5773 I bt_bluedroid: get_profile_interface avrcp
,10-13 20:09:04.275  5773  5773 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-13 20:09:04.275  5773  5773 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-13 20:09:04.275  5773  5773 D A2dpStateMachine: make
,10-13 20:09:04.276  5773  5773 I bt_bluedroid: get_profile_interface a2dp
,10-13 20:09:04.277  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-13 20:09:04.277  5773  5835 D A2dpStateMachine: Enter Disconnected: -2
,10-13 20:09:04.278  5773  5773 I BluetoothHidServiceJni: classInitNative: succeeds
10-13 20:09:04.278  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:04.279  5773  5773 D HidService: Received start request. Starting profile...
10-13 20:09:04.279  5773  5773 I bt_bluedroid: get_profile_interface hidhost
10-13 20:09:04.279  5773  5773 D HidService: setHidService(): set to: null
10-13 20:09:04.279  5773  5789 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf420856d
10-13 20:09:04.279  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-13 20:09:04.280  5773  5773 I BluetoothHealthServiceJni: classInitNative: succeeds
10-13 20:09:04.280  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:04.280  5773  5773 D HealthService: Received start request. Starting profile...
10-13 20:09:04.281  5773  5773 I bt_bluedroid: get_profile_interface health
,10-13 20:09:04.282  5773  5773 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-13 20:09:04.282  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:04.283  5773  5773 D PanService: Received start request. Starting profile...
10-13 20:09:04.283  5725  5725 D BluetoothInputDevice: Proxy object connected
10-13 20:09:04.283  5773  5773 D BluetoothPanServiceJni: initializeNative(L110): pan
10-13 20:09:04.283  5773  5773 I bt_bluedroid: get_profile_interface pan
10-13 20:09:04.284  5773  5789 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-13 20:09:04.285  5725  5725 D HidProfile: Bluetooth service connected
,10-13 20:09:04.285  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:04.286  5773  5773 D BluetoothMapService: Received start request. Starting profile...
10-13 20:09:04.286  5773  5773 D BluetoothMapService: start()
10-13 20:09:04.286  5725  5725 D BluetoothPan: BluetoothPAN Proxy object connected
10-13 20:09:04.286  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-13 20:09:04.287  5725  5725 D PanProfile: Bluetooth service connected
10-13 20:09:04.287  5725  5725 D BluetoothMap: Proxy object connected
10-13 20:09:04.287  5725  5725 D MapProfile: Bluetooth service connected
,10-13 20:09:04.288  5725  5725 D BluetoothMap: getConnectedDevices()
10-13 20:09:04.288  5725  5725 D BluetoothMap: Bluetooth is Not enabled
10-13 20:09:04.289  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-13 20:09:04.290  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-13 20:09:04.290  5773  5773 D BluetoothMapAppObserver: createReceiver()
,10-13 20:09:04.291  5773  5773 D BluetoothMapAppObserver: initObservers()
10-13 20:09:04.291  5773  5773 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-13 20:09:04.295  5773  5773 V SapService: SapBinder()
,10-13 20:09:04.295  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:04.296  5773  5773 D SapService: Received start request. Starting profile...
10-13 20:09:04.296  5773  5773 V SapService: start()
,10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOff()=false
,10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.298  5773  5833 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOn()=true
,10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.298  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isTurningOn()=true
,10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.299  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.300  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:04.300  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:04.300  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.300  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,10-13 20:09:04.300  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-13 20:09:04.300  5773  5785 D BluetoothAdapterProperties: ScanMode =  20
10-13 20:09:04.300  5773  5785 D BluetoothAdapterProperties: State =  11
,10-13 20:09:04.300  5773  5785 D BluetoothAdapterProperties: Setting state to 12
,10-13 20:09:04.300  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-13 20:09:04.301  5773  5785 I BluetoothAdapterState: Entering OnState
10-13 20:09:04.301  5725  5735 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-13 20:09:04.301   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:04.301   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-13 20:09:04.302  3107  3953 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-13 20:09:04.302  5773  5789 D BluetoothAdapterProperties: Scan Mode:21
10-13 20:09:04.302  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
10-13 20:09:04.302  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-13 20:09:04.303  3107  3107 D BluetoothInputDevice: Proxy object connected
10-13 20:09:04.303  3107  3107 D HidProfile: Bluetooth service connected
10-13 20:09:04.303  3107  3119 D BluetoothPan: onBluetoothStateChange on: true
,10-13 20:09:04.304  5613  5613 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-13 20:09:04.305  5725  5840 D BluetoothPan: onBluetoothStateChange on: true
10-13 20:09:04.306  3107  3953 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-13 20:09:04.306  5613  5613 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-13 20:09:04.306  5725  5736 D BluetoothMap: onBluetoothStateChange: up=true
10-13 20:09:04.307  3107  3119 D BluetoothPbap: onBluetoothStateChange: up=true
10-13 20:09:04.307  3107  3107 D BluetoothPan: BluetoothPAN Proxy object connected
10-13 20:09:04.307  3107  3107 D PanProfile: Bluetooth service connected
10-13 20:09:04.309  3107  3120 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:04.309  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:04.311  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:04.315  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:04.315  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-13 20:09:04.315   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
10-13 20:09:04.316  5773  5773 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,10-13 20:09:04.316  5725  5735 D BluetoothPbap: onBluetoothStateChange: up=true
,10-13 20:09:04.317  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-13 20:09:04.317  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.318  3107  3953 D BluetoothMap: onBluetoothStateChange: up=true
10-13 20:09:04.318  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-13 20:09:04.319  3107  3107 D BluetoothMap: Proxy object connected
10-13 20:09:04.319  3107  3107 D MapProfile: Bluetooth service connected
10-13 20:09:04.319  3784  3807 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:04.319  3107  3107 D BluetoothMap: getConnectedDevices()
10-13 20:09:04.320   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:04.320  5773  5773 D ObexServerSockets: Succeed to create listening sockets 
10-13 20:09:04.320  5773  5773 D ObexServerSockets0: startAccept()
10-13 20:09:04.320  5773  5773 D ObexServerSockets0: prepareForNewConnect()
,10-13 20:09:04.321   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:04.321  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:09:04.323  5773  5773 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-13 20:09:04.323  5773  5773 D BluetoothSdpJni: SDP Create record success - handle: 0
10-13 20:09:04.323  5773  5842 D ObexServerSockets0: Accepting socket connection...
10-13 20:09:04.323  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.324  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-13 20:09:04.324  5773  5773 D BluetoothMapService: onReceive
10-13 20:09:04.324  5773  5773 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-13 20:09:04.324  5773  5773 D BluetoothMapService: STATE_ON
10-13 20:09:04.324   926   926 D BluetoothA2dp: Proxy object connected
10-13 20:09:04.324  3107  3107 D BluetoothA2dp: Proxy object connected
10-13 20:09:04.325  5773  5844 D ObexServerSockets0: Accepting socket connection...
,10-13 20:09:04.326  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.326  5725  5725 D LocalBluetoothProfileManager: Adding local A2DP profile
10-13 20:09:04.328  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.330  5725  5725 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-13 20:09:04.330  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.330  5773  5846 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-13 20:09:04.332  5773  5846 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-13 20:09:04.332  5773  5846 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-13 20:09:04.336  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-13 20:09:04.338  5725  5725 D BluetoothA2dp: Proxy object connected
,10-13 20:09:04.340  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-13 20:09:04.342  5725  5725 D DockEventReceiver: finishStartingService: stopping service
,10-13 20:09:04.345  5725  5725 D BluetoothPbap: Proxy object connected
10-13 20:09:04.345  5725  5725 D PbapServerProfile: Bluetooth service connected
10-13 20:09:04.349  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-13 20:09:04.349  5773  5773 D ObexServerSockets0: prepareForNewConnect()
10-13 20:09:04.351  3107  3107 D BluetoothPbap: Proxy object connected
,10-13 20:09:04.351  3107  3107 D PbapServerProfile: Bluetooth service connected
10-13 20:09:04.351  5773  5850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:09:04.366  5773  5854 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:09:04.367  5773  5854 I BtOppRfcommListener: Accept thread started.
,10-13 20:09:04.383  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.384  5613  5659 D io.jxcore.node.ConnectivityMonitor: stop
10-13 20:09:04.384  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-13 20:09:04.386  5613  5659 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
10-13 20:09:04.386  5613  5659 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-13 20:09:04.388  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.388  5773  5785 D BluetoothAdapterState: Current state: ON, message: 23
10-13 20:09:04.389  5773  5785 D BluetoothAdapterProperties: Setting state to 13
10-13 20:09:04.389  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-13 20:09:04.389  5773  5785 D BluetoothAdapterProperties: onBluetoothDisable()
,10-13 20:09:04.390  5773  5773 D BluetoothMapService: onReceive
10-13 20:09:04.390  5773  5773 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-13 20:09:04.391  5773  5773 D BluetoothMapService: STATE_TURNING_OFF
,10-13 20:09:04.391  5773  5773 D BluetoothMapService: MAP Service closeService in
,10-13 20:09:04.391  5773  5773 D BluetoothMapMasInstance0: MAP Service shutdown
10-13 20:09:04.391  5773  5773 D ObexServerSockets0: shutdown(block = true)
10-13 20:09:04.391  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
10-13 20:09:04.392  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-13 20:09:04.392  5773  5842 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-13 20:09:04.392  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-13 20:09:04.392  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
10-13 20:09:04.392  5773  5844 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-13 20:09:04.392  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-13 20:09:04.393  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-13 20:09:04.393  5773  5830 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-13 20:09:04.394  5773  5773 I BtOppRfcommListener: stopping Accept Thread
10-13 20:09:04.394  5773  5854 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-13 20:09:04.394  5773  5854 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-13 20:09:04.396  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:04.396  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:09:04.396  5773  5773 D HeadsetService: Received stop request...Stopping profile...
10-13 20:09:04.398  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-13 20:09:04.398  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.399  5773  5773 D A2dpService: Received stop request...Stopping profile...
,10-13 20:09:04.399  5773  5835 D A2dpStateMachine: Exit Disconnected: -1
,10-13 20:09:04.400   926   926 D BluetoothA2dp: Proxy object disconnected
10-13 20:09:04.401  5725  5725 D DockEventReceiver: finishStartingService: stopping service
10-13 20:09:04.401  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:04.401  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:04.403  5613  5613 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-13 20:09:04.403  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.403  5725  5725 D BluetoothA2dp: Proxy object disconnected
10-13 20:09:04.406  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-13 20:09:04.406  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.406  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.406  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.406  3107  3107 D BluetoothA2dp: Proxy object disconnected
10-13 20:09:04.406  5773  5773 D HidService: Received stop request...Stopping profile...
10-13 20:09:04.406  5773  5773 D HidService: Stopping Bluetooth HidService
10-13 20:09:04.407  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-13 20:09:04.407  3107  3107 D BluetoothInputDevice: Proxy object disconnected
10-13 20:09:04.407  3107  3107 D HidProfile: Bluetooth service disconnected
10-13 20:09:04.407  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.409  5725  5725 D BluetoothInputDevice: Proxy object disconnected
10-13 20:09:04.409  5725  5725 D HidProfile: Bluetooth service disconnected
,10-13 20:09:04.411  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.411  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-13 20:09:04.412  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-13 20:09:04.412  5773  5827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:09:04.412  5773  5827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:09:04.412  5773  5827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:09:04.412  5773  5773 D HealthService: Received stop request...Stopping profile...
10-13 20:09:04.413  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-13 20:09:04.413  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-13 20:09:04.413  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.413  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.413  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.414  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
10-13 20:09:04.414  5773  5773 D PanService: Received stop request...Stopping profile...
,10-13 20:09:04.415  3107  3107 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-13 20:09:04.415  3107  3107 D PanProfile: Bluetooth service disconnected
10-13 20:09:04.416  5725  5725 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-13 20:09:04.416  5725  5725 D PanProfile: Bluetooth service disconnected
10-13 20:09:04.416  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-13 20:09:04.416  5773  5827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:09:04.416  5773  5827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:09:04.416  5773  5827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-13 20:09:04.416  5773  5827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-13 20:09:04.417  5773  5827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-13 20:09:04.417  5773  5827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-13 20:09:04.417  5773  5773 D BluetoothMapService: Received stop request...Stopping profile...
10-13 20:09:04.417  5773  5773 D BluetoothMapService: stop()
,10-13 20:09:04.417  5773  5773 D BluetoothMapAppObserver: deinitObservers()
,10-13 20:09:04.417  5773  5773 D BluetoothMapAppObserver: removeReceiver()
,10-13 20:09:04.419  3107  3107 D BluetoothMap: Proxy object disconnected
10-13 20:09:04.419  5725  5725 D BluetoothMap: Proxy object disconnected
10-13 20:09:04.419  3107  3107 D MapProfile: Bluetooth service disconnected
10-13 20:09:04.419  5725  5725 D MapProfile: Bluetooth service disconnected
10-13 20:09:04.419  5773  5773 D SapService: Received stop request...Stopping profile...
10-13 20:09:04.419  5773  5773 V SapService: stop()
10-13 20:09:04.422  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-13 20:09:04.422  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.422  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.422  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,10-13 20:09:04.422  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-13 20:09:04.423  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-13 20:09:04.423  3107  3107 D BluetoothPbap: Proxy object disconnected
10-13 20:09:04.423  3107  3107 D PbapServerProfile: Bluetooth service disconnected
10-13 20:09:04.423  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-13 20:09:04.423  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-13 20:09:04.423  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.423  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.423  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
,10-13 20:09:04.423  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-13 20:09:04.423  5773  5789 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-13 20:09:04.424  5725  5725 D BluetoothPbap: Proxy object disconnected
10-13 20:09:04.424  5725  5725 D PbapServerProfile: Bluetooth service disconnected
10-13 20:09:04.424  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-13 20:09:04.424  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-13 20:09:04.424  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.424  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.424  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.424  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,10-13 20:09:04.425  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-13 20:09:04.425  5773  5773 D BluetoothMapService: MAP Service closeService in
10-13 20:09:04.425  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-13 20:09:04.425  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.425  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.425  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.426  5773  5773 D BluetoothMapService: cleanup()
10-13 20:09:04.426  5773  5773 D BluetoothMapService: MAP Service closeService in
10-13 20:09:04.426  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-13 20:09:04.426  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.426  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.426  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:04.426  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-13 20:09:04.427  5773  5785 D BluetoothAdapterProperties: Setting state to 15
10-13 20:09:04.427  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-13 20:09:04.427  5773  5785 I BluetoothAdapterState: Entering BleOnState
10-13 20:09:04.428  5725  5736 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-13 20:09:04.435   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-13 20:09:04.435   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:09:04.435  3107  3119 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-13 20:09:04.436  3107  3953 D BluetoothPan: onBluetoothStateChange on: false
10-13 20:09:04.436  5725  5735 D BluetoothPan: onBluetoothStateChange on: false
10-13 20:09:04.437  3107  3120 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:09:04.437  5725  5840 D BluetoothMap: onBluetoothStateChange: up=false
10-13 20:09:04.438  3107  3119 D BluetoothPbap: onBluetoothStateChange: up=false
10-13 20:09:04.438  3107  3953 D BluetoothA2dp: onBluetoothStateChange: up=false
10-13 20:09:04.439   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
10-13 20:09:04.439  5725  5736 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:09:04.440  5725  5735 D BluetoothPbap: onBluetoothStateChange: up=false
10-13 20:09:04.440  3555  5826 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
10-13 20:09:04.440  3107  3120 D BluetoothMap: onBluetoothStateChange: up=false
10-13 20:09:04.440  3784  3807 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:09:04.441   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
10-13 20:09:04.441  5725  5840 D BluetoothA2dp: onBluetoothStateChange: up=false
10-13 20:09:04.442  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-13 20:09:04.442  5773  5785 D BluetoothAdapterProperties: Setting state to 16
10-13 20:09:04.442  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-13 20:09:04.443  5773  5785 D BluetoothAdapterProperties: onBleDisable
10-13 20:09:04.443  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
10-13 20:09:04.443  5773  5786 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-13 20:09:04.445  5773  5827 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,10-13 20:09:04.445  5773  5827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-13 20:09:04.445  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
10-13 20:09:04.446  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.447  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-13 20:09:04.449  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.452  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:04.453  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-13 20:09:04.455  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.457  5725  5725 D DockEventReceiver: finishStartingService: stopping service
,10-13 20:09:04.602  3555  5824 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-13 20:09:04.645  5773  5789 I bt_hci  : shut_down
,10-13 20:09:04.645  5773  5796 D bt_hwcfg: hw_epilog_process
10-13 20:09:04.645  5773  5796 I bt_vendor: low_power_mode_cb
,10-13 20:09:04.648  5773  5796 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-13 20:09:04.648  5773  5796 I bt_vendor: epilog_cb
10-13 20:09:04.648  5773  5796 I bt_hci  : epilog_finished_callback
10-13 20:09:04.648  5773  5789 I bt_hci_h4: hal_close
10-13 20:09:04.649  5773  5789 I bt_userial_vendor: device fd = 54 close
,10-13 20:09:04.667  3555  5822 W Uploader:  no longer exists, so no auth token.
,10-13 20:09:04.671   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:04.674  3555  5826 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-13 20:09:04.753  3555  5824 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,10-13 20:09:04.761  5773  5786 D bt_stack_manager: event_shut_down_stack finished.
,10-13 20:09:04.761  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-13 20:09:04.763  5773  5785 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-13 20:09:04.763  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-13 20:09:04.764  5773  5773 D BtGatt.GattService: Received stop request...Stopping profile...
,10-13 20:09:04.764  5773  5773 D BtGatt.GattService: stop()
10-13 20:09:04.764  5773  5773 D BtGatt.AdvertiseManager: advertise clients cleared
10-13 20:09:04.766  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:04.766  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:04.766  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:04.766  5773  5773 V BluetoothAdapterState: isBleTurningOff()=true
10-13 20:09:04.766  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-13 20:09:04.766  5773  5785 D BluetoothAdapterProperties: Setting state to 10
,10-13 20:09:04.767  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-13 20:09:04.767  5773  5785 I BluetoothAdapterState: Entering OffState
,10-13 20:09:04.768   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-13 20:09:04.776  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-13 20:09:04.776  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-13 20:09:04.776  5773  5773 I BluetoothServiceJni: cleanupNative: return from cleanup
10-13 20:09:04.777  5773  5786 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-13 20:09:04.782  5773  5773 I art     : System.exit called, status: 0
,10-13 20:09:04.783  5773  5773 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-13 20:09:04.807   926   937 I ActivityManager: Process com.android.bluetooth (pid 5773) has died
,10-13 20:09:04.825   926  2952 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-13 20:09:04.890  5613  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:04.891  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:09:04.891  5613  5672 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-13 20:09:04.891  5613  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:04.894  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:04.916   926   943 I ActivityManager: Start proc 5861:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-13 20:09:04.986  5861  5861 D AdapterServiceConfig: Adding HeadsetService
,10-13 20:09:04.987  5861  5861 D AdapterServiceConfig: Adding A2dpService
10-13 20:09:04.987  5861  5861 D AdapterServiceConfig: Adding HidService
10-13 20:09:04.987  5861  5861 D AdapterServiceConfig: Adding HealthService
,10-13 20:09:04.987  5861  5861 D AdapterServiceConfig: Adding PanService
10-13 20:09:04.988  5861  5861 D AdapterServiceConfig: Adding GattService
10-13 20:09:04.988  5861  5861 D AdapterServiceConfig: Adding BluetoothMapService
,10-13 20:09:04.988  5861  5861 D AdapterServiceConfig: Adding SapService
,10-13 20:09:05.001   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4e88818:true
,10-13 20:09:05.001  5861  5861 D BluetoothAdapterState: make() - Creating AdapterState
,10-13 20:09:05.004  5861  5861 I bt_bluedroid: init
10-13 20:09:05.004  5861  5873 I BluetoothAdapterState: Entering OffState
,10-13 20:09:05.006  5861  5874 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-13 20:09:05.006  5861  5874 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-13 20:09:05.006  5861  5874 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-13 20:09:05.006  5861  5874 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-13 20:09:05.007  5861  5861 I bt_bluedroid: get_profile_interface socket
,10-13 20:09:05.008  5861  5861 I bt_bluedroid: get_profile_interface sdp
10-13 20:09:05.008  5861  5877 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-13 20:09:05.009  5861  5877 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-13 20:09:05.013  5861  5872 I bt_bluedroid: config_hci_snoop_log
,10-13 20:09:05.014   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-13 20:09:05.065  5861  5873 D BluetoothAdapterState: Current state: OFF, message: 0
,10-13 20:09:05.065  5861  5873 D BluetoothAdapterProperties: Setting state to 14
10-13 20:09:05.065  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-13 20:09:05.067  5861  5873 D BluetoothBondStateMachine: make
,10-13 20:09:05.068  5861  5878 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-13 20:09:05.071  5861  5873 I BluetoothAdapterState: Entering PendingCommandState
,10-13 20:09:05.071  5861  5861 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-13 20:09:05.073  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:05.074  5861  5861 D BtGatt.DebugUtils: handleDebugAction() action=null
10-13 20:09:05.074  5861  5861 D BtGatt.GattService: Received start request. Starting profile...
10-13 20:09:05.074  5861  5861 D BtGatt.GattService: start()
10-13 20:09:05.074  5861  5861 I bt_bluedroid: get_profile_interface gatt
,10-13 20:09:05.075  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:05.075  5861  5861 D BtGatt.AdvertiseManager: advertise manager created
,10-13 20:09:05.080  5861  5861 V BluetoothAdapterState: isTurningOff()=false
,10-13 20:09:05.080  5861  5861 V BluetoothAdapterState: isTurningOn()=false
10-13 20:09:05.080  5861  5861 V BluetoothAdapterState: isBleTurningOn()=true
10-13 20:09:05.080  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:05.080  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-13 20:09:05.081  5861  5873 I bt_bluedroid: bt_bluedroid
10-13 20:09:05.081  5861  5874 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-13 20:09:05.082  5861  5874 I bt_hci  : start_up
,10-13 20:09:05.086  5861  5874 I bt_vendor: alloc value 0xf42a9871
,10-13 20:09:05.086  5861  5874 I bt_vendor: init
10-13 20:09:05.086  5861  5874 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-13 20:09:05.087  5861  5874 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-13 20:09:05.196  5861  5874 D bt_hci  : start_up starting async portion
10-13 20:09:05.197  5861  5881 I bt_hci  : event_finish_startup
,10-13 20:09:05.197  5861  5881 I bt_hci_h4: hal_open
10-13 20:09:05.197  5861  5881 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-13 20:09:05.192  5882  5882 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-13 20:09:05.198  5861  5881 I bt_userial_vendor: device fd = 54 open
,10-13 20:09:05.211  5861  5881 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-13 20:09:05.213  5861  5881 D bt_hwcfg: Chipset BCM4358A3
,10-13 20:09:05.213  5861  5881 D bt_hwcfg: Target name = [BCM4358A3]
10-13 20:09:05.213  5861  5881 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-13 20:09:05.397  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-13 20:09:05.590  5861  5881 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-13 20:09:05.590  5861  5881 D bt_hwcfg: Settlement delay -- 100 ms
10-13 20:09:05.590  5861  5881 I bt_hwcfg: Setting fw settlement delay to 100 
,10-13 20:09:05.672   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-13 20:09:05.714  5861  5881 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-13 20:09:05.714  5861  5881 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-13 20:09:05.716  5861  5881 I bt_hwcfg: vendor lib fwcfg completed
10-13 20:09:05.716  5861  5881 I bt_vendor: firmware callback
10-13 20:09:05.716  5861  5881 I bt_hci  : firmware_config_callback
,10-13 20:09:05.725  5861  5885 I bt_btu  : btu_task pending for preload complete event
,10-13 20:09:05.725  5861  5885 I bt_btu_task: Bluetooth chip preload is complete
10-13 20:09:05.726  5861  5885 I bt_btu  : btu_task received preload complete event
,10-13 20:09:05.731  5861  5885 I         : BTE_InitTraceLevels -- TRC_HCI
,10-13 20:09:05.732  5861  5885 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-13 20:09:05.732  5861  5885 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-13 20:09:05.732  5861  5885 I         : BTE_InitTraceLevels -- TRC_AVDT
10-13 20:09:05.732  5861  5885 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-13 20:09:05.732  5861  5885 I         : BTE_InitTraceLevels -- TRC_A2D
10-13 20:09:05.732  5861  5885 I         : BTE_InitTraceLevels -- TRC_BNEP
10-13 20:09:05.732  5861  5885 I         : BTE_InitTraceLevels -- TRC_BTM
10-13 20:09:05.733  5861  5885 I         : BTE_InitTraceLevels -- TRC_GAP
,10-13 20:09:05.733  5861  5885 I         : BTE_InitTraceLevels -- TRC_PAN
10-13 20:09:05.733  5861  5885 I         : BTE_InitTraceLevels -- TRC_SDP
10-13 20:09:05.733  5861  5885 I         : BTE_InitTraceLevels -- TRC_GATT
10-13 20:09:05.733  5861  5885 I         : BTE_InitTraceLevels -- TRC_SMP
,10-13 20:09:05.733  5861  5885 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-13 20:09:05.733  5861  5885 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-13 20:09:05.817  5861  5885 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4227549
10-13 20:09:05.817  5861  5885 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4227549 
,10-13 20:09:05.834  5861  5877 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-13 20:09:05.836  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-13 20:09:05.836  5861  5877 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-13 20:09:05.839  5861  5877 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-13 20:09:05.841  5861  5877 D BluetoothAdapterProperties: Scan Mode:20
10-13 20:09:05.842  5861  5877 D BluetoothAdapterProperties: Discoverable Timeout:120
10-13 20:09:05.842  5861  5877 D bt_hci  : do_postload posting postload work item
,10-13 20:09:05.842  5861  5881 I bt_hci  : event_postload
10-13 20:09:05.842  5861  5881 I bt_vendor: sco_config_cb
10-13 20:09:05.842  5861  5881 I bt_hci  : sco_config_callback postload finished.
10-13 20:09:05.846  5861  5877 D bt_bte_conf: Device ID record 1 : primary
10-13 20:09:05.846  5861  5877 D bt_bte_conf:   vendorId            = 000f
10-13 20:09:05.846  5861  5877 D bt_bte_conf:   vendorIdSource      = 0001
10-13 20:09:05.846  5861  5877 D bt_bte_conf:   product             = 1200
,10-13 20:09:05.846  5861  5877 D bt_bte_conf:   version             = 1436
,10-13 20:09:05.847  5861  5877 D bt_bte_conf:   clientExecutableURL = 
,10-13 20:09:05.847  5861  5877 D bt_bte_conf:   serviceDescription  = 
10-13 20:09:05.847  5861  5877 D bt_bte_conf:   documentationURL    = 
10-13 20:09:05.847  5861  5877 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-13 20:09:05.847  5861  5874 D bt_stack_manager: event_start_up_stack finished
,10-13 20:09:05.849  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-13 20:09:05.849  5861  5873 D BluetoothAdapterProperties: Setting state to 15
10-13 20:09:05.849  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-13 20:09:05.852  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:05.852  5861  5881 I bt_vendor: low_power_mode_cb
10-13 20:09:05.855  5861  5873 I BluetoothAdapterState: Entering BleOnState
10-13 20:09:05.855  5861  5873 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-13 20:09:05.855  5861  5873 D BluetoothAdapterProperties: Setting state to 11
10-13 20:09:05.855  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-13 20:09:05.856  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:05.861  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:05.866   926   926 D BluetoothHeadset: Proxy object connected
,10-13 20:09:05.866   926   926 D BluetoothHeadset: Proxy object connected
10-13 20:09:05.866  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:05.866   926   926 D BluetoothHeadset: Proxy object connected
,10-13 20:09:05.869  5725  5840 D BluetoothHeadset: Proxy object connected
,10-13 20:09:05.870  5861  5861 D HeadsetService: Received start request. Starting profile...
10-13 20:09:05.870  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:05.872  5861  5861 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-13 20:09:05.873  5861  5861 D HeadsetStateMachine: make
10-13 20:09:05.873  3784  3806 D BluetoothHeadset: Proxy object connected
10-13 20:09:05.874  3107  3953 D BluetoothHeadset: Proxy object connected
10-13 20:09:05.874  3107  3107 D HeadsetProfile: Bluetooth service connected
10-13 20:09:05.876  5725  5725 D HeadsetProfile: Bluetooth service connected
10-13 20:09:05.879  5861  5873 I BluetoothAdapterState: Entering PendingCommandState
,10-13 20:09:05.881  5861  5861 D HeadsetStateMachine: max_hf_connections = 1
,10-13 20:09:05.882  5861  5861 I bt_bluedroid: get_profile_interface handsfree
10-13 20:09:05.882  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-13 20:09:05.882  5861  5877 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-13 20:09:05.885  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:05.885  5861  5861 D A2dpService: Received start request. Starting profile...
,10-13 20:09:05.886  5861  5861 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-13 20:09:05.886  5861  5861 I bt_bluedroid: get_profile_interface avrcp
,10-13 20:09:05.892  5861  5861 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-13 20:09:05.892  5861  5861 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-13 20:09:05.892  5861  5861 D A2dpStateMachine: make
10-13 20:09:05.893  5861  5861 I bt_bluedroid: get_profile_interface a2dp
,10-13 20:09:05.895  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
10-13 20:09:05.895  5861  5893 D A2dpStateMachine: Enter Disconnected: -2
,10-13 20:09:05.896  5861  5861 I BluetoothHidServiceJni: classInitNative: succeeds
10-13 20:09:05.897  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:05.897  5861  5861 D HidService: Received start request. Starting profile...
,10-13 20:09:05.897  5861  5861 I bt_bluedroid: get_profile_interface hidhost
10-13 20:09:05.897  5861  5877 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf420856d
10-13 20:09:05.897  5861  5861 D HidService: setHidService(): set to: null
10-13 20:09:05.897  5861  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,10-13 20:09:05.898  5861  5861 I BluetoothHealthServiceJni: classInitNative: succeeds
10-13 20:09:05.899  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:05.900  5861  5861 D HealthService: Received start request. Starting profile...
,10-13 20:09:05.901  5861  5861 I bt_bluedroid: get_profile_interface health
,10-13 20:09:05.902  5861  5861 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-13 20:09:05.903  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:05.903  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
10-13 20:09:05.903  5861  5861 D PanService: Received start request. Starting profile...
10-13 20:09:05.903  5861  5861 D BluetoothPanServiceJni: initializeNative(L110): pan
10-13 20:09:05.904  5861  5861 I bt_bluedroid: get_profile_interface pan
10-13 20:09:05.904  5861  5877 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-13 20:09:05.906  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:05.906  5861  5861 D BluetoothMapService: Received start request. Starting profile...
10-13 20:09:05.906  5861  5861 D BluetoothMapService: start()
,10-13 20:09:05.909  5861  5861 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-13 20:09:05.910  5861  5861 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-13 20:09:05.910  5861  5861 D BluetoothMapAppObserver: createReceiver()
10-13 20:09:05.912  5861  5861 D BluetoothMapAppObserver: initObservers()
10-13 20:09:05.912  5861  5861 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-13 20:09:05.918  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-13 20:09:05.919  5861  5861 V SapService: SapBinder()
,10-13 20:09:05.919  5861  5861 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
10-13 20:09:05.920  5861  5861 D SapService: Received start request. Starting profile...
10-13 20:09:05.920  5861  5861 V SapService: start()
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
,10-13 20:09:05.922  5861  5891 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:05.922  5861  5861 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
,10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:05.923  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
10-13 20:09:05.924  5861  5861 V BluetoothAdapterState: isTurningOff()=false
,10-13 20:09:05.924  5861  5861 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:05.924  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:05.924  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
,10-13 20:09:05.925  5861  5861 V BluetoothAdapterState: isTurningOff()=false
10-13 20:09:05.925  5861  5861 V BluetoothAdapterState: isTurningOn()=true
10-13 20:09:05.925  5861  5861 V BluetoothAdapterState: isBleTurningOn()=false
10-13 20:09:05.925  5861  5861 V BluetoothAdapterState: isBleTurningOff()=false
,10-13 20:09:05.926  5861  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-13 20:09:05.926  5861  5873 D BluetoothAdapterProperties: ScanMode =  20
10-13 20:09:05.926  5861  5873 D BluetoothAdapterProperties: State =  11
,10-13 20:09:05.928  5861  5877 D BluetoothAdapterProperties: Scan Mode:21
,10-13 20:09:05.928  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-13 20:09:05.928  5861  5873 D BluetoothAdapterProperties: Setting state to 12
10-13 20:09:05.929  5861  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-13 20:09:05.929  5861  5877 D BluetoothAdapterProperties: Discoverable Timeout:120
10-13 20:09:05.929  5725  5735 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-13 20:09:05.929  5861  5873 I BluetoothAdapterState: Entering OnState
10-13 20:09:05.931   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:05.931   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:05.931  3107  3119 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-13 20:09:05.932  5725  5725 D BluetoothInputDevice: Proxy object connected
,10-13 20:09:05.932  5725  5725 D HidProfile: Bluetooth service connected
,10-13 20:09:05.936  5861  5861 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:05.936  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:09:05.937  5861  5861 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-13 20:09:05.938  5861  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:09:05.938  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:05.940  3107  3107 D BluetoothInputDevice: Proxy object connected
10-13 20:09:05.940  3107  3107 D HidProfile: Bluetooth service connected
,10-13 20:09:05.941  3107  3953 D BluetoothPan: onBluetoothStateChange on: true
,10-13 20:09:05.942  5861  5861 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:09:05.943  5725  5736 D BluetoothPan: onBluetoothStateChange on: true
,10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:05.944  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-13 20:09:05.945  3107  3120 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:05.945  5725  5735 D BluetoothMap: onBluetoothStateChange: up=true
10-13 20:09:05.946  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:05.947  3107  3119 D BluetoothPbap: onBluetoothStateChange: up=true
,10-13 20:09:05.947  5861  5861 D ObexServerSockets: Succeed to create listening sockets 
10-13 20:09:05.947  5861  5861 D ObexServerSockets0: startAccept()
10-13 20:09:05.947  5861  5861 D ObexServerSockets0: prepareForNewConnect()
10-13 20:09:05.949  3107  3953 D BluetoothA2dp: onBluetoothStateChange: up=true
10-13 20:09:05.950  5861  5861 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-13 20:09:05.950  5861  5861 D BluetoothSdpJni: SDP Create record success - handle: 0
10-13 20:09:05.951  5861  5899 D ObexServerSockets0: Accepting socket connection...
10-13 20:09:05.951   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
10-13 20:09:05.951  5861  5900 D ObexServerSockets0: Accepting socket connection...
10-13 20:09:05.951  3107  3107 D BluetoothPan: BluetoothPAN Proxy object connected
10-13 20:09:05.951  3107  3107 D PanProfile: Bluetooth service connected
10-13 20:09:05.952  5725  5736 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:05.952  5725  5840 D BluetoothPbap: onBluetoothStateChange: up=true
,10-13 20:09:05.953   926   926 D BluetoothA2dp: Proxy object connected
10-13 20:09:05.953  3107  3107 D BluetoothA2dp: Proxy object connected
10-13 20:09:05.954  3107  3953 D BluetoothMap: onBluetoothStateChange: up=true
,10-13 20:09:05.956  5725  5725 D BluetoothPan: BluetoothPAN Proxy object connected
10-13 20:09:05.956  5725  5725 D PanProfile: Bluetooth service connected
10-13 20:09:05.956  5725  5725 D BluetoothMap: Proxy object connected
,10-13 20:09:05.956  5725  5725 D MapProfile: Bluetooth service connected
,10-13 20:09:05.957  5725  5725 D BluetoothMap: getConnectedDevices()
10-13 20:09:05.957  3784  3980 D BluetoothHeadset: onBluetoothStateChange: up=true
10-13 20:09:05.957  3107  3107 D BluetoothMap: Proxy object connected
10-13 20:09:05.957  3107  3107 D MapProfile: Bluetooth service connected
10-13 20:09:05.957   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-13 20:09:05.957  3107  3107 D BluetoothMap: getConnectedDevices()
10-13 20:09:05.957  5725  5736 D BluetoothA2dp: onBluetoothStateChange: up=true
10-13 20:09:05.960   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
10-13 20:09:05.960   926   926 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
10-13 20:09:05.960  5861  5861 D BluetoothMapService: onReceive
10-13 20:09:05.961  5861  5861 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-13 20:09:05.961  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-13 20:09:05.961  5861  5861 D BluetoothMapService: STATE_ON
10-13 20:09:05.963  5861  5901 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-13 20:09:05.963  5725  5725 D BluetoothA2dp: Proxy object connected
10-13 20:09:05.963  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:05.965  5861  5901 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-13 20:09:05.965  5861  5901 D BluetoothSdpJni: SDP Create record success - handle: 1
10-13 20:09:05.965  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:05.969  5725  5725 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-13 20:09:05.974  3555  3555 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-13 20:09:05.974  5725  5725 D DockEventReceiver: finishStartingService: stopping service
,10-13 20:09:05.982  5725  5725 D BluetoothPbap: Proxy object connected
,10-13 20:09:05.982  5725  5725 D PbapServerProfile: Bluetooth service connected
,10-13 20:09:05.987  5861  5861 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-13 20:09:05.987  5861  5861 D ObexServerSockets0: prepareForNewConnect()
10-13 20:09:05.989  5861  5906 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:09:05.995  3107  3107 D BluetoothPbap: Proxy object connected
10-13 20:09:05.995  3107  3107 D PbapServerProfile: Bluetooth service connected
,10-13 20:09:06.005  5861  5910 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:09:06.006  5861  5910 I BtOppRfcommListener: Accept thread started.
,10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:06.413  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:06.418  5613  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:06.421  5613  5659 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,10-13 20:09:06.423   926  3802 D WifiService: setWifiEnabled: false pid=5613, uid=10077
10-13 20:09:06.423   926  3802 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-13 20:09:06.425   926  2950 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-13 20:09:06.425   926  2950 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-13 20:09:06.425   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-13 20:09:06.426   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-13 20:09:06.427  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:06.437   926  5795 D DhcpClient: Clearing IP address
,10-13 20:09:06.438   506   919 D CommandListener: Clearing all IP addresses on wlan0
,10-13 20:09:06.445   506   919 D CommandListener: Setting iface cfg
,10-13 20:09:06.449   926  5797 D DhcpClient: Receive thread stopped
,10-13 20:09:06.452  3555  5820 V NativeCrypto: Read error: ssl=0x7f73fb5d00: I/O error during system call, Connection timed out
,10-13 20:09:06.454  3555  5820 V NativeCrypto: SSL shutdown failed: ssl=0x7f73fb5d00: I/O error during system call, Broken pipe
,10-13 20:09:06.456   926  3802 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,10-13 20:09:06.457   926  5790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-13 20:09:06.459   926  5790 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
10-13 20:09:06.459   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
10-13 20:09:06.460   926  2952 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-13 20:09:06.461   926  2952 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-13 20:09:06.467   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-13 20:09:06.467   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
10-13 20:09:06.473   926   926 D RttService: SCAN_AVAILABLE : 1
10-13 20:09:06.473   532   532 E Parcel  : Reading a NULL string not supported here.
,10-13 20:09:06.474   926  3059 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-13 20:09:06.474   926  2952 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,10-13 20:09:06.477  3740  3883 W QCNEJ   : |CORE| network lost: 101
10-13 20:09:06.478  3740  3883 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-13 20:09:06.483   926  2950 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-13 20:09:06.492   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-13 20:09:06.506   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-13 20:09:06.527   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-13 20:09:06.527   506   919 D CommandListener: Clearing all IP addresses on wlan0
,10-13 20:09:06.529   926  2952 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-13 20:09:06.529   926  2952 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-13 20:09:06.531   926   943 D Tethering: MasterInitialState.processMessage what=3
,10-13 20:09:06.533   926  2950 D DhcpClient: doQuit
10-13 20:09:06.533   926  2950 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-13 20:09:06.533   926  5795 D DhcpClient: onQuitting
10-13 20:09:06.533  5720  5720 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:06.537  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-13 20:09:06.541  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:06.544  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:09:06.546  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:06.549  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-13 20:09:06.551  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:09:06.553  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:06.554  4888  4888 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-13 20:09:06.557  5720  5720 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-13 20:09:06.557  3856  3856 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-13 20:09:06.559  5034  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-13 20:09:06.559  5034  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-13 20:09:06.559  5034  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-13 20:09:06.559  5034  5059 E SarControlService: no key has been found,reset the power
10-13 20:09:06.559  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-13 20:09:06.559  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-13 20:09:06.559  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-13 20:09:06.560  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-13 20:09:06.560  5061  5061 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-13 20:09:06.562  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-13 20:09:06.562  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-13 20:09:06.562  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-13 20:09:06.565  3856  3856 D SystemUpdateService: onCreate
10-13 20:09:06.565  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-13 20:09:06.566  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-13 20:09:06.566  5061  5061 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,10-13 20:09:06.570  3856  3856 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-13 20:09:06.572  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000ee03000000000000ffffffff]
10-13 20:09:06.573  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-13 20:09:06.573  5061  5079 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-13 20:09:06.573  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:09:06.573  5034  5044 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-13 20:09:06.575  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000ef03000000000000ffffffff]
,10-13 20:09:06.575  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-13 20:09:06.575  5061  5079 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
,10-13 20:09:06.576  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:09:06.576  5034  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-13 20:09:06.578  3856  5920 I SystemUpdateService: active receiver: enabled
,10-13 20:09:06.580  3856  3856 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-13 20:09:06.585  3856  5400 I iu.UploadsManager: num queued entries: 0
,10-13 20:09:06.585  3856  5400 I iu.UploadsManager: num updated entries: 0
,10-13 20:09:06.586  3856  5400 I iu.SyncManager: NEXT; no task
,10-13 20:09:06.587  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-13 20:09:06.589  3856  3856 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-13 20:09:06.590  5404  5404 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-13 20:09:06.594   506   919 E Netd    : netlink response contains error (No such file or directory)
,10-13 20:09:06.594  5404  5404 D SprintDMHelper: simOperator: 
10-13 20:09:06.594  5404  5404 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-13 20:09:06.595   926  2952 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-13 20:09:06.596  3856  5920 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-13 20:09:06.603  5720  5720 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-13 20:09:06.604  3856  5920 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,10-13 20:09:06.604  3856  5920 I SystemUpdateService: now status is 0 (complete)
10-13 20:09:06.604  3856  5920 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-13 20:09:06.604  3856  5920 I SystemUpdateService: file has been verified
,10-13 20:09:06.607  5009  5923 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-13 20:09:06.608  3856  5920 I SystemUpdateService: OTA package size = 21989297
,10-13 20:09:06.612  5720  5720 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-13 20:09:06.626  3856  5920 I SystemUpdateService: showing system update notification
,10-13 20:09:06.637  3856  3856 D SystemUpdateService: onDestroy
,10-13 20:09:06.716   926  2950 D wifi    : In wifi stop Hal
,10-13 20:09:06.716   926  2950 D wifi    : halHandle = 0x7f62482c80, mVM = 0x7f7eb0d140, mCls = 0x1342
,10-13 20:09:06.716  5009  5009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-13 20:09:06.716   926  5719 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-13 20:09:06.716   926  5719 D WifiHAL : Got a signal to exit!!!
10-13 20:09:06.716   926  5719 I WifiHAL : Exit wifi_event_loop
10-13 20:09:06.717   926  2950 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-13 20:09:06.717   926  2950 E WifiHAL : Event processing terminated
10-13 20:09:06.718   926  2950 D wifi    : In wifi cleaned up handler
10-13 20:09:06.718   926  2950 I WifiHAL : Internal cleanup completed
,10-13 20:09:06.720  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:06.720  4060  4199 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-13 20:09:06.721  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:06.743   926  5719 D wifi    : set interface wlan0 flags (DOWN)
,10-13 20:09:06.743   926  2950 D WifiNative-HAL: HAL event thread stopped successfully
,10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:06.935  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-13 20:09:06.943  5613  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:09:06.946   926  3103 D WifiService: setWifiEnabled: true pid=5613, uid=10077
,10-13 20:09:06.946   926  3103 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:09:06.949  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:06.950   926   943 D Tethering: InitialState.processMessage what=4
10-13 20:09:06.954   506   919 D SoftapController: Softap fwReload - Ok
,10-13 20:09:06.960   506   919 D CommandListener: Setting iface cfg
,10-13 20:09:06.960   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-13 20:09:06.960   506   919 D CommandListener: Trying to bring down wlan0
,10-13 20:09:06.962   506   919 D CommandListener: Clearing all IP addresses on wlan0
,10-13 20:09:06.967   926  2950 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-13 20:09:07.453   926  3818 D WifiService: setWifiEnabled: true pid=5613, uid=10077
,10-13 20:09:07.457   926  3818 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-13 20:09:07.568   926  2950 D wifi    : set interface wlan0 flags (UP)
,10-13 20:09:07.569   926  2950 I WifiHAL : Initializing wifi
,10-13 20:09:07.569   926  2950 I WifiHAL : Creating socket
,10-13 20:09:07.573   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-13 20:09:07.576   926  2950 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-13 20:09:07.576   926  2950 D wifi    : Did set static halHandle = 0x7f62482c80
,10-13 20:09:07.576   926  2950 D wifi    : halHandle = 0x7f62482c80, mVM = 0x7f7eb0d140, mCls = 0x1912
10-13 20:09:07.576   926  2950 D wifi    : array field set
,10-13 20:09:07.576   926  2950 I WifiNative-HAL: interface[0] = wlan0
10-13 20:09:07.579   926  5927 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547109743744
10-13 20:09:07.579   926  5927 D wifi    : waitForHalEvents called, vm = 0x7f7eb0d140, obj = 0x1912, env = 0x7f64be92c0
,10-13 20:09:07.636  5928  5928 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-13 20:09:07.656  5928  5928 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-13 20:09:07.664  5928  5928 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-13 20:09:07.664  5928  5928 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-13 20:09:07.680   926  2950 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-13 20:09:07.685  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:07.693   926  2950 D WifiConfigStore: Loading config and enabling all networks 
,10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:07.693  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:09:07.696  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:07.699  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-13 20:09:07.701  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:09:07.703   926  2950 D WifiConfigStore: loaded 0 passpoint configs
10-13 20:09:07.703   926  2950 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-13 20:09:07.703  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:07.704   926  2950 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-13 20:09:07.706   926  2950 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-13 20:09:07.707   926  2950 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-13 20:09:07.707   926  2950 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-13 20:09:07.707   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-13 20:09:07.707   926  2950 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
10-13 20:09:07.712   926  2950 D WifiNative-HAL: Setting external_sim to 1
10-13 20:09:07.712   926  2950 D wifi    : setting dfs flag to true, 0x7f6787b840
10-13 20:09:07.713   926  2950 D WifiStateMachine: Setting OUI to DA-A1-19
10-13 20:09:07.713   926  2950 D wifi    : setting scan oui 0x7f6787b840
10-13 20:09:07.713   926  2950 D WifiHAL : Sending mac address OUI
10-13 20:09:07.714  5009  5009 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-13 20:09:07.718   926  2950 E native  : do suspend false
10-13 20:09:07.725   926   926 D RttService: SCAN_AVAILABLE : 3
10-13 20:09:07.725   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-13 20:09:07.725   926  3059 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-13 20:09:07.726   926  2950 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-13 20:09:07.727   506   919 D CommandListener: Setting iface cfg
10-13 20:09:07.732   926  2949 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
10-13 20:09:07.732   926  2949 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-13 20:09:07.741   926  2949 D WifiNative-HAL: p2pGetDeviceAddress
10-13 20:09:07.741   926  2949 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
10-13 20:09:07.746   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=245604 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:07.970  5613  5672 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-13 20:09:07.976  5613  5672 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:09:07.979  5613  5659 D BluetoothAdapter: enable(): BT is already enabled..!
,10-13 20:09:07.980   926  3935 D WifiService: setWifiEnabled: true pid=5613, uid=10077
10-13 20:09:07.980   926  3935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-13 20:09:07.981  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-13 20:09:07.981  5613  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-13 20:09:07.981  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-13 20:09:07.981  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-13 20:09:07.981  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-13 20:09:07.981  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7e7a5cc removed from the list
,10-13 20:09:07.981  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-13 20:09:07.982  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9edf015 removed from the list
,10-13 20:09:07.982  5613  5659 D io.jxcore.node.ConnectivityMonitor: stop
10-13 20:09:07.982  5613  5659 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-13 20:09:07.982  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-13 20:09:07.984  5613  5659 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
10-13 20:09:07.986  5613  5659 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,10-13 20:09:07.988  5613  5659 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
10-13 20:09:07.990  5613  5659 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
10-13 20:09:07.993  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,10-13 20:09:07.994  5613  5659 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,10-13 20:09:07.995  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
10-13 20:09:07.996  5613  5659 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-13 20:09:07.996  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
10-13 20:09:07.999  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,10-13 20:09:08.000  5613  5659 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@fb427e5 Bundle[{}]
10-13 20:09:08.000  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
10-13 20:09:08.001  5613  5659 I io.jxcore.node.LifeCycleMonitor: start: OK
10-13 20:09:08.001  5613  5659 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-13 20:09:08.002  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,10-13 20:09:08.003  5613  5659 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-13 20:09:08.004  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
,10-13 20:09:08.004  5613  5659 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-13 20:09:08.005  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,10-13 20:09:08.005  5613  5659 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-13 20:09:08.006  5613  5659 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
10-13 20:09:08.006  5613  5659 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-13 20:09:08.008  5613  5659 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,10-13 20:09:08.010  5613  5659 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
10-13 20:09:08.011  5613  5659 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
10-13 20:09:08.012  5613  5659 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,10-13 20:09:08.013  5613  5659 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,10-13 20:09:08.014  5613  5659 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,10-13 20:09:08.016  5613  5659 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,10-13 20:09:08.018  5613  5659 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
10-13 20:09:08.019  5613  5659 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
10-13 20:09:08.020  5613  5659 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
10-13 20:09:08.021  5613  5659 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
10-13 20:09:08.021  5613  5659 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
10-13 20:09:08.021  5613  5659 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,10-13 20:09:08.022  5613  5659 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
10-13 20:09:08.022  5613  5659 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-13 20:09:08.022  5613  5659 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,10-13 20:09:08.022  5613  5659 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,10-13 20:09:08.023  5613  5659 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
10-13 20:09:08.024  5613  5659 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
10-13 20:09:08.025  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-13 20:09:08.025  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cf52b8 added. We now have 3 listener(s)
,10-13 20:09:08.027  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-13 20:09:08.027  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-13 20:09:08.027  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-13 20:09:08.027  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-13 20:09:08.027  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fca7891 added. We now have 3 listener(s)
10-13 20:09:08.027  5613  5659 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-13 20:09:08.028  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-13 20:09:08.031  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-13 20:09:08.034  5613  5659 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-13 20:09:08.036  5613  5659 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-13 20:09:08.036  5613  5659 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-13 20:09:08.038  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-13 20:09:08.040  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-13 20:09:08.040  5613  5659 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,10-13 20:09:08.041  5613  5659 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
10-13 20:09:08.041  5613  5659 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-13 20:09:08.041  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,10-13 20:09:08.041  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-13 20:09:08.041  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-13 20:09:08.042  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-13 20:09:08.042  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-13 20:09:08.043  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-13 20:09:08.043  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-13 20:09:08.043  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-13 20:09:08.044  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-13 20:09:08.044  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-13 20:09:08.044  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-13 20:09:08.044  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-13 20:09:08.044  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:09:08.044  5613  5930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-13 20:09:08.044  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-13 20:09:08.044  5613  5930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-13 20:09:08.049  5613  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-13 20:09:08.049  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-13 20:09:08.045  5898  5898 W Binder_4: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[35272]" dev="sockfs" ino=35272 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:09:08.045  5898  5898 W Binder_4: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[35272]" dev="sockfs" ino=35272 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:09:08.051  5613  5930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-13 20:09:08.053  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-13 20:09:08.054  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-13 20:09:08.054  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-13 20:09:08.056  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-13 20:09:08.056  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-13 20:09:08.056  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
10-13 20:09:08.056  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:09:08.056  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-13 20:09:08.056  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-13 20:09:08.056  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:09:08.057  5613  5659 D BluetoothAdapter: STATE_ON
,10-13 20:09:08.061  5861  5898 D BtGatt.GattService: registerClient() - UUID=7f1b7c0c-8c78-4c11-af72-f7bb332b1b4d
,10-13 20:09:08.062  5861  5877 D BtGatt.GattService: onClientRegistered() - UUID=7f1b7c0c-8c78-4c11-af72-f7bb332b1b4d, clientIf=5
,10-13 20:09:08.062  5613  5624 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-13 20:09:08.064  5861  5879 D BtGatt.AdvertiseManager: message : 0
,10-13 20:09:08.066  5861  5879 D BtGatt.AdvertiseManager: starting multi advertising
,10-13 20:09:08.075  5861  5877 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-13 20:09:08.081  5861  5877 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-13 20:09:08.082  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-13 20:09:08.082  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-13 20:09:08.082  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-13 20:09:08.082  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-13 20:09:08.082  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-13 20:09:08.083  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-13 20:09:08.084  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-13 20:09:08.085  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-13 20:09:08.085  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-13 20:09:08.085  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-13 20:09:08.085  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-13 20:09:08.085  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:09:08.085  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-13 20:09:08.085  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-13 20:09:08.085  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-13 20:09:08.085  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-13 20:09:08.087  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-13 20:09:08.087  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-13 20:09:08.588  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-13 20:09:08.589  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,10-13 20:09:08.589  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-13 20:09:10.905  5928  5928 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:10.911  5928  5928 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:10.917  5928  5928 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:10.923  5928  5928 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-13 20:09:10.979   926  2950 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-13 20:09:10.980   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-13 20:09:10.980   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-13 20:09:10.993   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-13 20:09:11.024   926  2950 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-13 20:09:11.026  5928  5928 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-13 20:09:11.457  5928  5928 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-13 20:09:11.492  5928  5928 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-13 20:09:11.493  5928  5928 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-13 20:09:11.501   926  2950 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-13 20:09:11.502   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-13 20:09:11.502   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-13 20:09:11.526   926  2950 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-13 20:09:11.539   506   919 D CommandListener: Setting iface cfg
,10-13 20:09:11.545   926  2950 D WifiStateMachine: Start Dhcp Watchdog 3
,10-13 20:09:11.557   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-13 20:09:11.557   926  2952 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-13 20:09:11.551   926  5935 D DhcpClient: Receive thread started
10-13 20:09:11.566   926  2952 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-13 20:09:11.587  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-13 20:09:11.587  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-13 20:09:11.587  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-13 20:09:11.587  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-13 20:09:11.587  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-13 20:09:11.588  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-13 20:09:11.588  5613  5930 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-13 20:09:11.588  5613  5930 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-13 20:09:11.588  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-13 20:09:11.588  5613  5930 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-13 20:09:11.588  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-13 20:09:11.588  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-13 20:09:11.588  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-13 20:09:11.588  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-13 20:09:11.588  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-13 20:09:11.588  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-13 20:09:11.588  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-13 20:09:11.588  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-13 20:09:11.588  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-13 20:09:11.589  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:09:11.590  5613  5659 D BluetoothLeScanner: could not find callback wrapper
10-13 20:09:11.590  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-13 20:09:11.590  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-13 20:09:11.591  5861  5879 D BtGatt.AdvertiseManager: message : 1
,10-13 20:09:11.592  5861  5879 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-13 20:09:11.600  5861  5877 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-13 20:09:11.600  5861  5877 D BtGatt.GattService: Client app is not null!
,10-13 20:09:11.601  5861  5872 D BtGatt.GattService: unregisterClient() - clientIf=5
10-13 20:09:11.602  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-13 20:09:11.602  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-13 20:09:11.602  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-13 20:09:11.603  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-13 20:09:11.603  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:09:11.603  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-13 20:09:11.603  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-13 20:09:11.603  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,10-13 20:09:11.603  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-13 20:09:11.606  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-13 20:09:11.606  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-13 20:09:11.606  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-13 20:09:11.607  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-13 20:09:11.608  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-13 20:09:11.609  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-13 20:09:11.609  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-13 20:09:11.609  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:09:11.609  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-13 20:09:11.612  5613  5659 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,10-13 20:09:11.612  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-13 20:09:11.613  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-13 20:09:11.613  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-13 20:09:11.613  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-13 20:09:11.613  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:09:11.613  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-13 20:09:11.617  5613  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-13 20:09:11.617  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-13 20:09:11.621  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-13 20:09:11.622  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-13 20:09:11.622  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-13 20:09:11.627  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-13 20:09:11.627  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-13 20:09:11.627  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-13 20:09:11.628  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-13 20:09:11.628  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-13 20:09:11.629  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:09:11.632  5861  5902 D BtGatt.GattService: registerClient() - UUID=afd9388b-280e-41ab-bd39-47f264e33726
10-13 20:09:11.632  5861  5877 D BtGatt.GattService: onClientRegistered() - UUID=afd9388b-280e-41ab-bd39-47f264e33726, clientIf=5
,10-13 20:09:11.633  5613  5623 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-13 20:09:11.634  5861  5898 D BtGatt.GattService: start scan with filters
10-13 20:09:11.638  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-13 20:09:11.638  5861  5880 D BtGatt.ScanManager: handling starting scan
,10-13 20:09:11.638  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-13 20:09:11.639  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:09:11.639  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-13 20:09:11.639  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-13 20:09:11.639  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-13 20:09:11.639  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,10-13 20:09:11.640  5861  5880 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@d35e9ae
,10-13 20:09:11.641  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-13 20:09:11.642  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-13 20:09:11.642  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-13 20:09:11.643  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-13 20:09:11.646  5861  5877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-13 20:09:11.646  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-13 20:09:11.647  5861  5880 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-13 20:09:11.647   926  2950 E native  : do suspend false
,10-13 20:09:11.653  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-13 20:09:11.653  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:11.653  5861  5880 D BtGatt.ScanManager: Starting BLE batch scan
,10-13 20:09:11.654  5861  5880 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-13 20:09:11.657   926  5934 D DhcpClient: Broadcasting DHCPDISCOVER
,10-13 20:09:11.664  5861  5877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-13 20:09:11.664  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-13 20:09:11.669  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-13 20:09:11.670  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:11.670   926  5935 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172792, domain null
10-13 20:09:11.670   926  5934 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172792 seconds
,10-13 20:09:11.671   926  5934 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-13 20:09:11.684   926  5935 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-13 20:09:11.684   926  5934 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-13 20:09:11.685   506   919 D CommandListener: Setting iface cfg
10-13 20:09:11.687   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-13 20:09:11.689   926  5934 D DhcpClient: Scheduling renewal in 86399s
,10-13 20:09:11.694   926  2950 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-13 20:09:11.694   926  2950 D WifiConfigStore: No blacklist allowed without epno enabled
10-13 20:09:11.695   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-13 20:09:11.695   926  2952 D ConnectivityService: Adding iface wlan0 to network 102
,10-13 20:09:11.698   926  2950 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-13 20:09:11.726   926  2952 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-13 20:09:11.726   926  2952 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,10-13 20:09:11.729   926  2952 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-13 20:09:11.731   926  2952 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-13 20:09:11.732   926  2952 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-13 20:09:11.738   926  2952 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-13 20:09:11.742   926  2952 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-13 20:09:11.742   926  2952 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-13 20:09:11.743   926  2952 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-13 20:09:11.743   926  2950 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-13 20:09:11.743   926  2952 D ConnectivityService:    accepting network in place of null
10-13 20:09:11.743   926  2950 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-13 20:09:11.743   926  2952 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -48]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-13 20:09:11.762   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-13 20:09:11.781   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-13 20:09:11.785   926  2952 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-13 20:09:11.785   926  2952 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-13 20:09:11.785  3740  3883 W QCNEJ   : |CORE| network available: 102
10-13 20:09:11.786   926  2952 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-13 20:09:11.787  3740  3883 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-13 20:09:11.787   926  2952 D ConnectivityService: handlePromptUnvalidated 101
10-13 20:09:11.788  3740  3883 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-13 20:09:11.788  3740  3883 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-13 20:09:11.789   926   943 D Tethering: MasterInitialState.processMessage what=3
,10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:11.797  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:11.799  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:11.802  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:11.804  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-13 20:09:11.808  5613  5613 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-13 20:09:11.810  5613  5613 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-13 20:09:11.812  5034  5059 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-13 20:09:11.812  5034  5059 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-13 20:09:11.812  5034  5059 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-13 20:09:11.812  5034  5059 E SarControlService: no key has been found,reset the power
10-13 20:09:11.813  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-13 20:09:11.813  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-13 20:09:11.813  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-13 20:09:11.813  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-13 20:09:11.813  5061  5061 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-13 20:09:11.815  5034  5074 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-13 20:09:11.815  5034  5074 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-13 20:09:11.815  5034  5074 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-13 20:09:11.815  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-13 20:09:11.815  5061  5061 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-13 20:09:11.817  3856  3856 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-13 20:09:11.821  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000f003000000000000ffffffff]
,10-13 20:09:11.821  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-13 20:09:11.821  5061  5079 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-13 20:09:11.821  5061  5079 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@b5315f1 HexData = [00000000f103000000000000ffffffff]
10-13 20:09:11.821  5061  5079 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-13 20:09:11.821  5061  5079 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
,10-13 20:09:11.822  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:09:11.822  5034  5044 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-13 20:09:11.823  4888  4888 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-13 20:09:11.825  3856  3856 D SystemUpdateService: onCreate
10-13 20:09:11.825  5061  5061 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-13 20:09:11.825  5034  5045 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-13 20:09:11.829  3856  3856 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-13 20:09:11.839  3856  3856 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-13 20:09:11.845  3856  5400 I iu.UploadsManager: num queued entries: 0
,10-13 20:09:11.845  3856  5400 I iu.UploadsManager: num updated entries: 0
10-13 20:09:11.846  3856  5400 I iu.SyncManager: NEXT; no task
10-13 20:09:11.847  3856  5947 I SystemUpdateService: active receiver: enabled
,10-13 20:09:11.848  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-13 20:09:11.850  3856  3856 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-13 20:09:11.850   926  5933 D NetlinkSocketObserver: NeighborEvent{elapsedMs=249708, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
10-13 20:09:11.851  5404  5404 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-13 20:09:11.854  5404  5404 D SprintDMHelper: simOperator: 
10-13 20:09:11.854  5404  5404 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-13 20:09:11.880  3856  5947 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-13 20:09:11.890  3856  5947 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-13 20:09:11.890  3856  5947 I SystemUpdateService: now status is 0 (complete)
10-13 20:09:11.890  3856  5947 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-13 20:09:11.890  3856  5947 I SystemUpdateService: file has been verified
10-13 20:09:11.891  3856  5947 I SystemUpdateService: OTA package size = 21989297
,10-13 20:09:11.896  3856  5947 I SystemUpdateService: showing system update notification
,10-13 20:09:11.905  3856  3856 D SystemUpdateService: onDestroy
,10-13 20:09:12.143  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-13 20:09:12.143  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-13 20:09:12.143  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-13 20:09:12.174  5861  5861 D BtGatt.ScanManager: awakened up at time 250032
,10-13 20:09:12.177  5861  5880 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-13 20:09:12.210  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,10-13 20:09:12.211  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:12.211  5861  5877 D BtGatt.GattService: current time is 250069703966
10-13 20:09:12.212  5861  5877 D BtGatt.GattService: Batch record : [59, 52, 125, -29, 57, 84, 1, -128, -46, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, 84, -19, 40, -41, -104, 125, 1, -128, -53, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, -46, -4, -117, 6, 105, -37, 1, -128, -77, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -76, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-13 20:09:12.214  5861  5877 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-13 20:09:12.215  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
10-13 20:09:12.216  5861  5877 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-13 20:09:12.216  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-13 20:09:12.216  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-13 20:09:12.220  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults
10-13 20:09:12.221  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-13 20:09:12.221  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=54:39:E3:7D:34:3B, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-46, mTimestampNanos=249970797612}
,10-13 20:09:12.223  5613  5613 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null]
,10-13 20:09:12.224  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
10-13 20:09:12.224  5613  5613 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
10-13 20:09:12.225  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-13 20:09:12.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=250020797612}
10-13 20:09:12.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-13 20:09:12.226  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-77, mTimestampNanos=249870797612}
10-13 20:09:12.227  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-13 20:09:12.227  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-79, mTimestampNanos=249770797612}
10-13 20:09:12.227  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-13 20:09:12.227  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=7D:98:D7:28:ED:54, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=250070797612}
10-13 20:09:12.227  5613  5613 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-13 20:09:12.227  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6]
10-13 20:09:12.228  5613  5613 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: Want to call onPeerAdded. Listeners size = 1
10-13 20:09:12.228  5613  5613 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6], Bluetooth address: A8:81:95:E9:5F:6F, device name: '', device address: ''
10-13 20:09:12.229  5613  5613 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6], Bluetooth address: 44:78:3E:94:4A:3E, device name: '', device address: ''
,10-13 20:09:12.287   926  5932 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,10-13 20:09:12.390  5009  5951 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-13 20:09:12.712   926  5932 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 14 Oct 2016 00:09:12 GMT], X-Android-Received-Millis=[1476403752710], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476403752498]}
,10-13 20:09:12.713   926  2952 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-13 20:09:12.714   926  2952 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
10-13 20:09:12.714   926  2952 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-13 20:09:12.718   926  2952 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-13 20:09:12.785   926  2952 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,10-13 20:09:13.270  5861  5861 D BtGatt.ScanManager: awakened up at time 251128
,10-13 20:09:13.272  5861  5880 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-13 20:09:13.303  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-13 20:09:13.303  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:13.303  5861  5877 D BtGatt.GattService: current time is 251161847350
10-13 20:09:13.303  5861  5877 D BtGatt.GattService: Batch record : [59, 52, 125, -29, 57, 84, 1, -128, -47, 2, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 84, -19, 40, -41, -104, 125, 1, -128, -53, 1, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, 35, 97, 126, -92, 22, -56, 1, -128, -79, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -77, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -76, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -80, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-13 20:09:13.304  5861  5877 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-13 20:09:13.304  5861  5877 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-13 20:09:13.304  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
10-13 20:09:13.304  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
10-13 20:09:13.305  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-13 20:09:13.305  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-13 20:09:13.306  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults
10-13 20:09:13.306  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-13 20:09:13.306  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=FB:F2:70:61:22:51, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-80, mTimestampNanos=251062264797}
10-13 20:09:13.307  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-13 20:09:13.307  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-79, mTimestampNanos=250712264797}
10-13 20:09:13.307  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-13 20:09:13.307  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=7D:98:D7:28:ED:54, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-53, mTimestampNanos=251112264797}
10-13 20:09:13.307  5613  5613 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, 68, 120, 62, -108, 74, 62]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-13 20:09:13.308  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> 44:78:3E:94:4A:3E 6]
10-13 20:09:13.308  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-13 20:09:13.308  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=F4:45:54:B3:86:47, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-76, mTimestampNanos=250962264797}
10-13 20:09:13.309  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-13 20:09:13.309  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-77, mTimestampNanos=250812264797}
10-13 20:09:13.309  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-13 20:09:13.309  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=54:39:E3:7D:34:3B, mScanRecord=ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null], mRssi=-47, mTimestampNanos=251062264797}
10-13 20:09:13.310  5613  5613 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onPeerDiscovered: scan record ScanRecord [mAdvertiseFlags=-1, mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={00004ad1-0000-1000-8000-00805f9b34fb=[6, -88, -127, -107, -23, 95, 111]}, mTxPowerLevel=-2147483648, mDeviceName=null]
10-13 20:09:13.310  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onPeerDiscovered: [<no peer name> A8:81:95:E9:5F:6F 6]
10-13 20:09:13.310  5613  5613 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> 44:78:3E:94:4A:3E 6], device name: '', device address: ''
10-13 20:09:13.310  5613  5613 I io.jxcore.node.ConnectionHelper: onPeerUpdated: [<no peer name> A8:81:95:E9:5F:6F 6], device name: '', device address: ''
,10-13 20:09:14.578   926  2952 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-13 20:09:14.647  5613  5659 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
10-13 20:09:14.648  5613  5659 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
10-13 20:09:14.648  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-13 20:09:14.649  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-13 20:09:14.649  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-13 20:09:14.651  5613  5659 D BluetoothAdapter: STATE_ON
,10-13 20:09:14.653  5861  5889 D BtGatt.GattService: stopScan() - queue size =1
,10-13 20:09:14.656  5861  5902 D BtGatt.GattService: unregisterClient() - clientIf=5
10-13 20:09:14.658  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-13 20:09:14.658  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-13 20:09:14.658  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-13 20:09:14.658  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-13 20:09:14.659  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-13 20:09:14.659  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-13 20:09:14.659  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-13 20:09:14.659  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-13 20:09:14.666  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:09:14.670  5861  5861 D BtGatt.ScanManager: awakened up at time 252529
10-13 20:09:14.670  5861  5898 D BtGatt.GattService: registerClient() - UUID=d5637ba4-a793-4c9e-8d66-01607810c97c
10-13 20:09:14.671  5861  5877 D BtGatt.GattService: onClientRegistered() - UUID=d5637ba4-a793-4c9e-8d66-01607810c97c, clientIf=5
10-13 20:09:14.672  5613  5624 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-13 20:09:14.672  5861  5889 D BtGatt.GattService: start scan with filters
,10-13 20:09:14.675  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-13 20:09:14.675  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-13 20:09:14.675  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:14.675  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-13 20:09:14.675  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:09:14.679  5902  5902 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32244]" dev="sockfs" ino=32244 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:09:14.676  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-13 20:09:14.676  5861  5880 D BtGatt.ScanManager: stopping BLe Batch
,10-13 20:09:14.676  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-13 20:09:14.676  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-13 20:09:14.676  5613  5659 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-13 20:09:14.676  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-13 20:09:14.676  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-13 20:09:14.679  5902  5902 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32244]" dev="sockfs" ino=32244 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-13 20:09:14.677  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-13 20:09:14.678  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-13 20:09:14.678  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-13 20:09:14.678  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-13 20:09:14.678  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-13 20:09:14.679  5613  5959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-13 20:09:14.679  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-13 20:09:14.679  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-13 20:09:14.680  5613  5959 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-13 20:09:14.683  5613  5959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-13 20:09:14.683  5613  5659 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-13 20:09:14.686  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-13 20:09:14.686  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:14.686  5861  5880 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-13 20:09:14.690  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,10-13 20:09:14.690  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-13 20:09:14.690  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-13 20:09:14.690  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
10-13 20:09:14.690  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:09:14.690  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-13 20:09:14.690  5613  5659 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-13 20:09:14.691  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-13 20:09:14.691  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-13 20:09:14.691  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:14.692  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:09:14.692  5861  5880 D BtGatt.ScanManager: handling starting scan
,10-13 20:09:14.696  5861  5871 D BtGatt.GattService: registerClient() - UUID=00666c0a-d440-49d2-9744-a31bd4e050d5
,10-13 20:09:14.697  5861  5877 D BtGatt.GattService: onClientRegistered() - UUID=00666c0a-d440-49d2-9744-a31bd4e050d5, clientIf=6
10-13 20:09:14.697  5613  5623 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,10-13 20:09:14.698  5861  5879 D BtGatt.AdvertiseManager: message : 0
10-13 20:09:14.698  5861  5877 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-13 20:09:14.698  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:14.699  5861  5880 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-13 20:09:14.702  5861  5879 D BtGatt.AdvertiseManager: starting multi advertising
,10-13 20:09:14.709  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-13 20:09:14.709  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:14.710  5861  5880 D BtGatt.ScanManager: Starting BLE batch scan
10-13 20:09:14.710  5861  5880 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-13 20:09:14.713  5861  5877 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-13 20:09:14.721  5861  5877 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-13 20:09:14.721  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-13 20:09:14.725  5861  5877 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,10-13 20:09:14.725  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-13 20:09:14.725  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-13 20:09:14.725  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-13 20:09:14.725  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-13 20:09:14.725  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,10-13 20:09:14.726  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-13 20:09:14.726  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser, adv = true, disc = true
10-13 20:09:14.726  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-13 20:09:14.727  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-13 20:09:14.729  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-13 20:09:14.729  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:14.729  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-13 20:09:14.729  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-13 20:09:14.729  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-13 20:09:14.729  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-13 20:09:14.729  5613  5613 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-13 20:09:14.729  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:09:14.729  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
10-13 20:09:14.729  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-13 20:09:14.730  5613  5613 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
10-13 20:09:14.730  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,10-13 20:09:14.732  5613  5613 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
10-13 20:09:14.732  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-13 20:09:14.744   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 17 -> obsolete
,10-13 20:09:15.233  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-13 20:09:15.233  5613  5613 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-13 20:09:15.233  5613  5613 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-13 20:09:15.672   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:16.673   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:17.674   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:17.732  5613  5659 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-13 20:09:17.733  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-13 20:09:17.733  5613  5659 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-13 20:09:17.733  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-13 20:09:17.733  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-13 20:09:17.734  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-13 20:09:17.734  5613  5959 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-13 20:09:17.734  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-13 20:09:17.734  5613  5959 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-13 20:09:17.734  5613  5659 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-13 20:09:17.734  5613  5959 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-13 20:09:17.735  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-13 20:09:17.735  5613  5613 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-13 20:09:17.735  5613  5659 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cf52b8 removed from the list
10-13 20:09:17.735  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-13 20:09:17.735  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-13 20:09:17.735  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-13 20:09:17.735  5613  5613 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-13 20:09:17.735  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-13 20:09:17.735  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-13 20:09:17.736  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-13 20:09:17.736  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-13 20:09:17.738  5613  5659 D BluetoothAdapter: STATE_ON
10-13 20:09:17.739  5861  5871 D BtGatt.GattService: stopScan() - queue size =1
10-13 20:09:17.741  5861  5902 D BtGatt.GattService: unregisterClient() - clientIf=5
10-13 20:09:17.742  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-13 20:09:17.743  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-13 20:09:17.743  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-13 20:09:17.743  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:09:17.743  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-13 20:09:17.743  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-13 20:09:17.744  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
10-13 20:09:17.744  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
10-13 20:09:17.749  5861  5861 D BtGatt.ScanManager: awakened up at time 255607
10-13 20:09:17.755  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-13 20:09:17.755  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-13 20:09:17.756  5861  5879 D BtGatt.AdvertiseManager: message : 1
10-13 20:09:17.756  5861  5879 D BtGatt.AdvertiseManager: stop advertise for client 6
10-13 20:09:17.757  5861  5877 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-13 20:09:17.757  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:17.757  5861  5880 D BtGatt.ScanManager: stopping BLe Batch
,10-13 20:09:17.764  5861  5877 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,10-13 20:09:17.764  5861  5877 D BtGatt.GattService: Client app is not null!
,10-13 20:09:17.765  5861  5902 D BtGatt.GattService: unregisterClient() - clientIf=6
10-13 20:09:17.765  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-13 20:09:17.765  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-13 20:09:17.766  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-13 20:09:17.766  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-13 20:09:17.766  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-13 20:09:17.766  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-13 20:09:17.766  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-13 20:09:17.766  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-13 20:09:17.766  5613  5659 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-13 20:09:17.767  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-13 20:09:17.767  5613  5659 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-13 20:09:17.767  5613  5659 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-13 20:09:17.768  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-13 20:09:17.768  5613  5659 I org.thaliproject.p2p.btconnectorlib.utils.PeerModel: clear
10-13 20:09:17.769  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:09:17.769  5613  5659 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fca7891 removed from the list
10-13 20:09:17.769  5613  5659 D io.jxcore.node.ConnectivityMonitor: stop
10-13 20:09:17.769  5613  5613 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-13 20:09:17.769  5613  5659 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-13 20:09:17.769  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
10-13 20:09:17.769  5613  5613 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-13 20:09:17.771  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
10-13 20:09:17.772  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-13 20:09:17.772  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-13 20:09:17.772  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-13 20:09:17.772  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-13 20:09:17.772  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-13 20:09:17.772  5613  5659 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-13 20:09:17.773  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
10-13 20:09:17.775  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
10-13 20:09:17.775  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
10-13 20:09:17.776  5861  5877 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-13 20:09:17.776  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:17.776  5861  5880 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-13 20:09:17.776  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
10-13 20:09:17.777  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-13 20:09:17.777  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
10-13 20:09:17.778  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
10-13 20:09:17.779  5613  5659 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-13 20:09:17.795  5861  5877 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-13 20:09:17.795  5861  5877 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-13 20:09:17.795  5861  5877 D BtGatt.GattService: current time is 255653813373
10-13 20:09:17.795  5861  5877 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -79, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -80, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -95, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -81, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -92, 43, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
10-13 20:09:17.796  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-13 20:09:17.796  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-13 20:09:17.796  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-13 20:09:17.796  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-13 20:09:17.796  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-13 20:09:17.796  5861  5877 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,10-13 20:09:18.271  5613  5613 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-13 20:09:18.675   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:19.676   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:19.748   926  2952 D ConnectivityService: handlePromptUnvalidated 102
,10-13 20:09:19.783  5613  5659 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-13 20:09:19.940  5613  5961 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-13 20:09:19.940  5613  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-13 20:09:20.677   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-13 20:09:20.767  5613  5961 W !!      : call onHalfStreamCopied
,10-13 20:09:20.767  5613  5961 I testCopyDataAndClose: closing input stream
,10-13 20:09:21.561  5613  5961 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-13 20:09:21.561  5613  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-13 20:09:21.561  5613  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-13 20:09:21.561  5613  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-13 20:09:21.561  5613  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-13 20:09:21.562  5613  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-13 20:09:21.562  5613  5961 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-13 20:09:21.562  5613  5961 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-13 20:09:21.562  5613  5961 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-13 20:09:21.562  5613  5961 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-13 20:09:21.562  5613  5961 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-13 20:09:22.742   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 16, 17 -> obsolete
,10-13 20:09:23.706   926  2950 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 17 -> obsolete
,10-13 20:09:25.299  5613  5659 I StreamCopyingThreadTest: Starting test: testRun
,10-13 20:09:25.305  5613  5962 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
10-13 20:09:25.305  5613  5962 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-13 20:09:30.314  5613  5963 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,10-13 20:09:30.316  5613  5659 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-13 20:09:30.427  5613  5964 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-13 20:09:30.427  5613  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-13 20:09:32.134  5613  5964 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-13 20:09:32.134  5613  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-13 20:09:32.135  5613  5964 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-13 20:09:35.678   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:35.884  5613  5659 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-13 20:09:35.887  5613  5965 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-13 20:09:35.887  5613  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-13 20:09:35.887  5613  5965 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
10-13 20:09:35.887  5613  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-13 20:09:35.887  5613  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-13 20:09:35.887  5613  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-13 20:09:35.887  5613  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-13 20:09:35.888  5613  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-13 20:09:35.888  5613  5965 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-13 20:09:35.888  5613  5965 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-13 20:09:35.888  5613  5965 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-13 20:09:35.888  5613  5965 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-13 20:09:35.888  5613  5965 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-13 20:09:35.890  5613  5659 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-13 20:09:35.890  5613  5659 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-13 20:09:35.891  5613  5659 I StreamCopyingThreadTest: Starting test: testRunWithException
10-13 20:09:35.893  5613  5966 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-13 20:09:35.893  5613  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-13 20:09:35.894  5613  5966 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
10-13 20:09:35.894  5613  5966 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-13 20:09:35.894  5613  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-13 20:09:35.894  5613  5966 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-13 20:09:35.894  5613  5966 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-13 20:09:35.894  5613  5966 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-13 20:09:35.896  5613  5659 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
10-13 20:09:35.896  5613  5659 E com.test.thalitest.ThaliTestRunner: 
10-13 20:09:35.896  5613  5659 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-13 20:09:35.896  5613  5659 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.,junit.runners.ParentRunner.run(ParentRunner.java:363)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
10-13 2,0:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-13 20:09:35.897  5613  5659 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runne,rs.ParentRunner.runChildren(ParentRunner.java:288)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:35.898  5613  5659 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-13 20:09:35.900  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG UnitTest_app: 'Running unit tests'
10-13 20:09:35.900  5613  5659 I jxcore-log: 
10-13 20:09:35.900  5613  5659 I jxcore-log: *Native tests were executed*
10-13 20:09:35.900  5613  5659 I jxcore-log: 
10-13 20:09:35.901  5613  5659 I jxcore-log: Total number of executed tests:  82
10-13 20:09:35.901  5613  5659 I jxcore-log: 
10-13 20:09:35.901  5613  5659 I jxcore-log: Number of passed tests:  80
10-13 20:09:35.901  5613  5659 I jxcore-log: 
10-13 20:09:35.901  5613  5659 I jxcore-log: Number of failed tests:  2
10-13 20:09:35.901  5613  5659 I jxcore-log: 
10-13 20:09:35.901  5613  5659 I jxcore-log: Number of ignored tests:  0
10-13 20:09:35.901  5613  5659 I jxcore-log: 
10-13 20:09:35.9,01  5613  5659 I jxcore-log: Total duration:  46020
10-13 20:09:35.901  5613  5659 I jxcore-log: 
10-13 20:09:35.901  5613  5659 I jxcore-log: Failed to execute UT.
10-13 20:09:35.901  5613  5659 I jxcore-log: 
10-13 20:09:35.902  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-13 20:09:35.902  5613  5659 I jxcore-log: 
10-13 20:09:35.903  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-13 20:09:35.903  5613  5659 I jxcore-log: 
10-13 20:09:35.906  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.906  5613  5659 I jxcore-log: 
10-13 20:09:35.907  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.907  5613  5659 I jxcore-log: 
10-13 20:09:35.907  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.907  5613  5659 I jxcore-log: 
10-13 20:09:35.908  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-13 20:09:35.908  5613  5659 I jxcore-log: 
10-13 20:09:35.909  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-13 20:09:35.909  5613  5659 I jxcore-log: 
10-13 20:09:35.909  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-13 20:09:35.909  5613  5659 I jxcore-log: 
10-13 20:09:35.910  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-13 20:09:35.910  5613  5659 I jxcore-log: 
10-13 20:09:35.910  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.910  5613  5659 I jxcore-log: 
10-13 20:09:35.910  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-13 20:09:35.910  5613  5659 I jxcore-log: 
10-13 20:09:35.910  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-13 20:09:35.910  5613  5659 I jxcore-log: 
10-13 20:09:35.910  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-13 20:09:35.910  5613  5659 I jxcore-log: 
10-13 20:09:35.911  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-13 20:09:35.911  5613  5659 I jxcore-log: 
10-13 20:09:35.911  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.911  5613  5659 I jxcore-log: 
10-13 20:09:35.911  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.911  5613  5659 I jxcore-log: 
10-13 20:09:35.912  5613  56,59 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.912  5613  5659 I jxcore-log: 
10-13 20:09:35.912  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.912  5613  5659 I jxcore-log: 
10-13 20:09:35.912  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.912  5613  5659 I jxcore-log: 
10-13 20:09:35.912  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.912  5613  5659 I jxcore-log: 
10-13 20:09:35.913  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.913  5613  5659 I jxcore-log: 
10-13 20:09:35.913  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.913  5613  5659 I jxcore-log: 
10-13 20:09:35.913  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.913  5613  5659 I jxcore-log: 
10-13 20:09:35.913  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.913  5613  5659 I jxcore-log: 
10-13 20:09:35.914  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.914  5613  5659 I jxcore-log: 
10-13 20:09:35.914  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.914  5613  5659 I jxcore-log: 
10-13 20:09:35.914  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.914  5613  5659 I jxcore-log: 
10-13 20:09:35.914  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.914  5613  5659 I jxcore-log: 
10-13 20:09:35.916  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.916  5613  5659 I jxcore-log: 
10-13 20:09:35.916  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.916  5613  5659 I jxcore-log: 
10-13 20:09:35.916  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.916  5613  5659 I jxcore-log: 
10-13 20:09:35.916  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliM,obileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.916  5613  5659 I jxcore-log: 
10-13 20:09:35.917  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.917  5613  5659 I jxcore-log: 
10-13 20:09:35.917  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-13 20:09:35.917  5613  5659 I jxcore-log: 
10-13 20:09:35.917  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-13 20:09:35.917  5613  5659 I jxcore-log: 
10-13 20:09:35.917  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-13 20:09:35.917  5613  5659 I jxcore-log: 
10-13 20:09:35.918  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.918  5613  5659 I jxcore-log: 
10-13 20:09:35.918  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.918  5613  5659 I jxcore-log: 
10-13 20:09:35.918  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.918  5613  5659 I jxcore-log: 
10-13 20:09:35.918  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-13 20:09:35.918  5613  5659 I jxcore-log: 
10-13 20:09:35.919  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-13 20:09:35.919  5613  5659 I jxcore-log: 
,10-13 20:09:35.919  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.919  5613  5659 I jxcore-log: 
10-13 20:09:35.919  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.919  5613  5659 I jxcore-log: 
10-13 20:09:35.919  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-13 20:09:35.919  5613  5659 I jxcore-log: 
10-13 20:09:35.919  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-13 20:09:35.919  5613  5659 I jxcore-log: 
10-13 20:09:35.920  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-13 20:09:35.920  5613  5659 I jxcore-log: 
10-13 20:09:35.920  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-13 20:09:35.920  5613  5659 I jxcore-log: 
10-13 20:09:35.920  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-13 20:09:35.920  5613  5659 I jxcore-log: 
,10-13 20:09:35.920  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
10-13 20:09:35.920  5613  5659 I jxcore-log: 
10-13 20:09:35.921  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
10-13 20:09:35.921  5613  5659 I jxcore-log: 
10-13 20:09:35.921  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-13 20:09:35.921  5613  5659 I jxcore-log: 
10-13 20:09:35.926  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-13 20:09:35.926  5613  5659 I jxcore-log: 
10-13 20:09:35.926  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - WARN testUtils: 'myNameCallback not set!'
10-13 20:09:35.926  5613  5659 I jxcore-log: 
10-13 20:09:35.926  5613  5613 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-13 20:09:35.928  5613  5659 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-13 20:09:35.928  5613  5659 I jxcore-log: 2016-10-14 00:09:35 - DEBUG UnitTest_app: 'Running for NATIVE network type'
10-13 20:09:35.928  5613  5659 I jxcore-log: 
,10-13 20:09:36.679   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:37.681   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:37.944  5613  5659 I jxcore-log: 2016-10-14 00:09:37 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-13 20:09:37.944  5613  5659 I jxcore-log: 
,10-13 20:09:38.271  5613  5659 I jxcore-log: 2016-10-14 00:09:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-13 20:09:38.271  5613  5659 I jxcore-log: 
,10-13 20:09:38.286  5613  5659 I jxcore-log: 2016-10-14 00:09:38 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-13 20:09:38.286  5613  5659 I jxcore-log: 
,10-13 20:09:38.682   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:39.362  5613  5659 I jxcore-log: 2016-10-14 00:09:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-13 20:09:39.362  5613  5659 I jxcore-log: 
,10-13 20:09:39.508  5613  5659 I jxcore-log: 2016-10-14 00:09:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-13 20:09:39.508  5613  5659 I jxcore-log: 
,10-13 20:09:39.513  5613  5659 I jxcore-log: 2016-10-14 00:09:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-13 20:09:39.513  5613  5659 I jxcore-log: 
,10-13 20:09:39.518  5613  5659 I jxcore-log: 2016-10-14 00:09:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-13 20:09:39.518  5613  5659 I jxcore-log: 
,10-13 20:09:39.683   534   534 I ServiceManager: Waiting for service AtCmdFwd...
,10-13 20:09:39.998  5613  5659 I jxcore-log: 2016-10-14 00:09:39 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-13 20:09:39.998  5613  5659 I jxcore-log: 
,10-13 20:09:40.040  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-13 20:09:40.040  5613  5659 I jxcore-log: 
,10-13 20:09:40.052  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-13 20:09:40.052  5613  5659 I jxcore-log: 
,10-13 20:09:40.057  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-13 20:09:40.057  5613  5659 I jxcore-log: 
,10-13 20:09:40.330  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-13 20:09:40.330  5613  5659 I jxcore-log: 
,10-13 20:09:40.453  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-13 20:09:40.453  5613  5659 I jxcore-log: 
,10-13 20:09:40.681  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-13 20:09:40.681  5613  5659 I jxcore-log: 
,10-13 20:09:40.684   534   534 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-13 20:09:40.847  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
10-13 20:09:40.847  5613  5659 I jxcore-log: 
,10-13 20:09:40.853  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-13 20:09:40.853  5613  5659 I jxcore-log: 
,10-13 20:09:40.858  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-13 20:09:40.858  5613  5659 I jxcore-log: 
,10-13 20:09:40.865  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
10-13 20:09:40.865  5613  5659 I jxcore-log: 
,10-13 20:09:40.878  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-13 20:09:40.878  5613  5659 I jxcore-log: 
,10-13 20:09:40.883  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-13 20:09:40.883  5613  5659 I jxcore-log: 
,10-13 20:09:40.909  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-13 20:09:40.909  5613  5659 I jxcore-log: 
,10-13 20:09:40.944  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-13 20:09:40.944  5613  5659 I jxcore-log: 
,10-13 20:09:40.951  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-13 20:09:40.951  5613  5659 I jxcore-log: 
,10-13 20:09:40.958  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-13 20:09:40.958  5613  5659 I jxcore-log: 
,10-13 20:09:40.973  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-13 20:09:40.973  5613  5659 I jxcore-log: 
,10-13 20:09:40.977  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-13 20:09:40.977  5613  5659 I jxcore-log: 
,10-13 20:09:40.983  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-13 20:09:40.983  5613  5659 I jxcore-log: 
,10-13 20:09:40.989  5613  5659 I jxcore-log: 2016-10-14 00:09:40 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-13 20:09:40.989  5613  5659 I jxcore-log: 
,10-13 20:09:41.001  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-13 20:09:41.001  5613  5659 I jxcore-log: 
,10-13 20:09:41.023  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-13 20:09:41.023  5613  5659 I jxcore-log: 
,10-13 20:09:41.034  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-13 20:09:41.034  5613  5659 I jxcore-log: 
,10-13 20:09:41.047  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-13 20:09:41.047  5613  5659 I jxcore-log: 
,10-13 20:09:41.057  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-13 20:09:41.057  5613  5659 I jxcore-log: 
,10-13 20:09:41.070  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-13 20:09:41.070  5613  5659 I jxcore-log: 
,10-13 20:09:41.080  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-13 20:09:41.080  5613  5659 I jxcore-log: 
,10-13 20:09:41.084  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-13 20:09:41.084  5613  5659 I jxcore-log: 
,10-13 20:09:41.090  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-13 20:09:41.090  5613  5659 I jxcore-log: 
,10-13 20:09:41.096  5613  5659 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-13 20:09:41.097  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - INFO testUtils: 'BLE multiple advertisement supported'
10-13 20:09:41.097  5613  5659 I jxcore-log: 
,10-13 20:09:41.198  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - DEBUG CoordinatedClient: 'connected to the test server'
10-13 20:09:41.198  5613  5659 I jxcore-log: 
,10-13 20:09:41.312  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-13 20:09:41.312  5613  5659 I jxcore-log: 
,10-13 20:09:41.314  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - DEBUG CoordinatedClient: 'test client failed'
10-13 20:09:41.314  5613  5659 I jxcore-log: 
10-13 20:09:41.317  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-13 20:09:41.317  5613  5659 I jxcore-log: 
,10-13 20:09:41.322  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-13 20:09:41.322  5613  5659 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-13 20:09:41.322  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-13 20:09:41.322  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-13 20:09:41.322  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-13 20:09:41.322  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-13 20:09:41.322  5613  5659 I jxcore-log: 
,10-13 20:09:41.323  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-13 20:09:41.323  5613  5659 I jxcore-log: 
,10-13 20:09:41.325  5613  5659 I jxcore-log: 2016-10-14 00:09:41 - ERROR runTests: 'Test client failed: Native unit tests failed
10-13 20:09:41.325  5613  5659 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-13 20:09:41.325  5613  5659 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-13 20:09:41.325  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-13 20:09:41.325  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-13 20:09:41.325  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-13 20:09:41.325  5613  5659 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
10-13 20:09:41.325  5613  5659 I jxcore-log: 
,10-13 20:09:41.853  5975  5975 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-13 20:09:41.857  5975  5975 D AndroidRuntime: CheckJNI is OFF
,10-13 20:09:41.886  5975  5975 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-13 20:09:41.922  5975  5975 I Radio-JNI: register_android_hardware_Radio DONE
,10-13 20:09:41.939  5975  5975 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-13 20:09:41.947   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-13 20:09:41.948   926   939 I ActivityManager: Killing 5613:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-13 20:09:42.006   926  3103 I WindowState: WIN DEATH: Window{8117b24 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-13 20:09:42.006   926  3935 D GraphicsStats: Buffer count: 2
10-13 20:09:42.007   926  2951 D WifiService: Client connection lost with reason: 4
,10-13 20:09:42.074   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-13 20:09:42.075   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-13 20:09:42.076   926   939 E ActivityManager: Failure starting process com.test.thalitest
10-13 20:09:42.076   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-13 20:09:42.076   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:42.076   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:42.076   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-13 20:09:42.076   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-13 20:09:42.077   926   939 I ActivityManager:   Force finishing activity ActivityRecord{f06db71 u0 com.test.thalitest/.MainActivity t2}
,10-13 20:09:42.078   926   949 I art     : Starting a blocking GC Explicit
,10-13 20:09:42.083   926  3569 W ActivityManager: Spurious death for ProcessRecord{c1dbbb0 0:com.test.thalitest/u0a77}, curProc for 5613: null
,10-13 20:09:42.087   926   944 W WindowManager: Attempted to add application window with unknown token Token{72e0d56 ActivityRecord{f06db71 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,10-13 20:09:42.088   926   944 W WindowManager: Token{72e0d56 ActivityRecord{f06db71 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{72e0d56 ActivityRecord{f06db71 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-13 20:09:42.088   926   944 W WindowManager: view not successfully added to wm, removing view
,10-13 20:09:42.088   926   944 W WindowManager: Exception when adding starting window
10-13 20:09:42.088   926   944 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a8c1d6b V.E...... R.....ID 0,0-0,0} not attached to window manager
10-13 20:09:42.088   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-13 20:09:42.088   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-13 20:09:42.088   926   944 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-13 20:09:42.088   926   944 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-13 20:09:42.088   926   944 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-13 20:09:42.088   926   944 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:42.088   926   944 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:42.088   926   944 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-13 20:09:42.088   926   944 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-13 20:09:42.166   926   949 I art     : Explicit concurrent mark sweep GC freed 62365(4MB) AllocSpace objects, 15(496KB) LOS objects, 33% free, 29MB/43MB, paused 1.580ms total 87.924ms
,10-13 20:09:42.190   926   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-13 20:09:42.192  5975  5975 I art     : System.exit called, status: 0
,10-13 20:09:42.192  5975  5975 I AndroidRuntime: VM exiting with result code 0.
,10-13 20:09:42.196   926   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-13 20:09:42.200   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-13 20:09:42.205  5861  5861 D BluetoothMapAppObserver: onReceive
,10-13 20:09:42.205  5861  5861 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-13 20:09:42.209  4060  4169 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-13 20:09:42.214   926  2915 I InputReader: Reconfiguring input devices.  changes=0x00000010
10-13 20:09:42.216  3628  3628 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-13 20:09:42.240  3628  5987 I Keyboard.Facilitator.DecoderInitializer: run()
,10-13 20:09:42.244  3371  5988 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-13 20:09:42.257  3784  3784 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-13 20:09:42.268  3628  5987 I Decoder : createOrResetDecoder
,10-13 20:09:42.273   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
10-13 20:09:42.273  3555  3555 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-13 20:09:42.273  3555  3555 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-13 20:09:42.295  3856  5992 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-13 20:09:42.297  3856  5992 D AccountUtils: Clearing selected account for com.test.thalitest
,10-13 20:09:42.305    29    29 W kworker/3:1: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-13 20:09:42.309    29    29 W kworker/3:1: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-13 20:09:42.319    29    29 W kworker/3:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-13 20:09:42.326  3555  3555 I ConfigService: onCreate
,10-13 20:09:42.354  3856  5992 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-13 20:09:42.357  3628  5987 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-13 20:09:42.396  3856  5992 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:42.396  3856  5992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:42.396  3856  5992 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-13 20:09:42.397  3856  5992 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-13 20:09:42.406  3371  5988 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
--------- beginning of crash
10-13 20:09:42.407  3371  5988 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
10-13 20:09:42.407  3371  5988 E AndroidRuntime: Process: android.process.acore, PID: 3371
10-13 20:09:42.407  3371  5988 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-13 20:09:42.407  3371  5988 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-13 20:09:42.413   926  6000 E DropBoxManagerService: Can't write: system_app_crash
10-13 20:09:42.413   926  6000 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-13 20:09:42.413   926  6000 E DropBoxManagerService: 	... 5 more
,10-13 20:09:42.419  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,10-13 20:09:42.419  3856  3856 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,10-13 20:09:42.430  3856  3856 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,10-13 20:09:42.430  3856  3856 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,10-13 20:09:42.445  3371  5988 I Process : Sending signal. PID: 3371 SIG: 9
,10-13 20:09:42.459  4888  6002 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,10-13 20:09:42.473   926  3802 I ActivityManager: Start proc 6005:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,10-13 20:09:42.502  3856  6001 W BaseAppContext: Using Auth Proxy for data requests.
,10-13 20:09:42.509  3856  6001 W BaseAppContext: Using Auth Proxy for data requests.
,10-13 20:09:42.530  3856  3856 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,10-13 20:09:42.543  3856  6011 I GMPM-SVC: App measurement is starting up
,10-13 20:09:42.546  3856  6011 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-13 20:09:42.546  3856  6011 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-13 20:09:42.561   926  3802 I ActivityManager: Process android.process.acore (pid 3371) has died
,10-13 20:09:42.561   926  3802 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-13 20:09:42.718   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
