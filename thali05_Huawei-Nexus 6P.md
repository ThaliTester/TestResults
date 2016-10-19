#### Test 90009723439aaa5_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
10-19 10:25:37.972   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:38.477  5618  5618 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
10-19 10:25:38.483  5618  5618 D AndroidRuntime: CheckJNI is OFF
10-19 10:25:38.509  5618  5618 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
10-19 10:25:38.542  5618  5618 I Radio-JNI: register_android_hardware_Radio DONE
10-19 10:25:38.556  5618  5618 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
10-19 10:25:38.569   932  3884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
10-19 10:25:38.616   932  3884 I ActivityManager: Start proc 5627:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
10-19 10:25:38.635  5618  5618 D AndroidRuntime: Shutting down VM
,10-19 10:25:38.964   932  3593 I WindowManager: Screenshot max retries 4 of Token{82ccdeb ActivityRecord{ffe9d3a u0 com.test.thalitest/.MainActivity t2}} appWin=Window{8f79992 u0 Starting com.test.thalitest} drawState=4
,10-19 10:25:38.973   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:39.059  5627  5627 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,10-19 10:25:39.088  5627  5627 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,10-19 10:25:39.118  5627  5627 I LibraryLoader: Time to load native libraries: 27 ms (timestamps 501-528)
,10-19 10:25:39.118  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
,10-19 10:25:39.141  5627  5627 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5bc0ddc}
,10-19 10:25:39.141  5627  5627 I LibraryLoader: Expected native library version number "",actual native library version number ""
10-19 10:25:39.141  5627  5627 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,10-19 10:25:39.145  5627  5627 I BrowserStartupController: Initializing chromium process, singleProcess=true
,10-19 10:25:39.146  5627  5627 E SysUtils: ApplicationContext is null in ApplicationStatus
,10-19 10:25:39.184  5627  5627 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,10-19 10:25:39.194  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,10-19 10:25:39.194  5627  5627 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
10-19 10:25:39.194  5627  5627 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
10-19 10:25:39.194  5627  5627 I Adreno  : Build Date                       : 12/06/15
10-19 10:25:39.194  5627  5627 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
10-19 10:25:39.194  5627  5627 I Adreno  : Local Branch                     : mybranch17112971
10-19 10:25:39.194  5627  5627 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
10-19 10:25:39.194  5627  5627 I Adreno  : Remote Branch                    : NONE
10-19 10:25:39.194  5627  5627 I Adreno  : Reconstruct Branch               : NOTHING
,10-19 10:25:39.250   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2180d51:true
,10-19 10:25:39.281   734   734 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[34827]" dev="sockfs" ino=34827 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-19 10:25:39.281   734   734 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[34827]" dev="sockfs" ino=34827 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-19 10:25:39.295  5627  5627 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,10-19 10:25:39.305  5627  5627 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,10-19 10:25:39.334  5627  5664 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,10-19 10:25:39.331   734   734 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33081]" dev="sockfs" ino=33081 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
10-19 10:25:39.331   734   734 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33081]" dev="sockfs" ino=33081 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,10-19 10:25:39.338  3163  3163 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[34154]" dev="sockfs" ino=34154 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-19 10:25:39.338  3163  3163 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[34154]" dev="sockfs" ino=34154 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,10-19 10:25:39.343  5627  5651 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,10-19 10:25:39.375  5627  5664 I OpenGLRenderer: Initialized EGL, version 1.4
,10-19 10:25:39.444   932   950 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +478ms (total +854ms)
,10-19 10:25:39.473  5627  5627 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5627
,10-19 10:25:39.560  5627  5627 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,10-19 10:25:39.804  5627  5667 D jxcore_app_log: JniHelper::setJavaVM(0xf54fc000), pthread_self() = -581170896
,10-19 10:25:39.811  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
10-19 10:25:39.811  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
10-19 10:25:39.811  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
10-19 10:25:39.811  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
10-19 10:25:39.811  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,10-19 10:25:39.811  5627  5667 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69bb8d2 added. We now have 1 listener(s)
,10-19 10:25:39.817  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
10-19 10:25:39.817  5627  5667 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,10-19 10:25:39.818  5627  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-19 10:25:39.818  5627  5667 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
10-19 10:25:39.821  5627  5667 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d620c59 added. We now have 1 listener(s)
10-19 10:25:39.821  5627  5667 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-19 10:25:39.829   932  2962 D WifiService: New client listening to asynchronous messages
,10-19 10:25:39.829  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-19 10:25:39.829  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,10-19 10:25:39.830  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,10-19 10:25:39.830  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
10-19 10:25:39.830  5627  5667 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,10-19 10:25:39.832  5627  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:25:39.832  5627  5667 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,10-19 10:25:39.840  5627  5667 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-19 10:25:39.840  5627  5667 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-19 10:25:39.840  5627  5667 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
10-19 10:25:39.840  5627  5667 D io.jxcore.node.ConnectivityMonitor: start: OK
10-19 10:25:39.841  5627  5667 I io.jxcore.node.LifeCycleMonitor: start: OK
,10-19 10:25:39.973   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:39.991  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:25:39.996  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:25:39.998  5627  5627 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,10-19 10:25:40.404  5627  5636 I art     : Background sticky concurrent mark sweep GC freed 77831(7MB) AllocSpace objects, 17(1088KB) LOS objects, 24% free, 24MB/32MB, paused 1.451ms total 323.315ms
,10-19 10:25:40.695  5627  5636 I art     : Background partial concurrent mark sweep GC freed 59628(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.513ms total 117.669ms
,10-19 10:25:40.816  5627  5673 W jxcore-log: Initializing JXcore engine
,10-19 10:25:40.816  5627  5673 W jxcore-log: JXcore engine is ready
,10-19 10:25:40.838  5673  5673 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1552 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,10-19 10:25:40.838  5673  5673 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13722]" dev="sockfs" ino=13722 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,10-19 10:25:40.838  5673  5673 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5886 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,10-19 10:25:40.838  5673  5673 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31415]" dev="sockfs" ino=31415 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,10-19 10:25:40.848  5627  5673 W jxcore-log: Starting JXcore engine
,10-19 10:25:40.899  5627  5673 W jxcore-log: Platform android
10-19 10:25:40.899  5627  5673 W jxcore-log: 
,10-19 10:25:40.899  5627  5673 W jxcore-log: Process ARCH arm
10-19 10:25:40.899  5627  5673 W jxcore-log: 
,10-19 10:25:40.974   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:41.097  5627  5673 I jxcore-log: JXcore Cordova bridge is ready!
10-19 10:25:41.097  5627  5673 I jxcore-log: 
,10-19 10:25:41.097  5627  5673 W jxcore-log: JXcore engine is started
,10-19 10:25:41.106  5627  5667 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,10-19 10:25:41.114  5627  5627 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,10-19 10:25:41.975   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:42.976   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,10-19 10:25:51.110  5627  5673 I jxcore-log: 2016-10-19 14:25:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
10-19 10:25:51.110  5627  5673 I jxcore-log: 
,10-19 10:25:51.112  5627  5673 I jxcore-log: 2016-10-19 14:25:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
10-19 10:25:51.112  5627  5673 I jxcore-log: 
,10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-19 10:25:51.116  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-19 10:25:51.117  5627  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-19 10:25:51.119  5627  5673 I jxcore-log: 2016-10-19 14:25:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
10-19 10:25:51.119  5627  5673 I jxcore-log: 
,10-19 10:25:51.120  5627  5673 I jxcore-log: 2016-10-19 14:25:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
10-19 10:25:51.120  5627  5673 I jxcore-log: 
,10-19 10:25:51.385  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-19 10:25:51.385  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@67fb402 added. We now have 2 listener(s)
,10-19 10:25:51.386  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:25:51.386  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-19 10:25:51.387  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-19 10:25:51.387  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-19 10:25:51.387  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8c47113 added. We now have 2 listener(s)
,10-19 10:25:51.387  5627  5673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-19 10:25:51.388  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-19 10:25:51.391  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-19 10:25:51.395  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,10-19 10:25:51.396  5627  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-19 10:25:51.396  5627  5673 D io.jxcore.node.ConnectivityMonitor: start: OK
10-19 10:25:51.396  5627  5673 D ExecuteNativeTests: Running unit tests
,10-19 10:25:51.399  5627  5673 D BluetoothAdapter: enable(): BT is already enabled..!
,10-19 10:25:51.401   932  3167 D WifiService: setWifiEnabled: true pid=5627, uid=10077
10-19 10:25:51.401   932  3167 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-19 10:25:51.402  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:25:51.406  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:25:52.978   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:53.979   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:54.981   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:55.982   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:56.984   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:25:57.985   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,10-19 10:26:00.637   932  2958 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,10-19 10:26:01.407  5627  5673 I com.test.thalitest.ThaliTestRunner: Running UT
,10-19 10:26:01.476  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,10-19 10:26:01.476  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a65aa2d added. We now have 3 listener(s)
10-19 10:26:01.477  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:01.477  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,10-19 10:26:01.477  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-19 10:26:01.478  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,10-19 10:26:01.478  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f15b62 added. We now have 3 listener(s)
10-19 10:26:01.478  5627  5673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-19 10:26:01.479  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-19 10:26:01.482  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-19 10:26:01.486  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-19 10:26:01.487  5627  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-19 10:26:01.488  5627  5673 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-19 10:26:01.491  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
10-19 10:26:01.491  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-19 10:26:01.491  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:01.491  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:01.491  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:01.492  5627  5673 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
10-19 10:26:01.492  5627  5673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-19 10:26:01.492  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-19 10:26:01.492  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-19 10:26:01.492  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,10-19 10:26:01.492  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-19 10:26:01.493  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
10-19 10:26:01.494  5627  5673 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
10-19 10:26:01.495  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
10-19 10:26:01.496  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:01.497  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
10-19 10:26:01.497  5627  5673 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-19 10:26:01.503  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:01.504  5627  5673 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-19 10:26:01.504  5627  5673 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
10-19 10:26:01.504  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
10-19 10:26:01.504  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:01.504  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,10-19 10:26:01.505  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-19 10:26:01.505  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:01.505  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-19 10:26:01.506  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-19 10:26:01.506  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-19 10:26:01.506  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-19 10:26:01.506  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-19 10:26:01.506  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-19 10:26:01.506  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:01.506  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-19 10:26:01.506  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,10-19 10:26:01.508  5627  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-19 10:26:01.509  5627  5673 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-19 10:26:01.509  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-19 10:26:01.512  5627  5675 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:01.512  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-19 10:26:01.513  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-19 10:26:01.513  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-19 10:26:01.515  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-19 10:26:01.516  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:01.511  4831  4831 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[34845]" dev="sockfs" ino=34845 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:01.511  4831  4831 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[34845]" dev="sockfs" ino=34845 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:01.516  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
10-19 10:26:01.516  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:01.516  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-19 10:26:01.516  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-19 10:26:01.516  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:01.517  5627  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-19 10:26:01.517  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:01.519  4613  4831 D BtGatt.GattService: registerClient() - UUID=7ad3a641-8d36-4307-95ef-5262bc5308c8
,10-19 10:26:01.521  4613  4675 D BtGatt.GattService: onClientRegistered() - UUID=7ad3a641-8d36-4307-95ef-5262bc5308c8, clientIf=5
,10-19 10:26:01.521  5627  5638 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-19 10:26:01.524  4613  4680 D BtGatt.AdvertiseManager: message : 0
,10-19 10:26:01.528  4613  4680 D BtGatt.AdvertiseManager: starting multi advertising
,10-19 10:26:01.545  4613  4675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-19 10:26:01.553  4613  4675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-19 10:26:01.554  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-19 10:26:01.555  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
,10-19 10:26:01.555  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-19 10:26:01.555  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-19 10:26:01.555  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-19 10:26:01.555  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,10-19 10:26:01.556  5627  5673 I io.jxcore.node.ConnectionHelper: start: OK
,10-19 10:26:01.556  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-19 10:26:01.557  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-19 10:26:01.557  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-19 10:26:01.557  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-19 10:26:01.558  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,10-19 10:26:01.558  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:01.558  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-19 10:26:01.558  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-19 10:26:01.558  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-19 10:26:01.558  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-19 10:26:01.562  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-19 10:26:01.562  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-19 10:26:02.059  5627  5673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-19 10:26:02.060  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,10-19 10:26:02.060  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
10-19 10:26:02.060  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
10-19 10:26:02.060  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
10-19 10:26:02.060  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
10-19 10:26:02.060  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
10-19 10:26:02.060  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
10-19 10:26:02.061  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,10-19 10:26:02.062  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
10-19 10:26:02.063  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
10-19 10:26:02.063  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
10-19 10:26:02.063  5627  5673 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,10-19 10:26:02.063  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-19 10:26:02.063  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-19 10:26:02.063  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-19 10:26:02.063  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-19 10:26:02.064  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-19 10:26:02.064  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-19 10:26:02.064  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-19 10:26:02.064  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-19 10:26:02.064  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,10-19 10:26:02.064  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-19 10:26:02.065  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-19 10:26:02.065  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-19 10:26:02.065  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-19 10:26:02.065  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-19 10:26:02.066  5627  5675 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-19 10:26:02.067  5627  5673 D BluetoothAdapter: STATE_ON
,10-19 10:26:02.067  5627  5673 D BluetoothLeScanner: could not find callback wrapper
10-19 10:26:02.067  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-19 10:26:02.068  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-19 10:26:02.067  5627  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-19 10:26:02.068  5627  5675 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-19 10:26:02.069  4613  4680 D BtGatt.AdvertiseManager: message : 1
10-19 10:26:02.070  4613  4680 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-19 10:26:02.083  4613  4675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-19 10:26:02.083  4613  4675 D BtGatt.GattService: Client app is not null!
,10-19 10:26:02.085  4613  4832 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-19 10:26:02.086  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-19 10:26:02.086  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-19 10:26:02.086  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-19 10:26:02.087  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-19 10:26:02.087  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:02.087  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-19 10:26:02.087  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-19 10:26:02.087  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-19 10:26:02.087  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-19 10:26:02.088  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-19 10:26:02.089  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-19 10:26:02.089  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-19 10:26:02.089  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-19 10:26:02.091  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-19 10:26:02.091  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-19 10:26:02.092  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-19 10:26:02.093  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:02.093  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:02.093  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,10-19 10:26:02.093  5627  5673 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-19 10:26:02.093  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-19 10:26:02.093  5627  5673 V io.jxcore.node.ConnectivityMonitor: start: Already started
,10-19 10:26:02.093  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-19 10:26:02.093  5627  5673 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
10-19 10:26:02.093  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
10-19 10:26:02.094  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:02.094  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-19 10:26:02.094  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-19 10:26:02.094  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:02.096  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,10-19 10:26:02.098  4832  4832 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32123]" dev="sockfs" ino=32123 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-19 10:26:02.098  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-19 10:26:02.098  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-19 10:26:02.098  5627  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-19 10:26:02.098  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-19 10:26:02.099  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-19 10:26:02.100  5627  5678 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:02.099  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-19 10:26:02.098  4832  4832 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32123]" dev="sockfs" ino=32123 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:02.100  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-19 10:26:02.100  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:02.100  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-19 10:26:02.102  5627  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-19 10:26:02.110  5627  5673 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-19 10:26:02.110  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-19 10:26:02.115  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-19 10:26:02.116  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-19 10:26:02.116  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-19 10:26:02.119  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,10-19 10:26:02.119  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:02.120  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
,10-19 10:26:02.120  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:02.120  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-19 10:26:02.120  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-19 10:26:02.120  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:02.121  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:02.124  4613  4832 D BtGatt.GattService: registerClient() - UUID=8704807a-97a2-4a10-a247-6eeab79a897b
10-19 10:26:02.124  4613  4675 D BtGatt.GattService: onClientRegistered() - UUID=8704807a-97a2-4a10-a247-6eeab79a897b, clientIf=5
10-19 10:26:02.125  5627  5637 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,10-19 10:26:02.126  4613  4680 D BtGatt.AdvertiseManager: message : 0
,10-19 10:26:02.129  4613  4680 D BtGatt.AdvertiseManager: starting multi advertising
,10-19 10:26:02.141  4613  4675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-19 10:26:02.148  4613  4675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-19 10:26:02.149  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-19 10:26:02.149  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-19 10:26:02.149  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-19 10:26:02.149  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-19 10:26:02.150  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,10-19 10:26:02.151  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-19 10:26:02.153  5627  5673 I io.jxcore.node.ConnectionHelper: start: OK
10-19 10:26:02.153  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,10-19 10:26:02.154  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-19 10:26:02.154  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-19 10:26:02.154  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-19 10:26:02.154  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-19 10:26:02.154  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:02.154  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-19 10:26:02.154  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-19 10:26:02.154  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,10-19 10:26:02.154  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-19 10:26:02.157  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-19 10:26:02.157  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-19 10:26:02.657  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
10-19 10:26:02.658  5627  5673 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,10-19 10:26:02.658  5627  5673 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-19 10:26:02.658  5627  5673 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
10-19 10:26:02.658  5627  5673 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
10-19 10:26:02.658  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
10-19 10:26:02.659  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-19 10:26:02.659  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
10-19 10:26:02.661  4613  4680 D BtGatt.AdvertiseManager: message : 1
10-19 10:26:02.663  4613  4680 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-19 10:26:02.676  4613  4675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-19 10:26:02.676  4613  4675 D BtGatt.GattService: Client app is not null!
10-19 10:26:02.677  4613  4627 D BtGatt.GattService: unregisterClient() - clientIf=5
10-19 10:26:02.678  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-19 10:26:02.678  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-19 10:26:02.678  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,10-19 10:26:02.678  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-19 10:26:02.678  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-19 10:26:02.678  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:02.679  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
10-19 10:26:02.679  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:02.679  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-19 10:26:02.679  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-19 10:26:02.679  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:02.681  5627  5673 D BluetoothAdapter: STATE_ON
,10-19 10:26:02.684  4613  4627 D BtGatt.GattService: registerClient() - UUID=f833ddcb-e90a-4cf6-8372-d0b5476b84f9
10-19 10:26:02.685  4613  4675 D BtGatt.GattService: onClientRegistered() - UUID=f833ddcb-e90a-4cf6-8372-d0b5476b84f9, clientIf=5
,10-19 10:26:02.685  5627  5637 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-19 10:26:02.687  4613  4680 D BtGatt.AdvertiseManager: message : 0
,10-19 10:26:02.690  4613  4680 D BtGatt.AdvertiseManager: starting multi advertising
,10-19 10:26:02.703  4613  4675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-19 10:26:02.710  4613  4675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-19 10:26:02.711  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-19 10:26:02.711  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
,10-19 10:26:02.711  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-19 10:26:02.712  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
,10-19 10:26:02.712  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-19 10:26:02.712  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-19 10:26:02.712  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-19 10:26:02.712  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,10-19 10:26:02.712  5627  5673 I io.jxcore.node.ConnectionHelper: start: OK
10-19 10:26:02.712  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-19 10:26:02.712  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
,10-19 10:26:02.712  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-19 10:26:02.713  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-19 10:26:02.713  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:02.713  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-19 10:26:02.713  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-19 10:26:02.713  5627  5673 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
10-19 10:26:02.713  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
10-19 10:26:02.713  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-19 10:26:02.714  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-19 10:26:02.714  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-19 10:26:02.714  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-19 10:26:02.714  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-19 10:26:02.714  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-19 10:26:02.714  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-19 10:26:02.714  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-19 10:26:02.714  5627  5678 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-19 10:26:02.714  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-19 10:26:02.714  5627  5678 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-19 10:26:02.714  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-19 10:26:02.714  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-19 10:26:02.714  5627  5678 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-19 10:26:02.714  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-19 10:26:02.714  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-19 10:26:02.715  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:02.715  5627  5673 D BluetoothLeScanner: could not find callback wrapper
10-19 10:26:02.715  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-19 10:26:02.715  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-19 10:26:02.716  4613  4680 D BtGatt.AdvertiseManager: message : 1
10-19 10:26:02.717  4613  4680 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-19 10:26:02.724  4613  4675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
10-19 10:26:02.724  4613  4675 D BtGatt.GattService: Client app is not null!
10-19 10:26:02.725  4613  4627 D BtGatt.GattService: unregisterClient() - clientIf=5
10-19 10:26:02.726  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
10-19 10:26:02.726  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-19 10:26:02.726  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-19 10:26:02.726  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-19 10:26:02.726  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:02.726  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-19 10:26:02.726  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-19 10:26:02.726  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-19 10:26:02.726  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-19 10:26:02.727  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-19 10:26:02.728  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-19 10:26:02.728  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-19 10:26:02.728  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-19 10:26:02.729  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
10-19 10:26:02.729  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-19 10:26:02.729  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-19 10:26:02.729  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-19 10:26:02.730  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:02.730  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:02.730  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
10-19 10:26:02.731  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
10-19 10:26:02.731  5627  5673 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
10-19 10:26:02.733  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
10-19 10:26:02.733  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-19 10:26:02.734  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
10-19 10:26:02.735  5627  5673 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
10-19 10:26:02.735  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
10-19 10:26:02.736  5627  5673 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
10-19 10:26:02.736  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
10-19 10:26:02.737  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-19 10:26:02.737  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:02.737  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:02.737  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:02.737  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-19 10:26:02.737  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-19 10:26:02.737  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-19 10:26:02.737  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-19 10:26:02.738  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
10-19 10:26:02.738  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:02.738  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:02.738  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
10-19 10:26:02.739  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
10-19 10:26:02.739  5627  5673 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
10-19 10:26:02.739  5627  5673 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
10-19 10:26:02.742  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
10-19 10:26:02.742  5627  5673 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
10-19 10:26:02.743  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
10-19 10:26:02.744  5627  5673 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
10-19 10:26:02.744  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
10-19 10:26:02.745  5627  5673 E io.jxcore.node.ConnectionModel: addConnectionThread: A matching thread for outgoing connection already exists
10-19 10:26:02.745  5627  5673 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
10-19 10:26:02.745  5627  5673 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
10-19 10:26:02.745  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-19 10:26:02.745  5627  5673 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
10-19 10:26:02.745  5627  5673 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-19 10:26:02.745  5627  5673 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
10-19 10:26:02.745  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-19 10:26:02.745  5627  5673 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
10-19 10:26:02.745  5627  5673 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
10-19 10:26:02.745  5627  5673 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
10-19 10:26:02.745  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,10-19 10:26:02.745  5627  5673 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
10-19 10:26:02.746  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
10-19 10:26:02.746  5627  5673 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
10-19 10:26:02.746  5627  5673 V io.jxcore.node.ConnectivityMonitor: start: Already started
10-19 10:26:02.746  5627  5673 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
10-19 10:26:02.746  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
10-19 10:26:02.746  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:02.747  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-19 10:26:02.747  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-19 10:26:02.747  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:02.747  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-19 10:26:02.748  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-19 10:26:02.748  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-19 10:26:02.748  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-19 10:26:02.748  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-19 10:26:02.748  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
10-19 10:26:02.748  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:02.748  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-19 10:26:02.748  5627  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-19 10:26:02.749  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-19 10:26:02.749  5627  5682 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:02.751  5627  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-19 10:26:02.748  4627  4627 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31465]" dev="sockfs" ino=31465 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:02.748  4627  4627 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31465]" dev="sockfs" ino=31465 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:02.751  5627  5673 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-19 10:26:02.751  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-19 10:26:02.755  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-19 10:26:02.756  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-19 10:26:02.756  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-19 10:26:02.758  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-19 10:26:02.758  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:02.758  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
10-19 10:26:02.758  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:02.758  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-19 10:26:02.758  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-19 10:26:02.758  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:02.759  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:02.762  4613  4627 D BtGatt.GattService: registerClient() - UUID=8fa04599-8650-45dc-a483-7bf08a225bfe
10-19 10:26:02.762  4613  4675 D BtGatt.GattService: onClientRegistered() - UUID=8fa04599-8650-45dc-a483-7bf08a225bfe, clientIf=5
10-19 10:26:02.763  5627  5638 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-19 10:26:02.764  4613  4680 D BtGatt.AdvertiseManager: message : 0
10-19 10:26:02.766  4613  4680 D BtGatt.AdvertiseManager: starting multi advertising
10-19 10:26:02.775  4613  4675 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
10-19 10:26:02.781  4613  4675 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
10-19 10:26:02.781  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-19 10:26:02.782  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-19 10:26:02.782  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-19 10:26:02.782  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-19 10:26:02.782  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-19 10:26:02.783  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-19 10:26:02.784  5627  5673 I io.jxcore.node.ConnectionHelper: start: OK
10-19 10:26:02.784  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:02.784  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-19 10:26:02.784  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-19 10:26:02.784  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-19 10:26:02.784  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-19 10:26:02.785  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:02.785  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-19 10:26:02.785  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-19 10:26:02.785  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-19 10:26:02.785  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
10-19 10:26:02.788  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-19 10:26:02.788  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-19 10:26:03.286  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-19 10:26:03.286  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-19 10:26:03.286  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-19 10:26:03.286  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-19 10:26:03.287  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-19 10:26:03.287  5627  5682 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-19 10:26:03.287  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-19 10:26:03.287  5627  5682 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-19 10:26:03.287  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-19 10:26:03.287  5627  5682 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-19 10:26:03.288  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-19 10:26:03.288  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a65aa2d removed from the list
10-19 10:26:03.288  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-19 10:26:03.288  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-19 10:26:03.288  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-19 10:26:03.288  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-19 10:26:03.288  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-19 10:26:03.288  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-19 10:26:03.288  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,10-19 10:26:03.289  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
10-19 10:26:03.289  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-19 10:26:03.292  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:03.293  5627  5673 D BluetoothLeScanner: could not find callback wrapper
10-19 10:26:03.293  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,10-19 10:26:03.293  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-19 10:26:03.295  4613  4680 D BtGatt.AdvertiseManager: message : 1
10-19 10:26:03.297  4613  4680 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-19 10:26:03.310  4613  4675 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-19 10:26:03.310  4613  4675 D BtGatt.GattService: Client app is not null!
10-19 10:26:03.312  4613  4625 D BtGatt.GattService: unregisterClient() - clientIf=5
,10-19 10:26:03.313  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-19 10:26:03.313  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-19 10:26:03.313  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-19 10:26:03.313  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-19 10:26:03.313  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:03.313  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-19 10:26:03.313  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-19 10:26:03.314  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-19 10:26:03.314  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
10-19 10:26:03.316  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-19 10:26:03.316  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,10-19 10:26:03.316  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-19 10:26:03.319  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-19 10:26:03.321  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f15b62 removed from the list
,10-19 10:26:03.322  5627  5673 D io.jxcore.node.ConnectivityMonitor: stop
10-19 10:26:03.322  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-19 10:26:03.322  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:03.322  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:03.322  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-19 10:26:03.823  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-19 10:26:08.326  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,10-19 10:26:08.330  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-19 10:26:08.330  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-19 10:26:08.332  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-19 10:26:08.334  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,10-19 10:26:08.334  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,10-19 10:26:08.334  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
10-19 10:26:08.335  5627  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-19 10:26:08.336  5627  5683 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-19 10:26:08.337  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-19 10:26:08.337  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
10-19 10:26:08.337  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,10-19 10:26:08.335  4832  4832 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32143]" dev="sockfs" ino=32143 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:08.340  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
10-19 10:26:08.338  4832  4832 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32143]" dev="sockfs" ino=32143 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:08.340  5627  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-19 10:26:08.342  5627  5673 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
10-19 10:26:08.343  5627  5673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
10-19 10:26:08.343  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
10-19 10:26:08.344  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-19 10:26:08.344  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
10-19 10:26:08.345  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,10-19 10:26:08.352  5627  5673 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,10-19 10:26:08.353  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-19 10:26:08.353  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,10-19 10:26:08.353  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-19 10:26:08.353  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-19 10:26:08.353  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-19 10:26:08.353  5627  5683 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-19 10:26:08.353  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-19 10:26:08.353  5627  5683 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,10-19 10:26:08.354  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-19 10:26:08.354  5627  5683 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
10-19 10:26:08.354  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-19 10:26:08.354  5627  5673 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a65aa2d not in the list
10-19 10:26:08.354  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-19 10:26:08.354  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
10-19 10:26:08.354  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-19 10:26:08.354  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-19 10:26:08.354  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-19 10:26:08.354  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-19 10:26:08.354  5627  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-19 10:26:08.354  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,10-19 10:26:08.356  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-19 10:26:08.356  5627  5673 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f15b62 not in the list
10-19 10:26:08.356  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:08.356  5627  5673 D io.jxcore.node.ConnectivityMonitor: stop
10-19 10:26:08.356  5627  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-19 10:26:08.356  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:08.356  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-19 10:26:08.356  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-19 10:26:08.357  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
10-19 10:26:08.358  5627  5673 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
10-19 10:26:08.358  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-19 10:26:08.358  5627  5673 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,10-19 10:26:08.358  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
10-19 10:26:08.358  5627  5673 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
10-19 10:26:08.358  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
10-19 10:26:08.359  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
10-19 10:26:08.359  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
10-19 10:26:08.361  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,10-19 10:26:08.361  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
10-19 10:26:08.361  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
10-19 10:26:08.362  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
10-19 10:26:08.363  5627  5673 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
10-19 10:26:08.363  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
10-19 10:26:08.363  5627  5673 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
10-19 10:26:08.363  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,10-19 10:26:08.363  5627  5673 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
10-19 10:26:08.363  5627  5673 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
10-19 10:26:08.364  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
10-19 10:26:08.365  5627  5673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,10-19 10:26:08.365  5627  5673 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,10-19 10:26:08.365  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
10-19 10:26:08.366  5627  5673 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
10-19 10:26:08.366  5627  5673 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,10-19 10:26:08.366  5627  5673 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
10-19 10:26:08.366  5627  5673 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
10-19 10:26:08.367  5627  5673 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
10-19 10:26:08.367  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-19 10:26:08.368  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2b6112 added. We now have 3 listener(s)
10-19 10:26:08.369  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:08.369  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-19 10:26:08.369  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-19 10:26:08.369  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-19 10:26:08.370  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef800e3 added. We now have 3 listener(s)
10-19 10:26:08.370  5627  5673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
10-19 10:26:08.371  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
10-19 10:26:08.373  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-19 10:26:08.376  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-19 10:26:08.378  5627  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-19 10:26:08.378  5627  5673 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-19 10:26:08.379  5627  5673 D BluetoothAdapter: enable(): BT is already enabled..!
10-19 10:26:08.380   932  3884 D WifiService: setWifiEnabled: true pid=5627, uid=10077
10-19 10:26:08.380   932  3884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-19 10:26:08.381  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:08.381  5627  5673 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,10-19 10:26:08.384  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:08.385  5627  5673 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
10-19 10:26:08.385  5627  5673 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,10-19 10:26:08.389   932  3569 D WifiService: setWifiEnabled: false pid=5627, uid=10077
,10-19 10:26:08.389   932  3569 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-19 10:26:08.393   932  2958 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,10-19 10:26:08.393   932  2958 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
10-19 10:26:08.393   932  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-19 10:26:08.393   932  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-19 10:26:08.401   932  5380 D DhcpClient: Clearing IP address
10-19 10:26:08.402   510   925 D CommandListener: Clearing all IP addresses on wlan0
,10-19 10:26:08.409   510   925 D CommandListener: Setting iface cfg
10-19 10:26:08.410  3576  5434 V NativeCrypto: Read error: ssl=0x7fa44e4080: I/O error during system call, Connection timed out
,10-19 10:26:08.412   932  5381 D DhcpClient: Receive thread stopped
,10-19 10:26:08.412  3576  5434 V NativeCrypto: SSL shutdown failed: ssl=0x7fa44e4080: I/O error during system call, Broken pipe
,10-19 10:26:08.414   932  4237 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
10-19 10:26:08.415   932  5378 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,10-19 10:26:08.417   932  5378 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,10-19 10:26:08.418   932  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
10-19 10:26:08.418   932  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
10-19 10:26:08.419   932  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-19 10:26:08.428   932  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
10-19 10:26:08.428   932  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,10-19 10:26:08.435   536   536 E Parcel  : Reading a NULL string not supported here.
,10-19 10:26:08.435   932   932 D RttService: SCAN_AVAILABLE : 1
,10-19 10:26:08.435   932  2964 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,10-19 10:26:08.436   932  3092 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
10-19 10:26:08.438  3768  3903 W QCNEJ   : |CORE| network lost: 100
10-19 10:26:08.439  3768  3903 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
10-19 10:26:08.442   932  2958 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,10-19 10:26:08.450   932  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,10-19 10:26:08.464   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-19 10:26:08.483   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-19 10:26:08.484   510   925 D CommandListener: Clearing all IP addresses on wlan0
,10-19 10:26:08.484   932  2964 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
10-19 10:26:08.485   932  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-19 10:26:08.485   510   925 D TetherController: Setting IP forward enable = 0
,10-19 10:26:08.487   932   949 D Tethering: MasterInitialState.processMessage what=3
,10-19 10:26:08.491  5295  5295 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@314e088 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,10-19 10:26:08.493   932  2958 D DhcpClient: doQuit
10-19 10:26:08.493   932  2958 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-19 10:26:08.494   932  5380 D DhcpClient: onQuitting
10-19 10:26:08.495  3459  3459 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:08.497  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:08.500  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:08.504  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:08.506  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:08.508  5046  5068 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-19 10:26:08.509  5046  5068 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-19 10:26:08.509  5046  5068 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
10-19 10:26:08.509  5046  5068 E SarControlService: no key has been found,reset the power
10-19 10:26:08.509  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-19 10:26:08.509  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-19 10:26:08.509  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-19 10:26:08.510  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-19 10:26:08.510  5071  5071 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:08.510  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:08.511  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
10-19 10:26:08.512  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-19 10:26:08.512  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-19 10:26:08.512  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:08.513  3721  3721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-19 10:26:08.514  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-19 10:26:08.515  5071  5071 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-19 10:26:08.516  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:08.516  5627  5627 ,V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:08.516  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:08.516  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-19 10:26:08.516  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:08.516  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:08.516  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:08.516  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:08.518  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:08.518  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@57a64ae HexData = [00000000ea03000000000000ffffffff]
10-19 10:26:08.518  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-19 10:26:08.518  5071  5085 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
10-19 10:26:08.519  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:08.519  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-19 10:26:08.520  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-19 10:26:08.520  3721  3721 D SystemUpdateService: onCreate
10-19 10:26:08.521  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:08.524  3459  3459 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
10-19 10:26:08.525  3721  3721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-19 10:26:08.529  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@57a64ae HexData = [00000000eb03000000000000ffffffff]
10-19 10:26:08.529  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-19 10:26:08.529  5071  5085 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
10-19 10:26:08.531  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-19 10:26:08.531  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-19 10:26:08.533  3721  5703 I SystemUpdateService: active receiver: enabled
10-19 10:26:08.533  3459  3459 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
10-19 10:26:08.534  3721  3721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
10-19 10:26:08.535   510   918 W SocketClient: write error (Broken pipe)
10-19 10:26:08.535   510   918 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
10-19 10:26:08.535   510   918 W SocketListener: Error sending broadcast (Broken pipe)
,10-19 10:26:08.540  3721  5405 I iu.UploadsManager: num queued entries: 0
,10-19 10:26:08.540  3721  5405 I iu.UploadsManager: num updated entries: 0
10-19 10:26:08.541  3721  5405 I iu.SyncManager: NEXT; no task
,10-19 10:26:08.543  3721  3721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-19 10:26:08.544  3721  3721 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-19 10:26:08.547  5408  5408 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-19 10:26:08.550   510   925 E Netd    : netlink response contains error (No such file or directory)
10-19 10:26:08.551   510   925 D TetherController: Setting IP forward enable = 0
10-19 10:26:08.551   932  2964 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
10-19 10:26:08.551  5408  5408 D SprintDMHelper: simOperator: 
10-19 10:26:08.551  5408  5408 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-19 10:26:08.557  3721  5703 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-19 10:26:08.564  5020  5707 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,10-19 10:26:08.565  3459  3459 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
10-19 10:26:08.565  3721  5703 I SystemUpdateService: network: null; metered: false; mobile allowed: true
10-19 10:26:08.565  3721  5703 I SystemUpdateService: now status is 0 (complete)
,10-19 10:26:08.566  3721  5703 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,10-19 10:26:08.566  3721  5703 I SystemUpdateService: file has been verified
10-19 10:26:08.566  3721  5703 I SystemUpdateService: OTA package size = 21989297
,10-19 10:26:08.572  3721  5703 I SystemUpdateService: showing system update notification
,10-19 10:26:08.577  3459  3459 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-19 10:26:08.583   932  3593 I ActivityManager: Start proc 5709:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,10-19 10:26:08.595  3721  3721 D SystemUpdateService: onDestroy
,10-19 10:26:08.609  5709  5709 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,10-19 10:26:08.615   932  3593 I ActivityManager: Killing 4985:com.google.android.calendar/u0a36 (adj 15): empty #17
,10-19 10:26:08.682   932  2958 D wifi    : In wifi stop Hal
,10-19 10:26:08.682   932  2958 D wifi    : halHandle = 0x7f92a2ab80, mVM = 0x7faf04d140, mCls = 0x100a02
10-19 10:26:08.684   932  3456 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-19 10:26:08.684   932  3456 D WifiHAL : Got a signal to exit!!!
10-19 10:26:08.684   932  3456 I WifiHAL : Exit wifi_event_loop
10-19 10:26:08.684   932  2958 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,10-19 10:26:08.685   932  2958 E WifiHAL : Event processing terminated
10-19 10:26:08.685   932  2958 D wifi    : In wifi cleaned up handler
10-19 10:26:08.685  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-19 10:26:08.685   932  2958 I WifiHAL : Internal cleanup completed
10-19 10:26:08.686  4061  4218 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-19 10:26:08.686  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:08.688  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:08.689  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:08.711   932  3456 D wifi    : set interface wlan0 flags (DOWN)
,10-19 10:26:08.711   932  2958 D WifiNative-HAL: HAL event thread stopped successfully
,10-19 10:26:08.857  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-19 10:26:08.897  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:08.902   932  3884 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,10-19 10:26:08.902   932  3884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-19 10:26:08.917   510   925 D SoftapController: Softap fwReload - Ok
,10-19 10:26:08.918   932   949 D Tethering: InitialState.processMessage what=4
,10-19 10:26:08.924   510   925 D CommandListener: Setting iface cfg
,10-19 10:26:08.924   510   925 D CommandListener: Trying to bring down wlan0
,10-19 10:26:08.925   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-19 10:26:08.926   510   925 D CommandListener: Clearing all IP addresses on wlan0
,10-19 10:26:08.932   932  2958 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-19 10:26:09.407   932  3163 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,10-19 10:26:09.410   932  3163 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-19 10:26:09.606   932  2958 D wifi    : set interface wlan0 flags (UP)
,10-19 10:26:09.606   932  2958 I WifiHAL : Initializing wifi
10-19 10:26:09.606   932  2958 I WifiHAL : Creating socket
,10-19 10:26:09.611   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-19 10:26:09.612   932  2958 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-19 10:26:09.613   932  2958 D wifi    : Did set static halHandle = 0x7f92a2ab80
,10-19 10:26:09.613   932  2958 D wifi    : halHandle = 0x7f92a2ab80, mVM = 0x7faf04d140, mCls = 0x20162a
,10-19 10:26:09.613   932  2958 D wifi    : array field set
10-19 10:26:09.613   932  2958 I WifiNative-HAL: interface[0] = wlan0
10-19 10:26:09.615   932  5724 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547920980864
,10-19 10:26:09.615   932  5724 D wifi    : waitForHalEvents called, vm = 0x7faf04d140, obj = 0x20162a, env = 0x7f90516d80
,10-19 10:26:09.697  5725  5725 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-19 10:26:09.718   932  2958 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-19 10:26:09.719  5725  5725 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-19 10:26:09.726  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.730  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.732  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.741  5725  5725 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-19 10:26:09.741  5725  5725 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-19 10:26:09.758   932  2958 D WifiConfigStore: Loading config and enabling all networks 
,10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:09.762  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:09.765  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:09.769  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:09.771  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:09.773   932  2958 D WifiConfigStore: loaded 0 passpoint configs
10-19 10:26:09.774   932  2958 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,10-19 10:26:09.774   932  2958 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:09.775  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:09.775   932  2958 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
10-19 10:26:09.776   932  2958 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
10-19 10:26:09.777  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:09.777   932  2958 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-19 10:26:09.777   932  2958 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-19 10:26:09.777   932  2958 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-19 10:26:09.781   932  2958 D WifiNative-HAL: Setting external_sim to 1
,10-19 10:26:09.781  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-19 10:26:09.781   932  2958 D wifi    : setting dfs flag to true, 0x7f9210fba0
10-19 10:26:09.782   932  2958 D WifiStateMachine: Setting OUI to DA-A1-19
10-19 10:26:09.782   932  2958 D wifi    : setting scan oui 0x7f9210fba0
10-19 10:26:09.782   932  2958 D WifiHAL : Sending mac address OUI
,10-19 10:26:09.786   932  2958 E native  : do suspend false
,10-19 10:26:09.797   932  2958 D wifi    : android_net_wifi_setLinkLayerStats: 1
10-19 10:26:09.798   510   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,10-19 10:26:09.798   932   932 D RttService: SCAN_AVAILABLE : 3
10-19 10:26:09.798   932  3092 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,10-19 10:26:09.800   510   925 D CommandListener: Setting iface cfg
,10-19 10:26:09.803   932  2947 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '123 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 123 Failed to set address (No such device)'
10-19 10:26:09.803   932  2947 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-19 10:26:09.808   932  2947 D WifiNative-HAL: p2pGetDeviceAddress
,10-19 10:26:09.814   932  2947 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-19 10:26:09.820   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=271230 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=17 mControllerEnergyUsed=64 }
,10-19 10:26:09.913  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.920  4613  4671 D BluetoothAdapterState: Current state: ON, message: 23
,10-19 10:26:09.920  4613  4671 D BluetoothAdapterProperties: Setting state to 13
10-19 10:26:09.920  4613  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
10-19 10:26:09.921  4613  4671 D BluetoothAdapterProperties: onBluetoothDisable()
,10-19 10:26:09.922  4613  4671 I BluetoothAdapterState: Entering PendingCommandState
10-19 10:26:09.924  4613  4675 D BluetoothAdapterProperties: Scan Mode:20
10-19 10:26:09.924  4613  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-19 10:26:09.928  4613  4613 D HeadsetService: Received stop request...Stopping profile...
,10-19 10:26:09.929  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:09.929  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:09.931  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:09.931  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:09.932  3801  3817 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:09.933  3151  3919 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:09.934  3151  3151 D HeadsetProfile: Bluetooth service disconnected
10-19 10:26:09.934   932   932 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:09.934   932   932 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:09.934   932   932 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:09.936  4613  4613 D A2dpService: Received stop request...Stopping profile...
10-19 10:26:09.937  4613  4826 D A2dpStateMachine: Exit Disconnected: -1
10-19 10:26:09.938  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:09.939  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:09.939   932   932 D BluetoothA2dp: Proxy object disconnected
10-19 10:26:09.940  3151  3151 D BluetoothA2dp: Proxy object disconnected
10-19 10:26:09.943  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:09.943  4613  4613 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:09.943  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:09.943  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:09.943  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:09.943  4613  4613 V BluetoothAdapterState: isBleTurningOff()=false
,10-19 10:26:09.946  4613  4613 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,10-19 10:26:09.946  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:09.946  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:09.946  4613  4613 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-19 10:26:09.946  4613  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
10-19 10:26:09.946  4613  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:09.946  4613  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:09.946  4613  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:09.947  4613  4675 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
10-19 10:26:09.947  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:09.947  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:09.948  4613  4613 D HidService: Received stop request...Stopping profile...
10-19 10:26:09.948  4613  4613 D HidService: Stopping Bluetooth HidService
10-19 10:26:09.949  3151  3151 D BluetoothInputDevice: Proxy object disconnected
10-19 10:26:09.949  3151  3151 D HidProfile: Bluetooth service disconnected
10-19 10:26:09.949  4613  4613 D HealthService: Received stop request...Stopping profile...
,10-19 10:26:09.950  4613  4613 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:09.950  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:09.950  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:09.950  4613  4613 V BluetoothAdapterState: isBleTurningOff()=false
,10-19 10:26:09.952  4613  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:09.952  4613  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
10-19 10:26:09.952  4613  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:09.952  4613  4817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-19 10:26:09.952  4613  4817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-19 10:26:09.952  4613  4817 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-19 10:26:09.952  4613  4817 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-19 10:26:09.952  4613  4613 D PanService: Received stop request...Stopping profile...
10-19 10:26:09.953  3151  3151 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-19 10:26:09.953  3151  3151 D PanProfile: Bluetooth service disconnected
,10-19 10:26:09.954  4613  4613 D BluetoothMapService: Received stop request...Stopping profile...
,10-19 10:26:09.954  4613  4613 D BluetoothMapService: stop()
10-19 10:26:09.954  4613  4613 D BluetoothMapAppObserver: deinitObservers()
10-19 10:26:09.954  4613  4613 D BluetoothMapAppObserver: removeReceiver()
10-19 10:26:09.955  3151  3151 D BluetoothMap: Proxy object disconnected
10-19 10:26:09.955  3151  3151 D MapProfile: Bluetooth service disconnected
10-19 10:26:09.956  4613  4613 D SapService: Received stop request...Stopping profile...
10-19 10:26:09.956  4613  4613 V SapService: stop()
10-19 10:26:09.957  4613  4613 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:09.957  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:09.957  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:09.957  4613  4613 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:09.957  4613  4613 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-19 10:26:09.957  4613  4613 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-19 10:26:09.957  4613  4675 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-19 10:26:09.957  4613  4613 V BluetoothAdapterState: isTurningOff()=true
,10-19 10:26:09.958  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:09.958  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:09.958  4613  4613 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:09.958  4613  4613 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-19 10:26:09.958  4613  4675 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
10-19 10:26:09.958  4613  4613 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
10-19 10:26:09.958  4613  4613 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:09.958  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:09.958  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:09.958  4613  4613 V BluetoothAdapterState: isBleTurningOff()=false
,10-19 10:26:09.959  4613  4613 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-19 10:26:09.959  4613  4613 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-19 10:26:09.960  4613  4613 D BluetoothMapService: MAP Service closeService in
10-19 10:26:09.960  4613  4613 D BluetoothMapMasInstance0: MAP Service shutdown
10-19 10:26:09.960  4613  4613 D ObexServerSockets0: shutdown(block = true)
10-19 10:26:09.961  4613  4613 D ObexServerSockets0: shutdown called from another thread - interrupt().
,10-19 10:26:09.961  4613  4613 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-19 10:26:09.961  4613  4835 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
10-19 10:26:09.961  4613  4822 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-19 10:26:09.961  4613  4834 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-19 10:26:09.962  4613  4613 V BluetoothAdapterState: isTurningOff()=true
,10-19 10:26:09.962  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:09.962  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:09.962  4613  4613 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:09.962  4613  4613 D BluetoothMapService: cleanup()
10-19 10:26:09.963  4613  4613 D BluetoothMapService: MAP Service closeService in
10-19 10:26:09.963  4613  4613 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:09.963  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:09.963  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:09.963  4613  4613 V BluetoothAdapterState: isBleTurningOff()=false
,10-19 10:26:09.963  4613  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-19 10:26:09.964  4613  4671 D BluetoothAdapterProperties: Setting state to 15
10-19 10:26:09.964  4613  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-19 10:26:09.964  4613  4671 I BluetoothAdapterState: Entering BleOnState
,10-19 10:26:09.971   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
10-19 10:26:09.971   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
10-19 10:26:09.971   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-19 10:26:09.972  4613  4613 I BtOppRfcommListener: stopping Accept Thread
10-19 10:26:09.973  4613  5308 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-19 10:26:09.973  4613  5308 I BtOppRfcommListener: BluetoothSocket listen thread finished
,10-19 10:26:09.974  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.977  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.978  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.986   932   945 I ActivityManager: Start proc 5729:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
10-19 10:26:09.987  3801  4007 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-19 10:26:09.987  3151  3919 D BluetoothPbap: onBluetoothStateChange: up=false
10-19 10:26:09.988  3151  3165 D BluetoothInputDevice: onBluetoothStateChange: up=false
,10-19 10:26:09.989  3151  3162 D BluetoothHeadset: onBluetoothStateChange: up=false
10-19 10:26:09.989  3151  3919 D BluetoothMap: onBluetoothStateChange: up=false
10-19 10:26:09.989   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
10-19 10:26:09.990  3151  3162 D BluetoothA2dp: onBluetoothStateChange: up=false
10-19 10:26:09.990  3151  3165 D BluetoothPan: onBluetoothStateChange on: false
10-19 10:26:09.991  4613  4671 D BluetoothAdapterState: Current state: BLE ON, message: 20
10-19 10:26:09.991  4613  4671 D BluetoothAdapterProperties: Setting state to 16
10-19 10:26:09.991  4613  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-19 10:26:09.993  4613  4671 D BluetoothAdapterProperties: onBleDisable
10-19 10:26:09.993  4613  4671 I BluetoothAdapterState: Entering PendingCommandState
10-19 10:26:09.993  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:09.993  4613  4672 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,10-19 10:26:09.996  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:09.996  4613  4817 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-19 10:26:09.996  4613  4817 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:09.997  4613  4675 D BluetoothAdapterProperties: Scan Mode:20
10-19 10:26:09.998  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:10.000  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:10.004  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:10.006  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:10.034  5729  5729 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,10-19 10:26:10.044  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-19 10:26:10.049   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@58cc295:true
,10-19 10:26:10.050  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-19 10:26:10.064   932  3163 I ActivityManager: Start proc 5741:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,10-19 10:26:10.074  5729  5729 D LocalBluetoothProfileManager: Adding local MAP profile
,10-19 10:26:10.078  5729  5729 D BluetoothMap: Create BluetoothMap proxy object
,10-19 10:26:10.098  5729  5729 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,10-19 10:26:10.105  5741  5741 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,10-19 10:26:10.115  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-19 10:26:10.122   932   943 I ActivityManager: Killing 5295:com.google.android.music:main/u0a59 (adj 15): empty #17
,10-19 10:26:10.205  4613  4675 I bt_hci  : shut_down
,10-19 10:26:10.207  4613  4684 D bt_hwcfg: hw_epilog_process
,10-19 10:26:10.208  4613  4684 I bt_vendor: low_power_mode_cb
,10-19 10:26:10.211  4613  4684 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-19 10:26:10.211  4613  4684 I bt_vendor: epilog_cb
10-19 10:26:10.211  4613  4684 I bt_hci  : epilog_finished_callback
,10-19 10:26:10.213  4613  4675 I bt_hci_h4: hal_close
,10-19 10:26:10.214  4613  4675 I bt_userial_vendor: device fd = 54 close
,10-19 10:26:10.322  4613  4672 D bt_stack_manager: event_shut_down_stack finished.
10-19 10:26:10.323  4613  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
10-19 10:26:10.325  4613  4671 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-19 10:26:10.325  4613  4613 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-19 10:26:10.325  4613  4613 D BtGatt.GattService: Received stop request...Stopping profile...
,10-19 10:26:10.325  4613  4613 D BtGatt.GattService: stop()
10-19 10:26:10.325  4613  4613 D BtGatt.AdvertiseManager: advertise clients cleared
10-19 10:26:10.328  4613  4613 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:10.328  4613  4613 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:10.328  4613  4613 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:10.328  4613  4613 V BluetoothAdapterState: isBleTurningOff()=true
,10-19 10:26:10.328  4613  4671 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-19 10:26:10.329  4613  4671 D BluetoothAdapterProperties: Setting state to 10
10-19 10:26:10.329  4613  4671 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-19 10:26:10.329  4613  4671 I BluetoothAdapterState: Entering OffState
,10-19 10:26:10.331   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,10-19 10:26:10.337  4613  4613 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-19 10:26:10.337  4613  4613 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-19 10:26:10.337  4613  4613 I BluetoothServiceJni: cleanupNative: return from cleanup
10-19 10:26:10.339  4613  4672 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-19 10:26:10.343  4613  4613 I art     : System.exit called, status: 0
10-19 10:26:10.344  4613  4613 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-19 10:26:10.367  5741  5741 D StrictMode: StrictMode policy violation; ~duration=180 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.File.exists(File.java:361)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,10-19 10:26:10.367  5741  5741 D StrictMode: StrictMode policy violation; ~duration=179 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-19 10:26:10.367  5741  5741 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-19 10:26:10.367  5741  5741 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.k.a(PG:2107)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.e.b(PG:170)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-19 10:26:10.367  5741  5741 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.k.d(PG:1187)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.k.c(PG:18147)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.k.d(PG:583)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.v.a(PG:1161)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.y.a(PG:2188)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.e.b(PG:170)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.r.e.b(PG:15188)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.367  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-19 10:26:10.368  5741  5741 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.io.File.exists(File.java:361)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-19 10:26:10.368  5741  5741 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.io.File.doAccess(File.java:281)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.io.File.exists(File.java:361)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-19 10:26:10.368  5741  5741 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.io.File.lastModified(File.java:569)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
10-19 10:26:10.368  5741  5741 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
10-19 10:26:10.381   932  3593 I ActivityManager: Process com.android.bluetooth (pid 4613) has died
10-19 10:26:10.385  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-19 10:26:10.400   932  3167 I ActivityManager: Start proc 5773:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
10-19 10:26:10.401  5729  5729 D DockEventReceiver: finishStartingService: stopping service
10-19 10:26:10.403   932  3593 I ActivityManager: Killing 4694:com.android.providers.calendar/u0a1 (adj 15): empty #17
,10-19 10:26:10.419  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:10.469  5773  5773 D AdapterServiceConfig: Adding HeadsetService
10-19 10:26:10.470  5773  5773 D AdapterServiceConfig: Adding A2dpService
10-19 10:26:10.470  5773  5773 D AdapterServiceConfig: Adding HidService
10-19 10:26:10.470  5773  5773 D AdapterServiceConfig: Adding HealthService
10-19 10:26:10.470  5773  5773 D AdapterServiceConfig: Adding PanService
10-19 10:26:10.471  5773  5773 D AdapterServiceConfig: Adding GattService
10-19 10:26:10.471  5773  5773 D AdapterServiceConfig: Adding BluetoothMapService
10-19 10:26:10.471  5773  5773 D AdapterServiceConfig: Adding SapService
10-19 10:26:10.474  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-19 10:26:10.481   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@182303:true
,10-19 10:26:10.482  5773  5773 D BluetoothAdapterState: make() - Creating AdapterState
,10-19 10:26:10.485  5773  5773 I bt_bluedroid: init
,10-19 10:26:10.485  5773  5785 I BluetoothAdapterState: Entering OffState
,10-19 10:26:10.488  5773  5786 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-19 10:26:10.488  5773  5786 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-19 10:26:10.488  5773  5786 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-19 10:26:10.488  5773  5786 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-19 10:26:10.489  5773  5773 I bt_bluedroid: get_profile_interface socket
,10-19 10:26:10.491  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
10-19 10:26:10.492  5773  5773 I bt_bluedroid: get_profile_interface sdp
,10-19 10:26:10.492  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-19 10:26:10.497  5773  5783 I bt_bluedroid: config_hci_snoop_log
,10-19 10:26:10.498   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,10-19 10:26:10.501  5773  5785 D BluetoothAdapterState: Current state: OFF, message: 0
,10-19 10:26:10.501  5773  5785 D BluetoothAdapterProperties: Setting state to 14
10-19 10:26:10.501  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
10-19 10:26:10.503  5773  5785 D BluetoothBondStateMachine: make
,10-19 10:26:10.505  5773  5790 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-19 10:26:10.507  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,10-19 10:26:10.508  5773  5773 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
10-19 10:26:10.510  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
10-19 10:26:10.510  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-19 10:26:10.511  5773  5773 D BtGatt.GattService: Received start request. Starting profile...
10-19 10:26:10.511  5773  5773 D BtGatt.GattService: start()
10-19 10:26:10.511  5773  5773 I bt_bluedroid: get_profile_interface gatt
,10-19 10:26:10.512  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
,10-19 10:26:10.512  5773  5773 D BtGatt.AdvertiseManager: advertise manager created
,10-19 10:26:10.517  5773  5773 V BluetoothAdapterState: isTurningOff()=false
,10-19 10:26:10.517  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:10.517  5773  5773 V BluetoothAdapterState: isBleTurningOn()=true
10-19 10:26:10.517  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:10.517  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
10-19 10:26:10.518  5773  5785 I bt_bluedroid: bt_bluedroid
,10-19 10:26:10.518  5773  5786 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,10-19 10:26:10.519  5773  5786 I bt_hci  : start_up
,10-19 10:26:10.524  5773  5786 I bt_vendor: alloc value 0xf41ab871
,10-19 10:26:10.524  5773  5786 I bt_vendor: init
10-19 10:26:10.524  5773  5786 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-19 10:26:10.524  5773  5786 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-19 10:26:10.576  5741  5763 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,10-19 10:26:10.587   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@88fa198:true
,10-19 10:26:10.634  5773  5786 D bt_hci  : start_up starting async portion
,10-19 10:26:10.634  5773  5793 I bt_hci  : event_finish_startup
10-19 10:26:10.634  5773  5793 I bt_hci_h4: hal_open
10-19 10:26:10.634  5773  5793 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
10-19 10:26:10.631  5796  5796 W irq/448-msm_hs_: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
10-19 10:26:10.635  5773  5793 I bt_userial_vendor: device fd = 54 open
,10-19 10:26:10.649  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-19 10:26:10.652  5773  5793 D bt_hwcfg: Chipset BCM4358A3
,10-19 10:26:10.652  5773  5793 D bt_hwcfg: Target name = [BCM4358A3]
10-19 10:26:10.652  5773  5793 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-19 10:26:10.934  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-19 10:26:11.174  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-19 10:26:11.175  5773  5793 D bt_hwcfg: Settlement delay -- 100 ms
10-19 10:26:11.175  5773  5793 I bt_hwcfg: Setting fw settlement delay to 100 
,10-19 10:26:11.299  5773  5793 I bt_hwcfg: bt vendor lib: set UART baud 3000000
10-19 10:26:11.300  5773  5793 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-19 10:26:11.301  5773  5793 I bt_hwcfg: vendor lib fwcfg completed
10-19 10:26:11.302  5773  5793 I bt_vendor: firmware callback
10-19 10:26:11.302  5773  5793 I bt_hci  : firmware_config_callback
,10-19 10:26:11.310  5773  5798 I bt_btu  : btu_task pending for preload complete event
,10-19 10:26:11.310  5773  5798 I bt_btu_task: Bluetooth chip preload is complete
10-19 10:26:11.311  5773  5798 I bt_btu  : btu_task received preload complete event
,10-19 10:26:11.317  5773  5798 I         : BTE_InitTraceLevels -- TRC_HCI
,10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_AVDT
,10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_AVRC
10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_A2D
10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_BNEP
10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_BTM
,10-19 10:26:11.318  5773  5798 I         : BTE_InitTraceLevels -- TRC_GAP
,10-19 10:26:11.319  5773  5798 I         : BTE_InitTraceLevels -- TRC_PAN
10-19 10:26:11.319  5773  5798 I         : BTE_InitTraceLevels -- TRC_SDP
,10-19 10:26:11.319  5773  5798 I         : BTE_InitTraceLevels -- TRC_GATT
10-19 10:26:11.319  5773  5798 I         : BTE_InitTraceLevels -- TRC_SMP
10-19 10:26:11.319  5773  5798 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-19 10:26:11.319  5773  5798 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-19 10:26:11.409  5773  5798 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4129549
10-19 10:26:11.409  5773  5798 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4129549 
,10-19 10:26:11.427  5773  5789 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-19 10:26:11.428  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-19 10:26:11.429  5773  5789 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-19 10:26:11.431  5773  5789 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-19 10:26:11.434  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
,10-19 10:26:11.434  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
10-19 10:26:11.434  5773  5789 D bt_hci  : do_postload posting postload work item
10-19 10:26:11.434  5773  5793 I bt_hci  : event_postload
10-19 10:26:11.435  5773  5793 I bt_vendor: sco_config_cb
10-19 10:26:11.435  5773  5793 I bt_hci  : sco_config_callback postload finished.
,10-19 10:26:11.439  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:11.439  5773  5789 D bt_bte_conf: Device ID record 1 : primary
10-19 10:26:11.439  5773  5789 D bt_bte_conf:   vendorId            = 000f
,10-19 10:26:11.439  5773  5789 D bt_bte_conf:   vendorIdSource      = 0001
10-19 10:26:11.439  5773  5789 D bt_bte_conf:   product             = 1200
10-19 10:26:11.440  5773  5789 D bt_bte_conf:   version             = 1436
10-19 10:26:11.440  5773  5789 D bt_bte_conf:   clientExecutableURL = 
10-19 10:26:11.440  5773  5789 D bt_bte_conf:   serviceDescription  = 
10-19 10:26:11.440  5773  5789 D bt_bte_conf:   documentationURL    = 
10-19 10:26:11.440  5773  5789 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-19 10:26:11.440  5773  5786 D bt_stack_manager: event_start_up_stack finished
,10-19 10:26:11.441  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-19 10:26:11.442  5773  5785 D BluetoothAdapterProperties: Setting state to 15
10-19 10:26:11.442  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-19 10:26:11.443  5773  5785 I BluetoothAdapterState: Entering BleOnState
10-19 10:26:11.445  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:11.446  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 0
10-19 10:26:11.448  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:11.451  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-19 10:26:11.451  5773  5785 D BluetoothAdapterProperties: Setting state to 11
10-19 10:26:11.451  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-19 10:26:11.454  5773  5793 I bt_vendor: low_power_mode_cb
,10-19 10:26:11.458  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
10-19 10:26:11.459  5773  5773 D HeadsetService: Received start request. Starting profile...
10-19 10:26:11.461  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:11.461  5773  5773 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-19 10:26:11.462  5773  5773 D HeadsetStateMachine: make
10-19 10:26:11.462  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:11.465  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:11.473  5773  5773 D HeadsetStateMachine: max_hf_connections = 1
,10-19 10:26:11.474  5773  5773 I bt_bluedroid: get_profile_interface handsfree
10-19 10:26:11.474  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-19 10:26:11.474  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
10-19 10:26:11.477  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
,10-19 10:26:11.477  5773  5773 D A2dpService: Received start request. Starting profile...
10-19 10:26:11.478  5773  5773 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-19 10:26:11.478  5773  5773 I bt_bluedroid: get_profile_interface avrcp
10-19 10:26:11.479  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
,10-19 10:26:11.484  5773  5773 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
10-19 10:26:11.485  5773  5773 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-19 10:26:11.485  5773  5773 D A2dpStateMachine: make
,10-19 10:26:11.486  5773  5773 I bt_bluedroid: get_profile_interface a2dp
,10-19 10:26:11.490  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-19 10:26:11.491  5773  5807 D A2dpStateMachine: Enter Disconnected: -2
,10-19 10:26:11.492  5773  5773 I BluetoothHidServiceJni: classInitNative: succeeds
,10-19 10:26:11.493  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
,10-19 10:26:11.494  5729  5729 D BluetoothInputDevice: Proxy object connected
,10-19 10:26:11.495  5729  5729 D HidProfile: Bluetooth service connected
,10-19 10:26:11.497  5773  5773 D HidService: Received start request. Starting profile...
10-19 10:26:11.497  5773  5773 I bt_bluedroid: get_profile_interface hidhost
10-19 10:26:11.497  5773  5773 D HidService: setHidService(): set to: null
10-19 10:26:11.497  5773  5789 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf410a56d
10-19 10:26:11.498  5773  5773 I BluetoothHealthServiceJni: classInitNative: succeeds
10-19 10:26:11.498  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-19 10:26:11.498  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
10-19 10:26:11.499  5773  5773 D HealthService: Received start request. Starting profile...
10-19 10:26:11.499  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-19 10:26:11.501  5773  5773 I bt_bluedroid: get_profile_interface health
,10-19 10:26:11.501  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:11.501  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:11.501  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.501  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.502  5773  5773 I BluetoothPanServiceJni: classInitNative(L105): succeeds
10-19 10:26:11.502  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
,10-19 10:26:11.504  5773  5773 D PanService: Received start request. Starting profile...
,10-19 10:26:11.504  5773  5773 D BluetoothPanServiceJni: initializeNative(L110): pan
10-19 10:26:11.504  5773  5773 I bt_bluedroid: get_profile_interface pan
10-19 10:26:11.505  5773  5789 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
10-19 10:26:11.506  5773  5805 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
10-19 10:26:11.506  5729  5729 D BluetoothPan: BluetoothPAN Proxy object connected
10-19 10:26:11.506  5729  5729 D PanProfile: Bluetooth service connected
10-19 10:26:11.507  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
,10-19 10:26:11.508  5729  5729 D BluetoothMap: Proxy object connected
,10-19 10:26:11.508  5773  5773 D BluetoothMapService: Received start request. Starting profile...
10-19 10:26:11.508  5773  5773 D BluetoothMapService: start()
10-19 10:26:11.508  5729  5729 D MapProfile: Bluetooth service connected
10-19 10:26:11.508  5729  5729 D BluetoothMap: getConnectedDevices()
10-19 10:26:11.509  5729  5729 D BluetoothMap: Bluetooth is Not enabled
,10-19 10:26:11.511  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-19 10:26:11.512  5773  5773 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
10-19 10:26:11.512  5773  5773 D BluetoothMapAppObserver: createReceiver()
,10-19 10:26:11.513  5773  5773 D BluetoothMapAppObserver: initObservers()
,10-19 10:26:11.513  5773  5773 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-19 10:26:11.520  5773  5773 V SapService: SapBinder()
,10-19 10:26:11.520  5773  5773 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@55a3c74
,10-19 10:26:11.520  5773  5773 D SapService: Received start request. Starting profile...
10-19 10:26:11.521  5773  5773 V SapService: start()
,10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isTurningOff()=false
,10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.522  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isTurningOff()=false
,10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:11.523  5773  5773 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:11.524  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.524  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.524  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-19 10:26:11.524  5773  5785 D BluetoothAdapterProperties: ScanMode =  20
10-19 10:26:11.524  5773  5785 D BluetoothAdapterProperties: State =  11
10-19 10:26:11.525  5773  5789 D BluetoothAdapterProperties: Scan Mode:21
10-19 10:26:11.526  5773  5789 D BluetoothAdapterProperties: Discoverable Timeout:120
10-19 10:26:11.526  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-19 10:26:11.527  5773  5785 D BluetoothAdapterProperties: Setting state to 12
10-19 10:26:11.527  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-19 10:26:11.527  5773  5785 I BluetoothAdapterState: Entering OnState
10-19 10:26:11.527   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:11.527   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:11.528   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
10-19 10:26:11.529  3801  3811 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-19 10:26:11.529   932   932 D BluetoothA2dp: Proxy object connected
,10-19 10:26:11.530  3151  3919 D BluetoothPbap: onBluetoothStateChange: up=true
10-19 10:26:11.531  5627  5627 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,10-19 10:26:11.533  3151  3162 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-19 10:26:11.535  3151  3151 D BluetoothInputDevice: Proxy object connected
10-19 10:26:11.535  3151  3919 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:11.535  3151  3151 D HidProfile: Bluetooth service connected
10-19 10:26:11.534  5627  5627 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,10-19 10:26:11.535  5729  5739 D BluetoothPan: onBluetoothStateChange on: true
10-19 10:26:11.536  3151  3162 D BluetoothMap: onBluetoothStateChange: up=true
,10-19 10:26:11.537  3151  3151 D BluetoothMap: Proxy object connected
10-19 10:26:11.537  3151  3151 D MapProfile: Bluetooth service connected
10-19 10:26:11.537  3151  3151 D BluetoothMap: getConnectedDevices()
10-19 10:26:11.538   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:11.538  5729  5740 D BluetoothMap: onBluetoothStateChange: up=true
10-19 10:26:11.539  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-19 10:26:11.539  3151  3165 D BluetoothA2dp: onBluetoothStateChange: up=true
10-19 10:26:11.540  5773  5773 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-19 10:26:11.541  5729  5739 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-19 10:26:11.542  3151  3151 D BluetoothA2dp: Proxy object connected
,10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:11.542  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:11.542  5729  5740 D BluetoothPbap: onBluetoothStateChange: up=true
10-19 10:26:11.542  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:11.543  3151  3162 D BluetoothPan: onBluetoothStateChange on: true
10-19 10:26:11.544  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:11.544  5773  5773 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:11.545  5773  5773 D ObexServerSockets: Succeed to create listening sockets 
10-19 10:26:11.545  5773  5773 D ObexServerSockets0: startAccept()
10-19 10:26:11.545  5773  5773 D ObexServerSockets0: prepareForNewConnect()
10-19 10:26:11.546  3151  3151 D BluetoothPan: BluetoothPAN Proxy object connected
10-19 10:26:11.547  3151  3151 D PanProfile: Bluetooth service connected
10-19 10:26:11.548  5773  5773 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-19 10:26:11.548   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
10-19 10:26:11.548  5773  5773 D BluetoothSdpJni: SDP Create record success - handle: 0
,10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:11.548  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:11.549  5773  5812 D ObexServerSockets0: Accepting socket connection...
,10-19 10:26:11.549  5773  5773 D BluetoothMapService: onReceive
10-19 10:26:11.550  5773  5773 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-19 10:26:11.550  5773  5773 D BluetoothMapService: STATE_ON
10-19 10:26:11.550  5773  5813 D ObexServerSockets0: Accepting socket connection...
10-19 10:26:11.551  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:11.551  5729  5729 D LocalBluetoothProfileManager: Adding local A2DP profile
10-19 10:26:11.553  5773  5815 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:11.555  5773  5815 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,10-19 10:26:11.555  5773  5815 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:11.556  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:11.558  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:11.559  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-19 10:26:11.560  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:11.561  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:11.561  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:11.561  5729  5729 D LocalBluetoothProfileManager: Adding local HEADSET profile
,10-19 10:26:11.566  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-19 10:26:11.568  5729  5729 D BluetoothA2dp: Proxy object connected
,10-19 10:26:11.571  5773  5773 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-19 10:26:11.571  5773  5773 D ObexServerSockets0: prepareForNewConnect()
10-19 10:26:11.572  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-19 10:26:11.573  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-19 10:26:11.579  3151  3151 D BluetoothPbap: Proxy object connected
10-19 10:26:11.579  3151  3151 D PbapServerProfile: Bluetooth service connected
,10-19 10:26:11.580  5729  5729 D BluetoothPbap: Proxy object connected
,10-19 10:26:11.580  5729  5729 D PbapServerProfile: Bluetooth service connected
,10-19 10:26:11.587  5773  5819 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-19 10:26:11.600  5773  5823 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-19 10:26:11.601  5773  5823 I BtOppRfcommListener: Accept thread started.
,10-19 10:26:11.628  3801  3817 D BluetoothHeadset: Proxy object connected
,10-19 10:26:11.629  3151  3162 D BluetoothHeadset: Proxy object connected
10-19 10:26:11.629  3151  3151 D HeadsetProfile: Bluetooth service connected
10-19 10:26:11.629   932   932 D BluetoothHeadset: Proxy object connected
10-19 10:26:11.629   932   932 D BluetoothHeadset: Proxy object connected
10-19 10:26:11.629   932   932 D BluetoothHeadset: Proxy object connected
10-19 10:26:11.631  3801  4007 D BluetoothHeadset: Proxy object connected
,10-19 10:26:11.635  3151  3165 D BluetoothHeadset: Proxy object connected
,10-19 10:26:11.635  3151  3151 D HeadsetProfile: Bluetooth service connected
,10-19 10:26:11.639   932   949 D BluetoothHeadset: Proxy object connected
,10-19 10:26:11.664  5729  5739 D BluetoothHeadset: Proxy object connected
,10-19 10:26:11.665  5729  5729 D HeadsetProfile: Bluetooth service connected
,10-19 10:26:11.947  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:11.949  5627  5673 D io.jxcore.node.ConnectivityMonitor: stop
10-19 10:26:11.950  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-19 10:26:11.955  5627  5673 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
10-19 10:26:11.957  5627  5673 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,10-19 10:26:11.963  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:11.969  5773  5785 D BluetoothAdapterState: Current state: ON, message: 23
,10-19 10:26:11.970  5773  5785 D BluetoothAdapterProperties: Setting state to 13
,10-19 10:26:11.971  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,10-19 10:26:11.972  5773  5785 D BluetoothAdapterProperties: onBluetoothDisable()
,10-19 10:26:11.973  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
10-19 10:26:11.977  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
10-19 10:26:11.977  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,10-19 10:26:11.981  5773  5773 D HeadsetService: Received stop request...Stopping profile...
,10-19 10:26:11.984  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:11.985  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:11.985  3801  3811 D BluetoothHeadset: Proxy object disconnected
,10-19 10:26:11.987  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:11.987  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:11.988  5729  5740 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:11.989  3151  3919 D BluetoothHeadset: Proxy object disconnected
,10-19 10:26:11.989  5773  5773 D A2dpService: Received stop request...Stopping profile...
10-19 10:26:11.989  3151  3151 D HeadsetProfile: Bluetooth service disconnected
10-19 10:26:11.989   932   932 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:11.989   932   932 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:11.990   932   932 D BluetoothHeadset: Proxy object disconnected
10-19 10:26:11.990  5773  5807 D A2dpStateMachine: Exit Disconnected: -1
,10-19 10:26:11.990  5729  5729 D HeadsetProfile: Bluetooth service disconnected
10-19 10:26:11.992  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:11.992  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:11.994   932   932 D BluetoothA2dp: Proxy object disconnected
10-19 10:26:11.995  3151  3151 D BluetoothA2dp: Proxy object disconnected
10-19 10:26:11.997  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:11.998  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:11.998  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:11.998  5729  5729 D BluetoothA2dp: Proxy object disconnected
10-19 10:26:11.998  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:11.997  5627  5627 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:11.999  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:12.001  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
10-19 10:26:12.001  5773  5773 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
10-19 10:26:12.002  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-19 10:26:12.002  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:12.002  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:12.002  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,10-19 10:26:12.002  5773  5773 D HidService: Received stop request...Stopping profile...
10-19 10:26:12.002  5773  5773 D HidService: Stopping Bluetooth HidService
10-19 10:26:12.003  5773  5789 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
10-19 10:26:12.004  3151  3151 D BluetoothInputDevice: Proxy object disconnected
10-19 10:26:12.004  3151  3151 D HidProfile: Bluetooth service disconnected
10-19 10:26:12.004  5729  5729 D BluetoothInputDevice: Proxy object disconnected
10-19 10:26:12.004  5729  5729 D HidProfile: Bluetooth service disconnected
10-19 10:26:12.004  5773  5773 D HealthService: Received stop request...Stopping profile...
10-19 10:26:12.006  5773  5773 D PanService: Received stop request...Stopping profile...
,10-19 10:26:12.008  5773  5773 V BluetoothAdapterState: isTurningOff()=true
,10-19 10:26:12.008  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:12.008  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:12.008  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:12.008  3151  3151 D BluetoothPan: BluetoothPAN Proxy object disconnected
10-19 10:26:12.008  3151  3151 D PanProfile: Bluetooth service disconnected
10-19 10:26:12.009  5729  5729 D BluetoothPan: BluetoothPAN Proxy object disconnected
,10-19 10:26:12.009  5729  5729 D PanProfile: Bluetooth service disconnected
,10-19 10:26:12.010  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,10-19 10:26:12.010  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:12.010  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
10-19 10:26:12.010  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-19 10:26:12.010  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-19 10:26:12.010  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
10-19 10:26:12.010  5773  5798 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
10-19 10:26:12.010  5773  5773 D BluetoothMapService: Received stop request...Stopping profile...
10-19 10:26:12.010  5773  5773 D BluetoothMapService: stop()
,10-19 10:26:12.011  5773  5773 D BluetoothMapAppObserver: deinitObservers()
10-19 10:26:12.011  5773  5773 D BluetoothMapAppObserver: removeReceiver()
10-19 10:26:12.013  3151  3151 D BluetoothMap: Proxy object disconnected
10-19 10:26:12.013  3151  3151 D MapProfile: Bluetooth service disconnected
10-19 10:26:12.014  5773  5773 D SapService: Received stop request...Stopping profile...
10-19 10:26:12.014  5773  5773 V SapService: stop()
,10-19 10:26:12.014  5729  5729 D BluetoothMap: Proxy object disconnected
10-19 10:26:12.014  5729  5729 D MapProfile: Bluetooth service disconnected
,10-19 10:26:12.016  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:12.016  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:12.016  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,10-19 10:26:12.016  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:12.016  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
10-19 10:26:12.016  5773  5773 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
10-19 10:26:12.017  5773  5789 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
10-19 10:26:12.017  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:12.017  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:12.017  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
,10-19 10:26:12.017  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:12.017  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
10-19 10:26:12.018  5773  5789 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,10-19 10:26:12.019  5773  5773 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,10-19 10:26:12.019  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:12.019  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:12.019  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:12.019  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:12.020  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
10-19 10:26:12.020  5773  5773 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
10-19 10:26:12.021  5773  5773 D BluetoothMapService: MAP Service closeService in
10-19 10:26:12.021  5773  5773 D BluetoothMapMasInstance0: MAP Service shutdown
10-19 10:26:12.022  5773  5773 D ObexServerSockets0: shutdown(block = true)
10-19 10:26:12.022  5773  5812 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
10-19 10:26:12.022  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-19 10:26:12.023  5773  5773 D ObexServerSockets0: shutdown called from another thread - interrupt().
10-19 10:26:12.023  5773  5800 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
10-19 10:26:12.023  5773  5813 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,10-19 10:26:12.023  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:12.023  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:12.023  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:12.023  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:12.024  5773  5773 D BluetoothMapService: cleanup()
,10-19 10:26:12.025  5773  5773 D BluetoothMapService: MAP Service closeService in
10-19 10:26:12.026  5773  5773 V BluetoothAdapterState: isTurningOff()=true
10-19 10:26:12.026  5773  5773 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:12.026  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:12.026  5773  5773 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:12.027  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
10-19 10:26:12.027  5773  5785 D BluetoothAdapterProperties: Setting state to 15
10-19 10:26:12.027  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
10-19 10:26:12.027  5773  5773 I BtOppRfcommListener: stopping Accept Thread
10-19 10:26:12.028  5773  5823 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
10-19 10:26:12.028   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-19 10:26:12.028  5773  5823 I BtOppRfcommListener: BluetoothSocket listen thread finished
10-19 10:26:12.028   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
10-19 10:26:12.028   932   949 D BluetoothA2dp: onBluetoothStateChange: up=false
10-19 10:26:12.029  5729  5739 D BluetoothHeadset: onBluetoothStateChange: up=false
10-19 10:26:12.029  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:12.029  5773  5785 I BluetoothAdapterState: Entering BleOnState
10-19 10:26:12.029  3801  3817 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-19 10:26:12.030  3151  3165 D BluetoothPbap: onBluetoothStateChange: up=false
10-19 10:26:12.031  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
10-19 10:26:12.032  3151  3919 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-19 10:26:12.032  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:12.035  3151  3162 D BluetoothHeadset: onBluetoothStateChange: up=false
10-19 10:26:12.035  5729  5740 D BluetoothPan: onBluetoothStateChange on: false
10-19 10:26:12.036  3151  3165 D BluetoothMap: onBluetoothStateChange: up=false
10-19 10:26:12.038   932   949 D BluetoothHeadset: onBluetoothStateChange: up=false
,10-19 10:26:12.038  5729  5739 D BluetoothA2dp: onBluetoothStateChange: up=false
10-19 10:26:12.038  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-19 10:26:12.041  5729  5740 D BluetoothMap: onBluetoothStateChange: up=false
,10-19 10:26:12.041  3151  3919 D BluetoothA2dp: onBluetoothStateChange: up=false
,10-19 10:26:12.042  5729  5739 D BluetoothInputDevice: onBluetoothStateChange: up=false
10-19 10:26:12.042  5729  5740 D BluetoothPbap: onBluetoothStateChange: up=false
10-19 10:26:12.043  3151  3162 D BluetoothPan: onBluetoothStateChange on: false
10-19 10:26:12.044  5773  5785 D BluetoothAdapterState: Current state: BLE ON, message: 20
,10-19 10:26:12.044  5773  5785 D BluetoothAdapterProperties: Setting state to 16
10-19 10:26:12.044  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
10-19 10:26:12.045  5773  5785 D BluetoothAdapterProperties: onBleDisable
10-19 10:26:12.045  5773  5785 I BluetoothAdapterState: Entering PendingCommandState
10-19 10:26:12.046  5773  5789 D BluetoothAdapterProperties: Scan Mode:20
10-19 10:26:12.047  5773  5786 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
10-19 10:26:12.048  5773  5798 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
10-19 10:26:12.049  5773  5798 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,10-19 10:26:12.050  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:12.052  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:12.055  5729  5729 D DockEventReceiver: finishStartingService: stopping service
10-19 10:26:12.055  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:12.056  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:12.058  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-19 10:26:12.065  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,10-19 10:26:12.066  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-19 10:26:12.248  5773  5789 I bt_hci  : shut_down
,10-19 10:26:12.248  5773  5793 D bt_hwcfg: hw_epilog_process
10-19 10:26:12.249  5773  5793 I bt_vendor: low_power_mode_cb
,10-19 10:26:12.251  5773  5793 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
10-19 10:26:12.251  5773  5793 I bt_vendor: epilog_cb
10-19 10:26:12.251  5773  5793 I bt_hci  : epilog_finished_callback
10-19 10:26:12.252  5773  5789 I bt_hci_h4: hal_close
,10-19 10:26:12.252  5773  5789 I bt_userial_vendor: device fd = 54 close
,10-19 10:26:12.363  5773  5786 D bt_stack_manager: event_shut_down_stack finished.
,10-19 10:26:12.364  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,10-19 10:26:12.368  5773  5785 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
10-19 10:26:12.369  5773  5773 D BtGatt.DebugUtils: handleDebugAction() action=null
,10-19 10:26:12.369  5773  5773 D BtGatt.GattService: Received stop request...Stopping profile...
10-19 10:26:12.369  5773  5773 D BtGatt.GattService: stop()
10-19 10:26:12.370  5773  5773 D BtGatt.AdvertiseManager: advertise clients cleared
,10-19 10:26:12.372  5773  5773 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:12.372  5773  5773 V BluetoothAdapterState: isTurningOn()=false
,10-19 10:26:12.372  5773  5773 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:12.372  5773  5773 V BluetoothAdapterState: isBleTurningOff()=true
10-19 10:26:12.372  5773  5785 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
10-19 10:26:12.372  5773  5785 D BluetoothAdapterProperties: Setting state to 10
,10-19 10:26:12.373  5773  5785 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
10-19 10:26:12.373  5773  5785 I BluetoothAdapterState: Entering OffState
,10-19 10:26:12.374   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,10-19 10:26:12.383  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,10-19 10:26:12.383  5773  5773 W BluetoothSdpJni: Cleaning up Bluetooth Health object
10-19 10:26:12.383  5773  5773 I BluetoothServiceJni: cleanupNative: return from cleanup
10-19 10:26:12.385  5773  5786 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,10-19 10:26:12.390  5773  5773 I art     : System.exit called, status: 0
,10-19 10:26:12.390  5773  5773 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,10-19 10:26:12.414   932  3884 I ActivityManager: Process com.android.bluetooth (pid 5773) has died
,10-19 10:26:12.466  5627  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:12.467  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:12.467  5627  5684 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
10-19 10:26:12.467  5627  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:12.468  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:12.484   932   949 I ActivityManager: Start proc 5829:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,10-19 10:26:12.542  5829  5829 D AdapterServiceConfig: Adding HeadsetService
,10-19 10:26:12.542  5829  5829 D AdapterServiceConfig: Adding A2dpService
10-19 10:26:12.542  5829  5829 D AdapterServiceConfig: Adding HidService
10-19 10:26:12.542  5829  5829 D AdapterServiceConfig: Adding HealthService
10-19 10:26:12.543  5829  5829 D AdapterServiceConfig: Adding PanService
10-19 10:26:12.543  5829  5829 D AdapterServiceConfig: Adding GattService
10-19 10:26:12.543  5829  5829 D AdapterServiceConfig: Adding BluetoothMapService
10-19 10:26:12.543  5829  5829 D AdapterServiceConfig: Adding SapService
,10-19 10:26:12.552   932   949 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0ca658:true
,10-19 10:26:12.553  5829  5829 D BluetoothAdapterState: make() - Creating AdapterState
,10-19 10:26:12.556  5829  5829 I bt_bluedroid: init
,10-19 10:26:12.556  5829  5841 I BluetoothAdapterState: Entering OffState
,10-19 10:26:12.558  5829  5842 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,10-19 10:26:12.558  5829  5842 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
10-19 10:26:12.558  5829  5842 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
10-19 10:26:12.558  5829  5842 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
10-19 10:26:12.558  5829  5829 I bt_bluedroid: get_profile_interface socket
,10-19 10:26:12.560  5829  5845 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-19 10:26:12.560  5829  5829 I bt_bluedroid: get_profile_interface sdp
10-19 10:26:12.562  5829  5845 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-19 10:26:12.565  5829  5840 I bt_bluedroid: config_hci_snoop_log
,10-19 10:26:12.566   932   949 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,10-19 10:26:12.569  5829  5841 D BluetoothAdapterState: Current state: OFF, message: 0
10-19 10:26:12.570  5829  5841 D BluetoothAdapterProperties: Setting state to 14
,10-19 10:26:12.570  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,10-19 10:26:12.571  5829  5841 D BluetoothBondStateMachine: make
,10-19 10:26:12.572  5829  5846 I BluetoothBondStateMachine: StableState(): Entering Off State
,10-19 10:26:12.575  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
,10-19 10:26:12.577  5829  5829 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,10-19 10:26:12.579  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
,10-19 10:26:12.579  5829  5829 D BtGatt.DebugUtils: handleDebugAction() action=null
10-19 10:26:12.580  5829  5829 D BtGatt.GattService: Received start request. Starting profile...
10-19 10:26:12.580  5829  5829 D BtGatt.GattService: start()
,10-19 10:26:12.580  5829  5829 I bt_bluedroid: get_profile_interface gatt
,10-19 10:26:12.581  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
10-19 10:26:12.581  5829  5829 D BtGatt.AdvertiseManager: advertise manager created
,10-19 10:26:12.585  5829  5829 V BluetoothAdapterState: isTurningOff()=false
,10-19 10:26:12.585  5829  5829 V BluetoothAdapterState: isTurningOn()=false
10-19 10:26:12.585  5829  5829 V BluetoothAdapterState: isBleTurningOn()=true
10-19 10:26:12.585  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:12.585  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,10-19 10:26:12.586  5829  5841 I bt_bluedroid: bt_bluedroid
10-19 10:26:12.586  5829  5842 D bt_stack_manager: event_start_up_stack is bringing up the stack.
10-19 10:26:12.587  5829  5842 I bt_hci  : start_up
,10-19 10:26:12.591  5829  5842 I bt_vendor: alloc value 0xf41ab871
10-19 10:26:12.591  5829  5842 I bt_vendor: init
10-19 10:26:12.591  5829  5842 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
10-19 10:26:12.591  5829  5842 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,10-19 10:26:12.702  5829  5842 D bt_hci  : start_up starting async portion
10-19 10:26:12.702  5829  5849 I bt_hci  : event_finish_startup
,10-19 10:26:12.702  5829  5849 I bt_hci_h4: hal_open
10-19 10:26:12.702  5829  5849 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,10-19 10:26:12.705  5829  5849 I bt_userial_vendor: device fd = 54 open
,10-19 10:26:12.701  5850  5850 W irq/448-msm_hs_: type=1400 audit(0.0:119): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-19 10:26:12.719  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-19 10:26:12.722  5829  5849 D bt_hwcfg: Chipset BCM4358A3
,10-19 10:26:12.722  5829  5849 D bt_hwcfg: Target name = [BCM4358A3]
10-19 10:26:12.723  5829  5849 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,10-19 10:26:12.973  5725  5725 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-19 10:26:12.984  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,10-19 10:26:12.985   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:13.002  5725  5725 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-19 10:26:13.013  5725  5725 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-19 10:26:13.021  5725  5725 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-19 10:26:13.061   932  2958 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-19 10:26:13.062   932  2958 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-19 10:26:13.062   932  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-19 10:26:13.071   932  2958 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-19 10:26:13.107   932  2958 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-19 10:26:13.110  5725  5725 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-19 10:26:13.112  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 115200
,10-19 10:26:13.113  5829  5849 D bt_hwcfg: Settlement delay -- 100 ms
10-19 10:26:13.113  5829  5849 I bt_hwcfg: Setting fw settlement delay to 100 
,10-19 10:26:13.237  5829  5849 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,10-19 10:26:13.237  5829  5849 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
10-19 10:26:13.238  5829  5849 I bt_hwcfg: vendor lib fwcfg completed
10-19 10:26:13.238  5829  5849 I bt_vendor: firmware callback
,10-19 10:26:13.238  5829  5849 I bt_hci  : firmware_config_callback
,10-19 10:26:13.243  5829  5852 I bt_btu  : btu_task pending for preload complete event
,10-19 10:26:13.243  5829  5852 I bt_btu_task: Bluetooth chip preload is complete
,10-19 10:26:13.243  5829  5852 I bt_btu  : btu_task received preload complete event
,10-19 10:26:13.248  5829  5852 I         : BTE_InitTraceLevels -- TRC_HCI
10-19 10:26:13.248  5829  5852 I         : BTE_InitTraceLevels -- TRC_L2CAP
10-19 10:26:13.248  5829  5852 I         : BTE_InitTraceLevels -- TRC_RFCOMM
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_AVDT
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_AVRC
,10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_A2D
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_BNEP
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_BTM
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_GAP
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_PAN
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_SDP
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_GATT
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_SMP
10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_BTAPP
,10-19 10:26:13.249  5829  5852 I         : BTE_InitTraceLevels -- TRC_BTIF
,10-19 10:26:13.318  5829  5852 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4129549
10-19 10:26:13.318  5829  5852 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4129549 
,10-19 10:26:13.333  5829  5845 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,10-19 10:26:13.335  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,10-19 10:26:13.335  5829  5845 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,10-19 10:26:13.338  5829  5845 D BluetoothAdapterProperties: Name is: Nexus 6P
,10-19 10:26:13.341  5829  5845 D BluetoothAdapterProperties: Scan Mode:20
,10-19 10:26:13.341  5829  5845 D BluetoothAdapterProperties: Discoverable Timeout:120
,10-19 10:26:13.341  5829  5845 D bt_hci  : do_postload posting postload work item
,10-19 10:26:13.341  5829  5849 I bt_hci  : event_postload
,10-19 10:26:13.342  5829  5849 I bt_vendor: sco_config_cb
10-19 10:26:13.342  5829  5849 I bt_hci  : sco_config_callback postload finished.
10-19 10:26:13.344  5829  5845 D bt_bte_conf: Device ID record 1 : primary
10-19 10:26:13.345  5829  5845 D bt_bte_conf:   vendorId            = 000f
,10-19 10:26:13.345  5829  5845 D bt_bte_conf:   vendorIdSource      = 0001
10-19 10:26:13.345  5829  5845 D bt_bte_conf:   product             = 1200
10-19 10:26:13.345  5829  5845 D bt_bte_conf:   version             = 1436
10-19 10:26:13.345  5829  5845 D bt_bte_conf:   clientExecutableURL = 
10-19 10:26:13.345  5829  5845 D bt_bte_conf:   serviceDescription  = 
10-19 10:26:13.345  5829  5845 D bt_bte_conf:   documentationURL    = 
10-19 10:26:13.345  5829  5845 D bt_bte_conf: bte_load_did_conf no section named DID2.
10-19 10:26:13.346  5829  5842 D bt_stack_manager: event_start_up_stack finished
10-19 10:26:13.346  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
10-19 10:26:13.347  5829  5841 D BluetoothAdapterProperties: Setting state to 15
10-19 10:26:13.347  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
10-19 10:26:13.348  5829  5849 I bt_vendor: low_power_mode_cb
10-19 10:26:13.349  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:13.351  5829  5841 I BluetoothAdapterState: Entering BleOnState
,10-19 10:26:13.353  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:13.353  5829  5841 D BluetoothAdapterState: Current state: BLE ON, message: 1
10-19 10:26:13.353  5829  5841 D BluetoothAdapterProperties: Setting state to 11
10-19 10:26:13.353  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,10-19 10:26:13.357  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
,10-19 10:26:13.358  5829  5829 D HeadsetService: Received start request. Starting profile...
10-19 10:26:13.360  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:13.360  5829  5829 I BluetoothHeadsetServiceJni: classInitNative: succeeds
10-19 10:26:13.360  5829  5829 D HeadsetStateMachine: make
,10-19 10:26:13.362  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:13.369  5829  5829 D HeadsetStateMachine: max_hf_connections = 1
,10-19 10:26:13.369  5829  5829 I bt_bluedroid: get_profile_interface handsfree
10-19 10:26:13.369  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
10-19 10:26:13.369  5829  5845 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,10-19 10:26:13.373  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
,10-19 10:26:13.374  5829  5829 D A2dpService: Received start request. Starting profile...
10-19 10:26:13.374  5829  5829 I BluetoothAvrcpServiceJni: classInitNative: succeeds
10-19 10:26:13.374  5829  5841 I BluetoothAdapterState: Entering PendingCommandState
,10-19 10:26:13.374  5829  5829 I bt_bluedroid: get_profile_interface avrcp
,10-19 10:26:13.379  5829  5829 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,10-19 10:26:13.379  5829  5829 I BluetoothA2dpServiceJni: classInitNative: succeeds
10-19 10:26:13.379  5829  5829 D A2dpStateMachine: make
10-19 10:26:13.380  5829  5829 I bt_bluedroid: get_profile_interface a2dp
,10-19 10:26:13.380  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,10-19 10:26:13.381  5829  5861 D A2dpStateMachine: Enter Disconnected: -2
,10-19 10:26:13.383  5829  5829 I BluetoothHidServiceJni: classInitNative: succeeds
,10-19 10:26:13.383  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
10-19 10:26:13.384  5829  5829 D HidService: Received start request. Starting profile...
10-19 10:26:13.384  5829  5829 I bt_bluedroid: get_profile_interface hidhost
10-19 10:26:13.384  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-19 10:26:13.384  5829  5845 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf410a56d
10-19 10:26:13.384  5829  5829 D HidService: setHidService(): set to: null
10-19 10:26:13.384  5829  5845 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
10-19 10:26:13.386  5829  5829 I BluetoothHealthServiceJni: classInitNative: succeeds
,10-19 10:26:13.386  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
10-19 10:26:13.387  5829  5829 D HealthService: Received start request. Starting profile...
,10-19 10:26:13.388  5829  5829 I bt_bluedroid: get_profile_interface health
10-19 10:26:13.389  5829  5829 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,10-19 10:26:13.390  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
,10-19 10:26:13.390  5829  5829 D PanService: Received start request. Starting profile...
10-19 10:26:13.391  5829  5829 D BluetoothPanServiceJni: initializeNative(L110): pan
10-19 10:26:13.391  5829  5829 I bt_bluedroid: get_profile_interface pan
10-19 10:26:13.391  5829  5845 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,10-19 10:26:13.393  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
,10-19 10:26:13.393  5829  5829 D BluetoothMapService: Received start request. Starting profile...
,10-19 10:26:13.393  5829  5829 D BluetoothMapService: start()
,10-19 10:26:13.396  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,10-19 10:26:13.396  5829  5829 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,10-19 10:26:13.397  5829  5829 D BluetoothMapAppObserver: createReceiver()
,10-19 10:26:13.398  5829  5829 D BluetoothMapAppObserver: initObservers()
,10-19 10:26:13.398  5829  5829 D BluetoothMapAppObserver: getEnabledAccountItems()
,10-19 10:26:13.403  5829  5829 V BluetoothAdapterState: isTurningOff()=false
,10-19 10:26:13.403  5829  5829 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:13.403  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:13.403  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,10-19 10:26:13.404  5829  5858 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,10-19 10:26:13.405  5829  5829 V SapService: SapBinder()
10-19 10:26:13.405  5829  5829 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
,10-19 10:26:13.406  5829  5829 D SapService: Received start request. Starting profile...
10-19 10:26:13.406  5829  5829 V SapService: start()
,10-19 10:26:13.407  5829  5829 V BluetoothAdapterState: isTurningOff()=false
,10-19 10:26:13.407  5829  5829 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:13.407  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:13.407  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:13.407  5829  5829 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:13.407  5829  5829 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:13.407  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:13.408  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,10-19 10:26:13.408  5829  5829 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:13.408  5829  5829 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:13.408  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:13.408  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isTurningOn()=true
,10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isTurningOff()=false
10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:13.409  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
10-19 10:26:13.410  5829  5829 V BluetoothAdapterState: isTurningOff()=false
,10-19 10:26:13.410  5829  5829 V BluetoothAdapterState: isTurningOn()=true
10-19 10:26:13.410  5829  5829 V BluetoothAdapterState: isBleTurningOn()=false
10-19 10:26:13.410  5829  5829 V BluetoothAdapterState: isBleTurningOff()=false
,10-19 10:26:13.411  5829  5841 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,10-19 10:26:13.411  5829  5841 D BluetoothAdapterProperties: ScanMode =  20
10-19 10:26:13.411  5829  5841 D BluetoothAdapterProperties: State =  11
10-19 10:26:13.411  5829  5841 D BluetoothAdapterProperties: Setting state to 12
10-19 10:26:13.411  5829  5841 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
10-19 10:26:13.412   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:13.412   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:13.412  5829  5841 I BluetoothAdapterState: Entering OnState
10-19 10:26:13.412   932   949 D BluetoothA2dp: onBluetoothStateChange: up=true
10-19 10:26:13.412  5729  5739 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:13.413  3801  3811 D BluetoothHeadset: onBluetoothStateChange: up=true
,10-19 10:26:13.413   932   932 D BluetoothA2dp: Proxy object connected
10-19 10:26:13.414  5829  5845 D BluetoothAdapterProperties: Scan Mode:21
10-19 10:26:13.414  3151  3165 D BluetoothPbap: onBluetoothStateChange: up=true
10-19 10:26:13.414  5829  5845 D BluetoothAdapterProperties: Discoverable Timeout:120
10-19 10:26:13.414  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,10-19 10:26:13.415  3151  3162 D BluetoothInputDevice: onBluetoothStateChange: up=true
,10-19 10:26:13.417  3151  3919 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:13.417  5729  5740 D BluetoothPan: onBluetoothStateChange on: true
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:13.418  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:13.418  3151  3151 D BluetoothInputDevice: Proxy object connected
10-19 10:26:13.418  3151  3151 D HidProfile: Bluetooth service connected
10-19 10:26:13.419  3151  3162 D BluetoothMap: onBluetoothStateChange: up=true
10-19 10:26:13.420  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:13.421   932   949 D BluetoothHeadset: onBluetoothStateChange: up=true
10-19 10:26:13.422  5729  5739 D BluetoothA2dp: onBluetoothStateChange: up=true
10-19 10:26:13.422  5729  5729 D BluetoothPan: BluetoothPAN Proxy object connected
10-19 10:26:13.422  5729  5729 D PanProfile: Bluetooth service connected
,10-19 10:26:13.422  3151  3151 D BluetoothMap: Proxy object connected
,10-19 10:26:13.422  3151  3151 D MapProfile: Bluetooth service connected
10-19 10:26:13.422  3151  3151 D BluetoothMap: getConnectedDevices()
10-19 10:26:13.422  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-19 10:26:13.423  5829  5829 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
10-19 10:26:13.424  5729  5826 D BluetoothMap: onBluetoothStateChange: up=true
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:13.424  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:13.424  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:13.426  3151  3165 D BluetoothA2dp: onBluetoothStateChange: up=true
10-19 10:26:13.426  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:13.427  5829  5829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:13.427  3151  3151 D BluetoothA2dp: Proxy object connected
10-19 10:26:13.427  5729  5739 D BluetoothInputDevice: onBluetoothStateChange: up=true
10-19 10:26:13.428  5829  5829 D ObexServerSockets: Succeed to create listening sockets 
10-19 10:26:13.428  5829  5829 D ObexServerSockets0: startAccept()
10-19 10:26:13.428  5829  5829 D ObexServerSockets0: prepareForNewConnect()
10-19 10:26:13.429  5729  5826 D BluetoothPbap: onBluetoothStateChange: up=true
,10-19 10:26:13.430  5829  5829 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
10-19 10:26:13.430  5829  5829 D BluetoothSdpJni: SDP Create record success - handle: 0
10-19 10:26:13.430  5729  5729 D BluetoothA2dp: Proxy object connected
10-19 10:26:13.430  5829  5867 D ObexServerSockets0: Accepting socket connection...
10-19 10:26:13.431  5829  5868 D ObexServerSockets0: Accepting socket connection...
10-19 10:26:13.432  3151  3919 D BluetoothPan: onBluetoothStateChange on: true
10-19 10:26:13.433  3151  3151 D BluetoothPan: BluetoothPAN Proxy object connected
10-19 10:26:13.433  3151  3151 D PanProfile: Bluetooth service connected
10-19 10:26:13.433  5729  5729 D BluetoothMap: Proxy object connected
10-19 10:26:13.433  5729  5729 D MapProfile: Bluetooth service connected
,10-19 10:26:13.433  5729  5729 D BluetoothMap: getConnectedDevices()
10-19 10:26:13.434   932   932 I Telecom : BluetoothPhoneService: queryPhoneState
10-19 10:26:13.434  5829  5829 D BluetoothMapService: onReceive
10-19 10:26:13.434  5829  5829 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
10-19 10:26:13.434  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
10-19 10:26:13.434  5829  5829 D BluetoothMapService: STATE_ON
10-19 10:26:13.436  5729  5729 D BluetoothInputDevice: Proxy object connected
,10-19 10:26:13.436  5729  5729 D HidProfile: Bluetooth service connected
10-19 10:26:13.436  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:13.437  5829  5869 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:13.438  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:13.438  5829  5869 D BluetoothSdpJni: sdpCreateSapsRecordNative:
10-19 10:26:13.438  5829  5869 D BluetoothSdpJni: SDP Create record success - handle: 1
,10-19 10:26:13.442  5729  5729 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,10-19 10:26:13.448  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
10-19 10:26:13.449  5729  5729 D DockEventReceiver: finishStartingService: stopping service
,10-19 10:26:13.455  3151  3151 D BluetoothPbap: Proxy object connected
,10-19 10:26:13.455  3151  3151 D PbapServerProfile: Bluetooth service connected
,10-19 10:26:13.457  5729  5729 D BluetoothPbap: Proxy object connected
10-19 10:26:13.457  5729  5729 D PbapServerProfile: Bluetooth service connected
,10-19 10:26:13.461  5829  5829 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
10-19 10:26:13.461  5829  5829 D ObexServerSockets0: prepareForNewConnect()
,10-19 10:26:13.465  5829  5874 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-19 10:26:13.478  5829  5878 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,10-19 10:26:13.479  5829  5878 I BtOppRfcommListener: Accept thread started.
,10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:13.487  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:13.488  5627  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:13.489  5627  5673 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
10-19 10:26:13.490   932  3592 D WifiService: setWifiEnabled: false pid=5627, uid=10077
10-19 10:26:13.490   932  3592 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-19 10:26:13.491  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:13.492   932   932 D RttService: SCAN_AVAILABLE : 1
10-19 10:26:13.492   932  3092 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,10-19 10:26:13.513  3801  3817 D BluetoothHeadset: Proxy object connected
,10-19 10:26:13.513  5729  5740 D BluetoothHeadset: Proxy object connected
,10-19 10:26:13.513  5729  5739 D BluetoothHeadset: Proxy object connected
10-19 10:26:13.514  3151  3165 D BluetoothHeadset: Proxy object connected
10-19 10:26:13.514  3151  3151 D HeadsetProfile: Bluetooth service connected
10-19 10:26:13.514  3801  4007 D BluetoothHeadset: Proxy object connected
10-19 10:26:13.515   932   932 D BluetoothHeadset: Proxy object connected
10-19 10:26:13.515   932   932 D BluetoothHeadset: Proxy object connected
10-19 10:26:13.515   932   932 D BluetoothHeadset: Proxy object connected
10-19 10:26:13.516   932  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-19 10:26:13.516   510   925 D CommandListener: Clearing all IP addresses on wlan0
10-19 10:26:13.517  5729  5729 D HeadsetProfile: Bluetooth service connected
10-19 10:26:13.518  3151  3162 D BluetoothHeadset: Proxy object connected
10-19 10:26:13.518  3151  3151 D HeadsetProfile: Bluetooth service connected
,10-19 10:26:13.518  5729  5729 D HeadsetProfile: Bluetooth service connected
10-19 10:26:13.520   932  2958 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
10-19 10:26:13.521  5725  5725 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,10-19 10:26:13.522   932   949 D BluetoothHeadset: Proxy object connected
,10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:13.528  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:13.530  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:13.532  5725  5725 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:13.533  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
10-19 10:26:13.535  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:13.538  5725  5725 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:00:00:00:00:00 reason=3 locally_generated=1
,10-19 10:26:13.549  5725  5725 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,10-19 10:26:13.567  5725  5725 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,10-19 10:26:13.670  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-19 10:26:13.670   932  2958 D wifi    : In wifi stop Hal
10-19 10:26:13.670   932  2958 D wifi    : halHandle = 0x7f92a2ab80, mVM = 0x7faf04d140, mCls = 0x20162a
10-19 10:26:13.671   932  5724 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
10-19 10:26:13.671   932  5724 D WifiHAL : Got a signal to exit!!!
10-19 10:26:13.671   932  5724 I WifiHAL : Exit wifi_event_loop
10-19 10:26:13.674  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:13.674   932  2958 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
10-19 10:26:13.674   932  2958 E WifiHAL : Event processing terminated
10-19 10:26:13.675   932  2958 D wifi    : In wifi cleaned up handler
10-19 10:26:13.675   932  2958 I WifiHAL : Internal cleanup completed
,10-19 10:26:13.677  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:13.677  4061  4218 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,10-19 10:26:13.699   932  5724 D wifi    : set interface wlan0 flags (DOWN)
,10-19 10:26:13.699   932  2958 D WifiNative-HAL: HAL event thread stopped successfully
,10-19 10:26:13.906   932   949 D Tethering: InitialState.processMessage what=4
,10-19 10:26:13.914   932   949 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,10-19 10:26:13.986   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:13.999  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:14.004  5627  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:14.007   932   943 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,10-19 10:26:14.007   932   943 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-19 10:26:14.010  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:14.014   510   925 D SoftapController: Softap fwReload - Ok
,10-19 10:26:14.020   510   925 D CommandListener: Setting iface cfg
,10-19 10:26:14.020   510   925 D CommandListener: Trying to bring down wlan0
,10-19 10:26:14.022   510   925 D CommandListener: Clearing all IP addresses on wlan0
,10-19 10:26:14.029   932  2958 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,10-19 10:26:14.512   932  3593 D WifiService: setWifiEnabled: true pid=5627, uid=10077
,10-19 10:26:14.512   932  3593 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,10-19 10:26:14.621   932  2958 D wifi    : set interface wlan0 flags (UP)
,10-19 10:26:14.622   932  2958 I WifiHAL : Initializing wifi
10-19 10:26:14.622   932  2958 I WifiHAL : Creating socket
,10-19 10:26:14.625   932   949 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,10-19 10:26:14.631   932  2958 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,10-19 10:26:14.631   932  2958 D wifi    : Did set static halHandle = 0x7f92a2ab80
10-19 10:26:14.631   932  2958 D wifi    : halHandle = 0x7f92a2ab80, mVM = 0x7faf04d140, mCls = 0x20190a
10-19 10:26:14.631   932  2958 D wifi    : array field set
10-19 10:26:14.631   932  2958 I WifiNative-HAL: interface[0] = wlan0
,10-19 10:26:14.633   932  5882 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547920980864
10-19 10:26:14.633   932  5882 D wifi    : waitForHalEvents called, vm = 0x7faf04d140, obj = 0x20190a, env = 0x7f90518a00
,10-19 10:26:14.691  5883  5883 I wpa_supplicant: Successfully initialized wpa_supplicant
,10-19 10:26:14.712  5883  5883 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-19 10:26:14.726  5883  5883 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,10-19 10:26:14.726  5883  5883 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,10-19 10:26:14.741  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:14.742   932  2958 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,10-19 10:26:14.747  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:14.752   932  2958 D WifiConfigStore: Loading config and enabling all networks 
,10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:14.756  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:14.758  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:14.761  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:14.763  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:14.768   932  2958 D WifiConfigStore: loaded 0 passpoint configs
,10-19 10:26:14.768   932  2958 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
10-19 10:26:14.769   932  2958 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,10-19 10:26:14.770   932  2958 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,10-19 10:26:14.771   932  2958 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,10-19 10:26:14.771   932  2958 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
10-19 10:26:14.772   932  2958 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
10-19 10:26:14.772   932  2958 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,10-19 10:26:14.775   932  2958 D WifiNative-HAL: Setting external_sim to 1
,10-19 10:26:14.775   932  2958 D wifi    : setting dfs flag to true, 0x7f93850280
10-19 10:26:14.775  5020  5020 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
10-19 10:26:14.775   932  2958 D WifiStateMachine: Setting OUI to DA-A1-19
10-19 10:26:14.775   932  2958 D wifi    : setting scan oui 0x7f93850280
10-19 10:26:14.776   932  2958 D WifiHAL : Sending mac address OUI
,10-19 10:26:14.779   932  2958 E native  : do suspend false
,10-19 10:26:14.785   932  2958 D wifi    : android_net_wifi_setLinkLayerStats: 1
,10-19 10:26:14.786   932   932 D RttService: SCAN_AVAILABLE : 3
10-19 10:26:14.786   510   925 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
10-19 10:26:14.786   932  3092 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
10-19 10:26:14.787   510   925 D CommandListener: Setting iface cfg
,10-19 10:26:14.791   932  2947 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '135 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 135 Failed to set address (No such device)'
,10-19 10:26:14.791   932  2947 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,10-19 10:26:14.795   932   947 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=276205 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=5 mControllerEnergyUsed=19 }
,10-19 10:26:14.797   932  2947 D WifiNative-HAL: p2pGetDeviceAddress
,10-19 10:26:14.798   932  2947 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,10-19 10:26:14.987   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:15.025  5627  5684 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:15.032  5627  5684 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
10-19 10:26:15.034  5627  5673 D BluetoothAdapter: enable(): BT is already enabled..!
,10-19 10:26:15.035   932  3167 D WifiService: setWifiEnabled: true pid=5627, uid=10077
10-19 10:26:15.035   932  3167 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
10-19 10:26:15.036  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,10-19 10:26:15.036  5627  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
10-19 10:26:15.036  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-19 10:26:15.036  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-19 10:26:15.036  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,10-19 10:26:15.036  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b2b6112 removed from the list
10-19 10:26:15.036  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-19 10:26:15.036  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ef800e3 removed from the list
10-19 10:26:15.037  5627  5673 D io.jxcore.node.ConnectivityMonitor: stop
10-19 10:26:15.037  5627  5673 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,10-19 10:26:15.037  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,10-19 10:26:15.042  5627  5673 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,10-19 10:26:15.046  5627  5673 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
10-19 10:26:15.047  5627  5673 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
10-19 10:26:15.048  5627  5673 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
10-19 10:26:15.050  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
10-19 10:26:15.050  5627  5673 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
10-19 10:26:15.051  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
10-19 10:26:15.051  5627  5673 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
10-19 10:26:15.052  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
10-19 10:26:15.054  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,10-19 10:26:15.054  5627  5673 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7a4aa12 Bundle[{}]
,10-19 10:26:15.055  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
,10-19 10:26:15.055  5627  5673 I io.jxcore.node.LifeCycleMonitor: start: OK
10-19 10:26:15.055  5627  5673 I io.jxcore.node.LifeCycleMonitor: stop: OK
10-19 10:26:15.056  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
10-19 10:26:15.057  5627  5673 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
10-19 10:26:15.057  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
10-19 10:26:15.057  5627  5673 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
10-19 10:26:15.058  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
10-19 10:26:15.058  5627  5673 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
10-19 10:26:15.058  5627  5673 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,10-19 10:26:15.059  5627  5673 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
10-19 10:26:15.060  5627  5673 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,10-19 10:26:15.062  5627  5673 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,10-19 10:26:15.064  5627  5673 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,10-19 10:26:15.065  5627  5673 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
10-19 10:26:15.065  5627  5673 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
10-19 10:26:15.066  5627  5673 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
10-19 10:26:15.067  5627  5673 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
10-19 10:26:15.068  5627  5673 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
10-19 10:26:15.069  5627  5673 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,10-19 10:26:15.070  5627  5673 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,10-19 10:26:15.072  5627  5673 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
10-19 10:26:15.073  5627  5673 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
10-19 10:26:15.073  5627  5673 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 141)
,10-19 10:26:15.074  5627  5673 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,10-19 10:26:15.074  5627  5673 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
10-19 10:26:15.074  5627  5673 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 142)
10-19 10:26:15.075  5627  5673 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
10-19 10:26:15.076  5627  5673 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
10-19 10:26:15.076  5627  5673 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
10-19 10:26:15.076  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
10-19 10:26:15.076  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bda7c5e added. We now have 3 listener(s)
,10-19 10:26:15.078  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:15.078  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
10-19 10:26:15.078  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
10-19 10:26:15.078  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
10-19 10:26:15.078  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9fc83f added. We now have 3 listener(s)
10-19 10:26:15.078  5627  5673 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,10-19 10:26:15.079  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,10-19 10:26:15.081  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
10-19 10:26:15.085  5627  5673 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,10-19 10:26:15.088  5627  5673 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,10-19 10:26:15.088  5627  5673 D io.jxcore.node.ConnectivityMonitor: start: OK
,10-19 10:26:15.090  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,10-19 10:26:15.091  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
10-19 10:26:15.091  5627  5673 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
10-19 10:26:15.092  5627  5673 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
10-19 10:26:15.092  5627  5673 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
10-19 10:26:15.092  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,10-19 10:26:15.093  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:15.093  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-19 10:26:15.093  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-19 10:26:15.093  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,10-19 10:26:15.094  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-19 10:26:15.094  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-19 10:26:15.094  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-19 10:26:15.094  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-19 10:26:15.095  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-19 10:26:15.095  5627  5885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,10-19 10:26:15.095  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-19 10:26:15.095  5627  5885 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:15.095  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,10-19 10:26:15.095  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:15.095  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
10-19 10:26:15.098  5627  5885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
10-19 10:26:15.095  5856  5856 W Binder_3: type=1400 audit(0.0:120): avc: denied { ioctl } for path="socket:[31653]" dev="sockfs" ino=31653 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:15.095  5856  5856 W Binder_3: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[31653]" dev="sockfs" ino=31653 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,10-19 10:26:15.099  5627  5673 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,10-19 10:26:15.099  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,10-19 10:26:15.103  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,10-19 10:26:15.107  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,10-19 10:26:15.107  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,10-19 10:26:15.109  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-19 10:26:15.109  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:15.109  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
10-19 10:26:15.109  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:15.110  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-19 10:26:15.110  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-19 10:26:15.110  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:15.111  5627  5673 D BluetoothAdapter: STATE_ON
,10-19 10:26:15.113  5829  5856 D BtGatt.GattService: registerClient() - UUID=73637240-9a70-4dbf-8315-118243eff6c6
,10-19 10:26:15.114  5829  5845 D BtGatt.GattService: onClientRegistered() - UUID=73637240-9a70-4dbf-8315-118243eff6c6, clientIf=5
,10-19 10:26:15.115  5627  5637 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
10-19 10:26:15.117  5829  5847 D BtGatt.AdvertiseManager: message : 0
,10-19 10:26:15.119  5829  5847 D BtGatt.AdvertiseManager: starting multi advertising
,10-19 10:26:15.122  5829  5845 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,10-19 10:26:15.124  5829  5845 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,10-19 10:26:15.124  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-19 10:26:15.125  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
,10-19 10:26:15.125  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-19 10:26:15.125  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-19 10:26:15.125  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-19 10:26:15.126  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-19 10:26:15.127  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:15.127  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-19 10:26:15.127  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-19 10:26:15.127  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-19 10:26:15.127  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-19 10:26:15.127  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:15.127  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-19 10:26:15.127  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-19 10:26:15.127  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
10-19 10:26:15.128  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,10-19 10:26:15.130  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-19 10:26:15.130  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,10-19 10:26:15.631  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,10-19 10:26:15.631  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-19 10:26:15.631  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-19 10:26:15.988   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:16.989   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:17.989   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,10-19 10:26:18.629  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,10-19 10:26:18.629  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
10-19 10:26:18.629  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-19 10:26:18.629  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
10-19 10:26:18.630  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-19 10:26:18.630  5627  5885 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,10-19 10:26:18.630  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-19 10:26:18.630  5627  5885 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-19 10:26:18.630  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
10-19 10:26:18.631  5627  5885 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-19 10:26:18.631  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-19 10:26:18.631  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-19 10:26:18.631  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
10-19 10:26:18.631  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-19 10:26:18.632  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
10-19 10:26:18.632  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-19 10:26:18.632  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-19 10:26:18.632  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,10-19 10:26:18.632  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-19 10:26:18.636  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:18.636  5627  5673 D BluetoothLeScanner: could not find callback wrapper
10-19 10:26:18.636  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-19 10:26:18.637  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,10-19 10:26:18.638  5829  5847 D BtGatt.AdvertiseManager: message : 1
10-19 10:26:18.639  5829  5847 D BtGatt.AdvertiseManager: stop advertise for client 5
,10-19 10:26:18.653  5829  5845 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,10-19 10:26:18.653  5829  5845 D BtGatt.GattService: Client app is not null!
10-19 10:26:18.655  5829  5866 D BtGatt.GattService: unregisterClient() - clientIf=5
10-19 10:26:18.656  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-19 10:26:18.656  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-19 10:26:18.656  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-19 10:26:18.656  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,10-19 10:26:18.657  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:18.657  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-19 10:26:18.657  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,10-19 10:26:18.659  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,10-19 10:26:18.660  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-19 10:26:18.662  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,10-19 10:26:18.662  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-19 10:26:18.662  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
10-19 10:26:18.663  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
10-19 10:26:18.666  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,10-19 10:26:18.666  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
10-19 10:26:18.666  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:18.666  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:18.666  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-19 10:26:18.670  5627  5673 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,10-19 10:26:18.671  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-19 10:26:18.672  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-19 10:26:18.672  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
10-19 10:26:18.672  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
10-19 10:26:18.672  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:18.672  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,10-19 10:26:18.677  5627  5673 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-19 10:26:18.678  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
10-19 10:26:18.683  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-19 10:26:18.685  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-19 10:26:18.685  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-19 10:26:18.691  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-19 10:26:18.692  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-19 10:26:18.692  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-19 10:26:18.693  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-19 10:26:18.693  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-19 10:26:18.694  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:18.698  5829  5856 D BtGatt.GattService: registerClient() - UUID=db3737be-22d5-465d-a591-0ad583dd0963
10-19 10:26:18.699  5829  5845 D BtGatt.GattService: onClientRegistered() - UUID=db3737be-22d5-465d-a591-0ad583dd0963, clientIf=5
10-19 10:26:18.699  5627  5637 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
10-19 10:26:18.700  5829  5866 D BtGatt.GattService: start scan with filters
10-19 10:26:18.706  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-19 10:26:18.706  5829  5848 D BtGatt.ScanManager: handling starting scan
,10-19 10:26:18.707  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
10-19 10:26:18.707  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:18.707  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-19 10:26:18.707  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
10-19 10:26:18.707  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
10-19 10:26:18.707  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
10-19 10:26:18.709  5829  5848 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@663fc47
10-19 10:26:18.712  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
10-19 10:26:18.712  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-19 10:26:18.712  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
10-19 10:26:18.714  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-19 10:26:18.718  5829  5845 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-19 10:26:18.718  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:18.719  5829  5848 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-19 10:26:18.727  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-19 10:26:18.728  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:18.728  5829  5848 D BtGatt.ScanManager: Starting BLE batch scan
10-19 10:26:18.728  5829  5848 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-19 10:26:18.742  5829  5845 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-19 10:26:18.742  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-19 10:26:18.751  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,10-19 10:26:18.751  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-19 10:26:19.213  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,10-19 10:26:19.214  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
10-19 10:26:19.214  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-19 10:26:21.722  5627  5673 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,10-19 10:26:21.722  5627  5673 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
10-19 10:26:21.722  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
10-19 10:26:21.723  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
,10-19 10:26:21.743  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
10-19 10:26:21.743  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
10-19 10:26:21.744  5627  5673 D BluetoothAdapter: STATE_ON
,10-19 10:26:21.745  5829  5839 D BtGatt.GattService: stopScan() - queue size =1
,10-19 10:26:21.747  5829  5856 D BtGatt.GattService: unregisterClient() - clientIf=5
10-19 10:26:21.748  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-19 10:26:21.749  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-19 10:26:21.749  5829  5829 D BtGatt.ScanManager: awakened up at time 283159
10-19 10:26:21.749  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
10-19 10:26:21.749  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
10-19 10:26:21.749  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
10-19 10:26:21.749  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
10-19 10:26:21.750  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
10-19 10:26:21.750  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-19 10:26:21.754  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-19 10:26:21.754  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:21.755  5829  5848 D BtGatt.ScanManager: stopping BLe Batch
10-19 10:26:21.755  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:21.760  5829  5839 D BtGatt.GattService: registerClient() - UUID=896dc4f6-e696-4ed6-ae17-e7da2ac6252d
,10-19 10:26:21.760  5829  5845 D BtGatt.GattService: onClientRegistered() - UUID=896dc4f6-e696-4ed6-ae17-e7da2ac6252d, clientIf=5
10-19 10:26:21.761  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
10-19 10:26:21.761  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:21.761  5627  5638 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,10-19 10:26:21.761  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-19 10:26:21.761  5829  5856 D BtGatt.GattService: start scan with filters
10-19 10:26:21.764  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
10-19 10:26:21.764  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,10-19 10:26:21.764  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,10-19 10:26:21.764  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
10-19 10:26:21.764  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-19 10:26:21.764  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:21.764  5627  5673 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
10-19 10:26:21.765  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
10-19 10:26:21.765  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
10-19 10:26:21.765  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
10-19 10:26:21.766  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
10-19 10:26:21.766  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
10-19 10:26:21.766  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,10-19 10:26:21.766  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,10-19 10:26:21.766  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
10-19 10:26:21.766  5627  5890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
10-19 10:26:21.766  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
10-19 10:26:21.767  5627  5890 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
10-19 10:26:21.765  5859  5859 W Binder_4: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[31659]" dev="sockfs" ino=31659 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:21.765  5859  5859 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[31659]" dev="sockfs" ino=31659 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
10-19 10:26:21.767  5627  5673 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
10-19 10:26:21.769  5627  5890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,10-19 10:26:21.773  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser
,10-19 10:26:21.774  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
10-19 10:26:21.774  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
10-19 10:26:21.774  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
10-19 10:26:21.774  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
10-19 10:26:21.774  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start, state = NOT_STARTED
10-19 10:26:21.774  5627  5673 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
10-19 10:26:21.774  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,10-19 10:26:21.777  5627  5673 D BluetoothAdapter: STATE_ON
,10-19 10:26:21.780  5829  5856 D BtGatt.GattService: registerClient() - UUID=89e254da-e833-42a1-b574-7490db201ad3
10-19 10:26:21.780  5829  5845 D BtGatt.GattService: onClientRegistered() - UUID=89e254da-e833-42a1-b574-7490db201ad3, clientIf=6
,10-19 10:26:21.781  5627  5637 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
10-19 10:26:21.781  5829  5847 D BtGatt.AdvertiseManager: message : 0
,10-19 10:26:21.783  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
10-19 10:26:21.783  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-19 10:26:21.783  5829  5845 D BtGatt.GattService: current time is 283193523391
,10-19 10:26:21.784  5829  5845 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -95, 39, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 116, -43, -111, -91, -20, -29, 1, -128, -84, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -46, -4, -117, 6, 105, -37, 1, -128, -78, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -81, 41, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -81, 39, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -77, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -81, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 7, -113, -82, -121, -9, 65, 1, -128, -53, 32, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, 7, -113, -82, -121, -9, 65, 1, -128, -53, 30, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0]
10-19 10:26:21.785  5829  5845 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
10-19 10:26:21.786  5829  5847 D BtGatt.AdvertiseManager: starting multi advertising
10-19 10:26:21.786  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-19 10:26:21.787  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-19 10:26:21.787  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-19 10:26:21.787  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-19 10:26:21.787  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76,, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
10-19 10:26:21.787  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
10-19 10:26:21.787  5829  5845 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
10-19 10:26:21.788  5829  5845 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-19 10:26:21.789  5829  5848 D BtGatt.ScanManager: handling starting scan
10-19 10:26:21.796  5829  5845 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
10-19 10:26:21.800  5829  5845 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
10-19 10:26:21.800  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:21.801  5829  5848 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
10-19 10:26:21.804  5829  5845 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
10-19 10:26:21.805  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment
10-19 10:26:21.805  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTING
10-19 10:26:21.805  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
10-19 10:26:21.805  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTING
10-19 10:26:21.805  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
10-19 10:26:21.805  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
10-19 10:26:21.805  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser, adv = true, disc = true
10-19 10:26:21.805  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
10-19 10:26:21.807  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
10-19 10:26:21.809  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
10-19 10:26:21.809  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:21.809  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
10-19 10:26:21.809  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
10-19 10:26:21.809  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNING
10-19 10:26:21.809  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
10-19 10:26:21.809  5627  5627 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
10-19 10:26:21.809  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:21.809  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
10-19 10:26:21.809  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
10-19 10:26:21.809  5627  5627 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]
10-19 10:26:21.810  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING]
10-19 10:26:21.810  5829  5848 D BtGatt.ScanManager: Starting BLE batch scan
10-19 10:26:21.810  5829  5848 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
10-19 10:26:21.812  5627  5627 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
10-19 10:26:21.812  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
10-19 10:26:21.819  5829  5845 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
10-19 10:26:21.820  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:21.824  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
10-19 10:26:21.824  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,10-19 10:26:22.313  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,10-19 10:26:22.314  5627  5627 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,10-19 10:26:22.314  5627  5627 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,10-19 10:26:24.189   932  2958 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 15, 17 -> obsolete
,10-19 10:26:24.812  5627  5673 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,10-19 10:26:24.812  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
10-19 10:26:24.813  5627  5673 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
10-19 10:26:24.813  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,10-19 10:26:24.813  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
10-19 10:26:24.814  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
10-19 10:26:24.814  5627  5890 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
10-19 10:26:24.814  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,10-19 10:26:24.814  5627  5890 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
10-19 10:26:24.814  5627  5673 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
10-19 10:26:24.814  5627  5890 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,10-19 10:26:24.814  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
10-19 10:26:24.814  5627  5673 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bda7c5e removed from the list
10-19 10:26:24.815  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
10-19 10:26:24.815  5627  5627 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
10-19 10:26:24.815  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,10-19 10:26:24.815  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
10-19 10:26:24.815  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
10-19 10:26:24.815  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
10-19 10:26:24.815  5627  5627 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,10-19 10:26:24.815  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
10-19 10:26:24.815  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
10-19 10:26:24.818  5627  5673 D BluetoothAdapter: STATE_ON
10-19 10:26:24.820  5829  5866 D BtGatt.GattService: stopScan() - queue size =1
,10-19 10:26:24.822  5829  5856 D BtGatt.GattService: unregisterClient() - clientIf=5
10-19 10:26:24.823  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
10-19 10:26:24.823  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
10-19 10:26:24.823  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
10-19 10:26:24.823  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:24.822   932  2958 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 16, 17 -> obsolete
10-19 10:26:24.823  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
10-19 10:26:24.823  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
,10-19 10:26:24.824  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [ADVERTISING]
10-19 10:26:24.824  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [ADVERTISING]
10-19 10:26:24.828  5829  5829 D BtGatt.ScanManager: awakened up at time 286238
10-19 10:26:24.831  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
10-19 10:26:24.831  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
10-19 10:26:24.832  5829  5847 D BtGatt.AdvertiseManager: message : 1
,10-19 10:26:24.833  5829  5847 D BtGatt.AdvertiseManager: stop advertise for client 6
10-19 10:26:24.833  5829  5845 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
10-19 10:26:24.833  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:24.834  5829  5848 D BtGatt.ScanManager: stopping BLe Batch
,10-19 10:26:24.843  5829  5845 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,10-19 10:26:24.843  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:24.843  5829  5848 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,10-19 10:26:24.851  5829  5845 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,10-19 10:26:24.851  5829  5845 D BtGatt.GattService: Client app is not null!
10-19 10:26:24.853  5829  5859 D BtGatt.GattService: unregisterClient() - clientIf=6
10-19 10:26:24.853  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,10-19 10:26:24.853  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTED
10-19 10:26:24.853  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
10-19 10:26:24.854  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
10-19 10:26:24.854  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
10-19 10:26:24.854  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
10-19 10:26:24.854  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
10-19 10:26:24.854  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
10-19 10:26:24.854  5627  5673 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,10-19 10:26:24.856  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
10-19 10:26:24.857  5627  5673 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
10-19 10:26:24.857  5627  5673 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,10-19 10:26:24.858  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,10-19 10:26:24.861  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,10-19 10:26:24.861  5627  5627 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
10-19 10:26:24.861  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
10-19 10:26:24.862  5627  5627 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,10-19 10:26:24.862  5627  5673 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9fc83f removed from the list
10-19 10:26:24.862  5627  5673 D io.jxcore.node.ConnectivityMonitor: stop
10-19 10:26:24.862  5627  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
10-19 10:26:24.864  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
10-19 10:26:24.864  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
10-19 10:26:24.864  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
10-19 10:26:24.864  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,10-19 10:26:24.864  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
10-19 10:26:24.864  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
10-19 10:26:24.865  5627  5673 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
10-19 10:26:24.866  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
10-19 10:26:24.867  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,10-19 10:26:24.868  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
10-19 10:26:24.868  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
10-19 10:26:24.869  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
10-19 10:26:24.870  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
10-19 10:26:24.871  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
10-19 10:26:24.872  5627  5673 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,10-19 10:26:24.892  5829  5845 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=10
,10-19 10:26:24.892  5829  5845 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
10-19 10:26:24.892  5829  5845 D BtGatt.GattService: current time is 286302102886
10-19 10:26:24.892  5829  5845 D BtGatt.GattService: Batch record : [-88, 109, 69, 21, -87, 77, 1, -128, -47, 60, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 7, -113, -82, -121, -9, 65, 1, -128, -54, 34, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62, 0, -88, 109, 69, 21, -87, 77, 1, -128, -47, 0, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111, 0, 37, -47, 14, -113, 116, -46, 1, -128, -84, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -84, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -77, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -89, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -81, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -80, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 50, -35, 86, -77, -92, -11, 1, -128, -98, 22, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -87, -103, 48, 3, 1, -33, 18, -106, -111, -96, -124, 0]
,10-19 10:26:24.893  5829  5845 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
10-19 10:26:24.893  5829  5845 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, 68, 120, 62, -108, 74, 62]
10-19 10:26:24.893  5829  5845 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 6, -88, -127, -107, -23, 95, 111]
10-19 10:26:24.893  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
10-19 10:26:24.894  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
10-19 10:26:24.894  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,10-19 10:26:24.894  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
10-19 10:26:24.894  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
10-19 10:26:24.894  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
10-19 10:26:24.895  5829  5845 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 52, -97, 83, -21, -49, 113, -115, -80, -87, -103, 48, 3, 1, -33, 18, -106, -111, -96, -124]
,10-19 10:26:25.362  5627  5627 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,10-19 10:26:26.876  5627  5673 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,10-19 10:26:27.020  5627  5892 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-19 10:26:27.020  5627  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-19 10:26:27.341  5883  5883 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-19 10:26:27.345  5883  5883 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-19 10:26:27.350  5883  5883 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,10-19 10:26:27.406   932  2958 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
10-19 10:26:27.406   932  2958 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
10-19 10:26:27.407   932  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-19 10:26:27.417   932  2958 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,10-19 10:26:27.442   932  2958 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,10-19 10:26:27.443  5883  5883 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,10-19 10:26:27.810  5627  5892 W !!      : call onHalfStreamCopied
,10-19 10:26:27.811  5627  5892 I testCopyDataAndClose: closing input stream
,10-19 10:26:27.903  5883  5883 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,10-19 10:26:27.935  5883  5883 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,10-19 10:26:27.935  5883  5883 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,10-19 10:26:27.944   932  2958 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-19 10:26:27.944   932  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
10-19 10:26:27.944   932  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,10-19 10:26:27.957   932  2958 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,10-19 10:26:27.968   510   925 D CommandListener: Setting iface cfg
,10-19 10:26:27.972   932  2958 D WifiStateMachine: Start Dhcp Watchdog 2
,10-19 10:26:27.981   932  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-19 10:26:27.982   932  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
10-19 10:26:27.982   932  2964 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,10-19 10:26:27.985   932  5896 D DhcpClient: Receive thread started
,10-19 10:26:28.065   932  2958 E native  : do suspend false
,10-19 10:26:28.074   932  5895 D DhcpClient: Broadcasting DHCPDISCOVER
,10-19 10:26:28.094   932  5896 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172553, domain null
,10-19 10:26:28.095   932  5895 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172553 seconds
,10-19 10:26:28.096   932  5895 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,10-19 10:26:28.134   932  5896 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,10-19 10:26:28.134   932  5895 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,10-19 10:26:28.137   510   925 D CommandListener: Setting iface cfg
,10-19 10:26:28.142   932  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,10-19 10:26:28.147   932  5895 D DhcpClient: Scheduling renewal in 86399s
,10-19 10:26:28.155   932  2958 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,10-19 10:26:28.155   932  2958 D WifiConfigStore: No blacklist allowed without epno enabled
,10-19 10:26:28.156   932  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
10-19 10:26:28.158   932  2964 D ConnectivityService: Adding iface wlan0 to network 101
,10-19 10:26:28.162   932  2958 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,10-19 10:26:28.207   932  2964 E ConnectivityService: Unexpected mtu value: 0, wlan0
,10-19 10:26:28.208   932  2964 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
10-19 10:26:28.210   932  2964 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,10-19 10:26:28.212   932  2964 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,10-19 10:26:28.215   932  2964 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,10-19 10:26:28.226   932  2964 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-19 10:26:28.232   932  2964 D ConnectivityService: scheduleUnvalidatedPrompt 101
10-19 10:26:28.232   932  2964 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
10-19 10:26:28.232   932  2964 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
10-19 10:26:28.232   932  2964 D ConnectivityService:    accepting network in place of null
10-19 10:26:28.232   932  2958 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
10-19 10:26:28.232   932  2958 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
10-19 10:26:28.233   932  2964 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -50]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,10-19 10:26:28.238   932  5894 D NetlinkSocketObserver: NeighborEvent{elapsedMs=289648, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,10-19 10:26:28.260   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-19 10:26:28.282   510   925 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,10-19 10:26:28.286   932  2964 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
10-19 10:26:28.286  3768  3903 W QCNEJ   : |CORE| network available: 101
10-19 10:26:28.286   932  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
10-19 10:26:28.287   932  2964 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
10-19 10:26:28.289   932   949 D Tethering: MasterInitialState.processMessage what=3
10-19 10:26:28.289  3768  3903 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,10-19 10:26:28.294  3768  3903 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
10-19 10:26:28.294  3768  3903 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-19 10:26:28.297  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-19 10:26:28.300  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,10-19 10:26:28.304  5046  5068 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
10-19 10:26:28.304  5046  5068 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
10-19 10:26:28.304  5046  5068 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
10-19 10:26:28.304  5046  5068 E SarControlService: no key has been found,reset the power
10-19 10:26:28.304  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
10-19 10:26:28.304  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
10-19 10:26:28.304  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
10-19 10:26:28.305  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-19 10:26:28.305  5071  5071 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
10-19 10:26:28.306  5627  5627 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
10-19 10:26:28.307  5627  5627 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
10-19 10:26:28.307   932  5893 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
10-19 10:26:28.308  5046  5083 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,10-19 10:26:28.308  5046  5083 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
10-19 10:26:28.309  5046  5083 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
10-19 10:26:28.309  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
10-19 10:26:28.309  5071  5071 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
10-19 10:26:28.311  3721  3721 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
10-19 10:26:28.314  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@57a64ae HexData = [00000000ec03000000000000ffffffff]
10-19 10:26:28.314  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-19 10:26:28.314  5071  5085 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,10-19 10:26:28.314  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-19 10:26:28.315  5046  5056 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
10-19 10:26:28.316  3721  3721 D SystemUpdateService: onCreate
10-19 10:26:28.319  3721  3721 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
10-19 10:26:28.321  5071  5085 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@57a64ae HexData = [00000000ed03000000000000ffffffff]
10-19 10:26:28.321  5071  5085 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
10-19 10:26:28.321  5071  5085 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
10-19 10:26:28.321  5071  5071 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
10-19 10:26:28.322  5046  5057 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,10-19 10:26:28.338  3721  3721 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,10-19 10:26:28.345  3721  5906 I SystemUpdateService: active receiver: enabled
10-19 10:26:28.346  3721  5405 I iu.UploadsManager: num queued entries: 0
,10-19 10:26:28.347  3721  5405 I iu.UploadsManager: num updated entries: 0
10-19 10:26:28.348  3721  5405 I iu.SyncManager: NEXT; no task
,10-19 10:26:28.349  3721  3721 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,10-19 10:26:28.351  3721  3721 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,10-19 10:26:28.353  5408  5408 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,10-19 10:26:28.356  5408  5408 D SprintDMHelper: simOperator: 
10-19 10:26:28.356  5408  5408 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,10-19 10:26:28.376  3721  5906 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,10-19 10:26:28.390  3721  5906 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,10-19 10:26:28.390  3721  5906 I SystemUpdateService: now status is 0 (complete)
10-19 10:26:28.390  3721  5906 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
10-19 10:26:28.390  3721  5906 I SystemUpdateService: file has been verified
10-19 10:26:28.391  3721  5906 I SystemUpdateService: OTA package size = 21989297
,10-19 10:26:28.396  3721  5906 I SystemUpdateService: showing system update notification
,10-19 10:26:28.406  3721  3721 D SystemUpdateService: onDestroy
,10-19 10:26:28.412   932  5893 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 19 Oct 2016 14:26:28 GMT], X-Android-Received-Millis=[1476887188411], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1476887188334]}
,10-19 10:26:28.412   932  2964 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,10-19 10:26:28.412   932  2964 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
10-19 10:26:28.412   932  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
10-19 10:26:28.413   932  2964 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,10-19 10:26:28.491  5020  5911 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 155, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 155, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
10-19 10:26:28.567  5627  5892 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-19 10:26:29.288   932  2964 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,10-19 10:26:29.796   932  2958 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 17, 18 -> obsolete
,10-19 10:26:32.521  5627  5673 I StreamCopyingThreadTest: Starting test: testRun
,10-19 10:26:32.525  5627  5918 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: My test thread name). Connection data: Peer properties: [null null].
10-19 10:26:32.525  5627  5918 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-19 10:26:36.238   932  2964 D ConnectivityService: handlePromptUnvalidated 101
,10-19 10:26:37.529  5627  5919 E StreamCopyingThreadTest: StreamCopyingThread didn't close after 5s!
,10-19 10:26:37.532  5627  5673 I StreamCopyingThreadTest: Starting test: testCopyBigData
,10-19 10:26:37.679  5627  5920 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-19 10:26:37.679  5627  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-19 10:26:37.991   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:38.992   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:39.335  5627  5920 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-19 10:26:39.335  5627  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: testCopyBigData thread). Connection data: Peer properties: [null null].
10-19 10:26:39.336  5627  5920 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,10-19 10:26:39.993   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:40.994   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:41.996   539   539 I ServiceManager: Waiting for service AtCmdFwd...
,10-19 10:26:42.997   539   539 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,10-19 10:26:43.099   932  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-19 10:26:43.195  5627  5673 I StreamCopyingThreadTest: Starting test: testRunNotify
,10-19 10:26:43.197  5627  5921 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-19 10:26:43.197  5627  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 163, thread name: My test thread name). Connection data: Peer properties: [null null].
10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
10-19 10:26:43.198  5627  5921 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
10-19 10:26:43.199  5627  5921 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 163, name: My test thread name). Connection data: Peer properties: [null null].
10-19 10:26:43.199  5627  5921 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
10-19 10:26:43.199  5627  5673 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,10-19 10:26:43.200  5627  5673 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
10-19 10:26:43.200  5627  5673 I StreamCopyingThreadTest: Starting test: testRunWithException
10-19 10:26:43.202  5627  5922 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-19 10:26:43.202  5627  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,10-19 10:26:43.203  5627  5922 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 167, thread name: My test thread name): Test exception.
10-19 10:26:43.203  5627  5922 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-19 10:26:43.203  5627  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-19 10:26:43.203  5627  5922 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
10-19 10:26:43.203  5627  5922 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name). Connection data: Peer properties: [null null].
10-19 10:26:43.203  5627  5922 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
10-19 10:26:43.205  5627  5673 E com.test.thalitest.ThaliTestRunner: testConnect(io.jxcore.node.ConnectionHelperTest)
,10-19 10:26:43.205  5627  5673 E com.test.thalitest.ThaliTestRunner: 
10-19 10:26:43.205  5627  5673 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-19 10:26:43.205  5627  5673 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: 
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: Expected: is "We already have an outgoing connection to peer with ID 00:11:22:33:44:55"
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner:      but: was "Already connect(ing/ed)"
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:8)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.ConnectionHelperTest.testConnect(ConnectionHelperTest.java:551)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunAfters.evaluate(RunAfters.java:27)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRun,ner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: testRun(io.jxcore.node.StreamCopyingThreadTest)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: StreamCopyingThread should be closed
10-19 10:26:43.206 , 5627  5673 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: java.lang.AssertionError: StreamCopyingThread should be closed
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: Expected: is <true>
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner:      but: was <false>
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.hamcrest.MatcherAssert.assertThat(MatcherAssert.java:20)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.StreamCopyingThreadTest.testRun(StreamCopyingThreadTest.java:152)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at java.lang.reflect.Method.invoke(Native Method)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod$1.runReflectiveCall(FrameworkMethod.java:50)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.model.ReflectiveCallable.run(ReflectiveCallable.java:12)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.model.FrameworkMethod.invokeExplosively(FrameworkMethod.java:47)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.InvokeMethod.evaluate(InvokeMethod.java:17)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.internal.runners.statements.RunBefores.evaluate(RunBefores.java:26)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.ExpectedException$ExpectedExceptionStatement.evaluate(ExpectedException.java:239)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.TestWatcher$1.evaluate(TestWatcher.java:55)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.rules.RunRules.evaluate(RunRules.java:20)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runLeaf(ParentRunner.java:325)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:78)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.BlockJUnit4ClassRunner.runChild(BlockJUnit4ClassRunner.java:57)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner,: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:128)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.Suite.runChild(Suite.java:27)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$3.run(ParentRunner.java:290)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$1.schedule(ParentRunner.java:71)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.runChildren(ParentRunner.java:288)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.access$000(ParentRunner.java:58)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner$2.evaluate(ParentRunner.java:268)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runners.ParentRunner.run(ParentRunner.java:363)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:137)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:115)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.run(JUnitCore.java:105)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:62)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at org.junit.runner.JUnitCore.runClasses(JUnitCore.java:49)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.ThaliTestRunner.runTests(ThaliTestRunner.java:86)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at com.test.thalitest.RegisterExecuteUT$2.Receiver(RegisterExecuteUT.java:75)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.javaCall(jxcore.java:139)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore.evalEngine(Native Method)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.jxcore$4.run(jxcore.java:226)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.handleCallback(Handler.java:739)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at android.os.Handler.dispatchMessage(Handler.java:95)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:43.206  5627  5673 E com.test.thalitest.ThaliTestRunner: 	at io.jxcore.node.CoreThread.run(CoreRunnable.java:56)
10-19 10:26:43.209  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG UnitTest_app: 'Running unit tests'
10-19 10:26:43.209  5627  5673 I jxcore-log: 
10-19 10:26:43.210  5627  5673 I jxcore-log: *Native tests were executed*
10-19 10:26:43.210  5627  5673 I jxcore-log: 
10-19 10:26:43.210  5627  5673 I jxcore-log: Total number of executed tests:  82
10-19 10:26:43.210  5627  5673 I jxcore-log: 
10-19 10:26:43.210  5627  5673 I jxcore-log: Number of passed tests:  80
10-19 10:26:43.210  5627  5673 I jxcore-log: 
10-19 10:26:43.210  5627  5673 I jxcore-log: Number of failed tests:  2
10-19 10:26:43.210  5627  5673 I jxcore-log: 
10-19 10:26:43.210  5627  5673 I jxcore-log: Number of ignored tests:  0
10-19 10:26:43.210  5627  5673 I jxcore-log: 
10-19 10:26:43.210  5627  5673 I jxcore-log: Total duration:  41731
10-19 10:26:43.210  5627  5673 I jxcore-log: 
10-19 10:26:43.210 , 5627  5673 I jxcore-log: Failed to execute UT.
10-19 10:26:43.210  5627  5673 I jxcore-log: 
10-19 10:26:43.211  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG UnitTest_app: 'Failed to execute UT.'
10-19 10:26:43.211  5627  5673 I jxcore-log: 
10-19 10:26:43.213  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG UnitTest_app: 'Unit Test app is loaded'
10-19 10:26:43.213  5627  5673 I jxcore-log: 
10-19 10:26:43.218  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-19 10:26:43.218  5627  5673 I jxcore-log: 
10-19 10:26:43.218  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.218  5627  5673 I jxcore-log: 
10-19 10:26:43.220  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-19 10:26:43.220  5627  5673 I jxcore-log: 
10-19 10:26:43.221  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.221  5627  5673 I jxcore-log: 
10-19 10:26:43.222  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-19 10:26:43.222  5627  5673 I jxcore-log: 
10-19 10:26:43.222  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.222  5627  5673 I jxcore-log: 
10-19 10:26:43.223  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-19 10:26:43.223  5627  5673 I jxcore-log: 
10-19 10:26:43.223  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-19 10:26:43.223  5627  5673 I jxcore-log: 
10-19 10:26:43.224  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-19 10:26:43.224  5627  5673 I jxcore-log: 
10-19 10:26:43.224  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-19 10:26:43.224  5627  5673 I jxcore-log: 
10-19 10:26:43.225  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-19 10:26:43.225  5627  5673 I jxcore-log: 
10-19 10:26:43.225  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.225  5627  5673 I jxcore-log: 
10-19 10:26:43.225  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.225  5627  5673 I jxcore-log: 
10-19 10:26:43.225  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.225  5627  5673 I jxcore-log: 
10-19 10:26:43.226  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-19 10:26:43.226  5627  5673 I jxcore-log: 
10-19 10:26:43.226  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:4,3.226  5627  5673 I jxcore-log: 
10-19 10:26:43.226  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-19 10:26:43.226  5627  5673 I jxcore-log: 
10-19 10:26:43.226  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.226  5627  5673 I jxcore-log: 
10-19 10:26:43.226  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-19 10:26:43.226  5627  5673 I jxcore-log: 
10-19 10:26:43.227  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.227  5627  5673 I jxcore-log: 
10-19 10:26:43.227  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-19 10:26:43.227  5627  5673 I jxcore-log: 
10-19 10:26:43.227  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.227  5627  5673 I jxcore-log: 
10-19 10:26:43.227  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.227  5627  5673 I jxcore-log: 
10-19 10:26:43.228  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.228  5627  5673 I jxcore-log: 
10-19 10:26:43.228  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.228  5627  5673 I jxcore-log: 
10-19 10:26:43.228  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.228  5627  5673 I jxcore-log: 
10-19 10:26:43.228  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.228  5627  5673 I jxcore-log: 
10-19 10:26:43.229  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.229  5627  5673 I jxcore-log: 
10-19 10:26:43.229  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.229  5627  5673 I jxcore-log: 
10-19 10:26:43.230  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.230  5627  5673 I jxcore-log: 
10-19 10:26:43.230  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.230  5627  5673 I jxcore-log: 
10-19 10:26:43.231  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.231  5627  5673 I jxcore-log: 
,10-19 10:26:43.231  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.231  5627  5673 I jxcore-log: 
10-19 10:26:43.231  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.231  5627  5673 I jxcore-log: 
10-19 10:26:43.231  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.231  5627  5673 I jxcore-log: 
10-19 10:26:43.232  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.232  5627  5673 I jxcore-log: 
10-19 10:26:43.232  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.232  5627  5673 I jxcore-log: 
10-19 10:26:43.232  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.232  5627  5673 I jxcore-log: 
10-19 10:26:43.232  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.232  5627  5673 I jxcore-log: 
10-19 10:26:43.232  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.232  5627  5673 I jxcore-log: 
10-19 10:26:43.232  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.232  5627  5673 I jxcore-log: 
10-19 10:26:43.233  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.233  5627  5673 I jxcore-log: 
,10-19 10:26:43.233  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.233  5627  5673 I jxcore-log: 
10-19 10:26:43.233  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.233  5627  5673 I jxcore-log: 
10-19 10:26:43.233  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.233  5627  5673 I jxcore-log: 
10-19 10:26:43.233  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.233  5627  5673 I jxcore-log: 
10-19 10:26:43.234  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.234  5627  5673 I jxcore-log: 
10-19 10:26:43.234  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.234  5627  5673 I jxcore-log: 
10-19 10:26:43.234  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.234  5627  5673 I jxcore-log: 
10-19 10:26:43.234  5627  5627 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
10-19 10:26:43.234  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.234  5627  5673 I jxcore-log: 
10-19 10:26:43.234  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.234  5627  5673 I jxcore-log: 
10-19 10:26:43.235  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-19 10:26:43.235  5627  5673 I jxcore-log: 
,10-19 10:26:43.235  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.235  5627  5673 I jxcore-log: 
10-19 10:26:43.235  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-19 10:26:43.235  5627  5673 I jxcore-log: 
10-19 10:26:43.235  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.235  5627  5673 I jxcore-log: 
10-19 10:26:43.235  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
10-19 10:26:43.235  5627  5673 I jxcore-log: 
10-19 10:26:43.235  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.235  5627  5673 I jxcore-log: 
10-19 10:26:43.236  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.236  5627  5673 I jxcore-log: 
10-19 10:26:43.236  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.236  5627  5673 I jxcore-log: 
10-19 10:26:43.236  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.236  5627  5673 I jxcore-log: 
10-19 10:26:43.236  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.236  5627  5673 I jxcore-log: 
,10-19 10:26:43.236  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.236  5627  5673 I jxcore-log: 
10-19 10:26:43.237  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.237  5627  5673 I jxcore-log: 
10-19 10:26:43.237  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
10-19 10:26:43.237  5627  5673 I jxcore-log: 
10-19 10:26:43.237  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.237  5627  5673 I jxcore-log: 
10-19 10:26:43.237  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
10-19 10:26:43.237  5627  5673 I jxcore-log: 
10-19 10:26:43.237  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
10-19 10:26:43.237  5627  5673 I jxcore-log: 
10-19 10:26:43.238  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
10-19 10:26:43.238  5627  5673 I jxcore-log: 
,10-19 10:26:43.238  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
10-19 10:26:43.238  5627  5673 I jxcore-log: 
10-19 10:26:43.238  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-19 10:26:43.238  5627  5673 I jxcore-log: 
10-19 10:26:43.238  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.238  5627  5673 I jxcore-log: 
10-19 10:26:43.239  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
10-19 10:26:43.239  5627  5673 I jxcore-log: 
10-19 10:26:43.239  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
10-19 10:26:43.239  5627  5673 I jxcore-log: 
,10-19 10:26:43.244  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
10-19 10:26:43.244  5627  5673 I jxcore-log: 
10-19 10:26:43.244  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - WARN testUtils: 'myNameCallback not set!'
10-19 10:26:43.244  5627  5673 I jxcore-log: 
,10-19 10:26:43.245  5627  5673 E JX-Cordova: jxcore.CallJSMethod :{"isFulfilled":false,"isRejected":false}
,10-19 10:26:43.246  5627  5673 I jxcore-log: 2016-10-19 14:26:43 - DEBUG UnitTest_app: 'Running for WIFI network type'
10-19 10:26:43.246  5627  5673 I jxcore-log: 
,10-19 10:26:45.279  5627  5673 I jxcore-log: 2016-10-19 14:26:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
10-19 10:26:45.279  5627  5673 I jxcore-log: 
,10-19 10:26:45.612  5627  5673 I jxcore-log: 2016-10-19 14:26:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
10-19 10:26:45.612  5627  5673 I jxcore-log: 
,10-19 10:26:45.636  5627  5673 I jxcore-log: 2016-10-19 14:26:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
10-19 10:26:45.636  5627  5673 I jxcore-log: 
,10-19 10:26:46.132   932  2964 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,10-19 10:26:46.733  5627  5673 I jxcore-log: 2016-10-19 14:26:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
10-19 10:26:46.733  5627  5673 I jxcore-log: 
,10-19 10:26:46.883  5627  5673 I jxcore-log: 2016-10-19 14:26:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
10-19 10:26:46.883  5627  5673 I jxcore-log: 
,10-19 10:26:46.889  5627  5673 I jxcore-log: 2016-10-19 14:26:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
10-19 10:26:46.889  5627  5673 I jxcore-log: 
,10-19 10:26:46.894  5627  5673 I jxcore-log: 2016-10-19 14:26:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
10-19 10:26:46.894  5627  5673 I jxcore-log: 
,10-19 10:26:47.376  5627  5673 I jxcore-log: 2016-10-19 14:26:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
10-19 10:26:47.376  5627  5673 I jxcore-log: 
,10-19 10:26:47.420  5627  5673 I jxcore-log: 2016-10-19 14:26:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
10-19 10:26:47.420  5627  5673 I jxcore-log: 
,10-19 10:26:47.433  5627  5673 I jxcore-log: 2016-10-19 14:26:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
10-19 10:26:47.433  5627  5673 I jxcore-log: 
,10-19 10:26:47.437  5627  5673 I jxcore-log: 2016-10-19 14:26:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
10-19 10:26:47.437  5627  5673 I jxcore-log: 
,10-19 10:26:47.723  5627  5673 I jxcore-log: 2016-10-19 14:26:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
10-19 10:26:47.723  5627  5673 I jxcore-log: 
,10-19 10:26:47.853  5627  5673 I jxcore-log: 2016-10-19 14:26:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
10-19 10:26:47.853  5627  5673 I jxcore-log: 
,10-19 10:26:48.227  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
10-19 10:26:48.227  5627  5673 I jxcore-log: 
,10-19 10:26:48.234  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
10-19 10:26:48.234  5627  5673 I jxcore-log: 
,10-19 10:26:48.237  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
10-19 10:26:48.237  5627  5673 I jxcore-log: 
,10-19 10:26:48.242  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
10-19 10:26:48.242  5627  5673 I jxcore-log: 
,10-19 10:26:48.247  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
10-19 10:26:48.247  5627  5673 I jxcore-log: 
,10-19 10:26:48.274  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
10-19 10:26:48.274  5627  5673 I jxcore-log: 
,10-19 10:26:48.308  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
10-19 10:26:48.308  5627  5673 I jxcore-log: 
,10-19 10:26:48.315  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
10-19 10:26:48.315  5627  5673 I jxcore-log: 
,10-19 10:26:48.321  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
10-19 10:26:48.321  5627  5673 I jxcore-log: 
,10-19 10:26:48.337  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
10-19 10:26:48.337  5627  5673 I jxcore-log: 
,10-19 10:26:48.341  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
10-19 10:26:48.341  5627  5673 I jxcore-log: 
,10-19 10:26:48.347  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
10-19 10:26:48.347  5627  5673 I jxcore-log: 
,10-19 10:26:48.352  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
10-19 10:26:48.352  5627  5673 I jxcore-log: 
,10-19 10:26:48.365  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
10-19 10:26:48.365  5627  5673 I jxcore-log: 
,10-19 10:26:48.387  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
10-19 10:26:48.387  5627  5673 I jxcore-log: 
,10-19 10:26:48.398  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
10-19 10:26:48.398  5627  5673 I jxcore-log: 
,10-19 10:26:48.409  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
10-19 10:26:48.409  5627  5673 I jxcore-log: 
,10-19 10:26:48.420  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
10-19 10:26:48.420  5627  5673 I jxcore-log: 
,10-19 10:26:48.433  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
10-19 10:26:48.433  5627  5673 I jxcore-log: 
,10-19 10:26:48.443  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
10-19 10:26:48.443  5627  5673 I jxcore-log: 
,10-19 10:26:48.448  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
10-19 10:26:48.448  5627  5673 I jxcore-log: 
,10-19 10:26:48.468  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
10-19 10:26:48.468  5627  5673 I jxcore-log: 
,10-19 10:26:48.475  5627  5673 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,10-19 10:26:48.476  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - INFO testUtils: 'BLE multiple advertisement supported'
10-19 10:26:48.476  5627  5673 I jxcore-log: 
,10-19 10:26:48.636  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - DEBUG CoordinatedClient: 'connected to the test server'
10-19 10:26:48.636  5627  5673 I jxcore-log: 
,10-19 10:26:48.859  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
10-19 10:26:48.859  5627  5673 I jxcore-log: 
,10-19 10:26:48.862  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - DEBUG CoordinatedClient: 'test client failed'
10-19 10:26:48.862  5627  5673 I jxcore-log: 
,10-19 10:26:48.867  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - DEBUG CoordinatedClient: 'device disconnected from the test server'
10-19 10:26:48.867  5627  5673 I jxcore-log: 
,10-19 10:26:48.874  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-19 10:26:48.874  5627  5673 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-19 10:26:48.874  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-19 10:26:48.874  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-19 10:26:48.874  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-19 10:26:48.874  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
10-19 10:26:48.874  5627  5673 I jxcore-log: 
,10-19 10:26:48.874  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
10-19 10:26:48.874  5627  5673 I jxcore-log: 
10-19 10:26:48.877  5627  5673 I jxcore-log: 2016-10-19 14:26:48 - ERROR runTests: 'Test client failed: Native unit tests failed
10-19 10:26:48.877  5627  5673 I jxcore-log: CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:184:20
10-19 10:26:48.877  5627  5673 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
10-19 10:26:48.877  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
10-19 10:26:48.877  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
10-19 10:26:48.877  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
10-19 10:26:48.877  5627  5673 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13'
10-19 10:26:48.877  5627  5673 I jxcore-log: 
,10-19 10:26:49.440  5931  5931 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,10-19 10:26:49.445  5931  5931 D AndroidRuntime: CheckJNI is OFF
,10-19 10:26:49.474  5931  5931 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,10-19 10:26:49.509  5931  5931 I Radio-JNI: register_android_hardware_Radio DONE
,10-19 10:26:49.527  5931  5931 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,10-19 10:26:49.536   932   945 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,10-19 10:26:49.537   932   945 I ActivityManager: Killing 5627:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,10-19 10:26:49.633   932  3592 I WindowState: WIN DEATH: Window{ba5ecc1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,10-19 10:26:49.633   932   942 D GraphicsStats: Buffer count: 2
10-19 10:26:49.633   932  2962 D WifiService: Client connection lost with reason: 4
,10-19 10:26:49.668   932   945 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,10-19 10:26:49.668   932   945 W PackageManager: Package com.test.thalitest is missing; assuming frozen
10-19 10:26:49.669   932   945 E ActivityManager: Failure starting process com.test.thalitest
10-19 10:26:49.669   932   945 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
10-19 10:26:49.669   932   945 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:49.669   932   945 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:49.669   932   945 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-19 10:26:49.669   932   945 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-19 10:26:49.669   932   945 I ActivityManager:   Force finishing activity ActivityRecord{ffe9d3a u0 com.test.thalitest/.MainActivity t2}
10-19 10:26:49.671   932   955 I art     : Starting a blocking GC Explicit
,10-19 10:26:49.677   932   943 W ActivityManager: Spurious death for ProcessRecord{ad01f31 0:com.test.thalitest/u0a77}, curProc for 5627: null
,10-19 10:26:49.681   932   950 W WindowManager: Attempted to add application window with unknown token Token{82ccdeb ActivityRecord{ffe9d3a u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
10-19 10:26:49.682   932   950 W WindowManager: Token{82ccdeb ActivityRecord{ffe9d3a u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{82ccdeb ActivityRecord{ffe9d3a u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
10-19 10:26:49.682   932   950 W WindowManager: view not successfully added to wm, removing view
10-19 10:26:49.682   932   950 W WindowManager: Exception when adding starting window
10-19 10:26:49.682   932   950 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{effe1f0 V.E...... R.....ID 0,0-0,0} not attached to window manager
10-19 10:26:49.682   932   950 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
10-19 10:26:49.682   932   950 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
10-19 10:26:49.682   932   950 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
10-19 10:26:49.682   932   950 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
10-19 10:26:49.682   932   950 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
10-19 10:26:49.682   932   950 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:49.682   932   950 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:49.682   932   950 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-19 10:26:49.682   932   950 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,10-19 10:26:49.753   932   955 I art     : Explicit concurrent mark sweep GC freed 45522(2MB) AllocSpace objects, 9(272KB) LOS objects, 33% free, 28MB/43MB, paused 1.600ms total 81.550ms
,10-19 10:26:49.772   932   955 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,10-19 10:26:49.776  5931  5931 I art     : System.exit called, status: 0
,10-19 10:26:49.776  5931  5931 I AndroidRuntime: VM exiting with result code 0.
,10-19 10:26:49.780   932   955 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,10-19 10:26:49.788   932   945 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,10-19 10:26:49.793  5829  5829 D BluetoothMapAppObserver: onReceive
10-19 10:26:49.793  5829  5829 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
10-19 10:26:49.796  4061  4190 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
10-19 10:26:49.797  3680  3680 I Keyboard.Facilitator: resetDictionaries() : en_US
,10-19 10:26:49.804   932  2900 I InputReader: Reconfiguring input devices.  changes=0x00000010
,10-19 10:26:49.821  3402  5943 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,10-19 10:26:49.824  3680  5942 I Keyboard.Facilitator.DecoderInitializer: run()
,10-19 10:26:49.847  3801  3801 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,10-19 10:26:49.865  3680  5942 I Decoder : createOrResetDecoder
,10-19 10:26:49.866  3576  3576 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
10-19 10:26:49.866  3576  3576 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,10-19 10:26:49.875   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,10-19 10:26:49.878   407   407 W kworker/3:2: type=1400 audit(0.0:124): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-19 10:26:49.881   407   407 W kworker/3:2: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-19 10:26:49.895   407   407 W kworker/3:2: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,10-19 10:26:49.908  3576  3576 I ConfigService: onCreate
,10-19 10:26:49.910  3402  3423 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjABA3B19EC) - 
,10-19 10:26:49.911  3576  5949 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-19 10:26:49.911  3576  5949 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
10-19 10:26:49.911  3576  5949 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
10-19 10:26:49.913  3576  5949 W SQLiteOpenHelper: Opened config.db in read-only mode
,10-19 10:26:49.922  3680  5942 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,10-19 10:26:49.925  3721  5948 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,10-19 10:26:49.925  3721  5948 D AccountUtils: Clearing selected account for com.test.thalitest
,10-19 10:26:49.961  3721  5948 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,10-19 10:26:49.981  3402  5943 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,10-19 10:26:49.981  3402  5943 I Process : Sending signal. PID: 3402 SIG: 9
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:49.982  3721  5948 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQ,LiteDatabase.open(SQLiteDatabase.java:791)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
10-19 10:26:49.983  3721  5948 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
10-19 10:26:49.984  3721  5948 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,10-19 10:26:50.061  3721  5955 I GMPM-SVC: App measurement is starting up
,10-19 10:26:50.071  3721  5955 E GMPM-SVC: AppMeasurementService not registered/enabled
,10-19 10:26:50.072  3721  5955 E GMPM-SVC: Uploading is not possible. App measurement disabled
,10-19 10:26:50.105   932  3592 I ActivityManager: Process android.process.acore (pid 3402) has died
,10-19 10:26:50.106   932  3592 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,10-19 10:26:50.288   381   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
