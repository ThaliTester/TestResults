#### Test 86185956533f65d_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-21 11:58:15.639   929  5281 D NetlinkSocketObserver: NeighborEvent{elapsedMs=180425, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-21 11:58:16.137  5529  5529 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-21 11:58:16.143  5529  5529 D AndroidRuntime: CheckJNI is OFF
09-21 11:58:16.171  5529  5529 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-21 11:58:16.208  5529  5529 I Radio-JNI: register_android_hardware_Radio DONE
09-21 11:58:16.225  5529  5529 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-21 11:58:16.230   929  3526 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-21 11:58:16.273   929  3526 I ActivityManager: Start proc 5538:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-21 11:58:16.294  5529  5529 D AndroidRuntime: Shutting down VM
,09-21 11:58:16.614   929  3224 I WindowManager: Screenshot max retries 4 of Token{2355619 ActivityRecord{79c9160 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{acf2c78 u0 Starting com.test.thalitest} drawState=2
,09-21 11:58:16.681  5538  5538 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-21 11:58:16.715  5538  5538 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-21 11:58:16.778  5538  5538 I LibraryLoader: Time to load native libraries: 56 ms (timestamps 1508-1564)
,09-21 11:58:16.779  5538  5538 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-21 11:58:16.812  5538  5538 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {320920d}
,09-21 11:58:16.813  5538  5538 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-21 11:58:16.813  5538  5538 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-21 11:58:16.819  5538  5538 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-21 11:58:16.821  5538  5538 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-21 11:58:16.871  5538  5538 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-21 11:58:16.886  5538  5538 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-21 11:58:16.886  5538  5538 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-21 11:58:16.886  5538  5538 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-21 11:58:16.886  5538  5538 I Adreno  : Build Date                       : 12/06/15
09-21 11:58:16.886  5538  5538 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-21 11:58:16.886  5538  5538 I Adreno  : Local Branch                     : mybranch17112971
09-21 11:58:16.886  5538  5538 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-21 11:58:16.886  5538  5538 I Adreno  : Remote Branch                    : NONE
09-21 11:58:16.886  5538  5538 I Adreno  : Reconstruct Branch               : NOTHING
,09-21 11:58:16.937   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d9607af:true
,09-21 11:58:16.970   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32023]" dev="sockfs" ino=32023 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:58:16.970   406   406 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32023]" dev="sockfs" ino=32023 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:58:16.980  5538  5538 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-21 11:58:16.989  5538  5538 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-21 11:58:17.014  5538  5575 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-21 11:58:17.013   718   718 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29621]" dev="sockfs" ino=29621 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:58:17.013   718   718 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[29621]" dev="sockfs" ino=29621 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-21 11:58:17.017  3507  3507 W Binder_6: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32034]" dev="sockfs" ino=32034 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-21 11:58:17.017  3507  3507 W Binder_6: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32034]" dev="sockfs" ino=32034 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-21 11:58:17.021  5538  5562 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-21 11:58:17.040  5538  5575 I OpenGLRenderer: Initialized EGL, version 1.4
,09-21 11:58:17.118   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +499ms (total +873ms)
,09-21 11:58:17.168  5538  5538 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5538
,09-21 11:58:17.268  5538  5538 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-21 11:58:17.454  5538  5577 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -580388560
,09-21 11:58:17.461  5538  5577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-21 11:58:17.461  5538  5577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-21 11:58:17.461  5538  5577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-21 11:58:17.461  5538  5577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-21 11:58:17.461  5538  5577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-21 11:58:17.461  5538  5577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@55631da added. We now have 1 listener(s)
,09-21 11:58:17.464  5538  5577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-21 11:58:17.464  5538  5577 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 11:58:17.465  5538  5577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:17.466  5538  5577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-21 11:58:17.468  5538  5577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1037f01 added. We now have 1 listener(s)
09-21 11:58:17.468  5538  5577 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 11:58:17.476   929  3053 D WifiService: New client listening to asynchronous messages
09-21 11:58:17.476  5538  5577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-21 11:58:17.476  5538  5577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-21 11:58:17.476  5538  5577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-21 11:58:17.477  5538  5577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-21 11:58:17.477  5538  5577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-21 11:58:17.480  5538  5577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:17.480  5538  5577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-21 11:58:17.490  5538  5577 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:17.490  5538  5577 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:58:17.490  5538  5577 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-21 11:58:17.490  5538  5577 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:58:17.491  5538  5577 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 11:58:17.494  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:17.498  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:17.522  5538  5538 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-21 11:58:18.664  5538  5538 I Choreographer: Skipped 65 frames!  The application may be doing too much work on its main thread.
,09-21 11:58:19.021  5538  5547 I art     : Background sticky concurrent mark sweep GC freed 78001(7MB) AllocSpace objects, 18(1604KB) LOS objects, 25% free, 24MB/32MB, paused 1.463ms total 148.030ms
,09-21 11:58:19.207  5538  5584 W jxcore-log: Initializing JXcore engine
,09-21 11:58:19.207  5538  5584 W jxcore-log: JXcore engine is ready
,09-21 11:58:19.267  5584  5584 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11491 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-21 11:58:19.267  5584  5584 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[10580]" dev="sockfs" ino=10580 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-21 11:58:19.267  5584  5584 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-21 11:58:19.267  5584  5584 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32990]" dev="sockfs" ino=32990 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-21 11:58:19.280  5538  5584 W jxcore-log: Starting JXcore engine
,09-21 11:58:19.339  5538  5584 W jxcore-log: Platform android
09-21 11:58:19.339  5538  5584 W jxcore-log: 
,09-21 11:58:19.339  5538  5584 W jxcore-log: Process ARCH arm
09-21 11:58:19.339  5538  5584 W jxcore-log: 
,09-21 11:58:19.431  5538  5584 I jxcore-log: JXcore Cordova bridge is ready!
09-21 11:58:19.431  5538  5584 I jxcore-log: 
09-21 11:58:19.431  5538  5584 W jxcore-log: JXcore engine is started
,09-21 11:58:19.437  5538  5577 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-21 11:58:19.444  5538  5538 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-21 11:58:24.447   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 11:58:25.448   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 11:58:26.026  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-21 11:58:26.026  5538  5584 I jxcore-log: 
,09-21 11:58:26.027  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-21 11:58:26.027  5538  5584 I jxcore-log: 
,09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:26.031  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:58:26.033  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 11:58:26.035  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-21 11:58:26.035  5538  5584 I jxcore-log: 
09-21 11:58:26.036  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-21 11:58:26.036  5538  5584 I jxcore-log: 
,09-21 11:58:26.374  5538  5584 D executeNativeTests: Running unit tests
,09-21 11:58:26.415  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 11:58:26.415  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 added. We now have 2 listener(s)
,09-21 11:58:26.416  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 11:58:26.416  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:26.416  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-21 11:58:26.416  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:26.416  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 added. We now have 2 listener(s)
09-21 11:58:26.417  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:26.417  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 11:58:26.419  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:26.422  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:58:26.423  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.424  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:58:26.425  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 11:58:26.425  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-21 11:58:26.425  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 11:58:26.426  5538  5584 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-21 11:58:26.427  5538  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-21 11:58:26.427  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 11:58:26.427  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 11:58:26.427  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-21 11:58:26.427  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.427  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.427  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.428  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.428  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.428  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:26.428  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:26.428  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 removed from the list
09-21 11:58:26.428  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.428  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 removed from the list
09-21 11:58:26.435  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.438  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.438  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.438  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 11:58:26.439  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.439  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.439  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.439  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.439  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.439  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.440  5538  5584 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-21 11:58:26.440  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.441  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.441  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.441  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.441  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.441  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.441  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
,09-21 11:58:26.441  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.441  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.441  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.441  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.441  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.441  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.441  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.442  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.442  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.442  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.442  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
,09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 11:58:26.444  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 11:58:26.445  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.445  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.445  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.445  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.445  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.445  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 11:58:26.445  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.445  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.445  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.445  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.445  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.445  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.445  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.445  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.446  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.446  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.446  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.446  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.446  5538  5584 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 11:58:26.447  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:26.449   535   535 I ServiceManager: Waiting for service AtCmdFwd...
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:26.449  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:58:26.450  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.450  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:58:26.450  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:26.450  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 11:58:26.451  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:58:26.451  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:26.451  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:58:26.452  5538  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 11:58:26.453  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 11:58:26.453  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.457  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.458  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 11:58:26.460  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:58:26.460  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 11:58:26.462  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-21 11:58:26.463  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-21 11:58:26.463  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 11:58:26.463  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-21 11:58:26.463  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 11:58:26.464  5538  5584 D BluetoothAdapter: STATE_ON
,09-21 11:58:26.465  4528  4541 D BtGatt.GattService: registerClient() - UUID=cfeca99b-2006-4a5b-b48a-aa195e225345
,09-21 11:58:26.467  4528  4590 D BtGatt.GattService: onClientRegistered() - UUID=cfeca99b-2006-4a5b-b48a-aa195e225345, clientIf=5
09-21 11:58:26.468  5538  5549 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 11:58:26.469  4528  4760 D BtGatt.GattService: start scan with filters
,09-21 11:58:26.473  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 11:58:26.473  4528  4593 D BtGatt.ScanManager: handling starting scan
,09-21 11:58:26.473  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:58:26.473  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:58:26.473  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 11:58:26.474  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:26.474  4528  4593 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:26.475  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-21 11:58:26.475  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:26.475  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 11:58:26.476  5538  5584 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 11:58:26.477  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.478  5538  5584 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 11:58:26.478  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.478  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 11:58:26.478  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.478  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:58:26.478  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-21 11:58:26.478  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:58:26.478  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 11:58:26.478  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:58:26.478  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 11:58:26.478  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 11:58:26.479  5538  5584 D BluetoothAdapter: STATE_ON
09-21 11:58:26.479  4528  4541 D BtGatt.GattService: stopScan() - queue size =1
09-21 11:58:26.479  4528  4760 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:58:26.479  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:58:26.479  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 11:58:26.479  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 11:58:26.479  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:58:26.479  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-21 11:58:26.480  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:26.480  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:58:26.480  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 11:58:26.480  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:58:26.481  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:26.482  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.482  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 11:58:26.482  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:26.482  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.482  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.482  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.482  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.482  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.482  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.482  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.482  5538  5584 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-21 11:58:26.482  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:26.482  4528  4590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 11:58:26.482  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.483  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:26.483  4528  4593 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:26.485  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-21 11:58:26.487  4528  4590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-21 11:58:26.487  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.487  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.488  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:58:26.488  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:26.488  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 11:58:26.488  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:58:26.488  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:26.488  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:58:26.488  4528  4593 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:58:26.488  4528  4593 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-21 11:58:26.489  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.491  5538  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 11:58:26.491  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 11:58:26.491  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.496  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-21 11:58:26.496  4528  4590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-21 11:58:26.496  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.497  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:58:26.497  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 11:58:26.500  4528  4590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:58:26.501  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:26.501  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 11:58:26.501  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:58:26.501  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 11:58:26.501  5538  5584 D BluetoothAdapter: STATE_ON
,09-21 11:58:26.503  4528  4740 D BtGatt.GattService: registerClient() - UUID=eb8775b2-77e9-4e7c-bc3e-cf984ab77412
09-21 11:58:26.504  4528  4590 D BtGatt.GattService: onClientRegistered() - UUID=eb8775b2-77e9-4e7c-bc3e-cf984ab77412, clientIf=5
,09-21 11:58:26.504  5538  5549 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 11:58:26.504  4528  4542 D BtGatt.GattService: start scan with filters
,09-21 11:58:26.508  4528  4590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 11:58:26.508  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:26.508  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 11:58:26.508  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:58:26.509  4528  4593 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:58:26.509  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:58:26.509  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 11:58:26.510  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:26.510  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:58:26.510  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:26.510  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 11:58:26.512  5538  5584 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 11:58:26.513  4528  4590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:58:26.513  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.513  5538  5584 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-21 11:58:26.513  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.513  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.513  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 11:58:26.513  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.513  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:58:26.513  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 11:58:26.514  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:58:26.514  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-21 11:58:26.514  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:58:26.514  4528  4593 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 11:58:26.514  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 11:58:26.514  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 11:58:26.514  5538  5584 D BluetoothAdapter: STATE_ON
09-21 11:58:26.514  4528  4740 D BtGatt.GattService: stopScan() - queue size =0
,09-21 11:58:26.516  4528  4542 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:58:26.516  4528  4590 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 11:58:26.516  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:58:26.516  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 11:58:26.516  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.516  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 11:58:26.516  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:58:26.516  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 11:58:26.517  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-21 11:58:26.517  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:58:26.517  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 11:58:26.517  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:58:26.517  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:26.518  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.518  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.518  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-21 11:58:26.518  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.518  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.518  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.518  4528  4593 D BtGatt.ScanManager: handling starting scan
09-21 11:58:26.518  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.518  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.518  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 11:58:26.518  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.518  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:26.518  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.518  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.519  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.519  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.519  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.519  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.519  5538  5584 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-21 11:58:26.520  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:26.523  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:58:26.524  4528  4590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-21 11:58:26.524  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.524  4528  4593 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 11:58:26.525  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-21 11:58:26.525  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:58:26.526  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:26.526  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 11:58:26.526  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:58:26.526  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:26.526  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:58:26.528  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.529  4528  4590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 11:58:26.529  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.529  4528  4593 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:58:26.529  4528  4593 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 11:58:26.529  5538  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-21 11:58:26.529  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 11:58:26.530  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.534  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 11:58:26.534  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:58:26.534  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 11:58:26.538  4528  4590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-21 11:58:26.538  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.538  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 11:58:26.538  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:58:26.538  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 11:58:26.538  5538  5584 D BluetoothAdapter: STATE_ON
,09-21 11:58:26.540  4528  4740 D BtGatt.GattService: registerClient() - UUID=10fdb411-31e9-4be0-9776-55062553bb69
,09-21 11:58:26.540  4528  4590 D BtGatt.GattService: onClientRegistered() - UUID=10fdb411-31e9-4be0-9776-55062553bb69, clientIf=5
,09-21 11:58:26.541  5538  5549 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 11:58:26.541  4528  4541 D BtGatt.GattService: start scan with filters
09-21 11:58:26.542  4528  4590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:58:26.542  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:26.543  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 11:58:26.544  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:58:26.544  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:58:26.544  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 11:58:26.545  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:26.545  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:58:26.545  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:26.546  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 11:58:26.547  5538  5584 I io.jxcore.node.ConnectionHelper: start: OK
,09-21 11:58:26.547  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.547  5538  5584 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 11:58:26.547  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.547  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 11:58:26.547  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.548  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:58:26.548  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 11:58:26.548  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:58:26.548  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 11:58:26.548  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:58:26.548  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 11:58:26.548  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 11:58:26.549  5538  5584 D BluetoothAdapter: STATE_ON
09-21 11:58:26.549  4528  4590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 11:58:26.549  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.549  4528  4541 D BtGatt.GattService: stopScan() - queue size =0
09-21 11:58:26.549  4528  4593 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:58:26.549  4528  4542 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:58:26.550  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:58:26.550  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 11:58:26.550  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-21 11:58:26.550  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:58:26.550  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 11:58:26.553  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:26.553  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:58:26.553  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 11:58:26.553  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:58:26.554  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:26.554  4528  4590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:58:26.554  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.554  4528  4593 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 11:58:26.555  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.555  5538  5584 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 11:58:26.555  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.555  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.555  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.555  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.555  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.555  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.555  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:26.555  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:26.555  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.555  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.555  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.555  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.555  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.556  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.556  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.557  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.557  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.557  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.557  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.558  5538  5584 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-21 11:58:26.558  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.558  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.559  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.559  4528  4590 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 11:58:26.559  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.559  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.559  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.559  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.559  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.559  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.559  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.559  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.559  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.559  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.559  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.559  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.560  4528  4593 D BtGatt.ScanManager: handling starting scan
09-21 11:58:26.562  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.562  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.562  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.562  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.563  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-21 11:58:26.563  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.564  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.564  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.564  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.564  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.564  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.564  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.564  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.564  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.564  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.564  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.564  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.564  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.564  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.565  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.565  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.565  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.565  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.566  5538  5584 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-21 11:58:26.566  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.566  4528  4590 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 11:58:26.566  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.566  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.566  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.566  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.566  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.566  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.566  4528  4593 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 11:58:26.566  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.566  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.566  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.566  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.566  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.566  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.566  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.566  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.571  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.571  4528  4590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 11:58:26.571  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.571  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.571  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.571  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.571  4528  4593 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:58:26.571  4528  4593 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 11:58:26.571  5538  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-21 11:58:26.571  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.572  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.572  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.572  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.572  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.572  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.572  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.572  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.572  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.572  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.572  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.572  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.572  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.572  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.573  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.573  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.574  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.574  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.574  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 11:58:26.574  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 11:58:26.574  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 11:58:26.574  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 11:58:26.574  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-21 11:58:26.574  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-21 11:58:26.574  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.574  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.574  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.574  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.575  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.575  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.575  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.575  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.575  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.575  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.575  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.575  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.575  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.575  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.576  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.576  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.576  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.576  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.576  5538  5584 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 11:58:26.576  5538  5584 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-21 11:58:26.576  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-21 11:58:26.578  5538  5584 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 11:58:26.578  5538  5584 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-21 11:58:26.578  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-21 11:58:26.579  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-21 11:58:26.579  5538  5584 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-21 11:58:26.580  5538  5584 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 11:58:26.580  5538  5584 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-21 11:58:26.580  5538  5584 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 11:58:26.580  5538  5584 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 11:58:26.580  5538  5584 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-21 11:58:26.580  5538  5584 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 11:58:26.580  5538  5584 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-21 11:58:26.580  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-21 11:58:26.581  4528  4590 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 11:58:26.581  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.582  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-21 11:58:26.583  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-21 11:58:26.583  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-21 11:58:26.583  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-21 11:58:26.583  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-21 11:58:26.583  5538  5584 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-21 11:58:26.583  5538  5584 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-21 11:58:26.583  5538  5584 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-21 11:58:26.583  5538  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
09-21 11:58:26.584  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.584  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.584  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.584  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.584  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.584  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.584  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-21 11:58:26.585  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.585  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.585  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.586  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.586  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.586  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.586  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.586  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.586  5538  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
09-21 11:58:26.586  5538  5585 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 11:58:26.586  5538  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 121)
09-21 11:58:26.586  5538  5586 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 121)
09-21 11:58:26.586  4528  4590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:58:26.586  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.587  4542  4542 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28441]" dev="sockfs" ino=28441 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 11:58:26.587  4542  4542 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28441]" dev="sockfs" ino=28441 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-21 11:58:26.588  5538  5585 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
09-21 11:58:26.589  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.589  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.589  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.589  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.589  5538  5584 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-21 11:58:26.590  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.590  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.590  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.590  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.590  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.590  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.590  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.590  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.590  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.590  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.590  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.590  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.590  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.590  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.591  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.591  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.591  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.591  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.592  5538  5584 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-21 11:58:26.592  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.592  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.592  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.592  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.592  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.592  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.592  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.592  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.592  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.592  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.592  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.592  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.592  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.592  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.593  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.593  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.593  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.593  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.593  5538  5584 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-21 11:58:26.593  5538  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-21 11:58:26.593  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 11:58:26.594  5538  5584 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-21 11:58:26.594  5538  5584 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-21 11:58:26.594  5538  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-21 11:58:26.594  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 11:58:26.594  5538  5584 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-21 11:58:26.594  5538  5584 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-21 11:58:26.594  5538  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-21 11:58:26.594  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 11:58:26.594  5538  5584 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-21 11:58:26.594  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.594  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.594  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.594  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.594  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.594  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.594  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.594  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.594  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.594  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.595  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.595  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.595  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.595  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.595  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.595  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.595  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.595  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.596  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.596  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.596  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.596  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.596  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.596  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.596  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.596  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.596  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.596  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.596  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.596  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.596  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.596  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.596  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.596  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.596  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.596  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.596  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.597  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.597  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.597  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.597  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.597  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.597  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.597  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.597  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.597  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.597  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.598  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.598  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.598  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.598  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.598  4528  4590 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 11:58:26.598  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.598  5538  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-21 11:58:26.598  4528  4593 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:58:26.599  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:26.599  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-21 11:58:26.599  5538  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-21 11:58:26.599  5538  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-21 11:58:26.600  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-21 11:58:26.600  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 11:58:26.600  5538  5538 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-21 11:58:26.600  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.600  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-21 11:58:26.600  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-21 11:58:26.600  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-21 11:58:26.600  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.600  5538  5584 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-21 11:58:26.600  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.600  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.600  5538  5538 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-21 11:58:26.600  5538  5587 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-21 11:58:26.600  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:58:26.600  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 11:58:26.600  5538  5587 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-21 11:58:26.600  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:58:26.600  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.600  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.601  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:26.601  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.601  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.601  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.601  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.601  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:26.601  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.601  5538  5538 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-21 11:58:26.601  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.601  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:26.601  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.602  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.602  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.602  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.602  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.602  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.602  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.602  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.602  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.602  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.602  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.602  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.603  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.603  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.603  4528  4590 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:58:26.603  4528  4590 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:26.603  4528  4593 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 11:58:26.603  5538  5584 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-21 11:58:26.603  5538  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-21 11:58:26.603  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-21 11:58:26.603  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-21 11:58:26.603  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.604  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.604  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.604  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.604  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.604  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.604  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.604  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.604  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.604  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.604  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.604  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.604  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.604  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.605  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.605  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.605  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.605  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.607  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.607  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.607  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.607  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.607  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.607  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.607  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.607  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.607  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.607  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.607  4528  4590 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 11:58:26.607  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.607  4528  4590 D BtGatt.ScanMan,ager: callback done for clientIf - 5 status - 0
09-21 11:58:26.607  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.607  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.608  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.608  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.608  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.608  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.608  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.609  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:26.609  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:26.609  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:26.609  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:26.609  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.609  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.609  5538  5584 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@907b2f6 not in the list
09-21 11:58:26.609  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.609  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.609  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:26.609  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.609  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.609  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:26.609  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:26.610  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:26.610  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:26.610  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:26.610  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11256f7 not in the list
09-21 11:58:26.611  5538  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-21 11:58:26.611  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 11:58:26.611  5538  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-21 11:58:26.611  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-21 11:58:26.611  5538  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-21 11:58:26.611  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-21 11:58:26.612  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-21 11:58:26.612  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-21 11:58:26.612  5538  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-21 11:58:26.612  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-21 11:58:26.612  5538  5584 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-21 11:58:26.612  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-21 11:58:26.612  5538  5584 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-21 11:58:26.612  5538  5584 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-21 11:58:26.613  5538  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-21 11:58:26.613  5538  5584 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-21 11:58:26.613  5538  5584 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-21 11:58:26.613  5538  5584 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-21 11:58:26.613  5538  5584 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-21 11:58:26.613  5538  5584 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-21 11:58:26.614  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:26.614  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@30b0301 added. We now have 2 listener(s)
09-21 11:58:26.614  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:26.615  5538  5584 D BluetoothAdapter: enable(): BT is already enabled..!
09-21 11:58:26.615   929   939 D WifiService: setWifiEnabled: true pid=5538, uid=10077
09-21 11:58:26.615   929   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-21 11:58:26.616  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:26.616  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a60c5a6 added. We now have 3 listener(s)
09-21 11:58:26.616  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:26.619  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:26.619  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bd0ebe7 added. We now have 4 listener(s)
09-21 11:58:26.619  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:26.620  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:26.620  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b7f0394 added. We now have 5 listener(s)
09-21 11:58:26.620  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:26.621   929   940 D WifiService: setWifiEnabled: false pid=5538, uid=10077
09-21 11:58:26.621   929   940 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 11:58:26.622   929  3052 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-21 11:58:26.623   929  3052 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-21 11:58:26.623   929  3052 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-21 11:58:26.623   929  3052 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-21 11:58:26.624  4528  4582 D BluetoothAdapterState: Current state: ON, message: 23
09-21 11:58:26.624  4528  4582 D BluetoothAdapterProperties: Setting state to 13
09-21 11:58:26.624  4528  4582 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-21 11:58:26.625  4528  4582 D BluetoothAdapterProperties: onBluetoothDisable()
09-21 11:58:26.625  4528  4582 I BluetoothAdapterState: Entering PendingCommandState
09-21 11:58:26.626  4528  4590 D BluetoothAdapterProperties: Scan Mode:20
09-21 11:58:26.627  4528  4582 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-21 11:58:26.627  4528  4528 D BluetoothMapService: onReceive
09-21 11:58:26.627  4528  4528 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 11:58:26.627  4528  4528 D BluetoothMapService: STATE_TURNING_OFF
09-21 11:58:26.628  4528  4528 D BluetoothMapService: MAP Service closeService in
09-21 11:58:26.628  4528  4528 D BluetoothMapMasInstance0: MAP Service shutdown
09-21 11:58:26.628  4528  4528 D ObexServerSockets0: shutdown(block = true)
09-21 11:58:26.628  4528  4528 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 11:58:26.628  4528  4528 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 11:58:26.629  4528  4763 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-21 11:58:26.629  4528  4738 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-21 11:58:26.629  4528  4762 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-21 11:58:26.631  4528  4528 I BtOppRfcommListener: stopping Accept Thread
09-21 11:58:26.632   929  5282 D DhcpClient: Clearing IP address
09-21 11:58:26.632   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-21 11:58:26.632  4528  5234 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-21 11:58:26.633  4528  5234 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-21 11:58:26.635  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:26.635  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:58:26.636  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.636  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.638   929   942 I ActivityManager: Start proc 5590:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-21 11:58:26.638   507   922 D CommandListener: Setting iface cfg
09-21 11:58:26.639  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.641  4528  4528 D HeadsetService: Received stop request...Stopping profile...
09-21 11:58:26.641   929  5283 D DhcpClient: Receive thread stopped
09-21 11:58:26.641  3725  5336 V NativeCrypto: Read error: ssl=0x7f9eb0bc00: I/O error during system call, Connection timed out
09-21 11:58:26.642  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:26.643  3725  5336 V NativeCrypto: SSL shutdown failed: ssl=0x7f9eb0bc00: I/O error during system call, Broken pipe
09-21 11:58:26.643   929   929 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:26.644   929   929 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:26.644  3203  3851 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:26.645  3203  3203 D HeadsetProfile: Bluetooth service disconnected
09-21 11:58:26.645   929   929 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:26.645  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-21 11:58:26.645  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-21 11:58:26.645  4528  4528 D A2dpService: Received stop request...Stopping profile...
09-21 11:58:26.645  3636  3880 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:26.645   929  3224 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-21 11:58:26.645  4528  4743 D A2dpStateMachine: Exit Disconnected: -1
09-21 11:58:26.646   929  5280 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-21 11:58:26.646  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.646  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-21 11:58:26.646  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:58:26.646   929   929 D BluetoothA2dp: Proxy object disconnected
09-21 11:58:26.647  3203  3203 D BluetoothA2dp: Proxy object disconnected
09-21 11:58:26.647  4528  4528 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:26.647  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:26.647  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:26.648  4528  4528 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:26.648  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.649   929  5280 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-21 11:58:26.649  4528  4528 D HidService: Received stop request...Stopping profile...
09-21 11:58:26.649  4528  4528 D HidService: Stopping Bluetooth HidService
09-21 11:58:26.649  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.649   929  3054 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-21 11:58:26.650   929  3054 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
09-21 11:58:26.651   929  3054 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
09-21 11:58:26.652   929  3054 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-21 11:58:26.652   929  3054 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-21 11:58:26.652  3203  3203 D BluetoothInputDevice: Proxy object disconnected
09-21 11:58:26.652  3203  3203 D HidProfile: Bluetooth service disconnected
09-21 11:58:26.655   929   929 D RttService: SCAN_AVAILABLE : 1
09-21 11:58:26.656   533   533 E Parcel  : Reading a NULL string not supported here.
09-21 11:58:26.658   929  3054 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-21 11:58:26.659  3590  3791 W QCNEJ   : |CORE| network lost: 100
09-21 11:58:26.659  4528  4528 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-21 11:58:26.660  4528  4528 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-21 11:58:26.660   929  3158 D RttService: EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-21 11:58:26.660  4528  4590 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-21 11:58:26.660  4528  4733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:26.660  4528  4733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:26.660  4528  4528 D HealthService: Received stop request...Stopping profile...
09-21 11:58:26.660  4528  4733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:26.661  4528  4528 D PanService: Received stop request...Stopping profile...
09-21 11:58:26.661  3590  3791 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-21 11:58:26.661  4528  4590 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-21 11:58:26.662  4528  4528 D BluetoothMapService: Received stop request...Stopping profile...
09-21 11:58:26.662  4528  4528 D BluetoothMapService: stop()
09-21 11:58:26.663  4528  4528 D BluetoothMapAppObserver: deinitObservers()
09-21 11:58:26.663  4528  4528 D BluetoothMapAppObserver: removeReceiver()
09-21 11:58:26.664  4528  4528 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:26.665  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:26.665  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:26.665  4528  4528 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 11:58:26.666  4528  4733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-21 11:58:26.666  4528  4733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-21 11:58:26.666  4528  4590 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-21 11:58:26.666  4528  4528 D SapService: Received stop request...Stopping profile...
09-21 11:58:26.666  4528  4733 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 11:58:26.666  4528  4528 V SapService: stop()
09-21 11:58:26.666  4528  4733 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 11:58:26.666  4528  4733 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 11:58:26.666  4528  4733 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:26.674  4528  4528 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-21 11:58:26.674  4528  4528 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isTurningOff()=true
,09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:26.674  4528  4528 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:26.675  4528  4528 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-21 11:58:26.675  3203  3203 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 11:58:26.675  3203  3203 D PanProfile: Bluetooth service disconnected
09-21 11:58:26.675  4528  4528 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-21 11:58:26.675  3203  3203 D BluetoothMap: Proxy object disconnected
09-21 11:58:26.675  3203  3203 D MapProfile: Bluetooth service disconnected
09-21 11:58:26.675  4528  4590 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-21 11:58:26.675  4528  4590 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-21 11:58:26.676  4528  4528 V BluetoothAdapterState: isTurningOff()=true
,09-21 11:58:26.676  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:26.676  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:26.676  4528  4528 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:26.676  4528  4528 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-21 11:58:26.676  4528  4528 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-21 11:58:26.678  4528  4528 D BluetoothMapService: MAP Service closeService in
09-21 11:58:26.678  4528  4528 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:26.678  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:26.678  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:26.678  4528  4528 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:26.678  4528  4528 D BluetoothMapService: cleanup()
09-21 11:58:26.678  4528  4528 D BluetoothMapService: MAP Service closeService in
09-21 11:58:26.679  4528  4528 V BluetoothAdapterState: isTurningOff()=true
,09-21 11:58:26.679  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:26.679  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:26.679  4528  4528 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:26.679  4528  4582 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-21 11:58:26.679  4528  4582 D BluetoothAdapterProperties: Setting state to 15
09-21 11:58:26.679  4528  4582 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-21 11:58:26.680  4528  4582 I BluetoothAdapterState: Entering BleOnState
09-21 11:58:26.680  3636  3658 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:26.680  3203  3218 D BluetoothMap: onBluetoothStateChange: up=false
09-21 11:58:26.681   929  3052 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-21 11:58:26.681  3203  3216 D BluetoothPbap: onBluetoothStateChange: up=false
,09-21 11:58:26.685  3203  3851 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 11:58:26.685  3203  3216 D BluetoothPan: onBluetoothStateChange on: false
09-21 11:58:26.686  3203  3218 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 11:58:26.687   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:26.687  3203  3851 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:26.687   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:26.687   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-21 11:58:26.687   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-21 11:58:26.688  4528  4582 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-21 11:58:26.688  4528  4582 D BluetoothAdapterProperties: Setting state to 16
09-21 11:58:26.688  4528  4582 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-21 11:58:26.688  4528  4582 D BluetoothAdapterProperties: onBleDisable
09-21 11:58:26.689  4528  4582 I BluetoothAdapterState: Entering PendingCommandState
09-21 11:58:26.689  4528  4585 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-21 11:58:26.690  4528  4590 D BluetoothAdapterProperties: Scan Mode:20
09-21 11:58:26.691  4528  4733 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-21 11:58:26.691  4528  4733 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-21 11:58:26.692  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:26.692  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:26.693  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.693  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:26.694   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-21 11:58:26.698   929  3052 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-21 11:58:26.698  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:26.698  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:26.699  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.700  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:26.702  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.702  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.712  5590  5590 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-21 11:58:26.724   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-21 11:58:26.724   507   922 D CommandListener: Clearing all IP addresses on wlan0
09-21 11:58:26.724   507   922 D TetherController: Setting IP forward enable = 0
,09-21 11:58:26.725   929  3054 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-21 11:58:26.726   929  3054 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-21 11:58:26.727   929  3052 D DhcpClient: doQuit
09-21 11:58:26.727  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 11:58:26.727   929  3052 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 11:58:26.727   929  5282 D DhcpClient: onQuitting
,09-21 11:58:26.729  3726  3726 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-21 11:58:26.730   929   946 D Tethering: MasterInitialState.processMessage what=3
09-21 11:58:26.734  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:26.734  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:26.734  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.734  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:26.736  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 11:58:26.736  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:26.737  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:26.737  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 11:58:26.737  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:26.739  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.741  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.744  5169  5169 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@99c9fc9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-21 11:58:26.749   929   940 I ActivityManager: Start proc 5614:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-21 11:58:26.749  4966  4979 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-21 11:58:26.749  4966  4979 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-21 11:58:26.749  4966  4979 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-21 11:58:26.749  4966  4979 E SarControlService: no key has been found,reset the power
09-21 11:58:26.750  4966  5004 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-21 11:58:26.750  4966  5004 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-21 11:58:26.750  4966  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-21 11:58:26.750  4992  4992 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-21 11:58:26.751  4992  4992 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-21 11:58:26.752  4966  5004 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-21 11:58:26.752  4966  5004 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-21 11:58:26.752  4966  5004 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-21 11:58:26.754  4992  4992 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-21 11:58:26.754  4992  4992 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-21 11:58:26.755  3726  3726 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-21 11:58:26.758  4992  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@14af737 HexData = [00000000ea03000000000000ffffffff]
09-21 11:58:26.758  4992  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-21 11:58:26.758  4992  5006 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-21 11:58:26.760  4992  4992 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-21 11:58:26.760  4966  4976 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-21 11:58:26.761  4992  5006 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@14af737 HexData = [00000000eb03000000000000ffffffff]
09-21 11:58:26.761  4992  5006 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-21 11:58:26.761  4992  5006 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-21 11:58:26.762  4992  4992 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-21 11:58:26.762  4966  4977 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-21 11:58:26.762  3726  3726 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-21 11:58:26.769   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d421138:true
,09-21 11:58:26.787   507   922 E Netd    : netlink response contains error (No such file or directory)
,09-21 11:58:26.788   507   922 D TetherController: Setting IP forward enable = 0
09-21 11:58:26.789   929  3054 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-21 11:58:26.792  5590  5590 D LocalBluetoothProfileManager: Adding local MAP profile
09-21 11:58:26.793  5590  5590 D BluetoothMap: Create BluetoothMap proxy object
,09-21 11:58:26.802  3726  3726 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-21 11:58:26.809  5590  5590 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-21 11:58:26.815  5614  5614 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-21 11:58:26.822  3726  3726 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-21 11:58:26.828  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,09-21 11:58:26.831  4373  4373 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 11:58:26.831   929  3052 D wifi    : In wifi stop Hal
,09-21 11:58:26.831   929  3052 D wifi    : halHandle = 0x7f885a34e0, mVM = 0x7fa4bcd140, mCls = 0x100af6
09-21 11:58:26.831   929  3723 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-21 11:58:26.831   929  3723 D WifiHAL : Got a signal to exit!!!
09-21 11:58:26.831   929  3723 I WifiHAL : Exit wifi_event_loop
09-21 11:58:26.831   929  3052 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-21 11:58:26.832   929  3052 E WifiHAL : Event processing terminated
,09-21 11:58:26.832   929  3052 D wifi    : In wifi cleaned up handler
,09-21 11:58:26.832   929  3052 I WifiHAL : Internal cleanup completed
09-21 11:58:26.834  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:26.834  3565  4119 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 11:58:26.835  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:26.843   929  3665 I ActivityManager: Killing 4930:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-21 11:58:26.854   929  3723 D wifi    : set interface wlan0 flags (DOWN)
,09-21 11:58:26.855   929  3052 D WifiNative-HAL: HAL event thread stopped successfully
,09-21 11:58:26.897  4528  4590 I bt_hci  : shut_down
,09-21 11:58:26.901  4528  4594 D bt_hwcfg: hw_epilog_process
,09-21 11:58:26.901  4528  4594 I bt_vendor: low_power_mode_cb
,09-21 11:58:26.903  4528  4594 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-21 11:58:26.903  4528  4594 I bt_vendor: epilog_cb
09-21 11:58:26.903  4528  4594 I bt_hci  : epilog_finished_callback
,09-21 11:58:26.905  4528  4590 I bt_hci_h4: hal_close
,09-21 11:58:26.906  4528  4590 I bt_userial_vendor: device fd = 54 close
,09-21 11:58:27.015  5614  5614 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.015  5614  5614 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.015  5614  5614 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(Act,ivityThread.java:5422)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.015  5614  5614 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:170)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.015  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.016  5614  5614 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.r.k.d(PG:583)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:170)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.016  5614  5614 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.016  5614  5614 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.016  5614  5614 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:27.016  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:27.016  4528  4585 D bt_stack_manager: event_shut_down_stack finished.
09-21 11:58:27.017  4528  4582 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-21 11:58:27.018  4528  4582 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-21 11:58:27.019  4528  4528 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 11:58:27.020  4528  4528 D BtGatt.GattService: Received stop request...Stopping profile...
09-21 11:58:27.020  4528  4528 D BtGatt.GattService: stop()
09-21 11:58:27.020  4528  4528 D BtGatt.AdvertiseManager: advertise clients cleared
09-21 11:58:27.022  4528  4528 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:27.022  4528  4528 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:27.022  4528  4528 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:27.022  4528  4528 V BluetoothAdapterState: isBleTurningOff()=true
09-21 11:58:27.022  4528  4582 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-21 11:58:27.022  4528  4582 D BluetoothAdapterProperties: Setting state to 10
09-21 11:58:27.022  4528  4582 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-21 11:58:27.023  4528  4582 I BluetoothAdapterState: Entering OffState
09-21 11:58:27.023   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-21 11:58:27.035  4528  4528 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-21 11:58:27.035  4528  4528 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-21 11:58:27.036  4528  4585 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-21 11:58:27.037  4528  4528 I BluetoothServiceJni: cleanupNative: return from cleanup
09-21 11:58:27.046  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 11:58:27.050  4528  4585 D bt_stack_manager: event_clean_up_stack finished.
09-21 11:58:27.058   929   946 D Tethering: InitialState.processMessage what=4
09-21 11:58:27.061   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-21 11:58:27.061  4528  4528 I art     : System.exit called, status: 0
09-21 11:58:27.061  4528  4528 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-21 11:58:27.078  5590  5590 D DockEventReceiver: finishStartingService: stopping service
09-21 11:58:27.079   929  3651 I ActivityManager: Killing 5310:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-21 11:58:27.103  5538  5538 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 11:58:27.105   929  3661 I ActivityManager: Process com.android.bluetooth (pid 4528) has died
,09-21 11:58:27.107  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 11:58:27.118   929  3482 I ActivityManager: Start proc 5654:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,09-21 11:58:27.183  5654  5654 D AdapterServiceConfig: Adding HeadsetService
,09-21 11:58:27.184  5654  5654 D AdapterServiceConfig: Adding A2dpService
09-21 11:58:27.184  5654  5654 D AdapterServiceConfig: Adding HidService
,09-21 11:58:27.184  5654  5654 D AdapterServiceConfig: Adding HealthService
09-21 11:58:27.184  5654  5654 D AdapterServiceConfig: Adding PanService
09-21 11:58:27.184  5654  5654 D AdapterServiceConfig: Adding GattService
,09-21 11:58:27.184  5654  5654 D AdapterServiceConfig: Adding BluetoothMapService
09-21 11:58:27.185  5654  5654 D AdapterServiceConfig: Adding SapService
09-21 11:58:27.188   929  3279 I ActivityManager: Killing 5322:com.android.chrome/u0a39 (adj 15): empty #17
,09-21 11:58:27.240  3966  3966 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-21 11:58:27.243  3966  3966 D SystemUpdateService: onCreate
,09-21 11:58:27.250  3966  3966 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-21 11:58:27.260  3966  3966 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-21 11:58:27.265  3966  5306 I iu.UploadsManager: num queued entries: 0
09-21 11:58:27.265  3966  5306 I iu.UploadsManager: num updated entries: 0
09-21 11:58:27.266  3966  5306 I iu.SyncManager: NEXT; no task
,09-21 11:58:27.267  3966  3966 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-21 11:58:27.269  3966  3966 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-21 11:58:27.277  3966  5666 I SystemUpdateService: active receiver: enabled
,09-21 11:58:27.282  3966  5666 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-21 11:58:27.283   929   940 I ActivityManager: Start proc 5668:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-21 11:58:27.294  3966  5666 I SystemUpdateService: network: null; metered: false; mobile allowed: false
,09-21 11:58:27.296  3966  5666 I SystemUpdateService: now status is 0 (complete)
,09-21 11:58:27.296  3966  5666 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-21 11:58:27.296  3966  5666 I SystemUpdateService: file has been verified
09-21 11:58:27.296  3966  5666 I SystemUpdateService: OTA package size = 21989297
,09-21 11:58:27.321  5668  5668 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-21 11:58:27.323  3966  5666 I SystemUpdateService: showing system update notification
,09-21 11:58:27.325  5668  5668 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-21 11:58:27.331  5668  5668 D SprintDMHelper: simOperator: 
,09-21 11:58:27.331  5668  5668 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-21 11:58:27.343   929  3721 I ActivityManager: Start proc 5680:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-21 11:58:27.359  3966  3966 D SystemUpdateService: onDestroy
,09-21 11:58:27.364   929  3482 I ActivityManager: Killing 5340:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-21 11:58:27.433  4373  5694 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-21 11:58:27.442   929   939 I ActivityManager: Start proc 5695:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-21 11:58:27.444   929  3279 I ActivityManager: Killing 5169:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-21 11:58:27.449   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 11:58:27.471  5614  5645 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-21 11:58:27.481   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@735650a:true
,09-21 11:58:27.519  5695  5695 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-21 11:58:27.693   929  3651 I ActivityManager: Killing 4600:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-21 11:58:27.731   929  3721 I ActivityManager: Start proc 5709:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-21 11:58:27.759  5709  5709 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-21 11:58:27.767   929  3526 I ActivityManager: Killing 5397:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-21 11:58:28.451   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,09-21 11:58:29.452   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-21 11:58:29.648   929  3279 D WifiService: setWifiEnabled: true pid=5538, uid=10077
,09-21 11:58:29.648   929  3279 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 11:58:29.656   507   922 D SoftapController: Softap fwReload - Ok
,09-21 11:58:29.660   507   922 D CommandListener: Setting iface cfg
09-21 11:58:29.660   507   922 D CommandListener: Trying to bring down wlan0
,09-21 11:58:29.662   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-21 11:58:29.668   929  3052 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 11:58:30.282   929  3052 D wifi    : set interface wlan0 flags (UP)
,09-21 11:58:30.286   929  3052 I WifiHAL : Initializing wifi
09-21 11:58:30.286   929  3052 I WifiHAL : Creating socket
09-21 11:58:30.290   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-21 11:58:30.295   929  3052 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-21 11:58:30.295   929  3052 D wifi    : Did set static halHandle = 0x7f885a34e0
09-21 11:58:30.296   929  3052 D wifi    : halHandle = 0x7f885a34e0, mVM = 0x7fa4bcd140, mCls = 0x2017b2
09-21 11:58:30.296   929  3052 D wifi    : array field set
,09-21 11:58:30.296   929  3052 I WifiNative-HAL: interface[0] = wlan0
,09-21 11:58:30.298   929  5729 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547748459744
09-21 11:58:30.298   929  5729 D wifi    : waitForHalEvents called, vm = 0x7fa4bcd140, obj = 0x2017b2, env = 0x7f88e67900
,09-21 11:58:30.390  5730  5730 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-21 11:58:30.403  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:30.405   929  3052 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-21 11:58:30.405  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:30.413  5730  5730 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 11:58:30.421  5730  5730 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 11:58:30.421  5730  5730 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-21 11:58:30.440   929  3052 D WifiConfigStore: Loading config and enabling all networks 
,09-21 11:58:30.445  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:30.445  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:30.445  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:30.445  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:30.446  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:30.446  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:30.447  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:30.447  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:30.456   929  3052 D WifiConfigStore: loaded 0 passpoint configs
,09-21 11:58:30.457   929  3052 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-21 11:58:30.457   929  3052 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-21 11:58:30.458   929  3052 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-21 11:58:30.459   929  3052 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-21 11:58:30.460   929  3052 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-21 11:58:30.460   929  3052 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-21 11:58:30.460   929  3052 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-21 11:58:30.464   929  3052 D WifiNative-HAL: Setting external_sim to 1
,09-21 11:58:30.464  4373  4373 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 11:58:30.464   929  3052 D wifi    : setting dfs flag to true, 0x7f8b286ae0
09-21 11:58:30.465   929  3052 D WifiStateMachine: Setting OUI to DA-A1-19
09-21 11:58:30.465   929  3052 D wifi    : setting scan oui 0x7f8b286ae0
09-21 11:58:30.465   929  3052 D WifiHAL : Sending mac address OUI
,09-21 11:58:30.469   929  3052 E native  : do suspend false
,09-21 11:58:30.476   929  3052 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-21 11:58:30.476   929   929 D RttService: SCAN_AVAILABLE : 3
,09-21 11:58:30.476   929  3158 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-21 11:58:30.476   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-21 11:58:30.477   507   922 D CommandListener: Setting iface cfg
,09-21 11:58:30.481   929  3051 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-21 11:58:30.481   929  3051 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-21 11:58:30.489   929  3051 D WifiNative-HAL: p2pGetDeviceAddress
,09-21 11:58:30.494   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=195280 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-21 11:58:30.494   929  3051 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-21 11:58:32.656   929  3526 D WifiService: setWifiEnabled: false pid=5538, uid=10077
09-21 11:58:32.657   929  3526 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 11:58:32.663   929   929 D RttService: SCAN_AVAILABLE : 1
,09-21 11:58:32.664   929  3158 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-21 11:58:32.677   929  3052 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-21 11:58:32.678   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-21 11:58:32.685   929  3052 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-21 11:58:32.687  5730  5730 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-21 11:58:32.694  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:32.694  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:32.694  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:32.694  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:32.696  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:32.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:32.696  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 11:58:32.696  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:32.703  5730  5730 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-21 11:58:32.708  5730  5730 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-21 11:58:32.711  5730  5730 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-21 11:58:32.813   929  3052 D wifi    : In wifi stop Hal
,09-21 11:58:32.813   929  3052 D wifi    : halHandle = 0x7f885a34e0, mVM = 0x7fa4bcd140, mCls = 0x2017b2
09-21 11:58:32.813   929  5729 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-21 11:58:32.813   929  5729 D WifiHAL : Got a signal to exit!!!
09-21 11:58:32.813   929  5729 I WifiHAL : Exit wifi_event_loop
09-21 11:58:32.815   929  3052 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-21 11:58:32.815   929  3052 E WifiHAL : Event processing terminated
09-21 11:58:32.815   929  3052 D wifi    : In wifi cleaned up handler
09-21 11:58:32.815   929  3052 I WifiHAL : Internal cleanup completed
09-21 11:58:32.819  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:32.820  4373  4373 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 11:58:32.820  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:32.821  3565  4119 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-21 11:58:32.851   929  5729 D wifi    : set interface wlan0 flags (DOWN)
09-21 11:58:32.852   929  3052 D WifiNative-HAL: HAL event thread stopped successfully
,09-21 11:58:33.054   929   946 D Tethering: InitialState.processMessage what=4
09-21 11:58:33.056   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-21 11:58:35.697   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4d6a747:true
,09-21 11:58:35.698  5654  5654 D BluetoothAdapterState: make() - Creating AdapterState
,09-21 11:58:35.704  5654  5654 I bt_bluedroid: init
,09-21 11:58:35.705  5654  5735 I BluetoothAdapterState: Entering OffState
,09-21 11:58:35.709  5654  5736 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-21 11:58:35.709  5654  5736 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-21 11:58:35.709  5654  5736 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-21 11:58:35.709  5654  5736 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-21 11:58:35.711  5654  5654 I bt_bluedroid: get_profile_interface socket
,09-21 11:58:35.714  5654  5654 I bt_bluedroid: get_profile_interface sdp
09-21 11:58:35.714  5654  5739 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-21 11:58:35.718  5654  5739 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 11:58:35.726  5654  5664 I bt_bluedroid: config_hci_snoop_log
,09-21 11:58:35.728   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-21 11:58:35.738  5654  5735 D BluetoothAdapterState: Current state: OFF, message: 0
,09-21 11:58:35.738  5654  5735 D BluetoothAdapterProperties: Setting state to 14
,09-21 11:58:35.738  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-21 11:58:35.742  5654  5735 D BluetoothBondStateMachine: make
,09-21 11:58:35.745  5654  5740 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-21 11:58:35.750  5654  5735 I BluetoothAdapterState: Entering PendingCommandState
,09-21 11:58:35.752  5654  5654 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-21 11:58:35.756  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:35.757  5654  5654 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-21 11:58:35.758  5654  5654 D BtGatt.GattService: Received start request. Starting profile...
,09-21 11:58:35.758  5654  5654 D BtGatt.GattService: start()
09-21 11:58:35.758  5654  5654 I bt_bluedroid: get_profile_interface gatt
,09-21 11:58:35.761  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:35.761  5654  5654 D BtGatt.AdvertiseManager: advertise manager created
,09-21 11:58:35.770  5654  5654 V BluetoothAdapterState: isTurningOff()=false
,09-21 11:58:35.770  5654  5654 V BluetoothAdapterState: isTurningOn()=false
,09-21 11:58:35.770  5654  5654 V BluetoothAdapterState: isBleTurningOn()=true
09-21 11:58:35.770  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:35.771  5654  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-21 11:58:35.772  5654  5735 I bt_bluedroid: bt_bluedroid
09-21 11:58:35.772  5654  5736 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-21 11:58:35.773  5654  5736 I bt_hci  : start_up
,09-21 11:58:35.781  5654  5736 I bt_vendor: alloc value 0xf3fec871
,09-21 11:58:35.781  5654  5736 I bt_vendor: init
09-21 11:58:35.781  5654  5736 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-21 11:58:35.781  5654  5736 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-21 11:58:35.894  5654  5736 D bt_hci  : start_up starting async portion
,09-21 11:58:35.894  5654  5743 I bt_hci  : event_finish_startup
,09-21 11:58:35.894  5654  5743 I bt_hci_h4: hal_open
,09-21 11:58:35.893  5744  5744 W irq/448-msm_hs_: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-21 11:58:35.895  5654  5743 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-21 11:58:35.898  5654  5743 I bt_userial_vendor: device fd = 54 open
,09-21 11:58:35.911  5654  5743 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 11:58:35.914  5654  5743 D bt_hwcfg: Chipset BCM4358A3
,09-21 11:58:35.914  5654  5743 D bt_hwcfg: Target name = [BCM4358A3]
09-21 11:58:35.915  5654  5743 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-21 11:58:36.317  5654  5743 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-21 11:58:36.317  5654  5743 D bt_hwcfg: Settlement delay -- 100 ms
09-21 11:58:36.318  5654  5743 I bt_hwcfg: Setting fw settlement delay to 100 
,09-21 11:58:36.451  5654  5743 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 11:58:36.452  5654  5743 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-21 11:58:36.453  5654  5743 I bt_hwcfg: vendor lib fwcfg completed
,09-21 11:58:36.453  5654  5743 I bt_vendor: firmware callback
,09-21 11:58:36.453  5654  5743 I bt_hci  : firmware_config_callback
,09-21 11:58:36.464  5654  5746 I bt_btu  : btu_task pending for preload complete event
09-21 11:58:36.464  5654  5746 I bt_btu_task: Bluetooth chip preload is complete
,09-21 11:58:36.465  5654  5746 I bt_btu  : btu_task received preload complete event
,09-21 11:58:36.471  5654  5746 I         : BTE_InitTraceLevels -- TRC_HCI
,09-21 11:58:36.471  5654  5746 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-21 11:58:36.471  5654  5746 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-21 11:58:36.471  5654  5746 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-21 11:58:36.471  5654  5746 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-21 11:58:36.471  5654  5746 I         : BTE_InitTraceLevels -- TRC_A2D
,09-21 11:58:36.471  5654  5746 I         : BTE_InitTraceLevels -- TRC_BNEP
09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_BTM
09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_GAP
09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_PAN
09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_SDP
,09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_GATT
09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_SMP
09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-21 11:58:36.472  5654  5746 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-21 11:58:36.556  5654  5746 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f6a549
,09-21 11:58:36.557  5654  5746 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f6a549 
,09-21 11:58:36.572  5654  5739 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-21 11:58:36.573  5654  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-21 11:58:36.574  5654  5739 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-21 11:58:36.576  5654  5739 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 11:58:36.579  5654  5739 D BluetoothAdapterProperties: Scan Mode:20
,09-21 11:58:36.579  5654  5739 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-21 11:58:36.580  5654  5739 D bt_hci  : do_postload posting postload work item
,09-21 11:58:36.580  5654  5743 I bt_hci  : event_postload
09-21 11:58:36.580  5654  5743 I bt_vendor: sco_config_cb
,09-21 11:58:36.580  5654  5743 I bt_hci  : sco_config_callback postload finished.
,09-21 11:58:36.584  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:36.589  5654  5739 D bt_bte_conf: Device ID record 1 : primary
09-21 11:58:36.589  5654  5739 D bt_bte_conf:   vendorId            = 000f
09-21 11:58:36.589  5654  5739 D bt_bte_conf:   vendorIdSource      = 0001
,09-21 11:58:36.589  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:36.589  5654  5739 D bt_bte_conf:   product             = 1200
09-21 11:58:36.589  5654  5739 D bt_bte_conf:   version             = 1436
09-21 11:58:36.589  5654  5739 D bt_bte_conf:   clientExecutableURL = 
09-21 11:58:36.589  5654  5739 D bt_bte_conf:   serviceDescription  = 
09-21 11:58:36.589  5654  5739 D bt_bte_conf:   documentationURL    = 
09-21 11:58:36.590  5654  5739 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-21 11:58:36.590  5654  5736 D bt_stack_manager: event_start_up_stack finished
09-21 11:58:36.591  5654  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-21 11:58:36.592  5654  5735 D BluetoothAdapterProperties: Setting state to 15
09-21 11:58:36.592  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-21 11:58:36.592  5654  5743 I bt_vendor: low_power_mode_cb
09-21 11:58:36.593  5654  5735 I BluetoothAdapterState: Entering BleOnState
,09-21 11:58:36.598  5654  5735 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-21 11:58:36.598  5654  5735 D BluetoothAdapterProperties: Setting state to 11
,09-21 11:58:36.598  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-21 11:58:36.603  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:36.604  5654  5654 D HeadsetService: Received start request. Starting profile...
09-21 11:58:36.607  5654  5654 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-21 11:58:36.607  5654  5654 D HeadsetStateMachine: make
,09-21 11:58:36.611  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:36.612  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:36.619  5654  5735 I BluetoothAdapterState: Entering PendingCommandState
,09-21 11:58:36.622  5654  5654 D HeadsetStateMachine: max_hf_connections = 1
,09-21 11:58:36.622  5654  5654 I bt_bluedroid: get_profile_interface handsfree
09-21 11:58:36.623  5654  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-21 11:58:36.623  5654  5739 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-21 11:58:36.626  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:36.627  5654  5654 D A2dpService: Received start request. Starting profile...
09-21 11:58:36.627  5654  5654 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-21 11:58:36.628  5654  5654 I bt_bluedroid: get_profile_interface avrcp
,09-21 11:58:36.634  5654  5654 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-21 11:58:36.634  5654  5654 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-21 11:58:36.634  5654  5654 D A2dpStateMachine: make
09-21 11:58:36.635  5654  5654 I bt_bluedroid: get_profile_interface a2dp
09-21 11:58:36.636  5654  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-21 11:58:36.638  5654  5654 I BluetoothHidServiceJni: classInitNative: succeeds
09-21 11:58:36.638  5654  5754 D A2dpStateMachine: Enter Disconnected: -2
09-21 11:58:36.639  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:36.641  5654  5654 D HidService: Received start request. Starting profile...
,09-21 11:58:36.641  5654  5654 I bt_bluedroid: get_profile_interface hidhost
09-21 11:58:36.641  5654  5654 D HidService: setHidService(): set to: null
09-21 11:58:36.641  5654  5739 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f4b56d
09-21 11:58:36.641  5654  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-21 11:58:36.641  5590  5590 D BluetoothInputDevice: Proxy object connected
09-21 11:58:36.642  5654  5654 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-21 11:58:36.642  5590  5590 D HidProfile: Bluetooth service connected
09-21 11:58:36.643  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:36.644  5654  5654 D HealthService: Received start request. Starting profile...
09-21 11:58:36.645  5654  5654 I bt_bluedroid: get_profile_interface health
09-21 11:58:36.646  5654  5654 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-21 11:58:36.646  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:36.648  5590  5590 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 11:58:36.648  5590  5590 D PanProfile: Bluetooth service connected
09-21 11:58:36.649  5654  5654 D PanService: Received start request. Starting profile...
09-21 11:58:36.649  5654  5654 D BluetoothPanServiceJni: initializeNative(L110): pan
09-21 11:58:36.649  5654  5654 I bt_bluedroid: get_profile_interface pan
09-21 11:58:36.650  5654  5739 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-21 11:58:36.652  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:36.653  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 11:58:36.654  5654  5654 D BluetoothMapService: Received start request. Starting profile...
,09-21 11:58:36.654  5654  5654 D BluetoothMapService: start()
09-21 11:58:36.657  5654  5654 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-21 11:58:36.658  5654  5654 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-21 11:58:36.658  5654  5654 D BluetoothMapAppObserver: createReceiver()
09-21 11:58:36.659  5654  5654 D BluetoothMapAppObserver: initObservers()
09-21 11:58:36.659  5654  5654 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-21 11:58:36.664  5590  5590 D BluetoothMap: Proxy object connected
,09-21 11:58:36.664  5590  5590 D MapProfile: Bluetooth service connected
09-21 11:58:36.664  5590  5590 D BluetoothMap: getConnectedDevices()
09-21 11:58:36.665  5654  5654 V SapService: SapBinder()
09-21 11:58:36.665  5654  5654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:36.665  5590  5590 D BluetoothMap: Bluetooth is Not enabled
,09-21 11:58:36.665  5654  5654 D SapService: Received start request. Starting profile...
09-21 11:58:36.666  5654  5654 V SapService: start()
,09-21 11:58:36.669  5654  5654 V BluetoothAdapterState: isTurningOff()=false
,09-21 11:58:36.669  5654  5654 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:36.669  5654  5751 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-21 11:58:36.669  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:36.669  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:36.670  5654  5654 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:36.671  5654  5654 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:36.671  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:36.671  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:36.671  5654  5654 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:36.671  5654  5654 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:36.671  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:36.671  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 11:58:36.672  5654  5654 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:36.672  5654  5654 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:36.672  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:36.672  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 11:58:36.673  5654  5654 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:36.673  5654  5654 V BluetoothAdapterState: isTurningOn()=true
,09-21 11:58:36.673  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:36.673  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:36.673  5654  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-21 11:58:36.673  5654  5735 D BluetoothAdapterProperties: ScanMode =  20
09-21 11:58:36.673  5654  5735 D BluetoothAdapterProperties: State =  11
,09-21 11:58:36.676  5654  5739 D BluetoothAdapterProperties: Scan Mode:21
09-21 11:58:36.677  5654  5739 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 11:58:36.677  5654  5735 D BluetoothAdapterProperties: Setting state to 12
09-21 11:58:36.677  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-21 11:58:36.677  5654  5735 I BluetoothAdapterState: Entering OnState
09-21 11:58:36.677  3636  3658 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:36.678  3203  3216 D BluetoothMap: onBluetoothStateChange: up=true
,09-21 11:58:36.680  3203  3203 D BluetoothMap: Proxy object connected
,09-21 11:58:36.680  3203  3203 D MapProfile: Bluetooth service connected
09-21 11:58:36.680  3203  3203 D BluetoothMap: getConnectedDevices()
09-21 11:58:36.680  3203  3218 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 11:58:36.681  3203  3851 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:36.682  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:36.683  5590  5602 D BluetoothPan: onBluetoothStateChange on: true
,09-21 11:58:36.684  5590  5603 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-21 11:58:36.684  3203  3203 D BluetoothA2dp: Proxy object connected
09-21 11:58:36.684  3203  3218 D BluetoothPan: onBluetoothStateChange on: true
09-21 11:58:36.686  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:36.686  5654  5654 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 11:58:36.686  5590  5602 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 11:58:36.687  5654  5654 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-21 11:58:36.687  3203  3203 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 11:58:36.687  3203  3203 D PanProfile: Bluetooth service connected
,09-21 11:58:36.688  3203  3851 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 11:58:36.688  5654  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 11:58:36.690   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:36.690  5590  5603 D BluetoothMap: onBluetoothStateChange: up=true
,09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:36.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:36.690  5654  5654 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 11:58:36.691  3203  3216 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:36.691  3203  3203 D BluetoothInputDevice: Proxy object connected
09-21 11:58:36.691  3203  3203 D HidProfile: Bluetooth service connected
09-21 11:58:36.691   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:36.691   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 11:58:36.692   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:36.692   929   929 D BluetoothA2dp: Proxy object connected
,09-21 11:58:36.692  5654  5654 D ObexServerSockets: Succeed to create listening sockets 
,09-21 11:58:36.692  5654  5654 D ObexServerSockets0: startAccept()
09-21 11:58:36.692  5654  5654 D ObexServerSockets0: prepareForNewConnect()
09-21 11:58:36.694  5654  5654 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-21 11:58:36.694  5654  5654 D BluetoothSdpJni: SDP Create record success - handle: 0
09-21 11:58:36.694  5654  5654 D BluetoothMapService: onReceive
09-21 11:58:36.695  5654  5654 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 11:58:36.695  5654  5654 D BluetoothMapService: STATE_ON
09-21 11:58:36.695  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:36.696  5654  5761 D ObexServerSockets0: Accepting socket connection...
09-21 11:58:36.696  5654  5762 D ObexServerSockets0: Accepting socket connection...
09-21 11:58:36.697  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:36.698  5590  5590 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-21 11:58:36.698   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-21 11:58:36.698  5654  5763 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-21 11:58:36.699  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:36.700  5654  5763 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-21 11:58:36.700  5654  5763 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-21 11:58:36.702  5590  5590 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-21 11:58:36.711  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-21 11:58:36.714  5590  5590 D BluetoothA2dp: Proxy object connected
,09-21 11:58:36.715  5654  5654 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-21 11:58:36.715  5654  5654 D ObexServerSockets0: prepareForNewConnect()
,09-21 11:58:36.718  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 11:58:36.718  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,09-21 11:58:36.726  5590  5590 D BluetoothPbap: Proxy object connected
,09-21 11:58:36.727  5590  5590 D PbapServerProfile: Bluetooth service connected
09-21 11:58:36.728  3203  3203 D BluetoothPbap: Proxy object connected
09-21 11:58:36.728  3203  3203 D PbapServerProfile: Bluetooth service connected
09-21 11:58:36.731  5654  5767 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 11:58:36.747  5654  5771 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 11:58:36.749  5654  5771 I BtOppRfcommListener: Accept thread started.
,09-21 11:58:36.780   929   929 D BluetoothHeadset: Proxy object connected
09-21 11:58:36.780   929   929 D BluetoothHeadset: Proxy object connected
,09-21 11:58:36.780  3203  3218 D BluetoothHeadset: Proxy object connected
,09-21 11:58:36.780  3203  3203 D HeadsetProfile: Bluetooth service connected
09-21 11:58:36.781   929   929 D BluetoothHeadset: Proxy object connected
09-21 11:58:36.781  3636  3663 D BluetoothHeadset: Proxy object connected
,09-21 11:58:36.790   929   946 D BluetoothHeadset: Proxy object connected
,09-21 11:58:36.791  3203  3216 D BluetoothHeadset: Proxy object connected
09-21 11:58:36.792  3203  3203 D HeadsetProfile: Bluetooth service connected
,09-21 11:58:36.792   929   946 D BluetoothHeadset: Proxy object connected
09-21 11:58:36.792   929   946 D BluetoothHeadset: Proxy object connected
,09-21 11:58:36.807  5590  5602 D BluetoothHeadset: Proxy object connected
,09-21 11:58:36.808  5590  5590 D HeadsetProfile: Bluetooth service connected
,09-21 11:58:38.675  5654  5735 D BluetoothAdapterState: Current state: ON, message: 23
,09-21 11:58:38.675  5654  5735 D BluetoothAdapterProperties: Setting state to 13
,09-21 11:58:38.675  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-21 11:58:38.677  5654  5735 D BluetoothAdapterProperties: onBluetoothDisable()
,09-21 11:58:38.678  5654  5735 I BluetoothAdapterState: Entering PendingCommandState
09-21 11:58:38.681  5654  5739 D BluetoothAdapterProperties: Scan Mode:20
09-21 11:58:38.685  5654  5654 D BluetoothMapService: onReceive
09-21 11:58:38.685  5654  5654 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 11:58:38.685  5654  5654 D BluetoothMapService: STATE_TURNING_OFF
09-21 11:58:38.686  5654  5654 D BluetoothMapService: MAP Service closeService in
09-21 11:58:38.686  5654  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-21 11:58:38.686  5654  5654 D BluetoothMapMasInstance0: MAP Service shutdown
09-21 11:58:38.686  5654  5654 D ObexServerSockets0: shutdown(block = true)
,09-21 11:58:38.690  5654  5654 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-21 11:58:38.690  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-21 11:58:38.690  5654  5761 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:38.690  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:38.691  5654  5762 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-21 11:58:38.692  5654  5654 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-21 11:58:38.692  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:38.692  5654  5748 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-21 11:58:38.692  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:38.693  5654  5654 I BtOppRfcommListener: stopping Accept Thread
09-21 11:58:38.694  5654  5771 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-21 11:58:38.694  5654  5771 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-21 11:58:38.694  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 11:58:38.696  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:38.696  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:38.697  5538  5538 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-21 11:58:38.697  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:38.701  5654  5654 D HeadsetService: Received stop request...Stopping profile...
09-21 11:58:38.702  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:38.704  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:38.706   929   929 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:38.706   929   929 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:38.706  3203  3851 D BluetoothHeadset: Proxy object disconnected
09-21 11:58:38.706   929   929 D BluetoothHeadset: Proxy object disconnected
,09-21 11:58:38.707  3636  3658 D BluetoothHeadset: Proxy object disconnected
,09-21 11:58:38.707  5590  5603 D BluetoothHeadset: Proxy object disconnected
,09-21 11:58:38.708  5654  5654 D A2dpService: Received stop request...Stopping profile...
09-21 11:58:38.708  5654  5754 D A2dpStateMachine: Exit Disconnected: -1
09-21 11:58:38.708  3203  3203 D HeadsetProfile: Bluetooth service disconnected
09-21 11:58:38.710   929   929 D BluetoothA2dp: Proxy object disconnected
09-21 11:58:38.710  3203  3203 D BluetoothA2dp: Proxy object disconnected
09-21 11:58:38.714  5654  5654 D HidService: Received stop request...Stopping profile...
09-21 11:58:38.714  5654  5654 D HidService: Stopping Bluetooth HidService
09-21 11:58:38.714  3203  3203 D BluetoothInputDevice: Proxy object disconnected
09-21 11:58:38.714  5590  5590 D DockEventReceiver: finishStartingService: stopping service
09-21 11:58:38.714  3203  3203 D HidProfile: Bluetooth service disconnected
09-21 11:58:38.715  5590  5590 D HeadsetProfile: Bluetooth service disconnected
09-21 11:58:38.716  5590  5590 D BluetoothA2dp: Proxy object disconnected
09-21 11:58:38.716  5654  5654 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:38.716  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:38.716  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:38.716  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:38.716  5590  5590 D BluetoothInputDevice: Proxy object disconnected
09-21 11:58:38.716  5590  5590 D HidProfile: Bluetooth service disconnected
09-21 11:58:38.716  5654  5654 D HealthService: Received stop request...Stopping profile...
,09-21 11:58:38.719  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 11:58:38.722  5654  5654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-21 11:58:38.722  5654  5654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-21 11:58:38.723  5654  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:38.723  5654  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:38.723  5654  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-21 11:58:38.723  5654  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-21 11:58:38.723  5654  5739 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-21 11:58:38.723  5654  5654 D PanService: Received stop request...Stopping profile...
09-21 11:58:38.724  3203  3203 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 11:58:38.724  3203  3203 D PanProfile: Bluetooth service disconnected
09-21 11:58:38.724  5654  5654 V BluetoothAdapterState: isTurningOff()=true
,09-21 11:58:38.724  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:38.724  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:38.724  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:38.724  5590  5590 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-21 11:58:38.724  5590  5590 D PanProfile: Bluetooth service disconnected
09-21 11:58:38.725  5654  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-21 11:58:38.725  5654  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:38.725  5654  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:38.726  5654  5746 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 11:58:38.726  5654  5746 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-21 11:58:38.726  5654  5746 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-21 11:58:38.726  5654  5746 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-21 11:58:38.726  5654  5654 D BluetoothMapService: Received stop request...Stopping profile...
09-21 11:58:38.726  5654  5654 D BluetoothMapService: stop()
09-21 11:58:38.727  5654  5654 D BluetoothMapAppObserver: deinitObservers()
,09-21 11:58:38.727  5654  5654 D BluetoothMapAppObserver: removeReceiver()
09-21 11:58:38.728  5590  5590 D BluetoothMap: Proxy object disconnected
09-21 11:58:38.729  5590  5590 D MapProfile: Bluetooth service disconnected
09-21 11:58:38.729  3203  3203 D BluetoothMap: Proxy object disconnected
09-21 11:58:38.729  5654  5654 D SapService: Received stop request...Stopping profile...
09-21 11:58:38.729  3203  3203 D MapProfile: Bluetooth service disconnected
09-21 11:58:38.729  5654  5654 V SapService: stop()
09-21 11:58:38.730  5654  5654 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:38.730  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:38.730  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:38.730  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 11:58:38.731  5654  5654 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-21 11:58:38.731  5654  5654 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-21 11:58:38.731  5654  5739 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-21 11:58:38.732  3203  3203 D BluetoothPbap: Proxy object disconnected
09-21 11:58:38.732  3203  3203 D PbapServerProfile: Bluetooth service disconnected
09-21 11:58:38.733  5590  5590 D BluetoothPbap: Proxy object disconnected
09-21 11:58:38.733  5654  5654 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:38.733  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:38.733  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:38.733  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:38.733  5590  5590 D PbapServerProfile: Bluetooth service disconnected
09-21 11:58:38.733  5654  5654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-21 11:58:38.734  5654  5739 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-21 11:58:38.734  5654  5654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-21 11:58:38.734  5654  5654 V BluetoothAdapterState: isTurningOff()=true
,09-21 11:58:38.734  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:38.734  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:38.734  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:38.734  5654  5654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-21 11:58:38.735  5654  5654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-21 11:58:38.737  5654  5654 D BluetoothMapService: MAP Service closeService in
09-21 11:58:38.737  5654  5654 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:38.737  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:38.737  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:38.737  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:38.738  5654  5654 D BluetoothMapService: cleanup()
,09-21 11:58:38.738  5654  5654 D BluetoothMapService: MAP Service closeService in
09-21 11:58:38.738  5654  5654 V BluetoothAdapterState: isTurningOff()=true
09-21 11:58:38.738  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:38.738  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:38.738  5654  5654 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:38.738  5654  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-21 11:58:38.738  5654  5735 D BluetoothAdapterProperties: Setting state to 15
09-21 11:58:38.738  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-21 11:58:38.739  5654  5735 I BluetoothAdapterState: Entering BleOnState
,09-21 11:58:38.741  3636  3663 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:38.742  3203  3216 D BluetoothMap: onBluetoothStateChange: up=false
,09-21 11:58:38.743  3203  3851 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 11:58:38.744  3203  3218 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 11:58:38.745  5590  5603 D BluetoothPan: onBluetoothStateChange on: false
,09-21 11:58:38.745  5590  5602 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 11:58:38.746  3203  3216 D BluetoothPan: onBluetoothStateChange on: false
,09-21 11:58:38.746  5590  5603 D BluetoothPbap: onBluetoothStateChange: up=false
09-21 11:58:38.747  3203  3851 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-21 11:58:38.748   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:38.748  5590  5602 D BluetoothMap: onBluetoothStateChange: up=false
09-21 11:58:38.749  3203  3218 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:38.749   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:38.749  5590  5603 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 11:58:38.749  5590  5602 D BluetoothHeadset: onBluetoothStateChange: up=false
09-21 11:58:38.750   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-21 11:58:38.750   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-21 11:58:38.750  5654  5735 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-21 11:58:38.750  5654  5735 D BluetoothAdapterProperties: Setting state to 16
09-21 11:58:38.750  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-21 11:58:38.751  5654  5735 D BluetoothAdapterProperties: onBleDisable
09-21 11:58:38.751  5654  5735 I BluetoothAdapterState: Entering PendingCommandState
09-21 11:58:38.752  5654  5736 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-21 11:58:38.753  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:38.753  5654  5739 D BluetoothAdapterProperties: Scan Mode:20
09-21 11:58:38.754  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-21 11:58:38.754  5654  5746 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-21 11:58:38.754  5654  5746 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-21 11:58:38.754  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:38.756  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:38.760  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-21 11:58:38.761  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:38.770  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,09-21 11:58:38.962  5654  5739 I bt_hci  : shut_down
,09-21 11:58:38.966  5654  5743 D bt_hwcfg: hw_epilog_process
,09-21 11:58:38.967  5654  5743 I bt_vendor: low_power_mode_cb
,09-21 11:58:38.969  5654  5743 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-21 11:58:38.969  5654  5743 I bt_vendor: epilog_cb
09-21 11:58:38.969  5654  5743 I bt_hci  : epilog_finished_callback
,09-21 11:58:38.972  5654  5739 I bt_hci_h4: hal_close
,09-21 11:58:38.972  5654  5739 I bt_userial_vendor: device fd = 54 close
,09-21 11:58:39.082  5654  5736 D bt_stack_manager: event_shut_down_stack finished.
,09-21 11:58:39.083  5654  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-21 11:58:39.088  5654  5735 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-21 11:58:39.088  5654  5654 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 11:58:39.089  5654  5654 D BtGatt.GattService: Received stop request...Stopping profile...
,09-21 11:58:39.089  5654  5654 D BtGatt.GattService: stop()
,09-21 11:58:39.090  5654  5654 D BtGatt.AdvertiseManager: advertise clients cleared,
09-21 11:58:39.094  5654  5654 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:39.094  5654  5654 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:39.095  5654  5654 V BluetoothAdapterState: isBleTurningOn()=false
,09-21 11:58:39.095  5654  5654 V BluetoothAdapterState: isBleTurningOff()=true
09-21 11:58:39.095  5654  5735 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-21 11:58:39.096  5654  5735 D BluetoothAdapterProperties: Setting state to 10
,09-21 11:58:39.096  5654  5735 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-21 11:58:39.097  5654  5735 I BluetoothAdapterState: Entering OffState
,09-21 11:58:39.098   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-21 11:58:39.114  5654  5654 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-21 11:58:39.114  5654  5654 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-21 11:58:39.115  5654  5654 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-21 11:58:39.117  5654  5736 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-21 11:58:39.126  5654  5654 I art     : System.exit called, status: 0
,09-21 11:58:39.126  5654  5654 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-21 11:58:39.156   929  3224 I ActivityManager: Process com.android.bluetooth (pid 5654) has died
,09-21 11:58:41.672  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 11:58:41.673  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 11:58:44.679  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:44.680  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ec39632 added. We now have 6 listener(s)
,09-21 11:58:44.681  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 11:58:44.685  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 11:58:44.685  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@db65f83 added. We now have 7 listener(s)
,09-21 11:58:44.685  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 11:58:44.687  5538  5584 I System.out: IsBluetoothEnabled
,09-21 11:58:44.696  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:44.723   929   946 I ActivityManager: Start proc 5779:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-21 11:58:44.812  5779  5779 D AdapterServiceConfig: Adding HeadsetService
,09-21 11:58:44.812  5779  5779 D AdapterServiceConfig: Adding A2dpService
09-21 11:58:44.812  5779  5779 D AdapterServiceConfig: Adding HidService
09-21 11:58:44.813  5779  5779 D AdapterServiceConfig: Adding HealthService
09-21 11:58:44.813  5779  5779 D AdapterServiceConfig: Adding PanService
09-21 11:58:44.813  5779  5779 D AdapterServiceConfig: Adding GattService
,09-21 11:58:44.813  5779  5779 D AdapterServiceConfig: Adding BluetoothMapService
09-21 11:58:44.813  5779  5779 D AdapterServiceConfig: Adding SapService
,09-21 11:58:44.827   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32f4c34:true
,09-21 11:58:44.828  5779  5779 D BluetoothAdapterState: make() - Creating AdapterState
,09-21 11:58:44.832  5779  5779 I bt_bluedroid: init
09-21 11:58:44.832  5779  5791 I BluetoothAdapterState: Entering OffState
,09-21 11:58:44.835  5779  5792 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-21 11:58:44.835  5779  5792 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-21 11:58:44.835  5779  5792 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-21 11:58:44.835  5779  5792 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-21 11:58:44.836  5779  5779 I bt_bluedroid: get_profile_interface socket
,09-21 11:58:44.838  5779  5779 I bt_bluedroid: get_profile_interface sdp
,09-21 11:58:44.838  5779  5795 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-21 11:58:44.840  5779  5795 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 11:58:44.846  5779  5790 I bt_bluedroid: config_hci_snoop_log
09-21 11:58:44.848   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-21 11:58:44.853  5779  5791 D BluetoothAdapterState: Current state: OFF, message: 0
,09-21 11:58:44.853  5779  5791 D BluetoothAdapterProperties: Setting state to 14
09-21 11:58:44.854  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-21 11:58:44.857  5779  5791 D BluetoothBondStateMachine: make
,09-21 11:58:44.859  5779  5796 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-21 11:58:44.861  5779  5791 I BluetoothAdapterState: Entering PendingCommandState
,09-21 11:58:44.863  5779  5779 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-21 11:58:44.865  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:44.866  5779  5779 D BtGatt.DebugUtils: handleDebugAction() action=null
09-21 11:58:44.866  5779  5779 D BtGatt.GattService: Received start request. Starting profile...
09-21 11:58:44.866  5779  5779 D BtGatt.GattService: start()
09-21 11:58:44.866  5779  5779 I bt_bluedroid: get_profile_interface gatt
09-21 11:58:44.867  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:44.867  5779  5779 D BtGatt.AdvertiseManager: advertise manager created
,09-21 11:58:44.873  5779  5779 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:44.873  5779  5779 V BluetoothAdapterState: isTurningOn()=false
09-21 11:58:44.873  5779  5779 V BluetoothAdapterState: isBleTurningOn()=true
09-21 11:58:44.873  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:44.873  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-21 11:58:44.874  5779  5791 I bt_bluedroid: bt_bluedroid
,09-21 11:58:44.875  5779  5792 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-21 11:58:44.875  5779  5792 I bt_hci  : start_up
,09-21 11:58:44.880  5779  5792 I bt_vendor: alloc value 0xf4039871
,09-21 11:58:44.881  5779  5792 I bt_vendor: init
09-21 11:58:44.881  5779  5792 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-21 11:58:44.881  5779  5792 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-21 11:58:44.990  5779  5792 D bt_hci  : start_up starting async portion
,09-21 11:58:44.991  5779  5799 I bt_hci  : event_finish_startup
09-21 11:58:44.991  5779  5799 I bt_hci_h4: hal_open
09-21 11:58:44.991  5779  5799 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-21 11:58:44.995  5779  5799 I bt_userial_vendor: device fd = 54 open
,09-21 11:58:44.990  5800  5800 W irq/448-msm_hs_: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 11:58:45.009  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 11:58:45.011  5779  5799 D bt_hwcfg: Chipset BCM4358A3
,09-21 11:58:45.012  5779  5799 D bt_hwcfg: Target name = [BCM4358A3]
09-21 11:58:45.012  5779  5799 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-21 11:58:45.412  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-21 11:58:45.412  5779  5799 D bt_hwcfg: Settlement delay -- 100 ms
09-21 11:58:45.412  5779  5799 I bt_hwcfg: Setting fw settlement delay to 100 
,09-21 11:58:45.547  5779  5799 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-21 11:58:45.548  5779  5799 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-21 11:58:45.549  5779  5799 I bt_hwcfg: vendor lib fwcfg completed
,09-21 11:58:45.549  5779  5799 I bt_vendor: firmware callback
,09-21 11:58:45.549  5779  5799 I bt_hci  : firmware_config_callback
,09-21 11:58:45.558  5779  5802 I bt_btu  : btu_task pending for preload complete event
,09-21 11:58:45.558  5779  5802 I bt_btu_task: Bluetooth chip preload is complete
09-21 11:58:45.558  5779  5802 I bt_btu  : btu_task received preload complete event
,09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_HCI
,09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_AVDT
09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_A2D
,09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_BNEP
09-21 11:58:45.564  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTM
09-21 11:58:45.565  5779  5802 I         : BTE_InitTraceLevels -- TRC_GAP
09-21 11:58:45.565  5779  5802 I         : BTE_InitTraceLevels -- TRC_PAN
09-21 11:58:45.565  5779  5802 I         : BTE_InitTraceLevels -- TRC_SDP
09-21 11:58:45.565  5779  5802 I         : BTE_InitTraceLevels -- TRC_GATT
09-21 11:58:45.565  5779  5802 I         : BTE_InitTraceLevels -- TRC_SMP
,09-21 11:58:45.565  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-21 11:58:45.565  5779  5802 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-21 11:58:45.647  5779  5802 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fb7549
,09-21 11:58:45.648  5779  5802 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fb7549 
,09-21 11:58:45.672  5779  5795 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-21 11:58:45.674  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-21 11:58:45.674  5779  5795 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-21 11:58:45.677  5779  5795 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-21 11:58:45.679  5779  5795 D BluetoothAdapterProperties: Scan Mode:20
09-21 11:58:45.680  5779  5795 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 11:58:45.680  5779  5795 D bt_hci  : do_postload posting postload work item
,09-21 11:58:45.680  5779  5799 I bt_hci  : event_postload
09-21 11:58:45.680  5779  5799 I bt_vendor: sco_config_cb
09-21 11:58:45.681  5779  5799 I bt_hci  : sco_config_callback postload finished.
09-21 11:58:45.682  5779  5795 D bt_bte_conf: Device ID record 1 : primary
09-21 11:58:45.683  5779  5795 D bt_bte_conf:   vendorId            = 000f
09-21 11:58:45.683  5779  5795 D bt_bte_conf:   vendorIdSource      = 0001
09-21 11:58:45.683  5779  5795 D bt_bte_conf:   product             = 1200
09-21 11:58:45.683  5779  5795 D bt_bte_conf:   version             = 1436
09-21 11:58:45.683  5779  5795 D bt_bte_conf:   clientExecutableURL = 
09-21 11:58:45.683  5779  5795 D bt_bte_conf:   serviceDescription  = 
09-21 11:58:45.683  5779  5795 D bt_bte_conf:   documentationURL    = 
09-21 11:58:45.683  5779  5795 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-21 11:58:45.684  5779  5792 D bt_stack_manager: event_start_up_stack finished
09-21 11:58:45.684  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-21 11:58:45.685  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:45.685  5779  5791 D BluetoothAdapterProperties: Setting state to 15
09-21 11:58:45.685  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-21 11:58:45.686  5779  5791 I BluetoothAdapterState: Entering BleOnState
09-21 11:58:45.689  5779  5799 I bt_vendor: low_power_mode_cb
,09-21 11:58:45.692  5779  5791 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-21 11:58:45.693  5779  5791 D BluetoothAdapterProperties: Setting state to 11
09-21 11:58:45.693  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-21 11:58:45.702  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:45.703  5779  5779 D HeadsetService: Received start request. Starting profile...
,09-21 11:58:45.703  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:45.706  5779  5779 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-21 11:58:45.706  5779  5779 D HeadsetStateMachine: make
,09-21 11:58:45.712  5779  5791 I BluetoothAdapterState: Entering PendingCommandState
,09-21 11:58:45.716  5779  5779 D HeadsetStateMachine: max_hf_connections = 1
,09-21 11:58:45.716  5779  5779 I bt_bluedroid: get_profile_interface handsfree
09-21 11:58:45.716  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-21 11:58:45.716  5779  5795 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-21 11:58:45.721  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:45.721  5779  5779 D A2dpService: Received start request. Starting profile...
,09-21 11:58:45.722  5779  5779 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-21 11:58:45.722  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 11:58:45.722  5779  5779 I bt_bluedroid: get_profile_interface avrcp
,09-21 11:58:45.729  5779  5779 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-21 11:58:45.729  5779  5779 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-21 11:58:45.729  5779  5779 D A2dpStateMachine: make
,09-21 11:58:45.730  5779  5779 I bt_bluedroid: get_profile_interface a2dp
,09-21 11:58:45.731  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-21 11:58:45.732  5779  5811 D A2dpStateMachine: Enter Disconnected: -2
,09-21 11:58:45.733  5779  5779 I BluetoothHidServiceJni: classInitNative: succeeds
,09-21 11:58:45.734  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:45.734  5779  5779 D HidService: Received start request. Starting profile...
09-21 11:58:45.734  5779  5779 I bt_bluedroid: get_profile_interface hidhost
,09-21 11:58:45.735  5779  5795 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f9856d
09-21 11:58:45.735  5779  5779 D HidService: setHidService(): set to: null
09-21 11:58:45.735  5779  5795 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-21 11:58:45.735  5779  5779 I BluetoothHealthServiceJni: classInitNative: succeeds
09-21 11:58:45.736  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:45.736  5779  5779 D HealthService: Received start request. Starting profile...
,09-21 11:58:45.738  5779  5779 I bt_bluedroid: get_profile_interface health
,09-21 11:58:45.738  5779  5779 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-21 11:58:45.739  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
09-21 11:58:45.739  5779  5779 D PanService: Received start request. Starting profile...
09-21 11:58:45.739  5779  5779 D BluetoothPanServiceJni: initializeNative(L110): pan
09-21 11:58:45.740  5779  5779 I bt_bluedroid: get_profile_interface pan
09-21 11:58:45.740  5779  5795 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-21 11:58:45.741  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:45.742  5779  5779 D BluetoothMapService: Received start request. Starting profile...
09-21 11:58:45.742  5779  5779 D BluetoothMapService: start()
,09-21 11:58:45.744  5779  5779 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-21 11:58:45.745  5779  5779 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-21 11:58:45.745  5779  5779 D BluetoothMapAppObserver: createReceiver()
09-21 11:58:45.746  5779  5779 D BluetoothMapAppObserver: initObservers()
,09-21 11:58:45.746  5779  5779 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-21 11:58:45.752  5779  5779 V SapService: SapBinder()
09-21 11:58:45.752  5779  5779 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:45.752  5779  5779 D SapService: Received start request. Starting profile...
09-21 11:58:45.752  5779  5779 V SapService: start()
,09-21 11:58:45.755  5779  5779 V BluetoothAdapterState: isTurningOff()=false
,09-21 11:58:45.756  5779  5779 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:45.756  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:45.756  5779  5809 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-21 11:58:45.756  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:45.756  5779  5779 V BluetoothAdapterState: isTurningOff()=false
,09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:45.757  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isTurningOn()=true
,09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:45.758  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 11:58:45.759  5779  5779 V BluetoothAdapterState: isTurningOff()=false
09-21 11:58:45.759  5779  5779 V BluetoothAdapterState: isTurningOn()=true
09-21 11:58:45.759  5779  5779 V BluetoothAdapterState: isBleTurningOn()=false
09-21 11:58:45.759  5779  5779 V BluetoothAdapterState: isBleTurningOff()=false
,09-21 11:58:45.760  5779  5791 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-21 11:58:45.760  5779  5791 D BluetoothAdapterProperties: ScanMode =  20
09-21 11:58:45.760  5779  5791 D BluetoothAdapterProperties: State =  11
09-21 11:58:45.761  5779  5791 D BluetoothAdapterProperties: Setting state to 12
09-21 11:58:45.761  5779  5791 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-21 11:58:45.761  5779  5791 I BluetoothAdapterState: Entering OnState
09-21 11:58:45.761  3636  3880 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:45.761  5779  5795 D BluetoothAdapterProperties: Scan Mode:21
09-21 11:58:45.761  5779  5795 D BluetoothAdapterProperties: Discoverable Timeout:120
09-21 11:58:45.762  3203  3216 D BluetoothMap: onBluetoothStateChange: up=true
09-21 11:58:45.764  3203  3218 D BluetoothPbap: onBluetoothStateChange: up=true
09-21 11:58:45.765  3203  3203 D BluetoothMap: Proxy object connected
09-21 11:58:45.765  3203  3203 D MapProfile: Bluetooth service connected
09-21 11:58:45.765  3203  3203 D BluetoothMap: getConnectedDevices()
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:45.766  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:45.766  3203  3851 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 11:58:45.768  5590  5602 D BluetoothPan: onBluetoothStateChange on: true
,09-21 11:58:45.769  3203  3203 D BluetoothA2dp: Proxy object connected
09-21 11:58:45.769  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:45.772  5779  5779 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-21 11:58:45.772  5779  5779 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-21 11:58:45.774  5590  5603 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-21 11:58:45.774  5779  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 11:58:45.776  5779  5779 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 11:58:45.777  5779  5779 D ObexServerSockets: Succeed to create listening sockets 
,09-21 11:58:45.777  5779  5779 D ObexServerSockets0: startAccept()
09-21 11:58:45.777  5779  5779 D ObexServerSockets0: prepareForNewConnect()
,09-21 11:58:45.779  5779  5779 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-21 11:58:45.779  5779  5779 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-21 11:58:45.780  5590  5590 D BluetoothPan: BluetoothPAN Proxy object connected
,09-21 11:58:45.781  5590  5590 D PanProfile: Bluetooth service connected
09-21 11:58:45.781  5779  5817 D ObexServerSockets0: Accepting socket connection...
09-21 11:58:45.781  5779  5818 D ObexServerSockets0: Accepting socket connection...
09-21 11:58:45.782  3203  3216 D BluetoothPan: onBluetoothStateChange on: true
09-21 11:58:45.784  3203  3203 D BluetoothPan: BluetoothPAN Proxy object connected
09-21 11:58:45.784  3203  3203 D PanProfile: Bluetooth service connected
09-21 11:58:45.784  5590  5603 D BluetoothPbap: onBluetoothStateChange: up=true
,09-21 11:58:45.786  3203  3218 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-21 11:58:45.787  5590  5590 D BluetoothInputDevice: Proxy object connected
,09-21 11:58:45.787  5590  5590 D HidProfile: Bluetooth service connected
09-21 11:58:45.787   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:45.787  3203  3203 D BluetoothInputDevice: Proxy object connected
09-21 11:58:45.788  3203  3203 D HidProfile: Bluetooth service connected
09-21 11:58:45.788  5590  5602 D BluetoothMap: onBluetoothStateChange: up=true
09-21 11:58:45.790  3203  3851 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:45.790   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:45.790  5590  5603 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 11:58:45.792  5590  5602 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:45.792   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-21 11:58:45.793   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-21 11:58:45.793   929   929 D BluetoothA2dp: Proxy object connected
,09-21 11:58:45.796  5779  5779 D BluetoothMapService: onReceive
,09-21 11:58:45.796  5779  5779 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-21 11:58:45.796  5779  5779 D BluetoothMapService: STATE_ON
,09-21 11:58:45.796   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-21 11:58:45.797  5590  5590 D BluetoothMap: Proxy object connected
,09-21 11:58:45.797  5590  5590 D MapProfile: Bluetooth service connected
09-21 11:58:45.797  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:45.797  5590  5590 D BluetoothMap: getConnectedDevices()
09-21 11:58:45.798  5779  5821 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 11:58:45.799  5590  5590 D BluetoothA2dp: Proxy object connected
,09-21 11:58:45.799  5779  5821 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-21 11:58:45.800  5779  5821 D BluetoothSdpJni: SDP Create record success - handle: 1
09-21 11:58:45.804  5590  5590 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-21 11:58:45.811  3725  3725 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-21 11:58:45.811  5590  5590 D DockEventReceiver: finishStartingService: stopping service
,09-21 11:58:45.818  5779  5779 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-21 11:58:45.818  5779  5779 D ObexServerSockets0: prepareForNewConnect()
,09-21 11:58:45.822  5590  5590 D BluetoothPbap: Proxy object connected
,09-21 11:58:45.822  5590  5590 D PbapServerProfile: Bluetooth service connected
09-21 11:58:45.822  3203  3203 D BluetoothPbap: Proxy object connected
09-21 11:58:45.823  3203  3203 D PbapServerProfile: Bluetooth service connected
,09-21 11:58:45.828  5779  5825 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 11:58:45.839  5779  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-21 11:58:45.840  5779  5829 I BtOppRfcommListener: Accept thread started.
,09-21 11:58:45.863   929   929 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.863   929   929 D BluetoothHeadset: Proxy object connected
09-21 11:58:45.864  3203  3218 D BluetoothHeadset: Proxy object connected
09-21 11:58:45.864  3203  3203 D HeadsetProfile: Bluetooth service connected
09-21 11:58:45.864   929   929 D BluetoothHeadset: Proxy object connected
09-21 11:58:45.864  3636  3658 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.865  5590  5819 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.866  5590  5590 D HeadsetProfile: Bluetooth service connected
,09-21 11:58:45.888   929   946 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.890  3203  3216 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.890  3203  3203 D HeadsetProfile: Bluetooth service connected
09-21 11:58:45.891   929   946 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.893  5590  5603 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.893   929   946 D BluetoothHeadset: Proxy object connected
,09-21 11:58:45.893  5590  5590 D HeadsetProfile: Bluetooth service connected
,09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:46.713  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:46.720  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:46.723  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 11:58:46.723  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a12c500 added. We now have 8 listener(s)
,09-21 11:58:46.723  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 11:58:46.727   929  3672 D WifiService: setWifiEnabled: false pid=5538, uid=10077
09-21 11:58:46.728   929  3672 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 11:58:46.734  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:46.735   929  3721 D WifiService: setWifiEnabled: true pid=5538, uid=10077
09-21 11:58:46.735   929  3721 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-21 11:58:46.743   507   922 D SoftapController: Softap fwReload - Ok
,09-21 11:58:46.746   507   922 D CommandListener: Setting iface cfg
,09-21 11:58:46.746   507   922 D CommandListener: Trying to bring down wlan0
09-21 11:58:46.747   507   922 D CommandListener: Clearing all IP addresses on wlan0
,09-21 11:58:46.750   929  3052 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-21 11:58:47.359   929  3052 D wifi    : set interface wlan0 flags (UP)
,09-21 11:58:47.364   929  3052 I WifiHAL : Initializing wifi
09-21 11:58:47.364   929  3052 I WifiHAL : Creating socket
,09-21 11:58:47.369   929  3052 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-21 11:58:47.369   929  3052 D wifi    : Did set static halHandle = 0x7f885a34e0
,09-21 11:58:47.369   929  3052 D wifi    : halHandle = 0x7f885a34e0, mVM = 0x7fa4bcd140, mCls = 0x2017ca
09-21 11:58:47.370   929  3052 D wifi    : array field set
09-21 11:58:47.368   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-21 11:58:47.370   929  3052 I WifiNative-HAL: interface[0] = wlan0
09-21 11:58:47.372   929  5834 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547748459744
,09-21 11:58:47.372   929  5834 D wifi    : waitForHalEvents called, vm = 0x7fa4bcd140, obj = 0x2017ca, env = 0x7f88e68380
,09-21 11:58:47.430  5835  5835 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-21 11:58:47.450  5835  5835 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 11:58:47.460  5835  5835 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-21 11:58:47.460  5835  5835 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-21 11:58:47.473   929  3052 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-21 11:58:47.484   929  3052 D WifiConfigStore: Loading config and enabling all networks 
,09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:47.484  5538  5538 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-21 11:58:47.487  5538  5538 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:47.489  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:47.496   929  3052 D WifiConfigStore: loaded 0 passpoint configs
,09-21 11:58:47.496   929  3052 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-21 11:58:47.496   929  3052 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-21 11:58:47.497   929  3052 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-21 11:58:47.498   929  3052 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-21 11:58:47.499   929  3052 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-21 11:58:47.499   929  3052 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-21 11:58:47.499   929  3052 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-21 11:58:47.502  4373  4373 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-21 11:58:47.502   929  3052 D WifiNative-HAL: Setting external_sim to 1
09-21 11:58:47.502   929  3052 D wifi    : setting dfs flag to true, 0x7f894ef640
09-21 11:58:47.503   929  3052 D WifiStateMachine: Setting OUI to DA-A1-19
09-21 11:58:47.503   929  3052 D wifi    : setting scan oui 0x7f894ef640
09-21 11:58:47.503   929  3052 D WifiHAL : Sending mac address OUI
,09-21 11:58:47.507   929  3052 E native  : do suspend false
,09-21 11:58:47.514   929   929 D RttService: SCAN_AVAILABLE : 3
,09-21 11:58:47.514   929  3052 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-21 11:58:47.514   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-21 11:58:47.514   929  3158 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-21 11:58:47.515   507   922 D CommandListener: Setting iface cfg
,09-21 11:58:47.519   929  3051 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-21 11:58:47.519   929  3051 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-21 11:58:47.527   929  3051 D WifiNative-HAL: p2pGetDeviceAddress
,09-21 11:58:47.527   929  3051 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-21 11:58:47.534   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=212320 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=16 mControllerEnergyUsed=60 }
,09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:47.754  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:47.759  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:47.766  5538  5584 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-21 11:58:47.767  5538  5584 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-21 11:58:47.772  5538  5584 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f55664b Bundle[{}]
,09-21 11:58:47.773  5538  5584 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-21 11:58:47.774  5538  5584 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-21 11:58:47.775  5538  5584 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-21 11:58:47.776  5538  5584 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-21 11:58:47.776  5538  5584 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-21 11:58:47.778  5538  5584 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-21 11:58:47.786  5538  5584 I System.out: Running OutgoingSocketThread
,09-21 11:58:47.787  5538  5837 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,09-21 11:58:47.789  5538  5837 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44166
09-21 11:58:47.789  5538  5837 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-21 11:58:48.789  5538  5584 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,09-21 11:58:48.789  5538  5584 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,09-21 11:58:48.794  5538  5584 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,09-21 11:58:48.796  5538  5584 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-21 11:58:48.796  5538  5584 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,09-21 11:58:48.802  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-21 11:58:48.802  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41139 added. We now have 2 listener(s)
09-21 11:58:48.806  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.806  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.806  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.806  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 11:58:48.806  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a10e37e added. We now have 9 listener(s)
09-21 11:58:48.807  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.807  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 11:58:48.811  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:48.815  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:48.817  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:48.817  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:58:48.817  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.817  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5f312c added. We now have 3 listener(s)
,09-21 11:58:48.819  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.819  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.820  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.820  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.820  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.820  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b87f5 added. We now have 10 listener(s)
09-21 11:58:48.820  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.821  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:48.821  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:48.821  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-21 11:58:48.821  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.821  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.821  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.821  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.821  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@41139 removed from the list
09-21 11:58:48.821  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.821  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a10e37e removed from the list
09-21 11:58:48.821  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.822  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:48.822  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 11:58:48.822  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.823  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.824  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 11:58:48.825  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.825  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.825  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a10e37e not in the list
09-21 11:58:48.825  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.825  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 11:58:48.826  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.826  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:48.826  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.826  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8b87f5 removed from the list
09-21 11:58:48.826  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.826  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 11:58:48.826  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.826  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.826  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f5f312c removed from the list
,09-21 11:58:48.827  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.827  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b53b98a added. We now have 2 listener(s)
09-21 11:58:48.828  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.829  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-21 11:58:48.829  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.829  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.829  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fea3bfb added. We now have 9 listener(s)
09-21 11:58:48.829  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.830  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 11:58:48.832  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:48.835  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:48.836  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:48.837  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:58:48.837  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.837  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd9ae71 added. We now have 3 listener(s)
,09-21 11:58:48.838  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:48.838  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.838  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.838  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.839  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.839  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53be456 added. We now have 10 listener(s)
09-21 11:58:48.839  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.839  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:48.839  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 11:58:48.839  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:58:48.839  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:48.839  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 11:58:48.839  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-21 11:58:48.842  5538  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 11:58:48.842  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-21 11:58:48.845  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 11:58:48.846  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:58:48.846  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 11:58:48.848  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 11:58:48.848  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:58:48.848  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-21 11:58:48.849  5538  5584 D BluetoothAdapter: STATE_ON
,09-21 11:58:48.851  5779  5820 D BtGatt.GattService: registerClient() - UUID=671cd45e-ff75-41be-a0b3-bb13f300c739
09-21 11:58:48.852  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=671cd45e-ff75-41be-a0b3-bb13f300c739, clientIf=5
,09-21 11:58:48.853  5538  5548 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 11:58:48.853  5779  5808 D BtGatt.GattService: start scan with filters
09-21 11:58:48.857  5779  5798 D BtGatt.ScanManager: handling starting scan
,09-21 11:58:48.858  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 11:58:48.858  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:58:48.858  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:58:48.858  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-21 11:58:48.858  5779  5798 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@95b743c
,09-21 11:58:48.860  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:48.860  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:58:48.860  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:48.861  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 11:58:48.864  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-21 11:58:48.864  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.865  5538  5584 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-21 11:58:48.865  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-21 11:58:48.865  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:48.865  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-21 11:58:48.865  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.865  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:58:48.865  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-21 11:58:48.865  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:58:48.865  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 11:58:48.865  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:58:48.865  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 11:58:48.865  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-21 11:58:48.867  5538  5584 D BluetoothAdapter: STATE_ON
,09-21 11:58:48.867  5779  5789 D BtGatt.GattService: stopScan() - queue size =1
09-21 11:58:48.868  5779  5820 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:58:48.868  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:58:48.868  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 11:58:48.868  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 11:58:48.868  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:58:48.868  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-21 11:58:48.869  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:48.869  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:58:48.869  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 11:58:48.870  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:58:48.870  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.871  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 11:58:48.871  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.871  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:48.871  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:48.871  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:48.871  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:58:48.871  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 11:58:48.873  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:48.873  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:48.873  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-21 11:58:48.873  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.873  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.873  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.873  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.873  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b53b98a removed from the list
09-21 11:58:48.873  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.873  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fea3bfb removed from the list
09-21 11:58:48.873  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:48.873  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.874  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.874  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.875  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:48.875  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.875  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.875  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fea3bfb not in the list
09-21 11:58:48.876  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.876  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.877  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.877  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:48.877  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.877  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53be456 removed from the list
09-21 11:58:48.877  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.877  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.877  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.877  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.878  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd9ae71 removed from the list
09-21 11:58:48.878  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.878  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a9efe2 added. We now have 2 listener(s)
,09-21 11:58:48.880  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-21 11:58:48.880  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.880  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.880  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.880  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 11:58:48.880  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.880  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13e2f73 added. We now have 9 listener(s)
09-21 11:58:48.881  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-21 11:58:48.881  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 11:58:48.885  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:48.886  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:58:48.886  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:48.888  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:48.890  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:48.890  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-21 11:58:48.890  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.891  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@baebaa9 added. We now have 3 listener(s)
09-21 11:58:48.892  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 11:58:48.892  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.892  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.892  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.892  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.892  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:58:48.892  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.892  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfb282e added. We now have 10 listener(s)
09-21 11:58:48.892  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.892  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:48.893  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:48.893  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.893  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-21 11:58:48.893  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:58:48.893  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:48.893  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-21 11:58:48.897  5538  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 11:58:48.897  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 11:58:48.897  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:58:48.897  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.897  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.897  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 11:58:48.900  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 11:58:48.901  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:58:48.901  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 11:58:48.902  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 11:58:48.902  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.904  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-21 11:58:48.905  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:58:48.905  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-21 11:58:48.905  5538  5584 D BluetoothAdapter: STATE_ON
09-21 11:58:48.906  5779  5789 D BtGatt.GattService: registerClient() - UUID=28426fd9-43e8-4e40-b1b3-28e929cc95b9
,09-21 11:58:48.907  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=28426fd9-43e8-4e40-b1b3-28e929cc95b9, clientIf=5
,09-21 11:58:48.907  5538  5549 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-21 11:58:48.908  5779  5807 D BtGatt.GattService: start scan with filters
09-21 11:58:48.910  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-21 11:58:48.910  5779  5798 D BtGatt.ScanManager: handling starting scan
09-21 11:58:48.910  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:58:48.910  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:58:48.910  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 11:58:48.912  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 11:58:48.912  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:58:48.912  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-21 11:58:48.913  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-21 11:58:48.915  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:48.915  5538  5584 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-21 11:58:48.915  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:48.915  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:48.915  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:48.915  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.915  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 11:58:48.915  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:58:48.915  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.915  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a9efe2 removed from the list
09-21 11:58:48.915  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.915  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13e2f73 removed from the list
09-21 11:58:48.915  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:48.915  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.916  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.916  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-21 11:58:48.916  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.916  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.916  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 11:58:48.916  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.917  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.917  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13e2f73 not in the list
09-21 11:58:48.917  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:58:48.917  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 11:58:48.917  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:58:48.917  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 11:58:48.917  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-21 11:58:48.917  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 11:58:48.917  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.917  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 11:58:48.917  5538  5584 D BluetoothAdapter: STATE_ON
09-21 11:58:48.918  5779  5807 D BtGatt.GattService: stopScan() - queue size =1
09-21 11:58:48.919  5779  5808 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:58:48.919  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:58:48.919  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 11:58:48.919  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-21 11:58:48.919  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:58:48.919  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 11:58:48.921  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-21 11:58:48.921  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.921  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:58:48.921  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 11:58:48.921  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:48.921  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:58:48.922  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-21 11:58:48.922  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:58:48.922  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.923  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.923  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:48.923  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.923  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:48.923  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dfb282e removed from the list
09-21 11:58:48.923  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.923  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:48.923  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.923  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:48.923  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.923  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.923  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@baebaa9 removed from the list
09-21 11:58:48.924  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.924  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@215993a added. We now have 2 listener(s)
09-21 11:58:48.926  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.926  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.926  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: s,etIdentityString: 
09-21 11:58:48.926  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.926  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4be19eb added. We now have 9 listener(s)
09-21 11:58:48.926  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.927  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 11:58:48.929  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:48.930  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 11:58:48.930  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:48.933  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:48.934  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-21 11:58:48.935  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.937  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-21 11:58:48.937  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:58:48.937  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.937  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2215e1 added. We now have 3 listener(s)
09-21 11:58:48.938  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.938  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.938  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.938  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.938  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.938  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4340f06 added. We now have 10 listener(s)
,09-21 11:58:48.938  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.938  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:48.939  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-21 11:58:48.939  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-21 11:58:48.939  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-21 11:58:48.939  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-21 11:58:48.940  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.940  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 11:58:48.940  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.940  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:58:48.941  5538  5584 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-21 11:58:48.941  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-21 11:58:48.944  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:58:48.944  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.944  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-21 11:58:48.944  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-21 11:58:48.945  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-21 11:58:48.945  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-21 11:58:48.949  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-21 11:58:48.949  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.950  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-21 11:58:48.950  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-21 11:58:48.950  5538  5584 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-21 11:58:48.951  5538  5584 D BluetoothAdapter: STATE_ON
,09-21 11:58:48.954  5779  5808 D BtGatt.GattService: registerClient() - UUID=62a98bc2-32fe-4c4c-b5a1-e7bb6d848f9a
,09-21 11:58:48.954  5779  5795 D BtGatt.GattService: onClientRegistered() - UUID=62a98bc2-32fe-4c4c-b5a1-e7bb6d848f9a, clientIf=5
,09-21 11:58:48.954  5538  5548 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-21 11:58:48.955  5779  5807 D BtGatt.GattService: start scan with filters
,09-21 11:58:48.956  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-21 11:58:48.956  5779  5798 D BtGatt.ScanManager: handling starting scan
09-21 11:58:48.956  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-21 11:58:48.956  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-21 11:58:48.956  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-21 11:58:48.958  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 11:58:48.959  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-21 11:58:48.959  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-21 11:58:48.960  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-21 11:58:48.961  5779  5795 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-21 11:58:48.961  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.961  5779  5798 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-21 11:58:48.963  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-21 11:58:48.963  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:48.964  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:48.964  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.964  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.964  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-21 11:58:48.964  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.964  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@215993a removed from the list
09-21 11:58:48.964  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.964  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4be19eb removed from the list
09-21 11:58:48.964  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
,09-21 11:58:48.964  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.965  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.965  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-21 11:58:48.965  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.965  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.965  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:48.966  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.965  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-21 11:58:48.966  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.966  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.966  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4be19eb not in the list
09-21 11:58:48.966  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-21 11:58:48.966  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-21 11:58:48.966  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-21 11:58:48.966  5779  5798 D BtGatt.ScanManager: Starting BLE batch scan
09-21 11:58:48.966  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-21 11:58:48.966  5779  5798 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-21 11:58:48.966  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-21 11:58:48.966  5538  5584 D BluetoothAdapter: STATE_ON
,09-21 11:58:48.967  5779  5820 D BtGatt.GattService: stopScan() - queue size =1
09-21 11:58:48.968  5779  5790 D BtGatt.GattService: unregisterClient() - clientIf=5
09-21 11:58:48.968  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-21 11:58:48.968  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-21 11:58:48.968  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-21 11:58:48.968  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-21 11:58:48.968  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-21 11:58:48.969  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:48.969  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-21 11:58:48.969  5538  5584 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-21 11:58:48.969  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-21 11:58:48.969  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.970  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.970  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:48.970  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.971  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:48.971  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4340f06 removed from the list
09-21 11:58:48.971  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.971  5538  5538 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-21 11:58:48.971  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-21 11:58:48.971  5538  5538 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-21 11:58:48.971  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.971  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.971  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e2215e1 removed from the list
09-21 11:58:48.971  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.971  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f721592 added. We now have 2 listener(s)
09-21 11:58:48.972  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.972  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.972  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.973  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-21 11:58:48.973  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@711db63 added. We now have 9 listener(s)
09-21 11:58:48.973  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.974  5779  5795 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-21 11:58:48.974  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.974  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-21 11:58:48.977  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-21 11:58:48.979  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-21 11:58:48.979  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-21 11:58:48.981  5538  5584 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-21 11:58:48.983  5538  5584 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-21 11:58:48.983  5538  5584 D io.jxcore.node.ConnectivityMonitor: start: OK
09-21 11:58:48.983  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-21 11:58:48.983  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cea019 added. We now have 3 listener(s)
09-21 11:58:48.984  5779  5795 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-21 11:58:48.984  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.984  5779  5798 D BtGatt.ScanManager: stopping BLe Batch
09-21 11:58:48.984  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.984  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-21 11:58:48.984  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-21 11:58:48.984  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-21 11:58:48.985  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-21 11:58:48.985  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@317f8de added. We now have 10 listener(s)
09-21 11:58:48.985  5538  5584 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-21 11:58:48.985  5538  5584 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-21 11:58:48.985  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:48.985  5538  5584 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-21 11:58:48.985  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.985  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.985  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-21 11:58:48.985  5538  5538 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-21 11:58:48.985  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.985  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f721592 removed from the list
,09-21 11:58:48.985  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.985  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@711db63 removed from the list
09-21 11:58:48.985  5538  5584 D io.jxcore.node.ConnectivityMonitor: stop
09-21 11:58:48.985  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.986  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.986  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.987  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-21 11:58:48.987  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.987  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.987  5538  5584 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@711db63 not in the list
09-21 11:58:48.987  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.988  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-21 11:58:48.988  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-21 11:58:48.988  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-21 11:58:48.988  5538  5584 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-21 11:58:48.989  5538  5584 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@317f8de removed from the list
09-21 11:58:48.989  5538  5584 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-21 11:58:48.989  5538  5584 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-21 11:58:48.989  5538  5584 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-21 11:58:48.989  5779  5795 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-21 11:58:48.989  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.989  5538  5584 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-21 11:58:48.989  5538  5584 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cea019 removed from the list
09-21 11:58:48.989  5779  5798 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-21 11:58:48.990  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-21 11:58:48.990  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-21 11:58:48.990  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-21 11:58:48.990  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-21 11:58:48.990  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-21 11:58:48.990  5538  5584 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-21 11:58:48.993  5779  5795 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-21 11:58:48.993  5779  5795 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-21 11:58:48.994  5538  5838 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
,09-21 11:58:48.994  5538  5838 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
09-21 11:58:48.995  5538  5838 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-21 11:58:48.996  5538  5839 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
,09-21 11:58:48.996  5538  5839 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
09-21 11:58:48.996  5538  5839 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-21 11:58:48.999  5538  5584 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-21 11:58:48.999  5538  5584 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-21 11:58:48.999  5538  5584 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-21 11:58:48.999  5538  5584 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-21 11:58:48.999  5538  5584 D com.test.thalitest.ThaliTestRunner: Total duration: 22585 ms
,09-21 11:58:49.001  5538  5584 I jxcore-log: *Native tests were executed*
09-21 11:58:49.001  5538  5584 I jxcore-log: 
,09-21 11:58:49.001  5538  5584 I jxcore-log: Total number of executed tests:  80
09-21 11:58:49.001  5538  5584 I jxcore-log: 
09-21 11:58:49.001  5538  5584 I jxcore-log: Number of passed tests:  80
09-21 11:58:49.001  5538  5584 I jxcore-log: 
09-21 11:58:49.001  5538  5584 I jxcore-log: Number of failed tests:  0
09-21 11:58:49.001  5538  5584 I jxcore-log: 
09-21 11:58:49.002  5538  5584 I jxcore-log: Number of ignored tests:  0
09-21 11:58:49.002  5538  5584 I jxcore-log: 
09-21 11:58:49.002  5538  5584 I jxcore-log: Total duration:  22585
09-21 11:58:49.002  5538  5584 I jxcore-log: 
09-21 11:58:49.002  5538  5584 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-21 11:58:49.002  5538  5584 I jxcore-log: 
,09-21 11:58:49.005  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:49.005  5538  5584 I jxcore-log: 
09-21 11:58:49.008  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:49.008  5538  5584 I jxcore-log: 
09-21 11:58:49.009  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:49.009  5538  5584 I jxcore-log: 
09-21 11:58:49.010  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:49.010  5538  5584 I jxcore-log: 
09-21 11:58:49.012  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:49.012  5538  5584 I jxcore-log: 
09-21 11:58:49.012  5538  5538 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-21 11:58:49.014  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:49.014  5538  5584 I jxcore-log: 
09-21 11:58:49.016  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-21 11:58:49.016  5538  5584 I jxcore-log: 
09-21 11:58:49.018  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.018  5538  5584 I jxcore-log: 
09-21 11:58:49.019  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.019  5538  5584 I jxcore-log: 
09-21 11:58:49.020  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.020  5538  5584 I jxcore-log: 
09-21 11:58:49.021  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.021  5538  5584 I jxcore-log: 
09-21 11:58:49.022  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 11:58:49.022  5538  5584 I jxcore-log: 
,09-21 11:58:49.023  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.023  5538  5584 I jxcore-log: 
,09-21 11:58:49.023  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.023  5538  5584 I jxcore-log: 
,09-21 11:58:49.024  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.024  5538  5584 I jxcore-log: 
,09-21 11:58:49.025  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.025  5538  5584 I jxcore-log: 
,09-21 11:58:49.025  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.025  5538  5584 I jxcore-log: 
09-21 11:58:49.026  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.026  5538  5584 I jxcore-log: 
,09-21 11:58:49.026  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.026  5538  5584 I jxcore-log: 
,09-21 11:58:49.027  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.027  5538  5584 I jxcore-log: 
,09-21 11:58:49.028  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.028  5538  5584 I jxcore-log: 
09-21 11:58:49.028  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-21 11:58:49.028  5538  5584 I jxcore-log: 
,09-21 11:58:49.029  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.029  5538  5584 I jxcore-log: 
,09-21 11:58:49.030  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.030  5538  5584 I jxcore-log: 
,09-21 11:58:49.030  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.030  5538  5584 I jxcore-log: 
09-21 11:58:49.031  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.031  5538  5584 I jxcore-log: 
,09-21 11:58:49.032  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.032  5538  5584 I jxcore-log: 
,09-21 11:58:49.032  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.032  5538  5584 I jxcore-log: 
,09-21 11:58:49.033  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-21 11:58:49.033  5538  5584 I jxcore-log: 
,09-21 11:58:49.371  5538  5538 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 11:58:49.376  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 11:58:49.376  5538  5584 I jxcore-log: 
,09-21 11:58:49.423  5538  5538 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 11:58:49.428  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 11:58:49.428  5538  5584 I jxcore-log: 
,09-21 11:58:49.471  5538  5538 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-21 11:58:49.475  5538  5584 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-21 11:58:49.475  5538  5584 I jxcore-log: 
,09-21 11:58:49.499  5840  5840 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-21 11:58:49.505  5840  5840 D AndroidRuntime: CheckJNI is OFF
,09-21 11:58:49.534  5840  5840 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-21 11:58:49.569  5840  5840 I Radio-JNI: register_android_hardware_Radio DONE
,09-21 11:58:49.587  5840  5840 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-21 11:58:49.598   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-21 11:58:49.599   929   942 I ActivityManager: Killing 5538:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-21 11:58:49.669   929  3482 I WindowState: WIN DEATH: Window{45e3a9f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-21 11:58:49.675   929  3507 D GraphicsStats: Buffer count: 2
09-21 11:58:49.670   929  3053 D WifiService: Client connection lost with reason: 4
,09-21 11:58:49.730   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-21 11:58:49.730   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-21 11:58:49.731   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-21 11:58:49.731   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-21 11:58:49.731   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:49.731   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:49.731   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:49.731   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-21 11:58:49.732   929   942 I ActivityManager:   Force finishing activity ActivityRecord{79c9160 u0 com.test.thalitest/.MainActivity t2}
09-21 11:58:49.737   929  3661 W ActivityManager: Spurious death for ProcessRecord{71ee5c1 0:com.test.thalitest/u0a77}, curProc for 5538: null
,09-21 11:58:49.739   929   952 I art     : Starting a blocking GC Explicit
,09-21 11:58:49.744   929   947 W WindowManager: Attempted to add application window with unknown token Token{2355619 ActivityRecord{79c9160 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-21 11:58:49.745   929   947 W WindowManager: Token{2355619 ActivityRecord{79c9160 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{2355619 ActivityRecord{79c9160 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
,09-21 11:58:49.745   929   947 W WindowManager: view not successfully added to wm, removing view
09-21 11:58:49.745   929   947 W WindowManager: Exception when adding starting window
09-21 11:58:49.745   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{2ba72c0 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-21 11:58:49.745   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-21 11:58:49.745   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-21 11:58:49.745   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-21 11:58:49.745   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-21 11:58:49.745   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-21 11:58:49.745   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:49.745   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:49.745   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:49.745   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-21 11:58:49.816   929   952 I art     : Explicit concurrent mark sweep GC freed 24841(1578KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.489ms total 77.326ms
,09-21 11:58:49.836   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-21 11:58:49.839  5840  5840 I art     : System.exit called, status: 0
,09-21 11:58:49.839  5840  5840 I AndroidRuntime: VM exiting with result code 0.
,09-21 11:58:49.853   929   952 I ActivityManager: Start proc 5850:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-21 11:58:49.854   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-21 11:58:49.858   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-21 11:58:49.863  5779  5779 D BluetoothMapAppObserver: onReceive
,09-21 11:58:49.863  3565  4046 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-21 11:58:49.863  5779  5779 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-21 11:58:49.868   929  3041 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-21 11:58:49.869  3495  3495 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-21 11:58:49.899  3495  5861 I Keyboard.Facilitator.DecoderInitializer: run()
,09-21 11:58:49.902  3483  5862 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-21 11:58:49.909  3636  3636 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-21 11:58:49.926  3725  3725 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-21 11:58:49.926  3725  3725 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
09-21 11:58:49.927   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-21 11:58:49.930  3495  5861 I Decoder : createOrResetDecoder
09-21 11:58:49.940   445   445 W kworker/5:1: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 11:58:49.948  3966  5869 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-21 11:58:49.948  3966  5869 D AccountUtils: Clearing selected account for com.test.thalitest
09-21 11:58:49.947   445   445 W kworker/5:1: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 11:58:49.957   445   445 W kworker/5:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-21 11:58:49.957  3674  3790 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-21 11:58:49.971   929  3279 I ActivityManager: Start proc 5870:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-21 11:58:49.972  3674  3790 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-21 11:58:49.972  3674  3790 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3674
09-21 11:58:49.972  3674  3790 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:49.972  3674  3790 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 11:58:49.977   929  3665 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-21 11:58:49.978  3483  3509 E SQLiteLog: (14) cannot open file at line 31278 of [2ef4f3a5b1]
09-21 11:58:49.978  3483  3509 E SQLiteLog: (14) os_unix.c:31278: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj99383097C) - 
09-21 11:58:49.979   929  5880 E DropBoxManagerService: Can't write: system_app_crash
09-21 11:58:49.979   929  5880 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop118.tmp: open failed: EROFS (Read-only file system)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-21 11:58:49.979   929  5880 E DropBoxManagerService: 	... 5 more
,09-21 11:58:49.984  3674  3790 I Process : Sending signal. PID: 3674 SIG: 9
,09-21 11:58:50.019  3725  3725 I ConfigService: onCreate
,09-21 11:58:50.022  3725  5885 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-21 11:58:50.022  3725  5885 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-21 11:58:50.022  3725  5885 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-21 11:58:50.024  3725  5885 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-21 11:58:50.033  3966  5869 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-21 11:58:50.058  3495  5861 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-21 11:58:50.064  3966  5869 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:50.064  3966  5869 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:50.065  3966  5869 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-21 11:58:50.066  3966  5869 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-21 11:58:50.099  3483  3509 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-21 11:58:50.099  3483  3509 E AndroidRuntime: Process: android.process.acore, PID: 3483
09-21 11:58:50.099  3483  3509 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:50.099  3483  3509 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-21 11:58:50.125   929  3665 D GraphicsStats: Buffer count: 1
,09-21 11:58:50.125   929  3745 I WindowState: WIN DEATH: Window{3621a66 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-21 11:58:50.129  3483  3509 I Process : Sending signal. PID: 3483 SIG: 9
,09-21 11:58:50.130   929  3665 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3674) has died
,09-21 11:58:50.131   929  3665 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-21 11:58:50.133   929  3665 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-21 11:58:50.151   929   942 I ActivityManager: Start proc 5891:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-21 11:58:50.167  3966  5896 I GMPM-SVC: App measurement is starting up
,09-21 11:58:50.178  3966  5896 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-21 11:58:50.179  3966  5896 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-21 11:58:50.201  5891  5891 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:50.201  5891  5891 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-21 11:58:50.202  5891  5891 D AndroidRuntime: Shutting down VM
,09-21 11:58:50.208  5891  5891 E AndroidRuntime: FATAL EXCEPTION: main
09-21 11:58:50.208  5891  5891 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5891
09-21 11:58:50.208  5891  5891 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-21 11:58:50.208  5891  5891 E AndroidRuntime: 	... 10 more
09-21 11:58:50.211   929  3224 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-21 11:58:50.211  5891  5891 I Process : Sending signal. PID: 5891 SIG: 9
,09-21 11:58:50.221   929  3665 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5891) has died
,09-21 11:58:50.222   929  3665 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-21 11:58:50.237   929   942 I ActivityManager: Start proc 5908:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-21 11:58:50.287  5908  5908 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:50.287  5908  5908 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-21 11:58:50.287  5908  5908 D AndroidRuntime: Shutting down VM
,09-21 11:58:50.294  5908  5908 E AndroidRuntime: FATAL EXCEPTION: main
09-21 11:58:50.294  5908  5908 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 5908
09-21 11:58:50.294  5908  5908 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-21 11:58:50.294  5908  5908 E AndroidRuntime: 	... 10 more
09-21 11:58:50.296   929  3672 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-21 11:58:50.297  5908  5908 I Process : Sending signal. PID: 5908 SIG: 9
,09-21 11:58:50.313   929  3526 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 5908) has died
,09-21 11:58:50.315   929  3526 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-21 11:58:50.330   929   942 I ActivityManager: Start proc 5921:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-21 11:58:50.339   384   472 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
