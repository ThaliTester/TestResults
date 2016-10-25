#### Test 90793797671d7b3_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-25 08:27:37.509   927  5533 D NetlinkSocketObserver: NeighborEvent{elapsedMs=197598, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,10-25 08:27:37.969  5913  5913 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-25 08:27:37.975  5913  5913 D AndroidRuntime: CheckJNI is OFF
10-25 08:27:38.003  5913  5913 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-25 08:27:38.035  5913  5913 I Radio-JNI: register_android_hardware_Radio DONE
10-25 08:27:38.050  5913  5913 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-25 08:27:38.062   927  3314 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-25 08:27:38.107   927  3314 I ActivityManager: Start proc 5922:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-25 08:27:38.112  5913  5913 D AndroidRuntime: Shutting down VM
,10-25 08:27:38.453   927   937 I WindowManager: Screenshot max retries 4 of Token{283695b ActivityRecord{8c9c06a u0 com.test.thalitest/.MainActivity t2}} appWin=Window{f3df2c2 u0 Starting com.test.thalitest} drawState=2
,10-25 08:27:38.546  5922  5922 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-25 08:27:38.575  5922  5922 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-25 08:27:38.603  5922  5922 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 8673-8693)
,10-25 08:27:38.604  5922  5922 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-25 08:27:38.622  5922  5922 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {721579d}
,10-25 08:27:38.622  5922  5922 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-25 08:27:38.622  5922  5922 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
10-25 08:27:38.626  5922  5922 I BrowserStartupController: Initializing chromium process, singleProcess=true
10-25 08:27:38.627  5922  5922 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-25 08:27:38.659  5922  5922 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-25 08:27:38.674  5922  5922 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-25 08:27:38.674  5922  5922 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-25 08:27:38.674  5922  5922 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-25 08:27:38.674  5922  5922 I Adreno  : Build Date                       : 12/06/15
10-25 08:27:38.674  5922  5922 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-25 08:27:38.674  5922  5922 I Adreno  : Local Branch                     : mybranch17112971
10-25 08:27:38.674  5922  5922 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-25 08:27:38.674  5922  5922 I Adreno  : Remote Branch                    : NONE
10-25 08:27:38.674  5922  5922 I Adreno  : Reconstruct Branch               : NOTHING
,10-25 08:27:38.727   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b414a41:true
,10-25 08:27:38.764   756   756 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[24279]" dev="sockfs" ino=24279 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 08:27:38.764   756   756 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[24279]" dev="sockfs" ino=24279 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 08:27:38.779  5922  5922 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-25 08:27:38.788  5922  5922 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-25 08:27:38.807   756   756 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34298]" dev="sockfs" ino=34298 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-25 08:27:38.807   756   756 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[34298]" dev="sockfs" ino=34298 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-25 08:27:38.813  5922  5959 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-25 08:27:38.811  3711  3711 W Binder_6: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[24290]" dev="sockfs" ino=24290 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 08:27:38.811  3711  3711 W Binder_6: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[24290]" dev="sockfs" ino=24290 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-25 08:27:38.819  5922  5946 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-25 08:27:38.840  5922  5959 I OpenGLRenderer: Initialized EGL, version 1.4
,10-25 08:27:38.903   927   945 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +448ms (total +823ms)
,10-25 08:27:38.947  5922  5922 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5922
,10-25 08:27:39.074  5922  5922 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,10-25 08:27:39.187  5922  5961 D jxcore_app_log: JniHelper::setJavaVM(0xf4ebc000), pthread_self() = -585369296
,10-25 08:27:39.190  5922  5961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-25 08:27:39.190  5922  5961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-25 08:27:39.190  5922  5961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-25 08:27:39.190  5922  5961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-25 08:27:39.190  5922  5961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
10-25 08:27:39.190  5922  5961 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d65001b added. We now have 1 listener(s)
,10-25 08:27:39.193  5922  5961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,10-25 08:27:39.193  5922  5961 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-25 08:27:39.194  5922  5961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-25 08:27:39.194  5922  5961 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-25 08:27:39.196  5922  5961 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b00ef6 added. We now have 1 listener(s)
10-25 08:27:39.197  5922  5961 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 08:27:39.201   927  3085 D WifiService: New client listening to asynchronous messages
,10-25 08:27:39.201  5922  5961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 08:27:39.201  5922  5961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
10-25 08:27:39.201  5922  5961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
10-25 08:27:39.201  5922  5961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,10-25 08:27:39.201  5922  5961 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-25 08:27:39.203  5922  5961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:27:39.203  5922  5961 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-25 08:27:39.207  5922  5961 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 08:27:39.207  5922  5961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 08:27:39.207  5922  5961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,10-25 08:27:39.207  5922  5961 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 08:27:39.207  5922  5961 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-25 08:27:39.210  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:27:39.213  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:27:39.256  5922  5922 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-25 08:27:39.479  5922  5931 I art     : Background sticky concurrent mark sweep GC freed 85650(8MB) AllocSpace objects, 16(1044KB) LOS objects, 20% free, 25MB/32MB, paused 2.018ms total 110.333ms
,10-25 08:27:39.728  5922  5931 I art     : Background partial concurrent mark sweep GC freed 58414(6MB) AllocSpace objects, 3(2MB) LOS objects, 35% free, 28MB/44MB, paused 2.182ms total 128.057ms
,10-25 08:27:39.814  5922  5968 W jxcore-log: Initializing JXcore engine
,10-25 08:27:39.814  5922  5968 W jxcore-log: JXcore engine is ready
,10-25 08:27:39.834  5968  5968 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11534 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-25 08:27:39.834  5968  5968 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[16386]" dev="sockfs" ino=16386 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-25 08:27:39.834  5968  5968 W Thread-61: type=1400 audit(0.0:110): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=6252 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
10-25 08:27:39.834  5968  5968 W Thread-61: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34272]" dev="sockfs" ino=34272 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-25 08:27:39.846  5922  5968 W jxcore-log: Starting JXcore engine
,10-25 08:27:39.896  5922  5968 W jxcore-log: Platform android
10-25 08:27:39.896  5922  5968 W jxcore-log: 
,10-25 08:27:39.896  5922  5968 W jxcore-log: Process ARCH arm
10-25 08:27:39.896  5922  5968 W jxcore-log: 
,10-25 08:27:39.947   927  3077 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-25 08:27:40.078  5922  5968 I jxcore-log: JXcore Cordova bridge is ready!
10-25 08:27:40.078  5922  5968 I jxcore-log: 
,10-25 08:27:40.079  5922  5968 W jxcore-log: JXcore engine is started
,10-25 08:27:40.089  5922  5961 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-25 08:27:40.097  5922  5922 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-25 08:27:49.772  5922  5968 I jxcore-log: 2016-10-25 12:27:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-25 08:27:49.772  5922  5968 I jxcore-log: 
,10-25 08:27:49.774  5922  5968 I jxcore-log: 2016-10-25 12:27:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-25 08:27:49.774  5922  5968 I jxcore-log: 
,10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 08:27:49.779  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 08:27:49.780  5922  5968 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 08:27:49.782  5922  5968 I jxcore-log: 2016-10-25 12:27:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-25 08:27:49.782  5922  5968 I jxcore-log: 
10-25 08:27:49.783  5922  5968 I jxcore-log: 2016-10-25 12:27:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-25 08:27:49.783  5922  5968 I jxcore-log: 
,10-25 08:27:50.024  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 08:27:50.024  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b5030f added. We now have 2 listener(s)
,10-25 08:27:50.025  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-25 08:27:50.025  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 08:27:50.025  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 08:27:50.025  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 08:27:50.025  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9b0f9c added. We now have 2 listener(s)
,10-25 08:27:50.025  5922  5968 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 08:27:50.026  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-25 08:27:50.027  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 08:27:50.031  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-25 08:27:50.031  5922  5968 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 08:27:50.032  5922  5968 D io.jxcore.node.ConnectivityMonitor: start: OK
10-25 08:27:50.032  5922  5968 D ExecuteNativeTests: Running unit tests
10-25 08:27:50.033  5922  5968 D BluetoothAdapter: enable(): BT is already enabled..!
,10-25 08:27:50.033   927   937 D WifiService: setWifiEnabled: true pid=5922, uid=10077
,10-25 08:27:50.033   927   937 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 08:27:50.040  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:27:50.045  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:27:57.357   603   603 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,10-25 08:27:57.357   603   603 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,10-25 08:27:59.949   927  3077 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-25 08:28:00.040  5922  5968 I com.test.thalitest.ThaliTestRunner: Running UT
,10-25 08:28:00.098  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 08:28:00.098  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcfedce added. We now have 3 listener(s)
10-25 08:28:00.098  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-25 08:28:00.099  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 08:28:00.099  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-25 08:28:00.099  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 08:28:00.099  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75134ef added. We now have 3 listener(s)
10-25 08:28:00.099  5922  5968 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 08:28:00.099  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 08:28:00.101  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 08:28:00.104  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 08:28:00.105  5922  5968 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-25 08:28:00.105  5922  5968 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-25 08:28:00.108  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:00.109  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:00.109  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,10-25 08:28:00.109  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-25 08:28:00.109  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:00.109  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:00.109  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:00.110  5922  5968 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,10-25 08:28:00.110  5922  5968 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-25 08:28:00.110  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-25 08:28:00.110  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 08:28:00.110  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 08:28:00.110  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 08:28:00.111  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
10-25 08:28:00.111  5922  5968 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,10-25 08:28:00.112  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,10-25 08:28:00.114  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-25 08:28:00.114  5922  5968 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-25 08:28:00.114  5922  5968 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-25 08:28:00.114  5922  5968 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
10-25 08:28:00.114  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
10-25 08:28:00.114  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:00.115  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 08:28:00.115  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 08:28:00.115  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 08:28:00.115  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 08:28:00.116  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-25 08:28:00.116  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 08:28:00.116  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 08:28:00.116  5922  5970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-25 08:28:00.116  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 08:28:00.117  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,10-25 08:28:00.117  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:00.117  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 08:28:00.117  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 08:28:00.119  5922  5970 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:00.119  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-25 08:28:00.119  5922  5968 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-25 08:28:00.119  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 08:28:00.114  4944  4944 W Binder_5: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[35086]" dev="sockfs" ino=35086 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 08:28:00.121  5922  5970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 08:28:00.117  4944  4944 W Binder_5: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[35086]" dev="sockfs" ino=35086 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 08:28:00.122  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 08:28:00.123  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 08:28:00.123  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 08:28:00.124  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.124  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-25 08:28:00.125  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-25 08:28:00.125  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
10-25 08:28:00.125  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 08:28:00.126  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.126  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.126  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.126  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.126  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:00.129  4724  4739 D BtGatt.GattService: registerClient() - UUID=ec8e7701-5c89-40e9-87d8-635f36fbb026
,10-25 08:28:00.130  4724  4785 D BtGatt.GattService: onClientRegistered() - UUID=ec8e7701-5c89-40e9-87d8-635f36fbb026, clientIf=5
,10-25 08:28:00.130  5922  5933 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-25 08:28:00.132  4724  4789 D BtGatt.AdvertiseManager: message : 0
10-25 08:28:00.133  4724  4789 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 08:28:00.144  4724  4785 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 08:28:00.150  4724  4785 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 08:28:00.152  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.152  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.152  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 08:28:00.152  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.153  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.153  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.153  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.153  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.153  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-25 08:28:00.154  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-25 08:28:00.154  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.155  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.155  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.155  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.156  5922  5968 I io.jxcore.node.ConnectionHelper: start: OK
10-25 08:28:00.156  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:00.156  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.156  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:00.156  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 08:28:00.156  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.157  5922  5922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:00.157  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.157  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 08:28:00.157  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
,10-25 08:28:00.157  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.157  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.157  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 08:28:00.157  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-25 08:28:00.159  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-25 08:28:00.159  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 08:28:00.160  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.160  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.160  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.160  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:00.160  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 08:28:00.658  5922  5968 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,10-25 08:28:00.659  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,10-25 08:28:00.660  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-25 08:28:00.660  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-25 08:28:00.660  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-25 08:28:00.660  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-25 08:28:00.660  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-25 08:28:00.660  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-25 08:28:00.660  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-25 08:28:00.661  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-25 08:28:00.661  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-25 08:28:00.662  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,10-25 08:28:00.662  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-25 08:28:00.662  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-25 08:28:00.662  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 08:28:00.662  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-25 08:28:00.662  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-25 08:28:00.662  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-25 08:28:00.662  5922  5922 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 08:28:00.664  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-25 08:28:00.665  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-25 08:28:00.665  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 08:28:00.665  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 08:28:00.665  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-25 08:28:00.665  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 08:28:00.666  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 08:28:00.666  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 08:28:00.666  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 08:28:00.666  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 08:28:00.666  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 08:28:00.666  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 08:28:00.666  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 08:28:00.667  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.667  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.669  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:00.669  5922  5970 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 08:28:00.669  5922  5968 D BluetoothLeScanner: could not find callback wrapper
10-25 08:28:00.669  5922  5970 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 08:28:00.669  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 08:28:00.670  5922  5970 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-25 08:28:00.670  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.670  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.670  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 08:28:00.670  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.671  4724  4789 D BtGatt.AdvertiseManager: message : 1
10-25 08:28:00.672  4724  4789 D BtGatt.AdvertiseManager: stop advertise for client 5
10-25 08:28:00.684  4724  4785 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-25 08:28:00.685  4724  4785 D BtGatt.GattService: Client app is not null!
10-25 08:28:00.685  4724  4935 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 08:28:00.686  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-25 08:28:00.686  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.686  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 08:28:00.686  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.686  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.686  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.687  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-25 08:28:00.687  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 08:28:00.687  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.687  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.687  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 08:28:00.687  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.689  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 08:28:00.689  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 08:28:00.690  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 08:28:00.690  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.691  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.692  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.692  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.692  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 08:28:00.692  5922  5922 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 08:28:00.692  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-25 08:28:00.692  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-25 08:28:00.692  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-25 08:28:00.692  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 08:28:00.692  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 08:28:00.693  5922  5968 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-25 08:28:00.693  5922  5968 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-25 08:28:00.693  5922  5968 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-25 08:28:00.693  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-25 08:28:00.694  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:00.694  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 08:28:00.694  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 08:28:00.694  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:00.695  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 08:28:00.695  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 08:28:00.695  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 08:28:00.695  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 08:28:00.696  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 08:28:00.696  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 08:28:00.696  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-25 08:28:00.696  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:00.696  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 08:28:00.701  5922  5973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 08:28:00.701  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 08:28:00.701  5922  5968 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 08:28:00.701  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 08:28:00.702  5922  5973 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:00.701  4935  4935 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[35091]" dev="sockfs" ino=35091 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 08:28:00.701  4935  4935 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[35091]" dev="sockfs" ino=35091 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 08:28:00.704  5922  5973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 08:28:00.706  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 08:28:00.707  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 08:28:00.707  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 08:28:00.709  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.709  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 08:28:00.709  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-25 08:28:00.709  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
10-25 08:28:00.709  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 08:28:00.709  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.709  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.709  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.709  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.710  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:00.712  4724  4738 D BtGatt.GattService: registerClient() - UUID=45bdf277-7b9e-46f5-a901-3388595c8d20
10-25 08:28:00.713  4724  4785 D BtGatt.GattService: onClientRegistered() - UUID=45bdf277-7b9e-46f5-a901-3388595c8d20, clientIf=5
10-25 08:28:00.713  5922  5933 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-25 08:28:00.714  4724  4789 D BtGatt.AdvertiseManager: message : 0
10-25 08:28:00.716  4724  4789 D BtGatt.AdvertiseManager: starting multi advertising
10-25 08:28:00.726  4724  4785 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
10-25 08:28:00.731  4724  4785 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-25 08:28:00.732  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.732  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.732  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 08:28:00.732  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.732  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.732  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.732  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.732  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.732  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 08:28:00.734  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 08:28:00.734  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.735  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.735  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.735  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:00.735  5922  5968 I io.jxcore.node.ConnectionHelper: start: OK
10-25 08:28:00.735  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.736  5922  5922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.736  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 08:28:00.736  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.739  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-25 08:28:00.739  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 08:28:00.739  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.739  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.739  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 08:28:00.739  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:00.739  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 08:28:01.239  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
10-25 08:28:01.239  5922  5968 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-25 08:28:01.239  5922  5968 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-25 08:28:01.240  5922  5968 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-25 08:28:01.240  5922  5968 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-25 08:28:01.240  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
10-25 08:28:01.240  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-25 08:28:01.241  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,10-25 08:28:01.241  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.243  4724  4789 D BtGatt.AdvertiseManager: message : 1
10-25 08:28:01.244  4724  4789 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 08:28:01.260  4724  4785 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-25 08:28:01.260  4724  4785 D BtGatt.GattService: Client app is not null!
10-25 08:28:01.261  4724  4738 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 08:28:01.261  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-25 08:28:01.261  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.261  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 08:28:01.261  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.261  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.261  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 08:28:01.261  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.262  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-25 08:28:01.262  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-25 08:28:01.262  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
10-25 08:28:01.262  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-25 08:28:01.262  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.262  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.262  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.262  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.263  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:01.266  4724  4935 D BtGatt.GattService: registerClient() - UUID=d91ff0cf-f03b-4e12-9a4b-c99c53f2e93a
10-25 08:28:01.267  4724  4785 D BtGatt.GattService: onClientRegistered() - UUID=d91ff0cf-f03b-4e12-9a4b-c99c53f2e93a, clientIf=5
10-25 08:28:01.267  5922  5932 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-25 08:28:01.268  4724  4789 D BtGatt.AdvertiseManager: message : 0
,10-25 08:28:01.273  4724  4789 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 08:28:01.285  4724  4785 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 08:28:01.292  4724  4785 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 08:28:01.293  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.293  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.294  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,10-25 08:28:01.294  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.294  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.294  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.294  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.294  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.294  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 08:28:01.294  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 08:28:01.294  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 08:28:01.294  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
10-25 08:28:01.294  5922  5968 I io.jxcore.node.ConnectionHelper: start: OK
10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.295  5922  5922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 08:28:01.295  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,10-25 08:28:01.296  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.296  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:01.297  5922  5968 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-25 08:28:01.298  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-25 08:28:01.298  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,10-25 08:28:01.298  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 08:28:01.298  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 08:28:01.298  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-25 08:28:01.298  5922  5973 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 08:28:01.298  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 08:28:01.298  5922  5973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 08:28:01.298  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 08:28:01.298  5922  5973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 08:28:01.298  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-25 08:28:01.298  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 08:28:01.298  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 08:28:01.298  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 08:28:01.298  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 08:28:01.298  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 08:28:01.298  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 08:28:01.298  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 08:28:01.299  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.299  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.300  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:01.300  5922  5968 D BluetoothLeScanner: could not find callback wrapper
10-25 08:28:01.300  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 08:28:01.300  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.300  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.300  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 08:28:01.300  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.301  4724  4789 D BtGatt.AdvertiseManager: message : 1
,10-25 08:28:01.302  4724  4789 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 08:28:01.307  4724  4785 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-25 08:28:01.307  4724  4785 D BtGatt.GattService: Client app is not null!
10-25 08:28:01.308  4724  4935 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 08:28:01.308  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.309  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.309  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.309  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 08:28:01.310  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.311  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.311  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 08:28:01.312  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.312  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.312  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.312  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.312  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.312  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 08:28:01.312  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 08:28:01.313  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 08:28:01.313  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.313  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.314  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.314  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.314  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 08:28:01.314  5922  5922 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 08:28:01.314  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:01.314  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:01.314  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 08:28:01.316  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
10-25 08:28:01.316  5922  5968 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-25 08:28:01.317  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
10-25 08:28:01.318  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-25 08:28:01.318  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-25 08:28:01.319  5922  5968 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-25 08:28:01.319  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
10-25 08:28:01.319  5922  5968 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-25 08:28:01.320  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
10-25 08:28:01.320  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1, when trying to connect
10-25 08:28:01.320  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:01.320  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:01.320  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:01.320  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-25 08:28:01.320  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 08:28:01.320  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 08:28:01.320  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-25 08:28:01.321  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,10-25 08:28:01.321  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:01.321  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:01.321  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-25 08:28:01.322  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
10-25 08:28:01.322  5922  5968 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-25 08:28:01.322  5922  5968 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-25 08:28:01.325  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-25 08:28:01.325  5922  5968 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,10-25 08:28:01.326  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
10-25 08:28:01.327  5922  5968 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,10-25 08:28:01.328  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
10-25 08:28:01.328  5922  5968 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
,10-25 08:28:01.328  5922  5968 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-25 08:28:01.328  5922  5968 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-25 08:28:01.328  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-25 08:28:01.328  5922  5968 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-25 08:28:01.329  5922  5968 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-25 08:28:01.329  5922  5968 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-25 08:28:01.329  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 08:28:01.329  5922  5968 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-25 08:28:01.329  5922  5968 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-25 08:28:01.329  5922  5968 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,10-25 08:28:01.329  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 08:28:01.329  5922  5968 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-25 08:28:01.330  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-25 08:28:01.330  5922  5968 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-25 08:28:01.330  5922  5968 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-25 08:28:01.330  5922  5968 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-25 08:28:01.330  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
10-25 08:28:01.330  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-25 08:28:01.330  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,10-25 08:28:01.330  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 08:28:01.330  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:01.331  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 08:28:01.332  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 08:28:01.332  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 08:28:01.332  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 08:28:01.332  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 08:28:01.333  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-25 08:28:01.333  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 08:28:01.333  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:01.333  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 08:28:01.333  5922  5977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-25 08:28:01.334  5922  5977 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:01.334  4935  4935 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[34335]" dev="sockfs" ino=34335 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 08:28:01.334  4935  4935 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[34335]" dev="sockfs" ino=34335 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 08:28:01.337  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-25 08:28:01.337  5922  5968 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 08:28:01.337  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-25 08:28:01.337  5922  5977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 08:28:01.340  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 08:28:01.341  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 08:28:01.341  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 08:28:01.343  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.343  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-25 08:28:01.343  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-25 08:28:01.343  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
,10-25 08:28:01.344  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 08:28:01.344  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.344  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.344  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.344  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.345  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:01.346  4724  4944 D BtGatt.GattService: registerClient() - UUID=f922a689-1411-4144-bfeb-c88158964d2b
10-25 08:28:01.347  4724  4785 D BtGatt.GattService: onClientRegistered() - UUID=f922a689-1411-4144-bfeb-c88158964d2b, clientIf=5
10-25 08:28:01.347  5922  5932 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-25 08:28:01.348  4724  4789 D BtGatt.AdvertiseManager: message : 0
,10-25 08:28:01.350  4724  4789 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 08:28:01.359  4724  4785 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 08:28:01.365  4724  4785 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 08:28:01.365  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.365  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.365  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 08:28:01.365  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.365  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.366  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.366  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.366  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.366  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 08:28:01.367  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-25 08:28:01.367  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.368  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.368  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.368  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.368  5922  5968 I io.jxcore.node.ConnectionHelper: start: OK
10-25 08:28:01.368  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.369  5922  5922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.369  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 08:28:01.369  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-25 08:28:01.372  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.372  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 08:28:01.372  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.372  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.372  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 08:28:01.372  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:01.372  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 08:28:01.869  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 08:28:01.869  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-25 08:28:01.870  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 08:28:01.870  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-25 08:28:01.870  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 08:28:01.870  5922  5977 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-25 08:28:01.871  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 08:28:01.871  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-25 08:28:01.871  5922  5977 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-25 08:28:01.871  5922  5977 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 08:28:01.871  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 08:28:01.871  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-25 08:28:01.871  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcfedce removed from the list
,10-25 08:28:01.871  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-25 08:28:01.871  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 08:28:01.871  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 08:28:01.872  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 08:28:01.872  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 08:28:01.872  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 08:28:01.872  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.872  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.874  5922  5968 D BluetoothAdapter: STATE_ON
,10-25 08:28:01.874  5922  5968 D BluetoothLeScanner: could not find callback wrapper
10-25 08:28:01.874  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 08:28:01.875  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.875  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.875  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 08:28:01.875  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.877  4724  4789 D BtGatt.AdvertiseManager: message : 1
10-25 08:28:01.878  4724  4789 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 08:28:01.891  4724  4785 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-25 08:28:01.891  4724  4785 D BtGatt.GattService: Client app is not null!
,10-25 08:28:01.892  4724  4943 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 08:28:01.893  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-25 08:28:01.893  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.893  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 08:28:01.894  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.894  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.894  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.894  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-25 08:28:01.894  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 08:28:01.894  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.895  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.895  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 08:28:01.895  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.897  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.897  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 08:28:01.897  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.897  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:01.898  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.898  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.898  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.898  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 08:28:01.898  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 08:28:01.900  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-25 08:28:01.900  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.902  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.902  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.902  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:01.902  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75134ef removed from the list
,10-25 08:28:01.902  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:01.902  5922  5968 D io.jxcore.node.ConnectivityMonitor: stop
10-25 08:28:01.902  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:01.902  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:01.903  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-25 08:28:01.903  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 08:28:02.404  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 08:28:06.907  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-25 08:28:06.909  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,10-25 08:28:06.909  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 08:28:06.914  4944  4944 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[35101]" dev="sockfs" ino=35101 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 08:28:06.914  4944  4944 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[35101]" dev="sockfs" ino=35101 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 08:28:06.913  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 08:28:06.914  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 08:28:06.914  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-25 08:28:06.914  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-25 08:28:06.914  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-25 08:28:06.915  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-25 08:28:06.915  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 08:28:06.915  5922  5978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 08:28:06.916  5922  5978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:06.917  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
10-25 08:28:06.918  5922  5968 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,10-25 08:28:06.918  5922  5968 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-25 08:28:06.919  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-25 08:28:06.919  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 08:28:06.919  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-25 08:28:06.920  5922  5978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-25 08:28:06.922  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,10-25 08:28:06.931  5922  5968 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-25 08:28:06.932  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 08:28:06.932  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 08:28:06.932  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 08:28:06.932  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-25 08:28:06.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:06.933  5922  5978 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 08:28:06.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 08:28:06.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-25 08:28:06.933  5922  5978 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 08:28:06.933  5922  5968 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dcfedce not in the list
10-25 08:28:06.933  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 08:28:06.933  5922  5978 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 08:28:06.933  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 08:28:06.933  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-25 08:28:06.933  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 08:28:06.934  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 08:28:06.934  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 08:28:06.934  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 08:28:06.934  5922  5968 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 08:28:06.934  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:06.934  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:06.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:06.937  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 08:28:06.937  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:06.937  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:06.937  5922  5968 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@75134ef not in the list
10-25 08:28:06.937  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:06.937  5922  5968 D io.jxcore.node.ConnectivityMonitor: stop
10-25 08:28:06.938  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-25 08:28:06.938  5922  5968 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-25 08:28:06.938  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:06.938  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 08:28:06.940  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
10-25 08:28:06.940  5922  5968 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-25 08:28:06.941  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,10-25 08:28:06.941  5922  5968 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
10-25 08:28:06.941  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-25 08:28:06.941  5922  5968 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-25 08:28:06.941  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-25 08:28:06.942  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
10-25 08:28:06.943  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
10-25 08:28:06.945  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
10-25 08:28:06.946  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,10-25 08:28:06.946  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-25 08:28:06.946  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
10-25 08:28:06.948  5922  5968 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-25 08:28:06.948  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-25 08:28:06.948  5922  5968 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-25 08:28:06.948  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-25 08:28:06.948  5922  5968 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,10-25 08:28:06.949  5922  5968 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-25 08:28:06.949  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
10-25 08:28:06.950  5922  5968 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
10-25 08:28:06.950  5922  5968 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
10-25 08:28:06.950  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
10-25 08:28:06.951  5922  5968 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,10-25 08:28:06.951  5922  5968 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,10-25 08:28:06.951  5922  5968 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,10-25 08:28:06.951  5922  5968 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-25 08:28:06.952  5922  5968 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
10-25 08:28:06.952  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-25 08:28:06.952  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adf37df added. We now have 3 listener(s)
10-25 08:28:06.954  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-25 08:28:06.954  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 08:28:06.954  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-25 08:28:06.954  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 08:28:06.954  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98aec2c added. We now have 3 listener(s)
10-25 08:28:06.955  5922  5968 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-25 08:28:06.955  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 08:28:06.959  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 08:28:06.963  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 08:28:06.965  5922  5968 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 08:28:06.966  5922  5968 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-25 08:28:06.968  5922  5968 D BluetoothAdapter: enable(): BT is already enabled..!
,10-25 08:28:06.968   927  3276 D WifiService: setWifiEnabled: true pid=5922, uid=10077
10-25 08:28:06.968   927  3276 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-25 08:28:06.969  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:06.970  5922  5968 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
10-25 08:28:06.972  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:06.973  5922  5968 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,10-25 08:28:06.974  5922  5968 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,10-25 08:28:06.977   927  4928 D WifiService: setWifiEnabled: false pid=5922, uid=10077
10-25 08:28:06.977   927  4928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 08:28:06.980   927  3077 D WifiStateMachine: WifiStateMachine: Leaving Connected state
10-25 08:28:06.980   927  3077 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,10-25 08:28:06.980   927  3077 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 08:28:06.980   927  3077 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 08:28:06.988   927  5535 D DhcpClient: Clearing IP address
,10-25 08:28:06.988   505   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 08:28:06.996   505   920 D CommandListener: Setting iface cfg
,10-25 08:28:06.998   927  5536 D DhcpClient: Receive thread stopped
10-25 08:28:06.999  3695  5592 V NativeCrypto: Read error: ssl=0x7f8371a380: I/O error during system call, Connection timed out
10-25 08:28:07.001  3695  5592 V NativeCrypto: SSL shutdown failed: ssl=0x7f8371a380: I/O error during system call, Broken pipe
10-25 08:28:07.003   927  3266 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-25 08:28:07.003   927  5532 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
10-25 08:28:07.006   927  5532 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-25 08:28:07.006   927  3089 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-25 08:28:07.007   927  3089 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-25 08:28:07.008   927  3089 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-25 08:28:07.010   927  3089 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-25 08:28:07.010   927  3089 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-25 08:28:07.016   927  3089 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-25 08:28:07.016   927   927 D RttService: SCAN_AVAILABLE : 1
10-25 08:28:07.016   927  3197 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-25 08:28:07.017   601   601 E Parcel  : Reading a NULL string not supported here.
10-25 08:28:07.018  3886  4021 W QCNEJ   : |CORE| network lost: 100
,10-25 08:28:07.019  3886  4021 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,10-25 08:28:07.029   927  3077 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-25 08:28:07.041   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 08:28:07.045   927  3077 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-25 08:28:07.063   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 08:28:07.064   505   920 D CommandListener: Clearing all IP addresses on wlan0
10-25 08:28:07.064   927  3089 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,10-25 08:28:07.065   505   920 D TetherController: Setting IP forward enable = 0
,10-25 08:28:07.065   927  3089 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,10-25 08:28:07.068   927   944 D Tethering: MasterInitialState.processMessage what=3
10-25 08:28:07.071   927  3077 D DhcpClient: doQuit
10-25 08:28:07.071   927  3077 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-25 08:28:07.072  3555  3555 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-25 08:28:07.072   927  5535 D DhcpClient: onQuitting
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:07.073  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:07.077  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:07.076  5058  5058 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,10-25 08:28:07.081  5449  5449 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@2853e59 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-25 08:28:07.082  5194  5217 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-25 08:28:07.082  5194  5217 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:07.082  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:07.084  3867  3867 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-25 08:28:07.084  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:07.086  5194  5217 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-25 08:28:07.086  5194  5217 E SarControlService: no key has been found,reset the power
10-25 08:28:07.086  5194  5231 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-25 08:28:07.087  5194  5231 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-25 08:28:07.087  5194  5231 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,10-25 08:28:07.088  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 08:28:07.088  5219  5219 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:07.089  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:07.089  5194  5231 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-25 08:28:07.089  5194  5231 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 08:28:07.089  5194  5231 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-25 08:28:07.090  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 08:28:07.090  5219  5219 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-25 08:28:07.091  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:07.095  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:07.098  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:07.099  3555  3555 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-25 08:28:07.099  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:07.100  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:07.101  5219  5233 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1af3e47 HexData = [00000000ea03000000000000ffffffff]
,10-25 08:28:07.101  5219  5233 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 08:28:07.101  5219  5233 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-25 08:28:07.101  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 08:28:07.101  5194  5205 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-25 08:28:07.102  3867  3867 D SystemUpdateService: onCreate
10-25 08:28:07.104  3555  3555 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,10-25 08:28:07.106   505   913 W SocketClient: write error (Broken pipe)
10-25 08:28:07.106   505   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-25 08:28:07.106   505   913 W SocketListener: Error sending broadcast (Broken pipe)
10-25 08:28:07.106  5219  5233 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1af3e47 HexData = [00000000eb03000000000000ffffffff]
10-25 08:28:07.106  5219  5233 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 08:28:07.106  5219  5233 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-25 08:28:07.107  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 08:28:07.107  5194  5204 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
10-25 08:28:07.108  3867  3867 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 08:28:07.117  3867  3867 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,10-25 08:28:07.122  3867  5562 I iu.UploadsManager: num queued entries: 0
,10-25 08:28:07.122  3867  5562 I iu.UploadsManager: num updated entries: 0
10-25 08:28:07.123  3867  5562 I iu.SyncManager: NEXT; no task
10-25 08:28:07.123  3867  5998 I SystemUpdateService: active receiver: enabled
,10-25 08:28:07.125  3867  3867 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
10-25 08:28:07.126  3867  3867 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-25 08:28:07.129  3867  5998 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 08:28:07.129   505   920 E Netd    : netlink response contains error (No such file or directory)
,10-25 08:28:07.130   927  3089 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-25 08:28:07.131  3867  5998 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-25 08:28:07.131  3867  5998 I SystemUpdateService: now status is 0 (complete)
10-25 08:28:07.131  3867  5998 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 08:28:07.131  3867  5998 I SystemUpdateService: file has been verified
10-25 08:28:07.131   505   920 D TetherController: Setting IP forward enable = 0
10-25 08:28:07.131  3867  5998 I SystemUpdateService: OTA package size = 21989297
,10-25 08:28:07.135  3555  3555 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-25 08:28:07.137  3867  5998 I SystemUpdateService: showing system update notification
,10-25 08:28:07.143   927   937 I ActivityManager: Start proc 6002:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,10-25 08:28:07.151  3555  3555 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-25 08:28:07.156  3867  3867 D SystemUpdateService: onDestroy
,10-25 08:28:07.172  6002  6002 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,10-25 08:28:07.175  6002  6002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-25 08:28:07.182  6002  6002 D SprintDMHelper: simOperator: 
,10-25 08:28:07.182  6002  6002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-25 08:28:07.196  5160  6015 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-25 08:28:07.210   927  3276 I ActivityManager: Start proc 6016:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-25 08:28:07.212   927  3276 I ActivityManager: Killing 5449:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-25 08:28:07.248  6016  6016 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-25 08:28:07.254   927  3712 I ActivityManager: Killing 4801:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-25 08:28:07.268  5160  5160 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 08:28:07.270   927  3077 D wifi    : In wifi stop Hal
,10-25 08:28:07.270   927  3077 D wifi    : halHandle = 0x7f8239a540, mVM = 0x7f9ea0d140, mCls = 0x100a02
,10-25 08:28:07.271   927  3553 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-25 08:28:07.271   927  3553 D WifiHAL : Got a signal to exit!!!
10-25 08:28:07.271   927  3553 I WifiHAL : Exit wifi_event_loop
10-25 08:28:07.271   927  3077 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-25 08:28:07.272   927  3077 E WifiHAL : Event processing terminated
10-25 08:28:07.272   927  3077 D wifi    : In wifi cleaned up handler
10-25 08:28:07.272   927  3077 I WifiHAL : Internal cleanup completed
10-25 08:28:07.273  4184  4330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 08:28:07.273  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:07.276  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:07.278  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:07.293   927  3553 D wifi    : set interface wlan0 flags (DOWN)
10-25 08:28:07.293   927  3077 D WifiNative-HAL: HAL event thread stopped successfully
,10-25 08:28:07.358   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:07.438  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 08:28:07.482  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:07.487   927  5629 D WifiService: setWifiEnabled: true pid=5922, uid=10077
,10-25 08:28:07.487   927  5629 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 08:28:07.498   927   944 D Tethering: InitialState.processMessage what=4
,10-25 08:28:07.498   505   920 D SoftapController: Softap fwReload - Ok
,10-25 08:28:07.501   505   920 D CommandListener: Setting iface cfg
,10-25 08:28:07.501   505   920 D CommandListener: Trying to bring down wlan0
10-25 08:28:07.502   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
10-25 08:28:07.502   505   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 08:28:07.505   927  3077 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 08:28:07.992   927  3952 D WifiService: setWifiEnabled: true pid=5922, uid=10077
,10-25 08:28:07.995   927  3952 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 08:28:08.114   927  3077 D wifi    : set interface wlan0 flags (UP)
10-25 08:28:08.114   927  3077 I WifiHAL : Initializing wifi
10-25 08:28:08.115   927  3077 I WifiHAL : Creating socket
,10-25 08:28:08.121   927  3077 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-25 08:28:08.121   927  3077 D wifi    : Did set static halHandle = 0x7f8239a540
,10-25 08:28:08.121   927  3077 D wifi    : halHandle = 0x7f8239a540, mVM = 0x7f9ea0d140, mCls = 0x1996
10-25 08:28:08.121   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-25 08:28:08.121   927  3077 D wifi    : array field set
,10-25 08:28:08.122   927  3077 I WifiNative-HAL: interface[0] = wlan0
10-25 08:28:08.124   927  6031 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547645662528
,10-25 08:28:08.125   927  6031 D wifi    : waitForHalEvents called, vm = 0x7f9ea0d140, obj = 0x1996, env = 0x7f8238f480
,10-25 08:28:08.209  6032  6032 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-25 08:28:08.226   927  3077 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-25 08:28:08.233  6032  6032 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 08:28:08.241  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.242  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:08.243  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.257  6032  6032 I wpa_supplicant: rfkill: Cannot open RFKILL control device
10-25 08:28:08.257  6032  6032 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-25 08:28:08.273   927  3077 D WifiConfigStore: Loading config and enabling all networks 
,10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:08.279  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:08.281  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:08.283   927  3077 D WifiConfigStore: loaded 0 passpoint configs
,10-25 08:28:08.284   927  3077 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-25 08:28:08.285   927  3077 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:08.285  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:08.286   927  3077 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-25 08:28:08.286  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:08.287   927  3077 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-25 08:28:08.287   927  3077 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-25 08:28:08.287   927  3077 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-25 08:28:08.287   927  3077 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:08.290  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:08.291   927  3077 D WifiNative-HAL: Setting external_sim to 1
10-25 08:28:08.291   927  3077 D wifi    : setting dfs flag to true, 0x7f87d162a0
10-25 08:28:08.292   927  3077 D WifiStateMachine: Setting OUI to DA-A1-19
10-25 08:28:08.292  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:08.292   927  3077 D wifi    : setting scan oui 0x7f87d162a0
10-25 08:28:08.292   927  3077 D WifiHAL : Sending mac address OUI
,10-25 08:28:08.294  5160  5160 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 08:28:08.297   927  3077 E native  : do suspend false
,10-25 08:28:08.304   927   927 D RttService: SCAN_AVAILABLE : 3
,10-25 08:28:08.304   927  3077 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-25 08:28:08.304   505   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-25 08:28:08.304   927  3197 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 08:28:08.305   505   920 D CommandListener: Setting iface cfg
,10-25 08:28:08.309   927  3061 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
,10-25 08:28:08.309   927  3061 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-25 08:28:08.317   927  3061 D WifiNative-HAL: p2pGetDeviceAddress
,10-25 08:28:08.317   927  3061 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-25 08:28:08.324   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=228413 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,10-25 08:28:08.359   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:08.502  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.512  4724  4781 D BluetoothAdapterState: Current state: ON, message: 23
10-25 08:28:08.513  4724  4781 D BluetoothAdapterProperties: Setting state to 13
10-25 08:28:08.513  4724  4781 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-25 08:28:08.514  4724  4781 D BluetoothAdapterProperties: onBluetoothDisable()
,10-25 08:28:08.515  4724  4781 I BluetoothAdapterState: Entering PendingCommandState
10-25 08:28:08.516  4724  4724 D BluetoothMapService: onReceive
10-25 08:28:08.516  4724  4724 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-25 08:28:08.516  4724  4724 D BluetoothMapService: STATE_TURNING_OFF
10-25 08:28:08.517  4724  4724 D BluetoothMapService: MAP Service closeService in
10-25 08:28:08.517  4724  4724 D BluetoothMapMasInstance0: MAP Service shutdown
10-25 08:28:08.517  4724  4724 D ObexServerSockets0: shutdown(block = true)
10-25 08:28:08.518  4724  4724 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 08:28:08.518  4724  4946 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
10-25 08:28:08.518  4724  4724 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 08:28:08.518  4724  4947 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-25 08:28:08.518  4724  4932 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-25 08:28:08.522  4724  4724 I BtOppRfcommListener: stopping Accept Thread
,10-25 08:28:08.522  4724  5463 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-25 08:28:08.523  4724  5463 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-25 08:28:08.526  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:08.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:08.527  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:08.527  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:08.529  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:08.529  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:08.530  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:08.530  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:08.533  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:08.533  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:08.535  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:08.535  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:08.535   927   940 I ActivityManager: Start proc 6036:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,10-25 08:28:08.538  4724  4785 D BluetoothAdapterProperties: Scan Mode:20
10-25 08:28:08.538  4724  4781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-25 08:28:08.539  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:08.541  4724  4724 D HeadsetService: Received stop request...Stopping profile...
10-25 08:28:08.542  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:08.542   927   927 D BluetoothHeadset: Proxy object disconnected
10-25 08:28:08.543  3917  3945 D BluetoothHeadset: Proxy object disconnected
10-25 08:28:08.543  4724  4724 D A2dpService: Received stop request...Stopping profile...
10-25 08:28:08.543  4724  4938 D A2dpStateMachine: Exit Disconnected: -1
,10-25 08:28:08.544   927   927 D BluetoothHeadset: Proxy object disconnected
10-25 08:28:08.544   927   927 D BluetoothHeadset: Proxy object disconnected
10-25 08:28:08.544  3243  3255 D BluetoothHeadset: Proxy object disconnected
10-25 08:28:08.545   927   927 D BluetoothA2dp: Proxy object disconnected
,10-25 08:28:08.545  4724  4724 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:08.545  4724  4724 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:08.545  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.545  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:08.546  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.547  4724  4724 D HidService: Received stop request...Stopping profile...
,10-25 08:28:08.547  4724  4724 D HidService: Stopping Bluetooth HidService
,10-25 08:28:08.550  3243  3243 D HeadsetProfile: Bluetooth service disconnected
,10-25 08:28:08.550  3243  3243 D BluetoothA2dp: Proxy object disconnected
10-25 08:28:08.550  3243  3243 D BluetoothInputDevice: Proxy object disconnected
10-25 08:28:08.551  3243  3243 D HidProfile: Bluetooth service disconnected
,10-25 08:28:08.552  4724  4724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-25 08:28:08.552  4724  4724 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-25 08:28:08.552  4724  4785 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-25 08:28:08.552  4724  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-25 08:28:08.552  4724  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-25 08:28:08.552  4724  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:08.552  4724  4785 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-25 08:28:08.552  4724  4724 D HealthService: Received stop request...Stopping profile...
10-25 08:28:08.554  4724  4724 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:08.554  4724  4724 V BluetoothAdapterState: isTurningOn()=false
,10-25 08:28:08.554  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.554  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:08.554  4724  4724 D PanService: Received stop request...Stopping profile...
10-25 08:28:08.556  3243  3243 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 08:28:08.556  3243  3243 D PanProfile: Bluetooth service disconnected
10-25 08:28:08.557  4724  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-25 08:28:08.557  4724  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:08.557  4724  4914 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 08:28:08.557  4724  4914 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 08:28:08.557  4724  4914 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 08:28:08.557  4724  4914 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 08:28:08.557  4724  4785 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,10-25 08:28:08.558  4724  4724 D BluetoothMapService: Received stop request...Stopping profile...
,10-25 08:28:08.559  4724  4724 D BluetoothMapService: stop()
10-25 08:28:08.559  4724  4724 D BluetoothMapAppObserver: deinitObservers()
10-25 08:28:08.559  4724  4724 D BluetoothMapAppObserver: removeReceiver()
10-25 08:28:08.560  3243  3243 D BluetoothMap: Proxy object disconnected
10-25 08:28:08.560  3243  3243 D MapProfile: Bluetooth service disconnected
10-25 08:28:08.560  4724  4724 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:08.560  4724  4724 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:08.560  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.560  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:08.561  4724  4724 D SapService: Received stop request...Stopping profile...
10-25 08:28:08.561  4724  4724 V SapService: stop()
,10-25 08:28:08.565  4724  4724 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,10-25 08:28:08.565  4724  4724 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-25 08:28:08.565  4724  4785 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 08:28:08.565  4724  4724 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:08.565  4724  4724 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:08.565  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.565  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 08:28:08.566  4724  4724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-25 08:28:08.566  4724  4785 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-25 08:28:08.566  4724  4724 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-25 08:28:08.566  4724  4724 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:08.566  4724  4724 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:08.566  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.566  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:08.566  4724  4724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-25 08:28:08.567  4724  4724 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-25 08:28:08.567  4724  4724 D BluetoothMapService: MAP Service closeService in
10-25 08:28:08.567  4724  4724 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:08.567  4724  4724 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:08.567  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.568  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:08.568  4724  4724 D BluetoothMapService: cleanup()
10-25 08:28:08.568  4724  4724 D BluetoothMapService: MAP Service closeService in
10-25 08:28:08.568  4724  4724 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:08.568  4724  4724 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:08.568  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.568  4724  4724 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:08.568  4724  4781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-25 08:28:08.568  4724  4781 D BluetoothAdapterProperties: Setting state to 15
10-25 08:28:08.568  4724  4781 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-25 08:28:08.569  4724  4781 I BluetoothAdapterState: Entering BleOnState
,10-25 08:28:08.569  3917  4108 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:08.569   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 08:28:08.569   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:08.570  3243  3257 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:08.570  3243  3255 D BluetoothPan: onBluetoothStateChange on: false
10-25 08:28:08.571  3243  4076 D BluetoothMap: onBluetoothStateChange: up=false
10-25 08:28:08.571  3243  4076 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 08:28:08.573   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:08.574  3243  3255 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-25 08:28:08.575   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:08.575  3243  3257 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 08:28:08.576  4724  4781 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-25 08:28:08.576  4724  4781 D BluetoothAdapterProperties: Setting state to 16
10-25 08:28:08.576  4724  4781 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-25 08:28:08.577  4724  4781 D BluetoothAdapterProperties: onBleDisable
,10-25 08:28:08.577  4724  4781 I BluetoothAdapterState: Entering PendingCommandState
10-25 08:28:08.577  4724  4782 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-25 08:28:08.578  4724  4914 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-25 08:28:08.578  4724  4914 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-25 08:28:08.580  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.582  4724  4785 D BluetoothAdapterProperties: Scan Mode:20
,10-25 08:28:08.583  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.586  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:08.589  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.591  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:08.593  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:08.602  6036  6036 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-25 08:28:08.611  6036  6036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 08:28:08.617  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 08:28:08.618   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4be8085:true
,10-25 08:28:08.630   927  3276 I ActivityManager: Start proc 6048:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-25 08:28:08.642  6036  6036 D LocalBluetoothProfileManager: Adding local MAP profile
,10-25 08:28:08.646  6036  6036 D BluetoothMap: Create BluetoothMap proxy object
,10-25 08:28:08.660  6036  6036 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-25 08:28:08.667  6048  6048 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-25 08:28:08.676  6036  6036 D DockEventReceiver: finishStartingService: stopping service
,10-25 08:28:08.682   927  3711 I ActivityManager: Killing 5647:com.android.defcontainer/u0a7 (adj 15): empty #17
,10-25 08:28:08.785  4724  4785 I bt_hci  : shut_down
,10-25 08:28:08.789  4724  4791 D bt_hwcfg: hw_epilog_process
,10-25 08:28:08.789  4724  4791 I bt_vendor: low_power_mode_cb
,10-25 08:28:08.791  4724  4791 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-25 08:28:08.791  4724  4791 I bt_vendor: epilog_cb
10-25 08:28:08.791  4724  4791 I bt_hci  : epilog_finished_callback
10-25 08:28:08.793  4724  4785 I bt_hci_h4: hal_close
10-25 08:28:08.794  4724  4785 I bt_userial_vendor: device fd = 54 close
,10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.File.exists(File.java:361)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.e.b(PG:170)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.k.d(PG:583)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.e.b(PG:170)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.File.exists(File.java:361)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.File.exists(File.java:361)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.886  6048  6048 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:08.886  6048  6048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:08.890  6036  6036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 08:28:08.895  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 08:28:08.905  4724  4782 D bt_stack_manager: event_shut_down_stack finished.
10-25 08:28:08.905  4724  4781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-25 08:28:08.907  4724  4724 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 08:28:08.907  4724  4781 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-25 08:28:08.908  4724  4724 D BtGatt.GattService: Received stop request...Stopping profile...
10-25 08:28:08.909  4724  4724 D BtGatt.GattService: stop()
10-25 08:28:08.909  4724  4724 D BtGatt.AdvertiseManager: advertise clients cleared
10-25 08:28:08.909  6036  6036 D DockEventReceiver: finishStartingService: stopping service
10-25 08:28:08.910  4724  4724 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:08.910  4724  4724 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:08.910  4724  4724 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:08.910  4724  4724 V BluetoothAdapterState: isBleTurningOff()=true
10-25 08:28:08.910  4724  4781 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-25 08:28:08.910  4724  4781 D BluetoothAdapterProperties: Setting state to 10
10-25 08:28:08.910  4724  4781 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-25 08:28:08.911   927  3712 I ActivityManager: Killing 5670:com.google.android.partnersetup/u0a18 (adj 15): empty #17
10-25 08:28:08.911  4724  4781 I BluetoothAdapterState: Entering OffState
10-25 08:28:08.912   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-25 08:28:08.936  4724  4724 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
10-25 08:28:08.936  4724  4724 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-25 08:28:08.936  4724  4724 I BluetoothServiceJni: cleanupNative: return from cleanup
10-25 08:28:08.938  4724  4782 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
10-25 08:28:08.941  4724  4724 I art     : System.exit called, status: 0
10-25 08:28:08.941  4724  4724 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-25 08:28:09.002   927   938 I ActivityManager: Process com.android.bluetooth (pid 4724) has died
,10-25 08:28:09.011  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:09.024   927   944 I ActivityManager: Start proc 6080:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-25 08:28:09.085  6080  6080 D AdapterServiceConfig: Adding HeadsetService
,10-25 08:28:09.085  6080  6080 D AdapterServiceConfig: Adding A2dpService
10-25 08:28:09.085  6080  6080 D AdapterServiceConfig: Adding HidService
10-25 08:28:09.086  6080  6080 D AdapterServiceConfig: Adding HealthService
10-25 08:28:09.086  6080  6080 D AdapterServiceConfig: Adding PanService
,10-25 08:28:09.086  6080  6080 D AdapterServiceConfig: Adding GattService
10-25 08:28:09.086  6080  6080 D AdapterServiceConfig: Adding BluetoothMapService
10-25 08:28:09.086  6080  6080 D AdapterServiceConfig: Adding SapService
,10-25 08:28:09.096   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@70398e2:true
,10-25 08:28:09.096  6080  6080 D BluetoothAdapterState: make() - Creating AdapterState
,10-25 08:28:09.098  6080  6080 I bt_bluedroid: init
,10-25 08:28:09.098  6080  6092 I BluetoothAdapterState: Entering OffState
,10-25 08:28:09.100  6080  6093 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-25 08:28:09.100  6080  6093 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-25 08:28:09.101  6080  6093 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-25 08:28:09.101  6080  6093 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-25 08:28:09.101  6080  6080 I bt_bluedroid: get_profile_interface socket
,10-25 08:28:09.103  6080  6080 I bt_bluedroid: get_profile_interface sdp
10-25 08:28:09.103  6080  6096 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-25 08:28:09.104  6080  6096 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 08:28:09.107  6080  6091 I bt_bluedroid: config_hci_snoop_log
,10-25 08:28:09.108   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,10-25 08:28:09.111  6080  6092 D BluetoothAdapterState: Current state: OFF, message: 0
,10-25 08:28:09.111  6080  6092 D BluetoothAdapterProperties: Setting state to 14
10-25 08:28:09.111  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-25 08:28:09.113  6080  6092 D BluetoothBondStateMachine: make
,10-25 08:28:09.114  6080  6097 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-25 08:28:09.117  6080  6092 I BluetoothAdapterState: Entering PendingCommandState
,10-25 08:28:09.117  6080  6080 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-25 08:28:09.119  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
10-25 08:28:09.120  6080  6080 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 08:28:09.120  6080  6080 D BtGatt.GattService: Received start request. Starting profile...
,10-25 08:28:09.120  6080  6080 D BtGatt.GattService: start()
,10-25 08:28:09.120  6080  6080 I bt_bluedroid: get_profile_interface gatt
10-25 08:28:09.121  6048  6068 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
10-25 08:28:09.121  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:09.121  6080  6080 D BtGatt.AdvertiseManager: advertise manager created
,10-25 08:28:09.127  6080  6080 V BluetoothAdapterState: isTurningOff()=false
,10-25 08:28:09.127  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:09.127  6080  6080 V BluetoothAdapterState: isBleTurningOn()=true
10-25 08:28:09.127  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:09.127  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-25 08:28:09.128  6080  6092 I bt_bluedroid: bt_bluedroid
10-25 08:28:09.128  6080  6093 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-25 08:28:09.128  6080  6093 I bt_hci  : start_up
,10-25 08:28:09.133  6080  6093 I bt_vendor: alloc value 0xf3b93871
,10-25 08:28:09.133  6080  6093 I bt_vendor: init
10-25 08:28:09.133  6080  6093 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-25 08:28:09.133  6080  6093 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-25 08:28:09.138   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b32aeeb:true
,10-25 08:28:09.240  6080  6093 D bt_hci  : start_up starting async portion
10-25 08:28:09.241  6080  6100 I bt_hci  : event_finish_startup
10-25 08:28:09.241  6080  6100 I bt_hci_h4: hal_open
10-25 08:28:09.241  6080  6100 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-25 08:28:09.243  6080  6100 I bt_userial_vendor: device fd = 54 open
10-25 08:28:09.237  6103  6103 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 08:28:09.256  6080  6100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 08:28:09.259  6080  6100 D bt_hwcfg: Chipset BCM4358A3
,10-25 08:28:09.259  6080  6100 D bt_hwcfg: Target name = [BCM4358A3]
10-25 08:28:09.259  6080  6100 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-25 08:28:09.359   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:09.519  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-25 08:28:09.647  6080  6100 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-25 08:28:09.648  6080  6100 D bt_hwcfg: Settlement delay -- 100 ms
10-25 08:28:09.648  6080  6100 I bt_hwcfg: Setting fw settlement delay to 100 
,10-25 08:28:09.771  6080  6100 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-25 08:28:09.772  6080  6100 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-25 08:28:09.773  6080  6100 I bt_hwcfg: vendor lib fwcfg completed
,10-25 08:28:09.773  6080  6100 I bt_vendor: firmware callback
10-25 08:28:09.773  6080  6100 I bt_hci  : firmware_config_callback
10-25 08:28:09.782  6080  6105 I bt_btu  : btu_task pending for preload complete event
,10-25 08:28:09.782  6080  6105 I bt_btu_task: Bluetooth chip preload is complete
10-25 08:28:09.782  6080  6105 I bt_btu  : btu_task received preload complete event
,10-25 08:28:09.790  6080  6105 I         : BTE_InitTraceLevels -- TRC_HCI
,10-25 08:28:09.791  6080  6105 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-25 08:28:09.791  6080  6105 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-25 08:28:09.791  6080  6105 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-25 08:28:09.791  6080  6105 I         : BTE_InitTraceLevels -- TRC_AVRC
10-25 08:28:09.791  6080  6105 I         : BTE_InitTraceLevels -- TRC_A2D
10-25 08:28:09.791  6080  6105 I         : BTE_InitTraceLevels -- TRC_BNEP
,10-25 08:28:09.791  6080  6105 I         : BTE_InitTraceLevels -- TRC_BTM
10-25 08:28:09.792  6080  6105 I         : BTE_InitTraceLevels -- TRC_GAP
10-25 08:28:09.792  6080  6105 I         : BTE_InitTraceLevels -- TRC_PAN
10-25 08:28:09.792  6080  6105 I         : BTE_InitTraceLevels -- TRC_SDP
,10-25 08:28:09.792  6080  6105 I         : BTE_InitTraceLevels -- TRC_GATT
10-25 08:28:09.792  6080  6105 I         : BTE_InitTraceLevels -- TRC_SMP
10-25 08:28:09.792  6080  6105 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-25 08:28:09.793  6080  6105 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-25 08:28:09.875  6080  6105 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b11549
,10-25 08:28:09.875  6080  6105 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b11549 
,10-25 08:28:09.892  6080  6096 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-25 08:28:09.894  6080  6096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-25 08:28:09.895  6080  6096 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-25 08:28:09.898  6080  6096 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 08:28:09.901  6080  6096 D BluetoothAdapterProperties: Scan Mode:20
,10-25 08:28:09.902  6080  6096 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-25 08:28:09.902  6080  6096 D bt_hci  : do_postload posting postload work item
10-25 08:28:09.902  6080  6100 I bt_hci  : event_postload
10-25 08:28:09.902  6080  6100 I bt_vendor: sco_config_cb
10-25 08:28:09.902  6080  6100 I bt_hci  : sco_config_callback postload finished.
10-25 08:28:09.906  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:09.908  6080  6096 D bt_bte_conf: Device ID record 1 : primary
10-25 08:28:09.908  6080  6096 D bt_bte_conf:   vendorId            = 000f
10-25 08:28:09.908  6080  6096 D bt_bte_conf:   vendorIdSource      = 0001
10-25 08:28:09.908  6080  6096 D bt_bte_conf:   product             = 1200
10-25 08:28:09.909  6080  6096 D bt_bte_conf:   version             = 1436
,10-25 08:28:09.909  6080  6096 D bt_bte_conf:   clientExecutableURL = 
10-25 08:28:09.909  6080  6096 D bt_bte_conf:   serviceDescription  = 
10-25 08:28:09.909  6080  6096 D bt_bte_conf:   documentationURL    = 
10-25 08:28:09.909  6080  6096 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-25 08:28:09.909  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:09.909  6080  6093 D bt_stack_manager: event_start_up_stack finished
,10-25 08:28:09.911  6080  6100 I bt_vendor: low_power_mode_cb
10-25 08:28:09.911  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-25 08:28:09.911  6080  6092 D BluetoothAdapterProperties: Setting state to 15
,10-25 08:28:09.911  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-25 08:28:09.915  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:09.915  6080  6092 I BluetoothAdapterState: Entering BleOnState
,10-25 08:28:09.916  6080  6092 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-25 08:28:09.916  6080  6092 D BluetoothAdapterProperties: Setting state to 11
10-25 08:28:09.916  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-25 08:28:09.923  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:09.926  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:09.927  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:09.928  6080  6080 D HeadsetService: Received start request. Starting profile...
10-25 08:28:09.930  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:09.932  6080  6080 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,10-25 08:28:09.932  6080  6080 D HeadsetStateMachine: make
,10-25 08:28:09.939  6080  6092 I BluetoothAdapterState: Entering PendingCommandState
,10-25 08:28:09.940  6080  6080 D HeadsetStateMachine: max_hf_connections = 1
,10-25 08:28:09.940  6080  6080 I bt_bluedroid: get_profile_interface handsfree
10-25 08:28:09.940  6080  6096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-25 08:28:09.940  6080  6096 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,10-25 08:28:09.944  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:09.944  6080  6080 D A2dpService: Received start request. Starting profile...
10-25 08:28:09.945  6080  6080 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-25 08:28:09.945  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 08:28:09.945  6080  6080 I bt_bluedroid: get_profile_interface avrcp
,10-25 08:28:09.950  6080  6080 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-25 08:28:09.950  6080  6080 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-25 08:28:09.951  6080  6080 D A2dpStateMachine: make
,10-25 08:28:09.951  6080  6080 I bt_bluedroid: get_profile_interface a2dp
,10-25 08:28:09.953  6080  6096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-25 08:28:09.953  6080  6113 D A2dpStateMachine: Enter Disconnected: -2
,10-25 08:28:09.954  6080  6080 I BluetoothHidServiceJni: classInitNative: succeeds
10-25 08:28:09.955  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:09.956  6080  6080 D HidService: Received start request. Starting profile...
,10-25 08:28:09.956  6080  6080 I bt_bluedroid: get_profile_interface hidhost
10-25 08:28:09.956  6080  6096 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3af256d
10-25 08:28:09.956  6080  6080 D HidService: setHidService(): set to: null
10-25 08:28:09.956  6036  6036 D BluetoothInputDevice: Proxy object connected
10-25 08:28:09.957  6080  6096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-25 08:28:09.957  6080  6080 I BluetoothHealthServiceJni: classInitNative: succeeds
10-25 08:28:09.957  6036  6036 D HidProfile: Bluetooth service connected
10-25 08:28:09.957  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
10-25 08:28:09.958  6080  6080 D HealthService: Received start request. Starting profile...
,10-25 08:28:09.959  6080  6080 I bt_bluedroid: get_profile_interface health
10-25 08:28:09.960  6080  6080 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-25 08:28:09.961  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:09.962  6080  6080 D PanService: Received start request. Starting profile...
,10-25 08:28:09.962  6036  6036 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 08:28:09.962  6080  6080 D BluetoothPanServiceJni: initializeNative(L110): pan
10-25 08:28:09.962  6080  6080 I bt_bluedroid: get_profile_interface pan
10-25 08:28:09.962  6080  6096 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-25 08:28:09.962  6036  6036 D PanProfile: Bluetooth service connected
10-25 08:28:09.964  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:09.965  6036  6036 D BluetoothMap: Proxy object connected
,10-25 08:28:09.966  6036  6036 D MapProfile: Bluetooth service connected
10-25 08:28:09.966  6036  6036 D BluetoothMap: getConnectedDevices()
10-25 08:28:09.966  6080  6080 D BluetoothMapService: Received start request. Starting profile...
10-25 08:28:09.966  6036  6036 D BluetoothMap: Bluetooth is Not enabled
10-25 08:28:09.966  6080  6080 D BluetoothMapService: start()
,10-25 08:28:09.969  6080  6080 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-25 08:28:09.970  6080  6080 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-25 08:28:09.970  6080  6080 D BluetoothMapAppObserver: createReceiver()
10-25 08:28:09.972  6080  6080 D BluetoothMapAppObserver: initObservers()
10-25 08:28:09.972  6080  6080 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-25 08:28:09.978  6080  6080 V SapService: SapBinder()
10-25 08:28:09.978  6080  6080 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:09.978  6080  6080 D SapService: Received start request. Starting profile...
10-25 08:28:09.978  6080  6080 V SapService: start()
,10-25 08:28:09.980  6080  6080 V BluetoothAdapterState: isTurningOff()=false
,10-25 08:28:09.980  6080  6080 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:09.980  6080  6111 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-25 08:28:09.980  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:09.980  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:09.981  6080  6080 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:09.981  6080  6080 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:09.981  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:09.981  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isTurningOff()=false
,10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:09.982  6080  6080 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:09.983  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:09.983  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:09.983  6080  6080 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:09.983  6080  6080 V BluetoothAdapterState: isTurningOn()=true
,10-25 08:28:09.983  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:09.983  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:09.984  6080  6080 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:09.984  6080  6080 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:09.984  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:09.984  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:09.984  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-25 08:28:09.984  6080  6092 D BluetoothAdapterProperties: ScanMode =  20
,10-25 08:28:09.984  6080  6092 D BluetoothAdapterProperties: State =  11
10-25 08:28:09.986  6080  6096 D BluetoothAdapterProperties: Scan Mode:21
10-25 08:28:09.986  6080  6092 D BluetoothAdapterProperties: Setting state to 12
10-25 08:28:09.986  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-25 08:28:09.986  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 08:28:09.987  6080  6092 I BluetoothAdapterState: Entering OnState
10-25 08:28:09.987  3917  3948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:09.988   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
10-25 08:28:09.988  6080  6096 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 08:28:09.988  6036  6047 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 08:28:09.989   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:09.989  5922  5922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
10-25 08:28:09.989  3243  3255 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-25 08:28:09.989   927   927 D BluetoothA2dp: Proxy object connected
10-25 08:28:09.990  3243  3257 D BluetoothPan: onBluetoothStateChange on: true
10-25 08:28:09.992  5922  5922 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
10-25 08:28:09.992  3243  3243 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 08:28:09.992  3243  3243 D PanProfile: Bluetooth service connected
10-25 08:28:09.993  3243  3255 D BluetoothMap: onBluetoothStateChange: up=true
10-25 08:28:09.995  3243  3243 D BluetoothMap: Proxy object connected
10-25 08:28:09.995  3243  3243 D MapProfile: Bluetooth service connected
10-25 08:28:09.995  3243  3243 D BluetoothMap: getConnectedDevices()
,10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:09.996  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:09.997  6080  6080 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,10-25 08:28:09.997  6036  6046 D BluetoothMap: onBluetoothStateChange: up=true
,10-25 08:28:09.997  6080  6080 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-25 08:28:09.997  3243  3257 D BluetoothA2dp: onBluetoothStateChange: up=true
10-25 08:28:09.999  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:10.000  3243  3243 D BluetoothA2dp: Proxy object connected
10-25 08:28:10.000  6036  6047 D BluetoothPan: onBluetoothStateChange on: true
10-25 08:28:10.000   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:10.001  6080  6080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:10.001  3243  3255 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 08:28:10.003  6080  6080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:10.003  3243  3243 D BluetoothInputDevice: Proxy object connected
,10-25 08:28:10.003  3243  3243 D HidProfile: Bluetooth service connected
10-25 08:28:10.003   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:10.004  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:10.004  6080  6080 D ObexServerSockets: Succeed to create listening sockets 
,10-25 08:28:10.004  6080  6080 D ObexServerSockets0: startAccept()
10-25 08:28:10.004  6080  6080 D ObexServerSockets0: prepareForNewConnect()
10-25 08:28:10.004  6036  6046 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 08:28:10.006  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:10.006  3243  3257 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 08:28:10.006  6080  6080 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-25 08:28:10.006  6080  6080 D BluetoothSdpJni: SDP Create record success - handle: 0
10-25 08:28:10.007  6080  6119 D ObexServerSockets0: Accepting socket connection...
10-25 08:28:10.007  6080  6120 D ObexServerSockets0: Accepting socket connection...
,10-25 08:28:10.009  6080  6080 D BluetoothMapService: onReceive
10-25 08:28:10.009  6080  6080 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,10-25 08:28:10.010  6080  6080 D BluetoothMapService: STATE_ON
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:10.010  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:10.011   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-25 08:28:10.012  6080  6121 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:10.012  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:10.012  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-25 08:28:10.013  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:10.013  6080  6121 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-25 08:28:10.013  6080  6121 D BluetoothSdpJni: SDP Create record success - handle: 1
10-25 08:28:10.015  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:10.017  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:10.018  6036  6036 D LocalBluetoothProfileManager: Adding local A2DP profile
10-25 08:28:10.021  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:10.021  6036  6036 D LocalBluetoothProfileManager: Adding local HEADSET profile
10-25 08:28:10.022  5922  5968 D io.jxcore.node.ConnectivityMonitor: stop
10-25 08:28:10.022  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:10.023  5922  5968 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,10-25 08:28:10.024  5922  5968 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-25 08:28:10.025  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:10.026  6036  6036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 08:28:10.027  6080  6092 D BluetoothAdapterState: Current state: ON, message: 23
10-25 08:28:10.027  6080  6092 D BluetoothAdapterProperties: Setting state to 13
10-25 08:28:10.027  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-25 08:28:10.028  6080  6092 D BluetoothAdapterProperties: onBluetoothDisable()
,10-25 08:28:10.028  6080  6092 I BluetoothAdapterState: Entering PendingCommandState
10-25 08:28:10.030  6080  6096 D BluetoothAdapterProperties: Scan Mode:20
10-25 08:28:10.030  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
10-25 08:28:10.031  6080  6080 D BluetoothMapService: onReceive
10-25 08:28:10.031  6080  6080 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-25 08:28:10.031  6080  6080 D BluetoothMapService: STATE_TURNING_OFF
,10-25 08:28:10.033  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:10.033  6080  6080 D BluetoothMapService: MAP Service closeService in
,10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:10.033  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:10.033  6080  6080 D BluetoothMapMasInstance0: MAP Service shutdown
10-25 08:28:10.033  6080  6080 D ObexServerSockets0: shutdown(block = true)
10-25 08:28:10.034  6080  6080 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 08:28:10.034  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 08:28:10.034  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:10.034  6080  6080 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-25 08:28:10.034  6080  6107 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-25 08:28:10.034  6080  6120 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-25 08:28:10.034  6080  6119 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-25 08:28:10.034  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 08:28:10.028  6036  6036 D BluetoothA2dp: Proxy object connected
10-25 08:28:10.036  6080  6080 D HeadsetService: Received stop request...Stopping profile...
10-25 08:28:10.039  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:10.039  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:10.040  5922  5922 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:10.040  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:10.041  6036  6036 D DockEventReceiver: finishStartingService: stopping service
,10-25 08:28:10.042  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:10.043  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:10.050  6080  6080 D A2dpService: Received stop request...Stopping profile...
,10-25 08:28:10.050  6080  6113 D A2dpStateMachine: Exit Disconnected: -1
10-25 08:28:10.051   927   927 D BluetoothA2dp: Proxy object disconnected
,10-25 08:28:10.052  6080  6080 D HidService: Received stop request...Stopping profile...
10-25 08:28:10.052  6080  6080 D HidService: Stopping Bluetooth HidService
10-25 08:28:10.052  6036  6036 D BluetoothPbap: Proxy object connected
10-25 08:28:10.053  6036  6036 D PbapServerProfile: Bluetooth service connected
10-25 08:28:10.053  3243  3243 D BluetoothPbap: Proxy object connected
10-25 08:28:10.053  6036  6036 D BluetoothA2dp: Proxy object disconnected
10-25 08:28:10.053  3243  3243 D PbapServerProfile: Bluetooth service connected
10-25 08:28:10.053  6080  6080 D HealthService: Received stop request...Stopping profile...
10-25 08:28:10.053  3243  3243 D BluetoothA2dp: Proxy object disconnected
10-25 08:28:10.053  6036  6036 D BluetoothInputDevice: Proxy object disconnected
10-25 08:28:10.053  3243  3243 D BluetoothInputDevice: Proxy object disconnected
10-25 08:28:10.053  3243  3243 D HidProfile: Bluetooth service disconnected
10-25 08:28:10.054  6036  6036 D HidProfile: Bluetooth service disconnected
,10-25 08:28:10.058  6080  6080 V BluetoothAdapterState: isTurningOff()=true
,10-25 08:28:10.058  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.059  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:10.059  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.059  6080  6080 D PanService: Received stop request...Stopping profile...
,10-25 08:28:10.061  3243  3243 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 08:28:10.061  6036  6036 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-25 08:28:10.061  3243  3243 D PanProfile: Bluetooth service disconnected
,10-25 08:28:10.061  6036  6036 D PanProfile: Bluetooth service disconnected
,10-25 08:28:10.062  6080  6080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-25 08:28:10.062  6080  6080 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-25 08:28:10.063  6080  6096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-25 08:28:10.063  6080  6105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:10.063  6080  6105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:10.063  6080  6105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:10.063  6080  6096 E bt_btif : btif_hf_upstreams_evt: Invalid index 17
10-25 08:28:10.063  6080  6080 D BluetoothMapService: Received stop request...Stopping profile...
10-25 08:28:10.063  6080  6080 D BluetoothMapService: stop()
10-25 08:28:10.064  6080  6080 D BluetoothMapAppObserver: deinitObservers()
10-25 08:28:10.064  6080  6080 D BluetoothMapAppObserver: removeReceiver()
10-25 08:28:10.065  3243  3243 D BluetoothMap: Proxy object disconnected
10-25 08:28:10.065  3243  3243 D MapProfile: Bluetooth service disconnected
10-25 08:28:10.066  6036  6036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 08:28:10.067  6080  6080 D SapService: Received stop request...Stopping profile...
10-25 08:28:10.067  6080  6080 V SapService: stop()
,10-25 08:28:10.068  6036  6036 D BluetoothMap: Proxy object disconnected
10-25 08:28:10.068  6036  6036 D MapProfile: Bluetooth service disconnected
10-25 08:28:10.069  6080  6080 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:10.069  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.069  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 08:28:10.069  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.070  6080  6105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:10.070  6080  6105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:10.070  6080  6096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-25 08:28:10.071  6080  6105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-25 08:28:10.071  6080  6105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-25 08:28:10.071  6080  6105 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,10-25 08:28:10.071  6080  6105 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,10-25 08:28:10.072  6036  6036 D DockEventReceiver: finishStartingService: stopping service
,10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isTurningOff()=true
,10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.074  6080  6080 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-25 08:28:10.074  6080  6080 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isTurningOff()=true
10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isTurningOn()=false
,10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:10.074  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.074  6080  6096 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 08:28:10.074  6080  6080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-25 08:28:10.075  6080  6096 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-25 08:28:10.075  6080  6080 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-25 08:28:10.085  6080  6080 V BluetoothAdapterState: isTurningOff()=true
,10-25 08:28:10.085  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.085  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:10.086  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.086  6080  6080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-25 08:28:10.086  6080  6080 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,10-25 08:28:10.087  6080  6080 D BluetoothMapService: MAP Service closeService in
10-25 08:28:10.087  6080  6080 V BluetoothAdapterState: isTurningOff()=true
,10-25 08:28:10.087  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.087  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:10.087  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.087  6080  6080 D BluetoothMapService: cleanup()
10-25 08:28:10.087  6080  6080 D BluetoothMapService: MAP Service closeService in
,10-25 08:28:10.087  6080  6080 V BluetoothAdapterState: isTurningOff()=true
,10-25 08:28:10.088  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.088  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:10.088  6080  6080 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.088  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-25 08:28:10.088  6080  6092 D BluetoothAdapterProperties: Setting state to 15
,10-25 08:28:10.088  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,10-25 08:28:10.089  6080  6092 I BluetoothAdapterState: Entering BleOnState
10-25 08:28:10.090  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 08:28:10.091  3917  3945 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:10.092   927   944 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-25 08:28:10.092  6036  6047 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-25 08:28:10.092  3243  3243 D BluetoothPbap: Proxy object disconnected
10-25 08:28:10.092  3243  3243 D PbapServerProfile: Bluetooth service disconnected
10-25 08:28:10.093   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:10.093  3243  3257 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:10.093  3243  3255 D BluetoothPan: onBluetoothStateChange on: false
10-25 08:28:10.095  3243  4076 D BluetoothMap: onBluetoothStateChange: up=false
10-25 08:28:10.095  6036  6046 D BluetoothMap: onBluetoothStateChange: up=false
10-25 08:28:10.096  3243  3257 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 08:28:10.097  6036  6047 D BluetoothPan: onBluetoothStateChange on: false
10-25 08:28:10.097   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-25 08:28:10.098  6036  6046 D BluetoothA2dp: onBluetoothStateChange: up=false
10-25 08:28:10.098  3243  3255 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-25 08:28:10.099   927   944 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:10.099  6036  6047 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 08:28:10.101  3243  4076 D BluetoothPbap: onBluetoothStateChange: up=false
10-25 08:28:10.101  6036  6036 D BluetoothPbap: Proxy object disconnected
10-25 08:28:10.102  6036  6036 D PbapServerProfile: Bluetooth service disconnected
10-25 08:28:10.102  6036  6046 D BluetoothHeadset: onBluetoothStateChange: up=false
10-25 08:28:10.102  6080  6092 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-25 08:28:10.102  6080  6092 D BluetoothAdapterProperties: Setting state to 16
10-25 08:28:10.102  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,10-25 08:28:10.105  6080  6092 D BluetoothAdapterProperties: onBleDisable
,10-25 08:28:10.105  6080  6092 I BluetoothAdapterState: Entering PendingCommandState
10-25 08:28:10.106  6080  6096 D BluetoothAdapterProperties: Scan Mode:20
10-25 08:28:10.106  6036  6036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-25 08:28:10.107  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:10.107  6080  6093 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-25 08:28:10.108  6080  6105 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-25 08:28:10.108  6080  6105 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-25 08:28:10.108  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:10.110  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:10.111  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:10.111  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 08:28:10.113  6036  6036 D DockEventReceiver: finishStartingService: stopping service
,10-25 08:28:10.310  6080  6096 I bt_hci  : shut_down
,10-25 08:28:10.311  6080  6100 D bt_hwcfg: hw_epilog_process
,10-25 08:28:10.312  6080  6100 I bt_vendor: low_power_mode_cb
,10-25 08:28:10.315  6080  6100 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,10-25 08:28:10.315  6080  6100 I bt_vendor: epilog_cb
10-25 08:28:10.315  6080  6100 I bt_hci  : epilog_finished_callback
10-25 08:28:10.316  6080  6096 I bt_hci_h4: hal_close
10-25 08:28:10.317  6080  6096 I bt_userial_vendor: device fd = 54 close
,10-25 08:28:10.360   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:10.439  6080  6093 D bt_stack_manager: event_shut_down_stack finished.
,10-25 08:28:10.439  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-25 08:28:10.443  6080  6092 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,10-25 08:28:10.443  6080  6080 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 08:28:10.445  6080  6080 D BtGatt.GattService: Received stop request...Stopping profile...
10-25 08:28:10.445  6080  6080 D BtGatt.GattService: stop()
10-25 08:28:10.445  6080  6080 D BtGatt.AdvertiseManager: advertise clients cleared
,10-25 08:28:10.449  6080  6080 V BluetoothAdapterState: isTurningOff()=false
,10-25 08:28:10.449  6080  6080 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.449  6080  6080 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:10.449  6080  6080 V BluetoothAdapterState: isBleTurningOff()=true
,10-25 08:28:10.450  6080  6092 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-25 08:28:10.450  6080  6092 D BluetoothAdapterProperties: Setting state to 10
,10-25 08:28:10.450  6080  6092 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-25 08:28:10.452  6080  6092 I BluetoothAdapterState: Entering OffState
,10-25 08:28:10.454   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-25 08:28:10.468  6080  6080 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-25 08:28:10.469  6080  6080 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-25 08:28:10.469  6080  6080 I BluetoothServiceJni: cleanupNative: return from cleanup
,10-25 08:28:10.472  6080  6093 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-25 08:28:10.478  6080  6080 I art     : System.exit called, status: 0
,10-25 08:28:10.478  6080  6080 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-25 08:28:10.513   927  3276 I ActivityManager: Process com.android.bluetooth (pid 6080) has died
,10-25 08:28:10.527  5922  5979 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:10.527  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:10.528  5922  5979 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-25 08:28:10.528  5922  5979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:10.529  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:10.542   927   944 I ActivityManager: Start proc 6132:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-25 08:28:10.599  6132  6132 D AdapterServiceConfig: Adding HeadsetService
10-25 08:28:10.600  6132  6132 D AdapterServiceConfig: Adding A2dpService
10-25 08:28:10.600  6132  6132 D AdapterServiceConfig: Adding HidService
10-25 08:28:10.600  6132  6132 D AdapterServiceConfig: Adding HealthService
10-25 08:28:10.600  6132  6132 D AdapterServiceConfig: Adding PanService
10-25 08:28:10.600  6132  6132 D AdapterServiceConfig: Adding GattService
10-25 08:28:10.600  6132  6132 D AdapterServiceConfig: Adding BluetoothMapService
,10-25 08:28:10.600  6132  6132 D AdapterServiceConfig: Adding SapService
,10-25 08:28:10.609   927   944 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26beab:true
,10-25 08:28:10.609  6132  6132 D BluetoothAdapterState: make() - Creating AdapterState
,10-25 08:28:10.612  6132  6132 I bt_bluedroid: init
10-25 08:28:10.612  6132  6144 I BluetoothAdapterState: Entering OffState
,10-25 08:28:10.614  6132  6145 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
10-25 08:28:10.614  6132  6145 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-25 08:28:10.615  6132  6145 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-25 08:28:10.615  6132  6145 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,10-25 08:28:10.615  6132  6132 I bt_bluedroid: get_profile_interface socket
,10-25 08:28:10.616  6132  6148 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-25 08:28:10.617  6132  6132 I bt_bluedroid: get_profile_interface sdp
10-25 08:28:10.618  6132  6148 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-25 08:28:10.621  6132  6143 I bt_bluedroid: config_hci_snoop_log
,10-25 08:28:10.622   927   944 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
10-25 08:28:10.625  6132  6144 D BluetoothAdapterState: Current state: OFF, message: 0
10-25 08:28:10.626  6132  6144 D BluetoothAdapterProperties: Setting state to 14
10-25 08:28:10.626  6132  6144 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-25 08:28:10.627  6132  6144 D BluetoothBondStateMachine: make
,10-25 08:28:10.629  6132  6149 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-25 08:28:10.631  6132  6144 I BluetoothAdapterState: Entering PendingCommandState
,10-25 08:28:10.632  6132  6132 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-25 08:28:10.635  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:10.635  6132  6132 D BtGatt.DebugUtils: handleDebugAction() action=null
10-25 08:28:10.636  6132  6132 D BtGatt.GattService: Received start request. Starting profile...
10-25 08:28:10.636  6132  6132 D BtGatt.GattService: start()
10-25 08:28:10.636  6132  6132 I bt_bluedroid: get_profile_interface gatt
,10-25 08:28:10.637  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
10-25 08:28:10.637  6132  6132 D BtGatt.AdvertiseManager: advertise manager created
,10-25 08:28:10.641  6132  6132 V BluetoothAdapterState: isTurningOff()=false
,10-25 08:28:10.641  6132  6132 V BluetoothAdapterState: isTurningOn()=false
10-25 08:28:10.641  6132  6132 V BluetoothAdapterState: isBleTurningOn()=true
10-25 08:28:10.641  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:10.641  6132  6144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-25 08:28:10.642  6132  6144 I bt_bluedroid: bt_bluedroid
10-25 08:28:10.642  6132  6145 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-25 08:28:10.643  6132  6145 I bt_hci  : start_up
,10-25 08:28:10.647  6132  6145 I bt_vendor: alloc value 0xf3b93871
10-25 08:28:10.647  6132  6145 I bt_vendor: init
10-25 08:28:10.647  6132  6145 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-25 08:28:10.647  6132  6145 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-25 08:28:10.757  6132  6145 D bt_hci  : start_up starting async portion
,10-25 08:28:10.758  6132  6152 I bt_hci  : event_finish_startup
10-25 08:28:10.758  6132  6152 I bt_hci_h4: hal_open
10-25 08:28:10.758  6132  6152 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-25 08:28:10.761  6132  6152 I bt_userial_vendor: device fd = 54 open
,10-25 08:28:10.754  6153  6153 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 08:28:10.775  6132  6152 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-25 08:28:10.778  6132  6152 D bt_hwcfg: Chipset BCM4358A3
,10-25 08:28:10.778  6132  6152 D bt_hwcfg: Target name = [BCM4358A3]
,10-25 08:28:10.778  6132  6152 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-25 08:28:11.036  6132  6144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-25 08:28:11.188  6132  6152 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-25 08:28:11.188  6132  6152 D bt_hwcfg: Settlement delay -- 100 ms
10-25 08:28:11.189  6132  6152 I bt_hwcfg: Setting fw settlement delay to 100 
,10-25 08:28:11.313  6132  6152 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-25 08:28:11.314  6132  6152 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,10-25 08:28:11.317  6132  6152 I bt_hwcfg: vendor lib fwcfg completed
,10-25 08:28:11.317  6132  6152 I bt_vendor: firmware callback
10-25 08:28:11.317  6132  6152 I bt_hci  : firmware_config_callback
10-25 08:28:11.325  6132  6155 I bt_btu  : btu_task pending for preload complete event
,10-25 08:28:11.325  6132  6155 I bt_btu_task: Bluetooth chip preload is complete
10-25 08:28:11.325  6132  6155 I bt_btu  : btu_task received preload complete event
,10-25 08:28:11.332  6132  6155 I         : BTE_InitTraceLevels -- TRC_HCI
,10-25 08:28:11.332  6132  6155 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-25 08:28:11.332  6132  6155 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-25 08:28:11.332  6132  6155 I         : BTE_InitTraceLevels -- TRC_AVDT
10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_A2D
10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_BNEP
10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_BTM
10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_GAP
,10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_PAN
10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_SDP
10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_GATT
10-25 08:28:11.333  6132  6155 I         : BTE_InitTraceLevels -- TRC_SMP
10-25 08:28:11.334  6132  6155 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-25 08:28:11.334  6132  6155 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-25 08:28:11.361   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:11.390  6032  6032 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 08:28:11.395  6032  6032 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 08:28:11.399  6032  6032 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 08:28:11.403  6032  6032 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-25 08:28:11.415  6132  6155 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b11549
10-25 08:28:11.415  6132  6155 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b11549 
,10-25 08:28:11.430  6132  6148 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-25 08:28:11.431  6132  6148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-25 08:28:11.432  6132  6148 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-25 08:28:11.433  6132  6148 D BluetoothAdapterProperties: Name is: Nexus 6P
10-25 08:28:11.435  6132  6148 D BluetoothAdapterProperties: Scan Mode:20
10-25 08:28:11.436  6132  6148 D BluetoothAdapterProperties: Discoverable Timeout:120
10-25 08:28:11.436  6132  6148 D bt_hci  : do_postload posting postload work item
10-25 08:28:11.436  6132  6152 I bt_hci  : event_postload
10-25 08:28:11.436  6132  6152 I bt_vendor: sco_config_cb
10-25 08:28:11.436  6132  6152 I bt_hci  : sco_config_callback postload finished.
,10-25 08:28:11.438  6132  6148 D bt_bte_conf: Device ID record 1 : primary
10-25 08:28:11.438  6132  6148 D bt_bte_conf:   vendorId            = 000f
10-25 08:28:11.438  6132  6148 D bt_bte_conf:   vendorIdSource      = 0001
10-25 08:28:11.438  6132  6148 D bt_bte_conf:   product             = 1200
10-25 08:28:11.439  6132  6148 D bt_bte_conf:   version             = 1436
10-25 08:28:11.439  6132  6148 D bt_bte_conf:   clientExecutableURL = 
10-25 08:28:11.439  6132  6148 D bt_bte_conf:   serviceDescription  = 
10-25 08:28:11.439  6132  6148 D bt_bte_conf:   documentationURL    = 
10-25 08:28:11.439  6132  6148 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-25 08:28:11.439  6132  6145 D bt_stack_manager: event_start_up_stack finished
10-25 08:28:11.440  6132  6144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,10-25 08:28:11.440  6132  6144 D BluetoothAdapterProperties: Setting state to 15
10-25 08:28:11.440  6132  6144 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-25 08:28:11.441  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.442  6132  6144 I BluetoothAdapterState: Entering BleOnState
10-25 08:28:11.445  6132  6144 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-25 08:28:11.445  6132  6144 D BluetoothAdapterProperties: Setting state to 11
10-25 08:28:11.445  6132  6144 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
10-25 08:28:11.445  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.448  6132  6152 I bt_vendor: low_power_mode_cb
10-25 08:28:11.449  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
10-25 08:28:11.452   927   927 D BluetoothHeadset: Proxy object connected
10-25 08:28:11.452  3917  3945 D BluetoothHeadset: Proxy object connected
10-25 08:28:11.453  6132  6132 D HeadsetService: Received start request. Starting profile...
10-25 08:28:11.453   927   927 D BluetoothHeadset: Proxy object connected
10-25 08:28:11.453  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.454  6036  6047 D BluetoothHeadset: Proxy object connected
10-25 08:28:11.455   927   927 D BluetoothHeadset: Proxy object connected
10-25 08:28:11.455  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.456  6132  6132 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-25 08:28:11.456  6132  6132 D HeadsetStateMachine: make
,10-25 08:28:11.456  3243  3257 D BluetoothHeadset: Proxy object connected
10-25 08:28:11.456  6036  6036 D HeadsetProfile: Bluetooth service connected
10-25 08:28:11.456   927  3077 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-25 08:28:11.457   927  3077 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-25 08:28:11.457   927  3077 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-25 08:28:11.461  3243  3243 D HeadsetProfile: Bluetooth service connected
,10-25 08:28:11.467  6132  6144 I BluetoothAdapterState: Entering PendingCommandState
,10-25 08:28:11.468   927  3077 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-25 08:28:11.470  6132  6132 D HeadsetStateMachine: max_hf_connections = 1
,10-25 08:28:11.470  6132  6132 I bt_bluedroid: get_profile_interface handsfree
10-25 08:28:11.471  6132  6148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-25 08:28:11.471  6132  6148 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-25 08:28:11.474  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:11.474  6132  6132 D A2dpService: Received start request. Starting profile...
,10-25 08:28:11.475  6132  6132 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-25 08:28:11.475  6132  6132 I bt_bluedroid: get_profile_interface avrcp
,10-25 08:28:11.480  6132  6132 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-25 08:28:11.480  6132  6132 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-25 08:28:11.480  6132  6132 D A2dpStateMachine: make
10-25 08:28:11.481  6132  6132 I bt_bluedroid: get_profile_interface a2dp
,10-25 08:28:11.481  6132  6148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-25 08:28:11.482  6132  6165 D A2dpStateMachine: Enter Disconnected: -2
,10-25 08:28:11.483  6132  6132 I BluetoothHidServiceJni: classInitNative: succeeds
,10-25 08:28:11.483  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
10-25 08:28:11.484  6132  6132 D HidService: Received start request. Starting profile...
10-25 08:28:11.484  6132  6132 I bt_bluedroid: get_profile_interface hidhost
10-25 08:28:11.484  6132  6132 D HidService: setHidService(): set to: null
10-25 08:28:11.484  6132  6148 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3af256d
10-25 08:28:11.484  6132  6148 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-25 08:28:11.486  6132  6132 I BluetoothHealthServiceJni: classInitNative: succeeds
10-25 08:28:11.486  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
10-25 08:28:11.487  6132  6132 D HealthService: Received start request. Starting profile...
10-25 08:28:11.487  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-25 08:28:11.488  6132  6132 I bt_bluedroid: get_profile_interface health
,10-25 08:28:11.489  6132  6132 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-25 08:28:11.489  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
10-25 08:28:11.490  6132  6132 D PanService: Received start request. Starting profile...
,10-25 08:28:11.490  6132  6132 D BluetoothPanServiceJni: initializeNative(L110): pan
10-25 08:28:11.490  6132  6132 I bt_bluedroid: get_profile_interface pan
10-25 08:28:11.490  6132  6148 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-25 08:28:11.492  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:11.492  6132  6132 D BluetoothMapService: Received start request. Starting profile...
10-25 08:28:11.492  6132  6132 D BluetoothMapService: start()
,10-25 08:28:11.495  6132  6132 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-25 08:28:11.496  6132  6132 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-25 08:28:11.496  6132  6132 D BluetoothMapAppObserver: createReceiver()
10-25 08:28:11.497  6132  6132 D BluetoothMapAppObserver: initObservers()
,10-25 08:28:11.497  6132  6132 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-25 08:28:11.502   927  3077 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-25 08:28:11.503  6132  6132 V SapService: SapBinder()
,10-25 08:28:11.503  6032  6032 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
10-25 08:28:11.503  6132  6132 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:11.504  6132  6132 D SapService: Received start request. Starting profile...
10-25 08:28:11.504  6132  6132 V SapService: start()
,10-25 08:28:11.507  6132  6132 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:11.508  6132  6163 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isTurningOn()=true
,10-25 08:28:11.508  6132  6132 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:11.509  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:11.509  6132  6132 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:11.509  6132  6132 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:11.509  6132  6132 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:11.509  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
,10-25 08:28:11.509  6132  6132 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:11.510  6132  6132 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:11.510  6132  6132 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:11.510  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:11.510  6132  6132 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:11.510  6132  6132 V BluetoothAdapterState: isTurningOn()=true
,10-25 08:28:11.510  6132  6132 V BluetoothAdapterState: isBleTurningOn()=false
,10-25 08:28:11.510  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:11.511  6132  6132 V BluetoothAdapterState: isTurningOff()=false
10-25 08:28:11.512  6132  6132 V BluetoothAdapterState: isTurningOn()=true
10-25 08:28:11.512  6132  6132 V BluetoothAdapterState: isBleTurningOn()=false
10-25 08:28:11.512  6132  6132 V BluetoothAdapterState: isBleTurningOff()=false
10-25 08:28:11.512  6132  6144 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
10-25 08:28:11.512  6132  6144 D BluetoothAdapterProperties: ScanMode =  20
10-25 08:28:11.512  6132  6144 D BluetoothAdapterProperties: State =  11
10-25 08:28:11.512  6132  6144 D BluetoothAdapterProperties: Setting state to 12
10-25 08:28:11.512  6132  6144 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-25 08:28:11.513  6132  6144 I BluetoothAdapterState: Entering OnState
10-25 08:28:11.513  3917  3948 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:11.513   927   944 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 08:28:11.517  6036  6046 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 08:28:11.517  6132  6148 D BluetoothAdapterProperties: Scan Mode:21
,10-25 08:28:11.517  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-25 08:28:11.517  6132  6148 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-25 08:28:11.518   927   927 D BluetoothA2dp: Proxy object connected
,10-25 08:28:11.518   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:11.519  3243  4076 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:11.519  3243  3255 D BluetoothPan: onBluetoothStateChange on: true
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:11.521  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:11.521  3243  3257 D BluetoothMap: onBluetoothStateChange: up=true
10-25 08:28:11.521  3243  3243 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 08:28:11.522  3243  3243 D PanProfile: Bluetooth service connected
10-25 08:28:11.522  6132  6132 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-25 08:28:11.522  6036  6162 D BluetoothMap: onBluetoothStateChange: up=true
10-25 08:28:11.523  6132  6132 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-25 08:28:11.523  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:11.523  6036  6036 D BluetoothInputDevice: Proxy object connected
10-25 08:28:11.524  6036  6036 D HidProfile: Bluetooth service connected
10-25 08:28:11.525  3243  3255 D BluetoothA2dp: onBluetoothStateChange: up=true
,10-25 08:28:11.526  6036  6046 D BluetoothPan: onBluetoothStateChange on: true
10-25 08:28:11.526  3243  3243 D BluetoothA2dp: Proxy object connected
10-25 08:28:11.526  6132  6132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:11.526  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:11.528   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:11.528  6036  6162 D BluetoothA2dp: onBluetoothStateChange: up=true
10-25 08:28:11.529  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:11.529  3243  3255 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-25 08:28:11.530  6132  6132 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:11.531   927   944 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:11.531  3243  3243 D BluetoothInputDevice: Proxy object connected
10-25 08:28:11.531  3243  3243 D HidProfile: Bluetooth service connected
10-25 08:28:11.531  6036  6046 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 08:28:11.532  6132  6132 D ObexServerSockets: Succeed to create listening sockets 
10-25 08:28:11.532  6132  6132 D ObexServerSockets0: startAccept()
,10-25 08:28:11.532  6132  6132 D ObexServerSockets0: prepareForNewConnect()
10-25 08:28:11.532  3243  3257 D BluetoothPbap: onBluetoothStateChange: up=true
10-25 08:28:11.534  6132  6132 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-25 08:28:11.534  6132  6132 D BluetoothSdpJni: SDP Create record success - handle: 0
10-25 08:28:11.534  6036  6047 D BluetoothHeadset: onBluetoothStateChange: up=true
10-25 08:28:11.535  6132  6170 D ObexServerSockets0: Accepting socket connection...
10-25 08:28:11.535  6132  6171 D ObexServerSockets0: Accepting socket connection...
10-25 08:28:11.535  3243  3243 D BluetoothMap: Proxy object connected
10-25 08:28:11.535  3243  3243 D MapProfile: Bluetooth service connected
10-25 08:28:11.535  3243  3243 D BluetoothMap: getConnectedDevices()
10-25 08:28:11.536  6036  6036 D BluetoothPan: BluetoothPAN Proxy object connected
10-25 08:28:11.536  6036  6036 D PanProfile: Bluetooth service connected
10-25 08:28:11.536  6036  6036 D BluetoothA2dp: Proxy object connected
10-25 08:28:11.536   927   927 I Telecom : BluetoothPhoneService: queryPhoneState
10-25 08:28:11.536   927   927 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
10-25 08:28:11.537  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-25 08:28:11.537  6132  6132 D BluetoothMapService: onReceive
10-25 08:28:11.537  6132  6132 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-25 08:28:11.537  6132  6132 D BluetoothMapService: STATE_ON
10-25 08:28:11.538  6036  6036 D BluetoothMap: Proxy object connected
10-25 08:28:11.539  6036  6036 D MapProfile: Bluetooth service connected
10-25 08:28:11.539  6036  6036 D BluetoothMap: getConnectedDevices()
10-25 08:28:11.540  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:11.540  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:11.542  5922  5979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:11.542  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.542  6132  6173 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:11.543  5922  5968 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
10-25 08:28:11.543   927  3711 D WifiService: setWifiEnabled: false pid=5922, uid=10077
10-25 08:28:11.544   927  3711 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-25 08:28:11.544  6132  6173 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-25 08:28:11.544  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.544  6132  6173 D BluetoothSdpJni: SDP Create record success - handle: 1
10-25 08:28:11.546   927   927 D RttService: SCAN_AVAILABLE : 1
10-25 08:28:11.546   927  3197 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-25 08:28:11,.547  6036  6036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-25 08:28:11.553  6036  6036 D DockEventReceiver: finishStartingService: stopping service
10-25 08:28:11.557  3695  3695 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-25 08:28:11.558   927  3077 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 08:28:11.559   505   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 08:28:11.562   927  3077 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 08:28:11.563  6032  6032 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
10-25 08:28:11.563  6132  6132 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-25 08:28:11.563  6132  6132 D ObexServerSockets0: prepareForNewConnect()
10-25 08:28:11.564  3243  3243 D BluetoothPbap: Proxy object connected
10-25 08:28:11.564  3243  3243 D PbapServerProfile: Bluetooth service connected
,10-25 08:28:11.564  6036  6036 D BluetoothPbap: Proxy object connected
10-25 08:28:11.566  6036  6036 D PbapServerProfile: Bluetooth service connected
,10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:11.569  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:11.572  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:11.573  6132  6178 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:11.575  6032  6032 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-25 08:28:11.578  6032  6032 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:11.578  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:11.580  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:11.587  6132  6182 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 08:28:11.588  6132  6182 I BtOppRfcommListener: Accept thread started.
,10-25 08:28:11.596  6032  6032 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-25 08:28:11.605  6032  6032 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-25 08:28:11.707   927  3077 D wifi    : In wifi stop Hal
,10-25 08:28:11.707  5160  5160 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-25 08:28:11.707   927  3077 D wifi    : halHandle = 0x7f8239a540, mVM = 0x7f9ea0d140, mCls = 0x1996
10-25 08:28:11.707   927  6031 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-25 08:28:11.707   927  6031 D WifiHAL : Got a signal to exit!!!
10-25 08:28:11.707   927  6031 I WifiHAL : Exit wifi_event_loop
10-25 08:28:11.708   927  3077 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-25 08:28:11.708   927  3077 E WifiHAL : Event processing terminated
10-25 08:28:11.708   927  3077 D wifi    : In wifi cleaned up handler
10-25 08:28:11.708   927  3077 I WifiHAL : Internal cleanup completed
,10-25 08:28:11.711  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:11.713  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:11.714  4184  4330 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 08:28:11.745   927  6031 D wifi    : set interface wlan0 flags (DOWN)
,10-25 08:28:11.745   927  3077 D WifiNative-HAL: HAL event thread stopped successfully
,10-25 08:28:11.952   927   944 D Tethering: InitialState.processMessage what=4
,10-25 08:28:11.957   927   944 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:12.055  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:12.060  5922  5979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:12.063   927  3266 D WifiService: setWifiEnabled: true pid=5922, uid=10077
,10-25 08:28:12.063   927  3266 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 08:28:12.065  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:12.070   505   920 D SoftapController: Softap fwReload - Ok
,10-25 08:28:12.073   505   920 D CommandListener: Setting iface cfg
10-25 08:28:12.073   505   920 D CommandListener: Trying to bring down wlan0
,10-25 08:28:12.074   505   920 D CommandListener: Clearing all IP addresses on wlan0
,10-25 08:28:12.078   927  3077 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-25 08:28:12.361   603   603 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,10-25 08:28:12.571   927  4928 D WifiService: setWifiEnabled: true pid=5922, uid=10077
,10-25 08:28:12.571   927  4928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 08:28:12.655   927  3077 D wifi    : set interface wlan0 flags (UP)
,10-25 08:28:12.655   927  3077 I WifiHAL : Initializing wifi
,10-25 08:28:12.655   927  3077 I WifiHAL : Creating socket
,10-25 08:28:12.658   927  3077 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
10-25 08:28:12.658   927  3077 D wifi    : Did set static halHandle = 0x7f8239a540
10-25 08:28:12.658   927  3077 D wifi    : halHandle = 0x7f8239a540, mVM = 0x7f9ea0d140, mCls = 0x131e
10-25 08:28:12.659   927  3077 D wifi    : array field set
10-25 08:28:12.659   927  3077 I WifiNative-HAL: interface[0] = wlan0
10-25 08:28:12.660   927   944 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
10-25 08:28:12.661   927  6185 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547645662528
,10-25 08:28:12.662   927  6185 D wifi    : waitForHalEvents called, vm = 0x7f9ea0d140, obj = 0x131e, env = 0x7f8238f9c0
,10-25 08:28:12.708  6186  6186 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-25 08:28:12.727  6186  6186 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 08:28:12.751  6186  6186 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-25 08:28:12.751  6186  6186 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-25 08:28:12.762   927  3077 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-25 08:28:12.776   927  3077 D WifiConfigStore: Loading config and enabling all networks 
,10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:12.777  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:12.782  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:12.788   927  3077 D WifiConfigStore: loaded 0 passpoint configs
,10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:12.788  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-25 08:28:12.788   927  3077 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-25 08:28:12.789   927  3077 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
10-25 08:28:12.789   927  3077 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-25 08:28:12.791  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-25 08:28:12.791   927  3077 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-25 08:28:12.791   927  3077 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-25 08:28:12.791   927  3077 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-25 08:28:12.791   927  3077 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-25 08:28:12.793  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:12.794  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-25 08:28:12.795   927  3077 D WifiNative-HAL: Setting external_sim to 1
10-25 08:28:12.795   927  3077 D wifi    : setting dfs flag to true, 0x7f87ad1e80
10-25 08:28:12.796   927  3077 D WifiStateMachine: Setting OUI to DA-A1-19
10-25 08:28:12.796   927  3077 D wifi    : setting scan oui 0x7f87ad1e80
10-25 08:28:12.796   927  3077 D WifiHAL : Sending mac address OUI
10-25 08:28:12.796  5160  5160 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-25 08:28:12.801   927  3077 E native  : do suspend false
,10-25 08:28:12.808   927   927 D RttService: SCAN_AVAILABLE : 3
10-25 08:28:12.808   927  3077 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-25 08:28:12.808   505   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-25 08:28:12.808   927  3197 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-25 08:28:12.809   505   920 D CommandListener: Setting iface cfg
,10-25 08:28:12.813   927  3061 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '135 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 135 Failed to set address (No such device)'
,10-25 08:28:12.813   927  3061 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-25 08:28:12.819   927   942 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=232908 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=6 mControllerEnergyUsed=22 }
,10-25 08:28:12.821   927  3061 D WifiNative-HAL: p2pGetDeviceAddress
10-25 08:28:12.821   927  3061 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:13.082  5922  5979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:13.088  5922  5979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:13.091  5922  5968 D BluetoothAdapter: enable(): BT is already enabled..!
,10-25 08:28:13.092   927   938 D WifiService: setWifiEnabled: true pid=5922, uid=10077
10-25 08:28:13.092   927   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-25 08:28:13.093  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-25 08:28:13.094  5922  5968 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 08:28:13.094  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:13.094  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 08:28:13.094  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-25 08:28:13.095  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@adf37df removed from the list
,10-25 08:28:13.095  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 08:28:13.095  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98aec2c removed from the list
10-25 08:28:13.095  5922  5968 D io.jxcore.node.ConnectivityMonitor: stop
10-25 08:28:13.095  5922  5968 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-25 08:28:13.095  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:13.098  5922  5968 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
10-25 08:28:13.099  5922  5968 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,10-25 08:28:13.101  5922  5968 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
10-25 08:28:13.102  5922  5968 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,10-25 08:28:13.105  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
10-25 08:28:13.106  5922  5968 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-25 08:28:13.108  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,10-25 08:28:13.109  5922  5968 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,10-25 08:28:13.111  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,10-25 08:28:13.114  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
10-25 08:28:13.114  5922  5968 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@80a005b Bundle[{}]
,10-25 08:28:13.116  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,10-25 08:28:13.116  5922  5968 I io.jxcore.node.LifeCycleMonitor: start: OK
10-25 08:28:13.117  5922  5968 I io.jxcore.node.LifeCycleMonitor: stop: OK
,10-25 08:28:13.119  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,10-25 08:28:13.119  5922  5968 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-25 08:28:13.120  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
10-25 08:28:13.120  5922  5968 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,10-25 08:28:13.121  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
,10-25 08:28:13.122  5922  5968 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,10-25 08:28:13.123  5922  5968 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,10-25 08:28:13.125  5922  5968 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,10-25 08:28:13.127  5922  5968 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,10-25 08:28:13.129  5922  5968 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
10-25 08:28:13.130  5922  5968 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
10-25 08:28:13.131  5922  5968 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,10-25 08:28:13.132  5922  5968 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,10-25 08:28:13.134  5922  5968 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,10-25 08:28:13.136  5922  5968 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
10-25 08:28:13.137  5922  5968 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,10-25 08:28:13.138  5922  5968 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,10-25 08:28:13.141  5922  5968 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,10-25 08:28:13.142  5922  5968 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
10-25 08:28:13.142  5922  5968 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
10-25 08:28:13.143  5922  5968 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
10-25 08:28:13.143  5922  5968 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
10-25 08:28:13.143  5922  5968 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-25 08:28:13.143  5922  5968 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
,10-25 08:28:13.144  5922  5968 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
10-25 08:28:13.145  5922  5968 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,10-25 08:28:13.146  5922  5968 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,10-25 08:28:13.147  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-25 08:28:13.148  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2972fb added. We now have 3 listener(s)
10-25 08:28:13.149  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-25 08:28:13.149  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-25 08:28:13.149  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-25 08:28:13.150  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-25 08:28:13.150  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d09f18 added. We now have 3 listener(s)
10-25 08:28:13.150  5922  5968 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-25 08:28:13.151  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-25 08:28:13.155  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-25 08:28:13.159  5922  5968 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-25 08:28:13.161  5922  5968 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-25 08:28:13.162  5922  5968 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-25 08:28:13.163  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:13.165  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-25 08:28:13.168  5922  5968 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,10-25 08:28:13.168  5922  5968 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
10-25 08:28:13.168  5922  5968 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-25 08:28:13.168  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,10-25 08:28:13.169  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:13.169  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 08:28:13.169  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 08:28:13.169  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:13.170  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 08:28:13.170  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 08:28:13.170  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 08:28:13.171  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 08:28:13.171  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 08:28:13.171  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 08:28:13.171  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,10-25 08:28:13.171  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:13.171  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-25 08:28:13.172  5922  6188 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 08:28:13.175  5922  6188 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-25 08:28:13.177  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-25 08:28:13.177  5922  5968 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 08:28:13.177  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-25 08:28:13.174  6172  6172 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[36000]" dev="sockfs" ino=36000 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 08:28:13.180  5922  6188 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-25 08:28:13.182  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 08:28:13.182  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-25 08:28:13.182  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 08:28:13.184  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.184  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 08:28:13.184  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-25 08:28:13.184  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
10-25 08:28:13.184  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 08:28:13.184  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.184  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:13.184  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.185  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:13.174  6172  6172 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[36000]" dev="sockfs" ino=36000 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 08:28:13.185  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:13.188  6132  6161 D BtGatt.GattService: registerClient() - UUID=a6acb790-4fb6-4e8b-b121-0f48f8843497
10-25 08:28:13.189  6132  6148 D BtGatt.GattService: onClientRegistered() - UUID=a6acb790-4fb6-4e8b-b121-0f48f8843497, clientIf=5
,10-25 08:28:13.189  5922  5932 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-25 08:28:13.191  6132  6150 D BtGatt.AdvertiseManager: message : 0
,10-25 08:28:13.193  6132  6150 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 08:28:13.202  6132  6148 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-25 08:28:13.204  6132  6148 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-25 08:28:13.205  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.205  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:13.205  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 08:28:13.205  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.205  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.205  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.205  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.206  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.206  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-25 08:28:13.207  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-25 08:28:13.207  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:13.208  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.208  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.208  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:13.208  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
,10-25 08:28:13.209  5922  5922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 08:28:13.209  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-25 08:28:13.209  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,10-25 08:28:13.212  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,10-25 08:28:13.212  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 08:28:13.212  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:13.213  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:13.213  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 08:28:13.213  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:13.213  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-25 08:28:13.713  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-25 08:28:13.714  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 08:28:13.714  5922  5922 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 08:28:16.711  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-25 08:28:16.711  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-25 08:28:16.711  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 08:28:16.711  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 08:28:16.711  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-25 08:28:16.712  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 08:28:16.712  5922  6188 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 08:28:16.712  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 08:28:16.712  5922  6188 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-25 08:28:16.712  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-25 08:28:16.712  5922  6188 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-25 08:28:16.712  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-25 08:28:16.713  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 08:28:16.713  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-25 08:28:16.713  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 08:28:16.713  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 08:28:16.713  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.713  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.718  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:16.718  5922  5968 D BluetoothLeScanner: could not find callback wrapper
10-25 08:28:16.718  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 08:28:16.718  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.719  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.719  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-25 08:28:16.719  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.721  6132  6150 D BtGatt.AdvertiseManager: message : 1
,10-25 08:28:16.722  6132  6150 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-25 08:28:16.736  6132  6148 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-25 08:28:16.736  6132  6148 D BtGatt.GattService: Client app is not null!
10-25 08:28:16.737  6132  6159 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-25 08:28:16.739  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-25 08:28:16.739  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.739  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-25 08:28:16.740  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.740  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.740  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.740  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,10-25 08:28:16.742  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-25 08:28:16.742  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.742  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.742  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-25 08:28:16.743  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.747  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.747  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 08:28:16.749  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.750  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.750  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.750  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.750  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.751  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 08:28:16.751  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 08:28:16.752  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 08:28:16.752  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.754  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.754  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.754  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.755  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-25 08:28:16.755  5922  5922 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-25 08:28:16.755  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 08:28:16.755  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-25 08:28:16.755  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:16.755  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:16.756  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 08:28:16.761  5922  5968 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,10-25 08:28:16.762  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-25 08:28:16.763  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,10-25 08:28:16.763  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-25 08:28:16.763  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-25 08:28:16.763  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:16.763  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-25 08:28:16.769  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,10-25 08:28:16.769  5922  5968 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-25 08:28:16.769  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-25 08:28:16.775  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-25 08:28:16.776  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 08:28:16.776  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-25 08:28:16.782  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.782  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 08:28:16.783  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 08:28:16.783  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,10-25 08:28:16.783  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,10-25 08:28:16.784  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.785  5922  5968 D BluetoothAdapter: STATE_ON
,10-25 08:28:16.789  6132  6172 D BtGatt.GattService: registerClient() - UUID=d3717af5-a2d5-47a7-b81f-af28d9489ba3
,10-25 08:28:16.789  6132  6148 D BtGatt.GattService: onClientRegistered() - UUID=d3717af5-a2d5-47a7-b81f-af28d9489ba3, clientIf=5
10-25 08:28:16.790  5922  5932 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-25 08:28:16.791  6132  6161 D BtGatt.GattService: start scan with filters
,10-25 08:28:16.795  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,10-25 08:28:16.795  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.795  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 08:28:16.795  6132  6151 D BtGatt.ScanManager: handling starting scan
10-25 08:28:16.796  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.796  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.796  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,10-25 08:28:16.796  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-25 08:28:16.796  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.796  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.797  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-25 08:28:16.797  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.797  6132  6151 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@43d000c
,10-25 08:28:16.801  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.801  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 08:28:16.801  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.801  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.801  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.801  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-25 08:28:16.801  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 08:28:16.803  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-25 08:28:16.803  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.805  6132  6148 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 08:28:16.805  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 08:28:16.806  6132  6151 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-25 08:28:16.807  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.807  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:16.807  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:16.814  6132  6148 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-25 08:28:16.814  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 08:28:16.815  6132  6151 D BtGatt.ScanManager: Starting BLE batch scan
10-25 08:28:16.815  6132  6151 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-25 08:28:16.827  6132  6148 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-25 08:28:16.828  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 08:28:16.834  6132  6148 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-25 08:28:16.834  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 08:28:17.302  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-25 08:28:17.303  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,10-25 08:28:17.303  5922  5922 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 08:28:17.362   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:18.363   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:19.364   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:19.810  5922  5968 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
10-25 08:28:19.810  5922  5968 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
10-25 08:28:19.810  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-25 08:28:19.811  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-25 08:28:19.811  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-25 08:28:19.814  5922  5968 D BluetoothAdapter: STATE_ON
,10-25 08:28:19.817  6132  6159 D BtGatt.GattService: stopScan() - queue size =1
,10-25 08:28:19.821  6132  6143 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 08:28:19.823  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-25 08:28:19.824  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.824  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 08:28:19.825  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-25 08:28:19.825  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:19.825  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-25 08:28:19.826  6132  6132 D BtGatt.ScanManager: awakened up at time 239915
10-25 08:28:19.826  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-25 08:28:19.826  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-25 08:28:19.827  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-25 08:28:19.827  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.829  5922  5968 D BluetoothAdapter: STATE_ON
,10-25 08:28:19.831  6132  6148 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 08:28:19.831  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:19.831  6132  6151 D BtGatt.ScanManager: stopping BLe Batch
,10-25 08:28:19.833  6132  6172 D BtGatt.GattService: registerClient() - UUID=cc749326-f431-490b-b2ec-0f5f10db3b3c
,10-25 08:28:19.833  6132  6148 D BtGatt.GattService: onClientRegistered() - UUID=cc749326-f431-490b-b2ec-0f5f10db3b3c, clientIf=5
10-25 08:28:19.833  5922  5933 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-25 08:28:19.834  6132  6142 D BtGatt.GattService: start scan with filters
,10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-25 08:28:19.838  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.838  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:19.839  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:19.839  5922  5968 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-25 08:28:19.839  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-25 08:28:19.839  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-25 08:28:19.839  6132  6148 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-25 08:28:19.839  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:19.839  6132  6151 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-25 08:28:19.840  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-25 08:28:19.840  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-25 08:28:19.840  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-25 08:28:19.840  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-25 08:28:19.841  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-25 08:28:19.841  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-25 08:28:19.841  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-25 08:28:19.841  5922  6193 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-25 08:28:19.842  5922  6193 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-25 08:28:19.842  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
10-25 08:28:19.842  5922  5968 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-25 08:28:19.841  6143  6143 W Binder_2: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[34570]" dev="sockfs" ino=34570 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-25 08:28:19.841  6143  6143 W Binder_2: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[34570]" dev="sockfs" ino=34570 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-25 08:28:19.846  5922  6193 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-25 08:28:19.852  6132  6148 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,10-25 08:28:19.852  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:19.852  6132  6148 D BtGatt.GattService: current time is 239941941315
10-25 08:28:19.852  6132  6148 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -82, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -79, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-25 08:28:19.853  6132  6151 D BtGatt.ScanManager: handling starting scan
10-25 08:28:19.854  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,10-25 08:28:19.854  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:19.854  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.854  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-25 08:28:19.854  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-25 08:28:19.855  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
10-25 08:28:19.855  5922  5968 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-25 08:28:19.855  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.855  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.855  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:19.855  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-25 08:28:19.855  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.855  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-25 08:28:19.856  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:19.858  6132  6172 D BtGatt.GattService: registerClient() - UUID=a804d37a-f4ad-4914-86e9-21b67f24201d
10-25 08:28:19.859  6132  6148 D BtGatt.GattService: onClientRegistered() - UUID=a804d37a-f4ad-4914-86e9-21b67f24201d, clientIf=6
,10-25 08:28:19.859  5922  5933 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
,10-25 08:28:19.861  6132  6150 D BtGatt.AdvertiseManager: message : 0
10-25 08:28:19.862  6132  6148 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-25 08:28:19.862  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 08:28:19.862  6132  6151 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,10-25 08:28:19.864  6132  6150 D BtGatt.AdvertiseManager: starting multi advertising
,10-25 08:28:19.867  6132  6148 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,10-25 08:28:19.867  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:19.867  6132  6151 D BtGatt.ScanManager: Starting BLE batch scan
10-25 08:28:19.868  6132  6151 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,10-25 08:28:19.875  6132  6148 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,10-25 08:28:19.883  6132  6148 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,10-25 08:28:19.883  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-25 08:28:19.887  6132  6148 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,10-25 08:28:19.888  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = trueCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.888  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-25 08:28:19.889  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
10-25 08:28:19.889  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-25 08:28:19.890  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-25 08:28:19.890  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.891  6132  6148 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-25 08:28:19.891  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:19.893  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.893  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.893  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:19.893  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-25 08:28:19.893  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.893  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
,10-25 08:28:19.894  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=DB:69:06:8B:FC:D2, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[-46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-79, mTimestampNanos=237992345972}
10-25 08:28:19.894  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=D2:74:8F:0E:D1:25, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-81, mTimestampNanos=237642345972}
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: 
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: checkScanResult: ScanResult{mDevice=C8:16:A4:7E:61:23, mScanRecord=ScanRecord [mAdvertiseFlags=6, mServiceUuids=null, mManufacturerSpecificData={76=[2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]}, mServiceData={0000180a-0000-1000-8000-00805f9b34fb=[35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]}, mTxPowerLevel=-2147483648, mDeviceName=estimote], mRssi=-82, mTimestampNanos=238092345972}
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
,10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged true. Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.895  5922  5922 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-25 08:28:19.895  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.896  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.896  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
,10-25 08:28:19.896  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.898  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.898  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
10-25 08:28:19.898  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.898  5922  5922 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.898  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
10-25 08:28:19.898  5922  5922 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[main,5,main], id: 1
10-25 08:28:19.898  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,10-25 08:28:20.365   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:20.399  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-25 08:28:20.400  5922  5922 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-25 08:28:20.400  5922  5922 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-25 08:28:21.366   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:22.366   603   603 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-25 08:28:22.571   927  3077 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 13, 15 -> obsolete
,10-25 08:28:22.896  5922  5968 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-25 08:28:22.897  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-25 08:28:22.897  5922  5968 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-25 08:28:22.897  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-25 08:28:22.897  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,10-25 08:28:22.898  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-25 08:28:22.898  5922  6193 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-25 08:28:22.898  5922  6193 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-25 08:28:22.898  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-25 08:28:22.898  5922  6193 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-25 08:28:22.898  5922  5968 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-25 08:28:22.899  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-25 08:28:22.899  5922  5922 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-25 08:28:22.899  5922  5968 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d2972fb removed from the list
,10-25 08:28:22.899  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-25 08:28:22.899  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-25 08:28:22.899  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-25 08:28:22.899  5922  5922 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-25 08:28:22.899  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-25 08:28:22.899  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-25 08:28:22.900  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.900  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.900  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,10-25 08:28:22.902  5922  5968 D BluetoothAdapter: STATE_ON
10-25 08:28:22.905  6132  6172 D BtGatt.GattService: stopScan() - queue size =1
10-25 08:28:22.908  6132  6159 D BtGatt.GattService: unregisterClient() - clientIf=5
10-25 08:28:22.909  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-25 08:28:22.910  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.910  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-25 08:28:22.911  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.911  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.911  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
,10-25 08:28:22.911  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
10-25 08:28:22.912  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.912  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.912  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
10-25 08:28:22.912  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:22.913  6132  6132 D BtGatt.ScanManager: awakened up at time 243002
10-25 08:28:22.916  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.916  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 08:28:22.917  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.917  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.917  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.917  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.917  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-25 08:28:22.917  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.918  6132  6150 D BtGatt.AdvertiseManager: message : 1
10-25 08:28:22.919  6132  6150 D BtGatt.AdvertiseManager: stop advertise for client 6
10-25 08:28:22.919  6132  6148 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-25 08:28:22.919  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:22.920  6132  6151 D BtGatt.ScanManager: stopping BLe Batch
,10-25 08:28:22.929  6132  6148 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
10-25 08:28:22.930  6132  6148 D BtGatt.GattService: Client app is not null!
10-25 08:28:22.931  6132  6159 D BtGatt.GattService: unregisterClient() - clientIf=6
10-25 08:28:22.932  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-25 08:28:22.932  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,10-25 08:28:22.932  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-25 08:28:22.932  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged false. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.932  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-25 08:28:22.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-25 08:28:22.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.933  5922  5968 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-25 08:28:22.933  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.935  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-25 08:28:22.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finishedCurrent thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.936  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-25 08:28:22.936  5922  5968 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-25 08:28:22.938  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-25 08:28:22.939  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.940  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.940  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.940  5922  5968 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
10-25 08:28:22.940  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25, 08:28:22.940  5922  5968 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d09f18 removed from the list
10-25 08:28:22.940  5922  5922 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-25 08:28:22.940  5922  5968 D io.jxcore.node.ConnectivityMonitor: stop
10-25 08:28:22.941  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
10-25 08:28:22.941  5922  5968 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-25 08:28:22.941  5922  5922 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-25 08:28:22.943  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
10-25 08:28:22.943  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-25 08:28:22.943  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-25 08:28:22.943  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-25 08:28:22.943  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-25 08:28:22.943  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-25 08:28:22.943  5922  5968 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-25 08:28:22.944  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
10-25 08:28:22.945  6132  6148 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-25 08:28:22.945  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:22.946  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
10-25 08:28:22.946  6132  6151 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
10-25 08:28:22.947  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
10-25 08:28:22.947  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
10-25 08:28:22.949  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-25 08:28:22.950  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
10-25 08:28:22.954  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
10-25 08:28:22.955  5922  5968 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-25 08:28:22.966  6132  6148 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,10-25 08:28:22.966  6132  6148 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-25 08:28:22.966  6132  6148 D BtGatt.GattService: current time is 243055650305
10-25 08:28:22.966  6132  6148 D BtGatt.GattService: Batch record : [61, -98, 105, 33, 126, 81, 1, -128, -43, 23, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 81, 34, 97, 112, -14, -5, 1, -128, -84, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -86, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -81, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -84, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -78, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-25 08:28:22.966  6132  6148 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-25 08:28:22.967  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-25 08:28:22.967  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-25 08:28:22.967  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-25 08:28:22.967  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-25 08:28:22.967  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-25 08:28:22.967  6132  6148 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, ,37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,10-25 08:28:23.318   927  3077 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 14, 15 -> obsolete
,10-25 08:28:23.442  5922  5922 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-25 08:28:24.959  5922  5968 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-25 08:28:25.111  5922  6195 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 08:28:25.111  5922  6195 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 08:28:25.680   927  3077 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,10-25 08:28:25.681   927  3077 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-25 08:28:25.681   927  3077 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 08:28:25.691   927  3077 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-25 08:28:25.720   927  3077 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-25 08:28:25.721  6186  6186 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-25 08:28:25.926  5922  6195 W !!      : call onHalfStreamCopied
,10-25 08:28:25.926  5922  6195 I testCopyDataAndClose: closing input stream
,10-25 08:28:26.190  6186  6186 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-25 08:28:26.236  6186  6186 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-25 08:28:26.237  6186  6186 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-25 08:28:26.249   927  3077 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} },
10-25 08:28:26.249   927  3077 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-25 08:28:26.249   927  3089 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-25 08:28:26.266   927  3077 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-25 08:28:26.278   505   920 D CommandListener: Setting iface cfg
,10-25 08:28:26.285   927  3077 D WifiStateMachine: Start Dhcp Watchdog 2
,10-25 08:28:26.292   927  6199 D DhcpClient: Receive thread started
,10-25 08:28:26.296   927  3089 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-25 08:28:26.296   927  3077 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-25 08:28:26.296   927  3089 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-25 08:28:26.381   927  3077 E native  : do suspend false
,10-25 08:28:26.398   927  6198 D DhcpClient: Broadcasting DHCPDISCOVER
,10-25 08:28:26.412   927  6199 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172594, domain null
,10-25 08:28:26.413   927  6198 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172594 seconds
10-25 08:28:26.414   927  6198 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-25 08:28:26.428   927  6199 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-25 08:28:26.429   927  6198 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-25 08:28:26.432   505   920 D CommandListener: Setting iface cfg
,10-25 08:28:26.436   927  3077 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-25 08:28:26.441   927  6198 D DhcpClient: Scheduling renewal in 86399s
,10-25 08:28:26.451   927  3077 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-25 08:28:26.451   927  3077 D WifiConfigStore: No blacklist allowed without epno enabled
10-25 08:28:26.452   927  3089 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-25 08:28:26.471   927  3089 D ConnectivityService: Adding iface wlan0 to network 101
,10-25 08:28:26.481   927  3077 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-25 08:28:26.521   927  3089 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-25 08:28:26.521   927  3089 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,10-25 08:28:26.523   927  3089 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-25 08:28:26.525   927  3089 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-25 08:28:26.527   927  3089 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-25 08:28:26.532   927  3089 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-25 08:28:26.537   927  3089 D ConnectivityService: scheduleUnvalidatedPrompt 101
,10-25 08:28:26.537   927  3089 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-25 08:28:26.537   927  3089 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-25 08:28:26.537   927  3077 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-25 08:28:26.537   927  3089 D ConnectivityService:    accepting network in place of null
10-25 08:28:26.537   927  3077 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-25 08:28:26.538   927  3089 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-25 08:28:26.543   927  6197 D NetlinkSocketObserver: NeighborEvent{elapsedMs=246632, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-25 08:28:26.558   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 08:28:26.578   505   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-25 08:28:26.582   927  3089 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,10-25 08:28:26.582   927  3089 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-25 08:28:26.582  3886  4021 W QCNEJ   : |CORE| network available: 101
10-25 08:28:26.583   927  3089 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-25 08:28:26.584   927   944 D Tethering: MasterInitialState.processMessage what=3
10-25 08:28:26.588  3886  4021 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
10-25 08:28:26.589  3886  4021 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-25 08:28:26.589  3886  4021 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 08:28:26.593  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 08:28:26.595  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-25 08:28:26.600  5922  5922 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-25 08:28:26.602  5922  5922 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-25 08:28:26.611  5194  5217 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,10-25 08:28:26.611  5194  5217 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-25 08:28:26.611  5194  5217 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-25 08:28:26.611  5194  5217 E SarControlService: no key has been found,reset the power
10-25 08:28:26.612   927  6196 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-25 08:28:26.612  5194  5231 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-25 08:28:26.612  5194  5231 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-25 08:28:26.612  5194  5231 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-25 08:28:26.612  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 08:28:26.612  5219  5219 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,10-25 08:28:26.613  5194  5231 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-25 08:28:26.613  5194  5231 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-25 08:28:26.613  5194  5231 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-25 08:28:26.616  3867  3867 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,10-25 08:28:26.618  5058  5058 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,10-25 08:28:26.620  5219  5233 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1af3e47 HexData = [00000000ec03000000000000ffffffff]
,10-25 08:28:26.621  5219  5233 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 08:28:26.621  5219  5233 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
10-25 08:28:26.622  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 08:28:26.622  5194  5205 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-25 08:28:26.622  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-25 08:28:26.622  5219  5219 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-25 08:28:26.623  3867  3867 D SystemUpdateService: onCreate
,10-25 08:28:26.626  5219  5233 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@1af3e47 HexData = [00000000ed03000000000000ffffffff]
10-25 08:28:26.626  5219  5233 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-25 08:28:26.626  5219  5233 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-25 08:28:26.627  5219  5219 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-25 08:28:26.627  5194  5204 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-25 08:28:26.629  3867  3867 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,10-25 08:28:26.640  3867  3867 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-25 08:28:26.645  3867  6209 I SystemUpdateService: active receiver: enabled
,10-25 08:28:26.649  3867  3867 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-25 08:28:26.650  3867  3867 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-25 08:28:26.652  6002  6002 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-25 08:28:26.657  6002  6002 D SprintDMHelper: simOperator: 
,10-25 08:28:26.657  6002  6002 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-25 08:28:26.662   927  6196 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 25 Oct 2016 12:28:26 GMT], X-Android-Received-Millis=[1477398506661], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1477398506635]}
,10-25 08:28:26.663   927  3089 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-25 08:28:26.663   927  3089 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-25 08:28:26.658  3867  5562 I iu.UploadsManager: num queued entries: 0
10-25 08:28:26.663   927  3089 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-25 08:28:26.664   927  3089 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-25 08:28:26.666  3867  5562 I iu.UploadsManager: num updated entries: 0
,10-25 08:28:26.668  3867  6209 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-25 08:28:26.672  3867  5562 I iu.SyncManager: NEXT; no task
,10-25 08:28:26.689  3867  6209 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
10-25 08:28:26.689  3867  6209 I SystemUpdateService: now status is 0 (complete)
,10-25 08:28:26.689  3867  6209 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-25 08:28:26.689  3867  6209 I SystemUpdateService: file has been verified
10-25 08:28:26.689  3867  6209 I SystemUpdateService: OTA package size = 21989297
,10-25 08:28:26.702  3867  6209 I SystemUpdateService: showing system update notification
,10-25 08:28:26.712  3867  3867 D SystemUpdateService: onDestroy
,10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-25 08:28:26.713  5922  6195 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-25 08:28:26.815  5160  6216 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-25 08:28:27.584   927  3089 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-25 08:28:27.820   927  3077 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,10-25 08:28:30.524  5922  5968 I StreamCopyingThreadTest: Starting test: testRun
,10-25 08:28:30.528  5922  6223 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: My test thread name). Connection data: Peer properties: [null null].
10-25 08:28:30.528  5922  6223 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 08:28:32.368   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:33.369   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:34.370   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:34.542   927  3089 D ConnectivityService: handlePromptUnvalidated 101
,10-25 08:28:35.372   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:35.534  5922  6224 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,10-25 08:28:35.536  5922  5968 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-25 08:28:35.660  5922  6225 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 08:28:35.660  5922  6225 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 08:28:36.373   603   603 I ServiceManager: Waiting for service AtCmdFwd...
,10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-25 08:28:37.348  5922  6225 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-25 08:28:37.374   603   603 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-25 08:28:41.119  5922  5968 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-25 08:28:41.121  5922  6226 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
10-25 08:28:41.121  5922  6226 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-25 08:28:41.121  5922  6226 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 164, thread name: My test thread name). Connection data: Peer properties: [null null].
10-25 08:28:41.121  5922  6226 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 08:28:41.122  5922  6226 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-25 08:28:41.122  5922  6226 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 08:28:41.122  5922  6226 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-25 08:28:41.122  5922  6226 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-25 08:28:41.122  5922  6226 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-25 08:28:41.122  5922  6226 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-25 08:28:41.122  5922  6226 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-25 08:28:41.123  5922  6226 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 164, name: My test thread name). Connection data: Peer properties: [null null].
10-25 08:28:41.123  5922  6226 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,10-25 08:28:41.124  5922  5968 I StreamCopyingThreadTest: Starting test: testSetBufferSize
10-25 08:28:41.125  5922  5968 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,10-25 08:28:41.126  5922  5968 I StreamCopyingThreadTest: Starting test: testRunWithException
,10-25 08:28:41.127  5922  6227 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-25 08:28:41.127  5922  6227 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-25 08:28:41.128  5922  6227 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 168, thread name: My test thread name): Test exception.
,10-25 08:28:41.128  5922  6227 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-25 08:28:41.128  5922  6227 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-25 08:28:41.129  5922  6227 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-25 08:28:41.129  5922  6227 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 168, name: My test thread name). Connection data: Peer properties: [null null].
10-25 08:28:41.129  5922  6227 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,10-25 08:28:41.130  5922  5968 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
10-25 08:28:41.131  5922  5968 E com.test.thalitest.ThaliTestRunner: 
10-25 08:28:41.131  5922  5968 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-25 08:28:41.131  5922  5968 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.,junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
10-25 0,8:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-25 08:28:41.132  5922  5968 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: ,	,at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
,10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: ,	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
,10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
,10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:41.133  5922  5968 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
,10-25 08:28:41.136  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG UnitTest_app: 'Running unit tests'
10-25 08:28:41.136  5922  5968 I jxcore-log: 
10-25 08:28:41.136  5922  5968 I jxcore-log: *Native tests were executed*
,10-25 08:28:41.136  5922  5968 I jxcore-log: 
10-25 08:28:41.136  5922  5968 I jxcore-log: Total number of executed tests:  82
10-25 08:28:41.136  5922  5968 I jxcore-log: 
10-25 08:28:41.136  5922  5968 I jxcore-log: Number of passed tests:  80
10-25 08:28:41.136  5922  5968 I jxcore-log: 
10-25 08:28:41.136  5922  5968 I jxcore-log: Number of failed tests:  2
10-25 08:28:41.136  5922  5968 I jxcore-log: 
10-25 08:28:41.136  5922  5968 I jxcore-log: Number of ignored tests:  0
10-25 08:28:41.136  5922  5968 I jxcore-log: ,
10-25 08:28:41.137  5922  5968 I jxcore-log: Total duration:  41034
10-25 08:28:41.137  5922  5968 I jxcore-log: 
10-25 08:28:41.137  5922  5968 I jxcore-log: Failed to execute UT.
10-25 08:28:41.137  5922  5968 I jxcore-log: 
10-25 08:28:41.138  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-25 08:28:41.138  5922  5968 I jxcore-log: 
10-25 08:28:41.139  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-25 08:28:41.139  5922  5968 I jxcore-log: 
,10-25 08:28:41.142  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 08:28:41.142  5922  5968 I jxcore-log: 
10-25 08:28:41.142  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.142  5922  5968 I jxcore-log: 
,10-25 08:28:41.143  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 08:28:41.143  5922  5968 I jxcore-log: 
10-25 08:28:41.144  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.144  5922  5968 I jxcore-log: 
10-25 08:28:41.145  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 08:28:41.145  5922  5968 I jxcore-log: 
10-25 08:28:41.145  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.145  5922  5968 I jxcore-log: 
,10-25 08:28:41.145  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 08:28:41.145  5922  5968 I jxcore-log: 
10-25 08:28:41.145  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 08:28:41.145  5922  5968 I jxcore-log: 
10-25 08:28:41.146  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 08:28:41.146  5922  5968 I jxcore-log: 
,10-25 08:28:41.146  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 08:28:41.146  5922  5968 I jxcore-log: 
10-25 08:28:41.146  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 08:28:41.146  5922  5968 I jxcore-log: 
10-25 08:28:41.146  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.146  5922  5968 I jxcore-log: 
,10-25 08:28:41.147  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.147  5922  5968 I jxcore-log: 
10-25 08:28:41.147  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.147  5922  5968 I jxcore-log: 
10-25 08:28:41.147  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 08:28:41.147  5922  5968 I jxcore-log: 
,10-25 08:28:41.147  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.147  5922  5968 I jxcore-log: 
10-25 08:28:41.148  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 08:28:41.148  5922  5968 I jxcore-log: 
10-25 08:28:41.148  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.148  5922  5968 I jxcore-log: 
,10-25 08:28:41.148  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 08:28:41.148  5922  5968 I jxcore-log: 
10-25 08:28:41.148  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.148  5922  5968 I jxcore-log: 
10-25 08:28:41.148  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 08:28:41.148  5922  5968 I jxcore-log: 
10-25 08:28:41.149  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
,10-25 08:28:41.149  5922  5968 I jxcore-log: 
10-25 08:28:41.149  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.149  5922  5968 I jxcore-log: 
10-25 08:28:41.149  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.149  5922  5968 I jxcore-log: 
10-25 08:28:41.149  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.149  5922  5968 I jxcore-log: 
10-25 08:28:41.150  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.150  5922  5968 I jxcore-log: 
,10-25 08:28:41.150  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.150  5922  5968 I jxcore-log: 
10-25 08:28:41.150  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.150  5922  5968 I jxcore-log: 
10-25 08:28:41.150  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.150  5922  5968 I jxcore-log: 
,10-25 08:28:41.152  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.152  5922  5968 I jxcore-log: 
10-25 08:28:41.152  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.152  5922  5968 I jxcore-log: 
10-25 08:28:41.152  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.152  5922  5968 I jxcore-log: 
10-25 08:28:41.152  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.152  5922  5968 I jxcore-log: 
10-25 08:28:41.153  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.153  5922  5968 I jxcore-log: 
10-25 08:28:41.153  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.153  5922  5968 I jxcore-log: 
10-25 08:28:41.153  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.153  5922  5968 I jxcore-log: 
,10-25 08:28:41.153  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.153  5922  5968 I jxcore-log: 
10-25 08:28:41.153  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.153  5922  5968 I jxcore-log: 
10-25 08:28:41.153  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.153  5922  5968 I jxcore-log: 
10-25 08:28:41.154  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.154  5922  5968 I jxcore-log: 
,10-25 08:28:41.154  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.154  5922  5968 I jxcore-log: 
10-25 08:28:41.154  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.154  5922  5968 I jxcore-log: 
10-25 08:28:41.154  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.154  5922  5968 I jxcore-log: 
,10-25 08:28:41.154  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.154  5922  5968 I jxcore-log: 
10-25 08:28:41.155  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.155  5922  5968 I jxcore-log: 
10-25 08:28:41.155  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.155  5922  5968 I jxcore-log: 
10-25 08:28:41.155  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.155  5922  5968 I jxcore-log: 
,10-25 08:28:41.155  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.155  5922  5968 I jxcore-log: 
10-25 08:28:41.155  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.155  5922  5968 I jxcore-log: 
10-25 08:28:41.156  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.156  5922  5968 I jxcore-log: 
,10-25 08:28:41.156  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.156  5922  5968 I jxcore-log: 
10-25 08:28:41.156  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 08:28:41.156  5922  5968 I jxcore-log: 
10-25 08:28:41.156  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.156  5922  5968 I jxcore-log: 
,10-25 08:28:41.156  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 08:28:41.156  5922  5968 I jxcore-log: 
10-25 08:28:41.156  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.156  5922  5968 I jxcore-log: 
10-25 08:28:41.157  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-25 08:28:41.157  5922  5968 I jxcore-log: 
10-25 08:28:41.157  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.157  5922  5968 I jxcore-log: 
,10-25 08:28:41.157  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.157  5922  5968 I jxcore-log: 
10-25 08:28:41.157  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.157  5922  5968 I jxcore-log: 
10-25 08:28:41.157  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.157  5922  5968 I jxcore-log: 
10-25 08:28:41.158  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.158  5922  5968 I jxcore-log: 
10-25 08:28:41.158  5922  5922 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,10-25 08:28:41.158  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.158  5922  5968 I jxcore-log: 
10-25 08:28:41.158  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.158  5922  5968 I jxcore-log: 
10-25 08:28:41.158  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-25 08:28:41.158  5922  5968 I jxcore-log: 
,10-25 08:28:41.158  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.158  5922  5968 I jxcore-log: 
10-25 08:28:41.159  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-25 08:28:41.159  5922  5968 I jxcore-log: 
10-25 08:28:41.159  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-25 08:28:41.159  5922  5968 I jxcore-log: 
10-25 08:28:41.159  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
10-25 08:28:41.159  5922  5968 I jxcore-log: 
10-25 08:28:41.159  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-25 08:28:41.159  5922  5968 I jxcore-log: ,
10-25 08:28:41.159  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 08:28:41.159  5922  5968 I jxcore-log: 
10-25 08:28:41.160  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.160  5922  5968 I jxcore-log: 
10-25 08:28:41.160  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-25 08:28:41.160  5922  5968 I jxcore-log: 
,10-25 08:28:41.160  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-25 08:28:41.160  5922  5968 I jxcore-log: 
10-25 08:28:41.165  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-25 08:28:41.165  5922  5968 I jxcore-log: 
10-25 08:28:41.165  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - WARN testUtils: 'myNameCallback not set!'
10-25 08:28:41.165  5922  5968 I jxcore-log: 
10-25 08:28:41.166  5922  5968 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
10-25 08:28:41.167  5922  5968 I jxcore-log: 2016-10-25 12:28:41 - DEBUG UnitTest_app: 'Running for NATIVE network type'
,10-25 08:28:41.167  5922  5968 I jxcore-log: 
,10-25 08:28:43.148  5922  5968 I jxcore-log: 2016-10-25 12:28:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-25 08:28:43.148  5922  5968 I jxcore-log: 
,10-25 08:28:43.474  5922  5968 I jxcore-log: 2016-10-25 12:28:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-25 08:28:43.474  5922  5968 I jxcore-log: 
,10-25 08:28:43.489  5922  5968 I jxcore-log: 2016-10-25 12:28:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-25 08:28:43.489  5922  5968 I jxcore-log: 
,10-25 08:28:44.559  5922  5968 I jxcore-log: 2016-10-25 12:28:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-25 08:28:44.559  5922  5968 I jxcore-log: 
,10-25 08:28:44.705  5922  5968 I jxcore-log: 2016-10-25 12:28:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-25 08:28:44.705  5922  5968 I jxcore-log: 
,10-25 08:28:44.710  5922  5968 I jxcore-log: 2016-10-25 12:28:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-25 08:28:44.710  5922  5968 I jxcore-log: 
,10-25 08:28:44.715  5922  5968 I jxcore-log: 2016-10-25 12:28:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-25 08:28:44.715  5922  5968 I jxcore-log: 
,10-25 08:28:45.185  5922  5968 I jxcore-log: 2016-10-25 12:28:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-25 08:28:45.185  5922  5968 I jxcore-log: 
,10-25 08:28:45.226  5922  5968 I jxcore-log: 2016-10-25 12:28:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-25 08:28:45.226  5922  5968 I jxcore-log: 
,10-25 08:28:45.239  5922  5968 I jxcore-log: 2016-10-25 12:28:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-25 08:28:45.239  5922  5968 I jxcore-log: 
,10-25 08:28:45.244  5922  5968 I jxcore-log: 2016-10-25 12:28:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-25 08:28:45.244  5922  5968 I jxcore-log: 
,10-25 08:28:45.515  5922  5968 I jxcore-log: 2016-10-25 12:28:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-25 08:28:45.515  5922  5968 I jxcore-log: 
,10-25 08:28:45.637  5922  5968 I jxcore-log: 2016-10-25 12:28:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-25 08:28:45.637  5922  5968 I jxcore-log: 
,10-25 08:28:46.010  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-25 08:28:46.010  5922  5968 I jxcore-log: 
,10-25 08:28:46.044  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
10-25 08:28:46.044  5922  5968 I jxcore-log: 
,10-25 08:28:46.051  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-25 08:28:46.051  5922  5968 I jxcore-log: 
,10-25 08:28:46.057  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-25 08:28:46.057  5922  5968 I jxcore-log: 
,10-25 08:28:46.066  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
10-25 08:28:46.066  5922  5968 I jxcore-log: 
,10-25 08:28:46.079  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-25 08:28:46.079  5922  5968 I jxcore-log: 
,10-25 08:28:46.085  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-25 08:28:46.085  5922  5968 I jxcore-log: 
,10-25 08:28:46.112  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-25 08:28:46.112  5922  5968 I jxcore-log: 
,10-25 08:28:46.147  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-25 08:28:46.147  5922  5968 I jxcore-log: 
,10-25 08:28:46.154  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-25 08:28:46.154  5922  5968 I jxcore-log: 
,10-25 08:28:46.161  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-25 08:28:46.161  5922  5968 I jxcore-log: 
,10-25 08:28:46.176  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-25 08:28:46.176  5922  5968 I jxcore-log: 
,10-25 08:28:46.180  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-25 08:28:46.180  5922  5968 I jxcore-log: 
,10-25 08:28:46.186  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-25 08:28:46.186  5922  5968 I jxcore-log: 
,10-25 08:28:46.191  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-25 08:28:46.191  5922  5968 I jxcore-log: 
,10-25 08:28:46.204  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-25 08:28:46.204  5922  5968 I jxcore-log: 
,10-25 08:28:46.226  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-25 08:28:46.226  5922  5968 I jxcore-log: 
,10-25 08:28:46.237  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-25 08:28:46.237  5922  5968 I jxcore-log: 
,10-25 08:28:46.249  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-25 08:28:46.249  5922  5968 I jxcore-log: 
,10-25 08:28:46.259  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-25 08:28:46.259  5922  5968 I jxcore-log: 
,10-25 08:28:46.272  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-25 08:28:46.272  5922  5968 I jxcore-log: 
,10-25 08:28:46.281  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-25 08:28:46.281  5922  5968 I jxcore-log: 
,10-25 08:28:46.286  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-25 08:28:46.286  5922  5968 I jxcore-log: 
,10-25 08:28:46.292  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-25 08:28:46.292  5922  5968 I jxcore-log: 
,10-25 08:28:46.300  5922  5968 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-25 08:28:46.301  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - INFO testUtils: 'BLE multiple advertisement supported'
10-25 08:28:46.301  5922  5968 I jxcore-log: 
,10-25 08:28:46.459  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - DEBUG CoordinatedClient: 'connected to the test server'
10-25 08:28:46.459  5922  5968 I jxcore-log: 
,10-25 08:28:46.729  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-25 08:28:46.729  5922  5968 I jxcore-log: 
,10-25 08:28:46.731  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - DEBUG CoordinatedClient: 'test client failed'
10-25 08:28:46.731  5922  5968 I jxcore-log: 
,10-25 08:28:46.734  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-25 08:28:46.734  5922  5968 I jxcore-log: 
,10-25 08:28:46.739  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-25 08:28:46.739  5922  5968 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-25 08:28:46.739  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-25 08:28:46.739  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-25 08:28:46.739  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-25 08:28:46.739  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-25 08:28:46.739  5922  5968 I jxcore-log: 
,10-25 08:28:46.740  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-25 08:28:46.740  5922  5968 I jxcore-log: 
,10-25 08:28:46.744  5922  5968 I jxcore-log: 2016-10-25 12:28:46 - ERROR runTests: 'Test client failed: Native unit tests failed
10-25 08:28:46.744  5922  5968 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-25 08:28:46.744  5922  5968 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-25 08:28:46.744  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-25 08:28:46.744  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-25 08:28:46.744  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-25 08:28:46.744  5922  5968 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
10-25 08:28:46.744  5922  5968 I jxcore-log: 
,10-25 08:28:47.327  6236  6236 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-25 08:28:47.350  6236  6236 D AndroidRuntime: CheckJNI is OFF
,10-25 08:28:47.380  6236  6236 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-25 08:28:47.415  6236  6236 I Radio-JNI: register_android_hardware_Radio DONE
,10-25 08:28:47.432  6236  6236 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-25 08:28:47.443   927   940 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-25 08:28:47.444   927   940 I ActivityManager: Killing 5922:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-25 08:28:47.543   927  3965 D GraphicsStats: Buffer count: 2
,10-25 08:28:47.543   927  3085 D WifiService: Client connection lost with reason: 4
,10-25 08:28:47.543   927  3276 I WindowState: WIN DEATH: Window{cd045b1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-25 08:28:47.572   927   940 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-25 08:28:47.574   927   940 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-25 08:28:47.575   927   950 I art     : Starting a blocking GC Explicit
10-25 08:28:47.576   927   940 E ActivityManager: Failure starting process com.test.thalitest
10-25 08:28:47.576   927   940 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-25 08:28:47.576   927   940 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:47.576   927   940 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:47.576   927   940 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-25 08:28:47.576   927   940 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-25 08:28:47.576   927   940 I ActivityManager:   Force finishing activity ActivityRecord{8c9c06a u0 com.test.thalitest/.MainActivity t2}
,10-25 08:28:47.581   927  3952 W ActivityManager: Spurious death for ProcessRecord{5301e2b 0:com.test.thalitest/u0a77}, curProc for 5922: null
,10-25 08:28:47.585   927   945 W WindowManager: Attempted to add application window with unknown token Token{283695b ActivityRecord{8c9c06a u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,10-25 08:28:47.585   927   945 W WindowManager: Token{283695b ActivityRecord{8c9c06a u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{283695b ActivityRecord{8c9c06a u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-25 08:28:47.585   927   945 W WindowManager: view not successfully added to wm, removing view
10-25 08:28:47.586   927   945 W WindowManager: Exception when adding starting window
10-25 08:28:47.586   927   945 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a4cead2 V.E...... R.....ID 0,0-0,0} not attached to window manager
10-25 08:28:47.586   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-25 08:28:47.586   927   945 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-25 08:28:47.586   927   945 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-25 08:28:47.586   927   945 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-25 08:28:47.586   927   945 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-25 08:28:47.586   927   945 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:47.586   927   945 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:47.586   927   945 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-25 08:28:47.586   927   945 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-25 08:28:47.650   927   950 I art     : Explicit concurrent mark sweep GC freed 19005(1202KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.535ms total 74.737ms
,10-25 08:28:47.668   927   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-25 08:28:47.670  6236  6236 I art     : System.exit called, status: 0
,10-25 08:28:47.671  6236  6236 I AndroidRuntime: VM exiting with result code 0.
,10-25 08:28:47.687   927   950 I ActivityManager: Start proc 6246:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,10-25 08:28:47.688   927   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-25 08:28:47.693   927   940 I ActivityManager: Exiting empty application process com.test.thalitest (null)
10-25 08:28:47.697  6132  6132 D BluetoothMapAppObserver: onReceive
,10-25 08:28:47.698  6132  6132 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,10-25 08:28:47.701  4184  4299 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,10-25 08:28:47.702  3766  3766 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-25 08:28:47.706   927  3053 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-25 08:28:47.718  3766  6258 I Keyboard.Facilitator.DecoderInitializer: run()
,10-25 08:28:47.732  3766  6258 I Decoder : createOrResetDecoder
,10-25 08:28:47.760  3511  6261 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-25 08:28:47.760  3917  3917 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-25 08:28:47.778  3695  3695 I ConfigService: onCreate
,10-25 08:28:47.774   435   435 W kworker/5:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-25 08:28:47.777   435   435 W kworker/5:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 08:28:47.791   435   435 W kworker/5:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-25 08:28:47.793  3695  3695 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,10-25 08:28:47.793  3695  3695 D AndroidRuntime: Shutting down VM
--------- beginning of crash
10-25 08:28:47.794  3695  3695 E AndroidRuntime: FATAL EXCEPTION: main
10-25 08:28:47.794  3695  3695 E AndroidRuntime: Process: com.google.process.gapps, PID: 3695
10-25 08:28:47.794  3695  3695 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
10-25 08:28:47.794  3695  3695 E AndroidRuntime: 	... 8 more
10-25 08:28:47.797   927   927 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-25 08:28:47.801  3695  3695 I Process : Sending signal. PID: 3695 SIG: 9
,10-25 08:28:47.802  3960  4053 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,10-25 08:28:47.805   927  6267 E DropBoxManagerService: Can't write: system_app_crash
10-25 08:28:47.805   927  6267 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
10-25 08:28:47.805   927  6267 E DropBoxManagerService: 	... 8 more
,10-25 08:28:47.818  3511  3535 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjCF5B299AE) - 
,10-25 08:28:47.819  3511  3535 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
10-25 08:28:47.819  3511  3535 E AndroidRuntime: Process: android.process.acore, PID: 3511
10-25 08:28:47.819  3511  3535 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:47.819  3511  3535 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-25 08:28:47.821   927  3266 I ActivityManager: Start proc 6268:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,10-25 08:28:47.821  3960  4053 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
10-25 08:28:47.821  3960  4053 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3960
10-25 08:28:47.821  3960  4053 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:47.821  3960  4053 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,10-25 08:28:47.823   927  5629 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-25 08:28:47.826   927  6273 E DropBoxManagerService: Can't write: system_app_crash
10-25 08:28:47.826   927  6273 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 08:28:47.826   927  6273 E DropBoxManagerService: 	... 5 more
10-25 08:28:47.827   927  6274 E DropBoxManagerService: Can't write: system_app_crash
10-25 08:28:47.827   927  6274 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 08:28:47.827   927  6274 E DropBoxManagerService: 	... 5 more
,10-25 08:28:47.830  3960  4053 I Process : Sending signal. PID: 3960 SIG: 9
,10-25 08:28:47.832   927  3085 D WifiService: Client connection lost with reason: 4
10-25 08:28:47.832   927  3711 I ActivityManager: Process com.google.process.gapps (pid 3695) has died
10-25 08:28:47.833   927  3711 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
10-25 08:28:47.833   927  3711 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
10-25 08:28:47.833   927  3711 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 21000ms
10-25 08:28:47.833   927  3711 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 31000ms
,10-25 08:28:47.854   927   938 I ActivityManager: Start proc 6284:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: Failed to get gconfig value
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: java.lang.NullPointerException: Attempt to invoke interface method 'java.lang.String com.google.android.gms.config.ConfigApi$Value.getAsString(java.lang.String)' on a null object reference
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at com.android.inputmethod.latin.GconfigFlagGetter.getInt(GconfigFlagGetter.java:83)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at com.android.inputmethod.latin.DecoderFlagGetter.getFlagValues(DecoderFlagGetter.java:61)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator.resetDecoderFlagValues(Delight3DictionaryFacilitator.java:94)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator.-wrap0(Delight3DictionaryFacilitator.java)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at com.android.inputmethod.latin.Delight3DictionaryFacilitator$DecoderInitializer.run(Delight3DictionaryFacilitator.java:877)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at com.android.inputmethod.latin.utils.ExecutorUtils$RunnableChain.run(ExecutorUtils.java:148)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:269)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
10-25 08:28:47.856  3766  6258 W DecoderFlagGetter: 	at java.lang.Thread.run(Thread.java:818)
,10-25 08:28:47.864  3511  6261 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-25 08:28:47.866  3511  6261 I Process : Sending signal. PID: 3511 SIG: 9
,10-25 08:28:47.938   927   937 I WindowState: WIN DEATH: Window{a8e9e31 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,10-25 08:28:47.938   927  3314 D GraphicsStats: Buffer count: 1
10-25 08:28:47.938   927  3052 W InputDispatcher: channel 'a8e9e31 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,10-25 08:28:47.938   927  3052 E InputDispatcher: channel 'a8e9e31 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
10-25 08:28:47.939   927   937 W InputDispatcher: Attempted to unregister already unregistered input channel 'a8e9e31 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,10-25 08:28:47.944   927  3965 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3960) has died
,10-25 08:28:47.945   927  3965 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
10-25 08:28:47.946   927  3965 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-25 08:28:47.966   927   940 I ActivityManager: Start proc 6297:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-25 08:28:47.968   927  3712 I ActivityManager: Process android.process.acore (pid 3511) has died
,10-25 08:28:47.969   927  3712 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-25 08:28:48.015  6297  6297 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:48.015  6297  6297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-25 08:28:48.016  6297  6297 D AndroidRuntime: Shutting down VM
,10-25 08:28:48.022  6297  6297 E AndroidRuntime: FATAL EXCEPTION: main
10-25 08:28:48.022  6297  6297 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6297
10-25 08:28:48.022  6297  6297 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-25 08:28:48.022  6297  6297 E AndroidRuntime: 	... 10 more
10-25 08:28:48.024   927  3965 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-25 08:28:48.025   927  6310 E DropBoxManagerService: Can't write: system_app_crash
10-25 08:28:48.025   927  6310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 08:28:48.025   927  6310 E DropBoxManagerService: 	... 5 more
10-25 08:28:48.025  6297  6297 I Process : Sending signal. PID: 6297 SIG: 9
10-25 08:28:48.039   927  5629 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6297) has died
10-25 08:28:48.040   927  5629 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
10-25 08:28:48.054   927   940 I ActivityManager: Start proc 6311:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,10-25 08:28:48.105  6311  6311 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:48.105  6311  6311 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-25 08:28:48.105  6311  6311 D AndroidRuntime: Shutting down VM
,10-25 08:28:48.113  6311  6311 E AndroidRuntime: FATAL EXCEPTION: main
10-25 08:28:48.113  6311  6311 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6311
10-25 08:28:48.113  6311  6311 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
10-25 08:28:48.113  6311  6311 E AndroidRuntime: 	... 10 more
10-25 08:28:48.116   927  3266 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
10-25 08:28:48.116   927  6323 E DropBoxManagerService: Can't write: system_app_crash
10-25 08:28:48.116   927  6323 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-25 08:28:48.116   927  6323 E DropBoxManagerService: 	... 5 more
10-25 08:28:48.116  6311  6311 I Process : Sending signal. PID: 6311 SIG: 9
10-25 08:28:48.138   927  3952 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6311) has died
10-25 08:28:48.140   927  3952 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,10-25 08:28:48.157   927   940 I ActivityManager: Start proc 6324:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
