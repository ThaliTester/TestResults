#### Test 90916415f4fe0a6_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-26 16:56:03.623   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 16:56:04.099  5613  5613 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-26 16:56:04.104  5613  5613 D AndroidRuntime: CheckJNI is OFF
10-26 16:56:04.130  5613  5613 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-26 16:56:04.163  5613  5613 I Radio-JNI: register_android_hardware_Radio DONE
10-26 16:56:04.178  5613  5613 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-26 16:56:04.194   931  3119 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-26 16:56:04.237   931  3119 I ActivityManager: Start proc 5622:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-26 16:56:04.264  5613  5613 D AndroidRuntime: Shutting down VM
,10-26 16:56:04.588   931  3772 I WindowManager: Screenshot max retries 4 of Token{4faecc7 ActivityRecord{8a0be06 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{48b87de u0 Starting com.test.thalitest} drawState=2
,10-26 16:56:04.675  5622  5622 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750),
,10-26 16:56:04.706  5622  5622 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-26 16:56:04.728  5622  5622 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 1477-1495)
,10-26 16:56:04.728  5622  5622 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 16:56:04.746  5622  5622 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f7c686}
10-26 16:56:04.746  5622  5622 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 16:56:04.746  5622  5622 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 16:56:04.750  5622  5622 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 16:56:04.751  5622  5622 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 16:56:04.785  5622  5622 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 16:56:04.796  5622  5622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 16:56:04.796  5622  5622 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 16:56:04.796  5622  5622 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 16:56:04.796  5622  5622 I Adreno  : Build Date                       : 12/06/15
10-26 16:56:04.796  5622  5622 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 16:56:04.796  5622  5622 I Adreno  : Local Branch                     : mybranch17112971
10-26 16:56:04.796  5622  5622 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 16:56:04.796  5622  5622 I Adreno  : Remote Branch                    : NONE
10-26 16:56:04.796  5622  5622 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 16:56:04.828   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a79948d:true
,10-26 16:56:04.853  3438  3438 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[33934]" dev="sockfs" ino=33934 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 16:56:04.853  3438  3438 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[33934]" dev="sockfs" ino=33934 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 16:56:04.866  5622  5622 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 16:56:04.877  5622  5622 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 16:56:04.899  5622  5659 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 16:56:04.893   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[34873]" dev="sockfs" ino=34873 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 16:56:04.893   405   405 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[34873]" dev="sockfs" ino=34873 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 16:56:04.896   942   942 W Binder_2: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33945]" dev="sockfs" ino=33945 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 16:56:04.896   942   942 W Binder_2: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33945]" dev="sockfs" ino=33945 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 16:56:04.904  5622  5646 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-26 16:56:04.927  5622  5659 I OpenGLRenderer: Initialized EGL, version 1.4
,10-26 16:56:05.001   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +409ms (total +790ms)
,10-26 16:56:05.045  5622  5622 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5622
,10-26 16:56:05.131  5622  5622 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-26 16:56:05.300  5622  5661 D jxcore_app_log: JniHelper::setJavaVM(0xf4f7c000), pthread_self() = -585369296
,10-26 16:56:05.306  5622  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-26 16:56:05.306  5622  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-26 16:56:05.306  5622  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-26 16:56:05.306  5622  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-26 16:56:05.306  5622  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-26 16:56:05.306  5622  5661 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8b91fff added. We now have 1 listener(s)
,10-26 16:56:05.308  5622  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
10-26 16:56:05.309  5622  5661 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:56:05.309  5622  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-26 16:56:05.310  5622  5661 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,10-26 16:56:05.312  5622  5661 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@389bd1b added. We now have 1 listener(s)
10-26 16:56:05.312  5622  5661 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:56:05.317   931  2972 D WifiService: New client listening to asynchronous messages
,10-26 16:56:05.317  5622  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 16:56:05.317  5622  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-26 16:56:05.318  5622  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-26 16:56:05.318  5622  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-26 16:56:05.318  5622  5661 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-26 16:56:05.323  5622  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:56:05.323  5622  5661 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-26 16:56:05.326  5622  5661 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:05.327  5622  5661 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:05.327  5622  5661 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-26 16:56:05.327  5622  5661 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:56:05.327  5622  5661 I io.jxcore.node.LifeCycleMonitor: start: OK
10-26 16:56:05.329  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:05.333  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:05.441  5622  5622 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-26 16:56:05.950  5622  5668 W jxcore-log: Initializing JXcore engine
10-26 16:56:05.950  5622  5668 W jxcore-log: JXcore engine is ready
,10-26 16:56:05.969  5668  5668 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11865 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-26 16:56:05.969  5668  5668 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15459]" dev="sockfs" ino=15459 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
10-26 16:56:05.969  5668  5668 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-26 16:56:05.969  5668  5668 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32917]" dev="sockfs" ino=32917 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-26 16:56:05.982  5622  5668 W jxcore-log: Starting JXcore engine
,10-26 16:56:06.031  5622  5668 W jxcore-log: Platform android
10-26 16:56:06.031  5622  5668 W jxcore-log: 
,10-26 16:56:06.031  5622  5668 W jxcore-log: Process ARCH arm
10-26 16:56:06.031  5622  5668 W jxcore-log: 
,10-26 16:56:06.213  5622  5668 I jxcore-log: JXcore Cordova bridge is ready!
10-26 16:56:06.213  5622  5668 I jxcore-log: 
,10-26 16:56:06.213  5622  5668 W jxcore-log: JXcore engine is started
,10-26 16:56:06.226  5622  5661 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-26 16:56:06.234  5622  5622 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-26 16:56:15.825  5622  5668 I jxcore-log: 2016-10-26 20:56:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-26 16:56:15.825  5622  5668 I jxcore-log: 
,10-26 16:56:15.827  5622  5668 I jxcore-log: 2016-10-26 20:56:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-26 16:56:15.827  5622  5668 I jxcore-log: 
,10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:15.833  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:15.835  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:15.837  5622  5668 I jxcore-log: 2016-10-26 20:56:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-26 16:56:15.837  5622  5668 I jxcore-log: 
10-26 16:56:15.838  5622  5668 I jxcore-log: 2016-10-26 20:56:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-26 16:56:15.838  5622  5668 I jxcore-log: 
,10-26 16:56:16.086  5622  5668 I jxcore-log: 2016-10-26 20:56:16 - DEBUG UnitTest_app: 'Running unit tests'
10-26 16:56:16.086  5622  5668 I jxcore-log: 
,10-26 16:56:16.087  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:56:16.087  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40f050c added. We now have 2 listener(s)
,10-26 16:56:16.088  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:56:16.088  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:56:16.088  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 16:56:16.088  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 16:56:16.088  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@136fe55 added. We now have 2 listener(s)
,10-26 16:56:16.088  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:56:16.089  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 16:56:16.091  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:16.102  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:16.104  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:16.104  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 16:56:16.104  5622  5668 D executeNativeTests: Running unit tests
,10-26 16:56:16.110  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:16.115  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:16.142  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 16:56:16.142  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b added. We now have 3 listener(s)
10-26 16:56:16.142  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:56:16.142  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:56:16.142  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:56:16.143  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:56:16.143  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 added. We now have 3 listener(s)
10-26 16:56:16.143  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:56:16.143  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 16:56:16.144  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:16.150  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:16.150  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:56:16.151  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 16:56:16.152  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-26 16:56:16.152  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 16:56:16.152  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 16:56:16.152  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,10-26 16:56:16.153  5622  5668 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-26 16:56:16.153  5622  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-26 16:56:16.153  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 16:56:16.153  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 16:56:16.153  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 16:56:16.153  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 16:56:16.153  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:16.153  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 16:56:16.153  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:16.153  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:16.154  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:16.154  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:56:16.154  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:16.154  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-26 16:56:16.154  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b removed from the list
10-26 16:56:16.154  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:16.154  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 removed from the list
10-26 16:56:16.155  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:16.163  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:16.164  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:16.164  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:16.164  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:16.164  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:16.164  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.165  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:16.165  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.165  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.165  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:16.165  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:16.165  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:16.165  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:16.166  5622  5668 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-26 16:56:16.166  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:16.166  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:16.166  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 16:56:16.166  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:16.166  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:16.166  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:16.166  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:16.167  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
,10-26 16:56:16.167  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:16.167  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:16.167  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:16.167  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:56:16.167  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:16.167  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:16.167  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:16.167  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.167  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.167  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:16.167  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.167  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:16.167  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:16.167  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:16.167  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,10-26 16:56:16.170  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,10-26 16:56:16.171  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:16.171  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:16.171  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 16:56:16.171  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:16.171  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:16.171  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:16.171  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-26 16:56:16.171  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:16.171  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:16.171  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:16.171  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:16.171  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:16.171  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:16.171  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:16.171  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:16.171  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.172  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.172  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.172  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.172  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:16.172  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:16.172  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:16.172  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:16.172  5622  5668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 16:56:16.173  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:16.175  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:16.176  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:16.176  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:56:16.176  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:56:16.176  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurre,ntOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 16:56:16.176  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 16:56:16.177  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:56:16.177  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 16:56:16.178  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 16:56:16.178  5622  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 16:56:16.178  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 16:56:16.180  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:16.181  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 16:56:16.182  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 16:56:16.182  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 16:56:16.183  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:16.184  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-26 16:56:16.185  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-26 16:56:16.185  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.185  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 16:56:16.185  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 16:56:16.185  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 16:56:16.186  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 16:56:16.186  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.187  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:56:16.189  4592  4829 D BtGatt.GattService: registerClient() - UUID=32299aa5-c293-4391-b186-077d780fe442
10-26 16:56:16.190  4592  4675 D BtGatt.GattService: onClientRegistered() - UUID=32299aa5-c293-4391-b186-077d780fe442, clientIf=5
10-26 16:56:16.191  5622  5633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 16:56:16.193  4592  4606 D BtGatt.GattService: start scan with filters
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 16:56:16.198  4592  4685 D BtGatt.ScanManager: handling starting scan
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 16:56:16.198  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.198  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 16:56:16.198  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.199  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.199  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:56:16.200  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.200  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.200  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.200  4592  4685 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:56:16.200  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:56:16.200  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 16:56:16.201  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 16:56:16.201  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.202  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.202  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.202  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:16.202  5622  5668 I io.jxcore.node.ConnectionHelper: start: OK
10-26 16:56:16.208  4592  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 16:56:16.208  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:16.209  4592  4685 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 16:56:16.215  4592  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 16:56:16.215  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:16.216  4592  4685 D BtGatt.ScanManager: Starting BLE batch scan
10-26 16:56:16.216  4592  4685 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 16:56:16.230  4592  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-26 16:56:16.230  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:16.238  4592  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 16:56:16.239  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:56:16.702  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-26 16:56:16.702  5622  5622 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:56:16.703  5622  5622 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 16:56:19.208   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,10-26 16:56:19.214   931  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,10-26 16:56:21.206  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 16:56:21.206  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:21.207  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 16:56:21.207  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:21.207  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 16:56:21.207  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:21.207  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 16:56:21.207  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-26 16:56:21.207  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 16:56:21.207  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 16:56:21.208  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.208  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.208  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-26 16:56:21.210  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:56:21.210  4592  4863 D BtGatt.GattService: stopScan() - queue size =1
10-26 16:56:21.211  4592  4604 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 16:56:21.212  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-26 16:56:21.212  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.212  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 16:56:21.212  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.212  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:21.213  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 16:56:21.213  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 16:56:21.213  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.213  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.213  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-26 16:56:21.213  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.215  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:21.215  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:21.215  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.215  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:21.215  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.215  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.215  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.216  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 16:56:21.216  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:21.216  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.216  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.216  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 16:56:21.217  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 16:56:21.217  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:56:21.217  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.219  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.219  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.219  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:21.219  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:21.219  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:21.219  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:56:21.219  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:21.219  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:56:21.220  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:21.220  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:21.220  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:21.220  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:21.220  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:56:21.220  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:21.220  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:21.221  4592  4592 D BtGatt.ScanManager: awakened up at time 217989
10-26 16:56:21.228  4592  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 16:56:21.228  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:21.228  4592  4685 D BtGatt.ScanManager: stopping BLe Batch
,10-26 16:56:21.237  4592  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 16:56:21.237  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:21.238  4592  4685 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 16:56:21.262  4592  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-26 16:56:21.263  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:21.263  4592  4675 D BtGatt.GattService: current time is 218030704813
10-26 16:56:21.264  4592  4675 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -91, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -79, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -80, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -81, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -83, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -86, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-26 16:56:21.265  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 16:56:21.266  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 16:56:21.267  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,10-26 16:56:21.267  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-26 16:56:21.267  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-26 16:56:21.268  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-26 16:56:21.721  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 16:56:22.236   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-26 16:56:22.240   931  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,10-26 16:56:23.392   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-26 16:56:23.393   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-26 16:56:23.625   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 16:56:26.222  5622  5668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,10-26 16:56:26.228  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:26.238  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:26.243  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:56:26.244  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:56:26.244  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:56:26.244  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 16:56:26.244  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 16:56:26.244  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:56:26.244  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 16:56:26.250  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 16:56:26.251  5622  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-26 16:56:26.251  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 16:56:26.251  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:26.255  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:26.256  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 16:56:26.257  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 16:56:26.257  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 16:56:26.262  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.262  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 16:56:26.262  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 16:56:26.262  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 16:56:26.263  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-26 16:56:26.263  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.263  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:56:26.266  4592  4863 D BtGatt.GattService: registerClient() - UUID=f2470ad1-27c0-434a-a8e6-1efad21f97b8
10-26 16:56:26.266  4592  4675 D BtGatt.GattService: onClientRegistered() - UUID=f2470ad1-27c0-434a-a8e6-1efad21f97b8, clientIf=5
10-26 16:56:26.267  5622  5633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-26 16:56:26.267  4592  4604 D BtGatt.GattService: start scan with filters
,10-26 16:56:26.271  4592  4685 D BtGatt.ScanManager: handling starting scan
10-26 16:56:26.271  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 16:56:26.271  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.271  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-26 16:56:26.271  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.271  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.271  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 16:56:26.271  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 16:56:26.271  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.272  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.272  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 16:56:26.272  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.275  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.275  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:56:26.275  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.275  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.275  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:56:26.275  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.275  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 16:56:26.278  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 16:56:26.278  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.278  4592  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 16:56:26.278  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.278  4592  4685 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 16:56:26.281  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.281  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.281  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.281  5622  5668 I io.jxcore.node.ConnectionHelper: start: OK
10-26 16:56:26.285  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 16:56:26.285  4592  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 16:56:26.285  5622  5668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 16:56:26.286  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.286  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:26.286  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 16:56:26.286  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:26.286  4592  4685 D BtGatt.ScanManager: Starting BLE batch scan
10-26 16:56:26.286  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 16:56:26.286  4592  4685 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 16:56:26.286  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:26.286  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 16:56:26.286  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 16:56:26.286  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 16:56:26.286  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 16:56:26.286  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.286  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.286  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 16:56:26.287  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:56:26.288  4592  4863 D BtGatt.GattService: stopScan() - queue size =1
10-26 16:56:26.289  4592  4606 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 16:56:26.289  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 16:56:26.289  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.289  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,10-26 16:56:26.290  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.290  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.290  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 16:56:26.290  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 16:56:26.290  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.290  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.290  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-26 16:56:26.290  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.292  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.293  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 16:56:26.294  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 16:56:26.294  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:56:26.295  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.296  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.296  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.297  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.297  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:26.297  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:26.297  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:56:26.297  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:26.297  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:26.297  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:56:26.297  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:26.297  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:26.297  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-26 16:56:26.297  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:26.297  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:26.297  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:26.298  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:26.298  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:26.298  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.299  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.299  4592  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 16:56:26.299  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.299  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.299  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.299  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:26.299  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:26.300  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:26.300  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:26.300  5622  5668 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
10-26 16:56:26.302  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:56:26.306  4592  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 16:56:26.307  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:26.307  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:26.309  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:26.309  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:56:26.309  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:56:26.309  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 16:56:26.309  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 16:56:26.309  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:56:26.309  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 16:56:26.312  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:26.314  4592  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-26 16:56:26.314  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.314  4592  4685 D BtGatt.ScanManager: stopping BLe Batch
,10-26 16:56:26.315  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:26.315  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 16:56:26.315  5622  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 16:56:26.315  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-26 16:56:26.318  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 16:56:26.319  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 16:56:26.319  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-26 16:56:26.321  4592  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 16:56:26.321  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.321  4592  4685 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 16:56:26.323  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.323  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-26 16:56:26.323  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 16:56:26.323  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 16:56:26.323  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 16:56:26.323  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.324  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:56:26.326  4592  4863 D BtGatt.GattService: registerClient() - UUID=cd24aaf7-7b8c-4a6c-8907-b265df66310c
10-26 16:56:26.326  4592  4675 D BtGatt.GattService: onClientRegistered() - UUID=cd24aaf7-7b8c-4a6c-8907-b265df66310c, clientIf=5
10-26 16:56:26.327  5622  5632 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 16:56:26.327  4592  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-26 16:56:26.327  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.327  4592  4606 D BtGatt.GattService: start scan with filters
,10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 16:56:26.331  4592  4685 D BtGatt.ScanManager: handling starting scan
10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 16:56:26.331  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.331  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.331  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 16:56:26.332  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.333  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.333  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:56:26.334  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.334  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.334  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.334  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 16:56:26.334  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:56:26.335  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 16:56:26.335  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.336  4592  4675 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 16:56:26.336  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:26.336  4592  4685 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 16:56:26.337  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.337  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:26.337  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:26.337  5622  5668 I io.jxcore.node.ConnectionHelper: start: OK
,10-26 16:56:26.341  4592  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 16:56:26.341  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:56:26.342  4592  4685 D BtGatt.ScanManager: Starting BLE batch scan
10-26 16:56:26.342  4592  4685 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 16:56:26.350  4592  4675 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-26 16:56:26.350  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:56:26.354  4592  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 16:56:26.355  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:56:26.835  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
10-26 16:56:26.836  5622  5622 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 16:56:26.836  5622  5622 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 16:56:31.337  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 16:56:31.338  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:31.338  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 16:56:31.338  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:31.338  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 16:56:31.338  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:31.339  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 16:56:31.339  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-26 16:56:31.339  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 16:56:31.339  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 16:56:31.339  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.340  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.340  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 16:56:31.343  5622  5668 D BluetoothAdapter: STATE_ON
,10-26 16:56:31.345  4592  4606 D BtGatt.GattService: stopScan() - queue size =1
10-26 16:56:31.347  4592  4829 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-26 16:56:31.348  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 16:56:31.348  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.348  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 16:56:31.348  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.349  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:31.349  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 16:56:31.349  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 16:56:31.349  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:31.349  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.350  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 16:56:31.350  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.352  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.353  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:31.353  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.353  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.353  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.354  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.354  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.354  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 16:56:31.354  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.354  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.355  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.355  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 16:56:31.355  4592  4592 D BtGatt.ScanManager: awakened up at time 228122
10-26 16:56:31.355  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-26 16:56:31.359  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:56:31.359  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.360  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:31.361  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.361  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:31.361  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:56:31.361  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:56:31.361  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:31.362  4592  4675 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-26 16:56:31.362  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:31.363  4592  4685 D BtGatt.ScanManager: stopping BLe Batch
,10-26 16:56:31.369  4592  4675 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 16:56:31.370  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:31.370  4592  4685 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 16:56:31.387  4592  4675 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,10-26 16:56:31.387  4592  4675 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:56:31.387  4592  4675 D BtGatt.GattService: current time is 228154874772
10-26 16:56:31.387  4592  4675 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -80, 62, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -81, 79, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -95, 91, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -78, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -78, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -88, 63, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-26 16:56:31.388  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-26 16:56:31.389  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,10-26 16:56:31.389  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-26 16:56:31.389  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-26 16:56:31.389  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-26 16:56:31.390  4592  4675 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-26 16:56:31.861  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 16:56:31.861  5622  5622 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:31.862  5622  5622 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-26 16:56:33.394   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:34.395   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:35.396   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:36.362  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 16:56:36.363  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 16:56:36.363  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.363  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.363  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:56:36.363  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:56:36.364  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.364  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
,10-26 16:56:36.364  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.364  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
,10-26 16:56:36.364  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 16:56:36.364  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.366  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:56:36.366  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:36.366  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.370  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.370  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.371  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.371  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 16:56:36.371  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.371  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.371  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.373  5622  5668 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-26 16:56:36.374  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 16:56:36.375  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.375  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.375  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.375  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.375  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.375  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.375  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.377  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.377  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
,10-26 16:56:36.377  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.377  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.377  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.377  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.378  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.378  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.380  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.381  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:36.381  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.381  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.381  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.381  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.381  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.383  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 16:56:36.383  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:36.383  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.383  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 16:56:36.383  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.384  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.384  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.384  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.384  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.384  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.384  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.384  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.384  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.384  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:36.384  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.384  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.385  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.387  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.387  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.387  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.387  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.387  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.387  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.387  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.388  5622  5668 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-26 16:56:36.389  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:36.389  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-26 16:56:36.389  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.389  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.389  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.389  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.390  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.390  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.390  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.390  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.390  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.390  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:56:36.390  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.390  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.390  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.390  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.392  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.393  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:36.393  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.393  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.393  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.393  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.393  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.394  5622  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-26 16:56:36.394  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-26 16:56:36.394  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.395  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.395  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.395  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.395  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.395  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.395  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.395  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.395  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.395  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 16:56:36.395  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.396  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.396  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.396  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.396  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.397   536   536 I ServiceManager: Waiting for service AtCmdFwd...
10-26 16:56:36.399  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.399  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.399  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.399  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.399  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.400  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.400  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
,10-26 16:56:36.401  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 16:56:36.401  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 16:56:36.402  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 16:56:36.402  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 16:56:36.402  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-26 16:56:36.403  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 16:56:36.403  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-26 16:56:36.403  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 16:56:36.403  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-26 16:56:36.404  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:36.404  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.404  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.404  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.404  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.404  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:36.404  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.405  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.406  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.406  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.406  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.406  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.406  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.406  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.406  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.406  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:36.408  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.408  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.408  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.408  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.408  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.409  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:36.409  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.410  5622  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 16:56:36.410  5622  5668 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 16:56:36.410  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-26 16:56:36.415  5622  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 16:56:36.415  5622  5668 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
10-26 16:56:36.415  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-26 16:56:36.416  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,10-26 16:56:36.417  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-26 16:56:36.418  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-26 16:56:36.418  5622  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
10-26 16:56:36.419  5622  5668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 16:56:36.420  5622  5668 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
10-26 16:56:36.420  5622  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 16:56:36.420  5622  5668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 16:56:36.420  5622  5668 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
10-26 16:56:36.420  5622  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 16:56:36.420  5622  5668 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
10-26 16:56:36.421  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
10-26 16:56:36.424  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
10-26 16:56:36.425  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
10-26 16:56:36.425  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
10-26 16:56:36.426  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
10-26 16:56:36.426  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
10-26 16:56:36.427  5622  5668 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
10-26 16:56:36.427  5622  5668 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-26 16:56:36.427  5622  5668 E io.jxcore.node.ConnectionHelper: connect: Callback is null
10-26 16:56:36.428  5622  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
10-26 16:56:36.428  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:36.428  5622  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
10-26 16:56:36.428  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.428  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.428  5622  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
10-26 16:56:36.428  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.428  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.428  5622  5669 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
10-26 16:56:36.428  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.428  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.429  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
10-26 16:56:36.430  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.430  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.430  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.430  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.430  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.430  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.430  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.430  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.430  5622  5670 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
10-26 16:56:36.430  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.433  5622  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
10-26 16:56:36.433  5622  5669 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 16:56:36.433  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.433  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.434  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.434  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.434  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.434  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.434  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.435  5622  5668 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-26 16:56:36.429  4604  4604 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[30331]" dev="sockfs" ino=30331 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 16:56:36.429  4604  4604 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[30331]" dev="sockfs" ino=30331 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 16:56:36.436  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:36.436  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.437  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.437  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.437  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.437  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.437  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.437  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.437  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.437  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.437  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.437  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.438  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.438  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.438  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.438  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.439  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.439  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.439  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.439  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.439  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.439  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.440  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.442  5622  5668 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-26 16:56:36.442  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:36.442  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.442  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.443  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.443  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.443  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.443  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.443  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.443  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.443  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.443  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.443  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.443  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.443  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.443  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.443  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.444  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.444  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.445  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.445  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.445  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.445  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.445  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.445  5622  5668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-26 16:56:36.446  5622  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-26 16:56:36.446  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 16:56:36.446  5622  5668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-26 16:56:36.446  5622  5668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 16:56:36.446  5622  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-26 16:56:36.446  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 16:56:36.446  5622  5668 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-26 16:56:36.446  5622  5668 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-26 16:56:36.446  5622  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-26 16:56:36.446  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 16:56:36.447  5622  5668 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-26 16:56:36.447  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:36.447  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:36.447  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:36.447  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.447  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.447  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.447  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.447  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.447  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.447  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.447  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.447  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.447  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.447  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.447  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.447  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.449  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.449  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.449  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:36.449  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:36.449  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:36.449  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.449  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.450  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:36.450  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.450  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:36.450  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:36.450  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:36.450  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:36.450  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:36.450  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:36.450  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:36.450  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:37.398   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:38.398   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-26 16:56:41.451  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:41.451  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.451  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:41.452  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.452  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.452  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:41.452  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
,10-26 16:56:41.453  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:41.453  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:41.453  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:41.453  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:41.453  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.453  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:41.454  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:41.454  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:41.454  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.454  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.454  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 16:56:41.454  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.454  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.455  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.455  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.456  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.459  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:41.459  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.459  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.460  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:41.460  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 16:56:41.460  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.460  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
,10-26 16:56:41.464  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-26 16:56:41.465  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:56:41.469  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-26 16:56:41.471  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-26 16:56:41.471  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-26 16:56:41.471  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-26 16:56:41.471  5622  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-26 16:56:41.471  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-26 16:56:41.471  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 16:56:41.471  5622  5622 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-26 16:56:41.472  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 16:56:41.472  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-26 16:56:41.472  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-26 16:56:41.472  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-26 16:56:41.472  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.472  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-26 16:56:41.472  5622  5671 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 16:56:41.472  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-26 16:56:41.472  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:41.472  5622  5622 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-26 16:56:41.472  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.472  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 16:56:41.473  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-26 16:56:41.473  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-26 16:56:41.473  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.473  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.473  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:56:41.469  4829  4829 W Binder_3: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[34914]" dev="sockfs" ino=34914 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 16:56:41.474  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.474  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:41.469  4829  4829 W Binder_3: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[34914]" dev="sockfs" ino=34914 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-26 16:56:41.474  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.475  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.475  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
,10-26 16:56:41.475  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:56:41.475  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:41.475  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:56:41.475  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:41.475  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:56:41.475  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-26 16:56:41.475  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:41.475  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:56:41.475  5622  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-26 16:56:41.475  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:41.475  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-26 16:56:41.475  5622  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-26 16:56:41.475  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:41.475  5622  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-26 16:56:41.475  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.475  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.476  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:41.476  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.476  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.476  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:56:41.476  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.476  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.476  5622  5622 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-26 16:56:41.476  5622  5622 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:41.477  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.477  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.477  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.477  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:41.478  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:41.478  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.478  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.479  5622  5668 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-26 16:56:41.479  5622  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,10-26 16:56:41.479  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-26 16:56:41.480  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 16:56:41.480  5622  5668 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-26 16:56:41.480  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:41.480  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:41.480  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:41.480  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:41.480  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.480  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.480  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:41.480  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:41.480  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:41.480  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.481  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:41.481  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.481  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.481  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.481  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.481  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.482  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.483  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.483  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.483  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:41.483  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 16:56:41.483  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.483  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.488  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:41.489  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:41.489  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:41.489  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:41.489  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.489  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.489  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:41.489  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:41.489  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:41.490  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.490  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:41.490  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.490  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.490  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.490  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.490  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.491  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.491  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.491  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.491  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:56:41.491  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,10-26 16:56:41.491  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.491  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.492  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:56:41.492  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:56:41.492  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:56:41.492  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:56:41.492  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.492  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.493  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:56:41.493  5622  5668 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4257f4b not in the list
10-26 16:56:41.493  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:41.493  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.493  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:41.493  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.493  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.493  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:41.493  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:41.493  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.494  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.494  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.494  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:56:41.494  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 16:56:41.494  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:56:41.494  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:56:41.494  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc23d28 not in the list
10-26 16:56:41.495  5622  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-26 16:56:41.496  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 16:56:41.496  5622  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-26 16:56:41.496  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-26 16:56:41.497  5622  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-26 16:56:41.497  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-26 16:56:41.498  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-26 16:56:41.499  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,10-26 16:56:41.499  5622  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-26 16:56:41.499  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 16:56:41.499  5622  5668 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-26 16:56:41.499  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-26 16:56:41.499  5622  5668 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-26 16:56:41.499  5622  5668 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-26 16:56:41.500  5622  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-26 16:56:41.500  5622  5668 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-26 16:56:41.500  5622  5668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-26 16:56:41.501  5622  5668 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
10-26 16:56:41.501  5622  5668 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-26 16:56:41.501  5622  5668 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-26 16:56:41.501  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:56:41.502  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8965bca added. We now have 3 listener(s)
10-26 16:56:41.502  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:56:41.503  5622  5668 D BluetoothAdapter: enable(): BT is already enabled..!
10-26 16:56:41.504   931  3183 D WifiService: setWifiEnabled: true pid=5622, uid=10077
10-26 16:56:41.504   931  3183 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 16:56:41.562  4592  4812 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,10-26 16:56:41.562  4592  4823 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
10-26 16:56:41.563  5622  5669 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
10-26 16:56:41.563  5622  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
10-26 16:56:41.563  5622  5669 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,10-26 16:56:41.975  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 16:56:43.400   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:44.401   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:45.402   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:46.403   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:46.509  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 16:56:46.509  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38d13b added. We now have 4 listener(s)
,10-26 16:56:46.510  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:56:46.523  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:46.523  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38d13b removed from the list
10-26 16:56:46.524  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:46.524  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:56:46.524  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:56:46.526  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:56:46.526  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6934058 added. We now have 4 listener(s)
,10-26 16:56:46.526  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:56:46.530  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:56:46.531  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6934058 removed from the list
10-26 16:56:46.531  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:56:46.531  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:56:46.531  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:56:46.533  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:56:46.533  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@65d65b1 added. We now have 4 listener(s)
,10-26 16:56:46.533  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:56:46.540   931  3188 D WifiService: setWifiEnabled: false pid=5622, uid=10077
,10-26 16:56:46.540   931  3188 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 16:56:46.547   931  2971 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-26 16:56:46.547   931  2971 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 16:56:46.547   931  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 16:56:46.547   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 16:56:46.551  4592  4666 D BluetoothAdapterState: Current state: ON, message: 23
10-26 16:56:46.552  4592  4666 D BluetoothAdapterProperties: Setting state to 13
10-26 16:56:46.552  4592  4666 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-26 16:56:46.553  4592  4666 D BluetoothAdapterProperties: onBluetoothDisable()
10-26 16:56:46.554  4592  4666 I BluetoothAdapterState: Entering PendingCommandState
10-26 16:56:46.555  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:56:46.560  4592  4675 D BluetoothAdapterProperties: Scan Mode:20
,10-26 16:56:46.561  4592  4666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 16:56:46.562  4592  4592 D BluetoothMapService: onReceive
10-26 16:56:46.562  4592  4592 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-26 16:56:46.562  4592  4592 D BluetoothMapService: STATE_TURNING_OFF
,10-26 16:56:46.562  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:46.562  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:46.563  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.563  4592  4592 D BluetoothMapService: MAP Service closeService in
10-26 16:56:46.563  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:56:46.563  4592  4592 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 16:56:46.564  4592  4592 D ObexServerSockets0: shutdown(block = true)
10-26 16:56:46.564  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:56:46.564  4592  4592 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 16:56:46.564  4592  4592 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 16:56:46.565   931  5360 D DhcpClient: Clearing IP address
10-26 16:56:46.565  4592  4823 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-26 16:56:46.565  4592  4866 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-26 16:56:46.565  4592  4865 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-26 16:56:46.565   508   927 D CommandListener: Clearing all IP addresses on wlan0
10-26 16:56:46.568  4592  4592 I BtOppRfcommListener: stopping Accept Thread
10-26 16:56:46.569  4592  5302 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 16:56:46.569  4592  5302 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-26 16:56:46.569  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:46.572   508   927 D CommandListener: Setting iface cfg
,10-26 16:56:46.573  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:46.576  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:46.576  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:46.577  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.577  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:46.578   931   944 I ActivityManager: Start proc 5675:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-26 16:56:46.580   931  5361 D DhcpClient: Receive thread stopped
10-26 16:56:46.581  4592  4592 D HeadsetService: Received stop request...Stopping profile...
10-26 16:56:46.581  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:46.582  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:46.582  3569  5415 V NativeCrypto: Read error: ssl=0x7f87ca3c80: I/O error during system call, Connection timed out
10-26 16:56:46.582  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.583  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:46.583   931   931 D BluetoothHeadset: Proxy object disconnected
10-26 16:56:46.584  3722  4121 D BluetoothHeadset: Proxy object disconnected
10-26 16:56:46.585  3569  5415 V NativeCrypto: SSL shutdown failed: ssl=0x7f87ca3c80: I/O error during system call, Broken pipe
10-26 16:56:46.585  3111  3124 D BluetoothHeadset: Proxy object disconnected
10-26 16:56:46.585   931   931 D BluetoothHeadset: Proxy object disconnected
10-26 16:56:46.585   931   931 D BluetoothHeadset: Proxy object disconnected
10-26 16:56:46.588  3111  3111 D HeadsetProfile: Bluetooth service disconnected
10-26 16:56:46.589   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,10-26 16:56:46.589   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-26 16:56:46.591  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:46.592  4592  4592 D A2dpService: Received stop request...Stopping profile...
10-26 16:56:46.592  4592  4847 D A2dpStateMachine: Exit Disconnected: -1
10-26 16:56:46.594   931   931 D BluetoothA2dp: Proxy object disconnected
10-26 16:56:46.594  3111  3111 D BluetoothA2dp: Proxy object disconnected
10-26 16:56:46.594  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:56:46.595  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.595  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:46.598  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.598  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:46.598   931  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
10-26 16:56:46.599   931   931 D RttService: SCAN_AVAILABLE : 1
,10-26 16:56:46.599  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.599  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:46.599   534   534 E Parcel  : Reading a NULL string not supported here.
10-26 16:56:46.599   931  3047 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 16:56:46.601  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:46.601  3702  3871 W QCNEJ   : |CORE| network lost: 100
10-26 16:56:46.602  4592  4592 D HidService: Received stop request...Stopping profile...
10-26 16:56:46.602  4592  4592 D HidService: Stopping Bluetooth HidService
10-26 16:56:46.602  3702  3871 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-26 16:56:46.602  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.602  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:56:46.603  4592  4592 V BluetoothAdapterState: isTurningOff()=true
10-26 16:56:46.606  4592  4592 V BluetoothAdapterState: isTurningOn()=false
10-26 16:56:46.606  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:56:46.606  4592  4592 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 16:56:46.608  4592  4592 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-26 16:56:46.608  4592  4592 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 16:56:46.608  4592  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 16:56:46.609  4592  4812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:56:46.609  4592  4812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:56:46.609  4592  4812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:56:46.609  4592  4592 D HealthService: Received stop request...Stopping profile...
10-26 16:56:46.610  4592  4592 D PanService: Received stop request...Stopping profile...
10-26 16:56:46.610  4592  4675 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-26 16:56:46.611  4592  4592 D BluetoothMapService: Received stop request...Stopping profile...
10-26 16:56:46.612  4592  4592 D BluetoothMapService: stop()
,10-26 16:56:46.612  4592  4592 D BluetoothMapAppObserver: deinitObservers()
10-26 16:56:46.612  4592  4592 D BluetoothMapAppObserver: removeReceiver()
,10-26 16:56:46.614  4592  4592 D SapService: Received stop request...Stopping profile...
10-26 16:56:46.614  4592  4592 V SapService: stop()
,10-26 16:56:46.619  4592  4592 V BluetoothAdapterState: isTurningOff()=true
,10-26 16:56:46.619  4592  4592 V BluetoothAdapterState: isTurningOn()=false
,10-26 16:56:46.619  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 16:56:46.619  4592  4592 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:56:46.620  4592  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-26 16:56:46.620  4592  4812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:56:46.620  4592  4812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 16:56:46.620  4592  4812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-26 16:56:46.620  4592  4812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-26 16:56:46.620  4592  4812 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-26 16:56:46.621  4592  4812 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-26 16:56:46.621  4592  4592 V BluetoothAdapterState: isTurningOff()=true
10-26 16:56:46.621  4592  4592 V BluetoothAdapterState: isTurningOn()=false
10-26 16:56:46.621  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:56:46.621  4592  4592 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:56:46.621  4592  4592 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 16:56:46.621  4592  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 16:56:46.621  4592  4592 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 16:56:46.622  4592  4592 V BluetoothAdapterState: isTurningOff()=true
10-26 16:56:46.622  4592  4592 V BluetoothAdapterState: isTurningOn()=false
10-26 16:56:46.622  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:56:46.622  4592  4592 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:56:46.622  4592  4592 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 16:56:46.623  4592  4592 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 16:56:46.623  4592  4675 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-26 16:56:46.623  4592  4592 V BluetoothAdapterState: isTurningOff()=true
10-26 16:56:46.623  4592  4592 V BluetoothAdapterState: isTurningOn()=false
10-26 16:56:46.623  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:56:46.623  4592  4592 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:56:46.623  3111  3111 D BluetoothInputDevice: Proxy object disconnected
10-26 16:56:46.623  3111  3111 D HidProfile: Bluetooth service disconnected
10-26 16:56:46.623  4592  4592 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 16:56:46.623  4592  4592 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 16:56:46.623  3111  3111 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-26 16:56:46.624  3111  3111 D PanProfile: Bluetooth service disconnected
10-26 16:56:46.624  3111  3111 D BluetoothMap: Proxy object disconnected
10-26 16:56:46.624  3111  3111 D MapProfile: Bluetooth service disconnected
10-26 16:56:46.624  4592  4592 D BluetoothMapService: MAP Service closeService in
10-26 16:56:46.624  4592  4592 V BluetoothAdapterState: isTurningOff()=true
10-26 16:56:46.624  4592  4592 V BluetoothAdapterState: isTurningOn()=false
10-26 16:56:46.624  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:56:46.624  4592  4592 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:56:46.625  4592  4592 D BluetoothMapService: cleanup()
10-26 16:56:46.625  4592  4592 D BluetoothMapService: MAP Service closeService in
10-26 16:56:46.625  4592  4592 V BluetoothAdapterState: isTurningOff()=true
,10-26 16:56:46.625  4592  4592 V BluetoothAdapterState: isTurningOn()=false
10-26 16:56:46.625  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:56:46.625  4592  4592 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:56:46.625  4592  4666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 16:56:46.625  4592  4666 D BluetoothAdapterProperties: Setting state to 15
10-26 16:56:46.625  4592  4666 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 16:56:46.626  4592  4666 I BluetoothAdapterState: Entering BleOnState
10-26 16:56:46.626  3111  3945 D BluetoothMap: onBluetoothStateChange: up=false
,10-26 16:56:46.627  3722  3751 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:56:46.627   931  2971 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 16:56:46.627   931  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 16:56:46.628  3111  3125 D BluetoothPan: onBluetoothStateChange on: false
10-26 16:56:46.628   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:56:46.628   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 16:56:46.628   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:56:46.629  3111  3124 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:56:46.629  3111  3945 D BluetoothPbap: onBluetoothStateChange: up=false
,10-26 16:56:46.630  3111  3125 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 16:56:46.630   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:56:46.631  3111  3124 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 16:56:46.632  4592  4666 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 16:56:46.632  4592  4666 D BluetoothAdapterProperties: Setting state to 16
10-26 16:56:46.632  4592  4666 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 16:56:46.633  4592  4666 D BluetoothAdapterProperties: onBleDisable
10-26 16:56:46.633  4592  4666 I BluetoothAdapterState: Entering PendingCommandState
10-26 16:56:46.634  4592  4667 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-26 16:56:46.634   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 16:56:46.636  4592  4675 D BluetoothAdapterProperties: Scan Mode:20
10-26 16:56:46.637  4592  4812 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-26 16:56:46.637  4592  4812 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:56:46.638  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.638  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:46.641  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.641  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:56:46.644  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.644  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:46.645  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:46.647  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:46.648  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:46.657  5675  5675 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-26 16:56:46.659   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
10-26 16:56:46.660   508   927 D CommandListener: Clearing all IP addresses on wlan0
10-26 16:56:46.660   931  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-26 16:56:46.661   931  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 16:56:46.661   508   927 D TetherController: Setting IP forward enable = 0
10-26 16:56:46.662   931   948 D Tethering: MasterInitialState.processMessage what=3
10-26 16:56:46.664   931  2971 D DhcpClient: doQuit
10-26 16:56:46.664   931  2971 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 16:56:46.665  5273  5273 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@783d3d2 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
10-26 16:56:46.665   931  5360 D DhcpClient: onQuitting
10-26 16:56:46.665  3432  3432 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 16:56:46.665  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:46.668  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.669  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:46.670  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.670  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:46.671  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.671  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:46.672  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.672  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:56:46.676  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:46.676  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:46.677  5043  5056 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 16:56:46.677  5043  5056 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 16:56:46.677  5043  5056 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-26 16:56:46.677  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:46.677  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:46.677  5043  5056 E SarControlService: no key has been found,reset the power
10-26 16:56:46.677  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 16:56:46.677  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 16:56:46.678  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-26 16:56:46.678  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-26 16:56:46.678  5069  5069 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 16:56:46.679  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:46.680  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 16:56:46.680  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 16:56:46.680  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 16:56:46.682  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 16:56:46.682  5069  5069 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 16:56:46.683  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:46.684  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000ea03000000000000ffffffff]
10-26 16:56:46.685  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-26 16:56:46.685  5069  5083 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-26 16:56:46.685  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:56:46.685  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,10-26 16:56:46.691  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000eb03000000000000ffffffff]
10-26 16:56:46.692  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,10-26 16:56:46.692  5069  5083 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-26 16:56:46.692  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:56:46.693  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 16:56:46.693  3432  3432 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-26 16:56:46.698  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 16:56:46.699  3432  3432 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-26 16:56:46.700   508   920 W SocketClient: write error (Broken pipe)
10-26 16:56:46.700   508   920 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-26 16:56:46.700   508   920 W SocketListener: Error sending broadcast (Broken pipe)
,10-26 16:56:46.703  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 16:56:46.704   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@63c4995:true
,10-26 16:56:46.714   508   927 E Netd    : netlink response contains error (No such file or directory)
10-26 16:56:46.716   931  3183 I ActivityManager: Start proc 5702:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-26 16:56:46.725  3432  3432 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-26 16:56:46.728  5675  5675 D LocalBluetoothProfileManager: Adding local MAP profile
,10-26 16:56:46.730  5675  5675 D BluetoothMap: Create BluetoothMap proxy object
,10-26 16:56:46.745  5675  5675 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
10-26 16:56:46.745  3432  3432 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-26 16:56:46.759  5702  5702 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-26 16:56:46.763  5675  5675 D DockEventReceiver: finishStartingService: stopping service
,10-26 16:56:46.771   931  3804 I ActivityManager: Killing 5007:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-26 16:56:46.845  4592  4675 I bt_hci  : shut_down
,10-26 16:56:46.847  4592  4686 D bt_hwcfg: hw_epilog_process
,10-26 16:56:46.848  4592  4686 I bt_vendor: low_power_mode_cb
,10-26 16:56:46.850  4404  4404 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 16:56:46.850   931  2971 D wifi    : In wifi stop Hal
10-26 16:56:46.850   931  2971 D wifi    : halHandle = 0x7f85b6de00, mVM = 0x7fa21cd140, mCls = 0x100a02
10-26 16:56:46.850   931  3431 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 16:56:46.850   931  3431 D WifiHAL : Got a signal to exit!!!
10-26 16:56:46.850   931  3431 I WifiHAL : Exit wifi_event_loop
10-26 16:56:46.851   931  2971 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-26 16:56:46.851   931  2971 E WifiHAL : Event processing terminated
,10-26 16:56:46.851   931  2971 D wifi    : In wifi cleaned up handler
10-26 16:56:46.851   931  2971 I WifiHAL : Internal cleanup completed
10-26 16:56:46.852  4592  4686 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-26 16:56:46.852  4592  4686 I bt_vendor: epilog_cb
10-26 16:56:46.852  4592  4686 I bt_hci  : epilog_finished_callback
10-26 16:56:46.853  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:46.853  3875  4177 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 16:56:46.854  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:46.856  4592  4675 I bt_hci_h4: hal_close
10-26 16:56:46.856  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:46.857  4592  4675 I bt_userial_vendor: device fd = 54 close
,10-26 16:56:46.875   931  3431 D wifi    : set interface wlan0 flags (DOWN)
,10-26 16:56:46.875   931  2971 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 16:56:46.966  4592  4667 D bt_stack_manager: event_shut_down_stack finished.
,10-26 16:56:46.966  4592  4666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-26 16:56:46.968  4592  4592 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 16:56:46.968  4592  4666 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-26 16:56:46.969  4592  4592 D BtGatt.GattService: Received stop request...Stopping profile...
10-26 16:56:46.969  4592  4592 D BtGatt.GattService: stop()
10-26 16:56:46.969  4592  4592 D BtGatt.AdvertiseManager: advertise clients cleared
,10-26 16:56:46.971  4592  4592 V BluetoothAdapterState: isTurningOff()=false
,10-26 16:56:46.971  4592  4592 V BluetoothAdapterState: isTurningOn()=false
10-26 16:56:46.971  4592  4592 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:56:46.971  4592  4592 V BluetoothAdapterState: isBleTurningOff()=true
10-26 16:56:46.971  4592  4666 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 16:56:46.971  4592  4666 D BluetoothAdapterProperties: Setting state to 10
,10-26 16:56:46.971  4592  4666 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 16:56:46.972  4592  4666 I BluetoothAdapterState: Entering OffState
,10-26 16:56:46.973   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-26 16:56:46.979  4592  4592 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 16:56:46.979  4592  4592 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 16:56:46.979  4592  4592 I BluetoothServiceJni: cleanupNative: return from cleanup
10-26 16:56:46.980  4592  4667 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 16:56:46.988  5702  5702 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-26 16:56:46.988  5702  5702 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.988  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 16:56:46.989  5702  5702 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 16:56:46.989  5702  5702 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:170)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.989  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 16:56:46.990  5702  5702 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.r.k.d(PG:583)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:170)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.990  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 16:56:46.992  5702  5702 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.992  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 16:56:46.993  5702  5702 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at java.io.File.exists(File.java:361)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 16:56:46.993  5702  5702 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-26 16:56:46.993  5702  5702 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-26 16:56:46.995  4592  4667 D bt_stack_manager: event_clean_up_stack finished.
10-26 16:56:46.996  4592  4592 I art     : System.exit called, status: 0
10-26 16:56:46.997  4592  4592 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
10-26 16:56:47.000  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 16:56:47.022  5675  5675 D DockEventReceiver: finishStartingService: stopping service
10-26 16:56:47.023   931  3772 I ActivityManager: Killing 5389:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,10-26 16:56:47.045   931  3183 I ActivityManager: Process com.android.bluetooth (pid 4592) has died
10-26 16:56:47.048  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 16:56:47.060   931  3804 I ActivityManager: Start proc 5734:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,10-26 16:56:47.079   931   948 D Tethering: InitialState.processMessage what=4
,10-26 16:56:47.082   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 16:56:47.125  5734  5734 D AdapterServiceConfig: Adding HeadsetService
,10-26 16:56:47.126  5734  5734 D AdapterServiceConfig: Adding A2dpService
10-26 16:56:47.126  5734  5734 D AdapterServiceConfig: Adding HidService
10-26 16:56:47.126  5734  5734 D AdapterServiceConfig: Adding HealthService
10-26 16:56:47.126  5734  5734 D AdapterServiceConfig: Adding PanService
10-26 16:56:47.127  5734  5734 D AdapterServiceConfig: Adding GattService
10-26 16:56:47.127  5734  5734 D AdapterServiceConfig: Adding BluetoothMapService
10-26 16:56:47.127  5734  5734 D AdapterServiceConfig: Adding SapService
,10-26 16:56:47.134   931  3804 I ActivityManager: Killing 5402:com.android.chrome/u0a39 (adj 15): empty #17
,10-26 16:56:47.164  4025  4025 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 16:56:47.168  4025  4025 D SystemUpdateService: onCreate
,10-26 16:56:47.171  4025  4025 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-26 16:56:47.179  4025  4025 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-26 16:56:47.187  4025  5386 I iu.UploadsManager: num queued entries: 0
,10-26 16:56:47.187  4025  5386 I iu.UploadsManager: num updated entries: 0
10-26 16:56:47.188  4025  5386 I iu.SyncManager: NEXT; no task
,10-26 16:56:47.195  4025  4025 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 16:56:47.197  4025  4025 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-26 16:56:47.200  4025  5746 I SystemUpdateService: active receiver: enabled
,10-26 16:56:47.208   931  3585 I ActivityManager: Start proc 5748:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-26 16:56:47.211  4025  5746 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 16:56:47.217  4025  5746 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-26 16:56:47.219  4025  5746 I SystemUpdateService: now status is 0 (complete)
10-26 16:56:47.219  4025  5746 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-26 16:56:47.219  4025  5746 I SystemUpdateService: file has been verified
,10-26 16:56:47.220  4025  5746 I SystemUpdateService: OTA package size = 21989297
,10-26 16:56:47.243  5748  5748 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-26 16:56:47.247  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 16:56:47.254  5748  5748 D SprintDMHelper: simOperator: 
,10-26 16:56:47.254  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 16:56:47.265  4025  5746 I SystemUpdateService: showing system update notification
,10-26 16:56:47.265   931   941 I ActivityManager: Start proc 5760:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,10-26 16:56:47.295  4025  4025 D SystemUpdateService: onDestroy
,10-26 16:56:47.296   931  3800 I ActivityManager: Killing 5420:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,10-26 16:56:47.363  4404  5774 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-26 16:56:47.373   931  3804 I ActivityManager: Start proc 5775:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,10-26 16:56:47.375   931  3804 I ActivityManager: Killing 5273:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-26 16:56:47.404   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:47.447  5775  5775 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,10-26 16:56:47.603   931   941 I ActivityManager: Killing 4690:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-26 16:56:47.627  5702  5724 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-26 16:56:47.639   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dd7060a:true
,10-26 16:56:47.643   931  3183 I ActivityManager: Start proc 5787:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-26 16:56:47.674  5787  5787 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-26 16:56:47.682   931  3183 I ActivityManager: Killing 5483:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-26 16:56:47.704   508   927 D TetherController: Setting IP forward enable = 0
,10-26 16:56:48.405   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-26 16:56:51.566   931   942 D WifiService: setWifiEnabled: true pid=5622, uid=10077
,10-26 16:56:51.566   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 16:56:51.574   508   927 D SoftapController: Softap fwReload - Ok
,10-26 16:56:51.580   508   927 D CommandListener: Setting iface cfg
,10-26 16:56:51.581   508   927 D CommandListener: Trying to bring down wlan0
,10-26 16:56:51.583   508   927 D CommandListener: Clearing all IP addresses on wlan0
,10-26 16:56:51.588   931  2971 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 16:56:52.160   931  2971 D wifi    : set interface wlan0 flags (UP)
,10-26 16:56:52.163   931  2971 I WifiHAL : Initializing wifi
10-26 16:56:52.164   931  2971 I WifiHAL : Creating socket
10-26 16:56:52.164   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 16:56:52.169   931  2971 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-26 16:56:52.169   931  2971 D wifi    : Did set static halHandle = 0x7f85b6de00
10-26 16:56:52.169   931  2971 D wifi    : halHandle = 0x7f85b6de00, mVM = 0x7fa21cd140, mCls = 0x18f6
,10-26 16:56:52.170   931  2971 D wifi    : array field set
10-26 16:56:52.170   931  2971 I WifiNative-HAL: interface[0] = wlan0
,10-26 16:56:52.172   931  5812 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547704200704
,10-26 16:56:52.172   931  5812 D wifi    : waitForHalEvents called, vm = 0x7fa21cd140, obj = 0x18f6, env = 0x7f837a0080
,10-26 16:56:52.238  5813  5813 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 16:56:52.260  5813  5813 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 16:56:52.274   931  2971 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 16:56:52.276  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:52.277  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:52.278  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:52.287  5813  5813 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 16:56:52.287  5813  5813 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 16:56:52.304   931  2971 D WifiConfigStore: Loading config and enabling all networks 
10-26 16:56:52.305  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:52.305  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:56:52.305  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:52.305  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:52.307  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:52.307  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:52.307  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:52.307  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:56:52.308  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:52.308  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:52.308  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:52.309  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:56:52.314   931  2971 D WifiConfigStore: loaded 0 passpoint configs
10-26 16:56:52.314   931  2971 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-26 16:56:52.314   931  2971 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-26 16:56:52.315   931  2971 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-26 16:56:52.316   931  2971 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-26 16:56:52.317   931  2971 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-26 16:56:52.317   931  2971 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-26 16:56:52.317   931  2971 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-26 16:56:52.322   931  2971 D WifiNative-HAL: Setting external_sim to 1
,10-26 16:56:52.322  4404  4404 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 16:56:52.322   931  2971 D wifi    : setting dfs flag to true, 0x7f88a35d40
10-26 16:56:52.323   931  2971 D WifiStateMachine: Setting OUI to DA-A1-19
10-26 16:56:52.323   931  2971 D wifi    : setting scan oui 0x7f88a35d40
10-26 16:56:52.323   931  2971 D WifiHAL : Sending mac address OUI
,10-26 16:56:52.328   931  2971 E native  : do suspend false
,10-26 16:56:52.334   931  2971 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-26 16:56:52.335   508   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-26 16:56:52.335   931   931 D RttService: SCAN_AVAILABLE : 3
10-26 16:56:52.335   931  3047 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-26 16:56:52.336   508   927 D CommandListener: Setting iface cfg
,10-26 16:56:52.339   931  2959 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,10-26 16:56:52.339   931  2959 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 16:56:52.347   931  2959 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 16:56:52.352   931  2959 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-26 16:56:52.352   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=249119 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,10-26 16:56:55.450  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:56:55.455  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:56:55.462  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:56:55.467  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:56:55.473  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:56:55.533   931  2971 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 16:56:55.534   931  2971 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-26 16:56:55.534   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 16:56:55.546   931  2971 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 16:56:55.578   931  2971 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 16:56:55.580  5813  5813 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 16:56:56.010  5813  5813 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 16:56:56.042  5813  5813 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-26 16:56:56.043  5813  5813 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 16:56:56.054   931  2971 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 16:56:56.054   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-26 16:56:56.054   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 16:56:56.073   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 16:56:56.084   508   927 D CommandListener: Setting iface cfg
,10-26 16:56:56.090   931  2971 D WifiStateMachine: Start Dhcp Watchdog 2
,10-26 16:56:56.097   931  5819 D DhcpClient: Receive thread started
,10-26 16:56:56.100   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 16:56:56.100   931  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-26 16:56:56.100   931  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-26 16:56:56.181   931  2971 E native  : do suspend false
,10-26 16:56:56.196   931  5818 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 16:56:56.208   931  5819 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172587, domain null
,10-26 16:56:56.209   931  5818 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172587 seconds
,10-26 16:56:56.211   931  5818 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-26 16:56:56.226   931  5819 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 16:56:56.227   931  5818 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-26 16:56:56.230   508   927 D CommandListener: Setting iface cfg
,10-26 16:56:56.234   931  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 16:56:56.238   931  5818 D DhcpClient: Scheduling renewal in 86399s
,10-26 16:56:56.253   931  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
10-26 16:56:56.254   931  2971 D WifiConfigStore: No blacklist allowed without epno enabled
,10-26 16:56:56.257   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,10-26 16:56:56.263   931  2973 D ConnectivityService: Adding iface wlan0 to network 101
10-26 16:56:56.267   931  2971 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 16:56:56.313   931  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-26 16:56:56.313   931  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-26 16:56:56.316   931  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-26 16:56:56.318   931  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-26 16:56:56.320   931  2973 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-26 16:56:56.325   931  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-26 16:56:56.330   931  2973 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-26 16:56:56.330   931  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,10-26 16:56:56.330   931  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-26 16:56:56.330   931  2971 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-26 16:56:56.330   931  2973 D ConnectivityService:    accepting network in place of null
10-26 16:56:56.330   931  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 16:56:56.331   931  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 16:56:56.344   931  5817 D NetlinkSocketObserver: NeighborEvent{elapsedMs=253111, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 16:56:56.352   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 16:56:56.370   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 16:56:56.373   931  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-26 16:56:56.373  3702  3871 W QCNEJ   : |CORE| network available: 101
10-26 16:56:56.373   931  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 16:56:56.374   931  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-26 16:56:56.375   931   948 D Tethering: MasterInitialState.processMessage what=3
10-26 16:56:56.376  3702  3871 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-26 16:56:56.378  3702  3871 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 16:56:56.378  3702  3871 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 16:56:56.380  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:56.380  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:56.380  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:56.380  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:56:56.382  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:56.382  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:56.383  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.383  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:56:56.385  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:56:56.386  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:56:56.386  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.386  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:56:56.390  5043  5056 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 16:56:56.390  5043  5056 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 16:56:56.391  5043  5056 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-26 16:56:56.391  5043  5056 E SarControlService: no key has been found,reset the power
10-26 16:56:56.391  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 16:56:56.391  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 16:56:56.391  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 16:56:56.391  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 16:56:56.391  5069  5069 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 16:56:56.393  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 16:56:56.393  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 16:56:56.393  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 16:56:56.393  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 16:56:56.394  5069  5069 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 16:56:56.396  4025  4025 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 16:56:56.399  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000ec03000000000000ffffffff]
10-26 16:56:56.399  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 16:56:56.399  5069  5083 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-26 16:56:56.399  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000ed03000000000000ffffffff]
10-26 16:56:56.399  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 16:56:56.399  5069  5083 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-26 16:56:56.400  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:56:56.400  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 16:56:56.401  4025  4025 D SystemUpdateService: onCreate
10-26 16:56:56.402  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:56:56.403  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 16:56:56.405  4025  4025 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-26 16:56:56.415  4025  4025 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 16:56:56.423  4025  5386 I iu.UploadsManager: num queued entries: 0
10-26 16:56:56.424  4025  5386 I iu.UploadsManager: num updated entries: 0
10-26 16:56:56.424  4025  5386 I iu.SyncManager: NEXT; no task
10-26 16:56:56.427  4025  4025 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 16:56:56.429  4025  4025 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 16:56:56.430   931  5816 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-26 16:56:56.431  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-26 16:56:56.435  5748  5748 D SprintDMHelper: simOperator: 
10-26 16:56:56.436  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
10-26 16:56:56.444  4025  5829 I SystemUpdateService: active receiver: enabled
,10-26 16:56:56.470  4025  5829 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 16:56:56.477  4025  5829 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-26 16:56:56.477  4025  5829 I SystemUpdateService: now status is 0 (complete)
10-26 16:56:56.477  4025  5829 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 16:56:56.477  4025  5829 I SystemUpdateService: file has been verified
10-26 16:56:56.477  4025  5829 I SystemUpdateService: OTA package size = 21989297
,10-26 16:56:56.483  4025  5829 I SystemUpdateService: showing system update notification
,10-26 16:56:56.493  4025  4025 D SystemUpdateService: onDestroy
,10-26 16:56:56.503   931  5816 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 20:56:56 GMT], X-Android-Received-Millis=[1477515416502], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477515416466]}
,10-26 16:56:56.503   931  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-26 16:56:56.503   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-26 16:56:56.503   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-26 16:56:56.505   931  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-26 16:56:56.562  4404  5833 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-26 16:56:56.571   931  3188 D WifiService: setWifiEnabled: false pid=5622, uid=10077
,10-26 16:56:56.571   931  3188 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 16:56:56.573   931  2971 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-26 16:56:56.573   931  2971 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-26 16:56:56.573   931  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 16:56:56.573   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 16:56:56.581   931  5818 D DhcpClient: Clearing IP address
10-26 16:56:56.581   508   927 D CommandListener: Clearing all IP addresses on wlan0
,10-26 16:56:56.583   508   927 D CommandListener: Setting iface cfg
,10-26 16:56:56.584  3569  5839 V NativeCrypto: Read error: ssl=0x7f8654c000: I/O error during system call, Connection timed out
10-26 16:56:56.584  3569  5839 V NativeCrypto: SSL shutdown failed: ssl=0x7f8654c000: I/O error during system call, Broken pipe
,10-26 16:56:56.590   931  3887 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
10-26 16:56:56.590   931  5816 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
10-26 16:56:56.591   931  5816 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-26 16:56:56.595   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-26 16:56:56.596   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,10-26 16:56:56.599   534   534 E Parcel  : Reading a NULL string not supported here.
,10-26 16:56:56.601   931   931 D RttService: SCAN_AVAILABLE : 1
10-26 16:56:56.602   931  3047 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-26 16:56:56.603   931  5816 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,10-26 16:56:56.605   931  5819 D DhcpClient: Receive thread stopped
,10-26 16:56:56.606   931  2973 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
10-26 16:56:56.607   931  2971 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
10-26 16:56:56.608  3702  3871 W QCNEJ   : |CORE| network lost: 101
10-26 16:56:56.608  3702  3871 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-26 16:56:56.611   931  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-26 16:56:56.626   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 16:56:56.647   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 16:56:56.647   508   927 D CommandListener: Clearing all IP addresses on wlan0
10-26 16:56:56.647   931  2973 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-26 16:56:56.647   931  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-26 16:56:56.649   931   948 D Tethering: MasterInitialState.processMessage what=3
10-26 16:56:56.653   931  2971 D DhcpClient: doQuit
10-26 16:56:56.654   931  2971 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-26 16:56:56.654   931  5818 D DhcpClient: onQuitting
10-26 16:56:56.654  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:56.654  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:56:56.654  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.654  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:56.656  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:56.656  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:56.656  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.656  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:56.656  5813  5813 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-26 16:56:56.657  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:56.657  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:56.657  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.658  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:56:56.658  5043  5056 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 16:56:56.658  5043  5056 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 16:56:56.659  5043  5056 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-26 16:56:56.659  5043  5056 E SarControlService: no key has been found,reset the power
10-26 16:56:56.659  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 16:56:56.659  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 16:56:56.660  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 16:56:56.661  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 16:56:56.661  5069  5069 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 16:56:56.662  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:56.662  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:56.662  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.663  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:56.663  4025  4025 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-26 16:56:56.663  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:56:56.663  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:56:56.663  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:56:56.663  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:56:56.664  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 16:56:56.664  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 16:56:56.664  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-26 16:56:56.664  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:56.665  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 16:56:56.665  5069  5069 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 16:56:56.668  4025  4025 D SystemUpdateService: onCreate
10-26 16:56:56.672  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000ee03000000000000ffffffff]
10-26 16:56:56.672  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 16:56:56.672  5069  5083 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
10-26 16:56:56.672  5813  5813 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-26 16:56:56.673  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:56:56.673  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 16:56:56.673  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000ef03000000000000ffffffff]
10-26 16:56:56.673  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 16:56:56.673  5069  5083 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
10-26 16:56:56.674  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:56:56.674  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 16:56:56.675  4025  4025 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-26 16:56:56.678  5813  5813 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-26 16:56:56.678  4025  5849 I SystemUpdateService: active receiver: enabled
10-26 16:56:56.684  4025  4025 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-26 16:56:56.688  4025  5386 I iu.UploadsManager: num queued entries: 0
10-26 16:56:56.689  4025  5386 I iu.UploadsManager: num updated entries: 0
10-26 16:56:56.690  4025  5849 I SystemUpdateService: Already downloaded, skipping offpeak checks.
10-26 16:56:56.692  4025  4025 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-26 16:56:56.694  4025  4025 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 16:56:56.695  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
10-26 16:56:56.699  5748  5748 D SprintDMHelper: simOperator: 
10-26 16:56:56.699  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 16:56:56.706   508   927 E Netd    : netlink response contains error (No such file or directory)
10-26 16:56:56.707   931  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-26 16:56:56.710  4025  5386 I iu.SyncManager: NEXT; no task
10-26 16:56:56.711  4025  5849 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-26 16:56:56.711  4025  5849 I SystemUpdateService: now status is 0 (complete)
10-26 16:56:56.711  4025  5849 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 16:56:56.711  4025  5849 I SystemUpdateService: file has been verified
10-26 16:56:56.711  4025  5849 I SystemUpdateService: OTA package size = 21989297
10-26 16:56:56.714  4404  5853 I Babel   : connection state changed from CONNECTED to DISCONNECTED
10-26 16:56:56.716  5813  5813 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-26 16:56:56.729  5813  5813 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
10-26 16:56:56.730  4025  5849 I SystemUpdateService: showing system update notification
10-26 16:56:56.738  4025  4025 D SystemUpdateService: onDestroy
,10-26 16:56:56.831   931  2971 D wifi    : In wifi stop Hal
,10-26 16:56:56.831   931  2971 D wifi    : halHandle = 0x7f85b6de00, mVM = 0x7fa21cd140, mCls = 0x18f6
10-26 16:56:56.832   931  5812 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-26 16:56:56.833   931  5812 D WifiHAL : Got a signal to exit!!!
10-26 16:56:56.833   931  5812 I WifiHAL : Exit wifi_event_loop
10-26 16:56:56.833  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:56.834   931  2971 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-26 16:56:56.834   931  2971 E WifiHAL : Event processing terminated
10-26 16:56:56.834   931  2971 D wifi    : In wifi cleaned up handler
,10-26 16:56:56.834   931  2971 I WifiHAL : Internal cleanup completed
10-26 16:56:56.834  3875  4177 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-26 16:56:56.834  4404  4404 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 16:56:56.836  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:56:56.838  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:56:56.857   931  5812 D wifi    : set interface wlan0 flags (DOWN)
,10-26 16:56:56.857   931  2971 D WifiNative-HAL: HAL event thread stopped successfully
,10-26 16:56:57.062   931   948 D Tethering: InitialState.processMessage what=4
,10-26 16:56:57.068   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-26 16:56:57.375   931  2973 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-26 16:56:58.406   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:56:59.407   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:00.408   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:01.411   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:01.611   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a1dd76e:true
,10-26 16:57:01.612  5734  5734 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 16:57:01.619  5734  5734 I bt_bluedroid: init
,10-26 16:57:01.620  5734  5855 I BluetoothAdapterState: Entering OffState
,10-26 16:57:01.625  5734  5856 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-26 16:57:01.625  5734  5856 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 16:57:01.625  5734  5856 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,10-26 16:57:01.626  5734  5856 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-26 16:57:01.627  5734  5734 I bt_bluedroid: get_profile_interface socket
,10-26 16:57:01.632  5734  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-26 16:57:01.632  5734  5734 I bt_bluedroid: get_profile_interface sdp
,10-26 16:57:01.637  5734  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 16:57:01.642  5734  5745 I bt_bluedroid: config_hci_snoop_log
,10-26 16:57:01.644   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 16:57:01.652  5734  5855 D BluetoothAdapterState: Current state: OFF, message: 0
,10-26 16:57:01.652  5734  5855 D BluetoothAdapterProperties: Setting state to 14
10-26 16:57:01.652  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-26 16:57:01.655  5734  5855 D BluetoothBondStateMachine: make
,10-26 16:57:01.658  5734  5860 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 16:57:01.662  5734  5855 I BluetoothAdapterState: Entering PendingCommandState
,10-26 16:57:01.664  5734  5734 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-26 16:57:01.667  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:01.668  5734  5734 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-26 16:57:01.669  5734  5734 D BtGatt.GattService: Received start request. Starting profile...
10-26 16:57:01.669  5734  5734 D BtGatt.GattService: start()
10-26 16:57:01.670  5734  5734 I bt_bluedroid: get_profile_interface gatt
,10-26 16:57:01.671  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:01.671  5734  5734 D BtGatt.AdvertiseManager: advertise manager created
,10-26 16:57:01.679  5734  5734 V BluetoothAdapterState: isTurningOff()=false
,10-26 16:57:01.680  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:01.680  5734  5734 V BluetoothAdapterState: isBleTurningOn()=true
10-26 16:57:01.680  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:01.680  5734  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 16:57:01.682  5734  5855 I bt_bluedroid: bt_bluedroid
,10-26 16:57:01.682  5734  5856 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-26 16:57:01.682  5734  5856 I bt_hci  : start_up
,10-26 16:57:01.689  5734  5856 I bt_vendor: alloc value 0xf3bec871
,10-26 16:57:01.689  5734  5856 I bt_vendor: init
10-26 16:57:01.689  5734  5856 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 16:57:01.690  5734  5856 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 16:57:01.803  5734  5856 D bt_hci  : start_up starting async portion
,10-26 16:57:01.803  5734  5863 I bt_hci  : event_finish_startup
,10-26 16:57:01.806  5734  5863 I bt_hci_h4: hal_open
10-26 16:57:01.806  5734  5863 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-26 16:57:01.808  5734  5863 I bt_userial_vendor: device fd = 54 open
,10-26 16:57:01.803  5864  5864 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 16:57:01.823  5734  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 16:57:01.825  5734  5863 D bt_hwcfg: Chipset BCM4358A3
,10-26 16:57:01.825  5734  5863 D bt_hwcfg: Target name = [BCM4358A3]
10-26 16:57:01.825  5734  5863 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 16:57:02.222  5734  5863 I bt_hwcfg: bt vendor lib: set UART baud 115200
10-26 16:57:02.222  5734  5863 D bt_hwcfg: Settlement delay -- 100 ms
,10-26 16:57:02.223  5734  5863 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 16:57:02.358  5734  5863 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 16:57:02.358  5734  5863 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-26 16:57:02.361  5734  5863 I bt_hwcfg: vendor lib fwcfg completed
10-26 16:57:02.361  5734  5863 I bt_vendor: firmware callback
10-26 16:57:02.361  5734  5863 I bt_hci  : firmware_config_callback
,10-26 16:57:02.368  5734  5868 I bt_btu  : btu_task pending for preload complete event
,10-26 16:57:02.369  5734  5868 I bt_btu_task: Bluetooth chip preload is complete
10-26 16:57:02.369  5734  5868 I bt_btu  : btu_task received preload complete event
,10-26 16:57:02.375  5734  5868 I         : BTE_InitTraceLevels -- TRC_HCI
10-26 16:57:02.375  5734  5868 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-26 16:57:02.375  5734  5868 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-26 16:57:02.375  5734  5868 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-26 16:57:02.375  5734  5868 I         : BTE_InitTraceLevels -- TRC_AVRC
10-26 16:57:02.375  5734  5868 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 16:57:02.375  5734  5868 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_GAP
,10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_PAN
10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_SDP
10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_SMP
,10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_BTAPP
10-26 16:57:02.376  5734  5868 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 16:57:02.412   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:02.458  5734  5868 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b6a549
10-26 16:57:02.458  5734  5868 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b6a549 
,10-26 16:57:02.478  5734  5859 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 16:57:02.480  5734  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 16:57:02.480  5734  5859 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-26 16:57:02.485  5734  5859 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 16:57:02.488  5734  5859 D BluetoothAdapterProperties: Scan Mode:20
,10-26 16:57:02.488  5734  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 16:57:02.489  5734  5859 D bt_hci  : do_postload posting postload work item
10-26 16:57:02.489  5734  5863 I bt_hci  : event_postload
10-26 16:57:02.489  5734  5863 I bt_vendor: sco_config_cb
10-26 16:57:02.489  5734  5863 I bt_hci  : sco_config_callback postload finished.
10-26 16:57:02.493  5734  5859 D bt_bte_conf: Device ID record 1 : primary
,10-26 16:57:02.493  5734  5859 D bt_bte_conf:   vendorId            = 000f
10-26 16:57:02.493  5734  5859 D bt_bte_conf:   vendorIdSource      = 0001
10-26 16:57:02.493  5734  5859 D bt_bte_conf:   product             = 1200
10-26 16:57:02.493  5734  5859 D bt_bte_conf:   version             = 1436
10-26 16:57:02.493  5734  5859 D bt_bte_conf:   clientExecutableURL = 
10-26 16:57:02.493  5734  5859 D bt_bte_conf:   serviceDescription  = 
10-26 16:57:02.493  5734  5859 D bt_bte_conf:   documentationURL    = 
,10-26 16:57:02.494  5734  5859 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 16:57:02.494  5734  5856 D bt_stack_manager: event_start_up_stack finished
10-26 16:57:02.495  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:02.495  5734  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 16:57:02.495  5734  5855 D BluetoothAdapterProperties: Setting state to 15
10-26 16:57:02.496  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 16:57:02.498  5734  5863 I bt_vendor: low_power_mode_cb
10-26 16:57:02.498  5734  5855 I BluetoothAdapterState: Entering BleOnState
,10-26 16:57:02.501  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:02.502  5734  5855 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-26 16:57:02.502  5734  5855 D BluetoothAdapterProperties: Setting state to 11
10-26 16:57:02.502  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-26 16:57:02.503  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:02.506  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:02.507  5734  5734 D HeadsetService: Received start request. Starting profile...
10-26 16:57:02.509  5734  5734 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-26 16:57:02.510  5734  5734 D HeadsetStateMachine: make
,10-26 16:57:02.515  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:02.517  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:02.520  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:02.522  5734  5855 I BluetoothAdapterState: Entering PendingCommandState
,10-26 16:57:02.526  5734  5734 D HeadsetStateMachine: max_hf_connections = 1
,10-26 16:57:02.526  5734  5734 I bt_bluedroid: get_profile_interface handsfree
10-26 16:57:02.526  5734  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 16:57:02.527  5734  5859 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-26 16:57:02.529  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:02.530  5734  5734 D A2dpService: Received start request. Starting profile...
,10-26 16:57:02.530  5734  5734 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-26 16:57:02.531  5734  5734 I bt_bluedroid: get_profile_interface avrcp
,10-26 16:57:02.536  5734  5734 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-26 16:57:02.537  5734  5734 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 16:57:02.537  5734  5734 D A2dpStateMachine: make
10-26 16:57:02.538  5734  5734 I bt_bluedroid: get_profile_interface a2dp
,10-26 16:57:02.538  5734  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-26 16:57:02.540  5734  5876 D A2dpStateMachine: Enter Disconnected: -2
,10-26 16:57:02.540  5734  5734 I BluetoothHidServiceJni: classInitNative: succeeds
10-26 16:57:02.541  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:02.542  5675  5675 D BluetoothInputDevice: Proxy object connected
10-26 16:57:02.543  5675  5675 D HidProfile: Bluetooth service connected
,10-26 16:57:02.544  5734  5734 D HidService: Received start request. Starting profile...
10-26 16:57:02.544  5734  5734 I bt_bluedroid: get_profile_interface hidhost
10-26 16:57:02.544  5734  5734 D HidService: setHidService(): set to: null
10-26 16:57:02.545  5734  5859 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b4b56d
10-26 16:57:02.545  5734  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 16:57:02.545  5734  5734 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 16:57:02.546  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:02.546  5734  5734 D HealthService: Received start request. Starting profile...
,10-26 16:57:02.548  5734  5734 I bt_bluedroid: get_profile_interface health
,10-26 16:57:02.548  5734  5734 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-26 16:57:02.549  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:02.550  5734  5734 D PanService: Received start request. Starting profile...
,10-26 16:57:02.550  5675  5675 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 16:57:02.550  5734  5734 D BluetoothPanServiceJni: initializeNative(L110): pan
10-26 16:57:02.550  5734  5734 I bt_bluedroid: get_profile_interface pan
10-26 16:57:02.551  5675  5675 D PanProfile: Bluetooth service connected
10-26 16:57:02.551  5734  5859 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-26 16:57:02.554  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:02.555  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 16:57:02.555  5734  5734 D BluetoothMapService: Received start request. Starting profile...
,10-26 16:57:02.555  5734  5734 D BluetoothMapService: start()
10-26 16:57:02.555  5675  5675 D BluetoothMap: Proxy object connected
10-26 16:57:02.556  5675  5675 D MapProfile: Bluetooth service connected
10-26 16:57:02.556  5675  5675 D BluetoothMap: getConnectedDevices()
10-26 16:57:02.557  5675  5675 D BluetoothMap: Bluetooth is Not enabled
10-26 16:57:02.558  5734  5734 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
10-26 16:57:02.559  5734  5734 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-26 16:57:02.559  5734  5734 D BluetoothMapAppObserver: createReceiver()
10-26 16:57:02.560  5734  5734 D BluetoothMapAppObserver: initObservers()
10-26 16:57:02.560  5734  5734 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 16:57:02.566  5734  5734 V SapService: SapBinder()
,10-26 16:57:02.566  5734  5734 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:02.567  5734  5734 D SapService: Received start request. Starting profile...
10-26 16:57:02.567  5734  5734 V SapService: start()
,10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isTurningOff()=false
,10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:02.570  5734  5874 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isTurningOn()=true
,10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:02.570  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:02.571  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:02.572  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:02.572  5734  5734 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:02.572  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:02.572  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 16:57:02.572  5734  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 16:57:02.572  5734  5855 D BluetoothAdapterProperties: ScanMode =  20
10-26 16:57:02.572  5734  5855 D BluetoothAdapterProperties: State =  11
10-26 16:57:02.573  5734  5855 D BluetoothAdapterProperties: Setting state to 12
10-26 16:57:02.573  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-26 16:57:02.573  5734  5855 I BluetoothAdapterState: Entering OnState
10-26 16:57:02.573  3111  3124 D BluetoothMap: onBluetoothStateChange: up=true
,10-26 16:57:02.575  3111  3111 D BluetoothMap: Proxy object connected
10-26 16:57:02.575  3111  3111 D MapProfile: Bluetooth service connected
10-26 16:57:02.576  3111  3111 D BluetoothMap: getConnectedDevices()
10-26 16:57:02.576  3722  3751 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 16:57:02.577  5734  5859 D BluetoothAdapterProperties: Scan Mode:21
10-26 16:57:02.577  5734  5859 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 16:57:02.577  3111  3125 D BluetoothPan: onBluetoothStateChange on: true
,10-26 16:57:02.577  5622  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 16:57:02.579  3111  3111 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 16:57:02.579  5675  5688 D BluetoothMap: onBluetoothStateChange: up=true
10-26 16:57:02.579  3111  3111 D PanProfile: Bluetooth service connected
10-26 16:57:02.580   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 16:57:02.580  5675  5687 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:02.580  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:57:02.581   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 16:57:02.581   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 16:57:02.581  5675  5688 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 16:57:02.582  3111  3124 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 16:57:02.582   931   931 D BluetoothA2dp: Proxy object connected
10-26 16:57:02.582  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:02.583  3111  3125 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 16:57:02.584  3111  3945 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:02.586  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:57:02.586  5734  5734 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 16:57:02.586  3111  3111 D BluetoothA2dp: Proxy object connected
10-26 16:57:02.586  5734  5734 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 16:57:02.586   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 16:57:02.587  5675  5687 D BluetoothPan: onBluetoothStateChange on: true
10-26 16:57:02.588  3111  3125 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-26 16:57:02.588  5734  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 16:57:02.589  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:57:02.590  3111  3111 D BluetoothInputDevice: Proxy object connected
10-26 16:57:02.590  3111  3111 D HidProfile: Bluetooth service connected
,10-26 16:57:02.591   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:02.594  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:02.594  5734  5734 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 16:57:02.594  5675  5675 D LocalBluetoothProfileManager: Adding local A2DP profile
,10-26 16:57:02.596  5734  5734 D ObexServerSockets: Succeed to create listening sockets 
10-26 16:57:02.596  5734  5734 D ObexServerSockets0: startAccept()
10-26 16:57:02.596  5734  5734 D ObexServerSockets0: prepareForNewConnect()
10-26 16:57:02.598  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:02.598  5734  5734 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 16:57:02.598  5734  5734 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 16:57:02.598  5675  5675 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-26 16:57:02.598  5622  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 16:57:02.599  5734  5734 D BluetoothMapService: onReceive
10-26 16:57:02.599  5734  5884 D ObexServerSockets0: Accepting socket connection...
10-26 16:57:02.599  5734  5734 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 16:57:02.599  5734  5885 D ObexServerSockets0: Accepting socket connection...
,10-26 16:57:02.600  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:02.601  5734  5734 D BluetoothMapService: STATE_ON
10-26 16:57:02.603  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:02.604  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:02.604  5734  5886 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 16:57:02.606  5734  5886 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-26 16:57:02.606  5734  5886 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-26 16:57:02.611  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 16:57:02.613  5675  5675 D BluetoothA2dp: Proxy object connected
,10-26 16:57:02.618  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-26 16:57:02.626  3111  3111 D BluetoothPbap: Proxy object connected
,10-26 16:57:02.627  3111  3111 D PbapServerProfile: Bluetooth service connected
,10-26 16:57:02.627  5734  5734 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 16:57:02.627  5734  5734 D ObexServerSockets0: prepareForNewConnect()
,10-26 16:57:02.629  5675  5675 D DockEventReceiver: finishStartingService: stopping service
,10-26 16:57:02.630  5675  5675 D BluetoothPbap: Proxy object connected
,10-26 16:57:02.630  5675  5675 D PbapServerProfile: Bluetooth service connected
,10-26 16:57:02.635  5734  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 16:57:02.647  5734  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 16:57:02.648  5734  5894 I BtOppRfcommListener: Accept thread started.
,10-26 16:57:02.677   931   931 D BluetoothHeadset: Proxy object connected
,10-26 16:57:02.678  3722  4121 D BluetoothHeadset: Proxy object connected
10-26 16:57:02.678  3111  3124 D BluetoothHeadset: Proxy object connected
10-26 16:57:02.678  3111  3111 D HeadsetProfile: Bluetooth service connected
10-26 16:57:02.678   931   931 D BluetoothHeadset: Proxy object connected
10-26 16:57:02.678   931   931 D BluetoothHeadset: Proxy object connected
,10-26 16:57:02.680   931   948 D BluetoothHeadset: Proxy object connected
,10-26 16:57:02.682   931   948 D BluetoothHeadset: Proxy object connected
,10-26 16:57:02.683  3111  3125 D BluetoothHeadset: Proxy object connected
,10-26 16:57:02.683  3111  3111 D HeadsetProfile: Bluetooth service connected
,10-26 16:57:02.687   931   948 D BluetoothHeadset: Proxy object connected
,10-26 16:57:02.703  5675  5687 D BluetoothHeadset: Proxy object connected
,10-26 16:57:02.704  5675  5675 D HeadsetProfile: Bluetooth service connected
,10-26 16:57:03.412   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-26 16:57:04.337   931  2973 D ConnectivityService: handlePromptUnvalidated 101
,10-26 16:57:06.583  5734  5855 D BluetoothAdapterState: Current state: ON, message: 23
,10-26 16:57:06.584  5734  5855 D BluetoothAdapterProperties: Setting state to 13
,10-26 16:57:06.584  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-26 16:57:06.585  5734  5855 D BluetoothAdapterProperties: onBluetoothDisable()
,10-26 16:57:06.592  5734  5855 I BluetoothAdapterState: Entering PendingCommandState
,10-26 16:57:06.594  5734  5859 D BluetoothAdapterProperties: Scan Mode:20
10-26 16:57:06.596  5734  5734 D BluetoothMapService: onReceive
10-26 16:57:06.597  5734  5734 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 16:57:06.597  5734  5734 D BluetoothMapService: STATE_TURNING_OFF
10-26 16:57:06.597  5734  5734 D BluetoothMapService: MAP Service closeService in
,10-26 16:57:06.597  5734  5734 D BluetoothMapMasInstance0: MAP Service shutdown
10-26 16:57:06.597  5734  5734 D ObexServerSockets0: shutdown(block = true)
10-26 16:57:06.598  5734  5734 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 16:57:06.598  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-26 16:57:06.598  5734  5734 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-26 16:57:06.599  5734  5885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-26 16:57:06.599  5734  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-26 16:57:06.599  5734  5884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,10-26 16:57:06.599  5734  5870 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,10-26 16:57:06.601  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:06.601  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:06.601  5734  5734 I BtOppRfcommListener: stopping Accept Thread
10-26 16:57:06.602  5734  5894 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-26 16:57:06.602  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:57:06.602  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:06.603  5734  5894 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-26 16:57:06.605  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:06.605  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:06.606  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:57:06.606  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:06.608  5675  5675 D DockEventReceiver: finishStartingService: stopping service
10-26 16:57:06.611  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:06.611  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:57:06.611  5734  5734 D HeadsetService: Received stop request...Stopping profile...
10-26 16:57:06.611  5622  5622 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-26 16:57:06.612  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:06.614  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:06.614   931   931 D BluetoothHeadset: Proxy object disconnected
10-26 16:57:06.615  3722  3769 D BluetoothHeadset: Proxy object disconnected
10-26 16:57:06.616  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:06.615  5675  5688 D BluetoothHeadset: Proxy object disconnected
10-26 16:57:06.617  3111  3945 D BluetoothHeadset: Proxy object disconnected
10-26 16:57:06.617   931   931 D BluetoothHeadset: Proxy object disconnected
10-26 16:57:06.617   931   931 D BluetoothHeadset: Proxy object disconnected
10-26 16:57:06.618  5675  5675 D HeadsetProfile: Bluetooth service disconnected
10-26 16:57:06.618  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:06.618  5734  5734 D A2dpService: Received stop request...Stopping profile...
10-26 16:57:06.619  5734  5876 D A2dpStateMachine: Exit Disconnected: -1
10-26 16:57:06.620  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 16:57:06.620   931   931 D BluetoothA2dp: Proxy object disconnected
10-26 16:57:06.621  5675  5675 D BluetoothA2dp: Proxy object disconnected
,10-26 16:57:06.622  5734  5734 D HidService: Received stop request...Stopping profile...
,10-26 16:57:06.622  5734  5734 D HidService: Stopping Bluetooth HidService
10-26 16:57:06.622  3111  3111 D HeadsetProfile: Bluetooth service disconnected
10-26 16:57:06.623  3111  3111 D BluetoothA2dp: Proxy object disconnected
10-26 16:57:06.623  3111  3111 D BluetoothInputDevice: Proxy object disconnected
10-26 16:57:06.623  3111  3111 D HidProfile: Bluetooth service disconnected
10-26 16:57:06.623  5675  5675 D BluetoothInputDevice: Proxy object disconnected
10-26 16:57:06.623  5675  5675 D HidProfile: Bluetooth service disconnected
10-26 16:57:06.624  5734  5734 D HealthService: Received stop request...Stopping profile...
,10-26 16:57:06.625  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-26 16:57:06.626  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:06.626  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:06.626  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:06.626  5734  5734 D PanService: Received stop request...Stopping profile...
10-26 16:57:06.627  3111  3111 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 16:57:06.627  3111  3111 D PanProfile: Bluetooth service disconnected
10-26 16:57:06.628  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-26 16:57:06.628  5675  5675 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-26 16:57:06.628  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:06.628  5675  5675 D PanProfile: Bluetooth service disconnected
10-26 16:57:06.628  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:06.628  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 16:57:06.629  5734  5734 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-26 16:57:06.629  5734  5734 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-26 16:57:06.630  5734  5868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:57:06.630  5734  5868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:57:06.630  5734  5868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:57:06.630  5734  5734 D BluetoothMapService: Received stop request...Stopping profile...
10-26 16:57:06.630  5734  5734 D BluetoothMapService: stop()
10-26 16:57:06.631  5734  5734 D BluetoothMapAppObserver: deinitObservers()
10-26 16:57:06.631  5734  5734 D BluetoothMapAppObserver: removeReceiver()
10-26 16:57:06.631  5734  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-26 16:57:06.631  5734  5859 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-26 16:57:06.633  3111  3111 D BluetoothMap: Proxy object disconnected
10-26 16:57:06.633  3111  3111 D MapProfile: Bluetooth service disconnected
10-26 16:57:06.633  5675  5675 D BluetoothMap: Proxy object disconnected
10-26 16:57:06.633  5675  5675 D MapProfile: Bluetooth service disconnected
10-26 16:57:06.636  5675  5675 D BluetoothPbap: Proxy object disconnected
10-26 16:57:06.636  5675  5675 D PbapServerProfile: Bluetooth service disconnected
10-26 16:57:06.637  5734  5734 V BluetoothAdapterState: isTurningOff()=true
,10-26 16:57:06.637  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:06.637  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:06.637  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
,10-26 16:57:06.638  5734  5868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 16:57:06.638  5734  5868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-26 16:57:06.638  5734  5734 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-26 16:57:06.638  5734  5734 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-26 16:57:06.638  5734  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 16:57:06.638  5734  5868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 16:57:06.638  5734  5868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 16:57:06.638  5734  5868 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-26 16:57:06.638  5734  5859 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-26 16:57:06.638  5734  5868 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-26 16:57:06.639  5734  5734 D SapService: Received stop request...Stopping profile...
10-26 16:57:06.639  5734  5734 V SapService: stop()
,10-26 16:57:06.637  3111  3111 D BluetoothPbap: Proxy object disconnected
10-26 16:57:06.648  3111  3111 D PbapServerProfile: Bluetooth service disconnected
10-26 16:57:06.648  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-26 16:57:06.648  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:06.648  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:06.648  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:06.649  5734  5734 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-26 16:57:06.649  5734  5859 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-26 16:57:06.649  5734  5734 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-26 16:57:06.649  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-26 16:57:06.649  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:06.649  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:06.649  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:06.650  5734  5734 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-26 16:57:06.650  5734  5734 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-26 16:57:06.651  5734  5734 D BluetoothMapService: MAP Service closeService in
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:06.651  5734  5734 D BluetoothMapService: cleanup()
,10-26 16:57:06.651  5734  5734 D BluetoothMapService: MAP Service closeService in
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isTurningOff()=true
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isTurningOn()=false
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:06.651  5734  5734 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:06.652  5734  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-26 16:57:06.652  5734  5855 D BluetoothAdapterProperties: Setting state to 15
10-26 16:57:06.652  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-26 16:57:06.653  3111  3125 D BluetoothMap: onBluetoothStateChange: up=false
10-26 16:57:06.654  5734  5855 I BluetoothAdapterState: Entering BleOnState
10-26 16:57:06.655  3722  3751 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:57:06.655  3111  3124 D BluetoothPan: onBluetoothStateChange on: false
,10-26 16:57:06.656  5675  5687 D BluetoothMap: onBluetoothStateChange: up=false
,10-26 16:57:06.656   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 16:57:06.657  5675  5688 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 16:57:06.657  5675  5687 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 16:57:06.658   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
10-26 16:57:06.658   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:57:06.658  5675  5688 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-26 16:57:06.659  3111  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-26 16:57:06.659  3111  3125 D BluetoothPbap: onBluetoothStateChange: up=false
10-26 16:57:06.660  5675  5687 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 16:57:06.660  3111  3124 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-26 16:57:06.661   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-26 16:57:06.661  5675  5688 D BluetoothPan: onBluetoothStateChange on: false
10-26 16:57:06.662  3111  3945 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-26 16:57:06.668  5734  5855 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-26 16:57:06.668  5734  5855 D BluetoothAdapterProperties: Setting state to 16
,10-26 16:57:06.668  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-26 16:57:06.668  5734  5855 D BluetoothAdapterProperties: onBleDisable
10-26 16:57:06.668  5734  5855 I BluetoothAdapterState: Entering PendingCommandState
10-26 16:57:06.668  5734  5856 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-26 16:57:06.670  5734  5868 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,10-26 16:57:06.670  5734  5868 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-26 16:57:06.670  5734  5859 D BluetoothAdapterProperties: Scan Mode:20
10-26 16:57:06.671  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:06.671  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 16:57:06.674  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:06.677  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:06.677  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 16:57:06.680  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:06.682  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:06.682  5675  5675 D DockEventReceiver: finishStartingService: stopping service
,10-26 16:57:06.683  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:06.881  5734  5859 I bt_hci  : shut_down
,10-26 16:57:06.886  5734  5863 D bt_hwcfg: hw_epilog_process
,10-26 16:57:06.887  5734  5863 I bt_vendor: low_power_mode_cb
,10-26 16:57:06.890  5734  5863 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-26 16:57:06.890  5734  5863 I bt_vendor: epilog_cb
,10-26 16:57:06.890  5734  5863 I bt_hci  : epilog_finished_callback
,10-26 16:57:06.895  5734  5859 I bt_hci_h4: hal_close
10-26 16:57:06.896  5734  5859 I bt_userial_vendor: device fd = 54 close
,10-26 16:57:07.014  5734  5856 D bt_stack_manager: event_shut_down_stack finished.
,10-26 16:57:07.014  5734  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-26 16:57:07.019  5734  5855 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-26 16:57:07.019  5734  5734 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-26 16:57:07.020  5734  5734 D BtGatt.GattService: Received stop request...Stopping profile...
,10-26 16:57:07.020  5734  5734 D BtGatt.GattService: stop()
10-26 16:57:07.021  5734  5734 D BtGatt.AdvertiseManager: advertise clients cleared
,10-26 16:57:07.024  5734  5734 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:07.025  5734  5734 V BluetoothAdapterState: isTurningOn()=false
,10-26 16:57:07.025  5734  5734 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:07.025  5734  5734 V BluetoothAdapterState: isBleTurningOff()=true
10-26 16:57:07.025  5734  5855 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-26 16:57:07.026  5734  5855 D BluetoothAdapterProperties: Setting state to 10
,10-26 16:57:07.027  5734  5855 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-26 16:57:07.030  5734  5855 I BluetoothAdapterState: Entering OffState
,10-26 16:57:07.032   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-26 16:57:07.042  5734  5734 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-26 16:57:07.042  5734  5734 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-26 16:57:07.042  5734  5734 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-26 16:57:07.045  5734  5856 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-26 16:57:07.052  5734  5734 I art     : System.exit called, status: 0
,10-26 16:57:07.052  5734  5734 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-26 16:57:07.084   931  3188 I ActivityManager: Process com.android.bluetooth (pid 5734) has died
,10-26 16:57:11.581  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 16:57:11.582  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:11.586  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:11.587  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@65d65b1 removed from the list
10-26 16:57:11.587  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:57:11.587  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:11.587  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:57:11.589  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:11.590  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b594617 added. We now have 4 listener(s)
10-26 16:57:11.591  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:11.593  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:57:11.593  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b594617 removed from the list
,10-26 16:57:11.594  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:57:11.594  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:11.595  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:57:11.601  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 16:57:11.601  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5280a04 added. We now have 4 listener(s)
10-26 16:57:11.601  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:57:16.610  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:16.647   931   948 I ActivityManager: Start proc 5902:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-26 16:57:16.736  5902  5902 D AdapterServiceConfig: Adding HeadsetService
,10-26 16:57:16.736  5902  5902 D AdapterServiceConfig: Adding A2dpService
,10-26 16:57:16.736  5902  5902 D AdapterServiceConfig: Adding HidService
10-26 16:57:16.736  5902  5902 D AdapterServiceConfig: Adding HealthService
10-26 16:57:16.737  5902  5902 D AdapterServiceConfig: Adding PanService
10-26 16:57:16.737  5902  5902 D AdapterServiceConfig: Adding GattService
10-26 16:57:16.737  5902  5902 D AdapterServiceConfig: Adding BluetoothMapService
10-26 16:57:16.737  5902  5902 D AdapterServiceConfig: Adding SapService
,10-26 16:57:16.749   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc641cf:true
,10-26 16:57:16.750  5902  5902 D BluetoothAdapterState: make() - Creating AdapterState
,10-26 16:57:16.753  5902  5902 I bt_bluedroid: init
,10-26 16:57:16.753  5902  5914 I BluetoothAdapterState: Entering OffState
,10-26 16:57:16.755  5902  5915 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-26 16:57:16.756  5902  5915 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-26 16:57:16.756  5902  5915 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-26 16:57:16.756  5902  5915 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-26 16:57:16.757  5902  5902 I bt_bluedroid: get_profile_interface socket
,10-26 16:57:16.758  5902  5918 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-26 16:57:16.758  5902  5902 I bt_bluedroid: get_profile_interface sdp
,10-26 16:57:16.760  5902  5918 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 16:57:16.768  5902  5913 I bt_bluedroid: config_hci_snoop_log
,10-26 16:57:16.769   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-26 16:57:16.774  5902  5914 D BluetoothAdapterState: Current state: OFF, message: 0
10-26 16:57:16.774  5902  5914 D BluetoothAdapterProperties: Setting state to 14
10-26 16:57:16.775  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-26 16:57:16.776  5902  5914 D BluetoothBondStateMachine: make
,10-26 16:57:16.779  5902  5919 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-26 16:57:16.782  5902  5914 I BluetoothAdapterState: Entering PendingCommandState
,10-26 16:57:16.783  5902  5902 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-26 16:57:16.787  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:16.787  5902  5902 D BtGatt.DebugUtils: handleDebugAction() action=null
10-26 16:57:16.788  5902  5902 D BtGatt.GattService: Received start request. Starting profile...
,10-26 16:57:16.788  5902  5902 D BtGatt.GattService: start()
10-26 16:57:16.788  5902  5902 I bt_bluedroid: get_profile_interface gatt
10-26 16:57:16.789  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:16.789  5902  5902 D BtGatt.AdvertiseManager: advertise manager created
,10-26 16:57:16.795  5902  5902 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:16.795  5902  5902 V BluetoothAdapterState: isTurningOn()=false
,10-26 16:57:16.795  5902  5902 V BluetoothAdapterState: isBleTurningOn()=true
10-26 16:57:16.795  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:16.796  5902  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-26 16:57:16.798  5902  5914 I bt_bluedroid: bt_bluedroid
,10-26 16:57:16.798  5902  5915 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-26 16:57:16.798  5902  5915 I bt_hci  : start_up
,10-26 16:57:16.804  5902  5915 I bt_vendor: alloc value 0xf3c3b871
10-26 16:57:16.804  5902  5915 I bt_vendor: init
10-26 16:57:16.804  5902  5915 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-26 16:57:16.804  5902  5915 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-26 16:57:16.913  5902  5915 D bt_hci  : start_up starting async portion
,10-26 16:57:16.913  5902  5922 I bt_hci  : event_finish_startup
,10-26 16:57:16.914  5902  5922 I bt_hci_h4: hal_open
,10-26 16:57:16.914  5902  5922 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-26 16:57:16.909  5923  5923 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 16:57:16.917  5902  5922 I bt_userial_vendor: device fd = 54 open
,10-26 16:57:16.934  5902  5922 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-26 16:57:16.938  5902  5922 D bt_hwcfg: Chipset BCM4358A3
10-26 16:57:16.938  5902  5922 D bt_hwcfg: Target name = [BCM4358A3]
,10-26 16:57:16.938  5902  5922 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-26 16:57:17.444  5902  5922 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-26 16:57:17.445  5902  5922 D bt_hwcfg: Settlement delay -- 100 ms
,10-26 16:57:17.445  5902  5922 I bt_hwcfg: Setting fw settlement delay to 100 
,10-26 16:57:17.580  5902  5922 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-26 16:57:17.581  5902  5922 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-26 16:57:17.582  5902  5922 I bt_hwcfg: vendor lib fwcfg completed
10-26 16:57:17.583  5902  5922 I bt_vendor: firmware callback
10-26 16:57:17.583  5902  5922 I bt_hci  : firmware_config_callback
,10-26 16:57:17.594  5902  5925 I bt_btu  : btu_task pending for preload complete event
,10-26 16:57:17.594  5902  5925 I bt_btu_task: Bluetooth chip preload is complete
10-26 16:57:17.594  5902  5925 I bt_btu  : btu_task received preload complete event
,10-26 16:57:17.601  5902  5925 I         : BTE_InitTraceLevels -- TRC_HCI
,10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_L2CAP
,10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_AVDT
10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_A2D
10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_BNEP
10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_BTM
10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_GAP
10-26 16:57:17.602  5902  5925 I         : BTE_InitTraceLevels -- TRC_PAN
10-26 16:57:17.603  5902  5925 I         : BTE_InitTraceLevels -- TRC_SDP
,10-26 16:57:17.603  5902  5925 I         : BTE_InitTraceLevels -- TRC_GATT
10-26 16:57:17.603  5902  5925 I         : BTE_InitTraceLevels -- TRC_SMP
,10-26 16:57:17.603  5902  5925 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-26 16:57:17.603  5902  5925 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-26 16:57:17.699  5902  5925 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3bb9549
10-26 16:57:17.699  5902  5925 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3bb9549 
,10-26 16:57:17.721  5902  5918 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-26 16:57:17.723  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-26 16:57:17.724  5902  5918 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-26 16:57:17.726  5902  5918 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-26 16:57:17.730  5902  5918 D BluetoothAdapterProperties: Scan Mode:20
10-26 16:57:17.730  5902  5918 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-26 16:57:17.730  5902  5918 D bt_hci  : do_postload posting postload work item
10-26 16:57:17.731  5902  5922 I bt_hci  : event_postload
,10-26 16:57:17.731  5902  5922 I bt_vendor: sco_config_cb
10-26 16:57:17.731  5902  5922 I bt_hci  : sco_config_callback postload finished.
10-26 16:57:17.735  5902  5918 D bt_bte_conf: Device ID record 1 : primary
10-26 16:57:17.735  5902  5918 D bt_bte_conf:   vendorId            = 000f
,10-26 16:57:17.735  5902  5918 D bt_bte_conf:   vendorIdSource      = 0001
10-26 16:57:17.735  5902  5918 D bt_bte_conf:   product             = 1200
10-26 16:57:17.735  5902  5918 D bt_bte_conf:   version             = 1436
10-26 16:57:17.735  5902  5918 D bt_bte_conf:   clientExecutableURL = 
10-26 16:57:17.735  5902  5918 D bt_bte_conf:   serviceDescription  = 
10-26 16:57:17.735  5902  5918 D bt_bte_conf:   documentationURL    = 
10-26 16:57:17.736  5902  5918 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-26 16:57:17.736  5902  5915 D bt_stack_manager: event_start_up_stack finished
10-26 16:57:17.736  5902  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-26 16:57:17.736  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:17.736  5902  5914 D BluetoothAdapterProperties: Setting state to 15
10-26 16:57:17.737  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-26 16:57:17.737  5902  5914 I BluetoothAdapterState: Entering BleOnState
10-26 16:57:17.739  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:17.740  5902  5922 I bt_vendor: low_power_mode_cb
,10-26 16:57:17.740  5902  5914 D BluetoothAdapterState: Current state: BLE ON, message: 1
,10-26 16:57:17.740  5902  5914 D BluetoothAdapterProperties: Setting state to 11
10-26 16:57:17.740  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-26 16:57:17.745  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:17.746  5902  5902 D HeadsetService: Received start request. Starting profile...
10-26 16:57:17.748  5902  5902 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-26 16:57:17.749  5902  5902 D HeadsetStateMachine: make
10-26 16:57:17.752  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:17.755  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:17.761  5902  5902 D HeadsetStateMachine: max_hf_connections = 1
,10-26 16:57:17.761  5902  5902 I bt_bluedroid: get_profile_interface handsfree
10-26 16:57:17.761  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-26 16:57:17.763  5902  5918 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-26 16:57:17.763  5902  5914 I BluetoothAdapterState: Entering PendingCommandState
10-26 16:57:17.764  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:17.765  5902  5902 D A2dpService: Received start request. Starting profile...
10-26 16:57:17.765  5902  5902 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,10-26 16:57:17.766  5902  5902 I bt_bluedroid: get_profile_interface avrcp
,10-26 16:57:17.774  5902  5902 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-26 16:57:17.774  5902  5902 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-26 16:57:17.774  5902  5902 D A2dpStateMachine: make
,10-26 16:57:17.777  5902  5902 I bt_bluedroid: get_profile_interface a2dp
,10-26 16:57:17.777  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-26 16:57:17.779  5902  5934 D A2dpStateMachine: Enter Disconnected: -2
,10-26 16:57:17.779  5902  5902 I BluetoothHidServiceJni: classInitNative: succeeds
,10-26 16:57:17.780  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:17.780  5902  5902 D HidService: Received start request. Starting profile...
10-26 16:57:17.781  5902  5902 I bt_bluedroid: get_profile_interface hidhost
10-26 16:57:17.781  5902  5902 D HidService: setHidService(): set to: null
10-26 16:57:17.781  5902  5918 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b9a56d
10-26 16:57:17.781  5902  5918 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-26 16:57:17.783  5902  5902 I BluetoothHealthServiceJni: classInitNative: succeeds
10-26 16:57:17.783  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 16:57:17.783  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:17.784  5902  5902 D HealthService: Received start request. Starting profile...
,10-26 16:57:17.786  5902  5902 I bt_bluedroid: get_profile_interface health
,10-26 16:57:17.786  5902  5902 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-26 16:57:17.787  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:17.787  5902  5902 D PanService: Received start request. Starting profile...
10-26 16:57:17.788  5902  5902 D BluetoothPanServiceJni: initializeNative(L110): pan
,10-26 16:57:17.788  5902  5902 I bt_bluedroid: get_profile_interface pan
10-26 16:57:17.788  5902  5918 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-26 16:57:17.792  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:17.792  5902  5902 D BluetoothMapService: Received start request. Starting profile...
10-26 16:57:17.792  5902  5902 D BluetoothMapService: start()
,10-26 16:57:17.795  5902  5902 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-26 16:57:17.796  5902  5902 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-26 16:57:17.796  5902  5902 D BluetoothMapAppObserver: createReceiver()
,10-26 16:57:17.797  5902  5902 D BluetoothMapAppObserver: initObservers()
10-26 16:57:17.797  5902  5902 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-26 16:57:17.805  5902  5902 V SapService: SapBinder()
10-26 16:57:17.805  5902  5902 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
,10-26 16:57:17.805  5902  5902 D SapService: Received start request. Starting profile...
10-26 16:57:17.805  5902  5902 V SapService: start()
,10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isTurningOff()=false
,10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:17.807  5902  5931 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isTurningOn()=true
,10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:17.807  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:17.808  5902  5902 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:17.809  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
,10-26 16:57:17.809  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:17.810  5902  5902 V BluetoothAdapterState: isTurningOff()=false
10-26 16:57:17.810  5902  5902 V BluetoothAdapterState: isTurningOn()=true
10-26 16:57:17.810  5902  5902 V BluetoothAdapterState: isBleTurningOn()=false
10-26 16:57:17.810  5902  5902 V BluetoothAdapterState: isBleTurningOff()=false
10-26 16:57:17.810  5902  5914 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-26 16:57:17.810  5902  5914 D BluetoothAdapterProperties: ScanMode =  20
10-26 16:57:17.810  5902  5914 D BluetoothAdapterProperties: State =  11
10-26 16:57:17.812  5902  5914 D BluetoothAdapterProperties: Setting state to 12
10-26 16:57:17.812  5902  5914 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,10-26 16:57:17.813  3111  3125 D BluetoothMap: onBluetoothStateChange: up=true
10-26 16:57:17.813  5902  5918 D BluetoothAdapterProperties: Scan Mode:21
10-26 16:57:17.814  5902  5918 D BluetoothAdapterProperties: Discoverable Timeout:120
10-26 16:57:17.814  5622  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 16:57:17.814  5902  5914 I BluetoothAdapterState: Entering OnState
10-26 16:57:17.815  3722  3751 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 16:57:17.815  3111  3111 D BluetoothMap: Proxy object connected
10-26 16:57:17.816  3111  3111 D MapProfile: Bluetooth service connected
10-26 16:57:17.816  3111  3111 D BluetoothMap: getConnectedDevices()
10-26 16:57:17.817  3111  3124 D BluetoothPan: onBluetoothStateChange on: true
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:17.818  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:17.819  5675  5688 D BluetoothMap: onBluetoothStateChange: up=true
10-26 16:57:17.819  3111  3111 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 16:57:17.819  3111  3111 D PanProfile: Bluetooth service connected
10-26 16:57:17.821  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:57:17.822   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 16:57:17.822  5675  5687 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 16:57:17.824  5902  5902 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-26 16:57:17.824  5902  5902 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:17.824  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:57:17.825  5675  5688 D BluetoothPbap: onBluetoothStateChange: up=true
10-26 16:57:17.826  5902  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 16:57:17.826   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-26 16:57:17.826  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:57:17.827   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 16:57:17.827  5675  5687 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-26 16:57:17.827  5902  5902 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-26 16:57:17.828  5902  5902 D ObexServerSockets: Succeed to create listening sockets 
10-26 16:57:17.828  3111  3945 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 16:57:17.828  5902  5902 D ObexServerSockets0: startAccept()
10-26 16:57:17.828  5902  5902 D ObexServerSockets0: prepareForNewConnect()
10-26 16:57:17.829  3111  3124 D BluetoothPbap: onBluetoothStateChange: up=true
,10-26 16:57:17.830  5675  5688 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-26 16:57:17.831  5902  5902 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-26 16:57:17.831  5902  5902 D BluetoothSdpJni: SDP Create record success - handle: 0
10-26 16:57:17.831  3111  3125 D BluetoothA2dp: onBluetoothStateChange: up=true
10-26 16:57:17.831  5902  5940 D ObexServerSockets0: Accepting socket connection...
10-26 16:57:17.832   931   931 D BluetoothA2dp: Proxy object connected
10-26 16:57:17.832  5902  5941 D ObexServerSockets0: Accepting socket connection...
10-26 16:57:17.832  5675  5675 D BluetoothMap: Proxy object connected
10-26 16:57:17.832  5675  5675 D MapProfile: Bluetooth service connected
10-26 16:57:17.833  5675  5675 D BluetoothMap: getConnectedDevices()
,10-26 16:57:17.833  3111  3111 D BluetoothA2dp: Proxy object connected
10-26 16:57:17.833   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-26 16:57:17.834  5675  5688 D BluetoothPan: onBluetoothStateChange on: true
10-26 16:57:17.836  3111  3124 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-26 16:57:17.837  5675  5675 D BluetoothA2dp: Proxy object connected
,10-26 16:57:17.838  3111  3111 D BluetoothInputDevice: Proxy object connected
10-26 16:57:17.838  3111  3111 D HidProfile: Bluetooth service connected
10-26 16:57:17.838   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
10-26 16:57:17.839  5622  5622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-26 16:57:17.839  5902  5902 D BluetoothMapService: onReceive
10-26 16:57:17.839  5902  5902 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-26 16:57:17.839  5902  5902 D BluetoothMapService: STATE_ON
,10-26 16:57:17.841  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:17.842  5675  5675 D BluetoothInputDevice: Proxy object connected
10-26 16:57:17.842  5675  5675 D HidProfile: Bluetooth service connected
,10-26 16:57:17.842  5902  5942 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 16:57:17.842  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:17.843  5902  5942 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-26 16:57:17.843  5902  5942 D BluetoothSdpJni: SDP Create record success - handle: 1
10-26 16:57:17.844  5675  5675 D BluetoothPan: BluetoothPAN Proxy object connected
10-26 16:57:17.844  5675  5675 D PanProfile: Bluetooth service connected
,10-26 16:57:17.849  5675  5675 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-26 16:57:17.859  3569  3569 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-26 16:57:17.860  5675  5675 D DockEventReceiver: finishStartingService: stopping service
,10-26 16:57:17.863  3111  3111 D BluetoothPbap: Proxy object connected
,10-26 16:57:17.863  5675  5675 D BluetoothPbap: Proxy object connected
10-26 16:57:17.864  3111  3111 D PbapServerProfile: Bluetooth service connected
10-26 16:57:17.864  5675  5675 D PbapServerProfile: Bluetooth service connected
,10-26 16:57:17.864  5902  5902 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-26 16:57:17.864  5902  5902 D ObexServerSockets0: prepareForNewConnect()
,10-26 16:57:17.866  5902  5945 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 16:57:17.884  5902  5951 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-26 16:57:17.886  5902  5951 I BtOppRfcommListener: Accept thread started.
,10-26 16:57:17.917   931   931 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.918  3722  4121 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.918  5675  5687 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.919  3111  3124 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.919  3111  3111 D HeadsetProfile: Bluetooth service connected
,10-26 16:57:17.919   931   931 D BluetoothHeadset: Proxy object connected
10-26 16:57:17.919   931   931 D BluetoothHeadset: Proxy object connected
10-26 16:57:17.920  5675  5675 D HeadsetProfile: Bluetooth service connected
,10-26 16:57:17.923   931   948 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.927   931   948 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.929  3111  3945 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.929  3111  3111 D HeadsetProfile: Bluetooth service connected
,10-26 16:57:17.931  5675  5688 D BluetoothHeadset: Proxy object connected
,10-26 16:57:17.932  5675  5675 D HeadsetProfile: Bluetooth service connected
,10-26 16:57:17.934   931   948 D BluetoothHeadset: Proxy object connected
,10-26 16:57:18.413   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:19.414   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:20.415   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:21.417   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:21.628  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:21.634  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:57:21.635  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:21.635  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5280a04 removed from the list
10-26 16:57:21.635  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 16:57:21.635  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:21.635  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:21.637  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 16:57:21.637  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@831abed added. We now have 4 listener(s)
,10-26 16:57:21.638  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:57:21.644   931  3772 D WifiService: setWifiEnabled: false pid=5622, uid=10077
10-26 16:57:21.644   931  3772 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 16:57:22.418   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:23.419   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-26 16:57:26.653  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:26.654   931  3804 D WifiService: setWifiEnabled: true pid=5622, uid=10077
,10-26 16:57:26.654   931  3804 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-26 16:57:26.662   508   927 D SoftapController: Softap fwReload - Ok
,10-26 16:57:26.667   508   927 D CommandListener: Setting iface cfg
10-26 16:57:26.667   508   927 D CommandListener: Trying to bring down wlan0
10-26 16:57:26.669   508   927 D CommandListener: Clearing all IP addresses on wlan0
,10-26 16:57:26.675   931  2971 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-26 16:57:27.274   931  2971 D wifi    : set interface wlan0 flags (UP)
,10-26 16:57:27.276   931  2971 I WifiHAL : Initializing wifi
,10-26 16:57:27.277   931  2971 I WifiHAL : Creating socket
,10-26 16:57:27.283   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-26 16:57:27.284   931  2971 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-26 16:57:27.284   931  2971 D wifi    : Did set static halHandle = 0x7f85b6de00
10-26 16:57:27.284   931  2971 D wifi    : halHandle = 0x7f85b6de00, mVM = 0x7fa21cd140, mCls = 0x20153a
10-26 16:57:27.284   931  2971 D wifi    : array field set
10-26 16:57:27.285   931  2971 I WifiNative-HAL: interface[0] = wlan0
10-26 16:57:27.287   931  5956 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547704200704
10-26 16:57:27.287   931  5956 D wifi    : waitForHalEvents called, vm = 0x7fa21cd140, obj = 0x20153a, env = 0x7f837a1640
,10-26 16:57:27.289   931  2971 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-26 16:57:27.291   931  2971 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,10-26 16:57:27.296  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:27.299  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:27.349  5957  5957 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-26 16:57:27.371  5957  5957 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 16:57:27.408  5957  5957 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-26 16:57:27.408  5957  5957 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-26 16:57:28.307   931  2971 D WifiConfigStore: Loading config and enabling all networks 
,10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:28.318  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:57:28.323  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:28.332  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-26 16:57:28.335   931  2971 D WifiConfigStore: loaded 0 passpoint configs
10-26 16:57:28.336  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:57:28.336   931  2971 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-26 16:57:28.337   931  2971 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-26 16:57:28.338   931  2971 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-26 16:57:28.340   931  2971 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-26 16:57:28.340   931  2971 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-26 16:57:28.340   931  2971 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-26 16:57:28.340   931  2971 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-26 16:57:28.344   931  2971 D WifiNative-HAL: Setting external_sim to 1
,10-26 16:57:28.344  4404  4404 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-26 16:57:28.345   931  2971 D wifi    : setting dfs flag to true, 0x7f885f5140
10-26 16:57:28.346   931  2971 D WifiStateMachine: Setting OUI to DA-A1-19
,10-26 16:57:28.346   931  2971 D wifi    : setting scan oui 0x7f885f5140
10-26 16:57:28.346   931  2971 D WifiHAL : Sending mac address OUI
,10-26 16:57:28.351   931  2971 E native  : do suspend false
,10-26 16:57:28.364   931  2971 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-26 16:57:28.365   508   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-26 16:57:28.365   931   931 D RttService: SCAN_AVAILABLE : 3
10-26 16:57:28.365   931  3047 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-26 16:57:28.366   508   927 D CommandListener: Setting iface cfg
,10-26 16:57:28.372   931  2959 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '156 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 156 Failed to set address (No such device)'
,10-26 16:57:28.372   931  2959 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-26 16:57:28.385   931  2959 D WifiNative-HAL: p2pGetDeviceAddress
,10-26 16:57:28.386   931  2959 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-26 16:57:28.393   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=285160 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=21 mControllerEnergyUsed=79 }
,10-26 16:57:31.486  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:57:31.491  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:57:31.497  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:57:31.502  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:57:31.505  5957  5957 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-26 16:57:31.553   931  2971 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-26 16:57:31.554   931  2971 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-26 16:57:31.554   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 16:57:31.568   931  2971 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-26 16:57:31.608   931  2971 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-26 16:57:31.610  5957  5957 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:31.667  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:31.669  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:31.669  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.669  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@831abed removed from the list
10-26 16:57:31.669  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:57:31.670  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:57:31.670  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:57:31.675  5622  5668 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-26 16:57:31.675  5622  5668 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-26 16:57:31.678  5622  5668 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c00e90c Bundle[{}]
10-26 16:57:31.678  5622  5668 I io.jxcore.node.LifeCycleMonitor: start: OK
10-26 16:57:31.678  5622  5668 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-26 16:57:31.679  5622  5668 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,10-26 16:57:31.679  5622  5668 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-26 16:57:31.680  5622  5668 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-26 16:57:31.682  5622  5668 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-26 16:57:31.690  5622  5668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 164)
,10-26 16:57:31.691  5622  5668 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-26 16:57:31.691  5622  5668 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 165)
,10-26 16:57:31.693  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 16:57:31.693  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d69a22 added. We now have 3 listener(s)
,10-26 16:57:31.695  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.695  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.695  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.696  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.696  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a22cb3 added. We now have 4 listener(s)
10-26 16:57:31.696  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-26 16:57:31.697  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 16:57:31.701  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:31.706  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:31.708  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:31.708  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:57:31.708  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 16:57:31.709  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38a19e9 added. We now have 4 listener(s)
10-26 16:57:31.710  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.710  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:31.710  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.710  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.711  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.711  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e8366e added. We now have 5 listener(s)
10-26 16:57:31.711  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.711  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:57:31.711  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:57:31.711  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:57:31.711  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.711  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.711  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.711  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.711  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.711  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d69a22 removed from the list
10-26 16:57:31.711  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.711  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a22cb3 removed from the list
,10-26 16:57:31.711  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:31.712  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:57:31.712  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.713  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.713  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.713  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.715  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.715  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.715  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.715  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,10-26 16:57:31.715  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.715  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.715  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a22cb3 not in the list
10-26 16:57:31.715  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.715  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.715  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.717  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.717  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.717  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.717  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.717  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.717  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.717  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e8366e removed from the list
10-26 16:57:31.717  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 16:57:31.718  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.718  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.718  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.718  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.718  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38a19e9 removed from the list
10-26 16:57:31.719  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-26 16:57:31.719  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@288e10f added. We now have 3 listener(s)
,10-26 16:57:31.721  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.721  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.721  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.721  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.721  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@974959c added. We now have 4 listener(s)
,10-26 16:57:31.721  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.722  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 16:57:31.725  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:31.729  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:31.731  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:31.732  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:57:31.732  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:57:31.732  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b654b7a added. We now have 4 listener(s)
,10-26 16:57:31.733  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-26 16:57:31.734  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.734  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.734  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.734  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:31.734  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c7f2b added. We now have 5 listener(s)
10-26 16:57:31.734  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.734  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:57:31.734  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 16:57:31.735  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 16:57:31.735  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:57:31.735  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-26 16:57:31.737  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:31.738  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 16:57:31.738  5622  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 16:57:31.738  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 16:57:31.741  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 16:57:31.742  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 16:57:31.742  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 16:57:31.745  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.745  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 16:57:31.745  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 16:57:31.745  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 16:57:31.745  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 16:57:31.745  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.746  5622  5668 D BluetoothAdapter: STATE_ON
,10-26 16:57:31.749  5902  5912 D BtGatt.GattService: registerClient() - UUID=844d1dcb-927f-4ab5-8e80-a917942d6dd0
,10-26 16:57:31.750  5902  5918 D BtGatt.GattService: onClientRegistered() - UUID=844d1dcb-927f-4ab5-8e80-a917942d6dd0, clientIf=5
,10-26 16:57:31.750  5622  5632 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 16:57:31.751  5902  5932 D BtGatt.GattService: start scan with filters
,10-26 16:57:31.754  5902  5921 D BtGatt.ScanManager: handling starting scan
10-26 16:57:31.754  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-26 16:57:31.754  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.754  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,10-26 16:57:31.754  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.754  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.754  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 16:57:31.755  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 16:57:31.755  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.755  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.755  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 16:57:31.755  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.755  5902  5921 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@39fb599
10-26 16:57:31.757  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.757  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:57:31.757  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.757  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.757  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.757  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 16:57:31.757  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,10-26 16:57:31.758  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 16:57:31.759  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.761  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.761  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.761  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.761  5622  5668 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-26 16:57:31.761  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-26 16:57:31.761  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-26 16:57:31.761  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.761  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 16:57:31.761  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.761  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-26 16:57:31.761  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-26 16:57:31.762  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 16:57:31.762  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 16:57:31.762  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.762  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.762  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 16:57:31.762  5902  5918 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 16:57:31.762  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.763  5622  5668 D BluetoothAdapter: STATE_ON
,10-26 16:57:31.763  5902  5921 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 16:57:31.763  5902  5912 D BtGatt.GattService: stopScan() - queue size =1
10-26 16:57:31.764  5902  5932 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-26 16:57:31.764  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 16:57:31.764  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.764  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 16:57:31.764  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.764  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.765  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 16:57:31.765  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 16:57:31.765  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.765  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.765  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,10-26 16:57:31.765  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.766  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 16:57:31.767  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.767  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.767  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.767  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 16:57:31.767  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 16:57:31.767  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.767  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.768  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.768  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.768  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.769  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 16:57:31.769  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:57:31.769  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.769  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-26 16:57:31.769  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:57:31.769  5902  5921 D BtGatt.ScanManager: Starting BLE batch scan
10-26 16:57:31.769  5902  5921 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 16:57:31.770  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:57:31.770  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:57:31.771  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:57:31.771  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-26 16:57:31.771  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:57:31.771  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.771  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.771  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.771  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@288e10f removed from the list
10-26 16:57:31.771  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.771  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@974959c removed from the list
10-26 16:57:31.771  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:57:31.771  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.773  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.773  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.773  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.774  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.774  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.774  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.774  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.774  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.774  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.774  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@974959c not in the list
10-26 16:57:31.774  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.774  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.774  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.776  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.776  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.776  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.776  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.776  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.776  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.777  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17c7f2b removed from the list
10-26 16:57:31.777  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.777  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.777  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.777  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.777  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.777  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b654b7a removed from the list
,10-26 16:57:31.778  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:57:31.778  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c1e307 added. We now have 3 listener(s)
,10-26 16:57:31.779  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.779  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.779  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 16:57:31.779  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.779  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f23fc34 added. We now have 4 listener(s)
10-26 16:57:31.779  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.780  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 16:57:31.780  5902  5918 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 16:57:31.780  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:31.782  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:57:31.785  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 16:57:31.786  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:31.787  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:31.789  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:31.790  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-26 16:57:31.790  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:57:31.790  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dcfd2 added. We now have 4 listener(s)
10-26 16:57:31.791  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.791  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:31.791  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.791  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.791  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.791  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0fa8a3 added. We now have 5 listener(s)
10-26 16:57:31.791  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.791  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:57:31.792  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:57:31.792  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 16:57:31.792  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 16:57:31.792  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.792  5902  5921 D BtGatt.ScanManager: stopping BLe Batch
10-26 16:57:31.793  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,10-26 16:57:31.793  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:57:31.793  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-26 16:57:31.793  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:31.795  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 16:57:31.795  5622  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 16:57:31.795  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 16:57:31.798  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-26 16:57:31.798  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.798  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-26 16:57:31.798  5902  5921 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-26 16:57:31.799  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 16:57:31.799  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 16:57:31.802  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.802  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,10-26 16:57:31.802  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 16:57:31.803  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 16:57:31.803  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 16:57:31.803  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.803  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:57:31.803  5902  5918 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-26 16:57:31.803  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:31.805  5902  5912 D BtGatt.GattService: registerClient() - UUID=b88c83e7-4745-4c53-ad0d-fa2afbad7471
10-26 16:57:31.806  5902  5918 D BtGatt.GattService: onClientRegistered() - UUID=b88c83e7-4745-4c53-ad0d-fa2afbad7471, clientIf=5
,10-26 16:57:31.806  5622  5633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 16:57:31.807  5902  5932 D BtGatt.GattService: start scan with filters
,10-26 16:57:31.809  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 16:57:31.809  5902  5921 D BtGatt.ScanManager: handling starting scan
10-26 16:57:31.809  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.809  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 16:57:31.809  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.809  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.809  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 16:57:31.809  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 16:57:31.809  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.810  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.810  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 16:57:31.810  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.812  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.812  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:57:31.812  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.812  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.812  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:57:31.812  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.812  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-26 16:57:31.813  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 16:57:31.814  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.814  5902  5918 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 16:57:31.814  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:31.815  5902  5921 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-26 16:57:31.815  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.816  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.816  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.816  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:57:31.816  5622  5668 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-26 16:57:31.816  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:57:31.816  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:57:31.816  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:57:31.816  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.816  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.816  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 16:57:31.816  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.816  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.817  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c1e307 removed from the list
10-26 16:57:31.817  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,10-26 16:57:31.817  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f23fc34 removed from the list
10-26 16:57:31.817  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:57:31.817  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.817  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.817  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 16:57:31.817  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.817  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.818  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.818  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.819  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.819  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.819  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.819  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.819  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.819  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f23fc34 not in the list
10-26 16:57:31.819  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 16:57:31.819  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,10-26 16:57:31.819  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 16:57:31.819  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.819  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.819  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 16:57:31.820  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:57:31.820  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 16:57:31.820  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.820  5902  5932 D BtGatt.GattService: stopScan() - queue size =1
,10-26 16:57:31.821  5902  5921 D BtGatt.ScanManager: Starting BLE batch scan
10-26 16:57:31.821  5902  5921 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-26 16:57:31.821  5902  5913 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 16:57:31.821  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 16:57:31.821  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.821  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 16:57:31.821  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.821  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.822  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 16:57:31.822  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 16:57:31.822  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.822  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.822  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 16:57:31.822  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.823  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 16:57:31.824  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.824  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.824  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.824  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 16:57:31.824  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 16:57:31.824  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.824  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.825  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.825  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.825  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.825  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.826  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.826  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.826  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:57:31.826  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0fa8a3 removed from the list
10-26 16:57:31.826  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.826  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:57:31.826  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-26 16:57:31.826  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:57:31.826  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.826  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.826  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.826  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3dcfd2 removed from the list
10-26 16:57:31.827  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:57:31.827  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ea2bff added. We now have 3 listener(s)
,10-26 16:57:31.828  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.828  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.828  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.828  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 16:57:31.828  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e569dcc added. We now have 4 listener(s)
10-26 16:57:31.828  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.829  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-26 16:57:31.831  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:57:31.832  5902  5918 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 16:57:31.832  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:31.834  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:31.835  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-26 16:57:31.835  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:57:31.835  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:57:31.835  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@367872a added. We now have 4 listener(s)
10-26 16:57:31.836  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 16:57:31.836  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.836  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.836  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.836  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-26 16:57:31.836  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.837  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bf891b added. We now have 5 listener(s)
10-26 16:57:31.837  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.837  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:57:31.837  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-26 16:57:31.837  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:31.837  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-26 16:57:31.837  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-26 16:57:31.837  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-26 16:57:31.838  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-26 16:57:31.839  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-26 16:57:31.839  5622  5668 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-26 16:57:31.839  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-26 16:57:31.842  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-26 16:57:31.842  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-26 16:57:31.842  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.842  5902  5921 D BtGatt.ScanManager: stopping BLe Batch
,10-26 16:57:31.843  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-26 16:57:31.843  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-26 16:57:31.846  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.846  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-26 16:57:31.846  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-26 16:57:31.846  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-26 16:57:31.846  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-26 16:57:31.846  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.847  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:57:31.847  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 16:57:31.847  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:31.847  5902  5921 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 16:57:31.848  5902  5913 D BtGatt.GattService: registerClient() - UUID=8305fc76-97ad-4893-ae48-2c51c743084f
10-26 16:57:31.849  5902  5918 D BtGatt.GattService: onClientRegistered() - UUID=8305fc76-97ad-4893-ae48-2c51c743084f, clientIf=5
,10-26 16:57:31.849  5622  5633 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-26 16:57:31.849  5902  5943 D BtGatt.GattService: start scan with filters
10-26 16:57:31.852  5902  5918 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
10-26 16:57:31.852  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-26 16:57:31.853  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.853  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-26 16:57:31.853  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.853  5902  5921 D BtGatt.ScanManager: handling starting scan
,10-26 16:57:31.854  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.855  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:57:31.855  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.855  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.855  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-26 16:57:31.855  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.855  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-26 16:57:31.856  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-26 16:57:31.856  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.857  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.857  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.857  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.858  5902  5918 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-26 16:57:31.858  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.859  5902  5921 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-26 16:57:31.859  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:57:31.859  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:57:31.859  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:57:31.859  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.860  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.860  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-26 16:57:31.860  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.860  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.860  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7ea2bff removed from the list
10-26 16:57:31.860  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.860  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e569dcc removed from the list
10-26 16:57:31.860  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
,10-26 16:57:31.860  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.860  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.860  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
10-26 16:57:31.860  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.860  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.861  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.861  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.861  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.861  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.861  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.861  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.861  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.862  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e569dcc not in the list
10-26 16:57:31.862  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-26 16:57:31.862  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-26 16:57:31.862  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-26 16:57:31.862  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.862  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.862  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-26 16:57:31.863  5622  5668 D BluetoothAdapter: STATE_ON
10-26 16:57:31.863  5902  5913 D BtGatt.GattService: stopScan() - queue size =1
10-26 16:57:31.863  5902  5943 D BtGatt.GattService: unregisterClient() - clientIf=5
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-26 16:57:31.864  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.864  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.864  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-26 16:57:31.864  5902  5921 D BtGatt.ScanManager: Starting BLE batch scan
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.864  5902  5921 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.864  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
10-26 16:57:31.864  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.865  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.865  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:57:31.865  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.865  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.865  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.865  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.865  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.866  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-26 16:57:31.866  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.866  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.866  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.866  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-26 16:57:31.866  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-26 16:57:31.867  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.867  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.867  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.867  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.867  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.868  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.868  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.868  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.868  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bf891b removed from the list
10-26 16:57:31.868  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-26 16:57:31.868  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.868  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.868  5622  5622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-26 16:57:31.868  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.868  5622  5622 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-26 16:57:31.868  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.868  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.868  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@367872a removed from the list
10-26 16:57:31.868  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:57:31.868  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac39bf7 added. We now have 3 listener(s)
10-26 16:57:31.869  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.869  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.869  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.870  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-26 16:57:31.870  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d8da64 added. We now have 4 listener(s)
10-26 16:57:31.870  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.870  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-26 16:57:31.871  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-26 16:57:31.873  5902  5918 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-26 16:57:31.873  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-26 16:57:31.874  5622  5668 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-26 16:57:31.875  5622  5668 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-26 16:57:31.875  5622  5668 D io.jxcore.node.ConnectivityMonitor: start: OK
10-26 16:57:31.876  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-26 16:57:31.876  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175d182 added. We now have 4 listener(s)
10-26 16:57:31.876  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-26 16:57:31.876  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-26 16:57:31.877  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-26 16:57:31.877  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:31.877  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-26 16:57:31.877  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c0093 added. We now have 5 listener(s)
10-26 16:57:31.877  5622  5668 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-26 16:57:31.877  5622  5668 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-26 16:57:31.877  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:57:31.877  5622  5668 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-26 16:57:31.877  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.877  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.877  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-26 16:57:31.877  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.877  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-26 16:57:31.877  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ac39bf7 removed from the list
10-26 16:57:31.877  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.877  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d8da64 removed from the list
10-26 16:57:31.878  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-26 16:57:31.878  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-26 16:57:31.878  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.878  5622  5668 D io.jxcore.node.ConnectivityMonitor: stop
10-26 16:57:31.878  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.879  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.879  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-26 16:57:31.879  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.880  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.880  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.880  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.880  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.880  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.880  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.880  5622  5668 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6d8da64 not in the list
10-26 16:57:31.880  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.880  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.880  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-57,5,main], id: 57
,10-26 16:57:31.881  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.881  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.881  5622  5668 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-57,5,main], id: 57
10-26 16:57:31.881  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
10-26 16:57:31.881  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
10-26 16:57:31.881  5622  5668 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-26 16:57:31.881  5622  5668 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18c0093 removed from the list
,10-26 16:57:31.881  5622  5668 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-26 16:57:31.881  5622  5668 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-26 16:57:31.881  5622  5668 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-26 16:57:31.881  5622  5668 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-26 16:57:31.881  5622  5668 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-26 16:57:31.881  5622  5668 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@175d182 removed from the list
10-26 16:57:31.882  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-26 16:57:31.882  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-26 16:57:31.882  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-26 16:57:31.882  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-26 16:57:31.882  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-26 16:57:31.882  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,10-26 16:57:31.884  5902  5918 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,10-26 16:57:31.884  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.885  5902  5921 D BtGatt.ScanManager: stopping BLe Batch
,10-26 16:57:31.890  5902  5918 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-26 16:57:31.890  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-26 16:57:31.890  5902  5921 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-26 16:57:31.895  5902  5918 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,10-26 16:57:31.895  5902  5918 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-26 16:57:32.045  5957  5957 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-26 16:57:32.080  5957  5957 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
10-26 16:57:32.080  5957  5957 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-26 16:57:32.091   931  2971 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
10-26 16:57:32.092   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 16:57:32.092   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-26 16:57:32.110   931  2971 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-26 16:57:32.123   508   927 D CommandListener: Setting iface cfg
,10-26 16:57:32.127   931  2971 D WifiStateMachine: Start Dhcp Watchdog 3
,10-26 16:57:32.135   931  5962 D DhcpClient: Receive thread started
,10-26 16:57:32.140   931  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,10-26 16:57:32.140   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-26 16:57:32.140   931  2973 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,10-26 16:57:32.227   931  2971 E native  : do suspend false
,10-26 16:57:32.250   931  5961 D DhcpClient: Broadcasting DHCPDISCOVER
,10-26 16:57:32.262   931  5962 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,10-26 16:57:32.264   931  5961 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,10-26 16:57:32.266   931  5961 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-26 16:57:32.270  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 16:57:32.280   931  5962 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-26 16:57:32.281   931  5961 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
10-26 16:57:32.284   508   927 D CommandListener: Setting iface cfg
,10-26 16:57:32.290   931  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-26 16:57:32.294   931  5961 D DhcpClient: Scheduling renewal in 86399s
,10-26 16:57:32.312   931  2971 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-26 16:57:32.314   931  2971 D WifiConfigStore: No blacklist allowed without epno enabled
,10-26 16:57:32.315   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-26 16:57:32.317   931  2973 D ConnectivityService: Adding iface wlan0 to network 102
,10-26 16:57:32.326  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
10-26 16:57:32.328   931  2971 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-26 16:57:32.368   931  2973 E ConnectivityService: Unexpected mtu value: 0, wlan0
10-26 16:57:32.368   931  2973 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
10-26 16:57:32.368  5622  5622 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-26 16:57:32.371   931  2973 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,10-26 16:57:32.375   931  2973 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,10-26 16:57:32.377   931  2973 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,10-26 16:57:32.385   931  2973 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 16:57:32.389   931  2973 D ConnectivityService: scheduleUnvalidatedPrompt 102
,10-26 16:57:32.390   931  2973 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
10-26 16:57:32.390   931  2973 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
10-26 16:57:32.390   931  2973 D ConnectivityService:    accepting network in place of null
10-26 16:57:32.390   931  2971 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-26 16:57:32.390   931  2971 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-26 16:57:32.390   931  2973 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-26 16:57:32.405   931  5960 D NetlinkSocketObserver: NeighborEvent{elapsedMs=289172, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-26 16:57:32.412   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 16:57:32.435   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-26 16:57:32.438   931  2973 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,10-26 16:57:32.438   931  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-26 16:57:32.438  3702  3871 W QCNEJ   : |CORE| network available: 102
,10-26 16:57:32.440   931  2973 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
10-26 16:57:32.440   931   948 D Tethering: MasterInitialState.processMessage what=3
,10-26 16:57:32.442  3702  3871 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-26 16:57:32.444  3702  3871 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-26 16:57:32.445  3702  3871 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:57:32.450  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-26 16:57:32.453  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-26 16:57:32.457  5622  5622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-26 16:57:32.459  5622  5622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-26 16:57:32.459  5043  5056 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-26 16:57:32.459  5043  5056 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-26 16:57:32.459  5043  5056 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-26 16:57:32.460  5043  5056 E SarControlService: no key has been found,reset the power
10-26 16:57:32.460  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-26 16:57:32.460  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-26 16:57:32.460  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-26 16:57:32.461  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-26 16:57:32.461  5069  5069 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-26 16:57:32.462  5043  5081 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-26 16:57:32.462  5043  5081 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-26 16:57:32.462  5043  5081 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,10-26 16:57:32.464  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,10-26 16:57:32.464  5069  5069 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-26 16:57:32.465  4025  4025 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-26 16:57:32.469  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000f003000000000000ffffffff]
10-26 16:57:32.469  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 16:57:32.469  5069  5083 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
10-26 16:57:32.470  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:57:32.470  5043  5053 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-26 16:57:32.472  4025  4025 D SystemUpdateService: onCreate
10-26 16:57:32.473  5069  5083 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@84cdec8 HexData = [00000000f103000000000000ffffffff]
10-26 16:57:32.473  5069  5083 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-26 16:57:32.473  5069  5083 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
10-26 16:57:32.474  5069  5069 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-26 16:57:32.474  5043  5054 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-26 16:57:32.477  4025  4025 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-26 16:57:32.477   931  5959 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,10-26 16:57:32.487  4025  4025 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-26 16:57:32.494  4025  5386 I iu.UploadsManager: num queued entries: 0
,10-26 16:57:32.494  4025  5386 I iu.UploadsManager: num updated entries: 0
10-26 16:57:32.495  4025  5386 I iu.SyncManager: NEXT; no task
,10-26 16:57:32.498  4025  5972 I SystemUpdateService: active receiver: enabled
,10-26 16:57:32.500  4025  4025 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-26 16:57:32.502  4025  4025 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
10-26 16:57:32.504  5748  5748 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-26 16:57:32.507  5748  5748 D SprintDMHelper: simOperator: 
10-26 16:57:32.507  5748  5748 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-26 16:57:32.527   931  5959 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 26 Oct 2016 20:57:32 GMT], X-Android-Received-Millis=[1477515452526], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477515452501]}
,10-26 16:57:32.528   931  2973 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-26 16:57:32.528   931  2973 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,10-26 16:57:32.528   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
10-26 16:57:32.529   931  2973 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
10-26 16:57:32.529  4025  5972 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-26 16:57:32.543  4025  5972 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-26 16:57:32.544  4025  5972 I SystemUpdateService: now status is 0 (complete)
10-26 16:57:32.544  4025  5972 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-26 16:57:32.544  4025  5972 I SystemUpdateService: file has been verified
10-26 16:57:32.544  4025  5972 I SystemUpdateService: OTA package size = 21989297
,10-26 16:57:32.551  4025  5972 I SystemUpdateService: showing system update notification
,10-26 16:57:32.564  4025  4025 D SystemUpdateService: onDestroy
,10-26 16:57:32.608  4404  5977 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-26 16:57:34.032  5622  5984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 16:57:34.032  5622  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:34.819  5622  5984 W !!      : call onHalfStreamCopied
,10-26 16:57:34.819  5622  5984 I testCopyDataAndClose: closing input stream
,10-26 16:57:35.162   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-26 16:57:35.602  5622  5984 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 16:57:39.401  5622  5985 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:39.401  5622  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:40.395   931  2973 D ConnectivityService: handlePromptUnvalidated 102
,10-26 16:57:41.400  5622  5668 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 176. Connection data: Peer properties: [null null].
10-26 16:57:41.400  5622  5668 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:41.400  5622  5668 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 176, name: My test thread name)
,10-26 16:57:41.541  5622  5986 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 16:57:41.541  5622  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:41.569  5622  5985 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,10-26 16:57:41.569  5622  5985 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:41.569  5622  5985 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-26 16:57:43.181  5622  5986 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-26 16:57:43.396   931  2971 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,10-26 16:57:43.420   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:44.421   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:45.422   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:46.423   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:46.918  5622  5987 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:46.918  5622  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:46.918  5622  5987 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 180, thread name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:46.918  5622  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-26 16:57:46.919  5622  5987 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-26 16:57:46.919  5622  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:46.919  5622  5987 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,10-26 16:57:46.919  5622  5987 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-26 16:57:46.919  5622  5987 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-26 16:57:46.919  5622  5987 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,10-26 16:57:46.919  5622  5987 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-26 16:57:46.920  5622  5987 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:46.920  5622  5987 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-26 16:57:46.921  5622  5668 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-26 16:57:46.924  5622  5988 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:46.924  5622  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-26 16:57:46.925  5622  5988 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 184, thread name: My test thread name): Test exception.
10-26 16:57:46.925  5622  5988 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:46.925  5622  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 16:57:46.925  5622  5988 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-26 16:57:46.925  5622  5988 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
10-26 16:57:46.925  5622  5988 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-26 16:57:46.929  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
10-26 16:57:46.929  5622  5668 I jxcore-log: 
10-26 16:57:46.929  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'Number of passed tests:  82'
10-26 16:57:46.929  5622  5668 I jxcore-log: 
,10-26 16:57:46.930  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'Number of failed tests:  0'
10-26 16:57:46.930  5622  5668 I jxcore-log: 
10-26 16:57:46.930  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
10-26 16:57:46.930  5622  5668 I jxcore-log: 
10-26 16:57:46.930  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'Total duration:  90787'
10-26 16:57:46.930  5622  5668 I jxcore-log: 
10-26 16:57:46.932  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-26 16:57:46.932  5622  5668 I jxcore-log: 
,10-26 16:57:46.935  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.935  5622  5668 I jxcore-log: 
10-26 16:57:46.936  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.936  5622  5668 I jxcore-log: 
10-26 16:57:46.936  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.936  5622  5668 I jxcore-log: 
10-26 16:57:46.937  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.937  5622  5668 I jxcore-log: 
,10-26 16:57:46.937  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 16:57:46.937  5622  5668 I jxcore-log: 
,10-26 16:57:46.938  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 16:57:46.938  5622  5668 I jxcore-log: 
10-26 16:57:46.938  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.938  5622  5668 I jxcore-log: 
10-26 16:57:46.938  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.938  5622  5668 I jxcore-log: 
10-26 16:57:46.938  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-26 16:57:46.938  5622  5668 I jxcore-log: 
10-26 16:57:46.938  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 16:57:46.938  5622  5668 I jxcore-log: 
10-26 16:57:46.939  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 16:57:46.939  5622  5668 I jxcore-log: 
10-26 16:57:46.939  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.939  5622  5668 I jxcore-log: 
10-26 16:57:46.939  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.939  5622  5668 I jxcore-log: 
10-26 16:57:46.939  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.939  5622  5668 I jxcore-log: 
10-26 16:57:46.940  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.940  5622  5668 I jxcore-log: 
10-26 16:57:46.940  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.940  5622  5668 I jxcore-log: 
10-26 16:57:46.940  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.940  5622  5668 I jxcore-log: 
10-26 16:57:46.941  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.941  5622  5668 I jxcore-log: 
10-26 16:57:46.941  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.941  5622  5668 I jxcore-log: 
10-26 16:57:46.941  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.941  5622  5668 I jxcore-log: 
,10-26 16:57:46.941  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.941  5622  5668 I jxcore-log: 
10-26 16:57:46.942  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.942  5622  5668 I jxcore-log: 
10-26 16:57:46.942  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.942  5622  5668 I jxcore-log: 
10-26 16:57:46.943  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.943  5622  5668 I jxcore-log: 
10-26 16:57:46.944  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.944  5622  5668 I jxcore-log: 
10-26 16:57:46.944  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.944  5622  5668 I jxcore-log: 
10-26 16:57:46.944  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.944  5622  5668 I jxcore-log: 
,10-26 16:57:46.944  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.944  5622  5668 I jxcore-log: 
10-26 16:57:46.945  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.945  5622  5668 I jxcore-log: 
10-26 16:57:46.945  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.945  5622  5668 I jxcore-log: 
10-26 16:57:46.945  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.945  5622  5668 I jxcore-log: 
10-26 16:57:46.945  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.945  5622  5668 I jxcore-log: 
10-26 16:57:46.945  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.945  5622  5668 I jxcore-log: 
10-26 16:57:46.946  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.946  5622  5668 I jxcore-log: 
,10-26 16:57:46.946  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.946  5622  5668 I jxcore-log: 
10-26 16:57:46.946  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.946  5622  5668 I jxcore-log: 
10-26 16:57:46.946  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.946  5622  5668 I jxcore-log: 
10-26 16:57:46.947  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.947  5622  5668 I jxcore-log: 
10-26 16:57:46.947  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.947  5622  5668 I jxcore-log: 
10-26 16:57:46.947  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-26 16:57:46.947  5622  5668 I jxcore-log: 
10-26 16:57:46.947  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.947  5622  5668 I jxcore-log: 
10-26 16:57:46.947  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.947  5622  5668 I jxcore-log: 
,10-26 16:57:46.948  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.948  5622  5668 I jxcore-log: 
10-26 16:57:46.948  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.948  5622  5668 I jxcore-log: 
10-26 16:57:46.948  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.948  5622  5668 I jxcore-log: 
10-26 16:57:46.948  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-26 16:57:46.948  5622  5668 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
10-26 16:57:46.949  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.949  5622  5668 I jxcore-log: 
10-26 16:57:46.949  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.949  5622  5668 I jxcore-log: 
10-26 16:57:46.949  5622  5668 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-26 16:57:46.949  5622  5668 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,10-26 16:57:46.949  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-26 16:57:46.949  5622  5668 I jxcore-log: 
10-26 16:57:46.949  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 16:57:46.949  5622  5668 I jxcore-log: 
10-26 16:57:46.950  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 16:57:46.950  5622  5668 I jxcore-log: 
10-26 16:57:46.950  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-26 16:57:46.950  5622  5668 I jxcore-log: 
10-26 16:57:46.950  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.950  5622  5668 I jxcore-log: 
10-26 16:57:46.950  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-26 16:57:46.950  5622  5668 I jxcore-log: 
,10-26 16:57:46.955  5622  5622 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-26 16:57:46.956  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-26 16:57:46.956  5622  5668 I jxcore-log: 
10-26 16:57:46.956  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - WARN testUtils: 'myNameCallback not set!'
10-26 16:57:46.956  5622  5668 I jxcore-log: 
,10-26 16:57:46.957  5622  5668 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-26 16:57:46.958  5622  5668 I jxcore-log: 2016-10-26 20:57:46 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-26 16:57:46.958  5622  5668 I jxcore-log: 
,10-26 16:57:47.425   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:57:48.425   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 16:57:48.950  5622  5668 I jxcore-log: 2016-10-26 20:57:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-26 16:57:48.950  5622  5668 I jxcore-log: 
,10-26 16:57:49.274  5622  5668 I jxcore-log: 2016-10-26 20:57:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-26 16:57:49.274  5622  5668 I jxcore-log: 
,10-26 16:57:49.288  5622  5668 I jxcore-log: 2016-10-26 20:57:49 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-26 16:57:49.288  5622  5668 I jxcore-log: 
,10-26 16:57:50.374  5622  5668 I jxcore-log: 2016-10-26 20:57:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-26 16:57:50.374  5622  5668 I jxcore-log: 
,10-26 16:57:50.555  5622  5668 I jxcore-log: 2016-10-26 20:57:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-26 16:57:50.555  5622  5668 I jxcore-log: 
,10-26 16:57:50.561  5622  5668 I jxcore-log: 2016-10-26 20:57:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-26 16:57:50.561  5622  5668 I jxcore-log: 
,10-26 16:57:50.565  5622  5668 I jxcore-log: 2016-10-26 20:57:50 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-26 16:57:50.565  5622  5668 I jxcore-log: 
,10-26 16:57:51.034  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-26 16:57:51.034  5622  5668 I jxcore-log: 
,10-26 16:57:51.076  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-26 16:57:51.076  5622  5668 I jxcore-log: 
,10-26 16:57:51.089  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-26 16:57:51.089  5622  5668 I jxcore-log: 
,10-26 16:57:51.093  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-26 16:57:51.093  5622  5668 I jxcore-log: 
,10-26 16:57:51.370  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-26 16:57:51.370  5622  5668 I jxcore-log: 
,10-26 16:57:51.492  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-26 16:57:51.492  5622  5668 I jxcore-log: 
,10-26 16:57:51.875  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-26 16:57:51.875  5622  5668 I jxcore-log: 
,10-26 16:57:51.882  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-26 16:57:51.882  5622  5668 I jxcore-log: 
,10-26 16:57:51.886  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-26 16:57:51.886  5622  5668 I jxcore-log: 
,10-26 16:57:51.890  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-26 16:57:51.890  5622  5668 I jxcore-log: 
,10-26 16:57:51.895  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-26 16:57:51.895  5622  5668 I jxcore-log: 
,10-26 16:57:51.921  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-26 16:57:51.921  5622  5668 I jxcore-log: 
,10-26 16:57:51.954  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-26 16:57:51.954  5622  5668 I jxcore-log: 
,10-26 16:57:51.961  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-26 16:57:51.961  5622  5668 I jxcore-log: 
,10-26 16:57:51.967  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-26 16:57:51.967  5622  5668 I jxcore-log: 
,10-26 16:57:51.982  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-26 16:57:51.982  5622  5668 I jxcore-log: 
,10-26 16:57:51.987  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-26 16:57:51.987  5622  5668 I jxcore-log: 
,10-26 16:57:51.992  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-26 16:57:51.992  5622  5668 I jxcore-log: 
,10-26 16:57:51.998  5622  5668 I jxcore-log: 2016-10-26 20:57:51 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-26 16:57:51.998  5622  5668 I jxcore-log: 
,10-26 16:57:52.010  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
10-26 16:57:52.010  5622  5668 I jxcore-log: 
,10-26 16:57:52.016  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-26 16:57:52.016  5622  5668 I jxcore-log: 
,10-26 16:57:52.038  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-26 16:57:52.038  5622  5668 I jxcore-log: 
,10-26 16:57:52.049  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-26 16:57:52.049  5622  5668 I jxcore-log: 
,10-26 16:57:52.060  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-26 16:57:52.060  5622  5668 I jxcore-log: 
,10-26 16:57:52.070  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-26 16:57:52.070  5622  5668 I jxcore-log: 
,10-26 16:57:52.083  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-26 16:57:52.083  5622  5668 I jxcore-log: 
,10-26 16:57:52.093  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-26 16:57:52.093  5622  5668 I jxcore-log: 
,10-26 16:57:52.099  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-26 16:57:52.099  5622  5668 I jxcore-log: 
,10-26 16:57:52.121  5622  5668 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-26 16:57:52.122  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - INFO testUtils: 'BLE multiple advertisement supported'
10-26 16:57:52.122  5622  5668 I jxcore-log: 
,10-26 16:57:52.280  5622  5668 I jxcore-log: 2016-10-26 20:57:52 - DEBUG CoordinatedClient: 'connected to the test server'
10-26 16:57:52.280  5622  5668 I jxcore-log: 
,10-26 16:58:12.373   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 16:58:13.426   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-26 16:58:13.426   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-26 16:58:28.427   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:29.429   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:30.430   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:31.431   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:32.432   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:33.433   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-26 16:58:38.434   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:39.436   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:40.438   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:41.439   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:42.441   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:43.441   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-26 16:58:52.378   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 16:58:53.443   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:54.445   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:55.446   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:56.448   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:57.449   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:58:58.450   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-26 16:59:12.380   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 16:59:13.451   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:14.452   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:15.453   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:16.454   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:17.455   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:18.000   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 16:59:18.456   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-26 16:59:24.058   931  2973 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,10-26 16:59:38.458   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:39.459   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:40.460   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:41.461   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:42.463   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 16:59:43.463   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-26 16:59:52.382   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 17:00:08.464   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-26 17:00:08.464   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-26 17:00:12.384   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 17:00:28.466   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:29.467   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:30.468   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:31.469   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:32.385   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 17:00:32.471   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:33.471   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-26 17:00:38.473   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:39.474   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:40.475   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:41.477   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:42.478   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:43.479   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-26 17:00:53.480   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:54.482   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:55.484   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:56.485   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:57.486   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:00:58.487   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-26 17:01:07.761  5622  5668 I jxcore-log: 2016-10-26 21:01:07 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-26 17:01:07.761  5622  5668 I jxcore-log: 
,10-26 17:01:08.362  5622  5668 I jxcore-log: 2016-10-26 21:01:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:08.362  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:08.362  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:08.362  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:08.362  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:08.362  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:08.362  5622  5668 I jxcore-log: 
,10-26 17:01:08.370  5622  5668 I jxcore-log: 2016-10-26 21:01:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:08.370  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:08.370  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:08.370  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:08.370  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:08.370  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:08.370  5622  5668 I jxcore-log: 
,10-26 17:01:08.638  5622  5668 I jxcore-log: 2016-10-26 21:01:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:08.638  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:08.638  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:08.638  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:08.638  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:08.638  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:08.638  5622  5668 I jxcore-log: 
,10-26 17:01:08.643  5622  5668 I jxcore-log: 2016-10-26 21:01:08 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:08.643  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:08.643  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:08.643  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:08.643  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:08.643  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:08.643  5622  5668 I jxcore-log: 
,10-26 17:01:09.554  5622  5668 I jxcore-log: 2016-10-26 21:01:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:09.554  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:09.554  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:09.554  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:09.554  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:09.554  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:09.554  5622  5668 I jxcore-log: 
,10-26 17:01:09.558  5622  5668 I jxcore-log: 2016-10-26 21:01:09 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:09.558  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:09.558  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:09.558  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:09.558  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:09.558  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:09.558  5622  5668 I jxcore-log: 
,10-26 17:01:10.613  5622  5668 I jxcore-log: 2016-10-26 21:01:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:10.613  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:10.613  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:10.613  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:10.613  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:10.613  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:10.613  5622  5668 I jxcore-log: 
,10-26 17:01:10.617  5622  5668 I jxcore-log: 2016-10-26 21:01:10 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:10.617  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:10.617  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:10.617  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:10.617  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:10.617  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:10.617  5622  5668 I jxcore-log: 
,10-26 17:01:11.677  5622  5668 I jxcore-log: 2016-10-26 21:01:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:11.677  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:11.677  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:11.677  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:11.677  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:11.677  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:11.677  5622  5668 I jxcore-log: 
,10-26 17:01:11.681  5622  5668 I jxcore-log: 2016-10-26 21:01:11 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:11.681  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:11.681  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:11.681  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:11.681  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:11.681  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:11.681  5622  5668 I jxcore-log: 
,10-26 17:01:12.390   931  2971 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-26 17:01:12.704  5622  5668 I jxcore-log: 2016-10-26 21:01:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:12.704  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:12.704  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:12.704  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:12.704  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:12.704  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:12.704  5622  5668 I jxcore-log: 
,10-26 17:01:12.711  5622  5668 I jxcore-log: 2016-10-26 21:01:12 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:12.711  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:12.711  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:12.711  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:12.711  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:12.711  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:12.711  5622  5668 I jxcore-log: 
,10-26 17:01:13.488   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:01:13.748  5622  5668 I jxcore-log: 2016-10-26 21:01:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:13.748  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:13.748  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:13.748  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:13.748  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:13.748  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:13.748  5622  5668 I jxcore-log: 
,10-26 17:01:13.752  5622  5668 I jxcore-log: 2016-10-26 21:01:13 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:13.752  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:13.752  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:13.752  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:13.752  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:13.752  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:13.752  5622  5668 I jxcore-log: 
,10-26 17:01:14.490   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:01:14.801  5622  5668 I jxcore-log: 2016-10-26 21:01:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:14.801  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:14.801  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:14.801  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:14.801  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:14.801  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:14.801  5622  5668 I jxcore-log: 
,10-26 17:01:14.807  5622  5668 I jxcore-log: 2016-10-26 21:01:14 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:14.807  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:14.807  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:14.807  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:14.807  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:14.807  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:14.807  5622  5668 I jxcore-log: 
,10-26 17:01:15.491   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:01:16.434  5622  5668 I jxcore-log: 2016-10-26 21:01:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:16.434  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:16.434  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:16.434  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:16.434  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:16.434  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:16.434  5622  5668 I jxcore-log: 
,10-26 17:01:16.442  5622  5668 I jxcore-log: 2016-10-26 21:01:16 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:16.442  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:16.442  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:16.442  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:16.442  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:16.442  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:16.442  5622  5668 I jxcore-log: 
,10-26 17:01:16.492   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:01:17.493   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,10-26 17:01:17.510  5622  5668 I jxcore-log: 2016-10-26 21:01:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:17.510  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:17.510  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:17.510  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:17.510  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:17.510  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:17.510  5622  5668 I jxcore-log: 
,10-26 17:01:17.514  5622  5668 I jxcore-log: 2016-10-26 21:01:17 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:17.514  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:17.514  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:17.514  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:17.514  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:17.514  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:17.514  5622  5668 I jxcore-log: 
,10-26 17:01:17.844   931  5960 D NetlinkSocketObserver: NeighborEvent{elapsedMs=514610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-26 17:01:18.494   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-26 17:01:18.556  5622  5668 I jxcore-log: 2016-10-26 21:01:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:18.556  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:18.556  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:18.556  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:18.556  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:18.556  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:18.556  5622  5668 I jxcore-log: 
,10-26 17:01:18.563  5622  5668 I jxcore-log: 2016-10-26 21:01:18 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:18.563  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:18.563  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:18.563  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:18.563  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:18.563  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:18.563  5622  5668 I jxcore-log: 
,10-26 17:01:19.604  5622  5668 I jxcore-log: 2016-10-26 21:01:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:19.604  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:19.604  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:19.604  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:19.604  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:19.604  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:19.604  5622  5668 I jxcore-log: 
,10-26 17:01:19.610  5622  5668 I jxcore-log: 2016-10-26 21:01:19 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:19.610  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:19.610  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:19.610  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:19.610  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:19.610  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:19.610  5622  5668 I jxcore-log: 
,10-26 17:01:20.647  5622  5668 I jxcore-log: 2016-10-26 21:01:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:20.647  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:20.647  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:20.647  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:20.647  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:20.647  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:20.647  5622  5668 I jxcore-log: 
,10-26 17:01:20.654  5622  5668 I jxcore-log: 2016-10-26 21:01:20 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:20.654  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:20.654  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:20.654  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:20.654  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:20.654  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:20.654  5622  5668 I jxcore-log: 
,10-26 17:01:21.691  5622  5668 I jxcore-log: 2016-10-26 21:01:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:21.691  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:21.691  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:21.691  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:21.691  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:21.691  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:21.691  5622  5668 I jxcore-log: 
,10-26 17:01:21.695  5622  5668 I jxcore-log: 2016-10-26 21:01:21 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:21.695  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:21.695  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:21.695  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:21.695  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:21.695  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:21.695  5622  5668 I jxcore-log: 
,10-26 17:01:22.726  5622  5668 I jxcore-log: 2016-10-26 21:01:22 - ERROR CoordinatedClient: ' Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
10-26 17:01:22.726  5622  5668 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
10-26 17:01:22.726  5622  5668 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
10-26 17:01:22.726  5622  5668 I jxcore-log: emit@events.js:82:1
10-26 17:01:22.726  5622  5668 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
10-26 17:01:22.726  5622  5668 I jxcore-log: emit@events.js:82:1'
10-26 17:01:22.726  5622  5668 I jxcore-log: 
,10-26 17:01:22.734  5622  5668 E jxcore  : Error!: error is undefined
10-26 17:01:22.734  5622  5668 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js","_functionName":"CoordinatedClient.prototype._error","_lineNumber":"220","_columnNumber":"1","_msg":"    at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"131","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js","_functionName":"Socket.prototype.emit","_lineNumber":"133","_columnNumber":"5","_msg":"    at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.emitAll","_lineNumber":"81","_columnNumber":"7","_msg":"    at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect","_lineNumber":"507","_columnNumber":"5","_msg":"    at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.reconnect/timer</<","_lineNumber":"528","_columnNumber":"11","_msg":"    at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js","_functionName":"Manager.prototype.connect/errorSub<","_lineNumber":"235","_columnNumber":"7","_msg":"    at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:235:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js","_functionName":"Emitter.prototype.emit","_lineNumber":"134","_columnNumber":"7","_msg":"    at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/node_modules/component-emitter/index.js:134:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js","_functionName":"Socket.prototype.onError","_lineNumber":"670","_columnNumber":"3","_msg":"    at Socket.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/socket.js:670:3"}]
,10-26 17:01:22.737  5622  5668 I jxcore-log: 2016-10-26 21:01:22 - ERROR TestsProcess: 'uncaught exception, error: 'TypeError: error is undefined', stack: 'TypeError: error is undefined
10-26 17:01:22.737  5622  5668 I jxcore-log:     at CoordinatedClient.prototype._error@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:220:1
10-26 17:01:22.737  5622  5668 I jxcore-log:     at Emitter.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/component-emitter/index.js:131:7
10-26 17:01:22.737  5622  5668 I jxcore-log:     at Socket.prototype.emit@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/socket.js:133:5
10-26 17:01:22.737  5622  5668 I jxcore-log:     at Manager.prototype.emitAll@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:81:7
10-26 17:01:22.737  5622  5668 I jxcore-log:     at Manager.prototype.reconnect@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:507:5
10-26 17:01:22.737  5622  5668 I jxcore-log:     at Manager.prototype.reconnect/timer</<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/socket.io-client/lib/manager.js:528:11
10-26 17:01:22.737  5622  5668 I jxcore-log:     at Manager.prototype.connect/errorSub<@/data/data/com.test.thalitest/files/www/jxcore/node_modules/sock
10-26 17:01:22.738  5622  5668 I jxcore-log: 2016-10-26 21:01:22 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-26 17:01:22.738  5622  5668 I jxcore-log: 
,10-26 17:01:22.741  5622  5668 E jxcore-log: TypeError: 
10-26 17:01:22.741  5622  5668 E jxcore-log: error is undefined
10-26 17:01:22.741  5622  5668 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js 220:0)
10-26 17:01:22.741  5622  5668 E jxcore-log: 
,10-26 17:01:22.808   931  2948 W InputDispatcher: channel 'e45bafd com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
10-26 17:01:22.808   931  2948 E InputDispatcher: channel 'e45bafd com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,10-26 17:01:22.813   931  3585 I WindowState: WIN DEATH: Window{e45bafd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-26 17:01:22.814   931  3585 W InputDispatcher: Attempted to unregister already unregistered input channel 'e45bafd com.test.thalitest/com.test.thalitest.MainActivity (server)'
10-26 17:01:22.814   931  2972 D WifiService: Client connection lost with reason: 4
10-26 17:01:22.816   931  3772 D GraphicsStats: Buffer count: 2
,10-26 17:01:22.824   528   528 I Zygote  : Process 5622 exited cleanly (139)
,10-26 17:01:22.825   931  3183 I ActivityManager: Process com.test.thalitest (pid 5622) has died
,10-26 17:01:22.843   931  3183 I ActivityManager: Start proc 6004:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
,10-26 17:01:23.173   931  3887 I WindowManager: Screenshot max retries 4 of Token{4faecc7 ActivityRecord{8a0be06 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{32fe536 u0 Starting com.test.thalitest} drawState=4
,10-26 17:01:23.250  6004  6004 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-26 17:01:23.267  6004  6004 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-26 17:01:23.273  6004  6004 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 38-40)
,10-26 17:01:23.273  6004  6004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 17:01:23.281  6004  6004 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b4bfb61}
10-26 17:01:23.281  6004  6004 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-26 17:01:23.282  6004  6004 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-26 17:01:23.285  6004  6004 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-26 17:01:23.286  6004  6004 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-26 17:01:23.296  6004  6004 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-26 17:01:23.304  6004  6004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-26 17:01:23.304  6004  6004 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-26 17:01:23.304  6004  6004 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-26 17:01:23.304  6004  6004 I Adreno  : Build Date                       : 12/06/15
10-26 17:01:23.304  6004  6004 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-26 17:01:23.304  6004  6004 I Adreno  : Local Branch                     : mybranch17112971
10-26 17:01:23.304  6004  6004 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-26 17:01:23.304  6004  6004 I Adreno  : Remote Branch                    : NONE
10-26 17:01:23.304  6004  6004 I Adreno  : Reconstruct Branch               : NOTHING
,10-26 17:01:23.310  6002  6002 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-26 17:01:23.332  6002  6002 D AndroidRuntime: CheckJNI is OFF
,10-26 17:01:23.341   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f37b2f:true
,10-26 17:01:23.349  3438  3438 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34028]" dev="sockfs" ino=34028 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 17:01:23.349  3438  3438 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34028]" dev="sockfs" ino=34028 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 17:01:23.360  6002  6002 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-26 17:01:23.364  6004  6004 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-26 17:01:23.372  6004  6004 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-26 17:01:23.384  6002  6002 I Radio-JNI: register_android_hardware_Radio DONE
,10-26 17:01:23.396   405   405 W Binder_2: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[30636]" dev="sockfs" ino=30636 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-26 17:01:23.396   405   405 W Binder_2: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[30636]" dev="sockfs" ino=30636 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-26 17:01:23.399  6002  6002 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-26 17:01:23.400  6004  6046 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-26 17:01:23.399  3585  3585 W Binder_6: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[13805]" dev="sockfs" ino=13805 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 17:01:23.407  6004  6028 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
10-26 17:01:23.399  3585  3585 W Binder_6: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[13805]" dev="sockfs" ino=13805 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-26 17:01:23.411   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
10-26 17:01:23.411   931   944 I ActivityManager: Killing 6004:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-26 17:01:23.441   931  3119 I WindowState: WIN DEATH: Window{ff567ca u0 com.test.thalitest/com.test.thalitest.MainActivity}
10-26 17:01:23.441   931   941 D GraphicsStats: Buffer count: 2
,10-26 17:01:23.449   931   944 W ActivityManager: Force removing ActivityRecord{8a0be06 u0 com.test.thalitest/.MainActivity t2}: app died, no saved state
,10-26 17:01:23.461   931  3887 W ActivityManager: Spurious death for ProcessRecord{1c72c58 0:com.test.thalitest/u0a77}, curProc for 6004: null
,10-26 17:01:23.524   931   954 I art     : Starting a blocking GC Explicit
,10-26 17:01:23.536   931  5960 D NetlinkSocketObserver: NeighborEvent{elapsedMs=520303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,10-26 17:01:23.631   931   954 I art     : Explicit concurrent mark sweep GC freed 107511(7MB) AllocSpace objects, 67(2MB) LOS objects, 33% free, 29MB/43MB, paused 1.627ms total 106.668ms
,10-26 17:01:23.650   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-26 17:01:23.653  6002  6002 I art     : System.exit called, status: 0
,10-26 17:01:23.653  6002  6002 I AndroidRuntime: VM exiting with result code 0.
,10-26 17:01:23.668   931   954 I ActivityManager: Start proc 6050:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-26 17:01:23.669   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-26 17:01:23.675  5902  5902 D BluetoothMapAppObserver: onReceive
,10-26 17:01:23.675  5902  5902 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-26 17:01:23.680  3875  4083 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-26 17:01:23.690  3634  3634 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-26 17:01:23.717  3634  6062 I Keyboard.Facilitator.DecoderInitializer: run()
,10-26 17:01:23.720  3385  6063 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-26 17:01:23.726  3722  3722 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-26 17:01:23.740   931  2949 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-26 17:01:23.751  3569  3569 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,10-26 17:01:23.751  3569  3569 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
10-26 17:01:23.759   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-26 17:01:23.765  3634  6062 I Decoder : createOrResetDecoder
,10-26 17:01:23.763   445   445 W kworker/3:2: type=1400 audit(0.0:122): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 17:01:23.767  4025  6069 D AccountUtils: Clearing selected account for com.test.thalitest
,10-26 17:01:23.769   445   445 W kworker/3:2: type=1400 audit(0.0:123): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 17:01:23.786   445   445 W kworker/3:2: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-26 17:01:23.815  3385  3408 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
10-26 17:01:23.815  3385  3408 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj53125593B) - 
,--------- beginning of crash
10-26 17:01:23.816  3385  3408 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-26 17:01:23.816  3385  3408 E AndroidRuntime: Process: android.process.acore, PID: 3385
10-26 17:01:23.816  3385  3408 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-26 17:01:23.816  3385  3408 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-26 17:01:23.823   931  6072 E DropBoxManagerService: Can't write: system_app_crash
10-26 17:01:23.823   931  6072 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-26 17:01:23.823   931  6072 E DropBoxManagerService: 	... 5 more
,10-26 17:01:23.837  3569  3569 I ConfigService: onCreate
,10-26 17:01:23.840  3569  6073 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-26 17:01:23.840  3569  6073 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-26 17:01:23.840  3569  6073 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-26 17:01:23.842  3569  6073 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-26 17:01:23.847  4025  6069 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-26 17:01:23.867  3385  6063 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-26 17:01:23.868  3385  6063 I Process : Sending signal. PID: 3385 SIG: 9
,10-26 17:01:23.874  4025  6069 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-26 17:01:23.874  4025  6069 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-26 17:01:23.874  4025  6069 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-26 17:01:23.875  4025  6069 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-26 17:01:23.880  3634  6062 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-26 17:01:23.958  4025  6077 I GMPM-SVC: App measurement is starting up
,10-26 17:01:23.966  4025  6077 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-26 17:01:23.967  4025  6077 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-26 17:01:24.011   931  3585 I ActivityManager: Process android.process.acore (pid 3385) has died
,10-26 17:01:24.011   931  3585 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-26 17:01:24.189   382   480 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
