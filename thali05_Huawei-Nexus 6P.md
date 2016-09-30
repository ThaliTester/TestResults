#### Test 87119404f33de82_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
,09-30 05:35:36.254   604   604 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-30 05:35:36.254   604   604 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
09-30 05:35:36.731  5724  5724 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-30 05:35:36.736  5724  5724 D AndroidRuntime: CheckJNI is OFF
09-30 05:35:36.765  5724  5724 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-30 05:35:36.801  5724  5724 I Radio-JNI: register_android_hardware_Radio DONE
09-30 05:35:36.818  5724  5724 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-30 05:35:36.824   930  3218 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-30 05:35:36.871   930  3218 I ActivityManager: Start proc 5733:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-30 05:35:36.897  5724  5724 D AndroidRuntime: Shutting down VM
,09-30 05:35:37.222   930  4002 I WindowManager: Screenshot max retries 4 of Token{13bfe43 ActivityRecord{3f577f2 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{d28134a u0 Starting com.test.thalitest} drawState=2
,09-30 05:35:37.298  5733  5733 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-30 05:35:37.331  5733  5733 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-30 05:35:37.356  5733  5733 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 9261-9280)
,09-30 05:35:37.356  5733  5733 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-30 05:35:37.376  5733  5733 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fd39837}
,09-30 05:35:37.377  5733  5733 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-30 05:35:37.377  5733  5733 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-30 05:35:37.383  5733  5733 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-30 05:35:37.384  5733  5733 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-30 05:35:37.419  5733  5733 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-30 05:35:37.438  5733  5733 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-30 05:35:37.438  5733  5733 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-30 05:35:37.438  5733  5733 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-30 05:35:37.438  5733  5733 I Adreno  : Build Date                       : 12/06/15
09-30 05:35:37.438  5733  5733 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-30 05:35:37.438  5733  5733 I Adreno  : Local Branch                     : mybranch17112971
09-30 05:35:37.438  5733  5733 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-30 05:35:37.438  5733  5733 I Adreno  : Remote Branch                    : NONE
09-30 05:35:37.438  5733  5733 I Adreno  : Reconstruct Branch               : NOTHING
,09-30 05:35:37.482   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@87d0769:true
,09-30 05:35:37.513  4039  4039 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[13885]" dev="sockfs" ino=13885 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 05:35:37.513  4039  4039 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[13885]" dev="sockfs" ino=13885 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 05:35:37.526  5733  5733 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-30 05:35:37.534  5733  5733 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-30 05:35:37.559  5733  5770 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-30 05:35:37.556   403   403 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33275]" dev="sockfs" ino=33275 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-30 05:35:37.556   403   403 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33275]" dev="sockfs" ino=33275 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-30 05:35:37.559  3899  3899 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[33924]" dev="sockfs" ino=33924 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 05:35:37.559  3899  3899 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[33924]" dev="sockfs" ino=33924 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-30 05:35:37.565  5733  5757 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-30 05:35:37.598  5733  5770 I OpenGLRenderer: Initialized EGL, version 1.4
,09-30 05:35:37.674   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +448ms (total +823ms)
,09-30 05:35:37.696  5733  5733 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5733
,09-30 05:35:37.753  5733  5733 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-30 05:35:37.885  5733  5773 D jxcore_app_log: JniHelper::setJavaVM(0xf4fbc000), pthread_self() = -584054480
,09-30 05:35:37.889  5733  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-30 05:35:37.889  5733  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-30 05:35:37.889  5733  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-30 05:35:37.889  5733  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-30 05:35:37.889  5733  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-30 05:35:37.889  5733  5773 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f11e9fc added. We now have 1 listener(s)
,09-30 05:35:37.891  5733  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-30 05:35:37.891  5733  5773 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:35:37.892  5733  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:35:37.892  5733  5773 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-30 05:35:37.894  5733  5773 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68fa70b added. We now have 1 listener(s)
,09-30 05:35:37.894  5733  5773 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:35:37.898   930  3014 D WifiService: New client listening to asynchronous messages
,09-30 05:35:37.899  5733  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:35:37.899  5733  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-30 05:35:37.899  5733  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-30 05:35:37.899  5733  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-30 05:35:37.899  5733  5773 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-30 05:35:37.901  5733  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:35:37.901  5733  5773 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-30 05:35:37.905  5733  5773 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:35:37.905  5733  5773 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:35:37.905  5733  5773 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-30 05:35:37.905  5733  5773 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 05:35:37.906  5733  5773 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-30 05:35:37.908  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:35:37.911  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:35:37.922  5733  5733 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-30 05:35:38.210  5733  5779 W jxcore-log: Initializing JXcore engine
09-30 05:35:38.210  5733  5779 W jxcore-log: JXcore engine is ready
,09-30 05:35:38.233  5779  5779 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11708 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-30 05:35:38.233  5779  5779 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13480]" dev="sockfs" ino=13480 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-30 05:35:38.233  5779  5779 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-30 05:35:38.233  5779  5779 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31564]" dev="sockfs" ino=31564 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-30 05:35:38.242  5733  5779 W jxcore-log: Starting JXcore engine
,09-30 05:35:38.297  5733  5779 W jxcore-log: Platform android
09-30 05:35:38.297  5733  5779 W jxcore-log: 
,09-30 05:35:38.297  5733  5779 W jxcore-log: Process ARCH arm
09-30 05:35:38.297  5733  5779 W jxcore-log: 
,09-30 05:35:38.399  5733  5779 I jxcore-log: JXcore Cordova bridge is ready!
09-30 05:35:38.399  5733  5779 I jxcore-log: 
09-30 05:35:38.399  5733  5779 W jxcore-log: JXcore engine is started
,09-30 05:35:38.411  5733  5773 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-30 05:35:38.418  5733  5733 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-30 05:35:38.433   930  3013 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:35:46.255   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:35:47.256   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:35:48.002  5733  5779 I jxcore-log: 2016-09-30 09:35:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-30 05:35:48.002  5733  5779 I jxcore-log: 
,09-30 05:35:48.004  5733  5779 I jxcore-log: 2016-09-30 09:35:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-30 05:35:48.004  5733  5779 I jxcore-log: 
,09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:35:48.007  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:35:48.009  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:35:48.010  5733  5779 I jxcore-log: 2016-09-30 09:35:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-30 05:35:48.010  5733  5779 I jxcore-log: 
09-30 05:35:48.012  5733  5779 I jxcore-log: 2016-09-30 09:35:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-30 05:35:48.012  5733  5779 I jxcore-log: 
,09-30 05:35:48.256  5733  5779 I jxcore-log: 2016-09-30 09:35:48 - DEBUG UnitTest_app: 'Running unit tests'
09-30 05:35:48.256  5733  5779 I jxcore-log: 
,09-30 05:35:48.257  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:35:48.257  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@40fcd09 added. We now have 2 listener(s)
09-30 05:35:48.258  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 05:35:48.258   604   604 I ServiceManager: Waiting for service AtCmdFwd...
09-30 05:35:48.258  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:35:48.258  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:35:48.258  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:35:48.258  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9293b0e added. We now have 2 listener(s)
09-30 05:35:48.258  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:35:48.259  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:35:48.261  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:35:48.269  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:35:48.273  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:48.273  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:35:48.274  5733  5779 D executeNativeTests: Running unit tests
,09-30 05:35:48.279  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:35:48.284  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:35:48.311  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:35:48.311  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c added. We now have 3 listener(s)
09-30 05:35:48.312  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:35:48.312  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-30 05:35:48.312  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:35:48.312  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:35:48.312  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 added. We now have 3 listener(s)
09-30 05:35:48.312  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:35:48.312  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:35:48.314  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:35:48.316  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:35:48.317  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:48.317  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:35:48.318  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 05:35:48.318  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:35:48.318  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:35:48.318  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:35:48.319  5733  5779 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-30 05:35:48.319  5733  5779 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-30 05:35:48.319  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 05:35:48.319  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:35:48.319  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:35:48.319  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:35:48.320  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:35:48.320  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:35:48.320  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:35:48.321  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:35:48.321  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:48.321  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:35:48.321  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:35:48.321  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:35:48.321  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c removed from the list
09-30 05:35:48.321  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:48.321  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 removed from the list
,09-30 05:35:48.327  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:35:48.331  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:35:48.332  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:35:48.332  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:35:48.332  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:35:48.332  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:35:48.333  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:35:48.333  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:35:48.333  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:48.333  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:35:48.334  5733  5779 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-30 05:35:48.334  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:35:48.334  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:35:48.334  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:35:48.334  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:35:48.334  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:48.334  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:48.334  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:35:48.334  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
,09-30 05:35:48.334  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:48.334  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:35:48.334  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:35:48.334  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:48.334  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:48.334  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:48.334  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:48.335  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:35:48.335  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:35:48.335  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:48.335  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:35:48.337  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 05:35:48.337  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 05:35:48.337  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 05:35:48.337  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-3,0 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 05:35:48.338  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 05:35:48.338  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:35:48.338  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:35:48.338  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:35:48.338  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:35:48.339  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:48.339  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:48.339  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:35:48.339  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:35:48.339  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:48.339  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:35:48.339  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:35:48.339  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:48.339  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:48.339  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:48.339  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:48.339  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:35:48.339  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:35:48.339  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:48.340  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:35:48.340  5733  5779 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 05:35:48.341  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:35:48.343  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:35:48.344  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:48.344  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:35:48.344  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:35:48.344  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:35:48.344  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:35:48.344  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:35:48.344  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:35:48.346  5733  5779 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 05:35:48.346  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 05:35:48.347  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:35:48.350  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:35:48.350  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:35:48.351  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:35:48.351  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 05:35:48.352  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-30 05:35:48.353  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-30 05:35:48.353  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:35:48.353  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:35:48.353  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:35:48.353  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:35:48.354  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:35:48.354  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:35:48.356  4646  4867 D BtGatt.GattService: registerClient() - UUID=9ab1fcdc-d6ac-4fed-9754-d3f21369e8c5
09-30 05:35:48.357  4646  4707 D BtGatt.GattService: onClientRegistered() - UUID=9ab1fcdc-d6ac-4fed-9754-d3f21369e8c5, clientIf=5
09-30 05:35:48.358  5733  5743 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:35:48.359  4646  4660 D BtGatt.GattService: start scan with filters
09-30 05:35:48.366  4646  4711 D BtGatt.ScanManager: handling starting scan
09-30 05:35:48.366  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:35:48.366  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:35:48.366  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:35:48.366  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:35:48.366  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:35:48.366  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:35:48.367  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 05:35:48.368  4646  4711 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:35:48.371  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:35:48.371  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:35:48.371  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:35:48.373  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:35:48.375  5733  5779 I io.jxcore.node.ConnectionHelper: start: OK
09-30 05:35:48.375  4646  4707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:35:48.375  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:48.376  4646  4711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 05:35:48.381  4646  4707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:35:48.381  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:48.382  4646  4711 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:35:48.382  4646  4711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:35:48.391  4646  4707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:35:48.391  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:48.397  4646  4707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:35:48.397  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:35:48.873  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 05:35:48.874  5733  5733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:35:48.874  5733  5733 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 05:35:49.257   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 05:35:49.259   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:35:50.260   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:35:51.261   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 05:35:52.276   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 05:35:52.280   930  3015 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-30 05:35:53.379  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:35:53.380  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 05:35:53.380  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 05:35:53.380  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:35:53.380  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:35:53.380  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:35:53.380  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:35:53.380  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:35:53.380  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:35:53.380  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:35:53.381  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:35:53.381  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:35:53.382  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:35:53.383  4646  4867 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:35:53.385  4646  4660 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:35:53.386  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-30 05:35:53.386  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-30 05:35:53.386  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:35:53.387  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:35:53.387  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:35:53.387  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:35:53.387  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:35:53.387  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:35:53.389  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 05:35:53.390  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:35:53.390  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:35:53.390  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-30 05:35:53.390  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 05:35:53.391  4646  4646 D BtGatt.ScanManager: awakened up at time 235315
09-30 05:35:53.391  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:35:53.393  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:35:53.393  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:53.393  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:35:53.393  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:35:53.393  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:35:53.393  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:35:53.393  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:53.393  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
,09-30 05:35:53.394  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:35:53.394  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:53.393  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:35:53.394  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:35:53.399  4646  4707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:35:53.399  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:35:53.400  4646  4711 D BtGatt.ScanManager: stopping BLe Batch
,09-30 05:35:53.412  4646  4707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:35:53.412  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:35:53.413  4646  4711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:35:53.439  4646  4707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-30 05:35:53.439  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:53.439  4646  4707 D BtGatt.GattService: current time is 235363515276
09-30 05:35:53.440  4646  4707 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -75, 42, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -73, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -77, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -75, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -71, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -80, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 94, -15, 90, -35, -8, -1, 1, -128, -90, 38, 0, 31, 2, 1, 6, 27, -1, 87, 1, 0, 23, 26, -19, 57, 101, 37, 90, -84, 20, -25, -19, 126, 37, 110, -74, 108, 2, -1, -8, -35, 90, -15, 94, 17, 10, 9, 77, 73, 32, 66, 97, 110, 100, 32, 50, 5, 2, -32, -2, -25, -2]
09-30 05:35:53.441  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 05:35:53.442  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-30 05:35:53.442  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-30 05:35:53.443  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 05:35:53.444  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 05:35:53.444  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 05:35:53.444  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 27, -1, 87, 1, 0, 23, 26, -19, 57, 101, 37, 90, -84, 20, -25, -19, 126, 37, 110, -74, 108, 2, -1, -8, -35, 90, -15, 94, 10, 9, 77, 73, 32, 66, 97, 110, 100, 32, 50, 5, 2, -32, -2, -25, -2]
,09-30 05:35:53.895  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:35:55.304   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 05:35:55.310   930  3015 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 05:35:56.262   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:35:57.264   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:35:58.265   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:35:58.397  5733  5779 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-30 05:35:58.403  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:35:58.414  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:35:58.427  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:58.427  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 05:35:58.428  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:35:58.428  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:35:58.428  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:35:58.428  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:35:58.428  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:35:58.435  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:35:58.437  5733  5779 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 05:35:58.437  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 05:35:58.443  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:35:58.443  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:35:58.444  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:35:58.444  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 05:35:58.448  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:35:58.448  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:35:58.448  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-30 05:35:58.449  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:35:58.449  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:35:58.450  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:35:58.453  4646  4859 D BtGatt.GattService: registerClient() - UUID=12fd9f4b-2aa0-44e9-9e40-8ea390ddada6
09-30 05:35:58.453  4646  4707 D BtGatt.GattService: onClientRegistered() - UUID=12fd9f4b-2aa0-44e9-9e40-8ea390ddada6, clientIf=5
,09-30 05:35:58.454  5733  5744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:35:58.455  4646  4867 D BtGatt.GattService: start scan with filters
,09-30 05:35:58.459  4646  4711 D BtGatt.ScanManager: handling starting scan
,09-30 05:35:58.459  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:35:58.459  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-30 05:35:58.459  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:35:58.459  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:35:58.459  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:35:58.459  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:35:58.459  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-30 05:35:58.463  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:35:58.463  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:35:58.463  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:35:58.465  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:35:58.466  4646  4707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:35:58.466  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:35:58.466  4646  4711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 05:35:58.468  5733  5779 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 05:35:58.471  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:35:58.471  5733  5779 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 05:35:58.471  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 05:35:58.471  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 05:35:58.471  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:58.472  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:35:58.472  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:35:58.472  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:35:58.472  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 05:35:58.472  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:35:58.472  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:35:58.472  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:35:58.472  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:35:58.473  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:35:58.473  4646  4707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:35:58.473  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:58.474  4646  4711 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:35:58.474  4646  4711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:35:58.474  4646  4660 D BtGatt.GattService: stopScan() - queue size =1
,09-30 05:35:58.475  4646  4859 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:35:58.475  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:35:58.475  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:35:58.475  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-30 05:35:58.475  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:35:58.475  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:35:58.475  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:35:58.475  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:35:58.475  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 05:35:58.479  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:35:58.479  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:35:58.479  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:35:58.479  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:35:58.479  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 05:35:58.480  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:35:58.481  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:35:58.481  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-30 05:35:58.481  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:58.481  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:35:58.481  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:35:58.481  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:35:58.481  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:35:58.481  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:35:58.481  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:58.482  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:35:58.482  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:35:58.482  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:35:58.482  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:35:58.482  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:35:58.483  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:35:58.483  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:35:58.483  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:35:58.483  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:35:58.484  5733  5779 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-30 05:35:58.485  4646  4707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:35:58.485  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:58.486  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:35:58.490  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:35:58.491  4646  4707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:35:58.492  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:35:58.492  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:35:58.492  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:35:58.493  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:35:58.493  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-30 05:35:58.493  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:35:58.493  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:35:58.493  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:35:58.495  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:35:58.496  5733  5779 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 05:35:58.496  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 05:35:58.498  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:35:58.499  4646  4707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:35:58.499  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:58.499  4646  4711 D BtGatt.ScanManager: stopping BLe Batch
,09-30 05:35:58.502  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 05:35:58.502  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:35:58.503  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 05:35:58.504  4646  4707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:35:58.504  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:58.504  4646  4711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:35:58.507  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:35:58.507  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:35:58.507  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,09-30 05:35:58.507  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:35:58.507  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:35:58.508  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:35:58.509  4646  4707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:35:58.509  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:58.511  4646  4859 D BtGatt.GattService: registerClient() - UUID=e0cd4bef-cff3-4b59-88ee-0d5f47c71b08
,09-30 05:35:58.511  4646  4707 D BtGatt.GattService: onClientRegistered() - UUID=e0cd4bef-cff3-4b59-88ee-0d5f47c71b08, clientIf=5
09-30 05:35:58.511  5733  5744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:35:58.512  4646  4659 D BtGatt.GattService: start scan with filters
,09-30 05:35:58.514  4646  4711 D BtGatt.ScanManager: handling starting scan
,09-30 05:35:58.514  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:35:58.514  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:35:58.514  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:35:58.514  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:35:58.514  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:35:58.514  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:35:58.515  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:35:58.517  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:35:58.517  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:35:58.517  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:35:58.518  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:35:58.519  4646  4707 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:35:58.519  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:58.519  4646  4711 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:35:58.521  5733  5779 I io.jxcore.node.ConnectionHelper: start: OK
,09-30 05:35:58.524  4646  4707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-30 05:35:58.525  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:35:58.525  4646  4711 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:35:58.525  4646  4711 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-30 05:35:58.534  4646  4707 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:35:58.534  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:35:58.539  4646  4707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:35:58.539  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:35:59.019  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-30 05:35:59.019  5733  5733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:35:59.019  5733  5733 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 05:35:59.266   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:00.267   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:01.268   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 05:36:01.357   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 05:36:01.359   930  3015 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,09-30 05:36:03.521  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:36:03.522  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:03.522  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 05:36:03.522  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:03.522  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:36:03.522  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:03.523  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:36:03.523  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:36:03.523  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-30 05:36:03.523  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:36:03.523  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:36:03.523  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:36:03.525  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:36:03.527  4646  4659 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:36:03.530  4646  4660 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:36:03.530  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:36:03.530  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:36:03.531  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:36:03.531  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 05:36:03.531  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:36:03.531  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:36:03.532  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:36:03.532  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:36:03.535  4646  4646 D BtGatt.ScanManager: awakened up at time 245459
09-30 05:36:03.536  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 05:36:03.536  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:36:03.537  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:36:03.537  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:36:03.537  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 05:36:03.539  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:36:03.542  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:36:03.542  4646  4707 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:36:03.542  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:36:03.542  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:36:03.542  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:36:03.542  4646  4711 D BtGatt.ScanManager: stopping BLe Batch
,09-30 05:36:03.548  4646  4707 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 05:36:03.549  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:36:03.549  4646  4711 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:36:03.572  4646  4707 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-30 05:36:03.572  4646  4707 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:36:03.572  4646  4707 D BtGatt.GattService: current time is 245496471489
09-30 05:36:03.572  4646  4707 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -76, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -76, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -71, 76, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -75, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -78, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 94, -15, 90, -35, -8, -1, 1, -128, -79, 34, 0, 31, 2, 1, 6, 27, -1, 87, 1, 0, 23, 26, -19, 57, 101, 37, 90, -84, 20, -25, -19, 126, 37, 110, -74, 108, 2, -1, -8, -35, 90, -15, 94, 17, 10, 9, 77, 73, 32, 66, 97, 110, 100, 32, 50, 5, 2, -32, -2, -25, -2, 81, 34, 97, 112, -14, -5, 1, -128, -75, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-30 05:36:03.573  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-30 05:36:03.573  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-30 05:36:03.573  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-30 05:36:03.573  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-30 05:36:03.574  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-30 05:36:03.574  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 27, -1, 87, 1, 0, 23, 26, -19, 57, 101, 37, 90, -84, 20, -25, -19, 126, 37, 110, -74, 108, 2, -1, -8, -35, 90, -15, 94, 10, 9, 77, 73, 32, 66, 97, 110, 100, 32, 50, 5, 2, -32, -2, -25, -2]
09-30 05:36:03.574  4646  4707 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-30 05:36:04.043  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:36:04.043  5733  5733 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:04.043  5733  5733 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,09-30 05:36:04.385   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-30 05:36:04.393   930  3015 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,09-30 05:36:08.543  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:36:08.543  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:36:08.543  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.544  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.544  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.544  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:36:08.544  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.544  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.544  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.545  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
,09-30 05:36:08.545  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.545  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.547  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:08.547  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.550  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.550  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 05:36:08.551  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.551  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.552  5733  5779 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-30 05:36:08.554  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.554  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.554  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 05:36:08.554  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.555  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.555  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.555  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.555  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.555  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.555  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.556  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.556  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:08.556  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.556  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.556  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:08.559  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.559  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.560  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.560  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.562  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 05:36:08.562  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.562  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.562  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.562  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.562  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.562  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:08.562  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.562  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.563  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.563  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.563  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.563  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.563  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.563  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:08.563  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.564  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.565  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.565  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.565  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
,09-30 05:36:08.566  5733  5779 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-30 05:36:08.566  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.566  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.566  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.566  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.566  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.566  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.566  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.566  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.567  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.567  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.567  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.567  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.567  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.567  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.567  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.568  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:36:08.568  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.568  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.568  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.569  5733  5779 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-30 05:36:08.569  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.569  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.569  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.570  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.570  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.570  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.570  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.570  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.570  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.570  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.570  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.570  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:08.570  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.570  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.570  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.571  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.571  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.571  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.572  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.572  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 05:36:08.573  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:36:08.573  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:36:08.573  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 05:36:08.573  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:36:08.573  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:36:08.573  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-30 05:36:08.573  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-30 05:36:08.573  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-30 05:36:08.573  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.573  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.574  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.574  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.574  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.574  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.574  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.574  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.574  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.574  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.574  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.574  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.574  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.574  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.574  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:08.576  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.577  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.577  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.577  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.578  5733  5779 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:36:08.579  5733  5779 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-30 05:36:08.579  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-30 05:36:08.582  5733  5779 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-30 05:36:08.582  5733  5779 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-30 05:36:08.582  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-30 05:36:08.583  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-30 05:36:08.584  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-30 05:36:08.584  5733  5779 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-30 05:36:08.584  5733  5779 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 05:36:08.584  5733  5779 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-30 05:36:08.584  5733  5779 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:36:08.584  5733  5779 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 05:36:08.584  5733  5,779 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-30 05:36:08.584  5733  5779 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:36:08.584  5733  5779 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-30 05:36:08.584  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-30 05:36:08.588  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-30 05:36:08.589  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-30 05:36:08.589  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-30 05:36:08.590  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-30 05:36:08.590  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-30 05:36:08.590  5733  5779 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-30 05:36:08.590  5733  5779 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-30 05:36:08.591  5733  5779 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-30 05:36:08.591  5733  5780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
,09-30 05:36:08.591  5733  5780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
09-30 05:36:08.591  5733  5780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
09-30 05:36:08.591  5733  5780 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
09-30 05:36:08.591  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.592  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.592  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.592  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.592  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.592  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.592  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.592  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-30 05:36:08.593  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.593  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.593  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
,09-30 05:36:08.593  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.593  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.593  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.593  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.594  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.594  5733  5781 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
09-30 05:36:08.595  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.595  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.595  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.595  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.596  5733  5779 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-30 05:36:08.596  5733  5780 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
,09-30 05:36:08.596  5733  5780 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:36:08.596  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.597  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.597  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 05:36:08.597  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.597  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.597  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.597  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.597  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.597  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.597  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.597  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.597  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.597  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:08.597  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.593  4859  4859 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33299]" dev="sockfs" ino=33299 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 05:36:08.597  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.598  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.598  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.598  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.598  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.593  4859  4859 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33299]" dev="sockfs" ino=33299 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 05:36:08.599  5733  5779 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-30 05:36:08.599  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.600  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.600  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.600  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.600  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.600  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.600  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.600  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.600  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.600  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.600  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.600  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.600  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.600  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.600  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:08.602  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:36:08.602  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.602  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.602  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.603  5733  5779 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-30 05:36:08.603  5733  5779 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-30 05:36:08.603  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 05:36:08.603  5733  5779 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-30 05:36:08.603  5733  5779 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 05:36:08.603  5733  5779 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-30 05:36:08.603  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 05:36:08.603  5733  5779 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-30 05:36:08.603  5733  5779 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-30 05:36:08.603  5733  5779 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-30 05:36:08.603  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 05:36:08.603  5733  5779 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-30 05:36:08.604  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:08.604  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:08.604  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:08.604  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.604  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.604  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.604  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.604  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:08.604  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.604  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.604  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:36:08.604  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.604  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.604  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.604  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.605  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:08.605  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:08.605  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.605  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.606  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:08.606  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.606  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:08.606  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:08.606  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
,09-30 05:36:08.606  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:08.606  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:08.606  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:08.607  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:08.607  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:11.269   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:12.270   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:13.271   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:13.607  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:13.608  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
,09-30 05:36:13.608  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:13.608  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.608  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.608  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,09-30 05:36:13.608  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:13.609  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:13.609  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:13.609  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 05:36:13.609  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:13.610  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.610  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.610  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:13.610  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:13.610  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:13.610  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.611  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:13.611  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.611  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.611  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:13.611  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.614  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:13.615  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 05:36:13.615  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:13.615  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.619  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-30 05:36:13.620  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:36:13.622  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-30 05:36:13.624  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-30 05:36:13.624  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
09-30 05:36:13.624  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-30 05:36:13.624  5733  5782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,09-30 05:36:13.625  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-30 05:36:13.625  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:36:13.625  5733  5733 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-30 05:36:13.626  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:13.626  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-30 05:36:13.626  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-30 05:36:13.626  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-30 05:36:13.627  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.627  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 05:36:13.627  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-30 05:36:13.627  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:13.627  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:13.627  5733  5733 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-30 05:36:13.627  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:36:13.627  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:36:13.627  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:36:13.627  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.627  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:13.627  5733  5782 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:36:13.626  4659  4659 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29671]" dev="sockfs" ino=29671 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-30 05:36:13.626  4659  4659 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29671]" dev="sockfs" ino=29671 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-30 05:36:13.628  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:36:13.629  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.629  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:13.629  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:36:13.629  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:13.629  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 05:36:13.629  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:36:13.629  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:13.629  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:36:13.629  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:13.629  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.629  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
09-30 05:36:13.629  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:13.629  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:13.629  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.630  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:13.630  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.630  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.630  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.630  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:13.630  5733  5782 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-30 05:36:13.630  5733  5782 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-30 05:36:13.631  5733  5782 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-30 05:36:13.631  5733  5733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-30 05:36:13.631  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:13.631  5733  5733 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:13.631  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:13.631  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:13.631  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.633  5733  5779 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-30 05:36:13.633  5733  5779 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-30 05:36:13.633  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-30 05:36:13.633  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:36:13.633  5733  5779 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-30 05:36:13.634  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:13.634  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:13.634  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:13.634  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:13.634  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.634  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.634  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:13.634  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
,09-30 05:36:13.634  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:13.634  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.634  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:13.634  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.634  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.635  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.635  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.637  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:13.637  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:13.637  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:13.637  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
,09-30 05:36:13.644  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-30 05:36:13.644  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:13.644  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:13.644  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:13.644  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.644  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.644  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:13.644  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:13.644  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:13.644  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
,09-30 05:36:13.644  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:13.644  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.644  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.645  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.645  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.646  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:13.646  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:36:13.646  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:13.646  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.647  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:36:13.647  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:36:13.647  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:36:13.647  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:36:13.647  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.647  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.648  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:36:13.648  5733  5779 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56e6b6c not in the list
09-30 05:36:13.648  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:13.648  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.648  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:13.648  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.648  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.648  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:13.648  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:13.649  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:36:13.649  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-30 05:36:13.649  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:13.650  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@646d535 not in the list
09-30 05:36:13.651  5733  5779 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-30 05:36:13.651  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-30 05:36:13.651  5733  5779 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-30 05:36:13.651  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-30 05:36:13.651  5733  5779 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-30 05:36:13.651  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-30 05:36:13.653  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-30 05:36:13.653  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-30 05:36:13.654  5733  5779 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,09-30 05:36:13.655  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 05:36:13.655  5733  5779 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-30 05:36:13.655  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-30 05:36:13.655  5733  5779 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-30 05:36:13.655  5733  5779 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-30 05:36:13.656  5733  5779 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-30 05:36:13.656  5733  5779 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-30 05:36:13.656  5733  5779 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
,09-30 05:36:13.656  5733  5779 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-30 05:36:13.656  5733  5779 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-30 05:36:13.656  5733  5779 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-30 05:36:13.657  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:36:13.657  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d425b0f added. We now have 3 listener(s)
09-30 05:36:13.657  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:36:13.659  5733  5779 D BluetoothAdapter: enable(): BT is already enabled..!
09-30 05:36:13.660   930  3218 D WifiService: setWifiEnabled: true pid=5733, uid=10077
,09-30 05:36:13.660   930  3218 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:36:13.726  4646  4839 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-30 05:36:13.726  4646  4856 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
09-30 05:36:13.726  5733  5780 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
09-30 05:36:13.727  5733  5780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
09-30 05:36:13.727  5733  5780 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,09-30 05:36:14.130  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:36:14.272   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:15.273   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:16.274   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 05:36:18.438   930  3013 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:36:18.665  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:36:18.665  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@999879c added. We now have 4 listener(s)
09-30 05:36:18.665  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:36:18.677  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:18.678  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@999879c removed from the list
,09-30 05:36:18.678  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:36:18.678  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:18.678  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:18.680  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:36:18.680  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5875a5 added. We now have 4 listener(s)
,09-30 05:36:18.680  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:36:18.683  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:18.683  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c5875a5 removed from the list
09-30 05:36:18.683  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:18.684  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:18.684  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:18.685  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:36:18.685  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8208d7a added. We now have 4 listener(s)
09-30 05:36:18.686  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:36:18.689   930  3892 D WifiService: setWifiEnabled: false pid=5733, uid=10077
09-30 05:36:18.689   930  3892 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:36:18.697  4646  4703 D BluetoothAdapterState: Current state: ON, message: 23
09-30 05:36:18.697  4646  4703 D BluetoothAdapterProperties: Setting state to 13
,09-30 05:36:18.697  4646  4703 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 05:36:18.698  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:36:18.698  4646  4703 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 05:36:18.699  4646  4703 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:36:18.702  4646  4646 D BluetoothMapService: onReceive
09-30 05:36:18.702  4646  4646 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 05:36:18.702  4646  4646 D BluetoothMapService: STATE_TURNING_OFF
09-30 05:36:18.702  4646  4646 D BluetoothMapService: MAP Service closeService in
09-30 05:36:18.702  4646  4646 D BluetoothMapMasInstance0: MAP Service shutdown
,09-30 05:36:18.702  4646  4646 D ObexServerSockets0: shutdown(block = true)
,09-30 05:36:18.705  4646  4869 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-30 05:36:18.707  4646  4646 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 05:36:18.707  4646  4646 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 05:36:18.707  4646  4856 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 05:36:18.707  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:36:18.707  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:36:18.708  4646  4870 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 05:36:18.708   930  3013 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 05:36:18.708   930  3013 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 05:36:18.708   930  3013 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:36:18.708   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 05:36:18.709  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.709  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:18.709  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:36:18.710  4646  4646 I BtOppRfcommListener: stopping Accept Thread
,09-30 05:36:18.710  4646  5404 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 05:36:18.711  4646  5404 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 05:36:18.714  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:18.719   930   943 I ActivityManager: Start proc 5786:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-30 05:36:18.719  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:18.719  4646  4707 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:36:18.720  4646  4703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 05:36:18.720   930  5482 D DhcpClient: Clearing IP address
09-30 05:36:18.720   511   928 D CommandListener: Clearing all IP addresses on wlan0
09-30 05:36:18.722  4646  4646 D HeadsetService: Received stop request...Stopping profile...
09-30 05:36:18.723   511   928 D CommandListener: Setting iface cfg
,09-30 05:36:18.727   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:18.727   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:18.727  3182  3934 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:18.728  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.728  3815  3834 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:36:18.728  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:36:18.728   930   930 D BluetoothHeadset: Proxy object disconnected
,09-30 05:36:18.728  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.728  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:18.729  4646  4646 D A2dpService: Received stop request...Stopping profile...
09-30 05:36:18.729  4646  4862 D A2dpStateMachine: Exit Disconnected: -1
09-30 05:36:18.730   930   930 D BluetoothA2dp: Proxy object disconnected
,09-30 05:36:18.731  4646  4646 D HidService: Received stop request...Stopping profile...
09-30 05:36:18.731  4646  4646 D HidService: Stopping Bluetooth HidService
09-30 05:36:18.731  3625  5538 V NativeCrypto: Read error: ssl=0x7f80e86180: I/O error during system call, Connection timed out
09-30 05:36:18.732  4646  4646 D HealthService: Received stop request...Stopping profile...
09-30 05:36:18.733  3625  5538 V NativeCrypto: SSL shutdown failed: ssl=0x7f80e86180: I/O error during system call, Broken pipe
09-30 05:36:18.734  4646  4646 D PanService: Received stop request...Stopping profile...
09-30 05:36:18.734  3182  3182 D HeadsetProfile: Bluetooth service disconnected
,09-30 05:36:18.734  3182  3182 D BluetoothA2dp: Proxy object disconnected
,09-30 05:36:18.735  3182  3182 D BluetoothInputDevice: Proxy object disconnected
09-30 05:36:18.735  3182  3182 D HidProfile: Bluetooth service disconnected
09-30 05:36:18.735  3182  3182 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 05:36:18.735  3182  3182 D PanProfile: Bluetooth service disconnected
09-30 05:36:18.735   930  3223 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
09-30 05:36:18.735  4646  4646 D BluetoothMapService: Received stop request...Stopping profile...
,09-30 05:36:18.735  4646  4646 D BluetoothMapService: stop()
09-30 05:36:18.736   930  5480 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
09-30 05:36:18.736  4646  4646 D BluetoothMapAppObserver: deinitObservers()
09-30 05:36:18.736  4646  4646 D BluetoothMapAppObserver: removeReceiver()
09-30 05:36:18.737  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:36:18.737  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:36:18.738   930  5480 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-30 05:36:18.738   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-30 05:36:18.738   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-30 05:36:18.738  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.738  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:18.738  4646  4646 V BluetoothAdapterState: isTurningOff()=true
,09-30 05:36:18.738  4646  4646 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:18.739  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:18.739  4646  4646 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:18.740  3182  3182 D BluetoothMap: Proxy object disconnected
09-30 05:36:18.740  3182  3182 D MapProfile: Bluetooth service disconnected
09-30 05:36:18.742  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:36:18.742   602   602 E Parcel  : Reading a NULL string not supported here.
09-30 05:36:18.743  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.743  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:18.743   930   930 D RttService: SCAN_AVAILABLE : 1
09-30 05:36:18.743   930  3121 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 05:36:18.745   930  3015 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-30 05:36:18.746  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.746  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:36:18.746  4646  4646 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-30 05:36:18.746  4646  4646 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 05:36:18.747  4646  4646 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:18.747  4646  4707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 05:36:18.747  4646  4646 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:18.747  3775  3910 W QCNEJ   : |CORE| network lost: 100
09-30 05:36:18.747  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:18.747  4646  4646 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:18.747  4646  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-30 05:36:18.747  4646  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:18.747  4646  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:18.747  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.747  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:18.748  4646  4707 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-30 05:36:18.749  3775  3910 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-30 05:36:18.750  4646  4707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 05:36:18.750  4646  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:18.750  4646  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:18.750  4646  4839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:36:18.750  4646  4839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 05:36:18.750  4646  4839 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:36:18.750   930  3013 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 05:36:18.750  4646  4839 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 05:36:18.751  4646  4646 D SapService: Received stop request...Stopping profile...
09-30 05:36:18.751  4646  4646 V SapService: stop()
09-30 05:36:18.751  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.751  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:18.752  4646  4646 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:18.752  4646  4646 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:18.752  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:18.752  4646  4646 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:18.752  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.752  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:18.752  4646  4646 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 05:36:18.753  4646  4646 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 05:36:18.753  4646  4707 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 05:36:18.753   930  5483 D DhcpClient: Receive thread stopped
09-30 05:36:18.753  4646  4646 V BluetoothAdapterState: isTurningOff()=true
,09-30 05:36:18.753  4646  4646 V BluetoothAdapterState: isTurningOn()=false
,09-30 05:36:18.753  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:18.753  4646  4646 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:36:18.753  4646  4646 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,09-30 05:36:18.753  4646  4707 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 05:36:18.754  4646  4646 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-30 05:36:18.754  4646  4646 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:18.754  4646  4646 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:18.754  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:18.754  4646  4646 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:18.754  4646  4646 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 05:36:18.754  4646  4646 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 05:36:18.756  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.756  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:18.756  4646  4646 D BluetoothMapService: MAP Service closeService in
09-30 05:36:18.756  4646  4646 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:18.756  4646  4646 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:18.756  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:18.756  4646  4646 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:18.757  4646  4646 D BluetoothMapService: cleanup()
09-30 05:36:18.757  4646  4646 D BluetoothMapService: MAP Service closeService in
09-30 05:36:18.757  4646  4646 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:18.757  4646  4646 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:18.757  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:18.757  4646  4646 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:18.758   930  3013 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:36:18.760  4646  4703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 05:36:18.760  4646  4703 D BluetoothAdapterProperties: Setting state to 15
09-30 05:36:18.760  4646  4703 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 05:36:18.761  4646  4703 I BluetoothAdapterState: Entering BleOnState
09-30 05:36:18.761   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:18.761   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:36:18.762  3182  3199 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 05:36:18.762   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 05:36:18.763  3182  3194 D BluetoothMap: onBluetoothStateChange: up=false
09-30 05:36:18.763  3182  3934 D BluetoothPan: onBluetoothStateChange on: false
09-30 05:36:18.764  3182  3199 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 05:36:18.767  3815  4094 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:18.767  3182  3194 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:36:18.768   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:18.769  3182  3934 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:18.769   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 05:36:18.770  4646  4703 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 05:36:18.770  4646  4703 D BluetoothAdapterProperties: Setting state to 16
09-30 05:36:18.770  4646  4703 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-30 05:36:18.771  4646  4703 D BluetoothAdapterProperties: onBleDisable
09-30 05:36:18.771  4646  4703 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:36:18.771  4646  4704 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 05:36:18.772  4646  4707 D BluetoothAdapterProperties: Scan Mode:20
,09-30 05:36:18.773  4646  4839 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 05:36:18.773  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.773  4646  4839 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.773  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:36:18.774  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:18.776  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:18.777  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:18.778  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:18.779  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:18.800   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:36:18.800   511   928 D CommandListener: Clearing all IP addresses on wlan0
09-30 05:36:18.801   511   928 D TetherController: Setting IP forward enable = 0
,09-30 05:36:18.802   930  3015 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-30 05:36:18.803   930  3015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 05:36:18.803  5786  5786 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-30 05:36:18.805   930  3013 D DhcpClient: doQuit
09-30 05:36:18.805   930  3013 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 05:36:18.805   930  5482 D DhcpClient: onQuitting
09-30 05:36:18.806  3506  3506 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-30 05:36:18.809   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-30 05:36:18.813  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.813  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:36:18.814  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:36:18.814  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:18.816  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.816  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:18.816  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.816  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:18.817  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:18.818  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:18.818  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:18.818  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:18.819  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:18.819  5390  5390 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@64bb893 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-30 05:36:18.820  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:18.821  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:18.821  4983  4983 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-30 05:36:18.823  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:36:18.823  5140  5164 I SarControlServiceFlow: rese,tSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:36:18.823  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 05:36:18.823  5140  5164 E SarControlService: no key has been found,reset the power
09-30 05:36:18.824  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 05:36:18.824  3506  3506 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 05:36:18.824  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:36:18.824  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 05:36:18.824  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:36:18.824  5166  5166 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 05:36:18.826  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 05:36:18.826  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 05:36:18.826  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 05:36:18.827  3506  3506 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 05:36:18.827  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:36:18.827  5166  5166 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 05:36:18.830  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000ea03000000000000ffffffff]
09-30 05:36:18.830  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:36:18.830  5166  5180 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-30 05:36:18.831  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:36:18.831  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-30 05:36:18.834  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000eb03000000000000ffffffff]
09-30 05:36:18.834  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:36:18.834  5166  5180 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-30 05:36:18.835  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:36:18.835  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 05:36:18.844  5786  5786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:36:18.850   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14ae8f1:true
,09-30 05:36:18.861  3506  3506 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 05:36:18.862  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:36:18.863  3506  3506 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-30 05:36:18.863   511   928 E Netd    : netlink response contains error (No such file or directory)
09-30 05:36:18.863   511   928 D TetherController: Setting IP forward enable = 0
,09-30 05:36:18.865   930  3015 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-30 05:36:18.866   930  3015 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 05:36:18.878   930  3475 I ActivityManager: Start proc 5818:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-30 05:36:18.885  5786  5786 D LocalBluetoothProfileManager: Adding local MAP profile
09-30 05:36:18.888  5786  5786 D BluetoothMap: Create BluetoothMap proxy object
,09-30 05:36:18.895  5786  5786 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-30 05:36:18.912  5818  5818 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-30 05:36:18.916  5786  5786 D DockEventReceiver: finishStartingService: stopping service
,09-30 05:36:18.923   930  4002 I ActivityManager: Killing 5051:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-30 05:36:18.966   930  3013 D wifi    : In wifi stop Hal
,09-30 05:36:18.966  5114  5114 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 05:36:18.966   930  3013 D wifi    : halHandle = 0x7f6a8d1680, mVM = 0x7f86f4d140, mCls = 0x100a02
09-30 05:36:18.966   930  3505 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 05:36:18.966   930  3505 D WifiHAL : Got a signal to exit!!!
09-30 05:36:18.966   930  3505 I WifiHAL : Exit wifi_event_loop
09-30 05:36:18.967   930  3013 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-30 05:36:18.967   930  3013 E WifiHAL : Event processing terminated
09-30 05:36:18.967   930  3013 D wifi    : In wifi cleaned up handler
09-30 05:36:18.967   930  3013 I WifiHAL : Internal cleanup completed
09-30 05:36:18.968  4173  4275 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 05:36:18.968  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:18.970  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:18.971  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:18.979  4646  4707 I bt_hci  : shut_down
,09-30 05:36:18.983  4646  4712 D bt_hwcfg: hw_epilog_process
,09-30 05:36:18.983  4646  4712 I bt_vendor: low_power_mode_cb
,09-30 05:36:18.986  4646  4712 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-30 05:36:18.986  4646  4712 I bt_vendor: epilog_cb
09-30 05:36:18.986  4646  4712 I bt_hci  : epilog_finished_callback
,09-30 05:36:18.989   930  3505 D wifi    : set interface wlan0 flags (DOWN)
,09-30 05:36:18.989  4646  4707 I bt_hci_h4: hal_close
09-30 05:36:18.989   930  3013 D WifiNative-HAL: HAL event thread stopped successfully
09-30 05:36:18.989  4646  4707 I bt_userial_vendor: device fd = 54 close
,09-30 05:36:19.097  4646  4704 D bt_stack_manager: event_shut_down_stack finished.
,09-30 05:36:19.097  4646  4703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 05:36:19.099  4646  4703 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 05:36:19.099  4646  4646 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 05:36:19.100  4646  4646 D BtGatt.GattService: Received stop request...Stopping profile...
09-30 05:36:19.100  4646  4646 D BtGatt.GattService: stop()
09-30 05:36:19.100  4646  4646 D BtGatt.AdvertiseManager: advertise clients cleared
,09-30 05:36:19.101  4646  4646 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:36:19.102  4646  4646 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:19.102  4646  4646 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:19.102  4646  4646 V BluetoothAdapterState: isBleTurningOff()=true
09-30 05:36:19.102  4646  4703 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-30 05:36:19.102  4646  4703 D BluetoothAdapterProperties: Setting state to 10
,09-30 05:36:19.102  4646  4703 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 05:36:19.103  4646  4703 I BluetoothAdapterState: Entering OffState
09-30 05:36:19.103   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-30 05:36:19.109  4646  4646 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 05:36:19.109  4646  4646 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 05:36:19.109  4646  4646 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 05:36:19.111  4646  4704 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 05:36:19.119  4646  4646 I art     : System.exit called, status: 0
,09-30 05:36:19.119  4646  4646 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 05:36:19.167   930   941 I ActivityManager: Process com.android.bluetooth (pid 4646) has died
,09-30 05:36:19.191   930   947 D Tethering: InitialState.processMessage what=4
,09-30 05:36:19.194   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 05:36:19.199  5818  5818 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.199  5818  5818 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.199  5818  5818 D StrictMode: StrictMode policy violation; ~duration=190 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.199  5818  5818 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.199  5818  5818 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.k.d(PG:583)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.e.b(PG:170)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.199  5818  5818 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.199  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.200  5818  5818 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at java.io.File.exists(File.java:361)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.200  5818  5818 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:36:19.200  5818  5818 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:36:19.204  5786  5786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 05:36:19.219   930  3223 I ActivityManager: Start proc 5851:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
09-30 05:36:19.220  5786  5786 D DockEventReceiver: finishStartingService: stopping service
09-30 05:36:19.221   930  4001 I ActivityManager: Killing 5512:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,09-30 05:36:19.300  5851  5851 D AdapterServiceConfig: Adding HeadsetService
09-30 05:36:19.300  5851  5851 D AdapterServiceConfig: Adding A2dpService
09-30 05:36:19.300  5851  5851 D AdapterServiceConfig: Adding HidService
09-30 05:36:19.300  5851  5851 D AdapterServiceConfig: Adding HealthService
09-30 05:36:19.300  5851  5851 D AdapterServiceConfig: Adding PanService
09-30 05:36:19.300  5851  5851 D AdapterServiceConfig: Adding GattService
09-30 05:36:19.301  5851  5851 D AdapterServiceConfig: Adding BluetoothMapService
09-30 05:36:19.301  5851  5851 D AdapterServiceConfig: Adding SapService
,09-30 05:36:19.303   930   940 I ActivityManager: Killing 5525:com.android.chrome/u0a39 (adj 15): empty #17
,09-30 05:36:19.356  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:36:19.364  4008  4008 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 05:36:19.367  4008  4008 D SystemUpdateService: onCreate
,09-30 05:36:19.374  4008  4008 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-30 05:36:19.381  4008  4008 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 05:36:19.384  4008  5509 I iu.UploadsManager: num queued entries: 0
,09-30 05:36:19.384  4008  5509 I iu.UploadsManager: num updated entries: 0
09-30 05:36:19.385  4008  5509 I iu.SyncManager: NEXT; no task
,09-30 05:36:19.389  4008  4008 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 05:36:19.390  4008  4008 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
09-30 05:36:19.391  4008  5863 I SystemUpdateService: active receiver: enabled
,09-30 05:36:19.397  4008  5863 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:36:19.398  4008  5863 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 05:36:19.398  4008  5863 I SystemUpdateService: now status is 0 (complete)
09-30 05:36:19.399  4008  5863 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:36:19.399  4008  5863 I SystemUpdateService: file has been verified
,09-30 05:36:19.399  4008  5863 I SystemUpdateService: OTA package size = 21989297
,09-30 05:36:19.402   930  3218 I ActivityManager: Start proc 5865:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-30 05:36:19.419  4008  5863 I SystemUpdateService: showing system update notification
,09-30 05:36:19.438  5865  5865 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-30 05:36:19.443  5865  5865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:36:19.451  5865  5865 D SprintDMHelper: simOperator: 
,09-30 05:36:19.452  5865  5865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:36:19.464   930  3899 I ActivityManager: Start proc 5877:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-30 05:36:19.466  4008  4008 D SystemUpdateService: onDestroy
09-30 05:36:19.468   930  4001 I ActivityManager: Killing 5542:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,09-30 05:36:19.503  5818  5844 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-30 05:36:19.516   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@afa420c:true
,09-30 05:36:19.599  5114  5893 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 05:36:19.608   930  4002 I ActivityManager: Start proc 5894:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-30 05:36:19.612   930  3223 I ActivityManager: Killing 5390:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-30 05:36:19.662  5894  5894 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-30 05:36:19.809   930  3892 I ActivityManager: Killing 4718:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-30 05:36:19.840   930  4002 I ActivityManager: Start proc 5906:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-30 05:36:19.871  5906  5906 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-30 05:36:19.878   930  3475 I ActivityManager: Killing 5596:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-30 05:36:23.711   930  4001 D WifiService: setWifiEnabled: true pid=5733, uid=10077
,09-30 05:36:23.712   930  4001 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:36:23.722   511   928 D SoftapController: Softap fwReload - Ok
,09-30 05:36:23.732   511   928 D CommandListener: Setting iface cfg
,09-30 05:36:23.733   511   928 D CommandListener: Trying to bring down wlan0
,09-30 05:36:23.735   511   928 D CommandListener: Clearing all IP addresses on wlan0
,09-30 05:36:23.742   930  3013 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 05:36:24.315   930  3013 D wifi    : set interface wlan0 flags (UP)
,09-30 05:36:24.318   930  3013 I WifiHAL : Initializing wifi
09-30 05:36:24.318   930  3013 I WifiHAL : Creating socket
09-30 05:36:24.319   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-30 05:36:24.320   930  3013 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 05:36:24.320   930  3013 D wifi    : Did set static halHandle = 0x7f6a8d1680
09-30 05:36:24.320   930  3013 D wifi    : halHandle = 0x7f6a8d1680, mVM = 0x7f86f4d140, mCls = 0x1982
09-30 05:36:24.321   930  3013 D wifi    : array field set
09-30 05:36:24.321   930  3013 I WifiNative-HAL: interface[0] = wlan0
09-30 05:36:24.322   930  5924 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547248477824
,09-30 05:36:24.322   930  5924 D wifi    : waitForHalEvents called, vm = 0x7f86f4d140, obj = 0x1982, env = 0x7f67433ac0
,09-30 05:36:24.391  5925  5925 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 05:36:24.405  5925  5925 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 05:36:24.412  5925  5925 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 05:36:24.413  5925  5925 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 05:36:24.425   930  3013 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 05:36:24.433  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:24.433  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:24.433  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:24.433  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:24.434  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:24.435  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:24.435  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:24.435  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:24.435   930  3013 D WifiConfigStore: Loading config and enabling all networks 
09-30 05:36:24.436  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:24.436  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:36:24.437  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:24.437  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:24.438  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:24.439  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:24.440  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:24.444   930  3013 D WifiConfigStore: loaded 0 passpoint configs
09-30 05:36:24.445   930  3013 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-30 05:36:24.445   930  3013 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-30 05:36:24.446   930  3013 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-30 05:36:24.446   930  3013 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 05:36:24.447   930  3013 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-30 05:36:24.447   930  3013 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 05:36:24.447   930  3013 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 05:36:24.450   930  3013 D WifiNative-HAL: Setting external_sim to 1
,09-30 05:36:24.450  5114  5114 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 05:36:24.450   930  3013 D wifi    : setting dfs flag to true, 0x7f6d0adde0
09-30 05:36:24.451   930  3013 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 05:36:24.451   930  3013 D wifi    : setting scan oui 0x7f6d0adde0
09-30 05:36:24.451   930  3013 D WifiHAL : Sending mac address OUI
09-30 05:36:24.454   930  3013 E native  : do suspend false
,09-30 05:36:24.461   930  3013 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-30 05:36:24.461   930   930 D RttService: SCAN_AVAILABLE : 3
09-30 05:36:24.461   930  3121 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 05:36:24.465   511   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 05:36:24.466   511   928 D CommandListener: Setting iface cfg
09-30 05:36:24.466   930  3012 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '124 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 124 Failed to set address (No such device)'
,09-30 05:36:24.467   930  3012 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 05:36:24.475   930  3012 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 05:36:24.475   930  3012 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-30 05:36:24.479   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=266403 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-30 05:36:27.697  5925  5925 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:36:27.708  5925  5925 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:36:27.714  5925  5925 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:36:27.720  5925  5925 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:36:27.725  5925  5925 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:36:27.750   930  3013 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-30 05:36:27.751   930  3013 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-30 05:36:27.751   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:36:27.764   930  3013 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 05:36:27.801   930  3013 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 05:36:27.804  5925  5925 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 05:36:28.236  5925  5925 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 05:36:28.273  5925  5925 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-30 05:36:28.275  5925  5925 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 05:36:28.287   930  3013 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-30 05:36:28.287   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:36:28.287   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 05:36:28.306   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:36:28.320   511   928 D CommandListener: Setting iface cfg
,09-30 05:36:28.326   930  3013 D WifiStateMachine: Start Dhcp Watchdog 2
,09-30 05:36:28.334   930  5931 D DhcpClient: Receive thread started
,09-30 05:36:28.338   930  3013 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-30 05:36:28.338   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 05:36:28.338   930  3015 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-30 05:36:28.427   930  3013 E native  : do suspend false
,09-30 05:36:28.444   930  5930 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 05:36:28.457   930  5931 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172570, domain null
,09-30 05:36:28.458   930  5930 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172570 seconds
09-30 05:36:28.460   930  5930 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 05:36:28.472   930  5931 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 05:36:28.473   930  5930 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 05:36:28.475   511   928 D CommandListener: Setting iface cfg
,09-30 05:36:28.481   930  3013 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 05:36:28.485   930  5930 D DhcpClient: Scheduling renewal in 86399s
,09-30 05:36:28.502   930  3013 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
09-30 05:36:28.505   930  3013 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 05:36:28.506   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-30 05:36:28.509   930  3013 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-30 05:36:28.518   930  3015 D ConnectivityService: Adding iface wlan0 to network 101
,09-30 05:36:28.557   930  3015 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-30 05:36:28.557   930  3015 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-30 05:36:28.559   930  3015 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-30 05:36:28.561   930  3015 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-30 05:36:28.563   930  3015 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-30 05:36:28.570   930  3015 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-30 05:36:28.574   930  3015 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-30 05:36:28.574   930  3015 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-30 05:36:28.574   930  3015 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-30 05:36:28.574   930  3015 D ConnectivityService:    accepting network in place of null
09-30 05:36:28.574   930  3013 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 05:36:28.574   930  3013 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:36:28.575   930  3015 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -37]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 05:36:28.587   930  5929 D NetlinkSocketObserver: NeighborEvent{elapsedMs=270511, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 05:36:28.597   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:36:28.621   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:36:28.624   930  3015 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 05:36:28.624  3775  3910 W QCNEJ   : |CORE| network available: 101
09-30 05:36:28.624   930  3015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 05:36:28.626   930  3015 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-30 05:36:28.627   930   947 D Tethering: MasterInitialState.processMessage what=3
09-30 05:36:28.629  3775  3910 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
09-30 05:36:28.630  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:36:28.630  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:36:28.630  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.630  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:28.631  3775  3910 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 05:36:28.631  3775  3910 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-30 05:36:28.634  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:36:28.634  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:36:28.634  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.634  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:36:28.637  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:36:28.637  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:36:28.637  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.637  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:36:28.637  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:36:28.637  5140  5164 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:36:28.638  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 05:36:28.638  5140  5164 E SarControlService: no key has been found,reset the power
09-30 05:36:28.638  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 05:36:28.638  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:36:28.638  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,09-30 05:36:28.639  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 05:36:28.640  5166  5166 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 05:36:28.643  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 05:36:28.643  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 05:36:28.643  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 05:36:28.644  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:36:28.644  5166  5166 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 05:36:28.645  4983  4983 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-30 05:36:28.648  4008  4008 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-30 05:36:28.652  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000ec03000000000000ffffffff]
09-30 05:36:28.652  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:36:28.652  5166  5180 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-30 05:36:28.652  4008  4008 D SystemUpdateService: onCreate
09-30 05:36:28.653  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:36:28.653  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 05:36:28.658  4008  4008 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 05:36:28.659  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000ed03000000000000ffffffff]
09-30 05:36:28.659  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:36:28.659  5166  5180 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,09-30 05:36:28.660  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 05:36:28.660  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 05:36:28.672  4008  4008 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-30 05:36:28.673   930  5928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-30 05:36:28.677  4008  5509 I iu.UploadsManager: num queued entries: 0
,09-30 05:36:28.677  4008  5509 I iu.UploadsManager: num updated entries: 0
09-30 05:36:28.678  4008  5509 I iu.SyncManager: NEXT; no task
,09-30 05:36:28.680  4008  5942 I SystemUpdateService: active receiver: enabled
,09-30 05:36:28.682  4008  4008 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 05:36:28.683  4008  4008 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 05:36:28.685  5865  5865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:36:28.688  5865  5865 D SprintDMHelper: simOperator: 
,09-30 05:36:28.689  5865  5865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:36:28.710  4008  5942 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:36:28.718   930  3476 D WifiService: setWifiEnabled: false pid=5733, uid=10077
,09-30 05:36:28.718   930  3476 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:36:28.720   930  3013 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-30 05:36:28.720   930  3013 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-30 05:36:28.720   930  3013 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:36:28.720   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:36:28.727  4008  5942 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 05:36:28.727  4008  5942 I SystemUpdateService: now status is 0 (complete)
09-30 05:36:28.727  4008  5942 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:36:28.727  4008  5942 I SystemUpdateService: file has been verified
09-30 05:36:28.727  4008  5942 I SystemUpdateService: OTA package size = 21989297
,09-30 05:36:28.728   930  5930 D DhcpClient: Clearing IP address
,09-30 05:36:28.729   511   928 D CommandListener: Clearing all IP addresses on wlan0
,09-30 05:36:28.730   511   928 D CommandListener: Setting iface cfg
,09-30 05:36:28.732   930  5931 D DhcpClient: Receive thread stopped
09-30 05:36:28.733  4008  5942 I SystemUpdateService: showing system update notification
,09-30 05:36:28.745   930  5928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-30 05:36:28.745   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-30 05:36:28.745   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
09-30 05:36:28.745   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-30 05:36:28.748  4008  4008 D SystemUpdateService: onDestroy
09-30 05:36:28.750   602   602 E Parcel  : Reading a NULL string not supported here.
09-30 05:36:28.750   930   930 D RttService: SCAN_AVAILABLE : 1
09-30 05:36:28.751   930  3121 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-30 05:36:28.751   930  3015 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-30 05:36:28.753  3775  3910 W QCNEJ   : |CORE| network lost: 101
09-30 05:36:28.754  3775  3910 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-30 05:36:28.755   930  3013 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-30 05:36:28.758   930  3013 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-30 05:36:28.773   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:36:28.795   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-30 05:36:28.795   511   928 D CommandListener: Clearing all IP addresses on wlan0
09-30 05:36:28.796   930  3015 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-30 05:36:28.796   930  3015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:36:28.797   930  3013 D DhcpClient: doQuit
09-30 05:36:28.797   930  3013 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-30 05:36:28.797   930  5930 D DhcpClient: onQuitting
09-30 05:36:28.798  5925  5925 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-30 05:36:28.801   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-30 05:36:28.805  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:28.805  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:28.805  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.805  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:28.808  5925  5925 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-30 05:36:28.808  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:28.808  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:28.808  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.808  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:28.809  4983  4983 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-30 05:36:28.810  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:28.810  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:28.810  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:28.810  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:28.811  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:28.812  4008  4008 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 05:36:28.812  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:28.813  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:28.814  5925  5925 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-30 05:36:28.814  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:36:28.814  5140  5164 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:36:28.814  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-30 05:36:28.814  5140  5164 E SarControlService: no key has been found,reset the power
09-30 05:36:28.815  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-30 05:36:28.815  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:36:28.815  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 05:36:28.815  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:36:28.815  5166  5166 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-30 05:36:28.816  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-30 05:36:28.816  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-30 05:36:28.817  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,09-30 05:36:28.820  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,09-30 05:36:28.820  5166  5166 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 05:36:28.821  4008  4008 D SystemUpdateService: onCreate
,09-30 05:36:28.824  4008  4008 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 05:36:28.826  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000ee03000000000000ffffffff]
09-30 05:36:28.826  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:36:28.826  5166  5180 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
,09-30 05:36:28.827  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:36:28.827  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,09-30 05:36:28.830  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000ef03000000000000ffffffff]
09-30 05:36:28.830  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-30 05:36:28.830  5166  5180 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
09-30 05:36:28.831  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:36:28.831  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-30 05:36:28.833  4008  5960 I SystemUpdateService: active receiver: enabled
,09-30 05:36:28.835  4008  4008 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-30 05:36:28.839  4008  5509 I iu.UploadsManager: num queued entries: 0
09-30 05:36:28.840  4008  5509 I iu.UploadsManager: num updated entries: 0
09-30 05:36:28.840  4008  5509 I iu.SyncManager: NEXT; no task
,09-30 05:36:28.843  4008  4008 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-30 05:36:28.844  4008  4008 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 05:36:28.845  5865  5865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-30 05:36:28.850  5925  5925 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-30 05:36:28.850  5865  5865 D SprintDMHelper: simOperator: 
09-30 05:36:28.851  5865  5865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:36:28.857   511   928 E Netd    : netlink response contains error (No such file or directory)
,09-30 05:36:28.858   930  3015 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-30 05:36:28.859  4008  5960 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:36:28.861  4008  5960 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-30 05:36:28.861  4008  5960 I SystemUpdateService: now status is 0 (complete)
09-30 05:36:28.861  4008  5960 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:36:28.861  4008  5960 I SystemUpdateService: file has been verified
09-30 05:36:28.861  4008  5960 I SystemUpdateService: OTA package size = 21989297
,09-30 05:36:28.863  5925  5925 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-30 05:36:28.871   930  3013 D wifi    : In wifi stop Hal
,09-30 05:36:28.871   930  3013 D wifi    : halHandle = 0x7f6a8d1680, mVM = 0x7f86f4d140, mCls = 0x1982
09-30 05:36:28.871   930  5924 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
09-30 05:36:28.871   930  5924 D WifiHAL : Got a signal to exit!!!
09-30 05:36:28.872   930  5924 I WifiHAL : Exit wifi_event_loop
09-30 05:36:28.872  5114  5114 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 05:36:28.872   930  3013 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
09-30 05:36:28.872   930  3013 E WifiHAL : Event processing terminated
09-30 05:36:28.872   930  3013 D wifi    : In wifi cleaned up handler
09-30 05:36:28.872   930  3013 I WifiHAL : Internal cleanup completed
,09-30 05:36:28.873  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:28.874  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:28.875  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:28.876  4173  4275 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-30 05:36:28.877  4008  5960 I SystemUpdateService: showing system update notification
,09-30 05:36:28.889  4008  4008 D SystemUpdateService: onDestroy
,09-30 05:36:28.892   930  5924 D wifi    : set interface wlan0 flags (DOWN)
,09-30 05:36:28.892   930  3013 D WifiNative-HAL: HAL event thread stopped successfully
,09-30 05:36:29.097   930   947 D Tethering: InitialState.processMessage what=4
09-30 05:36:29.101   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-30 05:36:29.626   930  3015 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-30 05:36:31.275   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:32.277   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:33.278   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:33.717  5114  5946 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
,09-30 05:36:33.718  5114  5946 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 05:36:33.723  5114  5946 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-30 05:36:33.744   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@56f78ce:true
,09-30 05:36:33.745  5851  5851 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 05:36:33.748  5851  5851 I bt_bluedroid: init
,09-30 05:36:33.749  5851  5967 I BluetoothAdapterState: Entering OffState
,09-30 05:36:33.751  5851  5968 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-30 05:36:33.751  5851  5968 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 05:36:33.751  5851  5968 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 05:36:33.752  5851  5968 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-30 05:36:33.752  5851  5851 I bt_bluedroid: get_profile_interface socket
,09-30 05:36:33.754  5851  5971 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 05:36:33.754  5851  5851 I bt_bluedroid: get_profile_interface sdp
,09-30 05:36:33.757  5851  5971 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 05:36:33.761  5851  5862 I bt_bluedroid: config_hci_snoop_log
,09-30 05:36:33.762   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-30 05:36:33.767  5851  5967 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 05:36:33.767  5851  5967 D BluetoothAdapterProperties: Setting state to 14
09-30 05:36:33.767  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-30 05:36:33.769  5851  5967 D BluetoothBondStateMachine: make
,09-30 05:36:33.771  5851  5972 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 05:36:33.774  5851  5967 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:36:33.775  5851  5851 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 05:36:33.777  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:33.778  5851  5851 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 05:36:33.779  5851  5851 D BtGatt.GattService: Received start request. Starting profile...
,09-30 05:36:33.779  5851  5851 D BtGatt.GattService: start()
09-30 05:36:33.779  5851  5851 I bt_bluedroid: get_profile_interface gatt
,09-30 05:36:33.780  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:33.780  5851  5851 D BtGatt.AdvertiseManager: advertise manager created
,09-30 05:36:33.786  5851  5851 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:36:33.786  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:33.786  5851  5851 V BluetoothAdapterState: isBleTurningOn()=true
09-30 05:36:33.786  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:33.786  5851  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 05:36:33.787  5851  5967 I bt_bluedroid: bt_bluedroid
09-30 05:36:33.788  5851  5968 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 05:36:33.788  5851  5968 I bt_hci  : start_up
,09-30 05:36:33.794  5851  5968 I bt_vendor: alloc value 0xf3bf8871
,09-30 05:36:33.794  5851  5968 I bt_vendor: init
09-30 05:36:33.794  5851  5968 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 05:36:33.794  5851  5968 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 05:36:33.906  5851  5968 D bt_hci  : start_up starting async portion
,09-30 05:36:33.906  5851  5975 I bt_hci  : event_finish_startup
09-30 05:36:33.906  5851  5975 I bt_hci_h4: hal_open
09-30 05:36:33.907  5851  5975 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-30 05:36:33.910  5851  5975 I bt_userial_vendor: device fd = 54 open
,09-30 05:36:33.903  5976  5976 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 05:36:33.924  5851  5975 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 05:36:33.927  5851  5975 D bt_hwcfg: Chipset BCM4358A3
,09-30 05:36:33.927  5851  5975 D bt_hwcfg: Target name = [BCM4358A3]
09-30 05:36:33.927  5851  5975 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 05:36:34.279   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:34.325  5851  5975 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 05:36:34.325  5851  5975 D bt_hwcfg: Settlement delay -- 100 ms
09-30 05:36:34.326  5851  5975 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 05:36:34.459  5851  5975 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 05:36:34.460  5851  5975 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-30 05:36:34.461  5851  5975 I bt_hwcfg: vendor lib fwcfg completed
09-30 05:36:34.461  5851  5975 I bt_vendor: firmware callback
09-30 05:36:34.461  5851  5975 I bt_hci  : firmware_config_callback
,09-30 05:36:34.470  5851  5978 I bt_btu  : btu_task pending for preload complete event
09-30 05:36:34.471  5851  5978 I bt_btu_task: Bluetooth chip preload is complete
,09-30 05:36:34.471  5851  5978 I bt_btu  : btu_task received preload complete event
,09-30 05:36:34.478  5851  5978 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 05:36:34.479  5851  5978 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 05:36:34.479  5851  5978 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-30 05:36:34.479  5851  5978 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 05:36:34.479  5851  5978 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-30 05:36:34.479  5851  5978 I         : BTE_InitTraceLevels -- TRC_A2D
09-30 05:36:34.479  5851  5978 I         : BTE_InitTraceLevels -- TRC_BNEP
09-30 05:36:34.480  5851  5978 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 05:36:34.480  5851  5978 I         : BTE_InitTraceLevels -- TRC_GAP
,09-30 05:36:34.480  5851  5978 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 05:36:34.480  5851  5978 I         : BTE_InitTraceLevels -- TRC_SDP
09-30 05:36:34.480  5851  5978 I         : BTE_InitTraceLevels -- TRC_GATT
09-30 05:36:34.480  5851  5978 I         : BTE_InitTraceLevels -- TRC_SMP
,09-30 05:36:34.480  5851  5978 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 05:36:34.481  5851  5978 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 05:36:34.567  5851  5978 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3b76549
09-30 05:36:34.567  5851  5978 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3b76549 
,09-30 05:36:34.582  5851  5971 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 05:36:34.583  5851  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 05:36:34.584  5851  5971 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-30 05:36:34.586  5851  5971 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 05:36:34.590  5851  5971 D BluetoothAdapterProperties: Scan Mode:20
,09-30 05:36:34.590  5851  5971 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 05:36:34.591  5851  5971 D bt_hci  : do_postload posting postload work item
09-30 05:36:34.591  5851  5975 I bt_hci  : event_postload
,09-30 05:36:34.591  5851  5975 I bt_vendor: sco_config_cb
09-30 05:36:34.591  5851  5975 I bt_hci  : sco_config_callback postload finished.
,09-30 05:36:34.596  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:34.600  5851  5975 I bt_vendor: low_power_mode_cb
09-30 05:36:34.600  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:34.605  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:34.607  5851  5971 D bt_bte_conf: Device ID record 1 : primary
09-30 05:36:34.607  5851  5971 D bt_bte_conf:   vendorId            = 000f
09-30 05:36:34.607  5851  5971 D bt_bte_conf:   vendorIdSource      = 0001
09-30 05:36:34.607  5851  5971 D bt_bte_conf:   product             = 1200
09-30 05:36:34.607  5851  5971 D bt_bte_conf:   version             = 1436
,09-30 05:36:34.607  5851  5971 D bt_bte_conf:   clientExecutableURL = 
09-30 05:36:34.607  5851  5971 D bt_bte_conf:   serviceDescription  = 
09-30 05:36:34.607  5851  5971 D bt_bte_conf:   documentationURL    = 
09-30 05:36:34.607  5851  5971 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-30 05:36:34.608  5851  5968 D bt_stack_manager: event_start_up_stack finished
,09-30 05:36:34.608  5851  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 05:36:34.608  5851  5967 D BluetoothAdapterProperties: Setting state to 15
09-30 05:36:34.609  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 05:36:34.610  5851  5967 I BluetoothAdapterState: Entering BleOnState
,09-30 05:36:34.613  5851  5967 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-30 05:36:34.613  5851  5967 D BluetoothAdapterProperties: Setting state to 11
09-30 05:36:34.613  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 05:36:34.621  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:34.625  5851  5851 D HeadsetService: Received start request. Starting profile...
,09-30 05:36:34.626  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:34.627  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:34.628  5851  5851 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 05:36:34.629  5851  5851 D HeadsetStateMachine: make
09-30 05:36:34.631  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:34.638  5851  5967 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:36:34.640  5851  5851 D HeadsetStateMachine: max_hf_connections = 1
09-30 05:36:34.640  5851  5851 I bt_bluedroid: get_profile_interface handsfree
09-30 05:36:34.640  5851  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-30 05:36:34.640  5851  5971 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-30 05:36:34.644  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:34.644  5851  5851 D A2dpService: Received start request. Starting profile...
,09-30 05:36:34.645  5851  5851 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 05:36:34.646  5851  5851 I bt_bluedroid: get_profile_interface avrcp
,09-30 05:36:34.651  5851  5851 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 05:36:34.651  5851  5851 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 05:36:34.651  5851  5851 D A2dpStateMachine: make
09-30 05:36:34.652  5851  5851 I bt_bluedroid: get_profile_interface a2dp
,09-30 05:36:34.653  5851  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 05:36:34.655  5851  5986 D A2dpStateMachine: Enter Disconnected: -2
,09-30 05:36:34.655  5851  5851 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 05:36:34.656  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:34.657  5786  5786 D BluetoothInputDevice: Proxy object connected
,09-30 05:36:34.658  5851  5851 D HidService: Received start request. Starting profile...
09-30 05:36:34.658  5851  5851 I bt_bluedroid: get_profile_interface hidhost
09-30 05:36:34.658  5851  5971 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3b5756d
09-30 05:36:34.658  5851  5851 D HidService: setHidService(): set to: null
09-30 05:36:34.658  5851  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 05:36:34.658  5786  5786 D HidProfile: Bluetooth service connected
09-30 05:36:34.658  5851  5851 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 05:36:34.659  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:36:34.659  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:34.660  5851  5851 D HealthService: Received start request. Starting profile...
09-30 05:36:34.662  5851  5851 I bt_bluedroid: get_profile_interface health
,09-30 05:36:34.662  5851  5851 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-30 05:36:34.663  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:34.664  5786  5786 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 05:36:34.664  5851  5851 D PanService: Received start request. Starting profile...
09-30 05:36:34.665  5851  5851 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 05:36:34.665  5851  5851 I bt_bluedroid: get_profile_interface pan
09-30 05:36:34.665  5786  5786 D PanProfile: Bluetooth service connected
09-30 05:36:34.665  5851  5971 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-30 05:36:34.667  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:34.669  5851  5851 D BluetoothMapService: Received start request. Starting profile...
,09-30 05:36:34.669  5786  5786 D BluetoothMap: Proxy object connected
09-30 05:36:34.669  5851  5851 D BluetoothMapService: start()
09-30 05:36:34.669  5786  5786 D MapProfile: Bluetooth service connected
09-30 05:36:34.669  5786  5786 D BluetoothMap: getConnectedDevices()
09-30 05:36:34.670  5786  5786 D BluetoothMap: Bluetooth is Not enabled
09-30 05:36:34.672  5851  5851 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-30 05:36:34.673  5851  5851 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-30 05:36:34.673  5851  5851 D BluetoothMapAppObserver: createReceiver()
,09-30 05:36:34.675  5851  5851 D BluetoothMapAppObserver: initObservers()
09-30 05:36:34.675  5851  5851 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 05:36:34.683  5851  5851 V SapService: SapBinder()
,09-30 05:36:34.683  5851  5851 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:34.683  5851  5851 D SapService: Received start request. Starting profile...
09-30 05:36:34.683  5851  5851 V SapService: start()
,09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:34.686  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:34.687  5851  5984 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:34.687  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:34.688  5851  5851 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:34.688  5851  5851 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:34.688  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:34.688  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:34.689  5851  5851 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:34.689  5851  5851 V BluetoothAdapterState: isTurningOn()=true
,09-30 05:36:34.689  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:34.689  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:34.689  5851  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 05:36:34.689  5851  5967 D BluetoothAdapterProperties: ScanMode =  20
09-30 05:36:34.689  5851  5967 D BluetoothAdapterProperties: State =  11
09-30 05:36:34.690  5851  5967 D BluetoothAdapterProperties: Setting state to 12
09-30 05:36:34.690  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-30 05:36:34.691  5786  5798 D BluetoothPbap: onBluetoothStateChange: up=true
,09-30 05:36:34.692  5851  5971 D BluetoothAdapterProperties: Scan Mode:21
09-30 05:36:34.692  5851  5971 D BluetoothAdapterProperties: Discoverable Timeout:120
09-30 05:36:34.693  5733  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:36:34.693  5851  5967 I BluetoothAdapterState: Entering OnState
09-30 05:36:34.693   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:34.693   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:36:34.694  3182  3934 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 05:36:34.694   930   930 D BluetoothA2dp: Proxy object connected
,09-30 05:36:34.696   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:34.696  3182  3182 D BluetoothInputDevice: Proxy object connected
09-30 05:36:34.696  3182  3182 D HidProfile: Bluetooth service connected
09-30 05:36:34.696  3182  5932 D BluetoothMap: onBluetoothStateChange: up=true
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:34.697  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:34.698  3182  3934 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:36:34.699  3182  3182 D BluetoothMap: Proxy object connected
09-30 05:36:34.699  3182  3182 D MapProfile: Bluetooth service connected
09-30 05:36:34.699  3182  3182 D BluetoothMap: getConnectedDevices()
09-30 05:36:34.700  3182  3194 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 05:36:34.701  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:34.701  3182  3182 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 05:36:34.701  3182  3182 D PanProfile: Bluetooth service connected
09-30 05:36:34.701  5786  5803 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-30 05:36:34.701  3815  4094 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:34.702  3182  3199 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-30 05:36:34.702  5851  5851 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 05:36:34.703  5851  5851 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-30 05:36:34.706  3182  3182 D BluetoothA2dp: Proxy object connected
09-30 05:36:34.706   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:34.706  5786  5798 D BluetoothMap: onBluetoothStateChange: up=true
,09-30 05:36:34.707  5851  5851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:34.707  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:34.708  5851  5851 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:36:34.708  3182  3194 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 05:36:34.709  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:34.709  5786  5803 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:36:34.709  5851  5851 D ObexServerSockets: Succeed to create listening sockets 
09-30 05:36:34.710  5851  5851 D ObexServerSockets0: startAccept()
09-30 05:36:34.710  5851  5851 D ObexServerSockets0: prepareForNewConnect()
09-30 05:36:34.710   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:34.713  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:34.713  5851  5851 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 05:36:34.713  5851  5851 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 05:36:34.713  5851  5993 D ObexServerSockets0: Accepting socket connection...
09-30 05:36:34.714  5786  5786 D LocalBluetoothProfileManager: Adding local A2DP profile
09-30 05:36:34.714  5851  5851 D BluetoothMapService: onReceive
09-30 05:36:34.714  5851  5851 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-30 05:36:34.714  5851  5851 D BluetoothMapService: STATE_ON
09-30 05:36:34.714  5851  5994 D ObexServerSockets0: Accepting socket connection...
09-30 05:36:34.717  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:34.717  5733  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:36:34.718  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:34.718  5851  5995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:36:34.719  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:34.720  5851  5995 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 05:36:34.720  5851  5995 D BluetoothSdpJni: SDP Create record success - handle: 1
09-30 05:36:34.721  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:34.721  5786  5786 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-30 05:36:34.727  5786  5786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:36:34.729  5786  5786 D BluetoothA2dp: Proxy object connected
,09-30 05:36:34.733  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:36:34.735  5786  5786 D DockEventReceiver: finishStartingService: stopping service
,09-30 05:36:34.739  5786  5786 D BluetoothPbap: Proxy object connected
,09-30 05:36:34.740  5786  5786 D PbapServerProfile: Bluetooth service connected
09-30 05:36:34.740  5851  5851 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 05:36:34.741  5851  5851 D ObexServerSockets0: prepareForNewConnect()
,09-30 05:36:34.747  3182  3182 D BluetoothPbap: Proxy object connected
,09-30 05:36:34.747  3182  3182 D PbapServerProfile: Bluetooth service connected
09-30 05:36:34.748  5851  5999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:36:34.764  5851  6003 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:36:34.766  5851  6003 I BtOppRfcommListener: Accept thread started.
,09-30 05:36:34.794   930   930 D BluetoothHeadset: Proxy object connected
,09-30 05:36:34.794   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:36:34.795  3182  5932 D BluetoothHeadset: Proxy object connected
09-30 05:36:34.795  3182  3182 D HeadsetProfile: Bluetooth service connected
09-30 05:36:34.795  3815  3829 D BluetoothHeadset: Proxy object connected
09-30 05:36:34.795   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:36:34.796   930   947 D BluetoothHeadset: Proxy object connected
,09-30 05:36:34.802  3815  4284 D BluetoothHeadset: Proxy object connected
,09-30 05:36:34.806   930   947 D BluetoothHeadset: Proxy object connected
,09-30 05:36:34.810  3182  3934 D BluetoothHeadset: Proxy object connected
09-30 05:36:34.810  3182  3182 D HeadsetProfile: Bluetooth service connected
,09-30 05:36:34.823  5786  5798 D BluetoothHeadset: Proxy object connected
,09-30 05:36:34.825  5786  5786 D HeadsetProfile: Bluetooth service connected
,09-30 05:36:35.280   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:36.281   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 05:36:36.581   930  3015 D ConnectivityService: handlePromptUnvalidated 101
,09-30 05:36:38.733  5851  5967 D BluetoothAdapterState: Current state: ON, message: 23
,09-30 05:36:38.733  5851  5967 D BluetoothAdapterProperties: Setting state to 13
09-30 05:36:38.734  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-30 05:36:38.735  5851  5967 D BluetoothAdapterProperties: onBluetoothDisable()
09-30 05:36:38.736  5851  5967 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:36:38.741  5851  5851 D BluetoothMapService: onReceive
,09-30 05:36:38.741  5851  5851 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 05:36:38.741  5851  5851 D BluetoothMapService: STATE_TURNING_OFF
09-30 05:36:38.742  5851  5851 D BluetoothMapService: MAP Service closeService in
09-30 05:36:38.742  5851  5851 D BluetoothMapMasInstance0: MAP Service shutdown
09-30 05:36:38.742  5851  5851 D ObexServerSockets0: shutdown(block = true)
09-30 05:36:38.742  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:38.742  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:36:38.743  5851  5851 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 05:36:38.743  5851  5993 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-30 05:36:38.743  5851  5851 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-30 05:36:38.744  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:38.744  5851  5980 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-30 05:36:38.744  5851  5994 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-30 05:36:38.744  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-30 05:36:38.745  5851  5971 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:36:38.746  5851  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-30 05:36:38.747  5851  5851 I BtOppRfcommListener: stopping Accept Thread
,09-30 05:36:38.747  5851  6003 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-30 05:36:38.747  5851  6003 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-30 05:36:38.748  5786  5786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-30 05:36:38.752  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:38.752  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:38.753  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:36:38.753  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:38.755  5851  5851 D HeadsetService: Received stop request...Stopping profile...
,09-30 05:36:38.757  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:38.757  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:38.758  5733  5733 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-30 05:36:38.759  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:38.762  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:38.764  5786  5803 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:38.764   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:38.764   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:38.765  3182  3199 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:38.765  3815  3834 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:38.765  3182  3182 D HeadsetProfile: Bluetooth service disconnected
09-30 05:36:38.765   930   930 D BluetoothHeadset: Proxy object disconnected
09-30 05:36:38.769  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:38.771  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:38.771  5786  5786 D DockEventReceiver: finishStartingService: stopping service
09-30 05:36:38.772  5851  5851 D A2dpService: Received stop request...Stopping profile...
09-30 05:36:38.773  5851  5986 D A2dpStateMachine: Exit Disconnected: -1
09-30 05:36:38.774   930   930 D BluetoothA2dp: Proxy object disconnected
09-30 05:36:38.774  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:36:38.774  5786  5786 D HeadsetProfile: Bluetooth service disconnected
09-30 05:36:38.774  5786  5786 D BluetoothA2dp: Proxy object disconnected
09-30 05:36:38.775  5851  5851 D HidService: Received stop request...Stopping profile...
09-30 05:36:38.775  5851  5851 D HidService: Stopping Bluetooth HidService
09-30 05:36:38.776  3182  3182 D BluetoothA2dp: Proxy object disconnected
09-30 05:36:38.777  3182  3182 D BluetoothInputDevice: Proxy object disconnected
09-30 05:36:38.777  5786  5786 D BluetoothInputDevice: Proxy object disconnected
09-30 05:36:38.777  3182  3182 D HidProfile: Bluetooth service disconnected
09-30 05:36:38.777  5786  5786 D HidProfile: Bluetooth service disconnected
09-30 05:36:38.778  5851  5851 D HealthService: Received stop request...Stopping profile...
,09-30 05:36:38.782  5851  5851 V BluetoothAdapterState: isTurningOff()=true
,09-30 05:36:38.782  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:38.782  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:38.782  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:38.783  5851  5851 D PanService: Received stop request...Stopping profile...
09-30 05:36:38.784  3182  3182 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 05:36:38.784  3182  3182 D PanProfile: Bluetooth service disconnected
09-30 05:36:38.784  5786  5786 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-30 05:36:38.784  5786  5786 D PanProfile: Bluetooth service disconnected
09-30 05:36:38.785  5851  5851 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-30 05:36:38.785  5851  5851 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-30 05:36:38.785  5851  5978 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:38.785  5851  5978 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:38.785  5851  5978 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:38.786  5851  5851 D BluetoothMapService: Received stop request...Stopping profile...
09-30 05:36:38.786  5851  5851 D BluetoothMapService: stop()
09-30 05:36:38.785  5851  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-30 05:36:38.786  5851  5971 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-30 05:36:38.786  5851  5851 D BluetoothMapAppObserver: deinitObservers()
09-30 05:36:38.786  5851  5851 D BluetoothMapAppObserver: removeReceiver()
09-30 05:36:38.787  3182  3182 D BluetoothMap: Proxy object disconnected
,09-30 05:36:38.789  3182  3182 D MapProfile: Bluetooth service disconnected
09-30 05:36:38.788  5851  5851 D SapService: Received stop request...Stopping profile...
09-30 05:36:38.789  5851  5851 V SapService: stop()
09-30 05:36:38.788  5786  5786 D BluetoothMap: Proxy object disconnected
09-30 05:36:38.789  5786  5786 D MapProfile: Bluetooth service disconnected
,09-30 05:36:38.792  3182  3182 D BluetoothPbap: Proxy object disconnected
09-30 05:36:38.792  3182  3182 D PbapServerProfile: Bluetooth service disconnected
09-30 05:36:38.792  5851  5851 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:38.792  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:38.792  5786  5786 D BluetoothPbap: Proxy object disconnected
09-30 05:36:38.792  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:38.792  5786  5786 D PbapServerProfile: Bluetooth service disconnected
09-30 05:36:38.792  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:38.793  5851  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-30 05:36:38.793  5851  5978 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:38.794  5851  5851 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:38.794  5851  5978 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:38.794  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:38.794  5851  5978 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:36:38.794  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:38.794  5851  5978 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-30 05:36:38.794  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:38.794  5851  5978 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-30 05:36:38.794  5851  5978 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-30 05:36:38.794  5851  5851 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-30 05:36:38.794  5851  5851 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-30 05:36:38.794  5851  5971 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-30 05:36:38.794  5851  5851 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:38.795  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:38.795  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:38.795  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:38.795  5851  5851 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-30 05:36:38.795  5851  5851 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-30 05:36:38.795  5851  5851 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:38.795  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:38.795  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:38.796  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:36:38.796  5851  5971 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-30 05:36:38.796  5851  5851 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-30 05:36:38.796  5851  5851 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-30 05:36:38.797  5851  5851 D BluetoothMapService: MAP Service closeService in
09-30 05:36:38.797  5851  5851 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:38.797  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:38.797  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:38.797  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:38.797  5851  5851 D BluetoothMapService: cleanup()
09-30 05:36:38.797  5851  5851 D BluetoothMapService: MAP Service closeService in
09-30 05:36:38.797  5851  5851 V BluetoothAdapterState: isTurningOff()=true
09-30 05:36:38.797  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:38.798  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:38.798  5851  5851 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:38.798  5851  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-30 05:36:38.798  5851  5967 D BluetoothAdapterProperties: Setting state to 15
09-30 05:36:38.798  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-30 05:36:38.799  5851  5967 I BluetoothAdapterState: Entering BleOnState
,09-30 05:36:38.803  5786  5798 D BluetoothPbap: onBluetoothStateChange: up=false
,09-30 05:36:38.804  5786  5803 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:38.804   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:38.804   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:36:38.804  3182  3199 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 05:36:38.806   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:38.807  3182  3934 D BluetoothMap: onBluetoothStateChange: up=false
09-30 05:36:38.807  3182  3194 D BluetoothPan: onBluetoothStateChange on: false
09-30 05:36:38.807  3182  5932 D BluetoothPbap: onBluetoothStateChange: up=false
09-30 05:36:38.808  5786  5798 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-30 05:36:38.809  3815  4094 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-30 05:36:38.809  3182  3199 D BluetoothA2dp: onBluetoothStateChange: up=false
09-30 05:36:38.809   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:38.809  5786  5803 D BluetoothMap: onBluetoothStateChange: up=false
09-30 05:36:38.810  3182  3934 D BluetoothHeadset: onBluetoothStateChange: up=false
09-30 05:36:38.810  5786  5798 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-30 05:36:38.811  5786  5803 D BluetoothPan: onBluetoothStateChange on: false
09-30 05:36:38.812  5851  5967 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-30 05:36:38.812  5851  5967 D BluetoothAdapterProperties: Setting state to 16
09-30 05:36:38.812  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-30 05:36:38.812  5851  5967 D BluetoothAdapterProperties: onBleDisable
09-30 05:36:38.813  5851  5967 I BluetoothAdapterState: Entering PendingCommandState
09-30 05:36:38.813  5851  5968 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-30 05:36:38.814  5851  5971 D BluetoothAdapterProperties: Scan Mode:20
09-30 05:36:38.814  5851  5978 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-30 05:36:38.814  5851  5978 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-30 05:36:38.816  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:38.817  5786  5786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:36:38.817  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:38.819  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:38.822  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:38.823  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:38.824  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:38.827  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:36:38.829  5786  5786 D DockEventReceiver: finishStartingService: stopping service
,09-30 05:36:39.032  5851  5971 I bt_hci  : shut_down
,09-30 05:36:39.042  5851  5975 D bt_hwcfg: hw_epilog_process
,09-30 05:36:39.043  5851  5975 I bt_vendor: low_power_mode_cb
,09-30 05:36:39.046  5851  5975 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-30 05:36:39.046  5851  5975 I bt_vendor: epilog_cb
,09-30 05:36:39.046  5851  5975 I bt_hci  : epilog_finished_callback
,09-30 05:36:39.051  5851  5971 I bt_hci_h4: hal_close
09-30 05:36:39.052  5851  5971 I bt_userial_vendor: device fd = 54 close
,09-30 05:36:39.172  5851  5968 D bt_stack_manager: event_shut_down_stack finished.
09-30 05:36:39.172  5851  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-30 05:36:39.177  5851  5967 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-30 05:36:39.177  5851  5851 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-30 05:36:39.178  5851  5851 D BtGatt.GattService: Received stop request...Stopping profile...
,09-30 05:36:39.179  5851  5851 D BtGatt.GattService: stop()
09-30 05:36:39.179  5851  5851 D BtGatt.AdvertiseManager: advertise clients cleared
09-30 05:36:39.183  5851  5851 V BluetoothAdapterState: isTurningOff()=false
,09-30 05:36:39.183  5851  5851 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:39.183  5851  5851 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:39.183  5851  5851 V BluetoothAdapterState: isBleTurningOff()=true
09-30 05:36:39.184  5851  5967 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-30 05:36:39.184  5851  5967 D BluetoothAdapterProperties: Setting state to 10
09-30 05:36:39.185  5851  5967 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-30 05:36:39.186  5851  5967 I BluetoothAdapterState: Entering OffState
09-30 05:36:39.187   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-30 05:36:39.203  5851  5851 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-30 05:36:39.203  5851  5851 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-30 05:36:39.203  5851  5851 I BluetoothServiceJni: cleanupNative: return from cleanup
09-30 05:36:39.206  5851  5968 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-30 05:36:39.213  5851  5851 I art     : System.exit called, status: 0
,09-30 05:36:39.214  5851  5851 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-30 05:36:39.246   930  3898 I ActivityManager: Process com.android.bluetooth (pid 5851) has died
,09-30 05:36:43.728  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
,09-30 05:36:43.728  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:43.734  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:43.734  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8208d7a removed from the list
09-30 05:36:43.734  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:43.735  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:43.735  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:43.739  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:36:43.739  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9858188 added. We now have 4 listener(s)
09-30 05:36:43.740  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:36:43.741  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:36:43.741  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9858188 removed from the list
09-30 05:36:43.741  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:43.741  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:36:43.742  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:36:43.743  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:36:43.744  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27fc721 added. We now have 4 listener(s)
09-30 05:36:43.744  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:36:48.754  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:48.788   930   947 I ActivityManager: Start proc 6011:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-30 05:36:48.878  6011  6011 D AdapterServiceConfig: Adding HeadsetService
,09-30 05:36:48.878  6011  6011 D AdapterServiceConfig: Adding A2dpService
09-30 05:36:48.879  6011  6011 D AdapterServiceConfig: Adding HidService
09-30 05:36:48.879  6011  6011 D AdapterServiceConfig: Adding HealthService
09-30 05:36:48.879  6011  6011 D AdapterServiceConfig: Adding PanService
09-30 05:36:48.879  6011  6011 D AdapterServiceConfig: Adding GattService
09-30 05:36:48.880  6011  6011 D AdapterServiceConfig: Adding BluetoothMapService
09-30 05:36:48.880  6011  6011 D AdapterServiceConfig: Adding SapService
,09-30 05:36:48.893   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37797bc:true
,09-30 05:36:48.894  6011  6011 D BluetoothAdapterState: make() - Creating AdapterState
,09-30 05:36:48.897  6011  6011 I bt_bluedroid: init
,09-30 05:36:48.899  6011  6023 I BluetoothAdapterState: Entering OffState
,09-30 05:36:48.902  6011  6024 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-30 05:36:48.902  6011  6024 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-30 05:36:48.902  6011  6024 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-30 05:36:48.902  6011  6024 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-30 05:36:48.903  6011  6011 I bt_bluedroid: get_profile_interface socket
,09-30 05:36:48.905  6011  6011 I bt_bluedroid: get_profile_interface sdp
,09-30 05:36:48.905  6011  6027 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 05:36:48.907  6011  6027 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 05:36:48.910  6011  6022 I bt_bluedroid: config_hci_snoop_log
,09-30 05:36:48.911   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-30 05:36:48.926  6011  6023 D BluetoothAdapterState: Current state: OFF, message: 0
,09-30 05:36:48.926  6011  6023 D BluetoothAdapterProperties: Setting state to 14
09-30 05:36:48.926  6011  6023 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-30 05:36:48.928  6011  6023 D BluetoothBondStateMachine: make
,09-30 05:36:48.930  6011  6028 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-30 05:36:48.933  6011  6023 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:36:48.935  6011  6011 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-30 05:36:48.937  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:48.938  6011  6011 D BtGatt.DebugUtils: handleDebugAction() action=null
09-30 05:36:48.938  6011  6011 D BtGatt.GattService: Received start request. Starting profile...
09-30 05:36:48.938  6011  6011 D BtGatt.GattService: start()
09-30 05:36:48.938  6011  6011 I bt_bluedroid: get_profile_interface gatt
09-30 05:36:48.941  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:48.941  6011  6011 D BtGatt.AdvertiseManager: advertise manager created
,09-30 05:36:48.946  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:48.947  6011  6011 V BluetoothAdapterState: isTurningOn()=false
09-30 05:36:48.947  6011  6011 V BluetoothAdapterState: isBleTurningOn()=true
,09-30 05:36:48.947  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:48.947  6011  6023 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-30 05:36:48.948  6011  6023 I bt_bluedroid: bt_bluedroid
09-30 05:36:48.948  6011  6024 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-30 05:36:48.948  6011  6024 I bt_hci  : start_up
,09-30 05:36:48.955  6011  6024 I bt_vendor: alloc value 0xf3c69871
09-30 05:36:48.955  6011  6024 I bt_vendor: init
,09-30 05:36:48.955  6011  6024 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-30 05:36:48.955  6011  6024 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-30 05:36:49.063  6011  6024 D bt_hci  : start_up starting async portion
,09-30 05:36:49.063  6011  6031 I bt_hci  : event_finish_startup
09-30 05:36:49.063  6011  6031 I bt_hci_h4: hal_open
09-30 05:36:49.064  6011  6031 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-30 05:36:49.059  6032  6032 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-30 05:36:49.067  6011  6031 I bt_userial_vendor: device fd = 54 open
,09-30 05:36:49.081  6011  6031 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-30 05:36:49.084  6011  6031 D bt_hwcfg: Chipset BCM4358A3
,09-30 05:36:49.084  6011  6031 D bt_hwcfg: Target name = [BCM4358A3]
09-30 05:36:49.084  6011  6031 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-30 05:36:49.605  6011  6031 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-30 05:36:49.605  6011  6031 D bt_hwcfg: Settlement delay -- 100 ms
09-30 05:36:49.606  6011  6031 I bt_hwcfg: Setting fw settlement delay to 100 
,09-30 05:36:49.739  6011  6031 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-30 05:36:49.740  6011  6031 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-30 05:36:49.742  6011  6031 I bt_hwcfg: vendor lib fwcfg completed
09-30 05:36:49.742  6011  6031 I bt_vendor: firmware callback
09-30 05:36:49.742  6011  6031 I bt_hci  : firmware_config_callback
,09-30 05:36:49.754  6011  6034 I bt_btu  : btu_task pending for preload complete event
,09-30 05:36:49.754  6011  6034 I bt_btu_task: Bluetooth chip preload is complete
09-30 05:36:49.754  6011  6034 I bt_btu  : btu_task received preload complete event
,09-30 05:36:49.762  6011  6034 I         : BTE_InitTraceLevels -- TRC_HCI
,09-30 05:36:49.763  6011  6034 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-30 05:36:49.763  6011  6034 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-30 05:36:49.763  6011  6034 I         : BTE_InitTraceLevels -- TRC_AVDT
09-30 05:36:49.763  6011  6034 I         : BTE_InitTraceLevels -- TRC_AVRC
09-30 05:36:49.763  6011  6034 I         : BTE_InitTraceLevels -- TRC_A2D
,09-30 05:36:49.764  6011  6034 I         : BTE_InitTraceLevels -- TRC_BNEP
09-30 05:36:49.764  6011  6034 I         : BTE_InitTraceLevels -- TRC_BTM
09-30 05:36:49.764  6011  6034 I         : BTE_InitTraceLevels -- TRC_GAP
09-30 05:36:49.764  6011  6034 I         : BTE_InitTraceLevels -- TRC_PAN
09-30 05:36:49.764  6011  6034 I         : BTE_InitTraceLevels -- TRC_SDP
,09-30 05:36:49.764  6011  6034 I         : BTE_InitTraceLevels -- TRC_GATT
,09-30 05:36:49.764  6011  6034 I         : BTE_InitTraceLevels -- TRC_SMP
09-30 05:36:49.765  6011  6034 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-30 05:36:49.765  6011  6034 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-30 05:36:49.863  6011  6034 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3be7549
,09-30 05:36:49.863  6011  6034 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3be7549 
,09-30 05:36:49.878  6011  6027 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-30 05:36:49.881  6011  6027 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-30 05:36:49.881  6011  6027 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-30 05:36:49.884  6011  6027 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-30 05:36:49.888  6011  6027 D BluetoothAdapterProperties: Scan Mode:20
,09-30 05:36:49.888  6011  6027 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 05:36:49.888  6011  6027 D bt_hci  : do_postload posting postload work item
09-30 05:36:49.889  6011  6031 I bt_hci  : event_postload
09-30 05:36:49.889  6011  6031 I bt_vendor: sco_config_cb
09-30 05:36:49.889  6011  6031 I bt_hci  : sco_config_callback postload finished.
,09-30 05:36:49.894  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:49.898  6011  6027 D bt_bte_conf: Device ID record 1 : primary
,09-30 05:36:49.898  6011  6027 D bt_bte_conf:   vendorId            = 000f
09-30 05:36:49.898  6011  6027 D bt_bte_conf:   vendorIdSource      = 0001
,09-30 05:36:49.898  6011  6031 I bt_vendor: low_power_mode_cb
09-30 05:36:49.898  6011  6027 D bt_bte_conf:   product             = 1200
09-30 05:36:49.898  6011  6027 D bt_bte_conf:   version             = 1436
09-30 05:36:49.898  6011  6027 D bt_bte_conf:   clientExecutableURL = 
,09-30 05:36:49.898  6011  6027 D bt_bte_conf:   serviceDescription  = 
09-30 05:36:49.898  6011  6027 D bt_bte_conf:   documentationURL    = 
,09-30 05:36:49.898  6011  6027 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-30 05:36:49.899  6011  6024 D bt_stack_manager: event_start_up_stack finished
09-30 05:36:49.900  6011  6023 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-30 05:36:49.901  6011  6023 D BluetoothAdapterProperties: Setting state to 15
09-30 05:36:49.901  6011  6023 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-30 05:36:49.901  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:49.902  6011  6023 I BluetoothAdapterState: Entering BleOnState
,09-30 05:36:49.909  6011  6023 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-30 05:36:49.909  6011  6023 D BluetoothAdapterProperties: Setting state to 11
09-30 05:36:49.909  6011  6023 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-30 05:36:49.916  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:49.917  6011  6011 D HeadsetService: Received start request. Starting profile...
09-30 05:36:49.921  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:49.924  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:49.925  6011  6011 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-30 05:36:49.926  6011  6011 D HeadsetStateMachine: make
,09-30 05:36:49.932  6011  6023 I BluetoothAdapterState: Entering PendingCommandState
,09-30 05:36:49.942  6011  6011 D HeadsetStateMachine: max_hf_connections = 1
09-30 05:36:49.942  6011  6011 I bt_bluedroid: get_profile_interface handsfree
09-30 05:36:49.943  6011  6027 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-30 05:36:49.945  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:49.946  6011  6027 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,09-30 05:36:49.946  6011  6011 D A2dpService: Received start request. Starting profile...
,09-30 05:36:49.947  6011  6011 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-30 05:36:49.947  6011  6011 I bt_bluedroid: get_profile_interface avrcp
,09-30 05:36:49.953  6011  6011 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-30 05:36:49.954  6011  6011 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-30 05:36:49.954  6011  6011 D A2dpStateMachine: make
,09-30 05:36:49.955  6011  6011 I bt_bluedroid: get_profile_interface a2dp
09-30 05:36:49.956  6011  6027 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-30 05:36:49.957  6011  6044 D A2dpStateMachine: Enter Disconnected: -2
,09-30 05:36:49.959  6011  6011 I BluetoothHidServiceJni: classInitNative: succeeds
09-30 05:36:49.960  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:49.960  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-30 05:36:49.960  6011  6011 D HidService: Received start request. Starting profile...
09-30 05:36:49.960  6011  6011 I bt_bluedroid: get_profile_interface hidhost
09-30 05:36:49.961  6011  6011 D HidService: setHidService(): set to: null
,09-30 05:36:49.961  6011  6011 I BluetoothHealthServiceJni: classInitNative: succeeds
09-30 05:36:49.962  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:49.962  6011  6027 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3bc856d
09-30 05:36:49.962  6011  6027 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-30 05:36:49.963  6011  6011 D HealthService: Received start request. Starting profile...
,09-30 05:36:49.964  6011  6011 I bt_bluedroid: get_profile_interface health
09-30 05:36:49.965  6011  6011 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-30 05:36:49.965  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:36:49.966  6011  6011 D PanService: Received start request. Starting profile...
09-30 05:36:49.966  6011  6011 D BluetoothPanServiceJni: initializeNative(L110): pan
09-30 05:36:49.966  6011  6011 I bt_bluedroid: get_profile_interface pan
09-30 05:36:49.967  6011  6027 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-30 05:36:49.969  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:49.970  6011  6011 D BluetoothMapService: Received start request. Starting profile...
09-30 05:36:49.970  6011  6011 D BluetoothMapService: start()
,09-30 05:36:49.973  6011  6011 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-30 05:36:49.974  6011  6011 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-30 05:36:49.974  6011  6011 D BluetoothMapAppObserver: createReceiver()
09-30 05:36:49.975  6011  6011 D BluetoothMapAppObserver: initObservers()
09-30 05:36:49.975  6011  6011 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-30 05:36:49.982  6011  6011 V SapService: SapBinder()
09-30 05:36:49.982  6011  6011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
09-30 05:36:49.982  6011  6011 D SapService: Received start request. Starting profile...
09-30 05:36:49.982  6011  6011 V SapService: start()
,09-30 05:36:49.986  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:49.986  6011  6011 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:49.986  6011  6011 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:49.986  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:49.987  6011  6042 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:49.987  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
,09-30 05:36:49.988  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:49.988  6011  6011 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:49.988  6011  6011 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:49.988  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isBleTurningOn()=false
,09-30 05:36:49.989  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:49.990  6011  6011 V BluetoothAdapterState: isTurningOff()=false
09-30 05:36:49.990  6011  6011 V BluetoothAdapterState: isTurningOn()=true
09-30 05:36:49.990  6011  6011 V BluetoothAdapterState: isBleTurningOn()=false
09-30 05:36:49.990  6011  6011 V BluetoothAdapterState: isBleTurningOff()=false
09-30 05:36:49.991  6011  6023 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-30 05:36:49.991  6011  6023 D BluetoothAdapterProperties: ScanMode =  20
,09-30 05:36:49.991  6011  6023 D BluetoothAdapterProperties: State =  11
,09-30 05:36:49.992  6011  6027 D BluetoothAdapterProperties: Scan Mode:21
09-30 05:36:49.992  6011  6023 D BluetoothAdapterProperties: Setting state to 12
09-30 05:36:49.992  6011  6023 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-30 05:36:49.992  6011  6027 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-30 05:36:49.993  5733  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:36:49.993  5786  5803 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 05:36:49.993  6011  6023 I BluetoothAdapterState: Entering OnState
09-30 05:36:49.995  5786  5798 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:49.995   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:49.995   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:49.996  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:49.996  3182  3194 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 05:36:49.997   930   930 D BluetoothA2dp: Proxy object connected
09-30 05:36:49.998   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:49.998  3182  5932 D BluetoothMap: onBluetoothStateChange: up=true
09-30 05:36:49.999  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:49.999  3182  3182 D BluetoothInputDevice: Proxy object connected
09-30 05:36:49.999  3182  3182 D HidProfile: Bluetooth service connected
09-30 05:36:50.000  3182  3934 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:36:50.001  6011  6011 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 05:36:50.002  6011  6011 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-30 05:36:50.003  6011  6011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:36:50.004  3182  3194 D BluetoothPbap: onBluetoothStateChange: up=true
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:50.004  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-30 05:36:50.005  5786  5803 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-30 05:36:50.006  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:50.008  6011  6011 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:36:50.008  3815  3834 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:50.009  3182  3199 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:36:50.009  6011  6011 D ObexServerSockets: Succeed to create listening sockets 
09-30 05:36:50.009  6011  6011 D ObexServerSockets0: startAccept()
09-30 05:36:50.009  6011  6011 D ObexServerSockets0: prepareForNewConnect()
09-30 05:36:50.010  5786  5786 D BluetoothInputDevice: Proxy object connected
09-30 05:36:50.010  5786  5786 D HidProfile: Bluetooth service connected
09-30 05:36:50.011  3182  3182 D BluetoothA2dp: Proxy object connected
,09-30 05:36:50.011   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
09-30 05:36:50.011  5786  5798 D BluetoothMap: onBluetoothStateChange: up=true
,09-30 05:36:50.013  3182  5932 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-30 05:36:50.014  5786  5803 D BluetoothA2dp: onBluetoothStateChange: up=true
09-30 05:36:50.014  6011  6011 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-30 05:36:50.014  6011  6011 D BluetoothSdpJni: SDP Create record success - handle: 0
09-30 05:36:50.015  6011  6050 D ObexServerSockets0: Accepting socket connection...
09-30 05:36:50.015  6011  6051 D ObexServerSockets0: Accepting socket connection...
09-30 05:36:50.016  5786  5798 D BluetoothPan: onBluetoothStateChange on: true
09-30 05:36:50.017  3182  3182 D BluetoothMap: Proxy object connected
09-30 05:36:50.017  3182  3182 D MapProfile: Bluetooth service connected
09-30 05:36:50.017  3182  3182 D BluetoothMap: getConnectedDevices()
09-30 05:36:50.019  5786  5786 D BluetoothA2dp: Proxy object connected
09-30 05:36:50.019  3182  3182 D BluetoothPan: BluetoothPAN Proxy object connected
09-30 05:36:50.019  3182  3182 D PanProfile: Bluetooth service connected
09-30 05:36:50.019   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
,09-30 05:36:50.020  5733  5733 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
09-30 05:36:50.020  6011  6011 D BluetoothMapService: onReceive
09-30 05:36:50.021  6011  6011 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-30 05:36:50.021  6011  6011 D BluetoothMapService: STATE_ON
09-30 05:36:50.022  5786  5786 D BluetoothMap: Proxy object connected
09-30 05:36:50.022  5786  5786 D MapProfile: Bluetooth service connected
09-30 05:36:50.022  5786  5786 D BluetoothMap: getConnectedDevices()
09-30 05:36:50.023  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:50.024  5786  5786 D BluetoothPan: BluetoothPAN Proxy object connected
,09-30 05:36:50.025  5786  5786 D PanProfile: Bluetooth service connected
,09-30 05:36:50.026  6011  6052 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-30 05:36:50.026  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:36:50.027  6011  6052 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-30 05:36:50.027  6011  6052 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-30 05:36:50.031  5786  5786 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-30 05:36:50.036  5786  5786 D DockEventReceiver: finishStartingService: stopping service
,09-30 05:36:50.037  3625  3625 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-30 05:36:50.044  5786  5786 D BluetoothPbap: Proxy object connected
,09-30 05:36:50.044  5786  5786 D PbapServerProfile: Bluetooth service connected
09-30 05:36:50.044  6011  6011 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-30 05:36:50.044  6011  6011 D ObexServerSockets0: prepareForNewConnect()
,09-30 05:36:50.049  3182  3182 D BluetoothPbap: Proxy object connected
09-30 05:36:50.049  3182  3182 D PbapServerProfile: Bluetooth service connected
,09-30 05:36:50.055  6011  6057 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:36:50.067  6011  6061 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-30 05:36:50.068  6011  6061 I BtOppRfcommListener: Accept thread started.
,09-30 05:36:50.097  5786  6049 D BluetoothHeadset: Proxy object connected
09-30 05:36:50.097   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:36:50.097   930   930 D BluetoothHeadset: Proxy object connected
,09-30 05:36:50.097  3182  5932 D BluetoothHeadset: Proxy object connected
09-30 05:36:50.098  3182  3182 D HeadsetProfile: Bluetooth service connected
09-30 05:36:50.098  3815  4094 D BluetoothHeadset: Proxy object connected
09-30 05:36:50.098   930   930 D BluetoothHeadset: Proxy object connected
09-30 05:36:50.098   930   947 D BluetoothHeadset: Proxy object connected
09-30 05:36:50.100  5786  5786 D HeadsetProfile: Bluetooth service connected
,09-30 05:36:50.109  3815  3829 D BluetoothHeadset: Proxy object connected
,09-30 05:36:50.111   930   947 D BluetoothHeadset: Proxy object connected
,09-30 05:36:50.114  3182  3934 D BluetoothHeadset: Proxy object connected
09-30 05:36:50.114  3182  3182 D HeadsetProfile: Bluetooth service connected
,09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:53.769  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:36:53.775  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:53.776  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:36:53.777  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27fc721 removed from the list
09-30 05:36:53.777  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:36:53.777  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:36:53.777  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:36:53.780  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:36:53.781  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39a0746 added. We now have 4 listener(s)
09-30 05:36:53.781  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:36:53.783   930  3223 D WifiService: setWifiEnabled: false pid=5733, uid=10077
09-30 05:36:53.783   930  3223 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:36:56.284   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:57.285   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:58.287   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:58.793  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:58.794   930  3475 D WifiService: setWifiEnabled: true pid=5733, uid=10077
09-30 05:36:58.794   930  3475 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-30 05:36:58.804   511   928 D SoftapController: Softap fwReload - Ok
,09-30 05:36:58.809   511   928 D CommandListener: Setting iface cfg
09-30 05:36:58.810   511   928 D CommandListener: Trying to bring down wlan0
09-30 05:36:58.811   511   928 D CommandListener: Clearing all IP addresses on wlan0
,09-30 05:36:58.816   930  3013 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-30 05:36:59.288   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:36:59.500   930  3013 D wifi    : set interface wlan0 flags (UP)
,09-30 05:36:59.500   930  3013 I WifiHAL : Initializing wifi
,09-30 05:36:59.500   930  3013 I WifiHAL : Creating socket
,09-30 05:36:59.507   930  3013 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-30 05:36:59.507   930  3013 D wifi    : Did set static halHandle = 0x7f6a8d1680
09-30 05:36:59.507   930  3013 D wifi    : halHandle = 0x7f6a8d1680, mVM = 0x7f86f4d140, mCls = 0x201486
09-30 05:36:59.508   930  3013 D wifi    : array field set
09-30 05:36:59.508   930  3013 I WifiNative-HAL: interface[0] = wlan0
,09-30 05:36:59.510   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-30 05:36:59.512   930  6066 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547248477824
09-30 05:36:59.513   930  6066 D wifi    : waitForHalEvents called, vm = 0x7f86f4d140, obj = 0x201486, env = 0x7f69fe49c0
,09-30 05:36:59.560  6067  6067 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-30 05:36:59.581  6067  6067 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 05:36:59.592  6067  6067 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-30 05:36:59.592  6067  6067 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-30 05:36:59.615   930  3013 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-30 05:36:59.618  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:59.621  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:36:59.629   930  3013 D WifiConfigStore: Loading config and enabling all networks 
,09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:59.636  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:36:59.639  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-30 05:36:59.643  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-30 05:36:59.646  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-30 05:36:59.648   930  3013 D WifiConfigStore: loaded 0 passpoint configs
,09-30 05:36:59.648   930  3013 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-30 05:36:59.649   930  3013 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-30 05:36:59.650   930  3013 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-30 05:36:59.651   930  3013 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-30 05:36:59.651   930  3013 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-30 05:36:59.651   930  3013 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-30 05:36:59.652   930  3013 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-30 05:36:59.655   930  3013 D WifiNative-HAL: Setting external_sim to 1
,09-30 05:36:59.655   930  3013 D wifi    : setting dfs flag to true, 0x7f6d0ad420
09-30 05:36:59.655  5114  5114 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-30 05:36:59.656   930  3013 D WifiStateMachine: Setting OUI to DA-A1-19
09-30 05:36:59.656   930  3013 D wifi    : setting scan oui 0x7f6d0ad420
09-30 05:36:59.656   930  3013 D WifiHAL : Sending mac address OUI
,09-30 05:36:59.660   930  3013 E native  : do suspend false
,09-30 05:36:59.668   930  3013 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-30 05:36:59.668   930   930 D RttService: SCAN_AVAILABLE : 3
09-30 05:36:59.669   511   928 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-30 05:36:59.669   930  3121 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-30 05:36:59.670   511   928 D CommandListener: Setting iface cfg
,09-30 05:36:59.673   930  3012 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '157 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 157 Failed to set address (No such device)'
,09-30 05:36:59.673   930  3012 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-30 05:36:59.684   930  3012 D WifiNative-HAL: p2pGetDeviceAddress
,09-30 05:36:59.690   930  3012 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
09-30 05:36:59.690   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=301614 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,09-30 05:37:00.291   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:01.292   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 05:37:02.896  6067  6067 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:37:02.904  6067  6067 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:37:02.910  6067  6067 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:37:02.915  6067  6067 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:37:02.921  6067  6067 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-30 05:37:02.944   930  3013 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
09-30 05:37:02.945   930  3013 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-30 05:37:02.945   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:37:02.955   930  3013 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-30 05:37:02.985   930  3013 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-30 05:37:02.987  6067  6067 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-30 05:37:03.409  6067  6067 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-30 05:37:03.442  6067  6067 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-30 05:37:03.443  6067  6067 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-30 05:37:03.455   930  3013 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 05:37:03.456   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-30 05:37:03.456   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-30 05:37:03.472   930  3013 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-30 05:37:03.485   511   928 D CommandListener: Setting iface cfg
,09-30 05:37:03.490   930  3013 D WifiStateMachine: Start Dhcp Watchdog 3
,09-30 05:37:03.495   930  6072 D DhcpClient: Receive thread started
,09-30 05:37:03.501   930  3013 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-30 05:37:03.501   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 05:37:03.501   930  3015 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,09-30 05:37:03.581   930  3013 E native  : do suspend false
,09-30 05:37:03.595   930  6071 D DhcpClient: Broadcasting DHCPDISCOVER
,09-30 05:37:03.611   930  6072 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,09-30 05:37:03.612   930  6071 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,09-30 05:37:03.616   930  6071 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-30 05:37:03.628   930  6072 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-30 05:37:03.629   930  6071 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-30 05:37:03.633   511   928 D CommandListener: Setting iface cfg
,09-30 05:37:03.638   930  3013 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-30 05:37:03.644   930  6071 D DhcpClient: Scheduling renewal in 86399s
,09-30 05:37:03.651   930  3013 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-30 05:37:03.653   930  3013 D WifiConfigStore: No blacklist allowed without epno enabled
09-30 05:37:03.654   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-30 05:37:03.656   930  3015 D ConnectivityService: Adding iface wlan0 to network 102
,09-30 05:37:03.662   930  3013 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-30 05:37:03.709   930  3015 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-30 05:37:03.710   930  3015 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-30 05:37:03.715   930  3015 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-30 05:37:03.716   930  3015 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-30 05:37:03.718   930  3015 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-30 05:37:03.724   930  3015 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:37:03.729   930  3015 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-30 05:37:03.729   930  3015 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-30 05:37:03.729   930  3015 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-30 05:37:03.729   930  3015 D ConnectivityService:    accepting network in place of null
09-30 05:37:03.729   930  3013 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-30 05:37:03.729   930  3013 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-30 05:37:03.730   930  3015 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-30 05:37:03.742   930  6070 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305666, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 05:37:03.751   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:37:03.772   511   928 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-30 05:37:03.775   930  3015 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-30 05:37:03.775   930  3015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-30 05:37:03.775  3775  3910 W QCNEJ   : |CORE| network available: 102
09-30 05:37:03.776   930  3015 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-30 05:37:03.779   930   947 D Tethering: MasterInitialState.processMessage what=3
,09-30 05:37:03.781  3775  3910 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-30 05:37:03.783  3775  3910 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-30 05:37:03.783  3775  3910 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:03.786  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:37:03.788  5140  5164 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-30 05:37:03.789  5140  5164 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-30 05:37:03.790  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:37:03.791  4983  4983 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
09-30 05:37:03.789  5140  5164 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-30 05:37:03.793  5140  5164 E SarControlService: no key has been found,reset the power
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:03.793  5733  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:37:03.794  4008  4008 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-30 05:37:03.795  5733  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:03.797  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-30 05:37:03.797  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-30 05:37:03.797  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-30 05:37:03.798  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:37:03.798  5166  5166 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-30 05:37:03.799  5140  5177 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-30 05:37:03.799  5140  5177 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,09-30 05:37:03.799  5140  5177 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-30 05:37:03.800  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-30 05:37:03.800  5166  5166 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-30 05:37:03.801  4008  4008 D SystemUpdateService: onCreate
,09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:03.807  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:37:03.808  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:03.808  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:03.808  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39a0746 removed from the list
09-30 05:37:03.809  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:37:03.809  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:03.809  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:37:03.810  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000f003000000000000ffffffff]
09-30 05:37:03.810  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:37:03.811  5166  5180 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
09-30 05:37:03.811  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,09-30 05:37:03.811  5140  5151 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-30 05:37:03.812  4008  4008 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-30 05:37:03.812   930  6069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-30 05:37:03.813  5166  5180 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@959a2d1 HexData = [00000000f103000000000000ffffffff]
09-30 05:37:03.813  5166  5180 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-30 05:37:03.813  5166  5180 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
09-30 05:37:03.813  5733  6082 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-30 05:37:03.813  5733  6082 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
09-30 05:37:03.813  5166  5166 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-30 05:37:03.814  5140  5150 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-30 05:37:03.822  4008  4008 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-30 05:37:03.829  4008  5509 I iu.UploadsManager: num queued entries: 0
09-30 05:37:03.829  4008  5509 I iu.UploadsManager: num updated entries: 0
09-30 05:37:03.830  4008  5509 I iu.SyncManager: NEXT; no task
09-30 05:37:03.832  4008  4008 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-30 05:37:03.833  4008  4008 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-30 05:37:03.835  5865  5865 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-30 05:37:03.838  5865  5865 D SprintDMHelper: simOperator: 
,09-30 05:37:03.838  5865  5865 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-30 05:37:03.849  4008  6083 I SystemUpdateService: active receiver: enabled
,09-30 05:37:03.858   930  6069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 30 Sep 2016 09:37:03 GMT], X-Android-Received-Millis=[1475228223858], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1475228223834]}
,09-30 05:37:03.859   930  3015 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-30 05:37:03.859   930  3015 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-30 05:37:03.859   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-30 05:37:03.860   930  3015 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-30 05:37:03.871  4008  6083 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-30 05:37:03.876  4008  6083 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-30 05:37:03.876  4008  6083 I SystemUpdateService: now status is 0 (complete)
09-30 05:37:03.876  4008  6083 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-30 05:37:03.876  4008  6083 I SystemUpdateService: file has been verified
09-30 05:37:03.877  4008  6083 I SystemUpdateService: OTA package size = 21989297
,09-30 05:37:03.881  4008  6083 I SystemUpdateService: showing system update notification
,09-30 05:37:03.893  4008  4008 D SystemUpdateService: onDestroy
,09-30 05:37:03.945  5114  6088 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-30 05:37:06.522   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:37:06.838  5733  6095 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-30 05:37:06.838  5733  6082 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-30 05:37:06.839  5733  6095 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 05:37:06.839  5733  6082 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-30 05:37:06.840  5733  6082 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:37:06.840  5733  6095 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 05:37:06.842  5733  6082 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:37:06.842  5733  6095 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:37:06.843  5733  6082 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 05:37:06.843  5733  6095 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 05:37:06.848  5733  6097 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:06.848  5733  6097 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:37:06.849  5733  6099 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:06.849  5733  6099 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:06.849  5733  6100 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:06.849  5733  6100 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:37:06.850  5733  6099 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 159, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:06.850  5733  6099 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:06.850  5733  6099 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:06.850  5733  6099 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:06.850  5733  6098 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:06.850  5733  6098 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:06.850  5733  6099 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:37:06.850  5733  6099 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,09-30 05:37:06.851  5733  6098 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 158, thread name: OutgoingSocketThread/Sender): Socket closed
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:37:06.851  5733  6099 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:37:06.851  5733  6100 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 05:37:06.851  5733  6099 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:37:06.851  5733  6099 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:37:06.851  5733  6098 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:06.851  5733  6098 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:37:06.851  5733  6100 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 05:37:06.851  5733  6099 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 05:37:06.851  5733  6098 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
,09-30 05:37:06.851  5733  6098 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 05:37:06.852  5733  6099 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 159, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:06.852  5733  6099 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-30 05:37:06.852  5733  6100 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:06.852  5733  6100 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:37:06.852  5733  6098 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 158, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:06.852  5733  6098 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:37:06.853  5733  6097 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 157, thread name: IncomingSocketThread/Sender): Socket closed
,09-30 05:37:06.853  5733  6097 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:06.853  5733  6097 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 05:37:06.853  5733  6097 E io.jxcore.node.IncomingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 05:37:06.854  5733  6097 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 05:37:06.854  5733  6097 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 157, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:06.854  5733  6097 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
,09-30 05:37:09.824  5733  5779 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-30 05:37:09.826  5733  5779 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-30 05:37:09.831  5733  5779 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9ff1ec5 Bundle[{}]
,09-30 05:37:09.832  5733  5779 I io.jxcore.node.LifeCycleMonitor: start: OK
09-30 05:37:09.832  5733  5779 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-30 05:37:09.833  5733  5779 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-30 05:37:09.834  5733  5779 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-30 05:37:09.834  5733  5779 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-30 05:37:09.836  5733  5779 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-30 05:37:09.842  5733  5779 I System.out: Running OutgoingSocketThread
,09-30 05:37:09.845  5733  6101 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-30 05:37:09.845  5733  6101 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-30 05:37:11.735   930  3015 D ConnectivityService: handlePromptUnvalidated 102
,09-30 05:37:12.854  5733  6101 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-30 05:37:12.854  5733  6101 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,09-30 05:37:12.855  5733  6101 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-30 05:37:12.856  5733  6101 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:37:12.857  5733  6103 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-30 05:37:12.857  5733  6103 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-30 05:37:12.857  5733  6103 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:37:12.857  5733  6105 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:12.857  5733  6105 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:12.858  5733  6101 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-30 05:37:12.863  5733  6103 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:37:12.866  5733  6106 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 170, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:12.866  5733  6106 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:12.867  5733  6103 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-30 05:37:12.868  5733  6106 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 170, thread name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:12.868  5733  6106 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:12.868  5733  6106 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:12.868  5733  6106 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:12.868  5733  6106 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,09-30 05:37:12.868  5733  6106 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,09-30 05:37:12.869  5733  6105 E io.jxcore.node.StreamCopyingThread: Failed to read from input stream, got IO, not -1. Number of bytes read 0 (thread ID: 169, thread name: OutgoingSocketThread/Sender): Socket closed
09-30 05:37:12.869  5733  6105 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:12.869  5733  6105 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 05:37:12.870  5733  6105 E io.jxcore.node.OutgoingSocketThread: The sending thread failed with error: Failed to read from input stream, got IO, not -1. Number of bytes read 0: Socket closed
09-30 05:37:12.870  5733  6105 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
09-30 05:37:12.870  5733  6106 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:37:12.870  5733  6106 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 05:37:12.870  5733  6106 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:37:12.870  5733  6106 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-30 05:37:12.872  5733  6106 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 170, name: OutgoingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:12.872  5733  6106 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:37:12.872  5733  6105 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: OutgoingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:12.872  5733  6105 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 0 and the total number of bytes written 0
09-30 05:37:12.873  5733  6107 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:12.873  5733  6107 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 171, thread name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 05:37:12.874  5733  6107 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:37:12.875  5733  6107 I io.jxcore.node.IncomingSocketThread: The sending thread is done
09-30 05:37:12.875  5733  6108 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:12.875  5733  6108 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:37:12.875  5733  6107 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 171, name: IncomingSocketThread/Sender). Connection data: Peer properties: [null null].
09-30 05:37:12.875  5733  6107 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-30 05:37:12.876  5733  6108 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:12.876  5733  6108 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
,09-30 05:37:12.876  5733  6108 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:12.876  5733  6108 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true
09-30 05:37:12.877  5733  6108 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:37:12.877  5733  6108 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:37:12.877  5733  6108 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:37:12.877  5733  6108 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,09-30 05:37:12.877  5733  6108 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:37:12.877  5733  6108 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-30 05:37:12.877  5733  6108 I io.jxcore.node.IncomingSocketThread: Both threads are done, notifying the listener...
09-30 05:37:12.877  5733  6108 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: IncomingSocketThread/Receiver). Connection data: Peer properties: [null null].
09-30 05:37:12.877  5733  6108 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: true .During the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-30 05:37:14.693   930  3013 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 18, 19 -> obsolete
,09-30 05:37:15.855  5733  5779 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 181)
,09-30 05:37:15.857  5733  5779 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-30 05:37:15.857  5733  5779 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 182)
,09-30 05:37:15.863  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:15.863  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf09d07 added. We now have 3 listener(s)
,09-30 05:37:15.866  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:15.866  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:15.866  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-30 05:37:15.867  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:15.867  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb52e34 added. We now have 4 listener(s)
09-30 05:37:15.867  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:37:15.868  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:37:15.873  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:15.880  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:37:15.883  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:15.883  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 05:37:15.883  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:15.883  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdf51d2 added. We now have 4 listener(s)
09-30 05:37:15.885  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:15.885  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:15.885  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:15.885  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:15.886  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7002a3 added. We now have 5 listener(s)
09-30 05:37:15.886  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:37:15.886  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:37:15.886  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:37:15.886  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:37:15.886  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:37:15.887  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:15.887  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.887  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:37:15.887  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:15.887  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:15.887  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cf09d07 removed from the list
09-30 05:37:15.887  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:15.887  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb52e34 removed from the list
,09-30 05:37:15.890  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:37:15.891  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:37:15.891  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:37:15.892  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.892  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:15.893  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:15.893  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:15.893  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:15.893  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cb52e34 not in the list
09-30 05:37:15.893  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.893  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:15.895  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:15.895  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:37:15.895  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:15.895  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7002a3 removed from the list
09-30 05:37:15.895  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:15.895  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.895  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:15.895  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:15.895  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:15.895  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cdf51d2 removed from the list
09-30 05:37:15.896  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:15.896  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d90f9a0 added. We now have 3 listener(s)
09-30 05:37:15.898  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:15.898  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:15.898  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:15.898  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:15.898  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4893959 added. We now have 4 listener(s)
,09-30 05:37:15.899  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:37:15.900  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:37:15.903  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:15.908  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:37:15.911  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:15.911  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:37:15.911  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:15.911  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f625ff added. We now have 4 listener(s)
,09-30 05:37:15.913  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:15.913  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:15.913  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:15.913  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:15.913  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c0fcc added. We now have 5 listener(s)
09-30 05:37:15.913  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:37:15.914  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:37:15.914  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-30 05:37:15.914  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:37:15.914  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:37:15.914  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:37:15.915  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:37:15.917  5733  5779 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-30 05:37:15.917  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 05:37:15.918  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:37:15.921  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-30 05:37:15.922  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:37:15.922  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 05:37:15.926  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:37:15.926  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:37:15.926  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:37:15.926  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:37:15.926  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-30 05:37:15.927  5733  5779 D BluetoothAdapter: STATE_ON
,09-30 05:37:15.931  6011  6022 D BtGatt.GattService: registerClient() - UUID=621648a6-139d-42e8-a9fa-28f491487727
,09-30 05:37:15.932  6011  6027 D BtGatt.GattService: onClientRegistered() - UUID=621648a6-139d-42e8-a9fa-28f491487727, clientIf=5
09-30 05:37:15.933  5733  5744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 05:37:15.934  6011  6041 D BtGatt.GattService: start scan with filters
,09-30 05:37:15.939  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:37:15.939  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:37:15.939  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
,09-30 05:37:15.939  6011  6030 D BtGatt.ScanManager: handling starting scan
09-30 05:37:15.939  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:37:15.939  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:37:15.939  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:37:15.939  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:37:15.941  6011  6030 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@88c310e
,09-30 05:37:15.942  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:37:15.942  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:37:15.942  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:37:15.944  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:37:15.947  5733  5779 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-30 05:37:15.947  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-30 05:37:15.947  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-30 05:37:15.947  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.947  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:37:15.947  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:15.947  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-30 05:37:15.947  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:37:15.947  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:37:15.947  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:37:15.947  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:37:15.947  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 05:37:15.948  6011  6027 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:37:15.948  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:15.948  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:37:15.949  6011  6030 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:37:15.949  6011  6053 D BtGatt.GattService: stopScan() - queue size =1
,09-30 05:37:15.950  6011  6022 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:37:15.950  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:37:15.950  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:37:15.951  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:37:15.951  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:37:15.951  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:37:15.951  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:37:15.951  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:37:15.951  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-30 05:37:15.952  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 05:37:15.952  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:37:15.953  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:37:15.953  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:37:15.953  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-30 05:37:15.954  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:37:15.955  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:37:15.956  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:37:15.956  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-30 05:37:15.956  6011  6027 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:37:15.957  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:15.957  6011  6030 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:37:15.957  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:37:15.957  6011  6030 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:37:15.957  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:37:15.957  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:37:15.957  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:15.957  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:37:15.957  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:37:15.958  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:15.958  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:15.958  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d90f9a0 removed from the list
09-30 05:37:15.958  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:15.958  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4893959 removed from the list
09-30 05:37:15.958  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:37:15.958  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:37:15.958  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.958  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-30 05:37:15.961  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:15.961  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:15.961  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:15.961  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4893959 not in the list
09-30 05:37:15.961  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.961  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:15.962  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:15.962  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:15.962  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:15.962  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29c0fcc removed from the list
09-30 05:37:15.962  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:15.962  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:15.962  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:15.962  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:15.962  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:15.962  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f625ff removed from the list
09-30 05:37:15.963  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:15.963  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5605cb8 added. We now have 3 listener(s)
09-30 05:37:15.964  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:15.965  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:15.965  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:15.965  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:37:15.965  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@497ba91 added. We now have 4 listener(s)
09-30 05:37:15.965  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:37:15.966  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:37:15.967  6011  6027 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:37:15.967  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:15.969  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:15.973  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:37:15.973  6011  6027 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:37:15.973  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:37:15.975  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:37:15.975  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:37:15.975  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-30 05:37:15.976  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e14d5f7 added. We now have 4 listener(s)
,09-30 05:37:15.978  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-30 05:37:15.978  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:15.978  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:15.978  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:37:15.978  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:15.978  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1a8c64 added. We now have 5 listener(s)
09-30 05:37:15.978  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:37:15.979  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:37:15.979  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:37:15.979  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-30 05:37:15.979  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:37:15.980  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:37:15.980  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:37:15.980  6011  6027 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:37:15.980  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:15.981  6011  6030 D BtGatt.ScanManager: stopping BLe Batch
09-30 05:37:15.981  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:37:15.983  5733  5779 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 05:37:15.983  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-30 05:37:15.986  6011  6027 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:37:15.986  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:15.986  6011  6030 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-30 05:37:15.986  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:37:15.988  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:37:15.989  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-30 05:37:15.991  6011  6027 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:37:15.991  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:37:15.993  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-30 05:37:15.994  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:37:15.994  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:37:15.994  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:37:15.994  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
09-30 05:37:15.994  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:37:15.996  6011  6022 D BtGatt.GattService: registerClient() - UUID=04e46e66-4a38-4d0a-b40d-4aff866d7baf
09-30 05:37:15.996  6011  6027 D BtGatt.GattService: onClientRegistered() - UUID=04e46e66-4a38-4d0a-b40d-4aff866d7baf, clientIf=5
,09-30 05:37:15.996  5733  5744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-30 05:37:15.997  6011  6040 D BtGatt.GattService: start scan with filters
09-30 05:37:15.999  6011  6030 D BtGatt.ScanManager: handling starting scan
09-30 05:37:15.999  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:37:15.999  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:37:15.999  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:37:15.999  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
09-30 05:37:15.999  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:37:15.999  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-30 05:37:15.999  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:37:16.001  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-30 05:37:16.001  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-30 05:37:16.001  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:37:16.002  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:37:16.004  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:37:16.004  5733  5779 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
09-30 05:37:16.004  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:37:16.004  6011  6027 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-30 05:37:16.004  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:37:16.004  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.004  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:37:16.004  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:16.004  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.005  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:37:16.005  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:16.005  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-30 05:37:16.005  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5605cb8 removed from the list
09-30 05:37:16.005  6011  6030 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-30 05:37:16.005  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.005  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@497ba91 removed from the list
09-30 05:37:16.005  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:37:16.005  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:37:16.005  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.005  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-30 05:37:16.006  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.006  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:37:16.006  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:16.007  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:16.007  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.007  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@497ba91 not in the list
09-30 05:37:16.007  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-30 05:37:16.007  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:37:16.007  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:37:16.007  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:37:16.007  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-30 05:37:16.008  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:37:16.008  6011  6022 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:37:16.009  6011  6040 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:37:16.009  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:37:16.009  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:37:16.009  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-30 05:37:16.009  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:37:16.009  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:37:16.009  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:37:16.010  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:37:16.010  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:37:16.010  6011  6027 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:37:16.010  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.010  6011  6030 D BtGatt.ScanManager: Starting BLE batch scan
,09-30 05:37:16.010  6011  6030 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:37:16.011  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:37:16.011  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:37:16.011  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:37:16.011  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:37:16.011  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 05:37:16.011  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.012  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:16.012  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-30 05:37:16.012  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.013  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c1a8c64 removed from the list
09-30 05:37:16.013  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:37:16.013  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:16.013  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.013  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:37:16.013  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.013  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:16.013  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:37:16.013  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:16.013  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e14d5f7 removed from the list
09-30 05:37:16.013  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:16.013  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2260ad0 added. We now have 3 listener(s)
09-30 05:37:16.014  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:16.015  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:16.015  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:16.015  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-30 05:37:16.015  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5e2ac9 added. We now have 4 listener(s)
09-30 05:37:16.015  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:37:16.015  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-30 05:37:16.019  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:37:16.019  6011  6027 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:37:16.019  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:16.023  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-30 05:37:16.024  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-30 05:37:16.024  6011  6027 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:37:16.024  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.024  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
09-30 05:37:16.025  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:16.025  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36a8cef added. We now have 4 listener(s)
,09-30 05:37:16.027  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:16.027  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:16.027  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:16.027  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:16.027  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2903fc added. We now have 5 listener(s)
09-30 05:37:16.027  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-30 05:37:16.027  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:37:16.027  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-30 05:37:16.027  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:37:16.027  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-30 05:37:16.028  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-30 05:37:16.028  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-30 05:37:16.030  6011  6027 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:37:16.030  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.031  6011  6030 D BtGatt.ScanManager: stopping BLe Batch
09-30 05:37:16.031  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-30 05:37:16.032  5733  5779 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-30 05:37:16.032  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-30 05:37:16.035  6011  6027 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-30 05:37:16.035  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.035  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-30 05:37:16.035  6011  6030 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:37:16.036  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-30 05:37:16.036  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-30 05:37:16.039  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-30 05:37:16.039  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-30 05:37:16.039  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
09-30 05:37:16.039  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-30 05:37:16.039  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start
,09-30 05:37:16.040  5733  5779 D BluetoothAdapter: STATE_ON
09-30 05:37:16.040  6011  6027 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:37:16.041  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:37:16.042  6011  6053 D BtGatt.GattService: registerClient() - UUID=0a891fe3-6d89-4d1c-a8ce-df1ffdc03315
09-30 05:37:16.043  6011  6027 D BtGatt.GattService: onClientRegistered() - UUID=0a891fe3-6d89-4d1c-a8ce-df1ffdc03315, clientIf=5
,09-30 05:37:16.043  5733  5744 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-30 05:37:16.044  6011  6022 D BtGatt.GattService: start scan with filters
,09-30 05:37:16.046  6011  6030 D BtGatt.ScanManager: handling starting scan
09-30 05:37:16.046  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-30 05:37:16.046  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-30 05:37:16.046  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:37:16.046  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,09-30 05:37:16.046  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
09-30 05:37:16.046  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-30 05:37:16.046  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-30 05:37:16.048  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:37:16.048  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-30 05:37:16.048  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-30 05:37:16.049  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-30 05:37:16.051  6011  6027 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-30 05:37:16.051  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.051  6011  6030 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-30 05:37:16.054  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:37:16.054  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:37:16.054  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-30 05:37:16.054  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-30 05:37:16.055  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.055  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-30 05:37:16.055  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:16.055  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:16.055  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2260ad0 removed from the list
09-30 05:37:16.055  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.055  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5e2ac9 removed from the list
09-30 05:37:16.055  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:37:16.055  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:37:16.056  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.056  6011  6027 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-30 05:37:16.056  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-30 05:37:16.056  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.056  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-30 05:37:16.056  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-30 05:37:16.056  6011  6030 D BtGatt.ScanManager: Starting BLE batch scan
09-30 05:37:16.056  6011  6030 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-30 05:37:16.057  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:16.057  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:16.057  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.057  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5e2ac9 not in the list
09-30 05:37:16.057  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-30 05:37:16.057  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-30 05:37:16.057  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-30 05:37:16.057  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-30 05:37:16.057  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-30 05:37:16.065  5733  5779 D BluetoothAdapter: STATE_ON
,09-30 05:37:16.065  6011  6027 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-30 05:37:16.065  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.065  6011  6041 D BtGatt.GattService: stopScan() - queue size =1
09-30 05:37:16.066  6011  6021 D BtGatt.GattService: unregisterClient() - clientIf=5
09-30 05:37:16.066  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-30 05:37:16.066  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-30 05:37:16.066  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-30 05:37:16.067  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState
09-30 05:37:16.067  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
09-30 05:37:16.067  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
09-30 05:37:16.067  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-30 05:37:16.067  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-30 05:37:16.067  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:37:16.068  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-30 05:37:16.068  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTED
09-30 05:37:16.068  5733  5779 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-30 05:37:16.068  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-30 05:37:16.068  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.069  6011  6027 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-30 05:37:16.069  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.069  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:16.069  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:16.070  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.070  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:37:16.070  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2903fc removed from the list
09-30 05:37:16.070  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:16.070  5733  5733 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-30 05:37:16.070  5733  5733 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-30 05:37:16.070  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.070  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.070  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:16.070  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:16.070  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36a8cef removed from the list
09-30 05:37:16.071  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:16.071  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0063e8 added. We now have 3 listener(s)
,09-30 05:37:16.073  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:16.073  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:16.073  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:16.073  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:16.073  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50b6a01 added. We now have 4 listener(s)
09-30 05:37:16.073  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:37:16.074  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-30 05:37:16.075  6011  6027 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-30 05:37:16.076  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.076  6011  6030 D BtGatt.ScanManager: stopping BLe Batch
,09-30 05:37:16.076  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-30 05:37:16.080  6011  6027 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-30 05:37:16.080  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-30 05:37:16.081  5733  5779 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-30 05:37:16.081  6011  6030 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-30 05:37:16.083  5733  5779 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-30 05:37:16.083  5733  5779 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-30 05:37:16.083  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-30 05:37:16.083  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f12ae7 added. We now have 4 listener(s)
09-30 05:37:16.084  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-30 05:37:16.084  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-30 05:37:16.084  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-30 05:37:16.084  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-30 05:37:16.084  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6bd694 added. We now have 5 listener(s)
09-30 05:37:16.084  5733  5779 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-30 05:37:16.085  5733  5779 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-30 05:37:16.085  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:37:16.085  5733  5779 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-30 05:37:16.085  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:16.085  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.085  6011  6027 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-30 05:37:16.085  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:37:16.085  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-30 05:37:16.085  6011  6027 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-30 05:37:16.085  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:16.085  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:16.085  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0063e8 removed from the list
09-30 05:37:16.085  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.085  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50b6a01 removed from the list
09-30 05:37:16.087  5733  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-30 05:37:16.087  5733  5779 D io.jxcore.node.ConnectivityMonitor: stop
09-30 05:37:16.087  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.087  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-30 05:37:16.087  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.088  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:16.088  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:16.088  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-30 05:37:16.088  5733  5779 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50b6a01 not in the list
,09-30 05:37:16.089  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.089  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.090  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-30 05:37:16.090  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-30 05:37:16.090  5733  5779 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-30 05:37:16.090  5733  5779 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6bd694 removed from the list
09-30 05:37:16.091  5733  5779 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-30 05:37:16.091  5733  5779 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-30 05:37:16.091  5733  5779 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-30 05:37:16.091  5733  5779 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
09-30 05:37:16.091  5733  5779 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-30 05:37:16.091  5733  5779 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f12ae7 removed from the list
09-30 05:37:16.091  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-30 05:37:16.091  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-30 05:37:16.091  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-30 05:37:16.092  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:37:16.092  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-30 05:37:16.092  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-30 05:37:16.457  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:37:16.513  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:37:16.571  5733  5733 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-30 05:37:18.237  5733  6109 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 05:37:18.237  5733  6109 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:19.027  5733  6109 W !!      : call onHalfStreamCopied
,09-30 05:37:19.027  5733  6109 I testCopyDataAndClose: closing input stream
,09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
09-30 05:37:19.801  5733  6109 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 05:37:23.503  5733  6110 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:23.503  5733  6110 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:24.652   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:37:25.502  5733  5779 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 193. Connection data: Peer properties: [null null].
09-30 05:37:25.502  5733  5779 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:25.503  5733  5779 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 193, name: My test thread name)
,09-30 05:37:25.559  5733  6110 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,09-30 05:37:25.559  5733  6110 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:25.559  5733  6110 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,09-30 05:37:25.649  5733  6112 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 05:37:25.649  5733  6112 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:26.292   604   604 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-30 05:37:26.293   604   604 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: testCopyBigData thread). Connection data: Peer properties: [null null].
09-30 05:37:27.284  5733  6112 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,09-30 05:37:27.677   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:37:31.003  5733  6113 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:31.003  5733  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,09-30 05:37:31.003  5733  6113 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 197, thread name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:31.003  5733  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:31.003  5733  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
09-30 05:37:31.003  5733  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:31.004  5733  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
09-30 05:37:31.004  5733  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
09-30 05:37:31.004  5733  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
09-30 05:37:31.004  5733  6113 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
09-30 05:37:31.004  5733  6113 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,09-30 05:37:31.004  5733  6113 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:31.004  5733  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-30 05:37:31.006  5733  5779 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-30 05:37:31.008  5733  6114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:31.008  5733  6114 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
09-30 05:37:31.009  5733  6114 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 201, thread name: My test thread name): Test exception.
09-30 05:37:31.009  5733  6114 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:31.009  5733  6114 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-30 05:37:31.009  5733  6114 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
09-30 05:37:31.010  5733  6114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 201, name: My test thread name). Connection data: Peer properties: [null null].
09-30 05:37:31.010  5733  6114 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-30 05:37:31.013  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Total number of executed tests:  84'
09-30 05:37:31.013  5733  5779 I jxcore-log: 
09-30 05:37:31.014  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Number of passed tests:  82'
09-30 05:37:31.014  5733  5779 I jxcore-log: 
09-30 05:37:31.014  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Number of failed tests:  2'
09-30 05:37:31.014  5733  5779 I jxcore-log: 
09-30 05:37:31.014  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
09-30 05:37:31.014  5733  5779 I jxcore-log: 
,09-30 05:37:31.015  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Total duration:  102701'
09-30 05:37:31.015  5733  5779 I jxcore-log: 
09-30 05:37:31.016  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Failures: 
09-30 05:37:31.016  5733  5779 I jxcore-log:  IncomingSocketThread should get inputStream from OutgoingSocketThread and copy it to local incomingOutputStream
09-30 05:37:31.016  5733  5779 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 05:37:31.016  5733  5779 I jxcore-log:      but: was ""
09-30 05:37:31.016  5733  5779 I jxcore-log: OutgoingSocketThread should get inputStream from IncomingSocketThread and copy it to local outgoingOutputStream
09-30 05:37:31.016  5733  5779 I jxcore-log: Expected: is "Lorem ipsum dolor sit amet elit nibh, imperdiet dignissim, imperdiet wisi. Morbi vel risus. Nunc molestie placerat, nulla mi, id nulla ornare risus. Sed lacinia, urna eros lacus, elementum eu."
09-30 05:37:31.016  5733  5779 I jxcore-log:      but: was ""
09-30 05:37:31.016  5733  5779 I jxcore-log: '
09-30 05:37:31.016  5733  5779 I jxcore-log: 
09-30 05:37:31.016  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Failed to execute UT.'
09-30 05:37:31.016  5733  5779 I jxcore-log: 
,09-30 05:37:31.018  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Unit Test app is loaded'
09-30 05:37:31.018  5733  5779 I jxcore-log: 
,09-30 05:37:31.021  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.021  5733  5779 I jxcore-log: 
,09-30 05:37:31.023  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.023  5733  5779 I jxcore-log: 
09-30 05:37:31.023  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.023  5733  5779 I jxcore-log: 
09-30 05:37:31.023  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.023  5733  5779 I jxcore-log: 
09-30 05:37:31.023  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 05:37:31.023  5733  5779 I jxcore-log: 
09-30 05:37:31.024  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:37:31.024  5733  5779 I jxcore-log: 
09-30 05:37:31.024  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.024  5733  5779 I jxcore-log: 
09-30 05:37:31.025  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.025  5733  5779 I jxcore-log: 
09-30 05:37:31.025  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
09-30 05:37:31.025  5733  5779 I jxcore-log: 
09-30 05:37:31.025  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:37:31.025  5733  5779 I jxcore-log: 
09-30 05:37:31.025  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:37:31.025  5733  5779 I jxcore-log: 
,09-30 05:37:31.025  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.025  5733  5779 I jxcore-log: 
09-30 05:37:31.026  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.026  5733  5779 I jxcore-log: 
09-30 05:37:31.026  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.026  5733  5779 I jxcore-log: 
09-30 05:37:31.026  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.026  5733  5779 I jxcore-log: 
09-30 05:37:31.027  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.027  5733  5779 I jxcore-log: 
09-30 05:37:31.027  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.027  5733  5779 I jxcore-log: 
09-30 05:37:31.027  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.027  5733  5779 I jxcore-log: 
09-30 05:37:31.027  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.027  5733  5779 I jxcore-log: 
09-30 05:37:31.028  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.028  5733  5779 I jxcore-log: 
09-30 05:37:31.028  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.028  5733  5779 I jxcore-log: 
09-30 05:37:31.028  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.028  5733  5779 I jxcore-log: 
09-30 05:37:31.030  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.030  5733  5779 I jxcore-log: 
09-30 05:37:31.030  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.030  5733  5779 I jxcore-log: 
09-30 05:37:31.030  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.030  5733  5779 I jxcore-log: 
09-30 05:37:31.031  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.031  5733  5779 I jxcore-log: 
09-30 05:37:31.031  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare,"}'
09-30 05:37:31.031  5733  5779 I jxcore-log: 
09-30 05:37:31.031  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.031  5733  5779 I jxcore-log: 
09-30 05:37:31.031  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.031  5733  5779 I jxcore-log: 
09-30 05:37:31.032  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.032  5733  5779 I jxcore-log: 
09-30 05:37:31.032  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.032  5733  5779 I jxcore-log: 
09-30 05:37:31.032  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.032  5733  5779 I jxcore-log: 
09-30 05:37:31.032  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.032  5733  5779 I jxcore-log: 
09-30 05:37:31.032  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.032  5733  5779 I jxcore-log: 
09-30 05:37:31.033  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.033  5733  5779 I jxcore-log: 
09-30 05:37:31.033  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.033  5733  5779 I jxcore-log: 
09-30 05:37:31.033  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.033  5733  5779 I jxcore-log: 
09-30 05:37:31.033  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
09-30 05:37:31.033  5733  5779 I jxcore-log: 
09-30 05:37:31.034  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.034  5733  5779 I jxcore-log: 
09-30 05:37:31.034  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
09-30 05:37:31.034  5733  5779 I jxcore-log: 
09-30 05:37:31.034  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.034  5733  5779 I jxcore-log: 
09-30 05:37:31.034  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.034  5733  5779 I jxcore-log: 
09-30 05:37:31.034  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.034  5733  5779 I jxcore-log: 
09-30 0,5:37:31.035  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.035  5733  5779 I jxcore-log: 
09-30 05:37:31.035  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.035  5733  5779 I jxcore-log: 
09-30 05:37:31.035  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-30 05:37:31.035  5733  5779 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
09-30 05:37:31.035  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.035  5733  5779 I jxcore-log: 
09-30 05:37:31.036  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.036  5733  5779 I jxcore-log: 
09-30 05:37:31.036  5733  5779 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-30 05:37:31.036  5733  5779 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
09-30 05:37:31.036  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}'
09-30 05:37:31.036  5733  5779 I jxcore-log: 
09-30 05:37:31.036  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:37:31.036  5733  5779 I jxcore-log: 
09-30 05:37:31.036  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:37:31.036  5733  5779 I jxcore-log: 
09-30 05:37:31.037  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
09-30 05:37:31.037  5733  5779 I jxcore-log: 
,09-30 05:37:31.042  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
09-30 05:37:31.042  5733  5779 I jxcore-log: 
09-30 05:37:31.042  5733  5733 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-30 05:37:31.042  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - WARN testUtils: 'myNameCallback not set!'
09-30 05:37:31.042  5733  5779 I jxcore-log: 
09-30 05:37:31.043  5733  5779 I jxcore-log: 2016-09-30 09:37:31 - DEBUG UnitTest_app: 'Running for WIFI network type'
09-30 05:37:31.043  5733  5779 I jxcore-log: 
,09-30 05:37:32.813   930  6070 D NetlinkSocketObserver: NeighborEvent{elapsedMs=334737, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-30 05:37:33.022  5733  5779 I jxcore-log: 2016-09-30 09:37:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
09-30 05:37:33.022  5733  5779 I jxcore-log: 
,09-30 05:37:33.355  5733  5779 I jxcore-log: 2016-09-30 09:37:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
09-30 05:37:33.355  5733  5779 I jxcore-log: 
,09-30 05:37:33.370  5733  5779 I jxcore-log: 2016-09-30 09:37:33 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
09-30 05:37:33.370  5733  5779 I jxcore-log: 
,09-30 05:37:34.445  5733  5779 I jxcore-log: 2016-09-30 09:37:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
09-30 05:37:34.445  5733  5779 I jxcore-log: 
,09-30 05:37:34.606  5733  5779 I jxcore-log: 2016-09-30 09:37:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
09-30 05:37:34.606  5733  5779 I jxcore-log: 
,09-30 05:37:34.610  5733  5779 I jxcore-log: 2016-09-30 09:37:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
09-30 05:37:34.610  5733  5779 I jxcore-log: 
,09-30 05:37:34.615  5733  5779 I jxcore-log: 2016-09-30 09:37:34 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
09-30 05:37:34.615  5733  5779 I jxcore-log: 
,09-30 05:37:35.143  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
09-30 05:37:35.143  5733  5779 I jxcore-log: 
,09-30 05:37:35.194  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
09-30 05:37:35.194  5733  5779 I jxcore-log: 
,09-30 05:37:35.206  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
09-30 05:37:35.206  5733  5779 I jxcore-log: 
,09-30 05:37:35.211  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
09-30 05:37:35.211  5733  5779 I jxcore-log: 
,09-30 05:37:35.487  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
09-30 05:37:35.487  5733  5779 I jxcore-log: 
,09-30 05:37:35.612  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
09-30 05:37:35.612  5733  5779 I jxcore-log: 
,09-30 05:37:35.844  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
09-30 05:37:35.844  5733  5779 I jxcore-log: 
,09-30 05:37:35.854  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
09-30 05:37:35.854  5733  5779 I jxcore-log: 
,09-30 05:37:35.857  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
09-30 05:37:35.857  5733  5779 I jxcore-log: 
,09-30 05:37:35.991  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
09-30 05:37:35.991  5733  5779 I jxcore-log: 
,09-30 05:37:35.998  5733  5779 I jxcore-log: 2016-09-30 09:37:35 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
09-30 05:37:35.998  5733  5779 I jxcore-log: 
,09-30 05:37:36.025  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
09-30 05:37:36.025  5733  5779 I jxcore-log: 
,09-30 05:37:36.058  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
09-30 05:37:36.058  5733  5779 I jxcore-log: 
,09-30 05:37:36.065  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
09-30 05:37:36.065  5733  5779 I jxcore-log: 
,09-30 05:37:36.070  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
09-30 05:37:36.070  5733  5779 I jxcore-log: 
,09-30 05:37:36.084  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
09-30 05:37:36.084  5733  5779 I jxcore-log: 
,09-30 05:37:36.088  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
09-30 05:37:36.088  5733  5779 I jxcore-log: 
,09-30 05:37:36.093  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
09-30 05:37:36.093  5733  5779 I jxcore-log: 
,09-30 05:37:36.097  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
09-30 05:37:36.097  5733  5779 I jxcore-log: 
,09-30 05:37:36.109  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
09-30 05:37:36.109  5733  5779 I jxcore-log: 
,09-30 05:37:36.128  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
09-30 05:37:36.128  5733  5779 I jxcore-log: 
,09-30 05:37:36.137  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
09-30 05:37:36.137  5733  5779 I jxcore-log: 
,09-30 05:37:36.148  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
09-30 05:37:36.148  5733  5779 I jxcore-log: 
,09-30 05:37:36.157  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
09-30 05:37:36.157  5733  5779 I jxcore-log: 
,09-30 05:37:36.168  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
09-30 05:37:36.168  5733  5779 I jxcore-log: 
,09-30 05:37:36.178  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
09-30 05:37:36.178  5733  5779 I jxcore-log: 
,09-30 05:37:36.183  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
09-30 05:37:36.183  5733  5779 I jxcore-log: 
,09-30 05:37:36.204  5733  5779 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-30 05:37:36.205  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - INFO testUtils: 'BLE multiple advertisement supported'
09-30 05:37:36.205  5733  5779 I jxcore-log: 
,09-30 05:37:36.306  5733  5779 I jxcore-log: 2016-09-30 09:37:36 - DEBUG CoordinatedClient: 'connected to the test server'
09-30 05:37:36.306  5733  5779 I jxcore-log: 
,09-30 05:37:36.797  5733  5779 I jxcore-log: TAP version 13
09-30 05:37:36.797  5733  5779 I jxcore-log: 
,09-30 05:37:36.838  5733  5779 I jxcore-log: # setup
09-30 05:37:36.838  5733  5779 I jxcore-log: 
,09-30 05:37:37.769  5733  5779 I jxcore-log: # calling createNativeListener directly rejects
09-30 05:37:37.769  5733  5779 I jxcore-log: 
,09-30 05:37:37.915  5733  5779 I jxcore-log: 2016-09-30 09:37:37 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:37.915  5733  5779 I jxcore-log: 
,09-30 05:37:37.921  5733  5779 I jxcore-log: 2016-09-30 09:37:37 - DEBUG createNativeListener: 'listening 49654'
09-30 05:37:37.921  5733  5779 I jxcore-log: 
,09-30 05:37:37.930  5733  5779 I jxcore-log: ok 1 Should throw
09-30 05:37:37.930  5733  5779 I jxcore-log: 
,09-30 05:37:37.939  5733  5779 I jxcore-log: # teardown
09-30 05:37:37.939  5733  5779 I jxcore-log: 
,09-30 05:37:38.469  5733  5779 I jxcore-log: # setup
09-30 05:37:38.469  5733  5779 I jxcore-log: 
,09-30 05:37:39.177  5733  5779 I jxcore-log: # emits incomingConnectionState
09-30 05:37:39.177  5733  5779 I jxcore-log: 
,09-30 05:37:39.225  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:39.225  5733  5779 I jxcore-log: 
,09-30 05:37:39.229  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'listening 41110'
09-30 05:37:39.229  5733  5779 I jxcore-log: 
,09-30 05:37:39.240  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:39.240  5733  5779 I jxcore-log: 
,09-30 05:37:39.244  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:39.244  5733  5779 I jxcore-log: 
,09-30 05:37:39.254  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new mux'
09-30 05:37:39.254  5733  5779 I jxcore-log: 
,09-30 05:37:39.260  5733  5779 I jxcore-log: ok 2 initial connection state should be CONNECTED
09-30 05:37:39.260  5733  5779 I jxcore-log: 
,09-30 05:37:39.275  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:39.275  5733  5779 I jxcore-log: 
,09-30 05:37:39.276  5733  5779 I jxcore-log: ok 3 final connection state should be DISCONNECTED
09-30 05:37:39.276  5733  5779 I jxcore-log: 
,09-30 05:37:39.283  5733  5779 I jxcore-log: # teardown
09-30 05:37:39.283  5733  5779 I jxcore-log: 
,09-30 05:37:39.331  5733  5779 I jxcore-log: # setup
09-30 05:37:39.331  5733  5779 I jxcore-log: 
,09-30 05:37:39.359  5733  5779 I jxcore-log: # emits routerPortConnectionFailed
09-30 05:37:39.359  5733  5779 I jxcore-log: 
,09-30 05:37:39.439  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:39.439  5733  5779 I jxcore-log: 
,09-30 05:37:39.442  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'listening 48013'
09-30 05:37:39.442  5733  5779 I jxcore-log: 
,09-30 05:37:39.448  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:39.448  5733  5779 I jxcore-log: 
,09-30 05:37:39.450  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:39.450  5733  5779 I jxcore-log: 
,09-30 05:37:39.451  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new mux'
09-30 05:37:39.451  5733  5779 I jxcore-log: 
,09-30 05:37:39.478  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:39.478  5733  5779 I jxcore-log: 
,09-30 05:37:39.481  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:39.481  5733  5779 I jxcore-log: 
,09-30 05:37:39.486  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: ' $c@net.js:837:7
09-30 05:37:39.486  5733  5779 I jxcore-log: $09@net.js:829:13
09-30 05:37:39.486  5733  5779 I jxcore-log: '
09-30 05:37:39.486  5733  5779 I jxcore-log: 
,09-30 05:37:39.487  5733  5779 I jxcore-log: ok 4 tried to connect to right port
09-30 05:37:39.487  5733  5779 I jxcore-log: 
09-30 05:37:39.487  5733  5779 I jxcore-log: ok 5 failed due to refused connection
09-30 05:37:39.487  5733  5779 I jxcore-log: 
,09-30 05:37:39.488  5733  5779 I jxcore-log: ok 6 routerPortConnectionFailed is emitted
09-30 05:37:39.488  5733  5779 I jxcore-log: 
09-30 05:37:39.492  5733  5779 I jxcore-log: # teardown
09-30 05:37:39.492  5733  5779 I jxcore-log: 
09-30 05:37:39.493  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:39.493  5733  5779 I jxcore-log: 
,09-30 05:37:39.548  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'mux close'
09-30 05:37:39.548  5733  5779 I jxcore-log: 
,09-30 05:37:39.555  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:39.555  5733  5779 I jxcore-log: 
,09-30 05:37:39.571  5733  5779 I jxcore-log: # setup
09-30 05:37:39.571  5733  5779 I jxcore-log: 
,09-30 05:37:39.614  5733  5779 I jxcore-log: # native server connections all up
09-30 05:37:39.614  5733  5779 I jxcore-log: 
,09-30 05:37:39.664  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:39.664  5733  5779 I jxcore-log: 
,09-30 05:37:39.669  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'listening 49939'
09-30 05:37:39.669  5733  5779 I jxcore-log: 
,09-30 05:37:39.676  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:39.676  5733  5779 I jxcore-log: 
,09-30 05:37:39.677  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:39.677  5733  5779 I jxcore-log: 
09-30 05:37:39.678  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new mux'
09-30 05:37:39.678  5733  5779 I jxcore-log: 
,09-30 05:37:39.704  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:39.704  5733  5779 I jxcore-log: 
,09-30 05:37:39.708  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:39.708  5733  5779 I jxcore-log: 
,09-30 05:37:39.711  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:39.711  5733  5779 I jxcore-log: 
,09-30 05:37:39.714  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:39.714  5733  5779 I jxcore-log: 
,09-30 05:37:39.737  5733  5779 I jxcore-log: ok 7 Send/recvd #1 should be equal length
09-30 05:37:39.737  5733  5779 I jxcore-log: 
,09-30 05:37:39.738  5733  5779 I jxcore-log: ok 8 Send/recvd #1 should be same
09-30 05:37:39.738  5733  5779 I jxcore-log: 
,09-30 05:37:39.740  5733  5779 I jxcore-log: ok 9 Send/recvd #2 should be equal length
09-30 05:37:39.740  5733  5779 I jxcore-log: 
09-30 05:37:39.741  5733  5779 I jxcore-log: ok 10 Send/recvd #2 should be same
09-30 05:37:39.741  5733  5779 I jxcore-log: 
,09-30 05:37:39.744  5733  5779 I jxcore-log: ok 11 Should be exactly 2 client sockets
09-30 05:37:39.744  5733  5779 I jxcore-log: 
,09-30 05:37:39.750  5733  5779 I jxcore-log: # teardown
09-30 05:37:39.750  5733  5779 I jxcore-log: 
,09-30 05:37:39.788  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:39.788  5733  5779 I jxcore-log: 
,09-30 05:37:39.790  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:39.790  5733  5779 I jxcore-log: 
,09-30 05:37:39.792  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'mux close'
09-30 05:37:39.792  5733  5779 I jxcore-log: 
,09-30 05:37:39.796  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:39.796  5733  5779 I jxcore-log: 
,09-30 05:37:39.808  5733  5779 I jxcore-log: # setup
09-30 05:37:39.808  5733  5779 I jxcore-log: 
,09-30 05:37:39.886  5733  5779 I jxcore-log: # native server - closing incoming stream cleans outgoing socket
09-30 05:37:39.886  5733  5779 I jxcore-log: 
,09-30 05:37:39.951  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:39.951  5733  5779 I jxcore-log: 
,09-30 05:37:39.955  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'listening 49784'
09-30 05:37:39.955  5733  5779 I jxcore-log: 
,09-30 05:37:39.964  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:39.964  5733  5779 I jxcore-log: 
,09-30 05:37:39.965  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:39.965  5733  5779 I jxcore-log: 
,09-30 05:37:39.970  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new mux'
09-30 05:37:39.970  5733  5779 I jxcore-log: 
,09-30 05:37:39.981  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:39.981  5733  5779 I jxcore-log: 
,09-30 05:37:39.984  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:39.984  5733  5779 I jxcore-log: 
,09-30 05:37:39.997  5733  5779 I jxcore-log: 2016-09-30 09:37:39 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:39.997  5733  5779 I jxcore-log: 
,09-30 05:37:40.008  5733  5779 I jxcore-log: ok 12 socket shouldn't close until after stream
09-30 05:37:40.008  5733  5779 I jxcore-log: 
,09-30 05:37:40.009  5733  5779 I jxcore-log: ok 13 incoming remains open
09-30 05:37:40.009  5733  5779 I jxcore-log: 
,09-30 05:37:40.015  5733  5779 I jxcore-log: # teardown
09-30 05:37:40.015  5733  5779 I jxcore-log: 
,09-30 05:37:40.040  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'mux close'
09-30 05:37:40.040  5733  5779 I jxcore-log: 
,09-30 05:37:40.044  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:40.044  5733  5779 I jxcore-log: 
,09-30 05:37:40.051  5733  5779 I jxcore-log: # setup
09-30 05:37:40.051  5733  5779 I jxcore-log: 
,09-30 05:37:40.115  5733  5779 I jxcore-log: # native server - closing incoming connection cleans outgoing socket
09-30 05:37:40.115  5733  5779 I jxcore-log: 
,09-30 05:37:40.161  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:40.161  5733  5779 I jxcore-log: 
,09-30 05:37:40.164  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'listening 46568'
09-30 05:37:40.164  5733  5779 I jxcore-log: 
,09-30 05:37:40.171  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.171  5733  5779 I jxcore-log: 
,09-30 05:37:40.173  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.173  5733  5779 I jxcore-log: 
,09-30 05:37:40.175  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.175  5733  5779 I jxcore-log: 
,09-30 05:37:40.187  5733  5779 I jxcore-log: ok 14 we should not have gotten an error
09-30 05:37:40.187  5733  5779 I jxcore-log: 
,09-30 05:37:40.193  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:40.193  5733  5779 I jxcore-log: 
,09-30 05:37:40.198  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:40.198  5733  5779 I jxcore-log: 
,09-30 05:37:40.207  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:40.207  5733  5779 I jxcore-log: 
,09-30 05:37:40.212  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:40.212  5733  5779 I jxcore-log: 
,09-30 05:37:40.220  5733  5779 I jxcore-log: ok 15 socket shouldn't close until after incoming
09-30 05:37:40.220  5733  5779 I jxcore-log: 
,09-30 05:37:40.221  5733  5779 I jxcore-log: ok 16 incoming is cleaned up
09-30 05:37:40.221  5733  5779 I jxcore-log: 
,09-30 05:37:40.228  5733  5779 I jxcore-log: # teardown
09-30 05:37:40.228  5733  5779 I jxcore-log: 
,09-30 05:37:40.294  5733  5779 I jxcore-log: # setup
09-30 05:37:40.294  5733  5779 I jxcore-log: 
,09-30 05:37:40.398  5733  5779 I jxcore-log: # native server - closing outgoing socket cleans associated mux stream
09-30 05:37:40.398  5733  5779 I jxcore-log: 
,09-30 05:37:40.441  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:40.441  5733  5779 I jxcore-log: 
,09-30 05:37:40.445  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'listening 45264'
09-30 05:37:40.445  5733  5779 I jxcore-log: 
,09-30 05:37:40.454  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.454  5733  5779 I jxcore-log: 
,09-30 05:37:40.455  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.455  5733  5779 I jxcore-log: 
,09-30 05:37:40.460  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.460  5733  5779 I jxcore-log: 
,09-30 05:37:40.474  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:40.474  5733  5779 I jxcore-log: 
,09-30 05:37:40.477  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:40.477  5733  5779 I jxcore-log: 
,09-30 05:37:40.490  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:40.490  5733  5779 I jxcore-log: 
,09-30 05:37:40.498  5733  5779 I jxcore-log: ok 17 stream was closed
09-30 05:37:40.498  5733  5779 I jxcore-log: 
,09-30 05:37:40.499  5733  5779 I jxcore-log: ok 18 incoming should survive
09-30 05:37:40.499  5733  5779 I jxcore-log: 
09-30 05:37:40.499  5733  5779 I jxcore-log: ok 19 mux should have no streams
09-30 05:37:40.499  5733  5779 I jxcore-log: 
,09-30 05:37:40.504  5733  5779 I jxcore-log: # teardown
09-30 05:37:40.504  5733  5779 I jxcore-log: 
,09-30 05:37:40.556  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'mux close'
09-30 05:37:40.556  5733  5779 I jxcore-log: 
,09-30 05:37:40.574  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:40.574  5733  5779 I jxcore-log: 
,09-30 05:37:40.586  5733  5779 I jxcore-log: # setup
09-30 05:37:40.586  5733  5779 I jxcore-log: 
,09-30 05:37:40.653  5733  5779 I jxcore-log: # native server - closing the whole server cleans everything up
09-30 05:37:40.653  5733  5779 I jxcore-log: 
,09-30 05:37:40.695  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:40.695  5733  5779 I jxcore-log: 
,09-30 05:37:40.699  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'listening 49528'
09-30 05:37:40.699  5733  5779 I jxcore-log: 
,09-30 05:37:40.707  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.707  5733  5779 I jxcore-log: 
,09-30 05:37:40.708  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.708  5733  5779 I jxcore-log: 
09-30 05:37:40.710  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.710  5733  5779 I jxcore-log: 
,09-30 05:37:40.719  5733  5779 I jxcore-log: ok 20 we should not have gotten an error
09-30 05:37:40.719  5733  5779 I jxcore-log: 
,09-30 05:37:40.725  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:40.725  5733  5779 I jxcore-log: 
,09-30 05:37:40.728  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:40.728  5733  5779 I jxcore-log: 
,09-30 05:37:40.738  5733  5779 I jxcore-log: ok 21 Buffers are identical
09-30 05:37:40.738  5733  5779 I jxcore-log: 
,09-30 05:37:40.740  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:40.740  5733  5779 I jxcore-log: 
,09-30 05:37:40.743  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'mux close'
09-30 05:37:40.743  5733  5779 I jxcore-log: 
,09-30 05:37:40.745  5733  5779 I jxcore-log: ok 22 native server is nulled out
09-30 05:37:40.745  5733  5779 I jxcore-log: 
,09-30 05:37:40.745  5733  5779 I jxcore-log: ok 23 native server should be closed
09-30 05:37:40.745  5733  5779 I jxcore-log: 
09-30 05:37:40.745  5733  5779 I jxcore-log: ok 24 incoming has been removed
09-30 05:37:40.745  5733  5779 I jxcore-log: 
09-30 05:37:40.746  5733  5779 I jxcore-log: ok 25 Incoming should be done
09-30 05:37:40.746  5733  5779 I jxcore-log: 
09-30 05:37:40.746  5733  5779 I jxcore-log: ok 26 The mux object should be closed
09-30 05:37:40.746  5733  5779 I jxcore-log: 
09-30 05:37:40.746  5733  5779 I jxcore-log: ok 27 The mux stream should be closed
09-30 05:37:40.746  5733  5779 I jxcore-log: 
,09-30 05:37:40.747  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:40.747  5733  5779 I jxcore-log: 
,09-30 05:37:40.760  5733  5779 I jxcore-log: # teardown
09-30 05:37:40.760  5733  5779 I jxcore-log: 
,09-30 05:37:40.802  5733  5779 I jxcore-log: # setup
09-30 05:37:40.802  5733  5779 I jxcore-log: 
,09-30 05:37:40.832  5733  5779 I jxcore-log: # native server - we can get a ton of connections and data through and still clean up the server completely
09-30 05:37:40.832  5733  5779 I jxcore-log: 
,09-30 05:37:40.866  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:40.866  5733  5779 I jxcore-log: 
,09-30 05:37:40.869  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'listening 41465'
09-30 05:37:40.869  5733  5779 I jxcore-log: 
,09-30 05:37:40.894  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.894  5733  5779 I jxcore-log: 
,09-30 05:37:40.895  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.895  5733  5779 I jxcore-log: 
09-30 05:37:40.896  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.896  5733  5779 I jxcore-log: 
09-30 05:37:40.899  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.899  5733  5779 I jxcore-log: 
09-30 05:37:40.900  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.900  5733  5779 I jxcore-log: 
09-30 05:37:40.901  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.901  5733  5779 I jxcore-log: 
,09-30 05:37:40.903  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.903  5733  5779 I jxcore-log: 
,09-30 05:37:40.904  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.904  5733  5779 I jxcore-log: 
09-30 05:37:40.906  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.906  5733  5779 I jxcore-log: 
,09-30 05:37:40.910  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.910  5733  5779 I jxcore-log: 
,09-30 05:37:40.911  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.911  5733  5779 I jxcore-log: 
,09-30 05:37:40.912  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.912  5733  5779 I jxcore-log: 
,09-30 05:37:40.915  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.915  5733  5779 I jxcore-log: 
,09-30 05:37:40.916  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.916  5733  5779 I jxcore-log: 
,09-30 05:37:40.919  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.919  5733  5779 I jxcore-log: 
,09-30 05:37:40.922  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.922  5733  5779 I jxcore-log: 
,09-30 05:37:40.923  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.923  5733  5779 I jxcore-log: 
,09-30 05:37:40.924  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.924  5733  5779 I jxcore-log: 
,09-30 05:37:40.927  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.927  5733  5779 I jxcore-log: 
,09-30 05:37:40.927  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.927  5733  5779 I jxcore-log: 
,09-30 05:37:40.928  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.928  5733  5779 I jxcore-log: 
,09-30 05:37:40.933  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.933  5733  5779 I jxcore-log: 
,09-30 05:37:40.933  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.933  5733  5779 I jxcore-log: 
,09-30 05:37:40.934  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.934  5733  5779 I jxcore-log: 
,09-30 05:37:40.935  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.935  5733  5779 I jxcore-log: 
,09-30 05:37:40.936  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.936  5733  5779 I jxcore-log: 
,09-30 05:37:40.936  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.936  5733  5779 I jxcore-log: 
,09-30 05:37:40.937  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:40.937  5733  5779 I jxcore-log: 
09-30 05:37:40.938  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:40.938  5733  5779 I jxcore-log: 
,09-30 05:37:40.938  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new mux'
09-30 05:37:40.938  5733  5779 I jxcore-log: 
,09-30 05:37:40.993  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:40.993  5733  5779 I jxcore-log: 
,09-30 05:37:40.995  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:40.995  5733  5779 I jxcore-log: 
,09-30 05:37:40.997  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:40.997  5733  5779 I jxcore-log: 
,09-30 05:37:40.998  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:40.998  5733  5779 I jxcore-log: 
,09-30 05:37:40.999  5733  5779 I jxcore-log: 2016-09-30 09:37:40 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:40.999  5733  5779 I jxcore-log: 
,09-30 05:37:41.000  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.000  5733  5779 I jxcore-log: 
,09-30 05:37:41.001  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.001  5733  5779 I jxcore-log: 
09-30 05:37:41.002  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.002  5733  5779 I jxcore-log: 
,09-30 05:37:41.003  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.003  5733  5779 I jxcore-log: 
,09-30 05:37:41.004  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.004  5733  5779 I jxcore-log: 
,09-30 05:37:41.005  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.005  5733  5779 I jxcore-log: 
,09-30 05:37:41.006  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.006  5733  5779 I jxcore-log: 
09-30 05:37:41.007  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.007  5733  5779 I jxcore-log: 
,09-30 05:37:41.007  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.007  5733  5779 I jxcore-log: 
,09-30 05:37:41.008  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.008  5733  5779 I jxcore-log: 
,09-30 05:37:41.009  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.009  5733  5779 I jxcore-log: 
,09-30 05:37:41.010  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.010  5733  5779 I jxcore-log: 
,09-30 05:37:41.011  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.011  5733  5779 I jxcore-log: 
09-30 05:37:41.012  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.012  5733  5779 I jxcore-log: 
,09-30 05:37:41.013  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.013  5733  5779 I jxcore-log: 
,09-30 05:37:41.014  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.014  5733  5779 I jxcore-log: 
,09-30 05:37:41.014  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.014  5733  5779 I jxcore-log: 
09-30 05:37:41.015  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.015  5733  5779 I jxcore-log: 
,09-30 05:37:41.016  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.016  5733  5779 I jxcore-log: 
,09-30 05:37:41.017  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.017  5733  5779 I jxcore-log: 
,09-30 05:37:41.018  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.018  5733  5779 I jxcore-log: 
,09-30 05:37:41.019  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.019  5733  5779 I jxcore-log: 
09-30 05:37:41.020  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.020  5733  5779 I jxcore-log: 
,09-30 05:37:41.020  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.020  5733  5779 I jxcore-log: 
,09-30 05:37:41.021  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.021  5733  5779 I jxcore-log: 
09-30 05:37:41.021  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.021  5733  5779 I jxcore-log: 
09-30 05:37:41.022  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.022  5733  5779 I jxcore-log: 
,09-30 05:37:41.023  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.023  5733  5779 I jxcore-log: 
,09-30 05:37:41.024  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.024  5733  5779 I jxcore-log: 
09-30 05:37:41.024  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.024  5733  5779 I jxcore-log: 
,09-30 05:37:41.025  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.025  5733  5779 I jxcore-log: 
,09-30 05:37:41.026  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.026  5733  5779 I jxcore-log: 
09-30 05:37:41.026  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.026  5733  5779 I jxcore-log: 
,09-30 05:37:41.027  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.027  5733  5779 I jxcore-log: 
,09-30 05:37:41.027  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.027  5733  5779 I jxcore-log: 
,09-30 05:37:41.028  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.028  5733  5779 I jxcore-log: 
,09-30 05:37:41.029  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.029  5733  5779 I jxcore-log: 
09-30 05:37:41.030  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.030  5733  5779 I jxcore-log: 
,09-30 05:37:41.030  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.030  5733  5779 I jxcore-log: 
09-30 05:37:41.031  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.031  5733  5779 I jxcore-log: 
,09-30 05:37:41.032  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.032  5733  5779 I jxcore-log: 
,09-30 05:37:41.032  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.032  5733  5779 I jxcore-log: 
09-30 05:37:41.033  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.033  5733  5779 I jxcore-log: 
,09-30 05:37:41.039  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.039  5733  5779 I jxcore-log: 
,09-30 05:37:41.040  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.040  5733  5779 I jxcore-log: 
,09-30 05:37:41.040  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.040  5733  5779 I jxcore-log: 
,09-30 05:37:41.041  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.041  5733  5779 I jxcore-log: 
09-30 05:37:41.042  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.042  5733  5779 I jxcore-log: 
,09-30 05:37:41.043  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.043  5733  5779 I jxcore-log: 
09-30 05:37:41.043  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.043  5733  5779 I jxcore-log: 
,09-30 05:37:41.044  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.044  5733  5779 I jxcore-log: 
09-30 05:37:41.045  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.045  5733  5779 I jxcore-log: 
,09-30 05:37:41.046  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.046  5733  5779 I jxcore-log: 
09-30 05:37:41.046  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.046  5733  5779 I jxcore-log: 
,09-30 05:37:41.047  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.047  5733  5779 I jxcore-log: 
09-30 05:37:41.047  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.047  5733  5779 I jxcore-log: 
,09-30 05:37:41.048  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.048  5733  5779 I jxcore-log: 
09-30 05:37:41.049  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.049  5733  5779 I jxcore-log: 
,09-30 05:37:41.049  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.049  5733  5779 I jxcore-log: 
,09-30 05:37:41.050  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.050  5733  5779 I jxcore-log: 
09-30 05:37:41.051  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.051  5733  5779 I jxcore-log: 
,09-30 05:37:41.051  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.051  5733  5779 I jxcore-log: 
09-30 05:37:41.052  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.052  5733  5779 I jxcore-log: 
09-30 05:37:41.053  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.053  5733  5779 I jxcore-log: 
,09-30 05:37:41.053  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.053  5733  5779 I jxcore-log: 
,09-30 05:37:41.054  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.054  5733  5779 I jxcore-log: 
09-30 05:37:41.055  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.055  5733  5779 I jxcore-log: 
,09-30 05:37:41.056  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.056  5733  5779 I jxcore-log: 
09-30 05:37:41.056  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.056  5733  5779 I jxcore-log: 
,09-30 05:37:41.057  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.057  5733  5779 I jxcore-log: 
09-30 05:37:41.058  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.058  5733  5779 I jxcore-log: 
,09-30 05:37:41.058  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.058  5733  5779 I jxcore-log: 
09-30 05:37:41.059  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.059  5733  5779 I jxcore-log: 
,09-30 05:37:41.059  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:41.059  5733  5779 I jxcore-log: 
09-30 05:37:41.060  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:41.060  5733  5779 I jxcore-log: 
,09-30 05:37:41.105  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.105  5733  5779 I jxcore-log: 
,09-30 05:37:41.106  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.106  5733  5779 I jxcore-log: 
,09-30 05:37:41.107  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.107  5733  5779 I jxcore-log: 
,09-30 05:37:41.108  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.108  5733  5779 I jxcore-log: 
09-30 05:37:41.108  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.108  5733  5779 I jxcore-log: 
09-30 05:37:41.109  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.109  5733  5779 I jxcore-log: 
,09-30 05:37:41.109  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.109  5733  5779 I jxcore-log: 
09-30 05:37:41.110  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.110  5733  5779 I jxcore-log: 
,09-30 05:37:41.110  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.110  5733  5779 I jxcore-log: 
09-30 05:37:41.111  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.111  5733  5779 I jxcore-log: 
,09-30 05:37:41.111  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.111  5733  5779 I jxcore-log: 
,09-30 05:37:41.112  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.112  5733  5779 I jxcore-log: 
09-30 05:37:41.112  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.112  5733  5779 I jxcore-log: 
,09-30 05:37:41.112  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.112  5733  5779 I jxcore-log: 
09-30 05:37:41.113  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.113  5733  5779 I jxcore-log: 
09-30 05:37:41.114  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.114  5733  5779 I jxcore-log: 
,09-30 05:37:41.114  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.114  5733  5779 I jxcore-log: 
09-30 05:37:41.115  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.115  5733  5779 I jxcore-log: 
09-30 05:37:41.115  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.115  5733  5779 I jxcore-log: 
,09-30 05:37:41.115  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.115  5733  5779 I jxcore-log: 
09-30 05:37:41.116  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.116  5733  5779 I jxcore-log: 
09-30 05:37:41.116  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.116  5733  5779 I jxcore-log: 
,09-30 05:37:41.117  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.117  5733  5779 I jxcore-log: 
09-30 05:37:41.117  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.117  5733  5779 I jxcore-log: 
09-30 05:37:41.118  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.118  5733  5779 I jxcore-log: 
,09-30 05:37:41.118  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.118  5733  5779 I jxcore-log: 
09-30 05:37:41.119  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.119  5733  5779 I jxcore-log: 
09-30 05:37:41.119  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.119  5733  5779 I jxcore-log: 
,09-30 05:37:41.119  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.119  5733  5779 I jxcore-log: 
09-30 05:37:41.120  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.120  5733  5779 I jxcore-log: 
,09-30 05:37:41.120  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.120  5733  5779 I jxcore-log: 
09-30 05:37:41.121  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.121  5733  5779 I jxcore-log: 
09-30 05:37:41.121  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.121  5733  5779 I jxcore-log: 
09-30 05:37:41.122  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.122  5733  5779 I jxcore-log: 
,09-30 05:37:41.122  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.122  5733  5779 I jxcore-log: 
09-30 05:37:41.122  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.122  5733  5779 I jxcore-log: 
09-30 05:37:41.123  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.123  5733  5779 I jxcore-log: 
09-30 05:37:41.123  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.123  5733  5779 I jxcore-log: 
,09-30 05:37:41.124  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.124  5733  5779 I jxcore-log: 
09-30 05:37:41.124  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.124  5733  5779 I jxcore-log: 
09-30 05:37:41.124  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.124  5733  5779 I jxcore-log: 
,09-30 05:37:41.125  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.125  5733  5779 I jxcore-log: 
09-30 05:37:41.125  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.125  5733  5779 I jxcore-log: 
09-30 05:37:41.126  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.126  5733  5779 I jxcore-log: 
09-30 05:37:41.127  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.127  5733  5779 I jxcore-log: 
,09-30 05:37:41.128  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.128  5733  5779 I jxcore-log: 
09-30 05:37:41.128  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.128  5733  5779 I jxcore-log: 
09-30 05:37:41.131  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.131  5733  5779 I jxcore-log: 
09-30 05:37:41.131  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:41.131  5733  5779 I jxcore-log: 
09-30 05:37:41.132  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'mux close'
09-30 05:37:41.132  5733  5779 I jxcore-log: 
,09-30 05:37:41.134  5733  5779 I jxcore-log: ok 28 native server is nulled out
09-30 05:37:41.134  5733  5779 I jxcore-log: 
,09-30 05:37:41.134  5733  5779 I jxcore-log: ok 29 native server should be closed
09-30 05:37:41.134  5733  5779 I jxcore-log: 
09-30 05:37:41.134  5733  5779 I jxcore-log: ok 30 incoming has been removed
09-30 05:37:41.134  5733  5779 I jxcore-log: 
09-30 05:37:41.135  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.135  5733  5779 I jxcore-log: 
,09-30 05:37:41.136  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.136  5733  5779 I jxcore-log: 
09-30 05:37:41.136  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.136  5733  5779 I jxcore-log: 
09-30 05:37:41.136  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.136  5733  5779 I jxcore-log: 
,09-30 05:37:41.136  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.136  5733  5779 I jxcore-log: 
09-30 05:37:41.137  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.137  5733  5779 I jxcore-log: 
09-30 05:37:41.137  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.137  5733  5779 I jxcore-log: 
09-30 05:37:41.137  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.137  5733  5779 I jxcore-log: 
09-30 05:37:41.137  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.137  5733  5779 I jxcore-log: 
09-30 05:37:41.137  5733  5779 I jxcore-log: 2016-09-30 09:37:41 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:41.137  5733  5779 I jxcore-log: 
,09-30 05:37:41.210  5733  5779 I jxcore-log: # teardown
09-30 05:37:41.210  5733  5779 I jxcore-log: 
,09-30 05:37:41.273   930  6070 D NetlinkSocketObserver: NeighborEvent{elapsedMs=343196, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-30 05:37:41.294   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:41.323  5733  5779 I jxcore-log: # setup
09-30 05:37:41.323  5733  5779 I jxcore-log: 
,09-30 05:37:42.295   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:43.057  5733  5779 I jxcore-log: # native server - simulate mux failure, make sure everything is cleaned up
09-30 05:37:43.057  5733  5779 I jxcore-log: 
,09-30 05:37:43.296   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:43.712   930  3013 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:37:44.004  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:44.004  5733  5779 I jxcore-log: 
,09-30 05:37:44.007  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'listening 38217'
09-30 05:37:44.007  5733  5779 I jxcore-log: 
,09-30 05:37:44.014  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:44.014  5733  5779 I jxcore-log: 
,09-30 05:37:44.015  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:44.015  5733  5779 I jxcore-log: 
,09-30 05:37:44.017  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'new mux'
09-30 05:37:44.017  5733  5779 I jxcore-log: 
,09-30 05:37:44.025  5733  5779 I jxcore-log: ok 31 we should not have gotten an error
09-30 05:37:44.025  5733  5779 I jxcore-log: 
,09-30 05:37:44.029  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:44.029  5733  5779 I jxcore-log: 
,09-30 05:37:44.032  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:44.032  5733  5779 I jxcore-log: 
,09-30 05:37:44.040  5733  5779 I jxcore-log: ok 32 Buffers are identical
09-30 05:37:44.040  5733  5779 I jxcore-log: 
,09-30 05:37:44.041  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:44.041  5733  5779 I jxcore-log: 
09-30 05:37:44.042  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'mux close'
09-30 05:37:44.042  5733  5779 I jxcore-log: 
,09-30 05:37:44.053  5733  5779 I jxcore-log: 2016-09-30 09:37:44 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:44.053  5733  5779 I jxcore-log: 
,09-30 05:37:44.053  5733  5779 I jxcore-log: ok 33 server should be fine
09-30 05:37:44.053  5733  5779 I jxcore-log: 
09-30 05:37:44.054  5733  5779 I jxcore-log: ok 34 server should be open
09-30 05:37:44.054  5733  5779 I jxcore-log: 
09-30 05:37:44.054  5733  5779 I jxcore-log: ok 35 incoming has been removed
09-30 05:37:44.054  5733  5779 I jxcore-log: 
09-30 05:37:44.054  5733  5779 I jxcore-log: ok 36 The mux object should be closed
09-30 05:37:44.054  5733  5779 I jxcore-log: 
09-30 05:37:44.054  5733  5779 I jxcore-log: ok 37 The mux stream should be closed
09-30 05:37:44.054  5733  5779 I jxcore-log: 
,09-30 05:37:44.060  5733  5779 I jxcore-log: # teardown
09-30 05:37:44.060  5733  5779 I jxcore-log: 
,09-30 05:37:44.297   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:44.554  5733  5779 I jxcore-log: # setup
09-30 05:37:44.554  5733  5779 I jxcore-log: 
,09-30 05:37:45.298   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:45.638  5733  5779 I jxcore-log: # native server - timing out the incoming connection cleans everything up
09-30 05:37:45.638  5733  5779 I jxcore-log: 
,09-30 05:37:45.942  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'creating native server'
09-30 05:37:45.942  5733  5779 I jxcore-log: 
,09-30 05:37:45.947  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'listening 38823'
09-30 05:37:45.947  5733  5779 I jxcore-log: 
,09-30 05:37:45.956  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'new incoming socket'
09-30 05:37:45.956  5733  5779 I jxcore-log: 
,09-30 05:37:45.957  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'creating incoming mux'
09-30 05:37:45.957  5733  5779 I jxcore-log: 
09-30 05:37:45.959  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'new mux'
09-30 05:37:45.959  5733  5779 I jxcore-log: 
,09-30 05:37:45.966  5733  5779 I jxcore-log: ok 38 we should not have gotten an error
09-30 05:37:45.966  5733  5779 I jxcore-log: 
,09-30 05:37:45.970  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'new stream: '
09-30 05:37:45.970  5733  5779 I jxcore-log: 
,09-30 05:37:45.972  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'new outgoing socket'
09-30 05:37:45.972  5733  5779 I jxcore-log: 
,09-30 05:37:45.979  5733  5779 I jxcore-log: ok 39 Buffers are identical
09-30 05:37:45.979  5733  5779 I jxcore-log: 
,09-30 05:37:45.982  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'incoming socket timeout'
09-30 05:37:45.982  5733  5779 I jxcore-log: 
,09-30 05:37:45.983  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'stream close:'
09-30 05:37:45.983  5733  5779 I jxcore-log: 
,09-30 05:37:45.985  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'mux close'
09-30 05:37:45.985  5733  5779 I jxcore-log: 
,09-30 05:37:45.989  5733  5779 I jxcore-log: 2016-09-30 09:37:45 - DEBUG createNativeListener: 'incoming socket close'
09-30 05:37:45.989  5733  5779 I jxcore-log: 
,09-30 05:37:45.990  5733  5779 I jxcore-log: ok 40 server should be fine
09-30 05:37:45.990  5733  5779 I jxcore-log: 
09-30 05:37:45.990  5733  5779 I jxcore-log: ok 41 server should be open
09-30 05:37:45.990  5733  5779 I jxcore-log: 
09-30 05:37:45.990  5733  5779 I jxcore-log: ok 42 incoming has been removed
09-30 05:37:45.990  5733  5779 I jxcore-log: 
09-30 05:37:45.990  5733  5779 I jxcore-log: ok 43 The mux object should be closed
09-30 05:37:45.990  5733  5779 I jxcore-log: 
09-30 05:37:45.991  5733  5779 I jxcore-log: ok 44 The mux stream should be closed
09-30 05:37:45.991  5733  5779 I jxcore-log: 
,09-30 05:37:45.997  5733  5779 I jxcore-log: # teardown
09-30 05:37:45.997  5733  5779 I jxcore-log: 
,09-30 05:37:46.299   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-30 05:37:51.300   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:52.301   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:53.302   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:54.304   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:54.941  5733  5779 I jxcore-log: # setup
09-30 05:37:54.941  5733  5779 I jxcore-log: 
,09-30 05:37:55.164  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - server is not there
09-30 05:37:55.164  5733  5779 I jxcore-log: 
,09-30 05:37:55.304   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:37:55.425  5733  5779 I jxcore-log: 2016-09-30 09:37:55 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
09-30 05:37:55.425  5733  5779 I jxcore-log: 
,09-30 05:37:55.426  5733  5779 I jxcore-log: ok 45 Got right error
09-30 05:37:55.426  5733  5779 I jxcore-log: 
,09-30 05:37:55.431  5733  5779 I jxcore-log: # teardown
09-30 05:37:55.431  5733  5779 I jxcore-log: 
,09-30 05:37:55.462  5733  5779 I jxcore-log: # setup
09-30 05:37:55.462  5733  5779 I jxcore-log: 
,09-30 05:37:55.539  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - server accepts & closes connection
09-30 05:37:55.539  5733  5779 I jxcore-log: 
,09-30 05:37:55.622  5733  5779 I jxcore-log: 2016-09-30 09:37:55 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
09-30 05:37:55.622  5733  5779 I jxcore-log: 
,09-30 05:37:55.623  5733  5779 I jxcore-log: ok 46 Got socket hang up
09-30 05:37:55.623  5733  5779 I jxcore-log: 
,09-30 05:37:55.629  5733  5779 I jxcore-log: # teardown
09-30 05:37:55.629  5733  5779 I jxcore-log: 
,09-30 05:37:55.671  5733  5779 I jxcore-log: # setup
09-30 05:37:55.671  5733  5779 I jxcore-log: 
,09-30 05:37:55.746  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - server always returns 500
09-30 05:37:55.746  5733  5779 I jxcore-log: 
,09-30 05:37:55.899  5733  5779 I jxcore-log: 2016-09-30 09:37:55 - DEBUG localSeqManager: 'Got an error trying to update seq []'
09-30 05:37:55.899  5733  5779 I jxcore-log: 
,09-30 05:37:55.900  5733  5779 I jxcore-log: ok 47 Got 500 as expected
09-30 05:37:55.900  5733  5779 I jxcore-log: 
,09-30 05:37:55.904  5733  5779 I jxcore-log: # teardown
09-30 05:37:55.904  5733  5779 I jxcore-log: 
,09-30 05:37:55.931  5733  5779 I jxcore-log: # setup
09-30 05:37:55.931  5733  5779 I jxcore-log: 
,09-30 05:37:55.963  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - create new seq doc
09-30 05:37:55.963  5733  5779 I jxcore-log: 
,09-30 05:37:56.305   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-30 05:37:57.387  5733  5779 I jxcore-log: ok 48 should be equal
09-30 05:37:57.387  5733  5779 I jxcore-log: 
,09-30 05:37:57.387  5733  5779 I jxcore-log: ok 49 revs are equal
09-30 05:37:57.387  5733  5779 I jxcore-log: 
,09-30 05:37:57.392  5733  5779 I jxcore-log: # teardown
09-30 05:37:57.392  5733  5779 I jxcore-log: 
,09-30 05:37:57.429  5733  5779 I jxcore-log: # setup
09-30 05:37:57.429  5733  5779 I jxcore-log: 
,09-30 05:37:58.337  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - doc exists, need to get rev and update
09-30 05:37:58.337  5733  5779 I jxcore-log: 
,09-30 05:37:59.088  5733  5779 I jxcore-log: ok 50 should be equal
09-30 05:37:59.088  5733  5779 I jxcore-log: 
09-30 05:37:59.088  5733  5779 I jxcore-log: ok 51 revs are equal
09-30 05:37:59.088  5733  5779 I jxcore-log: 
,09-30 05:37:59.094  5733  5779 I jxcore-log: # teardown
09-30 05:37:59.094  5733  5779 I jxcore-log: 
,09-30 05:37:59.138  5733  5779 I jxcore-log: # setup
09-30 05:37:59.138  5733  5779 I jxcore-log: 
,09-30 05:37:59.189  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - update seq three times
09-30 05:37:59.189  5733  5779 I jxcore-log: 
,09-30 05:37:59.754  5733  5779 I jxcore-log: ok 52 should be equal
09-30 05:37:59.754  5733  5779 I jxcore-log: 
09-30 05:37:59.755  5733  5779 I jxcore-log: ok 53 revs are equal
09-30 05:37:59.755  5733  5779 I jxcore-log: 
,09-30 05:37:59.917  5733  5779 I jxcore-log: ok 54 should be equal
09-30 05:37:59.917  5733  5779 I jxcore-log: 
09-30 05:37:59.917  5733  5779 I jxcore-log: ok 55 revs are equal
09-30 05:37:59.917  5733  5779 I jxcore-log: 
,09-30 05:38:00.121  5733  5779 I jxcore-log: ok 56 should be equal
09-30 05:38:00.121  5733  5779 I jxcore-log: 
,09-30 05:38:00.122  5733  5779 I jxcore-log: ok 57 revs are equal
09-30 05:38:00.122  5733  5779 I jxcore-log: 
,09-30 05:38:00.129  5733  5779 I jxcore-log: # teardown
09-30 05:38:00.129  5733  5779 I jxcore-log: 
,09-30 05:38:00.168  5733  5779 I jxcore-log: # setup
09-30 05:38:00.168  5733  5779 I jxcore-log: 
,09-30 05:38:00.569  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - rev got changed under us
09-30 05:38:00.569  5733  5779 I jxcore-log: 
,09-30 05:38:01.155  5733  5779 I jxcore-log: 2016-09-30 09:38:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
09-30 05:38:01.155  5733  5779 I jxcore-log: 
,09-30 05:38:01.156  5733  5779 I jxcore-log: ok 58 Our rev is old so we should fail
09-30 05:38:01.156  5733  5779 I jxcore-log: 
,09-30 05:38:01.159  5733  5779 I jxcore-log: # teardown
09-30 05:38:01.159  5733  5779 I jxcore-log: 
,09-30 05:38:01.193  5733  5779 I jxcore-log: # setup
09-30 05:38:01.193  5733  5779 I jxcore-log: 
,09-30 05:38:01.273  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - fail if stop is called
09-30 05:38:01.273  5733  5779 I jxcore-log: 
,09-30 05:38:01.372  5733  5779 I jxcore-log: ok 59 confirm stop caused failure
09-30 05:38:01.372  5733  5779 I jxcore-log: 
,09-30 05:38:01.388  5733  5779 I jxcore-log: # teardown
09-30 05:38:01.388  5733  5779 I jxcore-log: 
,09-30 05:38:01.412  5733  5779 I jxcore-log: # setup
09-30 05:38:01.412  5733  5779 I jxcore-log: 
,09-30 05:38:01.463  5733  5779 I jxcore-log: # #_doImmediateSeqUpdate - stop after get but before put fails right
09-30 05:38:01.463  5733  5779 I jxcore-log: 
,09-30 05:38:01.774  5733  5779 I jxcore-log: 2016-09-30 09:38:01 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
09-30 05:38:01.774  5733  5779 I jxcore-log: 
09-30 05:38:01.776  5733  5779 I jxcore-log: ok 60 stop caused us to fail
09-30 05:38:01.776  5733  5779 I jxcore-log: 
,09-30 05:38:01.776  5733  5779 I jxcore-log: ok 61 We specifically failed on a stop before put
09-30 05:38:01.776  5733  5779 I jxcore-log: 
,09-30 05:38:01.782  5733  5779 I jxcore-log: # teardown
09-30 05:38:01.782  5733  5779 I jxcore-log: 
,09-30 05:38:01.907  5733  5779 I jxcore-log: # setup
09-30 05:38:01.907  5733  5779 I jxcore-log: 
,09-30 05:38:01.970  5733  5779 I jxcore-log: # #update - fail if stop is called
09-30 05:38:01.970  5733  5779 I jxcore-log: 
,09-30 05:38:02.053  5733  5779 I jxcore-log: ok 62 failed due to stop
09-30 05:38:02.053  5733  5779 I jxcore-log: 
,09-30 05:38:02.054  5733  5779 I jxcore-log: ok 63 failed due to stop
09-30 05:38:02.054  5733  5779 I jxcore-log: 
,09-30 05:38:02.062  5733  5779 I jxcore-log: # teardown
09-30 05:38:02.062  5733  5779 I jxcore-log: 
,09-30 05:38:02.131  5733  5779 I jxcore-log: # setup
09-30 05:38:02.131  5733  5779 I jxcore-log: 
,09-30 05:38:02.172  5733  5779 I jxcore-log: # #update - set seq for first time
09-30 05:38:02.172  5733  5779 I jxcore-log: 
,09-30 05:38:02.667  5733  5779 I jxcore-log: ok 64 should be equal
09-30 05:38:02.667  5733  5779 I jxcore-log: 
,09-30 05:38:02.673  5733  5779 I jxcore-log: # teardown
09-30 05:38:02.673  5733  5779 I jxcore-log: 
,09-30 05:38:02.721  5733  5779 I jxcore-log: # setup
09-30 05:38:02.721  5733  5779 I jxcore-log: 
,09-30 05:38:02.791  5733  5779 I jxcore-log: # #update - Fail on bad seq value
09-30 05:38:02.791  5733  5779 I jxcore-log: 
,09-30 05:38:03.201  5733  5779 I jxcore-log: 2016-09-30 09:38:03 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
09-30 05:38:03.201  5733  5779 I jxcore-log: 
,09-30 05:38:03.204  5733  5779 I jxcore-log: ok 65 Expected bad seq error
09-30 05:38:03.204  5733  5779 I jxcore-log: 
,09-30 05:38:03.210  5733  5779 I jxcore-log: # teardown
09-30 05:38:03.210  5733  5779 I jxcore-log: 
,09-30 05:38:03.254  5733  5779 I jxcore-log: # setup
09-30 05:38:03.254  5733  5779 I jxcore-log: 
,09-30 05:38:03.303  5733  5779 I jxcore-log: # #update - do we cancel timer properly on an immediate?
09-30 05:38:03.303  5733  5779 I jxcore-log: 
,09-30 05:38:03.714   930  3013 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:38:04.850  5733  5779 I jxcore-log: ok 66 Different promises
09-30 05:38:04.850  5733  5779 I jxcore-log: 
,09-30 05:38:04.853  5733  5779 I jxcore-log: ok 67 Timer was cancelled
09-30 05:38:04.853  5733  5779 I jxcore-log: 
,09-30 05:38:04.994  5733  5779 I jxcore-log: ok 68 should be equal
09-30 05:38:04.994  5733  5779 I jxcore-log: 
,09-30 05:38:05.001  5733  5779 I jxcore-log: # teardown
09-30 05:38:05.001  5733  5779 I jxcore-log: 
,09-30 05:38:05.512  5733  5779 I jxcore-log: # setup
09-30 05:38:05.512  5733  5779 I jxcore-log: 
,09-30 05:38:05.897  5733  5779 I jxcore-log: # #update - do we wait for blocked update
09-30 05:38:05.897  5733  5779 I jxcore-log: 
,09-30 05:38:06.104  5733  5779 I jxcore-log: ok 69 One go and one blocked
09-30 05:38:06.104  5733  5779 I jxcore-log: 
,09-30 05:38:06.104  5733  5779 I jxcore-log: ok 70 All blocked
09-30 05:38:06.104  5733  5779 I jxcore-log: 
09-30 05:38:06.105  5733  5779 I jxcore-log: ok 71 Still blocked
09-30 05:38:06.105  5733  5779 I jxcore-log: 
,09-30 05:38:06.306   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:06.512  5733  5779 I jxcore-log: ok 72 should be equal
09-30 05:38:06.512  5733  5779 I jxcore-log: 
,09-30 05:38:06.519  5733  5779 I jxcore-log: # teardown
09-30 05:38:06.519  5733  5779 I jxcore-log: 
,09-30 05:38:07.307   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:07.366  5733  5779 I jxcore-log: # setup
09-30 05:38:07.366  5733  5779 I jxcore-log: 
,09-30 05:38:08.309   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:08.349  5733  5779 I jxcore-log: # #update - test that we wait long enough
09-30 05:38:08.349  5733  5779 I jxcore-log: 
,09-30 05:38:09.310   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:10.145  5733  5779 I jxcore-log: ok 73 We waited long enough
09-30 05:38:10.145  5733  5779 I jxcore-log: 
,09-30 05:38:10.277  5733  5779 I jxcore-log: ok 74 should be equal
09-30 05:38:10.277  5733  5779 I jxcore-log: 
,09-30 05:38:10.284  5733  5779 I jxcore-log: # teardown
09-30 05:38:10.284  5733  5779 I jxcore-log: 
,09-30 05:38:10.311   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:11.312   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-30 05:38:22.119   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:38:25.140   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:38:26.313   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:27.314   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:28.316   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:29.317   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:30.318   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:31.319   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,09-30 05:38:43.313   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:38:43.716   930  3013 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:38:46.345   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:38:49.379   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:38:51.321   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:52.322   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:52.415   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:38:53.324   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:54.325   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:55.327   604   604 I ServiceManager: Waiting for service AtCmdFwd...
,09-30 05:38:56.328   604   604 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-30 05:38:58.484   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:39:01.516   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:39:03.720   930  3013 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-30 05:39:07.575   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:39:10.305  5733  5779 I jxcore-log: 2016-09-30 09:39:10 - ERROR CoordinatedClient: 'unexpected error: 'TimeoutError', stack: 'TimeoutError: 
09-30 05:39:10.305  5733  5779 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-30 05:39:10.305  5733  5779 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-30 05:39:10.305  5733  5779 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-30 05:39:10.305  5733  5779 I jxcore-log:     at $9@timers.js:120:1
09-30 05:39:10.305  5733  5779 I jxcore-log: ''
09-30 05:39:10.305  5733  5779 I jxcore-log: 
,09-30 05:39:10.308  5733  5779 I jxcore-log: 2016-09-30 09:39:10 - DEBUG CoordinatedClient: 'test client failed'
09-30 05:39:10.308  5733  5779 I jxcore-log: 
,09-30 05:39:10.316  5733  5779 I jxcore-log: 2016-09-30 09:39:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
09-30 05:39:10.316  5733  5779 I jxcore-log: 
,09-30 05:39:10.320  5733  5779 I jxcore-log: 2016-09-30 09:39:10 - ERROR CoordinatedThaliTape: 'tests failed, error: 'TimeoutError', stack: 'TimeoutError: 
09-30 05:39:10.320  5733  5779 I jxcore-log:     at SubError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
09-30 05:39:10.320  5733  5779 I jxcore-log:     at module.exports/afterTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
09-30 05:39:10.320  5733  5779 I jxcore-log:     at timeoutTimeout@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
09-30 05:39:10.320  5733  5779 I jxcore-log:     at $9@timers.js:120:1
09-30 05:39:10.320  5733  5779 I jxcore-log: ''
09-30 05:39:10.320  5733  5779 I jxcore-log: 
09-30 05:39:10.321  5733  5779 I jxcore-log: 2016-09-30 09:39:10 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
09-30 05:39:10.321  5733  5779 I jxcore-log: 
,09-30 05:39:10.606   930  3015 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-30 05:39:10.934  6125  6125 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-30 05:39:10.958  6125  6125 D AndroidRuntime: CheckJNI is OFF
,09-30 05:39:10.986  6125  6125 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-30 05:39:11.025  6125  6125 I Radio-JNI: register_android_hardware_Radio DONE
,09-30 05:39:11.043  6125  6125 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-30 05:39:11.054   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-30 05:39:11.055   930   943 I ActivityManager: Killing 5733:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-30 05:39:11.164   930  3898 I WindowState: WIN DEATH: Window{d299cd9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-30 05:39:11.164   930  3014 D WifiService: Client connection lost with reason: 4
,09-30 05:39:11.165   930  4002 D GraphicsStats: Buffer count: 2
,09-30 05:39:11.202   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-30 05:39:11.203   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-30 05:39:11.204   930   943 E ActivityManager: Failure starting process com.test.thalitest
09-30 05:39:11.204   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-30 05:39:11.204   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.204   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.204   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 05:39:11.204   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-30 05:39:11.204   930   943 I ActivityManager:   Force finishing activity ActivityRecord{3f577f2 u0 com.test.thalitest/.MainActivity t2}
,09-30 05:39:11.206   930   953 I art     : Starting a blocking GC Explicit
,09-30 05:39:11.211   930  3223 W ActivityManager: Spurious death for ProcessRecord{8e0196c 0:com.test.thalitest/u0a77}, curProc for 5733: null
,09-30 05:39:11.215   930   948 W WindowManager: Attempted to add application window with unknown token Token{13bfe43 ActivityRecord{3f577f2 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-30 05:39:11.215   930   948 W WindowManager: Token{13bfe43 ActivityRecord{3f577f2 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{13bfe43 ActivityRecord{3f577f2 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-30 05:39:11.216   930   948 W WindowManager: view not successfully added to wm, removing view
,09-30 05:39:11.216   930   948 W WindowManager: Exception when adding starting window
09-30 05:39:11.216   930   948 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{aa7e617 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-30 05:39:11.216   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-30 05:39:11.216   930   948 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-30 05:39:11.216   930   948 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-30 05:39:11.216   930   948 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-30 05:39:11.216   930   948 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-30 05:39:11.216   930   948 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.216   930   948 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.216   930   948 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-30 05:39:11.216   930   948 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-30 05:39:11.296   930   953 I art     : Explicit concurrent mark sweep GC freed 92287(6MB) AllocSpace objects, 46(1744KB) LOS objects, 33% free, 29MB/43MB, paused 1.423ms total 90.369ms
,09-30 05:39:11.316   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-30 05:39:11.319  6125  6125 I art     : System.exit called, status: 0
,09-30 05:39:11.319  6125  6125 I AndroidRuntime: VM exiting with result code 0.
,09-30 05:39:11.333   930   953 I ActivityManager: Start proc 6135:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,09-30 05:39:11.334   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-30 05:39:11.341   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-30 05:39:11.345  6011  6011 D BluetoothMapAppObserver: onReceive
09-30 05:39:11.345  6011  6011 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-30 05:39:11.352  4173  4223 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-30 05:39:11.353   930  3005 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-30 05:39:11.375  3720  3720 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-30 05:39:11.390  3720  6149 I Keyboard.Facilitator.DecoderInitializer: run()
,09-30 05:39:11.395  3815  3815 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-30 05:39:11.413  3720  6149 I Decoder : createOrResetDecoder
,09-30 05:39:11.409    29    29 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 05:39:11.416   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-30 05:39:11.413    29    29 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,--------- beginning of crash
09-30 05:39:11.435  3459  3487 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-30 05:39:11.435  3459  3487 E AndroidRuntime: Process: android.process.acore, PID: 3459
09-30 05:39:11.435  3459  3487 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.435  3459  3487 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 05:39:11.436  3625  3625 I ConfigService: onCreate
,09-30 05:39:11.438  3836  3975 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-30 05:39:11.429    29    29 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-30 05:39:11.460   930  4001 I ActivityManager: Start proc 6152:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,09-30 05:39:11.461  3836  3975 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-30 05:39:11.461  3836  3975 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3836
09-30 05:39:11.461  3836  3975 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.461  3836  3975 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-30 05:39:11.473   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 05:39:11.472   930  6164 E DropBoxManagerService: Can't write: system_app_crash
09-30 05:39:11.472   930  6164 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-30 05:39:11.472   930  6164 E DropBoxManagerService: 	... 5 more
,09-30 05:39:11.476  3836  3975 I Process : Sending signal. PID: 3836 SIG: 9
,09-30 05:39:11.485  3720  6149 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-30 05:39:11.512  3625  3625 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-30 05:39:11.513  3625  3625 D AndroidRuntime: Shutting down VM
09-30 05:39:11.514  3625  3625 E AndroidRuntime: FATAL EXCEPTION: main
09-30 05:39:11.514  3625  3625 E AndroidRuntime: Process: com.google.process.gapps, PID: 3625
09-30 05:39:11.514  3625  3625 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-30 05:39:11.514  3625  3625 E AndroidRuntime: 	... 8 more
,09-30 05:39:11.525  3625  3625 I Process : Sending signal. PID: 3625 SIG: 9
,09-30 05:39:11.526  3459  6150 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-30 05:39:11.567  3459  3487 I Process : Sending signal. PID: 3459 SIG: 9
,09-30 05:39:11.571   930  3014 D WifiService: Client connection lost with reason: 4
,09-30 05:39:11.571  3720  3720 W GmsClient: service died
,09-30 05:39:11.576   930  3218 I WindowState: WIN DEATH: Window{577dea1 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-30 05:39:11.576   930  3476 I ActivityManager: Process com.google.process.gapps (pid 3625) has died
09-30 05:39:11.575   930  3004 W InputDispatcher: channel '577dea1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-30 05:39:11.576   930  3898 D GraphicsStats: Buffer count: 1
09-30 05:39:11.577   930  3004 E InputDispatcher: channel '577dea1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,09-30 05:39:11.577   930  3218 W InputDispatcher: Attempted to unregister already unregistered input channel '577dea1 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-30 05:39:11.579   930  3476 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-30 05:39:11.580   930  3476 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 11000ms
09-30 05:39:11.580   930  3476 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
09-30 05:39:11.580   930  3476 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,09-30 05:39:11.592   930  3223 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3836) has died
09-30 05:39:11.592   930  3223 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 40987ms
,09-30 05:39:11.594   930  3223 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 05:39:11.600   378   378 E lowmemorykiller: Error writing /proc/3459/oom_score_adj; errno=22
,09-30 05:39:11.614   930   943 I ActivityManager: Start proc 6173:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 05:39:11.635   930  4001 I ActivityManager: Start proc 6186:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-30 05:39:11.669  6186  6186 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,09-30 05:39:11.670  6173  6173 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:39:11.670  6173  6173 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-30 05:39:11.670  6173  6173 D AndroidRuntime: Shutting down VM
09-30 05:39:11.677  6173  6173 E AndroidRuntime: FATAL EXCEPTION: main
09-30 05:39:11.677  6173  6173 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6173
09-30 05:39:11.677  6173  6173 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 05:39:11.677  6173  6173 E Andr,oidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 05:39:11.677  6173  6173 E AndroidRuntime: 	... 10 more
09-30 05:39:11.679   930  3476 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-30 05:39:11.680  6173  6173 I Process : Sending signal. PID: 6173 SIG: 9
09-30 05:39:11.682  6186  6186 I MultiDex: VM with version 2.1.0 has multidex support
09-30 05:39:11.682  6186  6186 I MultiDex: install
09-30 05:39:11.683  6186  6186 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-30 05:39:11.689  6186  6186 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm64
09-30 05:39:11.694  6186  6186 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:39:11.696  6186  6186 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:39:11.696  6186  6186 D AndroidRuntime: Shutting down VM
09-30 05:39:11.697  6186  6186 E AndroidRuntime: FATAL EXCEPTION: main
09-30 05:39:11.697  6186  6186 E AndroidRuntime: Process: com.google.process.gapps, PID: 6186
09-30 05:39:11.697  6186  6186 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 05:39:11.697  6186  6186 E AndroidRuntime: 	... 10 more
09-30 05:39:11.700  6186  6186 I Process : Sending signal. PID: 6186 SIG: 9
09-30 05:39:11.717   930  3898 I ActivityManager: Process com.google.process.gapps (pid 6186) has died
09-30 05:39:11.717   930  3898 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{e65028a u0 com.google.android.gms/.config.ConfigService}
09-30 05:39:11.717   930  3898 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{ca08ea3 u0 com.google.android.gms/.tapandpay.hce.service.TpHceService}
09-30 05:39:11.717   930  3898 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{7f5773b u0 com.google.android.gms/.gcm.GcmService}
09-30 05:39:11.717   930  3898 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{4a2a4d8 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
,09-30 05:39:11.718   930  3223 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6173) has died
09-30 05:39:11.720   930  3223 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-30 05:39:11.734   930   943 I ActivityManager: Start proc 6200:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 05:39:11.778  6200  6200 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:39:11.778  6200  6200 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:39:11.778  6200  6200 D AndroidRuntime: Shutting down VM
,09-30 05:39:11.787  6200  6200 E AndroidRuntime: FATAL EXCEPTION: main
09-30 05:39:11.787  6200  6200 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6200
09-30 05:39:11.787  6200  6200 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
09-30 05:39:11.787  6200  6200 E AndroidRuntime: 	... 10 more
09-30 05:39:11.790   930   941 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-30 05:39:11.791  6200  6200 I Process : Sending signal. PID: 6200 SIG: 9
,09-30 05:39:11.808   930  3218 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6200) has died
,09-30 05:39:11.810   930  3218 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-30 05:39:11.827   930   943 I ActivityManager: Start proc 6213:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-30 05:39:11.838   380   483 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
