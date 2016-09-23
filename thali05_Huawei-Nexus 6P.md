#### Test 864825820901bf9_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 06:04:11.343   929  5248 D NetlinkSocketObserver: NeighborEvent{elapsedMs=181705, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 06:04:11.793  5489  5489 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 06:04:11.799  5489  5489 D AndroidRuntime: CheckJNI is OFF
09-23 06:04:11.827  5489  5489 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 06:04:11.860  5489  5489 I Radio-JNI: register_android_hardware_Radio DONE
09-23 06:04:11.875  5489  5489 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 06:04:11.889   929  3603 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 06:04:11.931   929  3603 I ActivityManager: Start proc 5498:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 06:04:11.936  5489  5489 D AndroidRuntime: Shutting down VM
,09-23 06:04:12.266   929  3142 I WindowManager: Screenshot max retries 4 of Token{8409a2b ActivityRecord{e8cf27a u0 com.test.thalitest/.MainActivity t2}} appWin=Window{dd356d2 u0 Starting com.test.thalitest} drawState=4
,09-23 06:04:12.332  5498  5498 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 06:04:12.366  5498  5498 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 06:04:12.439  5498  5498 I LibraryLoader: Time to load native libraries: 68 ms (timestamps 2734-2802)
,09-23 06:04:12.439  5498  5498 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 06:04:12.476  5498  5498 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b4736d0}
,09-23 06:04:12.477  5498  5498 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 06:04:12.477  5498  5498 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 06:04:12.480  5498  5498 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-23 06:04:12.481  5498  5498 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 06:04:12.517  5498  5498 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 06:04:12.526  5498  5498 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 06:04:12.526  5498  5498 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 06:04:12.526  5498  5498 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 06:04:12.526  5498  5498 I Adreno  : Build Date                       : 12/06/15
09-23 06:04:12.526  5498  5498 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 06:04:12.526  5498  5498 I Adreno  : Local Branch                     : mybranch17112971
09-23 06:04:12.526  5498  5498 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 06:04:12.526  5498  5498 I Adreno  : Remote Branch                    : NONE
09-23 06:04:12.526  5498  5498 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 06:04:12.558   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5936391:true
,09-23 06:04:12.577   701   701 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[30054]" dev="sockfs" ino=30054 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:04:12.577   701   701 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[30054]" dev="sockfs" ino=30054 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:04:12.591  5498  5498 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 06:04:12.598  5498  5498 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 06:04:12.617   406   406 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[31501]" dev="sockfs" ino=31501 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:04:12.617   406   406 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[31501]" dev="sockfs" ino=31501 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:12.621  5498  5535 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 06:04:12.620  3805  3805 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[17378]" dev="sockfs" ino=17378 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 06:04:12.620  3805  3805 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[17378]" dev="sockfs" ino=17378 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 06:04:12.626  5498  5522 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 06:04:12.650  5498  5535 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 06:04:12.718   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +448ms (total +814ms)
,09-23 06:04:12.763  5498  5498 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5498
,09-23 06:04:12.854  5498  5498 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 06:04:12.980  5498  5537 D jxcore_app_log: JniHelper::setJavaVM(0xf4fbc000), pthread_self() = -564659920
,09-23 06:04:12.984  5498  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 06:04:12.984  5498  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 06:04:12.984  5498  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 06:04:12.984  5498  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 06:04:12.984  5498  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 06:04:12.984  5498  5537 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69abbc1 added. We now have 1 listener(s)
,09-23 06:04:12.987  5498  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 06:04:12.987  5498  5537 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 06:04:12.988  5498  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:04:12.988  5498  5537 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 06:04:12.990  5498  5537 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@189a354 added. We now have 1 listener(s)
09-23 06:04:12.990  5498  5537 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 06:04:12.996  5498  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:04:12.996  5498  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 06:04:12.996   929  2989 D WifiService: New client listening to asynchronous messages
09-23 06:04:12.996  5498  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-23 06:04:12.996  5498  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 06:04:12.996  5498  5537 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-23 06:04:12.998  5498  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:12.998  5498  5537 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 06:04:13.002  5498  5537 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:13.003  5498  5537 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:04:13.003  5498  5537 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 06:04:13.003  5498  5537 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 06:04:13.003  5498  5537 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 06:04:13.007  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:13.013  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:13.021  5498  5498 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 06:04:13.287  5498  5544 W jxcore-log: Initializing JXcore engine
09-23 06:04:13.287  5498  5544 W jxcore-log: JXcore engine is ready
,09-23 06:04:13.310  5544  5544 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12417 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-23 06:04:13.310  5544  5544 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12910]" dev="sockfs" ino=12910 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-23 06:04:13.310  5544  5544 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 06:04:13.310  5544  5544 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31479]" dev="sockfs" ino=31479 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 06:04:13.321  5498  5544 W jxcore-log: Starting JXcore engine
,09-23 06:04:13.380  5498  5544 W jxcore-log: Platform android
09-23 06:04:13.380  5498  5544 W jxcore-log: 
09-23 06:04:13.380  5498  5544 W jxcore-log: Process ARCH arm
09-23 06:04:13.380  5498  5544 W jxcore-log: 
,09-23 06:04:13.473  5498  5544 I jxcore-log: JXcore Cordova bridge is ready!
09-23 06:04:13.473  5498  5544 I jxcore-log: 
,09-23 06:04:13.473  5498  5544 W jxcore-log: JXcore engine is started
,09-23 06:04:13.479  5498  5537 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 06:04:13.482  5498  5498 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 06:04:19.543   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:04:20.044  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 06:04:20.044  5498  5544 I jxcore-log: 
,09-23 06:04:20.045  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 06:04:20.045  5498  5544 I jxcore-log: 
,09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:20.049  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:04:20.051  5498  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:04:20.053  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 06:04:20.053  5498  5544 I jxcore-log: 
09-23 06:04:20.054  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 06:04:20.054  5498  5544 I jxcore-log: 
,09-23 06:04:20.414  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:04:20.414  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4a3e092 added. We now have 2 listener(s)
09-23 06:04:20.415  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:20.415  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:04:20.415  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 06:04:20.415  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:04:20.415  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b1f4a63 added. We now have 2 listener(s)
09-23 06:04:20.415  5498  5544 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:04:20.416  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:04:20.418  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:20.421  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:04:20.422  5498  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:20.422  5498  5544 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 06:04:20.423  5498  5544 D ExecuteNativeTests: Running unit tests
,09-23 06:04:20.424  5498  5544 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 06:04:20.425   929  3175 D WifiService: setWifiEnabled: true pid=5498, uid=10077
09-23 06:04:20.425   929  3175 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:04:20.429  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:20.435  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:20.544   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:04:21.545   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:04:22.546   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:04:23.547   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:04:24.548   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 06:04:30.431  5498  5544 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 06:04:30.501  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:04:30.501  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74616fd added. We now have 3 listener(s)
09-23 06:04:30.502  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:30.502  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:04:30.502  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:04:30.502  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 06:04:30.502  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8870ff2 added. We now have 3 listener(s)
09-23 06:04:30.503  5498  5544 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:04:30.504  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:04:30.507  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:30.511  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:04:30.512  5498  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:04:30.512  5498  5544 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:04:30.518  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,09-23 06:04:30.519  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:04:30.519  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 06:04:30.519  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:04:30.519  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:04:30.519  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:30.520  5498  5544 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 06:04:30.520  5498  5544 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-23 06:04:30.520  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:04:30.520  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:30.521  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:30.521  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:30.521  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-23 06:04:30.521  5498  5544 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 06:04:30.522  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-23 06:04:30.524  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-23 06:04:30.524  5498  5544 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-23 06:04:30.526  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:30.526  5498  5544 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:04:30.527  5498  5544 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-23 06:04:30.527  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-23 06:04:30.527  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 06:04:30.527  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:04:30.527  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:04:30.527  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:30.527  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:04:30.528  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:04:30.528  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:04:30.528  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:04:30.528  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:04:30.528  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:30.528  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:04:30.529  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-23 06:04:30.530  5498  5544 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:04:30.530  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 06:04:30.532  5498  5546 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:04:30.535  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:04:30.536  5498  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:04:30.537  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:04:30.538  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:04:30.530  4701  4701 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28646]" dev="sockfs" ino=28646 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:30.539  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:04:30.539  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:30.539  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
,09-23 06:04:30.530  4701  4701 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28646]" dev="sockfs" ino=28646 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:30.540  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:30.540  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:30.540  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:04:30.541  5498  5544 D BluetoothAdapter: STATE_ON
,09-23 06:04:30.544  4477  4492 D BtGatt.GattService: registerClient() - UUID=0b5c9a5d-852a-4d56-a313-33f2ec55cca1
,09-23 06:04:30.544  4477  4565 D BtGatt.GattService: onClientRegistered() - UUID=0b5c9a5d-852a-4d56-a313-33f2ec55cca1, clientIf=5
,09-23 06:04:30.546  5498  5508 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:04:30.550  4477  4568 D BtGatt.AdvertiseManager: message : 0
,09-23 06:04:30.552  4477  4568 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:04:30.568  4477  4565 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:04:30.575  4477  4565 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:04:30.577  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:04:30.577  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 06:04:30.577  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:04:30.578  5498  5544 I io.jxcore.node.ConnectionHelper: start: OK
09-23 06:04:30.578  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:30.579  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:04:30.579  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:04:30.579  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-23 06:04:30.579  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:04:30.579  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:04:30.582  5498  5498 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:04:30.583  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:04:31.081  5498  5544 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 06:04:31.082  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 06:04:31.083  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 06:04:31.084  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 06:04:31.084  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 06:04:31.085  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 06:04:31.085  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:04:31.085  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-23 06:04:31.085  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 06:04:31.085  5498  5498 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:04:31.085  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 06:04:31.085  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 06:04:31.086  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 06:04:31.086  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 06:04:31.086  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:04:31.087  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:04:31.087  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:04:31.087  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:04:31.087  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:04:31.088  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:04:31.088  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:04:31.088  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:04:31.088  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-23 06:04:31.088  5498  5546 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:04:31.088  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:04:31.088  5498  5546 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:04:31.088  5498  5546 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:04:31.089  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:04:31.090  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:31.091  5498  5544 D BluetoothLeScanner: could not find callback wrapper
,09-23 06:04:31.091  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:04:31.091  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:04:31.092  4477  4568 D BtGatt.AdvertiseManager: message : 1
09-23 06:04:31.093  4477  4568 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:04:31.106  4477  4565 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:04:31.106  4477  4565 D BtGatt.GattService: Client app is not null!
09-23 06:04:31.108  4477  4735 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:04:31.109  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 06:04:31.109  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:31.109  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:04:31.109  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:04:31.109  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 06:04:31.111  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:31.111  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-23 06:04:31.111  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:04:31.112  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:04:31.115  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 06:04:31.115  5498  5498 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:04:31.115  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:31.116  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 06:04:31.116  5498  5498 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:04:31.116  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:04:31.124  5498  5544 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:04:31.125  5498  5544 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-23 06:04:31.125  5498  5544 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-23 06:04:31.125  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-23 06:04:31.130  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:31.130  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:04:31.130  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:04:31.130  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:31.131  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:04:31.132  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:04:31.132  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:04:31.132  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:04:31.132  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
,09-23 06:04:31.132  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:31.132  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:04:31.133  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:04:31.133  5498  5549 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:04:31.130  4735  4735 W Binder_4: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30078]" dev="sockfs" ino=30078 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:31.136  5498  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:04:31.130  4735  4735 W Binder_4: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30078]" dev="sockfs" ino=30078 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:31.137  5498  5544 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:04:31.138  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 06:04:31.142  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:04:31.143  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:04:31.143  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:04:31.145  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 06:04:31.145  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:31.146  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-23 06:04:31.146  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:31.146  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:31.146  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 06:04:31.147  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:31.149  4477  4490 D BtGatt.GattService: registerClient() - UUID=b05eba01-89c1-42d5-bca1-3d124be86ad3
,09-23 06:04:31.150  4477  4565 D BtGatt.GattService: onClientRegistered() - UUID=b05eba01-89c1-42d5-bca1-3d124be86ad3, clientIf=5
09-23 06:04:31.150  5498  5508 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:04:31.151  4477  4568 D BtGatt.AdvertiseManager: message : 0
,09-23 06:04:31.153  4477  4568 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:04:31.164  4477  4565 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:04:31.171  4477  4565 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:04:31.172  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:04:31.172  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 06:04:31.174  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:04:31.175  5498  5544 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 06:04:31.175  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:31.175  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:04:31.175  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:04:31.175  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:04:31.175  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:04:31.175  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 06:04:31.178  5498  5498 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:04:31.178  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:04:31.678  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
09-23 06:04:31.679  5498  5544 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:04:31.679  5498  5544 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:04:31.679  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 06:04:31.679  5498  5544 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-23 06:04:31.679  5498  5544 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-23 06:04:31.679  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 06:04:31.680  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 06:04:31.682  4477  4568 D BtGatt.AdvertiseManager: message : 1
,09-23 06:04:31.685  4477  4568 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:04:31.701  4477  4565 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:04:31.701  4477  4565 D BtGatt.GattService: Client app is not null!
,09-23 06:04:31.702  4477  4490 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:04:31.703  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:04:31.703  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:31.704  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:04:31.704  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:04:31.704  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:31.704  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,09-23 06:04:31.704  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:31.705  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:31.705  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:04:31.707  5498  5544 D BluetoothAdapter: STATE_ON
,09-23 06:04:31.714  4477  4492 D BtGatt.GattService: registerClient() - UUID=5f68fbc2-1b27-431c-b26e-3121ba175f1b
,09-23 06:04:31.714  4477  4565 D BtGatt.GattService: onClientRegistered() - UUID=5f68fbc2-1b27-431c-b26e-3121ba175f1b, clientIf=5
09-23 06:04:31.715  5498  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:04:31.717  4477  4568 D BtGatt.AdvertiseManager: message : 0
,09-23 06:04:31.721  4477  4568 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:04:31.737  4477  4565 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:04:31.745  4477  4565 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:04:31.746  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 06:04:31.746  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:04:31.746  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:04:31.746  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 06:04:31.746  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 06:04:31.747  5498  5544 I io.jxcore.node.ConnectionHelper: start: OK
09-23 06:04:31.747  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:04:31.747  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:04:31.747  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:04:31.748  5498  5544 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 06:04:31.748  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 06:04:31.748  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 06:04:31.748  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:04:31.748  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:04:31.748  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:04:31.749  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:04:31.749  5498  5549 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 06:04:31.749  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:04:31.749  5498  5549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:04:31.749  5498  5549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:04:31.749  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:04:31.749  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:04:31.749  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:04:31.749  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-23 06:04:31.749  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:04:31.749  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:04:31.750  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:31.750  5498  5544 D BluetoothLeScanner: could not find callback wrapper
09-23 06:04:31.750  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:04:31.750  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-23 06:04:31.751  4477  4568 D BtGatt.AdvertiseManager: message : 1
09-23 06:04:31.752  4477  4568 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:04:31.761  4477  4565 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:04:31.761  4477  4565 D BtGatt.GattService: Client app is not null!
,09-23 06:04:31.762  4477  4735 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:04:31.762  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:04:31.762  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:31.763  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 06:04:31.763  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:04:31.763  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:04:31.765  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:31.765  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:04:31.765  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:04:31.766  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:04:31.767  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 06:04:31.768  5498  5498 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:04:31.768  5498  5498 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:04:31.768  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:31.768  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:31.768  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:04:31.771  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-23 06:04:31.771  5498  5544 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-23 06:04:31.773  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-23 06:04:31.773  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-23 06:04:31.774  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-23 06:04:31.775  5498  5544 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-23 06:04:31.776  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-23 06:04:31.776  5498  5544 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-23 06:04:31.777  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-23 06:04:31.778  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:04:31.778  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:31.778  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 06:04:31.778  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:04:31.779  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:04:31.779  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-23 06:04:31.780  5498  5544 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:04:31.780  5498  5544 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 06:04:31.780  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 06:04:31.784  5498  5544 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-23 06:04:31.785  5498  5544 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 06:04:31.785  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 06:04:31.786  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 06:04:31.787  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 06:04:31.787  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 06:04:31.787  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 06:04:31.787  5498  5544 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-23 06:04:31.787  5498  5544 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:04:31.787  5498  5544 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-23 06:04:31.787  5498  5544 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:04:31.788  5498  5544 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:04:31.788  5498  5544 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-23 06:04:31.788  5498  5544 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:04:31.788  5498  5544 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:04:31.788  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-23 06:04:31.793  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-23 06:04:31.794  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-23 06:04:31.794  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-23 06:04:31.796  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-23 06:04:31.797  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-23 06:04:31.797  5498  5544 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-23 06:04:31.797  5498  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 129)
09-23 06:04:31.797  5498  5544 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:04:31.797  5498  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-23 06:04:31.797  5498  5544 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-23 06:04:31.797  5498  5553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:31.794  4492  4492 W Binder_2: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[31745]" dev="sockfs" ino=31745 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:31.794  4492  4492 W Binder_2: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[31745]" dev="sockfs" ino=31745 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:31.799  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-23 06:04:31.799  5498  5544 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-23 06:04:31.801  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-23 06:04:31.801  5498  5544 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-23 06:04:31.802  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-23 06:04:31.802  5498  5544 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-23 06:04:31.802  5498  5544 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-23 06:04:31.802  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:04:31.802  5498  5544 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-23 06:04:31.802  5498  5544 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 06:04:31.802  5498  5544 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-23 06:04:31.803  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:04:31.803  5498  5544 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-23 06:04:31.803  5498  5544 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 06:04:31.803  5498  5544 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 06:04:31.803  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:04:31.803  5498  5544 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-23 06:04:31.804  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-23 06:04:31.804  5498  5544 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:04:31.804  5498  5544 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:04:31.804  5498  5544 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-23 06:04:31.804  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-23 06:04:31.804  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:31.804  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:04:31.804  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:04:31.804  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:31.804  4701  4701 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31751]" dev="sockfs" ino=31751 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:31.804  4701  4701 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31751]" dev="sockfs" ino=31751 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:31.806  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:04:31.807  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:04:31.807  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:04:31.807  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:04:31.807  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:04:31.807  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:04:31.807  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:31.807  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:04:31.808  5498  5554 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:31.810  5498  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:04:31.811  5498  5544 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:04:31.812  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:04:31.816  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:04:31.816  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:04:31.816  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:04:31.818  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:04:31.818  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:31.818  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-23 06:04:31.818  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:31.818  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:31.818  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:04:31.819  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:31.820  4477  4735 D BtGatt.GattService: registerClient() - UUID=be541b32-6923-4e62-b2d4-25063dcadce4
09-23 06:04:31.821  4477  4565 D BtGatt.GattService: onClientRegistered() - UUID=be541b32-6923-4e62-b2d4-25063dcadce4, clientIf=5
09-23 06:04:31.821  5498  5508 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:04:31.822  4477  4568 D BtGatt.AdvertiseManager: message : 0
,09-23 06:04:31.824  4477  4568 D BtGatt.AdvertiseManager: starting multi advertising
09-23 06:04:31.834  4477  4565 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-23 06:04:31.839  4477  4565 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-23 06:04:31.839  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:04:31.839  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:04:31.841  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:04:31.842  5498  5544 I io.jxcore.node.ConnectionHelper: start: OK
09-23 06:04:31.842  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:31.842  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:04:31.842  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:04:31.842  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:04:31.842  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:04:31.842  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 06:04:31.845  5498  5498 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:04:31.845  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:04:32.342  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 06:04:32.343  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:04:32.343  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-23 06:04:32.343  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:04:32.343  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:04:32.344  5498  5554 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 06:04:32.344  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-23 06:04:32.344  5498  5554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:04:32.344  5498  5554 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-23 06:04:32.344  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 06:04:32.344  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:04:32.344  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-23 06:04:32.344  5498  5498 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-23 06:04:32.345  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 06:04:32.347  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74616fd removed from the list
09-23 06:04:32.347  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:04:32.347  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:04:32.348  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:04:32.348  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 06:04:32.348  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:04:32.349  5498  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 129
09-23 06:04:32.349  5498  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 129)
09-23 06:04:32.350  4477  4699 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
,09-23 06:04:32.350  5498  5555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 129)
09-23 06:04:32.350  5498  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 129)
09-23 06:04:32.351  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:32.351  5498  5544 D BluetoothLeScanner: could not find callback wrapper
,09-23 06:04:32.351  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:04:32.351  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:04:32.354  4477  4568 D BtGatt.AdvertiseManager: message : 1
09-23 06:04:32.355  4477  4568 D BtGatt.AdvertiseManager: stop advertise for client 5
09-23 06:04:32.361   929  2988 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 06:04:32.366  4477  4565 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:04:32.366  4477  4565 D BtGatt.GattService: Client app is not null!
09-23 06:04:32.367  4477  4492 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:04:32.368  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:04:32.368  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:32.368  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:04:32.368  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:04:32.368  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:04:32.370  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:32.370  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:04:32.370  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 06:04:32.371  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:04:32.372  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8870ff2 removed from the list
09-23 06:04:32.372  5498  5544 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:04:32.372  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:04:32.372  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:32.372  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:32.372  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:04:32.374  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,09-23 06:04:32.375  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-23 06:04:32.375  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:32.375  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:04:32.376  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:04:32.376  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:04:32.376  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:04:32.376  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:04:32.376  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:04:32.377  5498  5556 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:32.378  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
09-23 06:04:32.378  5498  5544 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-23 06:04:32.379  5498  5544 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-23 06:04:32.379  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:04:32.379  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:32.374  4735  4735 W Binder_4: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[31529]" dev="sockfs" ino=31529 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:32.379  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:04:32.380  5498  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:04:32.374  4735  4735 W Binder_4: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[31529]" dev="sockfs" ino=31529 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:32.380  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,09-23 06:04:32.385  5498  5544 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,09-23 06:04:32.386  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 06:04:32.387  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:04:32.387  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:04:32.387  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:04:32.387  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:04:32.387  5498  5556 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:04:32.387  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-23 06:04:32.387  5498  5556 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:04:32.387  5498  5556 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:04:32.387  5498  5544 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74616fd not in the list
09-23 06:04:32.387  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:04:32.387  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:04:32.387  5498  5498 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:04:32.387  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:04:32.387  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:04:32.387  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:04:32.387  5498  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 06:04:32.387  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:04:32.388  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:04:32.389  5498  5544 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8870ff2 not in the list
,09-23 06:04:32.389  5498  5544 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:04:32.389  5498  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 06:04:32.389  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:04:32.389  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:32.389  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:32.389  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:32.391  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-23 06:04:32.391  5498  5544 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-23 06:04:32.391  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:04:32.391  5498  5544 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-23 06:04:32.391  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:04:32.391  5498  5544 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-23 06:04:32.391  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:04:32.392  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
09-23 06:04:32.392  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
09-23 06:04:32.393  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-23 06:04:32.394  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 06:04:32.394  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-23 06:04:32.394  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-23 06:04:32.394  5498  5544 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-23 06:04:32.394  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 06:04:32.394  5498  5544 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-23 06:04:32.394  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 06:04:32.394  5498  5544 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-23 06:04:32.394  5498  5544 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-23 06:04:32.395  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-23 06:04:32.395  5498  5544 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-23 06:04:32.395  5498  5544 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-23 06:04:32.395  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-23 06:04:32.395  5498  5544 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-23 06:04:32.396  5498  5544 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,09-23 06:04:32.396  5498  5544 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-23 06:04:32.396  5498  5544 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-23 06:04:32.396  5498  5544 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-23 06:04:32.396  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 06:04:32.396  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f59a2 added. We now have 3 listener(s)
09-23 06:04:32.398  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:32.399  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:04:32.399  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:04:32.399  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:04:32.399  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f4b633 added. We now have 3 listener(s)
,09-23 06:04:32.399  5498  5544 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 06:04:32.400  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 06:04:32.402  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:32.406  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:04:32.407  5498  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:32.408  5498  5544 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 06:04:32.409  5498  5544 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 06:04:32.409   929  3175 D WifiService: setWifiEnabled: true pid=5498, uid=10077
09-23 06:04:32.409   929  3175 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:04:32.410  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:32.411  5498  5544 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,09-23 06:04:32.413  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:32.414  5498  5544 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
,09-23 06:04:32.414  5498  5544 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-23 06:04:32.417   929  3175 D WifiService: setWifiEnabled: false pid=5498, uid=10077
,09-23 06:04:32.417   929  3175 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:04:32.420   929  2988 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-23 06:04:32.420   929  2988 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-23 06:04:32.420   929  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 06:04:32.421   929  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:04:32.427   929  5249 D DhcpClient: Clearing IP address
09-23 06:04:32.428   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:04:32.429   508   921 D CommandListener: Setting iface cfg
,09-23 06:04:32.431   929  5250 D DhcpClient: Receive thread stopped
09-23 06:04:32.436  3634  5304 V NativeCrypto: Read error: ssl=0x7fa8a82700: I/O error during system call, Connection timed out
09-23 06:04:32.438  3634  5304 V NativeCrypto: SSL shutdown failed: ssl=0x7fa8a82700: I/O error during system call, Broken pipe
09-23 06:04:32.440   929  3805 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-23 06:04:32.441   929  5247 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-23 06:04:32.441   929  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-23 06:04:32.441   929  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-23 06:04:32.443   534   534 E Parcel  : Reading a NULL string not supported here.
,09-23 06:04:32.446   929  5247 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-23 06:04:32.446   929   929 D RttService: SCAN_AVAILABLE : 1
09-23 06:04:32.446   929  3097 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 06:04:32.449   929  2990 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-23 06:04:32.451  3518  3729 W QCNEJ   : |CORE| network lost: 100
09-23 06:04:32.451  3518  3729 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
09-23 06:04:32.453   929  2988 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-23 06:04:32.456   929  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 06:04:32.479   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:04:32.499   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-23 06:04:32.499   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-23 06:04:32.499   508   921 D TetherController: Setting IP forward enable = 0
,09-23 06:04:32.500   929  2990 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-23 06:04:32.501   929  2990 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 06:04:32.502   929  2988 D DhcpClient: doQuit
09-23 06:04:32.502   929  2988 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 06:04:32.502   929  5249 D DhcpClient: onQuitting
09-23 06:04:32.505   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-23 06:04:32.507  3659  3659 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-23 06:04:32.508  5136  5136 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@680a06b and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:32.508  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:32.510  4833  4833 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-23 06:04:32.511  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:32.515  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:32.517  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:32.521  3909  3909 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:32.521  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:32.522  3659  3659 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 06:04:32.519  4924  4942 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 06:04:32.522  4924  4942 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 06:04:32.523  4924  4942 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 06:04:32.523  4924  4942 E SarControlService: no key has been found,reset the power
09-23 06:04:32.523  4924  4962 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 06:04:32.523  4924  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 06:04:32.523  4924  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 06:04:32.524  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:04:32.524  4950  4950 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 06:04:32.524  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:32.525  4924  4962 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 06:04:32.525  4924  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 06:04:32.525  4924  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 06:04:32.526  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:04:32.526  4950  4950 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 06:04:32.527  3659  3659 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:32.528  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:32.531  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:32.533  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:32.534  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:32.538  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ed05769 HexData = [00000000ea03000000000000ffffffff]
09-23 06:04:32.538  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:04:32.538  4950  4964 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,09-23 06:04:32.539  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:04:32.540  4924  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 06:04:32.541  3909  3909 D SystemUpdateService: onCreate
09-23 06:04:32.545  3909  3909 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-23 06:04:32.546  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ed05769 HexData = [00000000eb03000000000000ffffffff]
09-23 06:04:32.546  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:04:32.546  4950  4964 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-23 06:04:32.547  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:04:32.547  4924  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 06:04:32.553  3909  5576 I SystemUpdateService: active receiver: enabled
,09-23 06:04:32.555  3909  3909 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-23 06:04:32.560  3909  5273 I iu.UploadsManager: num queued entries: 0
,09-23 06:04:32.562  3909  3909 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-23 06:04:32.563  3909  3909 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-23 06:04:32.565  5275  5275 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 06:04:32.569  5275  5275 D SprintDMHelper: simOperator: 
09-23 06:04:32.569   508   921 E Netd    : netlink response contains error (No such file or directory)
09-23 06:04:32.569  5275  5275 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-23 06:04:32.570   508   921 D TetherController: Setting IP forward enable = 0
09-23 06:04:32.570   929  2990 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-23 06:04:32.570   929  2990 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 06:04:32.579  3909  5273 I iu.UploadsManager: num updated entries: 0
,09-23 06:04:32.580  3909  5273 I iu.SyncManager: NEXT; no task
,09-23 06:04:32.581  3909  5576 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-23 06:04:32.582  3659  3659 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 06:04:32.583  4321  5580 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 06:04:32.591  3909  5576 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-23 06:04:32.591  3909  5576 I SystemUpdateService: now status is 0 (complete)
09-23 06:04:32.591  3909  5576 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 06:04:32.591  3909  5576 I SystemUpdateService: file has been verified
09-23 06:04:32.591  3909  5576 I SystemUpdateService: OTA package size = 21989297
,09-23 06:04:32.593   929  3597 I ActivityManager: Start proc 5582:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-23 06:04:32.597  3659  3659 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 06:04:32.600  3909  5576 I SystemUpdateService: showing system update notification
,09-23 06:04:32.612  3909  3909 D SystemUpdateService: onDestroy
,09-23 06:04:32.630  5582  5582 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-23 06:04:32.638   929  3142 I ActivityManager: Killing 4882:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-23 06:04:32.705   929  2988 D wifi    : In wifi stop Hal
,09-23 06:04:32.705   929  2988 D wifi    : halHandle = 0x7f974bad20, mVM = 0x7fb35cd140, mCls = 0x100b1e
09-23 06:04:32.705   929  3656 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 06:04:32.705   929  3656 D WifiHAL : Got a signal to exit!!!
,09-23 06:04:32.705   929  3656 I WifiHAL : Exit wifi_event_loop
,09-23 06:04:32.705   929  2988 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-23 06:04:32.705   929  2988 E WifiHAL : Event processing terminated
09-23 06:04:32.706   929  2988 D wifi    : In wifi cleaned up handler
09-23 06:04:32.706   929  2988 I WifiHAL : Internal cleanup completed
09-23 06:04:32.708  4321  4321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:04:32.710  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:32.711  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:32.712  3498  4064 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:04:32.713  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:32.728   929  3656 D wifi    : set interface wlan0 flags (DOWN)
,09-23 06:04:32.729   929  2988 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 06:04:32.890  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 06:04:32.924  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:32.928   929  3603 D WifiService: setWifiEnabled: true pid=5498, uid=10077
,09-23 06:04:32.929   929  3603 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:04:32.935   508   921 D SoftapController: Softap fwReload - Ok
,09-23 06:04:32.938   929   946 D Tethering: InitialState.processMessage what=4
,09-23 06:04:32.939   508   921 D CommandListener: Setting iface cfg
,09-23 06:04:32.940   508   921 D CommandListener: Trying to bring down wlan0
09-23 06:04:32.941   508   921 D CommandListener: Clearing all IP addresses on wlan0
09-23 06:04:32.944   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 06:04:32.946   929  2988 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:04:33.435   929  3459 D WifiService: setWifiEnabled: true pid=5498, uid=10077
,09-23 06:04:33.437   929  3459 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:04:33.549   929  2988 D wifi    : set interface wlan0 flags (UP)
,09-23 06:04:33.549   929  2988 I WifiHAL : Initializing wifi
09-23 06:04:33.550   929  2988 I WifiHAL : Creating socket
09-23 06:04:33.555   929  2988 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-23 06:04:33.556   929  2988 D wifi    : Did set static halHandle = 0x7f974bad20
09-23 06:04:33.556   929  2988 D wifi    : halHandle = 0x7f974bad20, mVM = 0x7fb35cd140, mCls = 0x1642
09-23 06:04:33.556   929  2988 D wifi    : array field set
09-23 06:04:33.557   929  2988 I WifiNative-HAL: interface[0] = wlan0
09-23 06:04:33.559   929  5597 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547999165728
09-23 06:04:33.560   929  5597 D wifi    : waitForHalEvents called, vm = 0x7fb35cd140, obj = 0x1642, env = 0x7f94217f00
,09-23 06:04:33.565   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 06:04:33.634  5598  5598 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 06:04:33.658  5598  5598 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:04:33.662   929  2988 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 06:04:33.671  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:33.675  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:33.677  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:33.702  5598  5598 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:04:33.702  5598  5598 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 06:04:33.717   929  2988 D WifiConfigStore: Loading config and enabling all networks 
,09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:33.721  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:33.723  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:33.727  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:33.729   929  2988 D WifiConfigStore: loaded 0 passpoint configs
09-23 06:04:33.729  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:33.729   929  2988 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:04:33.729   929  2988 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 06:04:33.730   929  2988 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:33.731  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:33.732   929  2988 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-23 06:04:33.732   929  2988 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-23 06:04:33.732   929  2988 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 06:04:33.732   929  2988 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-23 06:04:33.733  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:33.736   929  2988 D WifiNative-HAL: Setting external_sim to 1
,09-23 06:04:33.736  4321  4321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:04:33.736   929  2988 D wifi    : setting dfs flag to true, 0x7f9df33960
,09-23 06:04:33.737   929  2988 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 06:04:33.737   929  2988 D wifi    : setting scan oui 0x7f9df33960
09-23 06:04:33.737   929  2988 D WifiHAL : Sending mac address OUI
,09-23 06:04:33.741   929  2988 E native  : do suspend false
,09-23 06:04:33.748   929  2988 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 06:04:33.748   929   929 D RttService: SCAN_AVAILABLE : 3
09-23 06:04:33.749   929  3097 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 06:04:33.749   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-23 06:04:33.749   508   921 D CommandListener: Setting iface cfg
,09-23 06:04:33.753   929  2987 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-23 06:04:33.753   929  2987 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 06:04:33.766   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=204129 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
09-23 06:04:33.766   929  2987 D WifiNative-HAL: p2pGetDeviceAddress
09-23 06:04:33.766   929  2987 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 06:04:33.943  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:33.956  4477  4561 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 06:04:33.956  4477  4561 D BluetoothAdapterProperties: Setting state to 13
09-23 06:04:33.956  4477  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 06:04:33.957  4477  4561 D BluetoothAdapterProperties: onBluetoothDisable()
,09-23 06:04:33.962  4477  4561 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:04:33.962  4477  4477 D BluetoothMapService: onReceive
09-23 06:04:33.962  4477  4477 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:04:33.962  4477  4477 D BluetoothMapService: STATE_TURNING_OFF
,09-23 06:04:33.963  4477  4477 D BluetoothMapService: MAP Service closeService in
,09-23 06:04:33.963  4477  4477 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 06:04:33.963  4477  4477 D ObexServerSockets0: shutdown(block = true)
09-23 06:04:33.964  4477  4477 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:04:33.964  4477  4737 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-23 06:04:33.964  4477  4477 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:04:33.964  4477  4699 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 06:04:33.964  4477  4738 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 06:04:33.966  4477  4477 I BtOppRfcommListener: stopping Accept Thread
,09-23 06:04:33.966  4477  5215 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 06:04:33.967  4477  5215 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 06:04:33.969  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:33.969  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:33.970  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:04:33.970  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:33.974  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:33.974  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:33.975  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:04:33.976  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:33.980   929   942 I ActivityManager: Start proc 5602:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-23 06:04:33.981  4477  4565 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:04:33.982  4477  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-23 06:04:33.983  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:33.983  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:33.985  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:04:33.985  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:33.986  4477  4477 D HeadsetService: Received stop request...Stopping profile...
,09-23 06:04:33.987  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:33.989  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:33.990  3566  3584 D BluetoothHeadset: Proxy object disconnected
09-23 06:04:33.990   929   929 D BluetoothHeadset: Proxy object disconnected
09-23 06:04:33.990   929   929 D BluetoothHeadset: Proxy object disconnected
09-23 06:04:33.990   929   929 D BluetoothHeadset: Proxy object disconnected
09-23 06:04:33.990  3145  3453 D BluetoothHeadset: Proxy object disconnected
09-23 06:04:33.991  3145  3145 D HeadsetProfile: Bluetooth service disconnected
09-23 06:04:33.991  4477  4477 D A2dpService: Received stop request...Stopping profile...
09-23 06:04:33.991  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:33.993  4477  4726 D A2dpStateMachine: Exit Disconnected: -1
09-23 06:04:33.994   929   929 D BluetoothA2dp: Proxy object disconnected
,09-23 06:04:33.995  3145  3145 D BluetoothA2dp: Proxy object disconnected
09-23 06:04:33.995  4477  4477 D HidService: Received stop request...Stopping profile...
09-23 06:04:33.995  4477  4477 D HidService: Stopping Bluetooth HidService
09-23 06:04:33.996  3145  3145 D BluetoothInputDevice: Proxy object disconnected
09-23 06:04:33.996  3145  3145 D HidProfile: Bluetooth service disconnected
09-23 06:04:33.996  4477  4477 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:04:33.996  4477  4477 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:33.997  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:33.997  4477  4477 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:33.997  4477  4477 D HealthService: Received stop request...Stopping profile...
09-23 06:04:33.998  4477  4477 D PanService: Received stop request...Stopping profile...
09-23 06:04:33.999  3145  3145 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:04:33.999  3145  3145 D PanProfile: Bluetooth service disconnected
09-23 06:04:33.999  4477  4477 D BluetoothMapService: Received stop request...Stopping profile...
09-23 06:04:34.000  4477  4477 D BluetoothMapService: stop()
09-23 06:04:34.000  4477  4477 D BluetoothMapAppObserver: deinitObservers()
09-23 06:04:34.001  4477  4477 D BluetoothMapAppObserver: removeReceiver()
,09-23 06:04:34.002  3145  3145 D BluetoothMap: Proxy object disconnected
09-23 06:04:34.002  3145  3145 D MapProfile: Bluetooth service disconnected
,09-23 06:04:34.005  4477  4477 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-23 06:04:34.007  4477  4477 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 06:04:34.008  4477  4683 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:34.008  4477  4683 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:34.008  4477  4683 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 06:04:34.008  4477  4477 D SapService: Received stop request...Stopping profile...
09-23 06:04:34.008  4477  4477 V SapService: stop()
09-23 06:04:34.009  4477  4565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 06:04:34.009  4477  4565 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-23 06:04:34.017  4477  4477 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:04:34.017  4477  4477 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:34.017  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:34.017  4477  4477 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:34.018  4477  4565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 06:04:34.018  4477  4683 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:34.018  4477  4683 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:34.018  4477  4683 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:04:34.018  4477  4477 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:34.018  4477  4683 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:04:34.018  4477  4683 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:04:34.018  4477  4477 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:34.018  4477  4683 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:04:34.018  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:34.018  4477  4477 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:04:34.019  4477  4477 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 06:04:34.019  4477  4477 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 06:04:34.019  4477  4565 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:04:34.019  4477  4477 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:34.019  4477  4477 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:34.019  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:34.019  4477  4477 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:34.020  4477  4477 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 06:04:34.020  4477  4565 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-23 06:04:34.020  4477  4477 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-23 06:04:34.020  4477  4477 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:34.021  4477  4477 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:34.021  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:34.021  4477  4477 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:34.021  4477  4477 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 06:04:34.021  4477  4477 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-23 06:04:34.022  4477  4477 D BluetoothMapService: MAP Service closeService in
,09-23 06:04:34.022  4477  4477 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:34.022  4477  4477 V BluetoothAdapterState: isTurningOn()=false
,09-23 06:04:34.022  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:34.022  4477  4477 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:34.023  4477  4477 D BluetoothMapService: cleanup()
09-23 06:04:34.023  4477  4477 D BluetoothMapService: MAP Service closeService in
09-23 06:04:34.023  4477  4477 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:34.023  4477  4477 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:34.023  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:34.023  4477  4477 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:04:34.024  4477  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 06:04:34.024  4477  4561 D BluetoothAdapterProperties: Setting state to 15
09-23 06:04:34.024  4477  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-23 06:04:34.024  4477  4561 I BluetoothAdapterState: Entering BleOnState
,09-23 06:04:34.025  3145  3157 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:04:34.026   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:04:34.026  3566  3590 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:34.026  3145  3159 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:04:34.027  3145  3453 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:04:34.028   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:34.028  3145  3157 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:04:34.028   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-23 06:04:34.028   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:34.028  3145  3159 D BluetoothMap: onBluetoothStateChange: up=false
09-23 06:04:34.029  3145  3453 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:34.029  4477  4561 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 06:04:34.029  4477  4561 D BluetoothAdapterProperties: Setting state to 16
09-23 06:04:34.029  4477  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 06:04:34.030  4477  4561 D BluetoothAdapterProperties: onBleDisable
09-23 06:04:34.030  4477  4561 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:04:34.031  4477  4562 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-23 06:04:34.032  4477  4683 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-23 06:04:34.032  4477  4683 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:34.034  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:34.034  5602  5602 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-23 06:04:34.036  4477  4565 D BluetoothAdapterProperties: Scan Mode:20
,09-23 06:04:34.039  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:34.040  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:34.042  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:34.043  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:34.044  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:34.052  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:04:34.060   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f4f74d5:true
,09-23 06:04:34.061  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:04:34.074   929  3806 I ActivityManager: Start proc 5614:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-23 06:04:34.087  5602  5602 D LocalBluetoothProfileManager: Adding local MAP profile
,09-23 06:04:34.091  5602  5602 D BluetoothMap: Create BluetoothMap proxy object
,09-23 06:04:34.105  5602  5602 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-23 06:04:34.113  5614  5614 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-23 06:04:34.121  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:04:34.127   929  3175 I ActivityManager: Killing 5136:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-23 06:04:34.246  4477  4565 I bt_hci  : shut_down
,09-23 06:04:34.251  4477  4570 D bt_hwcfg: hw_epilog_process
,09-23 06:04:34.251  4477  4570 I bt_vendor: low_power_mode_cb
,09-23 06:04:34.253  4477  4570 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 06:04:34.253  4477  4570 I bt_vendor: epilog_cb
09-23 06:04:34.253  4477  4570 I bt_hci  : epilog_finished_callback
,09-23 06:04:34.256  4477  4565 I bt_hci_h4: hal_close
,09-23 06:04:34.256  4477  4565 I bt_userial_vendor: device fd = 54 close
,09-23 06:04:34.301  5614  5614 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 06:04:34.301  5614  5614 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:04:34.301  5614  5614 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:04:34.301  5614  5614 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:04:34.301  5614  5614 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.k.d(PG:583)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.301  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:04:34.302  5614  5614 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:04:34.302  5614  5614 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:04:34.302  5614  5614 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:04:34.302  5614  5614 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:04:34.305  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 06:04:34.312  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:04:34.316  5602  5602 D DockEventReceiver: finishStartingService: stopping service
09-23 06:04:34.318   929  3596 I ActivityManager: Killing 4575:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-23 06:04:34.365  4477  4562 D bt_stack_manager: event_shut_down_stack finished.
09-23 06:04:34.365  4477  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 06:04:34.367  4477  4561 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 06:04:34.367  4477  4477 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:04:34.367  4477  4477 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 06:04:34.368  4477  4477 D BtGatt.GattService: stop()
09-23 06:04:34.368  4477  4477 D BtGatt.AdvertiseManager: advertise clients cleared
09-23 06:04:34.369  4477  4477 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:34.369  4477  4477 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:34.369  4477  4477 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:34.369  4477  4477 V BluetoothAdapterState: isBleTurningOff()=true
09-23 06:04:34.369  4477  4561 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 06:04:34.370  4477  4561 D BluetoothAdapterProperties: Setting state to 10
09-23 06:04:34.370  4477  4561 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 06:04:34.370  4477  4561 I BluetoothAdapterState: Entering OffState
09-23 06:04:34.371   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-23 06:04:34.376  4477  4477 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 06:04:34.376  4477  4477 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 06:04:34.376  4477  4477 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 06:04:34.377  4477  4562 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 06:04:34.385  4477  4477 I art     : System.exit called, status: 0
,09-23 06:04:34.385  4477  4477 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 06:04:34.418   929  3597 I ActivityManager: Process com.android.bluetooth (pid 4477) has died
,09-23 06:04:34.455  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:34.469   929   946 I ActivityManager: Start proc 5647:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 06:04:34.525  5647  5647 D AdapterServiceConfig: Adding HeadsetService
,09-23 06:04:34.526  5647  5647 D AdapterServiceConfig: Adding A2dpService
09-23 06:04:34.526  5647  5647 D AdapterServiceConfig: Adding HidService
09-23 06:04:34.526  5647  5647 D AdapterServiceConfig: Adding HealthService
09-23 06:04:34.526  5647  5647 D AdapterServiceConfig: Adding PanService
09-23 06:04:34.526  5647  5647 D AdapterServiceConfig: Adding GattService
09-23 06:04:34.526  5647  5647 D AdapterServiceConfig: Adding BluetoothMapService
09-23 06:04:34.526  5647  5647 D AdapterServiceConfig: Adding SapService
,09-23 06:04:34.533   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@58ed4f2:true
,09-23 06:04:34.534  5647  5647 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 06:04:34.536  5647  5647 I bt_bluedroid: init
,09-23 06:04:34.536  5647  5659 I BluetoothAdapterState: Entering OffState
,09-23 06:04:34.538  5647  5660 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 06:04:34.538  5647  5660 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 06:04:34.538  5647  5660 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 06:04:34.538  5647  5660 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-23 06:04:34.538  5647  5647 I bt_bluedroid: get_profile_interface socket
09-23 06:04:34.540  5647  5647 I bt_bluedroid: get_profile_interface sdp
,09-23 06:04:34.540  5647  5663 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 06:04:34.541  5647  5663 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:04:34.542  5647  5658 I bt_bluedroid: config_hci_snoop_log
,09-23 06:04:34.543   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-23 06:04:34.546  5647  5659 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 06:04:34.546  5647  5659 D BluetoothAdapterProperties: Setting state to 14
09-23 06:04:34.546  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 06:04:34.548  5647  5659 D BluetoothBondStateMachine: make
,09-23 06:04:34.549  5647  5664 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 06:04:34.551  5647  5659 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:04:34.552  5647  5647 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 06:04:34.553  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:34.553  5647  5647 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:04:34.554  5647  5647 D BtGatt.GattService: Received start request. Starting profile...
09-23 06:04:34.554  5647  5647 D BtGatt.GattService: start()
09-23 06:04:34.554  5647  5647 I bt_bluedroid: get_profile_interface gatt
,09-23 06:04:34.554  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:34.555  5647  5647 D BtGatt.AdvertiseManager: advertise manager created
,09-23 06:04:34.555  5614  5636 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-23 06:04:34.558  5647  5647 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:04:34.558  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:34.558  5647  5647 V BluetoothAdapterState: isBleTurningOn()=true
09-23 06:04:34.558  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:34.558  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 06:04:34.560  5647  5659 I bt_bluedroid: bt_bluedroid
,09-23 06:04:34.560  5647  5660 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 06:04:34.560  5647  5660 I bt_hci  : start_up
,09-23 06:04:34.565  5647  5660 I bt_vendor: alloc value 0xf3c89871
09-23 06:04:34.565  5647  5660 I bt_vendor: init
,09-23 06:04:34.565  5647  5660 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 06:04:34.565  5647  5660 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 06:04:34.569   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@869abbb:true
,09-23 06:04:34.673  5647  5660 D bt_hci  : start_up starting async portion
09-23 06:04:34.670  5670  5670 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:04:34.673  5647  5667 I bt_hci  : event_finish_startup
09-23 06:04:34.674  5647  5667 I bt_hci_h4: hal_open
09-23 06:04:34.674  5647  5667 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-23 06:04:34.675  5647  5667 I bt_userial_vendor: device fd = 54 open
,09-23 06:04:34.688  5647  5667 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:04:34.690  5647  5667 D bt_hwcfg: Chipset BCM4358A3
,09-23 06:04:34.690  5647  5667 D bt_hwcfg: Target name = [BCM4358A3]
09-23 06:04:34.690  5647  5667 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 06:04:34.963  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 06:04:35.075  5647  5667 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 06:04:35.076  5647  5667 D bt_hwcfg: Settlement delay -- 100 ms
09-23 06:04:35.076  5647  5667 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 06:04:35.201  5647  5667 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:04:35.201  5647  5667 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-23 06:04:35.203  5647  5667 I bt_hwcfg: vendor lib fwcfg completed
09-23 06:04:35.203  5647  5667 I bt_vendor: firmware callback
09-23 06:04:35.204  5647  5667 I bt_hci  : firmware_config_callback
,09-23 06:04:35.212  5647  5672 I bt_btu  : btu_task pending for preload complete event
,09-23 06:04:35.212  5647  5672 I bt_btu_task: Bluetooth chip preload is complete
09-23 06:04:35.212  5647  5672 I bt_btu  : btu_task received preload complete event
,09-23 06:04:35.219  5647  5672 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 06:04:35.219  5647  5672 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-23 06:04:35.219  5647  5672 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-23 06:04:35.219  5647  5672 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-23 06:04:35.220  5647  5672 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-23 06:04:35.220  5647  5672 I         : BTE_InitTraceLevels -- TRC_A2D
,09-23 06:04:35.220  5647  5672 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-23 06:04:35.220  5647  5672 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 06:04:35.220  5647  5672 I         : BTE_InitTraceLevels -- TRC_GAP
,09-23 06:04:35.220  5647  5672 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 06:04:35.220  5647  5672 I         : BTE_InitTraceLevels -- TRC_SDP
09-23 06:04:35.221  5647  5672 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 06:04:35.221  5647  5672 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 06:04:35.221  5647  5672 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-23 06:04:35.221  5647  5672 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 06:04:35.306  5647  5672 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c07549
09-23 06:04:35.306  5647  5672 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c07549 
,09-23 06:04:35.334  5647  5663 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 06:04:35.335  5647  5663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 06:04:35.336  5647  5663 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 06:04:35.338  5647  5663 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:04:35.341  5647  5663 D BluetoothAdapterProperties: Scan Mode:20
,09-23 06:04:35.341  5647  5663 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:04:35.342  5647  5663 D bt_hci  : do_postload posting postload work item
09-23 06:04:35.342  5647  5667 I bt_hci  : event_postload
,09-23 06:04:35.342  5647  5667 I bt_vendor: sco_config_cb
09-23 06:04:35.342  5647  5667 I bt_hci  : sco_config_callback postload finished.
09-23 06:04:35.345  5647  5663 D bt_bte_conf: Device ID record 1 : primary
09-23 06:04:35.345  5647  5663 D bt_bte_conf:   vendorId            = 000f
09-23 06:04:35.345  5647  5663 D bt_bte_conf:   vendorIdSource      = 0001
09-23 06:04:35.345  5647  5663 D bt_bte_conf:   product             = 1200
09-23 06:04:35.345  5647  5663 D bt_bte_conf:   version             = 1436
09-23 06:04:35.345  5647  5663 D bt_bte_conf:   clientExecutableURL = 
09-23 06:04:35.345  5647  5663 D bt_bte_conf:   serviceDescription  = 
,09-23 06:04:35.346  5647  5663 D bt_bte_conf:   documentationURL    = 
09-23 06:04:35.346  5647  5663 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 06:04:35.346  5647  5660 D bt_stack_manager: event_start_up_stack finished
09-23 06:04:35.347  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.347  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 06:04:35.347  5647  5659 D BluetoothAdapterProperties: Setting state to 15
09-23 06:04:35.347  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 06:04:35.348  5647  5659 I BluetoothAdapterState: Entering BleOnState
09-23 06:04:35.352  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:35.354  5647  5659 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 06:04:35.354  5647  5659 D BluetoothAdapterProperties: Setting state to 11
09-23 06:04:35.354  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-23 06:04:35.355  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.355  5647  5667 I bt_vendor: low_power_mode_cb
,09-23 06:04:35.362  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:35.363  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:35.364  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:35.364  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.365  5647  5647 D HeadsetService: Received start request. Starting profile...
09-23 06:04:35.367  5647  5647 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 06:04:35.367  5647  5647 D HeadsetStateMachine: make
,09-23 06:04:35.374  5647  5659 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:04:35.377  5647  5647 D HeadsetStateMachine: max_hf_connections = 1
,09-23 06:04:35.377  5647  5647 I bt_bluedroid: get_profile_interface handsfree
09-23 06:04:35.377  5647  5663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 06:04:35.377  5647  5663 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-23 06:04:35.380  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:35.380  5647  5647 D A2dpService: Received start request. Starting profile...
,09-23 06:04:35.382  5647  5647 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 06:04:35.382  5647  5647 I bt_bluedroid: get_profile_interface avrcp
,09-23 06:04:35.387  5647  5647 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 06:04:35.387  5647  5647 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 06:04:35.387  5647  5647 D A2dpStateMachine: make
09-23 06:04:35.388  5647  5647 I bt_bluedroid: get_profile_interface a2dp
,09-23 06:04:35.390  5647  5663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 06:04:35.391  5647  5680 D A2dpStateMachine: Enter Disconnected: -2
,09-23 06:04:35.391  5647  5647 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 06:04:35.392  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:35.393  5647  5647 D HidService: Received start request. Starting profile...
,09-23 06:04:35.393  5647  5647 I bt_bluedroid: get_profile_interface hidhost
09-23 06:04:35.394  5647  5647 D HidService: setHidService(): set to: null
09-23 06:04:35.394  5647  5663 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3be856d
09-23 06:04:35.394  5647  5663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 06:04:35.394  5647  5647 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 06:04:35.395  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:35.395  5647  5647 D HealthService: Received start request. Starting profile...
09-23 06:04:35.396  5602  5602 D BluetoothInputDevice: Proxy object connected
09-23 06:04:35.396  5602  5602 D HidProfile: Bluetooth service connected
09-23 06:04:35.396  5647  5647 I bt_bluedroid: get_profile_interface health
09-23 06:04:35.397  5647  5647 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 06:04:35.398  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:35.399  5602  5602 D BluetoothPan: BluetoothPAN Proxy object connected
,09-23 06:04:35.399  5647  5647 D PanService: Received start request. Starting profile...
09-23 06:04:35.399  5602  5602 D PanProfile: Bluetooth service connected
09-23 06:04:35.399  5647  5647 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 06:04:35.399  5647  5647 I bt_bluedroid: get_profile_interface pan
09-23 06:04:35.400  5647  5663 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-23 06:04:35.402  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:35.403  5647  5647 D BluetoothMapService: Received start request. Starting profile...
09-23 06:04:35.403  5602  5602 D BluetoothMap: Proxy object connected
09-23 06:04:35.403  5647  5647 D BluetoothMapService: start()
,09-23 06:04:35.404  5602  5602 D MapProfile: Bluetooth service connected
,09-23 06:04:35.404  5602  5602 D BluetoothMap: getConnectedDevices()
09-23 06:04:35.404  5602  5602 D BluetoothMap: Bluetooth is Not enabled
09-23 06:04:35.405  5647  5647 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-23 06:04:35.406  5647  5647 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-23 06:04:35.406  5647  5647 D BluetoothMapAppObserver: createReceiver()
09-23 06:04:35.408  5647  5647 D BluetoothMapAppObserver: initObservers()
09-23 06:04:35.408  5647  5647 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 06:04:35.414  5647  5647 V SapService: SapBinder()
09-23 06:04:35.414  5647  5647 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:35.415  5647  5647 D SapService: Received start request. Starting profile...
09-23 06:04:35.415  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:04:35.415  5647  5647 V SapService: start()
,09-23 06:04:35.419  5647  5647 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:04:35.419  5647  5647 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:35.419  5647  5678 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 06:04:35.419  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.419  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.420  5647  5647 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:35.421  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.422  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:04:35.423  5647  5647 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:04:35.423  5647  5647 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:35.423  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.423  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.423  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 06:04:35.424  5647  5659 D BluetoothAdapterProperties: ScanMode =  20
09-23 06:04:35.424  5647  5659 D BluetoothAdapterProperties: State =  11
,09-23 06:04:35.426  5647  5663 D BluetoothAdapterProperties: Scan Mode:21
,09-23 06:04:35.426  5647  5659 D BluetoothAdapterProperties: Setting state to 12
,09-23 06:04:35.426  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 06:04:35.426  5647  5663 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:04:35.427  5647  5659 I BluetoothAdapterState: Entering OnState
09-23 06:04:35.427  3145  3157 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:04:35.428   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:04:35.428  5498  5498 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 06:04:35.429  5602  5613 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:04:35.429  3566  3590 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:04:35.430  5602  5612 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:04:35.430   929   929 D BluetoothA2dp: Proxy object connected
09-23 06:04:35.431  5498  5498 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 06:04:35.433  5647  5647 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:04:35.433  5602  5613 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:04:35.433  5647  5647 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:35.434  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:35.434  3145  3159 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:04:35.435  5647  5647 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:04:35.436  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:35.437  3145  3145 D BluetoothA2dp: Proxy object connected
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:35.440  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:35.440  3145  3157 D BluetoothPan: onBluetoothStateChange on: true
,09-23 06:04:35.441  5647  5647 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:35.442  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:35.442  3145  3145 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:04:35.442  3145  3145 D PanProfile: Bluetooth service connected
09-23 06:04:35.442   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:04:35.443  3145  3159 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:04:35.443  5647  5647 D ObexServerSockets: Succeed to create listening sockets 
,09-23 06:04:35.443  5647  5647 D ObexServerSockets0: startAccept()
,09-23 06:04:35.443  5647  5647 D ObexServerSockets0: prepareForNewConnect()
09-23 06:04:35.445  3145  3145 D BluetoothInputDevice: Proxy object connected
09-23 06:04:35.445  3145  3145 D HidProfile: Bluetooth service connected
09-23 06:04:35.445  5602  5612 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:04:35.445   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:04:35.445   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:04:35.445  3145  3159 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:04:35.445  5647  5647 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:35.446  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:35.446  5647  5647 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 06:04:35.447  3145  3145 D BluetoothMap: Proxy object connected
09-23 06:04:35.447  3145  3145 D MapProfile: Bluetooth service connected
09-23 06:04:35.447  3145  3453 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:04:35.447  3145  3145 D BluetoothMap: getConnectedDevices()
09-23 06:04:35.448  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:35.448   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 06:04:35.449  5647  5647 D BluetoothMapService: onReceive
,09-23 06:04:35.449  5647  5647 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:04:35.449  5647  5647 D BluetoothMapService: STATE_ON
09-23 06:04:35.451  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.451  5647  5686 D ObexServerSockets0: Accepting socket connection...
09-23 06:04:35.452  5602  5602 D LocalBluetoothProfileManager: Adding local A2DP profile
09-23 06:04:35.452  5647  5685 D ObexServerSockets0: Accepting socket connection...
09-23 06:04:35.453  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.453  5647  5688 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:35.455  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.455  5647  5688 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 06:04:35.455  5647  5688 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-23 06:04:35.456  5602  5602 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-23 06:04:35.462  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:04:35.464  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:35.465  5498  5544 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 06:04:35.465  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:04:35.465  5602  5602 D BluetoothA2dp: Proxy object connected
09-23 06:04:35.466  5498  5544 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-23 06:04:35.467  5498  5544 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-23 06:04:35.470  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:04:35.472  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.474  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:04:35.475  5647  5659 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 06:04:35.476  5647  5659 D BluetoothAdapterProperties: Setting state to 13
09-23 06:04:35.476  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 06:04:35.476  5647  5659 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 06:04:35.477  5647  5659 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:04:35.479  5647  5663 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:04:35.480  5602  5602 D BluetoothPbap: Proxy object connected
09-23 06:04:35.480  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-23 06:04:35.480  3145  3145 D BluetoothPbap: Proxy object connected
09-23 06:04:35.480  3145  3145 D PbapServerProfile: Bluetooth service connected
09-23 06:04:35.482  5602  5602 D PbapServerProfile: Bluetooth service connected
,09-23 06:04:35.483  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:35.483  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:35.484  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:04:35.484  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:35.486  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:35.486  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:35.487  5647  5647 D BluetoothMapService: onReceive
09-23 06:04:35.487  5647  5647 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:04:35.487  5647  5647 D BluetoothMapService: STATE_TURNING_OFF
09-23 06:04:35.488  5647  5647 D HeadsetService: Received stop request...Stopping profile...
09-23 06:04:35.488  5498  5498 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:04:35.488  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:35.490  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.491  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:35.496  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 06:04:35.502  5647  5647 D A2dpService: Received stop request...Stopping profile...
09-23 06:04:35.502  5647  5680 D A2dpStateMachine: Exit Disconnected: -1
09-23 06:04:35.503  5602  5602 D DockEventReceiver: finishStartingService: stopping service
09-23 06:04:35.503   929   929 D BluetoothA2dp: Proxy object disconnected
09-23 06:04:35.503  3145  3145 D BluetoothA2dp: Proxy object disconnected
09-23 06:04:35.504  5602  5602 D BluetoothA2dp: Proxy object disconnected
09-23 06:04:35.508  5647  5647 D HidService: Received stop request...Stopping profile...
09-23 06:04:35.508  5647  5647 D HidService: Stopping Bluetooth HidService
09-23 06:04:35.509  3145  3145 D BluetoothInputDevice: Proxy object disconnected
09-23 06:04:35.509  3145  3145 D HidProfile: Bluetooth service disconnected
09-23 06:04:35.510  5602  5602 D BluetoothInputDevice: Proxy object disconnected
09-23 06:04:35.510  5602  5602 D HidProfile: Bluetooth service disconnected
09-23 06:04:35.510  5647  5647 D HealthService: Received stop request...Stopping profile...
09-23 06:04:35.511  5647  5647 D PanService: Received stop request...Stopping profile...
09-23 06:04:35.512  3145  3145 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:04:35.512  3145  3145 D PanProfile: Bluetooth service disconnected
09-23 06:04:35.513  5602  5602 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:04:35.513  5602  5602 D PanProfile: Bluetooth service disconnected
09-23 06:04:35.513  5647  5647 D BluetoothMapService: Received stop request...Stopping profile...
09-23 06:04:35.513  5647  5647 D BluetoothMapService: stop()
09-23 06:04:35.514  5647  5647 D BluetoothMapAppObserver: deinitObservers()
09-23 06:04:35.514  5647  5647 D BluetoothMapAppObserver: removeReceiver()
09-23 06:04:35.515  3145  3145 D BluetoothMap: Proxy object disconnected
09-23 06:04:35.515  5602  5602 D BluetoothMap: Proxy object disconnected
09-23 06:04:35.515  3145  3145 D MapProfile: Bluetooth service disconnected
09-23 06:04:35.515  5602  5602 D MapProfile: Bluetooth service disconnected
09-23 06:04:35.516  5647  5647 D SapService: Received stop request...Stopping profile...
09-23 06:04:35.516  5647  5647 V SapService: stop()
09-23 06:04:35.517  5647  5647 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:35.517  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.517  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.517  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.518  5647  5647 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 06:04:35.518  5647  5647 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 06:04:35.518  5647  5672 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:35.518  5647  5672 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:35.518  5647  5672 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:35.519  5647  5663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 06:04:35.519  5647  5663 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-23 06:04:35.520  5647  5647 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:35.520  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.520  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.520  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.521  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:04:35.522  5647  5647 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:35.522  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.522  5647  5672 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:35.522  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.522  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.522  5647  5672 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:35.522  5647  5647 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 06:04:35.522  5647  5647 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 06:04:35.523  5647  5647 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:35.523  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.523  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.523  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.523  5647  5647 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 06:04:35.523  5647  5663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:04:35.523  5647  5672 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:04:35.523  5647  5663 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:04:35.523  5647  5672 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:04:35.524  5647  5663 E bt_btif : L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:04:35.524  5647  5672 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:04:35.524  5647  5672 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:04:35.524  5647  5647 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 06:04:35.524  5647  5647 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:35.524  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.524  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.524  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.525  5647  5647 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 06:04:35.526  5647  5647 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 06:04:35.527  5647  5647 D BluetoothMapService: MAP Service closeService in
09-23 06:04:35.528  5647  5647 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 06:04:35.528  5647  5647 D ObexServerSockets0: shutdown(block = true)
09-23 06:04:35.528  5647  5647 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:04:35.528  5647  5685 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 06:04:35.528  5647  5647 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:04:35.528  5647  5686 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 06:04:35.528  5647  5674 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 06:04:35.529  5647  5647 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:35.529  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.529  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.529  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.530  5647  5647 D BluetoothMapService: cleanup()
09-23 06:04:35.530  5647  5647 D BluetoothMapService: MAP Service closeService in
09-23 06:04:35.530  5647  5647 V BluetoothAdapterState: isTurningOff()=true
09-23 06:04:35.530  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.530  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:35.530  5647  5647 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:35.531  3145  3145 D BluetoothPbap: Proxy object disconnected
09-23 06:04:35.531  3145  3145 D PbapServerProfile: Bluetooth service disconnected
09-23 06:04:35.531  5602  5602 D BluetoothPbap: Proxy object disconnected
09-23 06:04:35.532  5602  5602 D PbapServerProfile: Bluetooth service disconnected
09-23 06:04:35.533  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 06:04:35.533  5647  5659 D BluetoothAdapterProperties: Setting state to 15
09-23 06:04:35.533  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 06:04:35.534  5647  5659 I BluetoothAdapterState: Entering BleOnState
09-23 06:04:35.534  3145  3159 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:04:35.537  5602  5613 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:35.537  5602  5612 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:04:35.537   929   946 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:04:35.537  5602  5613 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:04:35.538  3566  3836 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:35.538  5602  5612 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:04:35.538  5602  5613 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:04:35.539  3145  3453 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:04:35.539  3145  3157 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:04:35.539   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:35.540  3145  3159 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:04:35.540  5602  5612 D BluetoothMap: onBluetoothStateChange: up=false
09-23 06:04:35.540   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:35.540   929   946 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:35.540  3145  3453 D BluetoothMap: onBluetoothStateChange: up=false
09-23 06:04:35.541  3145  3157 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:04:35.541  5647  5659 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 06:04:35.541  5647  5659 D BluetoothAdapterProperties: Setting state to 16
09-23 06:04:35.541  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 06:04:35.542  5647  5659 D BluetoothAdapterProperties: onBleDisable
09-23 06:04:35.542  5647  5659 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:04:35.542  5647  5660 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 06:04:35.545  5647  5672 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 06:04:35.545  5647  5672 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:04:35.545  5647  5663 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:04:35.546  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.548  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.548  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 06:04:35.550  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.552  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:35.554  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:04:35.555  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:04:35.746  5647  5663 I bt_hci  : shut_down
,09-23 06:04:35.747  5647  5667 D bt_hwcfg: hw_epilog_process
,09-23 06:04:35.748  5647  5667 I bt_vendor: low_power_mode_cb
,09-23 06:04:35.751  5647  5667 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 06:04:35.752  5647  5667 I bt_vendor: epilog_cb
09-23 06:04:35.752  5647  5667 I bt_hci  : epilog_finished_callback
,09-23 06:04:35.755  5647  5663 I bt_hci_h4: hal_close
,09-23 06:04:35.756  5647  5663 I bt_userial_vendor: device fd = 54 close
,09-23 06:04:35.877  5647  5660 D bt_stack_manager: event_shut_down_stack finished.
,09-23 06:04:35.877  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-23 06:04:35.881  5647  5659 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-23 06:04:35.881  5647  5647 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:04:35.883  5647  5647 D BtGatt.GattService: Received stop request...Stopping profile...
,09-23 06:04:35.883  5647  5647 D BtGatt.GattService: stop()
09-23 06:04:35.883  5647  5647 D BtGatt.AdvertiseManager: advertise clients cleared
,09-23 06:04:35.887  5647  5647 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:35.887  5647  5647 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:35.887  5647  5647 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:04:35.887  5647  5647 V BluetoothAdapterState: isBleTurningOff()=true
09-23 06:04:35.888  5647  5659 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 06:04:35.888  5647  5659 D BluetoothAdapterProperties: Setting state to 10
,09-23 06:04:35.888  5647  5659 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 06:04:35.890  5647  5659 I BluetoothAdapterState: Entering OffState
,09-23 06:04:35.891   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-23 06:04:35.907  5647  5647 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 06:04:35.907  5647  5647 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 06:04:35.908  5647  5647 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 06:04:35.910  5647  5660 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 06:04:35.916  5647  5647 I art     : System.exit called, status: 0
,09-23 06:04:35.917  5647  5647 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 06:04:35.944   929  3805 I ActivityManager: Process com.android.bluetooth (pid 5647) has died
,09-23 06:04:35.973  5498  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:35.974  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:35.974  5498  5557 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:04:35.974  5498  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:35.975  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:35.988   929   946 I ActivityManager: Start proc 5700:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 06:04:36.044  5700  5700 D AdapterServiceConfig: Adding HeadsetService
,09-23 06:04:36.044  5700  5700 D AdapterServiceConfig: Adding A2dpService
09-23 06:04:36.044  5700  5700 D AdapterServiceConfig: Adding HidService
09-23 06:04:36.044  5700  5700 D AdapterServiceConfig: Adding HealthService
09-23 06:04:36.044  5700  5700 D AdapterServiceConfig: Adding PanService
09-23 06:04:36.045  5700  5700 D AdapterServiceConfig: Adding GattService
09-23 06:04:36.045  5700  5700 D AdapterServiceConfig: Adding BluetoothMapService
09-23 06:04:36.045  5700  5700 D AdapterServiceConfig: Adding SapService
,09-23 06:04:36.054   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b0f0b7b:true
,09-23 06:04:36.054  5700  5700 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 06:04:36.057  5700  5700 I bt_bluedroid: init
09-23 06:04:36.057  5700  5712 I BluetoothAdapterState: Entering OffState
,09-23 06:04:36.059  5700  5713 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-23 06:04:36.059  5700  5713 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 06:04:36.059  5700  5713 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 06:04:36.059  5700  5713 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 06:04:36.060  5700  5700 I bt_bluedroid: get_profile_interface socket
,09-23 06:04:36.061  5700  5716 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 06:04:36.062  5700  5700 I bt_bluedroid: get_profile_interface sdp
,09-23 06:04:36.063  5700  5716 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:04:36.066  5700  5711 I bt_bluedroid: config_hci_snoop_log
,09-23 06:04:36.067   929   946 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 06:04:36.071  5700  5712 D BluetoothAdapterState: Current state: OFF, message: 0
,09-23 06:04:36.071  5700  5712 D BluetoothAdapterProperties: Setting state to 14
09-23 06:04:36.071  5700  5712 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-23 06:04:36.073  5700  5712 D BluetoothBondStateMachine: make
,09-23 06:04:36.074  5700  5717 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 06:04:36.076  5700  5712 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:04:36.077  5700  5700 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 06:04:36.079  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:36.080  5700  5700 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 06:04:36.080  5700  5700 D BtGatt.GattService: Received start request. Starting profile...
09-23 06:04:36.081  5700  5700 D BtGatt.GattService: start()
09-23 06:04:36.081  5700  5700 I bt_bluedroid: get_profile_interface gatt
,09-23 06:04:36.082  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:36.082  5700  5700 D BtGatt.AdvertiseManager: advertise manager created
,09-23 06:04:36.087  5700  5700 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:36.087  5700  5700 V BluetoothAdapterState: isTurningOn()=false
09-23 06:04:36.087  5700  5700 V BluetoothAdapterState: isBleTurningOn()=true
09-23 06:04:36.087  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:36.087  5700  5712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 06:04:36.088  5700  5712 I bt_bluedroid: bt_bluedroid
,09-23 06:04:36.088  5700  5713 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-23 06:04:36.089  5700  5713 I bt_hci  : start_up
,09-23 06:04:36.093  5700  5713 I bt_vendor: alloc value 0xf3c89871
,09-23 06:04:36.093  5700  5713 I bt_vendor: init
09-23 06:04:36.093  5700  5713 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 06:04:36.093  5700  5713 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 06:04:36.202  5700  5713 D bt_hci  : start_up starting async portion
09-23 06:04:36.202  5700  5720 I bt_hci  : event_finish_startup
09-23 06:04:36.202  5700  5720 I bt_hci_h4: hal_open
09-23 06:04:36.202  5700  5720 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 06:04:36.197  5721  5721 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:04:36.206  5700  5720 I bt_userial_vendor: device fd = 54 open
,09-23 06:04:36.219  5700  5720 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:04:36.222  5700  5720 D bt_hwcfg: Chipset BCM4358A3
,09-23 06:04:36.222  5700  5720 D bt_hwcfg: Target name = [BCM4358A3]
09-23 06:04:36.222  5700  5720 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 06:04:36.482  5700  5712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 06:04:36.615  5700  5720 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 06:04:36.616  5700  5720 D bt_hwcfg: Settlement delay -- 100 ms
09-23 06:04:36.616  5700  5720 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 06:04:36.739  5700  5720 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:04:36.739  5700  5720 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-23 06:04:36.741  5700  5720 I bt_hwcfg: vendor lib fwcfg completed
,09-23 06:04:36.741  5700  5720 I bt_vendor: firmware callback
,09-23 06:04:36.741  5700  5720 I bt_hci  : firmware_config_callback
,09-23 06:04:36.748  5700  5723 I bt_btu  : btu_task pending for preload complete event
09-23 06:04:36.749  5700  5723 I bt_btu_task: Bluetooth chip preload is complete
09-23 06:04:36.749  5700  5723 I bt_btu  : btu_task received preload complete event
,09-23 06:04:36.758  5700  5723 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_BTM
,09-23 06:04:36.759  5700  5723 I         : BTE_InitTraceLevels -- TRC_GAP
,09-23 06:04:36.760  5700  5723 I         : BTE_InitTraceLevels -- TRC_PAN
,09-23 06:04:36.760  5700  5723 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 06:04:36.760  5700  5723 I         : BTE_InitTraceLevels -- TRC_GATT
,09-23 06:04:36.760  5700  5723 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 06:04:36.760  5700  5723 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-23 06:04:36.760  5700  5723 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 06:04:36.845  5700  5723 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c07549
09-23 06:04:36.845  5700  5723 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c07549 
,09-23 06:04:36.867  5700  5716 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 06:04:36.869  5700  5716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:04:36.869  5700  5716 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 06:04:36.873  5700  5716 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:04:36.876  5700  5716 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:04:36.876  5700  5716 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:04:36.877  5700  5716 D bt_hci  : do_postload posting postload work item
,09-23 06:04:36.877  5700  5720 I bt_hci  : event_postload
09-23 06:04:36.877  5700  5720 I bt_vendor: sco_config_cb
09-23 06:04:36.877  5700  5720 I bt_hci  : sco_config_callback postload finished.
09-23 06:04:36.879  5700  5716 D bt_bte_conf: Device ID record 1 : primary
09-23 06:04:36.879  5700  5716 D bt_bte_conf:   vendorId            = 000f
09-23 06:04:36.880  5700  5716 D bt_bte_conf:   vendorIdSource      = 0001
09-23 06:04:36.880  5700  5716 D bt_bte_conf:   product             = 1200
09-23 06:04:36.881  5700  5716 D bt_bte_conf:   version             = 1436
09-23 06:04:36.881  5700  5716 D bt_bte_conf:   clientExecutableURL = 
,09-23 06:04:36.881  5700  5716 D bt_bte_conf:   serviceDescription  = 
09-23 06:04:36.881  5700  5716 D bt_bte_conf:   documentationURL    = 
09-23 06:04:36.881  5700  5716 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 06:04:36.881  5700  5713 D bt_stack_manager: event_start_up_stack finished
09-23 06:04:36.882  5700  5712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 06:04:36.883  5700  5712 D BluetoothAdapterProperties: Setting state to 15
09-23 06:04:36.883  5700  5712 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-23 06:04:36.885  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:36.886  5700  5712 I BluetoothAdapterState: Entering BleOnState
09-23 06:04:36.887  5700  5720 I bt_vendor: low_power_mode_cb
09-23 06:04:36.888  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:36.889  5700  5712 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 06:04:36.889  5700  5712 D BluetoothAdapterProperties: Setting state to 11
09-23 06:04:36.889  5700  5712 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 06:04:36.895  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:36.901  3566  3590 D BluetoothHeadset: Proxy object connected
,09-23 06:04:36.901  5700  5700 D HeadsetService: Received start request. Starting profile...
09-23 06:04:36.901  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:36.902  5602  5612 D BluetoothHeadset: Proxy object connected
09-23 06:04:36.904  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:36.904  5700  5700 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 06:04:36.904  5700  5700 D HeadsetStateMachine: make
09-23 06:04:36.904   929   929 D BluetoothHeadset: Proxy object connected
09-23 06:04:36.904   929   929 D BluetoothHeadset: Proxy object connected
,09-23 06:04:36.904   929   929 D BluetoothHeadset: Proxy object connected
09-23 06:04:36.905  3145  3157 D BluetoothHeadset: Proxy object connected
09-23 06:04:36.906  5602  5602 D HeadsetProfile: Bluetooth service connected
09-23 06:04:36.907  5598  5598 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:04:36.909  5598  5598 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:04:36.910  5598  5598 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-23 06:04:36.910  5700  5712 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:04:36.913  5700  5700 D HeadsetStateMachine: max_hf_connections = 1
09-23 06:04:36.913  5700  5700 I bt_bluedroid: get_profile_interface handsfree
09-23 06:04:36.913  5700  5716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 06:04:36.914  5700  5716 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
09-23 06:04:36.917  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:36.917  5700  5700 D A2dpService: Received start request. Starting profile...
,09-23 06:04:36.918  5700  5700 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 06:04:36.919  5700  5700 I bt_bluedroid: get_profile_interface avrcp
,09-23 06:04:36.922  3145  3145 D HeadsetProfile: Bluetooth service connected
,09-23 06:04:36.925  5700  5700 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 06:04:36.925  5700  5700 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 06:04:36.925  5700  5700 D A2dpStateMachine: make
09-23 06:04:36.926  5700  5700 I bt_bluedroid: get_profile_interface a2dp
,09-23 06:04:36.927  5700  5716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 06:04:36.930  5700  5732 D A2dpStateMachine: Enter Disconnected: -2
,09-23 06:04:36.932  5700  5700 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 06:04:36.932  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:36.933  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:04:36.933  5700  5700 D HidService: Received start request. Starting profile...
,09-23 06:04:36.933  5700  5700 I bt_bluedroid: get_profile_interface hidhost
,09-23 06:04:36.934  5700  5716 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3be856d
09-23 06:04:36.934  5700  5700 D HidService: setHidService(): set to: null
09-23 06:04:36.934  5700  5716 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 06:04:36.934  5700  5700 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 06:04:36.935  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:36.936  5700  5700 D HealthService: Received start request. Starting profile...
,09-23 06:04:36.937  5700  5700 I bt_bluedroid: get_profile_interface health
,09-23 06:04:36.938  5700  5700 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 06:04:36.938  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:36.939  5700  5700 D PanService: Received start request. Starting profile...
09-23 06:04:36.939  5700  5700 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 06:04:36.939  5700  5700 I bt_bluedroid: get_profile_interface pan
09-23 06:04:36.940  5700  5716 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-23 06:04:36.942  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
,09-23 06:04:36.942  5700  5700 D BluetoothMapService: Received start request. Starting profile...
,09-23 06:04:36.942  5700  5700 D BluetoothMapService: start()
09-23 06:04:36.945  5700  5700 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-23 06:04:36.946  5700  5700 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 06:04:36.946  5700  5700 D BluetoothMapAppObserver: createReceiver()
09-23 06:04:36.948  5700  5700 D BluetoothMapAppObserver: initObservers()
09-23 06:04:36.948  5700  5700 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 06:04:36.954  5700  5700 V SapService: SapBinder()
,09-23 06:04:36.954  5700  5700 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:36.954  5700  5700 D SapService: Received start request. Starting profile...
09-23 06:04:36.954  5700  5700 V SapService: start()
,09-23 06:04:36.957  5700  5700 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:04:36.957  5700  5700 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:36.957  5700  5700 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:36.957  5700  5730 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 06:04:36.957  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:36.958  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:36.959  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:04:36.960  5700  5700 V BluetoothAdapterState: isTurningOff()=false
09-23 06:04:36.960  5700  5700 V BluetoothAdapterState: isTurningOn()=true
09-23 06:04:36.960  5700  5700 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:04:36.960  5700  5700 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:04:36.961  5700  5712 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 06:04:36.961  5700  5712 D BluetoothAdapterProperties: ScanMode =  20
09-23 06:04:36.961  5700  5712 D BluetoothAdapterProperties: State =  11
,09-23 06:04:36.962  5700  5716 D BluetoothAdapterProperties: Scan Mode:21
,09-23 06:04:36.962  5700  5712 D BluetoothAdapterProperties: Setting state to 12
09-23 06:04:36.962  5700  5712 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 06:04:36.962  5700  5716 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:04:36.963  5700  5712 I BluetoothAdapterState: Entering OnState
09-23 06:04:36.963  3145  3453 D BluetoothPbap: onBluetoothStateChange: up=true
,09-23 06:04:36.965  5602  5613 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:04:36.966  5602  5612 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:36.967  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:36.967   929   946 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:04:36.968  5602  5613 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:04:36.968   929   929 D BluetoothA2dp: Proxy object connected
09-23 06:04:36.969  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:36.970  3566  3900 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:04:36.970  5602  5612 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:04:36.972  5602  5613 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:36.972  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:36.972  5700  5700 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:04:36.973  5700  5700 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 06:04:36.974  3145  3157 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:04:36.974  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:36.974  5700  5700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:36.975  3145  3145 D BluetoothA2dp: Proxy object connected
09-23 06:04:36.975  5602  5602 D BluetoothA2dp: Proxy object connected
09-23 06:04:36.975  3145  3453 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:04:36.976  5700  5700 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:04:36.977   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:04:36.977  3145  3159 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:04:36.977  3145  3145 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:04:36.977  3145  3145 D PanProfile: Bluetooth service connected
09-23 06:04:36.978  5602  5602 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:04:36.978  5602  5602 D PanProfile: Bluetooth service connected
09-23 06:04:36.978  5700  5700 D ObexServerSockets: Succeed to create listening sockets 
09-23 06:04:36.979  5700  5700 D ObexServerSockets0: startAccept()
09-23 06:04:36.979  5700  5700 D ObexServerSockets0: prepareForNewConnect()
,09-23 06:04:36.979  5602  5612 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:04:36.981   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:04:36.981   929   946 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:04:36.981  3145  3453 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:04:36.981  5700  5700 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 06:04:36.981  5700  5700 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 06:04:36.982  5700  5738 D ObexServerSockets0: Accepting socket connection...
09-23 06:04:36.982  5700  5739 D ObexServerSockets0: Accepting socket connection...
09-23 06:04:36.983  3145  3145 D BluetoothInputDevice: Proxy object connected
09-23 06:04:36.983  5602  5602 D BluetoothInputDevice: Proxy object connected
09-23 06:04:36.983  5602  5602 D HidProfile: Bluetooth service connected
09-23 06:04:36.983  3145  3145 D HidProfile: Bluetooth service connected
09-23 06:04:36.983  3145  3159 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:04:36.984   929   929 I Telecom : BluetoothPhoneService: queryPhoneState
,09-23 06:04:36.985  5700  5700 D BluetoothMapService: onReceive
09-23 06:04:36.985   929   929 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-23 06:04:36.985  5700  5700 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:04:36.985  5700  5700 D BluetoothMapService: STATE_ON
,09-23 06:04:36.987  3145  3145 D BluetoothMap: Proxy object connected
09-23 06:04:36.987  3145  3145 D MapProfile: Bluetooth service connected
09-23 06:04:36.987  3145  3145 D BluetoothMap: getConnectedDevices()
,09-23 06:04:36.988  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:36.989  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:36.989  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:36.990  5602  5602 D BluetoothMap: Proxy object connected
09-23 06:04:36.990  5602  5602 D MapProfile: Bluetooth service connected
09-23 06:04:36.990  5602  5602 D BluetoothMap: getConnectedDevices()
09-23 06:04:36.990  5700  5740 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:04:36.991  5700  5740 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-23 06:04:36.992  5700  5740 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 06:04:36.992  5498  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:04:36.992  5498  5544 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
09-23 06:04:36.993   929  3597 D WifiService: setWifiEnabled: false pid=5498, uid=10077
09-23 06:04:36.993   929  3597 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:04:36.994  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:36.995   929   929 D RttService: SCAN_AVAILABLE : 1
09-23 06:04:36.995   929  3097 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 06:04:36.996  5602  5602 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:04:37.001  5602  5602 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:04:37.002  3634  3634 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:04:37.002   929  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 06:04:37.003   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:04:37.008   929  2988 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:04:37.008  5598  5598 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-23 06:04:37.012  5602  5602 D BluetoothPbap: Proxy object connected
,09-23 06:04:37.012  5602  5602 D PbapServerProfile: Bluetooth service connected
09-23 06:04:37.012  5700  5700 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:04:37.012  5700  5700 D ObexServerSockets0: prepareForNewConnect()
,09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:37.015  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:37.017  3145  3145 D BluetoothPbap: Proxy object connected
09-23 06:04:37.017  3145  3145 D PbapServerProfile: Bluetooth service connected
,09-23 06:04:37.018  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:37.021  5700  5747 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:37.022  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:37.024  5598  5598 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 06:04:37.024  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:37.034  5700  5751 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:37.035  5700  5751 I BtOppRfcommListener: Accept thread started.
,09-23 06:04:37.044  5598  5598 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 06:04:37.056  5598  5598 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 06:04:37.158  4321  4321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:04:37.158   929  2988 D wifi    : In wifi stop Hal
,09-23 06:04:37.158   929  2988 D wifi    : halHandle = 0x7f974bad20, mVM = 0x7fb35cd140, mCls = 0x1642
09-23 06:04:37.159   929  5597 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-23 06:04:37.159   929  5597 D WifiHAL : Got a signal to exit!!!
09-23 06:04:37.159   929  5597 I WifiHAL : Exit wifi_event_loop
09-23 06:04:37.160   929  2988 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 06:04:37.160   929  2988 E WifiHAL : Event processing terminated
09-23 06:04:37.160   929  2988 D wifi    : In wifi cleaned up handler
,09-23 06:04:37.160   929  2988 I WifiHAL : Internal cleanup completed
09-23 06:04:37.162  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:37.166  3498  4064 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:04:37.169  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:37.190   929  5597 D wifi    : set interface wlan0 flags (DOWN)
,09-23 06:04:37.191   929  2988 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 06:04:37.396   929   946 D Tethering: InitialState.processMessage what=4
,09-23 06:04:37.403   929   946 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:37.504  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:37.509  5498  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:37.513   929  3596 D WifiService: setWifiEnabled: true pid=5498, uid=10077
,09-23 06:04:37.513  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:37.513   929  3596 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:04:37.519   508   921 D SoftapController: Softap fwReload - Ok
09-23 06:04:37.522   508   921 D CommandListener: Setting iface cfg
09-23 06:04:37.522   508   921 D CommandListener: Trying to bring down wlan0
09-23 06:04:37.523   508   921 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:04:37.527   929  2988 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:04:38.018   929  3142 D WifiService: setWifiEnabled: true pid=5498, uid=10077
,09-23 06:04:38.023   929  3142 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:04:38.124   929  2988 D wifi    : set interface wlan0 flags (UP)
,09-23 06:04:38.124   929  2988 I WifiHAL : Initializing wifi
09-23 06:04:38.124   929  2988 I WifiHAL : Creating socket
,09-23 06:04:38.131   929   946 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 06:04:38.135   929  2988 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 06:04:38.135   929  2988 D wifi    : Did set static halHandle = 0x7f974bad20
,09-23 06:04:38.135   929  2988 D wifi    : halHandle = 0x7f974bad20, mVM = 0x7fb35cd140, mCls = 0x200f6a
09-23 06:04:38.136   929  2988 D wifi    : array field set
,09-23 06:04:38.136   929  2988 I WifiNative-HAL: interface[0] = wlan0
,09-23 06:04:38.139   929  5754 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547999165728
09-23 06:04:38.140   929  5754 D wifi    : waitForHalEvents called, vm = 0x7fb35cd140, obj = 0x200f6a, env = 0x7f94218d40
,09-23 06:04:38.202  5755  5755 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 06:04:38.225  5755  5755 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:04:38.236  5755  5755 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:04:38.237  5755  5755 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 06:04:38.240   929  2988 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 06:04:38.248  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:38.251  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:38.266   929  2988 D WifiConfigStore: Loading config and enabling all networks 
,09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:38.271  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:38.273  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:38.276   929  2988 D WifiConfigStore: loaded 0 passpoint configs
09-23 06:04:38.276   929  2988 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-23 06:04:38.277   929  2988 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-23 06:04:38.277   929  2988 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:38.278  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:04:38.279   929  2988 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:04:38.279   929  2988 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-23 06:04:38.279   929  2988 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 06:04:38.279   929  2988 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 06:04:38.280  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:38.283   929  2988 D WifiNative-HAL: Setting external_sim to 1
,09-23 06:04:38.283  4321  4321 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:04:38.283   929  2988 D wifi    : setting dfs flag to true, 0x7f9b4bfd40
09-23 06:04:38.284   929  2988 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 06:04:38.284   929  2988 D wifi    : setting scan oui 0x7f9b4bfd40
09-23 06:04:38.284   929  2988 D WifiHAL : Sending mac address OUI
,09-23 06:04:38.288   929  2988 E native  : do suspend false
,09-23 06:04:38.295   929  2988 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-23 06:04:38.296   508   921 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 06:04:38.296   929   929 D RttService: SCAN_AVAILABLE : 3
09-23 06:04:38.296   929  3097 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 06:04:38.297   508   921 D CommandListener: Setting iface cfg
,09-23 06:04:38.301   929  2987 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-23 06:04:38.301   929  2987 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 06:04:38.309   929  2987 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 06:04:38.314   929  2987 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-23 06:04:38.314   929   944 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=208677 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:38.535  5498  5557 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:38.539  5498  5557 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:38.543  5498  5544 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 06:04:38.544   929  3806 D WifiService: setWifiEnabled: true pid=5498, uid=10077
,09-23 06:04:38.544   929  3806 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:04:38.545  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 06:04:38.546  5498  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 06:04:38.546  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:04:38.546  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 06:04:38.546  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1f59a2 removed from the list
,09-23 06:04:38.547  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:04:38.547  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8f4b633 removed from the list
09-23 06:04:38.547  5498  5544 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:04:38.547  5498  5544 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 06:04:38.547  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 06:04:38.551  5498  5544 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,09-23 06:04:38.555  5498  5544 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-23 06:04:38.560  5498  5757 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-23 06:04:38.560  5498  5757 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 06:04:39.079  5498  5759 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-23 06:04:39.079  5498  5757 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-23 06:04:39.079  5498  5757 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:04:39.079  5498  5759 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:04:39.080  5498  5757 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:04:39.081  5498  5757 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:04:39.081  5498  5759 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:04:39.081  5498  5757 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-23 06:04:39.081  5498  5759 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:04:39.083  5498  5761 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Sender)
09-23 06:04:39.084  5498  5763 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: IncomingSocketThread/Sender)
09-23 06:04:39.084  5498  5759 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-23 06:04:39.085  5498  5762 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver)
09-23 06:04:39.085  5498  5764 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: IncomingSocketThread/Receiver)
,09-23 06:04:39.085  5498  5762 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver)
09-23 06:04:39.086  5498  5762 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 06:04:39.086  5498  5762 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-23 06:04:39.086  5498  5764 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: IncomingSocketThread/Receiver)
09-23 06:04:39.086  5498  5764 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 06:04:39.086  5498  5764 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-23 06:04:39.565  5498  5544 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-23 06:04:39.567  5498  5544 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-23 06:04:39.572  5498  5544 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-23 06:04:39.577  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-23 06:04:39.578  5498  5544 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-23 06:04:39.579  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
09-23 06:04:39.580  5498  5544 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-23 06:04:39.581  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-23 06:04:39.584  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-23 06:04:39.585  5498  5544 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ed72ca6 Bundle[{}]
09-23 06:04:39.585  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-23 06:04:39.585  5498  5544 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 06:04:39.586  5498  5544 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-23 06:04:39.586  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-23 06:04:39.586  5498  5544 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-23 06:04:39.587  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-23 06:04:39.587  5498  5544 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-23 06:04:39.588  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-23 06:04:39.589  5498  5544 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-23 06:04:39.590  5498  5544 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,09-23 06:04:39.591  5498  5544 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-23 06:04:39.592  5498  5544 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,09-23 06:04:39.594  5498  5544 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-23 06:04:39.596  5498  5544 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
09-23 06:04:39.597  5498  5544 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,09-23 06:04:39.598  5498  5544 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,09-23 06:04:39.599  5498  5544 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,09-23 06:04:39.601  5498  5544 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-23 06:04:39.604  5498  5765 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-23 06:04:39.604  5498  5765 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 06:04:39.608  5498  5765 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-23 06:04:39.608  5498  5765 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:04:39.608  5498  5765 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:04:39.608  5498  5765 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:04:39.609  5498  5767 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-23 06:04:39.609  5498  5767 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:04:39.609  5498  5767 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:04:39.609  5498  5768 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Sender)
09-23 06:04:39.609  5498  5765 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 06:04:39.610  5498  5767 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:04:39.611  5498  5769 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: OutgoingSocketThread/Receiver)
,09-23 06:04:39.611  5498  5767 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-23 06:04:39.612  5498  5770 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: IncomingSocketThread/Sender)
09-23 06:04:39.612  5498  5769 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: OutgoingSocketThread/Receiver)
09-23 06:04:39.612  5498  5769 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 06:04:39.612  5498  5769 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 06:04:39.612  5498  5771 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 175, name: IncomingSocketThread/Receiver)
,09-23 06:04:39.613  5498  5771 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 175, thread name: IncomingSocketThread/Receiver)
,09-23 06:04:39.613  5498  5771 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 06:04:39.614  5498  5771 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 175, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 06:04:40.109  5498  5544 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-23 06:04:40.111  5498  5544 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
09-23 06:04:40.112  5498  5544 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
09-23 06:04:40.115  5498  5544 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-23 06:04:40.118  5498  5544 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-23 06:04:40.120  5498  5544 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,09-23 06:04:40.120  5498  5544 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 184)
,09-23 06:04:40.122  5498  5544 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,09-23 06:04:40.123  5498  5544 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-23 06:04:40.123  5498  5544 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 185)
09-23 06:04:40.125  5498  5544 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-23 06:04:40.127  5498  5544 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,09-23 06:04:40.128  5498  5544 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,09-23 06:04:40.129  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:04:40.129  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b591c added. We now have 3 listener(s)
,09-23 06:04:40.132  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 06:04:40.132  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:04:40.132  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:04:40.132  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:04:40.132  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee3a925 added. We now have 3 listener(s)
,09-23 06:04:40.133  5498  5544 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:04:40.134  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:04:40.139  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:04:40.144  5498  5544 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:04:40.146  5498  5544 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:04:40.147  5498  5544 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:04:40.149  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:04:40.151  5498  5544 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,09-23 06:04:40.151  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:04:40.152  5498  5544 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-23 06:04:40.152  5498  5544 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-23 06:04:40.152  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-23 06:04:40.152  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:40.152  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:04:40.152  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-23 06:04:40.153  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:40.154  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:04:40.154  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 06:04:40.155  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:04:40.155  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:04:40.155  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:04:40.155  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:40.155  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:04:40.155  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:04:40.156  5498  5772 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:04:40.160  5498  5772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 06:04:40.154  5741  5741 W Binder_5: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32905]" dev="sockfs" ino=32905 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:40.161  5498  5544 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:04:40.161  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:04:40.157  5741  5741 W Binder_5: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32905]" dev="sockfs" ino=32905 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:04:40.167  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:04:40.168  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:04:40.168  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:04:40.170  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:04:40.170  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:40.170  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
,09-23 06:04:40.170  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:40.171  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:40.171  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:04:40.172  5498  5544 D BluetoothAdapter: STATE_ON
,09-23 06:04:40.175  5700  5728 D BtGatt.GattService: registerClient() - UUID=b66bbf57-8691-4e98-b4a7-d455b962e430
,09-23 06:04:40.176  5700  5716 D BtGatt.GattService: onClientRegistered() - UUID=b66bbf57-8691-4e98-b4a7-d455b962e430, clientIf=5
,09-23 06:04:40.176  5498  5508 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:04:40.178  5700  5718 D BtGatt.AdvertiseManager: message : 0
,09-23 06:04:40.181  5700  5718 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:04:40.192  5700  5716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:04:40.198  5700  5716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:04:40.199  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:04:40.199  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 06:04:40.200  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:04:40.202  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 06:04:40.202  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:04:40.202  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:04:40.202  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-23 06:04:40.202  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:04:40.202  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:04:40.205  5498  5498 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:04:40.205  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:04:40.706  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:04:40.707  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 06:04:40.707  5498  5498 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:04:41.513   929  2988 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 06:04:41.515   929  2988 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 06:04:41.515   929  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:04:41.529   929  2988 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 06:04:41.565   929  2988 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 06:04:41.567  5755  5755 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 06:04:42.010  5755  5755 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 06:04:42.042  5755  5755 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 06:04:42.043  5755  5755 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 06:04:42.058   929  2988 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 06:04:42.059   929  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
09-23 06:04:42.059   929  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:04:42.076   929  2988 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:04:42.089   508   921 D CommandListener: Setting iface cfg
,09-23 06:04:42.096   929  2988 D WifiStateMachine: Start Dhcp Watchdog 2
,09-23 06:04:42.102   929  5777 D DhcpClient: Receive thread started
,09-23 06:04:42.107   929  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:04:42.107   929  2988 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-23 06:04:42.107   929  2990 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-23 06:04:42.188   929  2988 E native  : do suspend false
,09-23 06:04:42.203   929  5776 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 06:04:42.221   929  5777 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172630, domain null
,09-23 06:04:42.222   929  5776 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172630 seconds
,09-23 06:04:42.225   929  5776 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 06:04:42.238   929  5777 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 06:04:42.239   929  5776 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 06:04:42.245   508   921 D CommandListener: Setting iface cfg
,09-23 06:04:42.251   929  2988 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 06:04:42.256   929  5776 D DhcpClient: Scheduling renewal in 86399s
,09-23 06:04:42.270   929  2988 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 06:04:42.273   929  2988 D WifiConfigStore: No blacklist allowed without epno enabled
,09-23 06:04:42.274   929  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-23 06:04:42.276   929  2990 D ConnectivityService: Adding iface wlan0 to network 101
09-23 06:04:42.288   929  2988 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 06:04:42.330   929  2990 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 06:04:42.330   929  2990 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-23 06:04:42.334   929  2990 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-23 06:04:42.338   929  2990 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-23 06:04:42.339   929  2990 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-23 06:04:42.345   929  2990 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:04:42.350   929  2990 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-23 06:04:42.350   929  2990 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-23 06:04:42.351   929  2990 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-23 06:04:42.351   929  2990 D ConnectivityService:    accepting network in place of null
09-23 06:04:42.351   929  2988 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 06:04:42.351   929  2988 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 06:04:42.351   929  2990 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 06:04:42.364   929  5775 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212727, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 06:04:42.375   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:04:42.398   508   921 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:04:42.401   929  2990 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-23 06:04:42.401   929  2990 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-23 06:04:42.402  3518  3729 W QCNEJ   : |CORE| network available: 101
,09-23 06:04:42.403   929  2990 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-23 06:04:42.405  3518  3729 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-23 06:04:42.406   929   946 D Tethering: MasterInitialState.processMessage what=3
,09-23 06:04:42.407  3518  3729 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-23 06:04:42.408  3518  3729 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:42.415  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:04:42.417  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:42.422  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:04:42.424  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:04:42.427  5498  5498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:04:42.428  5498  5498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:04:42.429  4924  4942 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 06:04:42.429  4924  4942 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 06:04:42.429  4924  4942 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 06:04:42.429  4924  4942 E SarControlService: no key has been found,reset the power
09-23 06:04:42.430  4924  4962 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 06:04:42.430  4924  4962 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 06:04:42.430  4924  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-23 06:04:42.430  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-23 06:04:42.430  4950  4950 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 06:04:42.431  4924  4962 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 06:04:42.431  4924  4962 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 06:04:42.432  4924  4962 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 06:04:42.432  4833  4833 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-23 06:04:42.433  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-23 06:04:42.433  4950  4950 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 06:04:42.436  3909  3909 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 06:04:42.439  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ed05769 HexData = [00000000ec03000000000000ffffffff]
09-23 06:04:42.439  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:04:42.439  4950  4964 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-23 06:04:42.440  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-23 06:04:42.440  4924  4934 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-23 06:04:42.442  4950  4964 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@ed05769 HexData = [00000000ed03000000000000ffffffff]
09-23 06:04:42.442  4950  4964 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:04:42.442  4950  4964 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-23 06:04:42.442  4950  4950 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:04:42.443  4924  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 06:04:42.443  3909  3909 D SystemUpdateService: onCreate
09-23 06:04:42.445  3909  3909 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 06:04:42.456  3909  3909 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-23 06:04:42.462  3909  5788 I SystemUpdateService: active receiver: enabled
,09-23 06:04:42.465  3909  5273 I iu.UploadsManager: num queued entries: 0
,09-23 06:04:42.465  3909  5273 I iu.UploadsManager: num updated entries: 0
09-23 06:04:42.466  3909  5273 I iu.SyncManager: NEXT; no task
,09-23 06:04:42.467   929  5774 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-23 06:04:42.468  3909  3909 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 06:04:42.469  3909  3909 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 06:04:42.471  5275  5275 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 06:04:42.475  5275  5275 D SprintDMHelper: simOperator: 
09-23 06:04:42.475  5275  5275 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 06:04:42.498  3909  5788 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 06:04:42.510  3909  5788 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-23 06:04:42.510  3909  5788 I SystemUpdateService: now status is 0 (complete)
09-23 06:04:42.510  3909  5788 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 06:04:42.510  3909  5788 I SystemUpdateService: file has been verified
09-23 06:04:42.510  3909  5788 I SystemUpdateService: OTA package size = 21989297
,09-23 06:04:42.516  3909  5788 I SystemUpdateService: showing system update notification
,09-23 06:04:42.519   929  5774 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 10:04:42 GMT], X-Android-Received-Millis=[1474625082518], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474625082492]}
,09-23 06:04:42.519   929  2990 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 06:04:42.519   929  2990 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-23 06:04:42.519   929  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-23 06:04:42.520   929  2990 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 06:04:42.526  3909  3909 D SystemUpdateService: onDestroy
,09-23 06:04:42.615  4321  5793 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 06:04:43.206  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 06:04:43.206  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 06:04:43.206  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 06:04:43.207  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-23 06:04:43.207  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 06:04:43.207  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-23 06:04:43.207  5498  5772 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 06:04:43.207  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:04:43.207  5498  5772 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:04:43.208  5498  5772 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-23 06:04:43.208  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:04:43.208  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:04:43.208  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:04:43.208  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:04:43.208  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:04:43.208  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:04:43.210  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:43.211  5498  5544 D BluetoothLeScanner: could not find callback wrapper
09-23 06:04:43.211  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:04:43.211  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:04:43.213  5700  5718 D BtGatt.AdvertiseManager: message : 1
09-23 06:04:43.214  5700  5718 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:04:43.231  5700  5716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:04:43.231  5700  5716 D BtGatt.GattService: Client app is not null!
,09-23 06:04:43.233  5700  5710 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:04:43.235  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 06:04:43.235  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:43.235  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 06:04:43.235  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:04:43.235  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:04:43.238  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:43.238  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:04:43.238  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:04:43.239  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:04:43.242  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 06:04:43.242  5498  5498 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:04:43.242  5498  5498 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:04:43.242  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:43.243  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:43.243  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:04:43.246  5498  5544 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
09-23 06:04:43.246  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:04:43.247  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:04:43.247  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 06:04:43.247  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 06:04:43.247  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:04:43.247  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 06:04:43.253  5498  5544 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:04:43.253  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 06:04:43.258  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:04:43.259  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:04:43.259  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:04:43.265  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 06:04:43.265  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 06:04:43.266  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 06:04:43.268  5498  5544 D BluetoothAdapter: STATE_ON
,09-23 06:04:43.271  5700  5741 D BtGatt.GattService: registerClient() - UUID=aa183e4b-9fe0-4bc7-87e1-3c2d540dd052
09-23 06:04:43.272  5700  5716 D BtGatt.GattService: onClientRegistered() - UUID=aa183e4b-9fe0-4bc7-87e1-3c2d540dd052, clientIf=5
,09-23 06:04:43.272  5498  5509 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 06:04:43.273  5700  5710 D BtGatt.GattService: start scan with filters
,09-23 06:04:43.279  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 06:04:43.279  5700  5719 D BtGatt.ScanManager: handling starting scan
,09-23 06:04:43.279  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 06:04:43.279  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 06:04:43.280  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 06:04:43.281  5700  5719 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@6e6e50b
09-23 06:04:43.283  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 06:04:43.283  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:04:43.283  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 06:04:43.285  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:04:43.290  5700  5716 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 06:04:43.290  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:04:43.291  5700  5719 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 06:04:43.297  5700  5716 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 06:04:43.297  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:04:43.298  5700  5719 D BtGatt.ScanManager: Starting BLE batch scan
09-23 06:04:43.298  5700  5719 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 06:04:43.308  5700  5716 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 06:04:43.308  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:04:43.314  5700  5716 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 06:04:43.314  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:04:43.401   929  2990 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-23 06:04:43.785  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 06:04:43.785  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:04:43.785  5498  5498 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:04:45.128   929  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:04:46.291  5498  5544 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-23 06:04:46.292  5498  5544 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
,09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 06:04:46.292  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 06:04:46.293  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:04:46.293  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:04:46.295  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:46.297  5700  5741 D BtGatt.GattService: stopScan() - queue size =1
09-23 06:04:46.299  5700  5710 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:04:46.300  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:04:46.301  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:46.301  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:04:46.301  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 06:04:46.301  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-23 06:04:46.301  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 06:04:46.307  5700  5700 D BtGatt.ScanManager: awakened up at time 216670
09-23 06:04:46.308  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:46.314  5700  5716 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 06:04:46.314  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:04:46.315  5700  5719 D BtGatt.ScanManager: stopping BLe Batch
09-23 06:04:46.318  5700  5710 D BtGatt.GattService: registerClient() - UUID=5a16a2ca-ccc7-4317-9bc5-0870536be66b
09-23 06:04:46.319  5700  5716 D BtGatt.GattService: onClientRegistered() - UUID=5a16a2ca-ccc7-4317-9bc5-0870536be66b, clientIf=5
,09-23 06:04:46.319  5498  5508 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 06:04:46.319  5700  5742 D BtGatt.GattService: start scan with filters
09-23 06:04:46.323  5700  5716 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 06:04:46.324  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 06:04:46.324  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:04:46.324  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 06:04:46.324  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:46.324  5700  5719 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 06:04:46.324  5498  5544 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:04:46.324  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:04:46.324  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:04:46.325  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:04:46.326  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:04:46.326  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:04:46.326  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:04:46.326  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:04:46.326  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 06:04:46.326  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 06:04:46.326  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:04:46.327  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:46.327  5498  5801 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:04:46.328  5700  5711 D BtGatt.GattService: stopScan() - queue size =0
,09-23 06:04:46.324  5741  5741 W Binder_5: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32943]" dev="sockfs" ino=32943 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:04:46.327  5741  5741 W Binder_5: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32943]" dev="sockfs" ino=32943 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:04:46.329  5700  5710 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:04:46.329  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:04:46.329  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:46.329  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 06:04:46.329  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 06:04:46.330  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 06:04:46.330  5498  5801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:04:46.331  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:46.332  5498  5544 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:04:46.336  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 06:04:46.336  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:04:46.336  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-23 06:04:46.336  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:46.336  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:04:46.336  5498  5544 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
,09-23 06:04:46.337  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:46.340  5700  5710 D BtGatt.GattService: registerClient() - UUID=1a0646db-287c-4950-a76d-23725baf2a97
09-23 06:04:46.340  5700  5716 D BtGatt.GattService: onClientRegistered() - UUID=1a0646db-287c-4950-a76d-23725baf2a97, clientIf=5
09-23 06:04:46.340  5498  5509 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:04:46.341  5700  5716 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
09-23 06:04:46.341  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:04:46.341  5700  5716 D BtGatt.GattService: current time is 216704340040
09-23 06:04:46.341  5700  5716 D BtGatt.GattService: Batch record : [-14, -6, 115, -106, 10, 90, 1, -128, -61, 49, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62, 0, 35, 97, 126, -92, 22, -56, 1, -128, -77, 59, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -114, -23, -55, -71, -91, 117, 1, -128, -60, 42, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, -52, 11, 57, -70, 107, -17, 1, 0, -92, 30, 0, 28, 2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 20, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52, 71, -122, -77, 84, 69, -12, 1, -128, -76, 40, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -74, 36, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -77, 31, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0]
09-23 06:04:46.342  5700  5718 D BtGatt.AdvertiseManager: message : 0
09-23 06:04:46.342  5700  5719 D BtGatt.ScanManager: handling starting scan
,09-23 06:04:46.343  5700  5716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, 68, 120, 62, -108, 74, 62]
,09-23 06:04:46.345  5700  5718 D BtGatt.AdvertiseManager: starting multi advertising
09-23 06:04:46.346  5700  5716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 06:04:46.346  5700  5716 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-23 06:04:46.346  5700  5716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 2, 10, 0, 3, 2, -25, -2, 17, 7, 28, -37, 54, 78, 111, 108, 127, 14, -112, 127, 124, -7, 58, 38, 64, 82, 6, 9, 78, 97, 98, 117, 88, 12, -1, 1, 2, 1, 1, -106, -17, 107, -70, 57, 11, -52]
09-23 06:04:46.346  5700  5716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 06:04:46.347  5700  5716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 06:04:46.347  5700  5716 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
,09-23 06:04:46.352  5700  5716 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 06:04:46.352  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:04:46.352  5700  5719 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 06:04:46.361  5700  5716 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:04:46.365  5700  5716 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 06:04:46.365  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:04:46.366  5700  5719 D BtGatt.ScanManager: Starting BLE batch scan
09-23 06:04:46.366  5700  5719 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 06:04:46.369  5700  5716 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:04:46.370  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:04:46.371  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:04:46.372  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:04:46.373  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:46.373  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:46.373  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:04:46.373  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:04:46.373  5498  5498 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-23 06:04:46.373  5498  5498 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-23 06:04:46.373  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 06:04:46.378  5498  5498 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:04:46.378  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:04:46.380  5700  5716 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 06:04:46.380  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:04:46.384  5700  5716 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 06:04:46.384  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:04:46.389  5700  5716 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-23 06:04:46.389  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:04:46.389  5700  5719 D BtGatt.ScanManager: stopping BLe Batch
,09-23 06:04:46.393  5700  5716 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-23 06:04:46.393  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:04:46.393  5700  5719 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 06:04:46.397  5700  5716 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-23 06:04:46.397  5700  5716 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:04:46.879  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:04:46.879  5498  5498 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:04:46.880  5498  5498 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:04:48.157   929  2990 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:04:48.762   929  2988 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,09-23 06:04:49.549   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 06:04:49.549   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 06:04:49.876  5498  5544 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-23 06:04:49.877  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 06:04:49.877  5498  5544 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:04:49.877  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:04:49.877  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:04:49.878  5498  5801 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 06:04:49.879  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:04:49.879  5498  5801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:04:49.879  5498  5544 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:04:49.879  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 06:04:49.879  5498  5801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:04:49.879  5498  5498 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:04:49.879  5498  5544 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4b591c removed from the list
09-23 06:04:49.879  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:04:49.879  5498  5498 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:04:49.879  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 06:04:49.880  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:04:49.880  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:04:49.880  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:04:49.882  5498  5544 D BluetoothAdapter: STATE_ON
09-23 06:04:49.883  5498  5544 D BluetoothLeScanner: could not find callback wrapper
09-23 06:04:49.883  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:04:49.883  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:04:49.886  5700  5718 D BtGatt.AdvertiseManager: message : 1
09-23 06:04:49.888  5700  5718 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:04:49.900  5700  5716 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:04:49.900  5700  5716 D BtGatt.GattService: Client app is not null!
09-23 06:04:49.901  5700  5710 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:04:49.902  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:04:49.902  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:04:49.902  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:04:49.902  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:04:49.903  5498  5544 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:04:49.905  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:04:49.906  5498  5544 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:04:49.906  5498  5544 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 06:04:49.907  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:04:49.909  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:49.909  5498  5544 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee3a925 removed from the list
09-23 06:04:49.910  5498  5544 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:04:49.910  5498  5498 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:04:49.910  5498  5544 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:04:49.910  5498  5498 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:04:49.914  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-23 06:04:49.914  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-23 06:04:49.914  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:04:49.914  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 06:04:49.915  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:04:49.915  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-23 06:04:49.915  5498  5544 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 06:04:49.916  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,09-23 06:04:49.917  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,09-23 06:04:49.918  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
09-23 06:04:49.919  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
09-23 06:04:49.920  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-23 06:04:49.921  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-23 06:04:49.921  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
09-23 06:04:49.922  5498  5544 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
09-23 06:04:49.923  5498  5544 I StreamCopyingThreadTest: Starting test: testRun
,09-23 06:04:49.926  5498  5804 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 198, name: My test thread name)
,09-23 06:04:50.352   929  2990 D ConnectivityService: handlePromptUnvalidated 101
,09-23 06:04:50.411  5498  5498 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 06:04:51.515  5498  5804 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 198
,09-23 06:04:51.515  5498  5804 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 198, name: My test thread name)
09-23 06:04:51.515  5498  5804 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 198, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-23 06:04:51.931  5498  5544 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-23 06:04:51.934  5498  5806 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name)
,09-23 06:04:51.934  5498  5806 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 200, thread name: My test thread name)
09-23 06:04:51.935  5498  5806 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-23 06:04:51.938  5498  5544 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-23 06:04:51.940  5498  5544 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:04:51.945  5498  5544 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-23 06:04:51.948  5498  5807 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: My test thread name)
09-23 06:04:51.949  5498  5807 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 204, thread name: My test thread name): Test exception.
09-23 06:04:51.949  5498  5807 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-23 06:04:51.954  5498  5544 I jxcore-log: *Native tests were executed*
09-23 06:04:51.954  5498  5544 I jxcore-log: 
,09-23 06:04:51.955  5498  5544 I jxcore-log: Total number of executed tests:  82
09-23 06:04:51.955  5498  5544 I jxcore-log: 
09-23 06:04:51.955  5498  5544 I jxcore-log: Number of passed tests:  82
09-23 06:04:51.955  5498  5544 I jxcore-log: 
09-23 06:04:51.955  5498  5544 I jxcore-log: Number of failed tests:  0
09-23 06:04:51.955  5498  5544 I jxcore-log: 
09-23 06:04:51.955  5498  5544 I jxcore-log: Number of ignored tests:  0
09-23 06:04:51.955  5498  5544 I jxcore-log: 
09-23 06:04:51.956  5498  5544 I jxcore-log: Total duration:  21451
09-23 06:04:51.956  5498  5544 I jxcore-log: 
09-23 06:04:51.957  5498  5544 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 06:04:51.957  5498  5544 I jxcore-log: 
,09-23 06:04:51.963  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:04:51.963  5498  5544 I jxcore-log: 
09-23 06:04:51.968  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:04:51.968  5498  5544 I jxcore-log: 
09-23 06:04:51.969  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:04:51.969  5498  5544 I jxcore-log: 
09-23 06:04:51.971  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:04:51.971  5498  5544 I jxcore-log: 
09-23 06:04:51.973  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:04:51.973  5498  5544 I jxcore-log: 
09-23 06:04:51.975  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:04:51.975  5498  5544 I jxcore-log: 
,09-23 06:04:51.979  5498  5498 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-23 06:04:51.979  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:04:51.979  5498  5544 I jxcore-log: 
,09-23 06:04:51.981  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.981  5498  5544 I jxcore-log: 
09-23 06:04:51.982  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:04:51.982  5498  5544 I jxcore-log: 
09-23 06:04:51.983  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:04:51.983  5498  5544 I jxcore-log: 
09-23 06:04:51.984  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:04:51.984  5498  5544 I jxcore-log: 
,09-23 06:04:51.985  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 06:04:51.985  5498  5544 I jxcore-log: 
09-23 06:04:51.987  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.987  5498  5544 I jxcore-log: 
,09-23 06:04:51.988  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.988  5498  5544 I jxcore-log: 
,09-23 06:04:51.990  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.990  5498  5544 I jxcore-log: 
,09-23 06:04:51.991  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.991  5498  5544 I jxcore-log: 
09-23 06:04:51.992  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.992  5498  5544 I jxcore-log: 
09-23 06:04:51.993  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.993  5498  5544 I jxcore-log: 
,09-23 06:04:51.994  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.994  5498  5544 I jxcore-log: 
,09-23 06:04:51.995  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.995  5498  5544 I jxcore-log: 
,09-23 06:04:51.996  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.996  5498  5544 I jxcore-log: 
,09-23 06:04:51.998  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.998  5498  5544 I jxcore-log: 
,09-23 06:04:51.999  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.999  5498  5544 I jxcore-log: 
,09-23 06:04:51.999  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:04:51.999  5498  5544 I jxcore-log: 
09-23 06:04:52.000  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:52.000  5498  5544 I jxcore-log: 
,09-23 06:04:52.001  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:52.001  5498  5544 I jxcore-log: 
,09-23 06:04:52.002  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:52.002  5498  5544 I jxcore-log: 
09-23 06:04:52.002  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:04:52.002  5498  5544 I jxcore-log: 
,09-23 06:04:52.003  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:04:52.003  5498  5544 I jxcore-log: 
09-23 06:04:52.004  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:04:52.004  5498  5544 I jxcore-log: 
,09-23 06:04:52.005  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:52.005  5498  5544 I jxcore-log: 
,09-23 06:04:52.005  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:52.005  5498  5544 I jxcore-log: 
09-23 06:04:52.006  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:52.006  5498  5544 I jxcore-log: 
,09-23 06:04:52.007  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:04:52.007  5498  5544 I jxcore-log: 
,09-23 06:04:52.007  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:04:52.007  5498  5544 I jxcore-log: 
09-23 06:04:52.008  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:04:52.008  5498  5544 I jxcore-log: 
,09-23 06:04:52.009  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:04:52.009  5498  5544 I jxcore-log: 
,09-23 06:04:52.010  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:04:52.010  5498  5544 I jxcore-log: 
,09-23 06:04:52.011  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-23 06:04:52.011  5498  5544 I jxcore-log: 
,09-23 06:04:52.011  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:04:52.011  5498  5544 I jxcore-log: 
09-23 06:04:52.012  5498  5544 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 06:04:52.012  5498  5544 I jxcore-log: 
,09-23 06:04:52.363   929  2988 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,09-23 06:04:52.451  5808  5808 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 06:04:52.456  5808  5808 D AndroidRuntime: CheckJNI is OFF
,09-23 06:04:52.488  5808  5808 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 06:04:52.524  5808  5808 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 06:04:52.540  5808  5808 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 06:04:52.550   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-23 06:04:52.551   929   942 I ActivityManager: Killing 5498:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-23 06:04:52.630   929  2989 D WifiService: Client connection lost with reason: 4
09-23 06:04:52.630   929  3508 D GraphicsStats: Buffer count: 2
,09-23 06:04:52.630   929  3459 I WindowState: WIN DEATH: Window{4c35301 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-23 06:04:52.707   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-23 06:04:52.707   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-23 06:04:52.708   929   942 E ActivityManager: Failure starting process com.test.thalitest
09-23 06:04:52.708   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-23 06:04:52.708   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:52.708   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:52.708   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:04:52.708   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 06:04:52.709   929   942 I ActivityManager:   Force finishing activity ActivityRecord{e8cf27a u0 com.test.thalitest/.MainActivity t2}
,09-23 06:04:52.710   929   952 I art     : Starting a blocking GC Explicit
,09-23 06:04:52.716   929  3174 W ActivityManager: Spurious death for ProcessRecord{8eb0afb 0:com.test.thalitest/u0a77}, curProc for 5498: null
,09-23 06:04:52.720   929   947 W WindowManager: Attempted to add application window with unknown token Token{8409a2b ActivityRecord{e8cf27a u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-23 06:04:52.721   929   947 W WindowManager: Token{8409a2b ActivityRecord{e8cf27a u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{8409a2b ActivityRecord{e8cf27a u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-23 06:04:52.721   929   947 W WindowManager: view not successfully added to wm, removing view
09-23 06:04:52.721   929   947 W WindowManager: Exception when adding starting window
09-23 06:04:52.721   929   947 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{ecafae2 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-23 06:04:52.721   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-23 06:04:52.721   929   947 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-23 06:04:52.721   929   947 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-23 06:04:52.721   929   947 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-23 06:04:52.721   929   947 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-23 06:04:52.721   929   947 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:52.721   929   947 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:52.721   929   947 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:04:52.721   929   947 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 06:04:52.792   929   952 I art     : Explicit concurrent mark sweep GC freed 21656(1325KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.529ms total 81.535ms
,09-23 06:04:52.814   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-23 06:04:52.818  5808  5808 I art     : System.exit called, status: 0
09-23 06:04:52.818  5808  5808 I AndroidRuntime: VM exiting with result code 0.
,09-23 06:04:52.823   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-23 06:04:52.833   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-23 06:04:52.836  3421  3421 I Keyboard.Facilitator: resetDictionaries() : en_US
09-23 06:04:52.838  5700  5700 D BluetoothMapAppObserver: onReceive
09-23 06:04:52.838  5700  5700 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-23 06:04:52.851  3498  3976 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-23 06:04:52.857   929  2968 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-23 06:04:52.867  3421  5819 I Keyboard.Facilitator.DecoderInitializer: run()
,09-23 06:04:52.873  3421  5819 I Decoder : createOrResetDecoder
,09-23 06:04:52.902  3566  3566 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-23 06:04:52.904    28    28 W kworker/2:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:04:52.912   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-23 06:04:52.907    28    28 W kworker/2:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:04:52.914  3634  3634 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,09-23 06:04:52.914  3634  3634 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-23 06:04:52.914    28    28 W kworker/2:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:04:52.921  3583  3723 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-23 06:04:52.924  3434  5822 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-23 06:04:52.928   929   941 E PackageManager: Failed to write settings, restoring backup
09-23 06:04:52.928   929   941 E PackageManager: java.io.IOException: write failed: EROFS (Read-only file system)
09-23 06:04:52.928   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
09-23 06:04:52.928   929   941 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
09-23 06:04:52.928   929   941 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
09-23 06:04:52.928   929   941 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
09-23 06:04:52.928   929   941 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
09-23 06:04:52.928   929   941 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:236)
09-23 06:04:52.928   929   941 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:468)
09-23 06:04:52.928   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4644)
09-23 06:04:52.928   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-23 06:04:52.928   929   941 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-23 06:04:52.928   929   941 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:52.928   929   941 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:52.928   929   941 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:04:52.928   929   941 E PackageManager: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
09-23 06:04:52.928   929   941 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
09-23 06:04:52.928   929   941 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
09-23 06:04:52.928   929   941 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
09-23 06:04:52.928   929   941 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
09-23 06:04:52.928   929   941 E PackageManager: 	... 12 more
,09-23 06:04:52.930  3434  3455 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj49B2AE933) - 
09-23 06:04:52.930   929   942 E DropBoxManagerService: Can't write: system_server_wtf
09-23 06:04:52.930   929   942 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-23 06:04:52.930   929   942 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 06:04:52.930   929   942 E DropBoxManagerService: 	... 13 more
--------- beginning of crash
09-23 06:04:52.931  3434  3455 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-23 06:04:52.931  3434  3455 E AndroidRuntime: Process: android.process.acore, PID: 3434
09-23 06:04:52.931  3434  3455 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-23 06:04:52.931  3434  3455 E AndroidRun,time: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:52.931  3434  3455 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 06:04:52.938   929  3603 I ActivityManager: Start proc 5825:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-23 06:04:52.939  3583  3723 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-23 06:04:52.939  3583  3723 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3583
09-23 06:04:52.939  3583  3723 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:04:52.939  3583  3723 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 06:04:52.943   929  5831 E DropBoxManagerService: Can't write: system_app_crash
09-23 06:04:52.943   929  5831 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 06:04:52.943   929  5831 E DropBoxManagerService: 	... 5 more
09-23 06:04:52.943   929  3175 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-23 06:04:52.947  3583  3723 I Process : Sending signal. PID: 3583 SIG: 9
09-23 06:04:52.954  3634  3634 I ConfigService: onCreate
09-23 06:04:52.955  3909  5838 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-23 06:04:52.955  3909  5838 D AccountUtils: Clearing selected account for com.test.thalitest
,09-23 06:04:52.959  3634  5839 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 06:04:52.959  3634  5839 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 06:04:52.959  3634  5839 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-23 06:04:52.963  3634  5839 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-23 06:04:52.973  3421  5819 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-23 06:04:53.040  3434  3455 I Process : Sending signal. PID: 3434 SIG: 9
,09-23 06:04:53.048   929  3142 D GraphicsStats: Buffer count: 1
,09-23 06:04:53.048   929  3459 I WindowState: WIN DEATH: Window{65e915d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-23 06:04:53.053   929  3806 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3583) has died
,09-23 06:04:53.054   929  3806 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-23 06:04:53.306   383   482 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
