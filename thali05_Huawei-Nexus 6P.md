#### Test 861743796628be0_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 06:41:58.353   928  5080 D NetlinkSocketObserver: NeighborEvent{elapsedMs=183517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 06:41:58.809  5328  5328 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 06:41:58.814  5328  5328 D AndroidRuntime: CheckJNI is OFF
09-23 06:41:58.839  5328  5328 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 06:41:58.870  5328  5328 I Radio-JNI: register_android_hardware_Radio DONE
09-23 06:41:58.886  5328  5328 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 06:41:58.889   928   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 06:41:58.945   928   938 I ActivityManager: Start proc 5337:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 06:41:58.956  5328  5328 D AndroidRuntime: Shutting down VM
,09-23 06:41:59.295   928  3451 I WindowManager: Screenshot max retries 4 of Token{4d79ade ActivityRecord{f1f8a19 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{80f6351 u0 Starting com.test.thalitest} drawState=4
,09-23 06:41:59.374  5337  5337 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 06:41:59.409  5337  5337 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 06:41:59.482  5337  5337 I LibraryLoader: Time to load native libraries: 65 ms (timestamps 4581-4646)
09-23 06:41:59.483  5337  5337 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 06:41:59.525  5337  5337 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a14e2a}
,09-23 06:41:59.526  5337  5337 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 06:41:59.526  5337  5337 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 06:41:59.532  5337  5337 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 06:41:59.534  5337  5337 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 06:41:59.583  5337  5337 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 06:41:59.597  5337  5337 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 06:41:59.597  5337  5337 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 06:41:59.598  5337  5337 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 06:41:59.598  5337  5337 I Adreno  : Build Date                       : 12/06/15
09-23 06:41:59.598  5337  5337 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 06:41:59.598  5337  5337 I Adreno  : Local Branch                     : mybranch17112971
09-23 06:41:59.598  5337  5337 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 06:41:59.598  5337  5337 I Adreno  : Remote Branch                    : NONE
09-23 06:41:59.598  5337  5337 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 06:41:59.650   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4928bbc:true
,09-23 06:41:59.676   701   701 W Binder_3: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22462]" dev="sockfs" ino=22462 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:41:59.676   701   701 W Binder_3: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22462]" dev="sockfs" ino=22462 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 06:41:59.692  5337  5337 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 06:41:59.701  5337  5337 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 06:41:59.726   701   701 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30618]" dev="sockfs" ino=30618 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 06:41:59.726   701   701 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30618]" dev="sockfs" ino=30618 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 06:41:59.730  5337  5374 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 06:41:59.729  3053  3053 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22467]" dev="sockfs" ino=22467 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-23 06:41:59.729  3053  3053 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[22467]" dev="sockfs" ino=22467 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 06:41:59.737  5337  5361 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 06:41:59.767  5337  5374 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 06:41:59.850   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +552ms (total +928ms)
,09-23 06:41:59.881  5337  5337 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5337
,09-23 06:41:59.971  5337  5337 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 06:42:00.141  5337  5377 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -582219472
,09-23 06:42:00.148  5337  5377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 06:42:00.148  5337  5377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 06:42:00.148  5337  5377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 06:42:00.148  5337  5377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 06:42:00.148  5337  5377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 06:42:00.148  5337  5377 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a91353 added. We now have 1 listener(s)
,09-23 06:42:00.150  5337  5377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
09-23 06:42:00.151  5337  5377 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 06:42:00.151  5337  5377 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 06:42:00.151  5337  5377 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 06:42:00.153  5337  5377 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@846c58e added. We now have 1 listener(s)
09-23 06:42:00.154  5337  5377 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:42:00.159   928  2900 D WifiService: New client listening to asynchronous messages
,09-23 06:42:00.160  5337  5377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 06:42:00.160  5337  5377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 06:42:00.160  5337  5377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 06:42:00.160  5337  5377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 06:42:00.160  5337  5377 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 06:42:00.162  5337  5377 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:00.162  5337  5377 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 06:42:00.167  5337  5377 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:00.167  5337  5377 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:42:00.167  5337  5377 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 06:42:00.167  5337  5377 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 06:42:00.168  5337  5377 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 06:42:00.171  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:00.174  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:00.195  5337  5337 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 06:42:00.712  5337  5346 I art     : Background sticky concurrent mark sweep GC freed 77737(8MB) AllocSpace objects, 19(2MB) LOS objects, 27% free, 23MB/32MB, paused 1.480ms total 209.108ms
,09-23 06:42:00.802  5337  5383 W jxcore-log: Initializing JXcore engine
09-23 06:42:00.802  5337  5383 W jxcore-log: JXcore engine is ready
,09-23 06:42:00.846  5383  5383 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11939 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-23 06:42:00.846  5383  5383 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16444]" dev="sockfs" ino=16444 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-23 06:42:00.846  5383  5383 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 06:42:00.846  5383  5383 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[30594]" dev="sockfs" ino=30594 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 06:42:00.858  5337  5383 W jxcore-log: Starting JXcore engine
,09-23 06:42:00.912  5337  5383 W jxcore-log: Platform android
09-23 06:42:00.912  5337  5383 W jxcore-log: 
,09-23 06:42:00.912  5337  5383 W jxcore-log: Process ARCH arm
09-23 06:42:00.912  5337  5383 W jxcore-log: 
,09-23 06:42:01.004  5337  5383 I jxcore-log: JXcore Cordova bridge is ready!
09-23 06:42:01.004  5337  5383 I jxcore-log: 
,09-23 06:42:01.004  5337  5383 W jxcore-log: JXcore engine is started
,09-23 06:42:01.015  5337  5377 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 06:42:01.022  5337  5337 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 06:42:04.200   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:42:05.201   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:42:06.202   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:42:07.203   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:42:07.693  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 06:42:07.693  5337  5383 I jxcore-log: 
,09-23 06:42:07.695  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 06:42:07.695  5337  5383 I jxcore-log: 
,09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:07.699  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:42:07.700  5337  5383 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:42:07.702  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 06:42:07.702  5337  5383 I jxcore-log: 
,09-23 06:42:07.703  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 06:42:07.703  5337  5383 I jxcore-log: 
,09-23 06:42:08.061  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:42:08.061  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@355015c added. We now have 2 listener(s)
09-23 06:42:08.061  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 06:42:08.062  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:42:08.062  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 06:42:08.062  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:42:08.062  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ac3cc65 added. We now have 2 listener(s)
09-23 06:42:08.062  5337  5383 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:42:08.062  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:42:08.064  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:08.068  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:42:08.069  5337  5383 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:08.069  5337  5383 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 06:42:08.069  5337  5383 D ExecuteNativeTests: Running unit tests
09-23 06:42:08.070  5337  5383 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 06:42:08.070   928  3437 D WifiService: setWifiEnabled: true pid=5337, uid=10077
09-23 06:42:08.070   928  3437 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:42:08.076  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:08.082  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:08.205   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:42:09.206   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 06:42:17.218   928  2899 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 06:42:18.075  5337  5383 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 06:42:18.146  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 06:42:18.146  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3835af added. We now have 3 listener(s)
09-23 06:42:18.147  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:18.147  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:42:18.147  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 06:42:18.147  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:42:18.147  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a45dbc added. We now have 3 listener(s)
09-23 06:42:18.148  5337  5383 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:42:18.149  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:42:18.152  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:18.156  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:42:18.157  5337  5383 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:42:18.157  5337  5383 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:42:18.164  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,09-23 06:42:18.164  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:18.164  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:42:18.164  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:18.164  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:18.164  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 06:42:18.165  5337  5383 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 06:42:18.165  5337  5383 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 06:42:18.165  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:42:18.165  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:18.165  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:18.165  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:18.166  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
09-23 06:42:18.166  5337  5383 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 06:42:18.167  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-23 06:42:18.169  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
09-23 06:42:18.169  5337  5383 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:42:18.170  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:18.170  5337  5383 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:42:18.171  5337  5383 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-23 06:42:18.171  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-23 06:42:18.171  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:18.171  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:42:18.171  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:42:18.171  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:42:18.172  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:42:18.172  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 06:42:18.172  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-23 06:42:18.172  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:42:18.172  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:42:18.173  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:18.173  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:42:18.173  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:42:18.174  5337  5383 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:42:18.174  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:42:18.176  5337  5386 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:18.176  4644  4644 W Binder_5: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[29544]" dev="sockfs" ino=29544 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:18.176  4644  4644 W Binder_5: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[29544]" dev="sockfs" ino=29544 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:18.180  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:42:18.182  5337  5386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 06:42:18.183  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:42:18.184  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:42:18.187  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:42:18.187  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:18.188  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-23 06:42:18.189  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:18.189  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-23 06:42:18.189  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:42:18.190  5337  5383 D BluetoothAdapter: STATE_ON
,09-23 06:42:18.193  4401  4418 D BtGatt.GattService: registerClient() - UUID=61821315-2a2b-45ac-bc94-c71275689e00
,09-23 06:42:18.194  4401  4474 D BtGatt.GattService: onClientRegistered() - UUID=61821315-2a2b-45ac-bc94-c71275689e00, clientIf=5
,09-23 06:42:18.197  5337  5347 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:42:18.200  4401  4476 D BtGatt.AdvertiseManager: message : 0
,09-23 06:42:18.202  4401  4476 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:42:18.218  4401  4474 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:42:18.225  4401  4474 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:42:18.226  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:42:18.226  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 06:42:18.227  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:42:18.228  5337  5383 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 06:42:18.228  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:18.228  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-23 06:42:18.228  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:42:18.228  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:42:18.229  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,09-23 06:42:18.229  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:42:18.232  5337  5337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:42:18.232  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:42:18.731  5337  5383 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 06:42:18.731  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 06:42:18.731  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 06:42:18.731  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 06:42:18.731  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 06:42:18.732  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 06:42:18.733  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-23 06:42:18.734  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 06:42:18.734  5337  5383 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 06:42:18.734  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 06:42:18.735  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 06:42:18.735  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 06:42:18.735  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 06:42:18.735  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:42:18.735  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:42:18.736  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:42:18.736  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:42:18.736  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-23 06:42:18.736  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:42:18.736  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:42:18.736  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:42:18.737  5337  5386 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 06:42:18.737  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:42:18.737  5337  5386 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:42:18.737  5337  5386 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:42:18.738  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:18.739  5337  5383 D BluetoothLeScanner: could not find callback wrapper
,09-23 06:42:18.739  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:42:18.739  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:42:18.740  4401  4476 D BtGatt.AdvertiseManager: message : 1
09-23 06:42:18.741  4401  4476 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:42:18.754  4401  4474 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:42:18.755  4401  4474 D BtGatt.GattService: Client app is not null!
09-23 06:42:18.756  4401  4643 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:42:18.759  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:42:18.759  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 06:42:18.759  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:42:18.759  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:42:18.759  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:42:18.762  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:18.762  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:42:18.763  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:42:18.764  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:42:18.766  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 06:42:18.766  5337  5337 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:42:18.767  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:42:18.767  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:18.768  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:18.768  5337  5337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:42:18.768  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:18.768  5337  5383 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:42:18.768  5337  5383 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:42:18.769  5337  5383 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
,09-23 06:42:18.769  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-23 06:42:18.769  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:18.769  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:42:18.769  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:42:18.769  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:18.770  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:42:18.771  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:42:18.772  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:42:18.772  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:42:18.772  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:42:18.772  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:42:18.772  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:18.772  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:42:18.775  5337  5389 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:18.773  4418  4418 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[31141]" dev="sockfs" ino=31141 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:18.779  5337  5389 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:42:18.773  4418  4418 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[31141]" dev="sockfs" ino=31141 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:18.789  5337  5383 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:42:18.789  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:42:18.794  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:42:18.795  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:42:18.795  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:42:18.797  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:42:18.798  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:18.798  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
09-23 06:42:18.798  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:18.798  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:18.798  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:42:18.799  5337  5383 D BluetoothAdapter: STATE_ON
,09-23 06:42:18.803  4401  4644 D BtGatt.GattService: registerClient() - UUID=1745d24b-2309-4871-b6e0-ac5ccfaee404
09-23 06:42:18.803  4401  4474 D BtGatt.GattService: onClientRegistered() - UUID=1745d24b-2309-4871-b6e0-ac5ccfaee404, clientIf=5
09-23 06:42:18.804  5337  5348 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 06:42:18.805  4401  4476 D BtGatt.AdvertiseManager: message : 0
09-23 06:42:18.809  4401  4476 D BtGatt.AdvertiseManager: starting multi advertising
09-23 06:42:18.822  4401  4474 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-23 06:42:18.830  4401  4474 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-23 06:42:18.831  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:42:18.831  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:42:18.833  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:42:18.834  5337  5383 I io.jxcore.node.ConnectionHelper: start: OK
09-23 06:42:18.834  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:18.834  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:42:18.835  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:42:18.835  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:42:18.835  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:42:18.835  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 06:42:18.839  5337  5337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:42:18.839  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:42:19.339  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,09-23 06:42:19.339  5337  5383 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
,09-23 06:42:19.340  5337  5383 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:42:19.340  5337  5383 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 06:42:19.340  5337  5383 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-23 06:42:19.340  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
,09-23 06:42:19.340  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 06:42:19.341  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 06:42:19.343  4401  4476 D BtGatt.AdvertiseManager: message : 1
09-23 06:42:19.345  4401  4476 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:42:19.361  4401  4474 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:42:19.361  4401  4474 D BtGatt.GattService: Client app is not null!
,09-23 06:42:19.363  4401  4644 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:42:19.363  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:42:19.364  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 06:42:19.364  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 06:42:19.364  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:42:19.364  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:19.364  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,09-23 06:42:19.364  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-23 06:42:19.365  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:19.365  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:42:19.366  5337  5383 D BluetoothAdapter: STATE_ON
,09-23 06:42:19.371  4401  4643 D BtGatt.GattService: registerClient() - UUID=1df3392d-807e-4964-9d25-f0efcf85c55a
,09-23 06:42:19.374  4401  4474 D BtGatt.GattService: onClientRegistered() - UUID=1df3392d-807e-4964-9d25-f0efcf85c55a, clientIf=5
09-23 06:42:19.374  5337  5347 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:42:19.376  4401  4476 D BtGatt.AdvertiseManager: message : 0
09-23 06:42:19.380  4401  4476 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:42:19.394  4401  4474 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:42:19.402  4401  4474 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:42:19.403  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 06:42:19.403  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:42:19.403  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:42:19.403  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 06:42:19.403  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 06:42:19.403  5337  5383 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 06:42:19.403  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:42:19.404  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:42:19.404  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-23 06:42:19.404  5337  5383 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 06:42:19.405  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 06:42:19.405  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 06:42:19.405  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:42:19.405  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:42:19.405  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 06:42:19.405  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:42:19.405  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:42:19.406  5337  5389 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 06:42:19.406  5337  5389 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:42:19.406  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:42:19.406  5337  5389 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:42:19.406  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:42:19.406  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:42:19.406  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-23 06:42:19.406  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:42:19.406  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:42:19.407  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:19.408  5337  5383 D BluetoothLeScanner: could not find callback wrapper
,09-23 06:42:19.408  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:42:19.408  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:42:19.409  4401  4476 D BtGatt.AdvertiseManager: message : 1
09-23 06:42:19.409  4401  4476 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:42:19.418  4401  4474 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 06:42:19.419  4401  4474 D BtGatt.GattService: Client app is not null!
,09-23 06:42:19.420  4401  4644 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:42:19.421  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:42:19.421  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:42:19.421  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 06:42:19.421  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:42:19.421  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 06:42:19.423  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:42:19.423  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:42:19.423  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 06:42:19.424  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:42:19.425  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 06:42:19.425  5337  5337 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:42:19.426  5337  5337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:42:19.426  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:19.426  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:19.426  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:42:19.427  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-23 06:42:19.428  5337  5383 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-23 06:42:19.429  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
09-23 06:42:19.430  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-23 06:42:19.432  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
,09-23 06:42:19.432  5337  5383 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-23 06:42:19.433  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-23 06:42:19.434  5337  5383 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-23 06:42:19.434  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-23 06:42:19.435  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-23 06:42:19.435  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:19.435  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:19.435  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:19.435  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:42:19.435  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:19.435  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:19.435  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:19.435  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 06:42:19.435  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:19.436  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:19.436  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 06:42:19.436  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-23 06:42:19.437  5337  5383 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-23 06:42:19.437  5337  5383 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 06:42:19.437  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 06:42:19.440  5337  5383 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-23 06:42:19.440  5337  5383 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-23 06:42:19.440  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 06:42:19.440  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 06:42:19.441  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections:, Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 06:42:19.442  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 06:42:19.442  5337  5383 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-23 06:42:19.442  5337  5383 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:42:19.443  5337  5383 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-23 06:42:19.443  5337  5383 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:42:19.443  5337  5383 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:42:19.443  5337  5383 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-23 06:42:19.443  5337  5383 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:42:19.443  5337  5383 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 06:42:19.443  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-23 06:42:19.449  4418  4418 W Binder_1: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[30644]" dev="sockfs" ino=30644 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:19.449  4418  4418 W Binder_1: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[30644]" dev="sockfs" ino=30644 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:42:19.447  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-23 06:42:19.447  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-23 06:42:19.448  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-23 06:42:19.448  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-23 06:42:19.448  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-23 06:42:19.448  5337  5383 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-23 06:42:19.448  5337  5383 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 06:42:19.449  5337  5383 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-23 06:42:19.449  5337  5393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 129)
09-23 06:42:19.450  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-23 06:42:19.450  5337  5393 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-23 06:42:19.450  5337  5393 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:19.450  5337  5383 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-23 06:42:19.452  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-23 06:42:19.452  5337  5383 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-23 06:42:19.453  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-23 06:42:19.453  5337  5383 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-23 06:42:19.453  5337  5383 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-23 06:42:19.453  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:42:19.453  5337  5383 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-23 06:42:19.453  5337  5383 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 06:42:19.453  5337  5383 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-23 06:42:19.453  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:42:19.453  5337  5383 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-23 06:42:19.453  5337  5383 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 06:42:19.453  5337  5383 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 06:42:19.453  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:42:19.453  5337  5383 W io.jxcore.node.ConnectionHel,per: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-23 06:42:19.454  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-23 06:42:19.454  5337  5383 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 06:42:19.454  5337  5383 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 06:42:19.454  5337  5383 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-23 06:42:19.454  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-23 06:42:19.455  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:19.455  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:42:19.455  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:42:19.455  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:19.456  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:42:19.457  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:42:19.457  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:42:19.457  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:42:19.457  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:42:19.457  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:19.457  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:42:19.457  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-23 06:42:19.460  5337  5394 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:19.460  5337  5383 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 06:42:19.460  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 06:42:19.462  5337  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 06:42:19.456  4635  4635 W Binder_3: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[31933]" dev="sockfs" ino=31933 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:42:19.456  4635  4635 W Binder_3: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[31933]" dev="sockfs" ino=31933 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:42:19.464  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:42:19.465  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:42:19.465  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:42:19.466  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:42:19.467  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:19.467  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-23 06:42:19.467  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:19.467  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:19.467  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:42:19.467  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:19.469  4401  4420 D BtGatt.GattService: registerClient() - UUID=2186e206-a96f-439c-b372-ff8e12fed8f6
09-23 06:42:19.470  4401  4474 D BtGatt.GattService: onClientRegistered() - UUID=2186e206-a96f-439c-b372-ff8e12fed8f6, clientIf=5
09-23 06:42:19.470  5337  5347 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:42:19.471  4401  4476 D BtGatt.AdvertiseManager: message : 0
,09-23 06:42:19.473  4401  4476 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:42:19.482  4401  4474 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:42:19.487  4401  4474 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:42:19.488  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:42:19.488  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 06:42:19.489  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:42:19.490  5337  5383 I io.jxcore.node.ConnectionHelper: start: OK
09-23 06:42:19.490  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 06:42:19.491  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:42:19.491  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:42:19.491  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:42:19.491  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:42:19.491  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:42:19.493  5337  5337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:42:19.493  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:42:19.991  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 06:42:19.991  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:42:19.991  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:42:19.991  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 06:42:19.992  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:42:19.992  5337  5394 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:42:19.992  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:42:19.992  5337  5394 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-23 06:42:19.992  5337  5394 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:42:19.992  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 06:42:19.993  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-23 06:42:19.994  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:42:19.994  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:42:19.995  5337  5337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:42:19.995  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3835af removed from the list
09-23 06:42:19.995  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 06:42:19.995  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:42:19.995  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:42:19.995  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:42:19.996  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:42:19.996  5337  5395 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 129
09-23 06:42:19.997  5337  5395 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 129)
09-23 06:42:19.997  4401  4633 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-23 06:42:19.998  5337  5395 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 129)
09-23 06:42:19.998  5337  5393 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 129)
09-23 06:42:19.999  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:19.999  5337  5383 D BluetoothLeScanner: could not find callback wrapper
,09-23 06:42:19.999  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:42:20.012  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-23 06:42:20.015  4401  4476 D BtGatt.AdvertiseManager: message : 1
,09-23 06:42:20.016  4401  4476 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:42:20.023  4401  4474 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:42:20.023  4401  4474 D BtGatt.GattService: Client app is not null!
09-23 06:42:20.024  4401  4418 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:42:20.024  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 06:42:20.025  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:42:20.025  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:42:20.025  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:42:20.025  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 06:42:20.027  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:20.027  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:42:20.027  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 06:42:20.027  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 06:42:20.028  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a45dbc removed from the list
09-23 06:42:20.028  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:20.029  5337  5383 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:42:20.029  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:20.029  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:42:20.029  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:20.031  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
09-23 06:42:20.032  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:42:20.032  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:42:20.033  4644  4644 W Binder_5: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[29557]" dev="sockfs" ino=29557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:20.033  4644  4644 W Binder_5: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[29557]" dev="sockfs" ino=29557 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:42:20.033  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 06:42:20.033  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:42:20.033  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:42:20.033  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:42:20.033  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:42:20.033  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:42:20.034  5337  5396 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:20.035  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
,09-23 06:42:20.035  5337  5383 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-23 06:42:20.036  5337  5383 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 06:42:20.036  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 06:42:20.036  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:20.036  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 06:42:20.036  5337  5396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:42:20.037  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,09-23 06:42:20.041  5337  5383 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,09-23 06:42:20.043  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 06:42:20.043  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:42:20.043  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:42:20.043  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:42:20.043  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:42:20.043  5337  5396 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:42:20.043  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:42:20.043  5337  5396 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 06:42:20.043  5337  5396 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:42:20.044  5337  5383 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c3835af not in the list
,09-23 06:42:20.044  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:42:20.044  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 06:42:20.044  5337  5337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:42:20.044  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:42:20.044  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:42:20.044  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:42:20.044  5337  5383 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 06:42:20.044  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 06:42:20.047  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:42:20.047  5337  5383 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a45dbc not in the list
09-23 06:42:20.047  5337  5383 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:42:20.047  5337  5383 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 06:42:20.047  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:20.047  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:42:20.047  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:20.048  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:42:20.050  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,09-23 06:42:20.050  5337  5383 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-23 06:42:20.050  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:42:20.051  5337  5383 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-23 06:42:20.051  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 06:42:20.051  5337  5383 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-23 06:42:20.051  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 06:42:20.051  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
09-23 06:42:20.052  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,09-23 06:42:20.054  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
,09-23 06:42:20.054  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 06:42:20.054  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-23 06:42:20.054  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-23 06:42:20.055  5337  5383 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-23 06:42:20.055  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 06:42:20.055  5337  5383 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-23 06:42:20.055  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 06:42:20.055  5337  5383 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-23 06:42:20.055  5337  5383 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-23 06:42:20.055  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-23 06:42:20.056  5337  5383 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-23 06:42:20.056  5337  5383 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-23 06:42:20.056  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-23 06:42:20.056  5337  5383 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-23 06:42:20.056  5337  5383 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-23 06:42:20.056  5337  5383 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-23 06:42:20.056  5337  5383 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-23 06:42:20.057  5337  5383 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
09-23 06:42:20.057  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 06:42:20.057  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b98adec added. We now have 3 listener(s)
09-23 06:42:20.058  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:20.059  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:42:20.059  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:42:20.059  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:42:20.059  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58825b5 added. We now have 3 listener(s)
09-23 06:42:20.059  5337  5383 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 06:42:20.059  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:42:20.062  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:20.066  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:42:20.068  5337  5383 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:42:20.068  5337  5383 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:42:20.070  5337  5383 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 06:42:20.070   928  3427 D WifiService: setWifiEnabled: true pid=5337, uid=10077
09-23 06:42:20.070   928  3427 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:42:20.070  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:20.072  5337  5383 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,09-23 06:42:20.074  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:20.075  5337  5383 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
09-23 06:42:20.075  5337  5383 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-23 06:42:20.079   928  3464 D WifiService: setWifiEnabled: false pid=5337, uid=10077
,09-23 06:42:20.079   928  3464 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:42:20.081   928  2899 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-23 06:42:20.081   928  2899 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-23 06:42:20.082   928  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 06:42:20.082   928  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:42:20.089   928  5081 D DhcpClient: Clearing IP address
,09-23 06:42:20.089   508   927 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:42:20.097   508   927 D CommandListener: Setting iface cfg
,09-23 06:42:20.105  3528  5136 V NativeCrypto: Read error: ssl=0x7f9074d980: I/O error during system call, Connection timed out
,09-23 06:42:20.106   928  5082 D DhcpClient: Receive thread stopped
09-23 06:42:20.107  3528  5136 V NativeCrypto: SSL shutdown failed: ssl=0x7f9074d980: I/O error during system call, Broken pipe
,09-23 06:42:20.108   928  3427 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,09-23 06:42:20.109   928  5079 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,09-23 06:42:20.111   928  5079 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-23 06:42:20.113   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
09-23 06:42:20.113   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 06:42:20.116   928  2901 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 06:42:20.116   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-23 06:42:20.116   534   534 E Parcel  : Reading a NULL string not supported here.
09-23 06:42:20.116   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-23 06:42:20.118   928   928 D RttService: SCAN_AVAILABLE : 1
,09-23 06:42:20.119   928  3009 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 06:42:20.122   928  2901 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-23 06:42:20.125  3414  3589 W QCNEJ   : |CORE| network lost: 100
09-23 06:42:20.126  3414  3589 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-23 06:42:20.132   928  2899 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-23 06:42:20.148   928  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 06:42:20.151   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:42:20.174   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:42:20.174   508   927 D CommandListener: Clearing all IP addresses on wlan0
09-23 06:42:20.174   508   927 D TetherController: Setting IP forward enable = 0
09-23 06:42:20.175   928  2901 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-23 06:42:20.176   928  2901 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 06:42:20.178   928   945 D Tethering: MasterInitialState.processMessage what=3
,09-23 06:42:20.183   928  2899 D DhcpClient: doQuit
09-23 06:42:20.184   928  2899 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:42:20.184   928  5081 D DhcpClient: onQuitting
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:20.185  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:20.185  3550  3550 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 06:42:20.188  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:20.192  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:20.194  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:20.197  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:20.198  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:20.201  4783  4798 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 06:42:20.201  4783  4798 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 06:42:20.201  4783  4798 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,09-23 06:42:20.202  4783  4798 E SarControlService: no key has been found,reset the power
,09-23 06:42:20.202  4783  4823 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 06:42:20.202  4783  4823 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,09-23 06:42:20.202  4783  4823 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 06:42:20.203  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:42:20.203  4812  4812 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 06:42:20.204  4783  4823 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 06:42:20.204  4783  4823 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 06:42:20.204  4783  4823 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 06:42:20.206  3838  3838 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:20.207  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:20.209  3550  3550 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 06:42:20.209  3838  3838 D SystemUpdateService: onCreate
,09-23 06:42:20.210  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:42:20.210  4812  4812 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 06:42:20.210  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:20.212  3550  3550 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-23 06:42:20.213  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:20.214  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:20.215  4812  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9234ccc HexData = [00000000ea03000000000000ffffffff]
09-23 06:42:20.215  4812  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:42:20.215  4812  4826 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-23 06:42:20.215  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:42:20.215  4783  4795 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 06:42:20.216  3838  3838 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 06:42:20.224  4812  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9234ccc HexData = [00000000eb03000000000000ffffffff]
,09-23 06:42:20.224  4812  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:42:20.224  4812  4826 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
09-23 06:42:20.225  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:42:20.225  4783  4793 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 06:42:20.226  3838  3838 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-23 06:42:20.232  3838  5105 I iu.UploadsManager: num queued entries: 0
09-23 06:42:20.233  3838  5105 I iu.UploadsManager: num updated entries: 0
,09-23 06:42:20.233  3838  5105 I iu.SyncManager: NEXT; no task
,09-23 06:42:20.234  3838  5416 I SystemUpdateService: active receiver: enabled
,09-23 06:42:20.236  3838  3838 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-23 06:42:20.238  3838  3838 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 06:42:20.241  3838  5416 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 06:42:20.243   508   927 E Netd    : netlink response contains error (No such file or directory)
09-23 06:42:20.243  3838  5416 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-23 06:42:20.243  3838  5416 I SystemUpdateService: now status is 0 (complete)
,09-23 06:42:20.243  3838  5416 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 06:42:20.243  3838  5416 I SystemUpdateService: file has been verified
09-23 06:42:20.243  3838  5416 I SystemUpdateService: OTA package size = 21989297
09-23 06:42:20.243   928  2901 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 06:42:20.244   508   927 D TetherController: Setting IP forward enable = 0
,09-23 06:42:20.250   928  3343 I ActivityManager: Start proc 5420:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
09-23 06:42:20.251  3838  5416 I SystemUpdateService: showing system update notification
,09-23 06:42:20.263  3838  3838 D SystemUpdateService: onDestroy
,09-23 06:42:20.265  3550  3550 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 06:42:20.283  3550  3550 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 06:42:20.299  5420  5420 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,09-23 06:42:20.301  5420  5420 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 06:42:20.308  5420  5420 D SprintDMHelper: simOperator: 
09-23 06:42:20.308  5420  5420 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 06:42:20.320  4228  5433 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 06:42:20.333   928  3427 I ActivityManager: Start proc 5434:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-23 06:42:20.335   928  3427 I ActivityManager: Killing 4764:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-23 06:42:20.367  5434  5434 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-23 06:42:20.374   928  3053 I ActivityManager: Killing 4862:com.google.android.deskclock/u0a66 (adj 15): empty #17
,09-23 06:42:20.392  4228  4228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:42:20.393   928  2899 D wifi    : In wifi stop Hal
09-23 06:42:20.393   928  2899 D wifi    : halHandle = 0x7f7e4e7640, mVM = 0x7f9a60d140, mCls = 0x200b1a
09-23 06:42:20.393   928  3549 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-23 06:42:20.393   928  3549 D WifiHAL : Got a signal to exit!!!
09-23 06:42:20.393   928  3549 I WifiHAL : Exit wifi_event_loop
09-23 06:42:20.394   928  2899 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-23 06:42:20.394   928  2899 E WifiHAL : Event processing terminated
09-23 06:42:20.394   928  2899 D wifi    : In wifi cleaned up handler
09-23 06:42:20.394   928  2899 I WifiHAL : Internal cleanup completed
09-23 06:42:20.395  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:20.395  3389  3944 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:42:20.397  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:20.398  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:20.422   928  3549 D wifi    : set interface wlan0 flags (DOWN)
09-23 06:42:20.423   928  2899 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 06:42:20.548  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 06:42:20.585  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:20.587   928   938 D WifiService: setWifiEnabled: true pid=5337, uid=10077
09-23 06:42:20.587   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:42:20.628   928   945 D Tethering: InitialState.processMessage what=4
09-23 06:42:20.629   508   927 D SoftapController: Softap fwReload - Ok
,09-23 06:42:20.633   508   927 D CommandListener: Setting iface cfg
,09-23 06:42:20.634   508   927 D CommandListener: Trying to bring down wlan0
09-23 06:42:20.634   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-23 06:42:20.635   508   927 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:42:20.641   928  2899 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:42:21.093   928  3487 D WifiService: setWifiEnabled: true pid=5337, uid=10077
,09-23 06:42:21.094   928  3487 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:42:21.250   928  2899 D wifi    : set interface wlan0 flags (UP)
,09-23 06:42:21.251   928  2899 I WifiHAL : Initializing wifi
,09-23 06:42:21.251   928  2899 I WifiHAL : Creating socket
,09-23 06:42:21.256   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-23 06:42:21.260   928  2899 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-23 06:42:21.260   928  2899 D wifi    : Did set static halHandle = 0x7f7e4e7640
09-23 06:42:21.260   928  2899 D wifi    : halHandle = 0x7f7e4e7640, mVM = 0x7f9a60d140, mCls = 0x1017b2
09-23 06:42:21.260   928  2899 D wifi    : array field set
09-23 06:42:21.261   928  2899 I WifiNative-HAL: interface[0] = wlan0
09-23 06:42:21.263   928  5449 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547579917888
09-23 06:42:21.263   928  5449 D wifi    : waitForHalEvents called, vm = 0x7f9a60d140, obj = 0x1017b2, env = 0x7f7f12ea80
,09-23 06:42:21.346  5450  5450 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 06:42:21.364   928  2899 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 06:42:21.368  5450  5450 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:42:21.377  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:21.378  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:21.380  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:21.395  5450  5450 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:42:21.396  5450  5450 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 06:42:21.410   928  2899 D WifiConfigStore: Loading config and enabling all networks 
,09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:21.414  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:21.417  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:21.420  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:21.421   928  2899 D WifiConfigStore: loaded 0 passpoint configs
09-23 06:42:21.421   928  2899 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:42:21.421   928  2899 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 06:42:21.422  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:21.422   928  2899 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-23 06:42:21.423   928  2899 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:42:21.423   928  2899 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 06:42:21.423   928  2899 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 06:42:21.423   928  2899 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:21.425  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:21.426   928  2899 D WifiNative-HAL: Setting external_sim to 1
09-23 06:42:21.426   928  2899 D wifi    : setting dfs flag to true, 0x7f829efb20
09-23 06:42:21.427   928  2899 D WifiStateMachine: Setting OUI to DA-A1-19
,09-23 06:42:21.427   928  2899 D wifi    : setting scan oui 0x7f829efb20
09-23 06:42:21.427   928  2899 D WifiHAL : Sending mac address OUI
,09-23 06:42:21.428  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:21.430  4228  4228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:42:21.431   928  2899 E native  : do suspend false
,09-23 06:42:21.438   928  2899 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-23 06:42:21.438   508   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 06:42:21.438   928   928 D RttService: SCAN_AVAILABLE : 3
09-23 06:42:21.439   928  3009 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 06:42:21.439   508   927 D CommandListener: Setting iface cfg
,09-23 06:42:21.443   928  2884 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-23 06:42:21.443   928  2884 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 06:42:21.455   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=206619 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,09-23 06:42:21.456   928  2884 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 06:42:21.456   928  2884 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 06:42:21.600  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:21.612  4401  4470 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 06:42:21.613  4401  4470 D BluetoothAdapterProperties: Setting state to 13
09-23 06:42:21.613  4401  4470 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-23 06:42:21.614  4401  4470 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 06:42:21.617  4401  4470 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:42:21.619  4401  4401 D BluetoothMapService: onReceive
09-23 06:42:21.619  4401  4401 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:42:21.619  4401  4401 D BluetoothMapService: STATE_TURNING_OFF
09-23 06:42:21.619  4401  4401 D BluetoothMapService: MAP Service closeService in
09-23 06:42:21.619  4401  4401 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 06:42:21.620  4401  4401 D ObexServerSockets0: shutdown(block = true)
,09-23 06:42:21.620  4401  4401 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:42:21.621  4401  4401 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:42:21.621  4401  4646 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 06:42:21.621  4401  4647 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-23 06:42:21.621  4401  4633 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 06:42:21.625  4401  4401 I BtOppRfcommListener: stopping Accept Thread
09-23 06:42:21.626  4401  5029 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 06:42:21.627  4401  5029 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-23 06:42:21.629  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:21.629  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:21.631  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:21.631  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:21.636  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:21.636  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:21.638  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:21.638  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:21.643  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:21.643  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:21.644  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetoot,h is disabled - will return stored value
09-23 06:42:21.644  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:21.658   928   941 I ActivityManager: Start proc 5454:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-23 06:42:21.660  4401  4474 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:42:21.660  4401  4470 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 06:42:21.663  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:21.666  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:21.669  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:21.670  4401  4401 D HeadsetService: Received stop request...Stopping profile...
,09-23 06:42:21.675   928   928 D BluetoothHeadset: Proxy object disconnected
,09-23 06:42:21.676  3058  3069 D BluetoothHeadset: Proxy object disconnected
,09-23 06:42:21.676   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:21.676  3058  3058 D HeadsetProfile: Bluetooth service disconnected
09-23 06:42:21.676  4401  4401 D A2dpService: Received stop request...Stopping profile...
09-23 06:42:21.676  3448  3467 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:21.677  4401  4638 D A2dpStateMachine: Exit Disconnected: -1
09-23 06:42:21.677   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:21.678   928   928 D BluetoothA2dp: Proxy object disconnected
,09-23 06:42:21.678  3058  3058 D BluetoothA2dp: Proxy object disconnected
09-23 06:42:21.679  4401  4401 D HidService: Received stop request...Stopping profile...
09-23 06:42:21.680  4401  4401 D HidService: Stopping Bluetooth HidService
09-23 06:42:21.681  3058  3058 D BluetoothInputDevice: Proxy object disconnected
09-23 06:42:21.681  3058  3058 D HidProfile: Bluetooth service disconnected
09-23 06:42:21.681  4401  4401 D HealthService: Received stop request...Stopping profile...
,09-23 06:42:21.682  4401  4401 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:42:21.683  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:21.683  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:21.683  4401  4401 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:21.685  4401  4401 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 06:42:21.685  4401  4401 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 06:42:21.685  4401  4607 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 06:42:21.685  4401  4607 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 06:42:21.685  4401  4401 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:21.685  4401  4607 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:21.685  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:21.685  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:21.685  4401  4401 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:21.685  4401  4474 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 06:42:21.685  4401  4474 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 06:42:21.686  4401  4607 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:21.686  4401  4607 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:21.687  4401  4607 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:42:21.687  4401  4401 D PanService: Received stop request...Stopping profile...
09-23 06:42:21.687  4401  4607 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:42:21.687  4401  4607 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:42:21.687  4401  4607 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:42:21.687  4401  4474 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 06:42:21.688  4401  4401 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:21.688  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:21.688  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:21.688  4401  4401 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:21.689  3058  3058 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:42:21.689  3058  3058 D PanProfile: Bluetooth service disconnected
,09-23 06:42:21.689  4401  4401 D BluetoothMapService: Received stop request...Stopping profile...
09-23 06:42:21.689  4401  4401 D BluetoothMapService: stop()
09-23 06:42:21.690  4401  4401 D BluetoothMapAppObserver: deinitObservers()
09-23 06:42:21.690  4401  4401 D BluetoothMapAppObserver: removeReceiver()
09-23 06:42:21.692  3058  3058 D BluetoothMap: Proxy object disconnected
09-23 06:42:21.692  4401  4401 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 06:42:21.692  3058  3058 D MapProfile: Bluetooth service disconnected
09-23 06:42:21.692  4401  4401 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 06:42:21.692  4401  4474 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:42:21.692  4401  4401 D SapService: Received stop request...Stopping profile...
09-23 06:42:21.693  4401  4401 V SapService: stop()
,09-23 06:42:21.696  4401  4401 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:21.696  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:21.696  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:21.696  4401  4401 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:42:21.696  4401  4401 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 06:42:21.696  4401  4474 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-23 06:42:21.697  4401  4401 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-23 06:42:21.699  4401  4401 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:21.699  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:21.699  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:21.699  4401  4401 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:21.699  4401  4401 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 06:42:21.699  4401  4401 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 06:42:21.701  4401  4401 D BluetoothMapService: MAP Service closeService in
09-23 06:42:21.701  4401  4401 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:21.701  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:21.701  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:21.701  4401  4401 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:21.701  4401  4401 D BluetoothMapService: cleanup()
,09-23 06:42:21.701  4401  4401 D BluetoothMapService: MAP Service closeService in
09-23 06:42:21.702  4401  4401 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:21.702  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:21.702  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:21.702  4401  4401 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:21.702  4401  4470 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 06:42:21.702  4401  4470 D BluetoothAdapterProperties: Setting state to 15
09-23 06:42:21.702  4401  4470 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-23 06:42:21.703  4401  4470 I BluetoothAdapterState: Entering BleOnState
09-23 06:42:21.703  3448  3715 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:21.704   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:42:21.704   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:21.704  3058  3069 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:42:21.705  3058  3070 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:42:21.705   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:21.706  3058  3612 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:42:21.707  3058  3069 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-23 06:42:21.707  3058  3070 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:42:21.708  3058  3612 D BluetoothMap: onBluetoothStateChange: up=false
,09-23 06:42:21.709   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-23 06:42:21.709  4401  4470 D BluetoothAdapterState: Current state: BLE ON, message: 20
,09-23 06:42:21.709  4401  4470 D BluetoothAdapterProperties: Setting state to 16
,09-23 06:42:21.709  4401  4470 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-23 06:42:21.710  4401  4470 D BluetoothAdapterProperties: onBleDisable
09-23 06:42:21.710  4401  4470 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:42:21.710  4401  4471 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 06:42:21.711  4401  4607 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 06:42:21.711  4401  4607 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:21.712  4401  4474 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:42:21.713  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:21.713  5454  5454 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
09-23 06:42:21.714  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:21.719  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:21.720  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:21.721  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:21.723  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:21.730  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:42:21.739   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e95350:true
09-23 06:42:21.740  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:42:21.753   928   939 I ActivityManager: Start proc 5466:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-23 06:42:21.767  5454  5454 D LocalBluetoothProfileManager: Adding local MAP profile
,09-23 06:42:21.769  5454  5454 D BluetoothMap: Create BluetoothMap proxy object
,09-23 06:42:21.783  5454  5454 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-23 06:42:21.793  5466  5466 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-23 06:42:21.798  5454  5454 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:42:21.806   928  3437 I ActivityManager: Killing 5155:com.qualcomm.timeservice/1000 (adj 15): empty #17
,09-23 06:42:21.918  4401  4474 I bt_hci  : shut_down
,09-23 06:42:21.923  4401  4479 D bt_hwcfg: hw_epilog_process
,09-23 06:42:21.923  4401  4479 I bt_vendor: low_power_mode_cb
,09-23 06:42:21.926  4401  4479 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 06:42:21.926  4401  4479 I bt_vendor: epilog_cb
09-23 06:42:21.926  4401  4479 I bt_hci  : epilog_finished_callback
09-23 06:42:21.928  4401  4474 I bt_hci_h4: hal_close
09-23 06:42:21.928  4401  4474 I bt_userial_vendor: device fd = 54 close
,09-23 06:42:21.998  5466  5466 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.998  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:21.999  5466  5466 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:21.999  5466  5466 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(,ActivityThread.java:5422)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:21.999  5466  5466 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:21.999  5466  5466 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.k.d(PG:583)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:21.999  5466  5466 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:21.999  5466  5466 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:21.999  5466  5466 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 06:42:21.999  5466  5466 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 06:42:22.004  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 06:42:22.010  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:42:22.020  5454  5454 D DockEventReceiver: finishStartingService: stopping service
09-23 06:42:22.021   928   938 I ActivityManager: Killing 4484:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-23 06:42:22.052  4401  4471 D bt_stack_manager: event_shut_down_stack finished.
09-23 06:42:22.052  4401  4470 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 06:42:22.054  4401  4401 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:42:22.054  4401  4470 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 06:42:22.055  4401  4401 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 06:42:22.055  4401  4401 D BtGatt.GattService: stop()
09-23 06:42:22.055  4401  4401 D BtGatt.AdvertiseManager: advertise clients cleared
09-23 06:42:22.056  4401  4401 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:22.056  4401  4401 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:22.056  4401  4401 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:22.056  4401  4401 V BluetoothAdapterState: isBleTurningOff()=true
09-23 06:42:22.057  4401  4470 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 06:42:22.057  4401  4470 D BluetoothAdapterProperties: Setting state to 10
09-23 06:42:22.057  4401  4470 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 06:42:22.057  4401  4470 I BluetoothAdapterState: Entering OffState
09-23 06:42:22.058   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-23 06:42:22.064  4401  4401 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 06:42:22.064  4401  4401 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 06:42:22.065  4401  4401 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 06:42:22.065  4401  4471 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-23 06:42:22.070  4401  4401 I art     : System.exit called, status: 0
09-23 06:42:22.070  4401  4401 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 06:42:22.112  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:22.114   381   381 E lowmemorykiller: Error writing /proc/4401/oom_score_adj; errno=22
09-23 06:42:22.114   928   945 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,09-23 06:42:22.115   928   945 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 1308)
,09-23 06:42:22.115   928   945 W ActivityManager: Application dead when creating service ServiceRecord{c47d57b u0 com.android.bluetooth/.btservice.AdapterService}
,09-23 06:42:22.121   928   945 I ActivityManager: Process com.android.bluetooth (pid 4401) has died
09-23 06:42:22.122   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 1000ms
,09-23 06:42:22.122   928   945 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/.btservice.AdapterService in 4000ms
09-23 06:42:22.123   928   945 W ActivityManager: Exception when starting service com.android.bluetooth/.btservice.AdapterService
09-23 06:42:22.123   928   945 W ActivityManager: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:503)
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:928)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1531)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1435)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.am.ActiveServices.bindServiceLocked(ActiveServices.java:817)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.am.ActivityManagerService.bindService(ActivityManagerService.java:16010)
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1317)
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.app.ContextImpl.bindServiceAsUser(ContextImpl.java:1293)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.doBind(BluetoothManagerService.java:1588)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.handleEnable(BluetoothManagerService.java:1544)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService.-wrap7(BluetoothManagerService.java)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1215)
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:22.123   928   945 W ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:42:22.123   928   945 W ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 06:42:22.124   928   938 W ActivityManager: Spurious death for ProcessRecord{340253a 0:com.android.bluetooth/1002}, curProc for 4401: null
,09-23 06:42:22.237  5466  5489 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-23 06:42:22.248   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@194a3f1:true
,09-23 06:42:24.587  5450  5450 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:42:24.592  5450  5450 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:42:24.599  5450  5450 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 06:42:25.114   928   945 E BluetoothManagerService: MESSAGE_TIMEOUT_BIND
,09-23 06:42:25.157   928   945 I ActivityManager: Start proc 5500:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 06:42:25.243  5500  5500 D AdapterServiceConfig: Adding HeadsetService
09-23 06:42:25.244  5500  5500 D AdapterServiceConfig: Adding A2dpService
09-23 06:42:25.244  5500  5500 D AdapterServiceConfig: Adding HidService
09-23 06:42:25.244  5500  5500 D AdapterServiceConfig: Adding HealthService
09-23 06:42:25.244  5500  5500 D AdapterServiceConfig: Adding PanService
09-23 06:42:25.244  5500  5500 D AdapterServiceConfig: Adding GattService
09-23 06:42:25.244  5500  5500 D AdapterServiceConfig: Adding BluetoothMapService
09-23 06:42:25.244  5500  5500 D AdapterServiceConfig: Adding SapService
,09-23 06:42:25.258   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1dc1fae:true
,09-23 06:42:25.258  5500  5500 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 06:42:25.260  5500  5500 I bt_bluedroid: init
,09-23 06:42:25.261  5500  5512 I BluetoothAdapterState: Entering OffState
,09-23 06:42:25.262  5500  5513 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 06:42:25.263  5500  5513 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 06:42:25.263  5500  5513 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 06:42:25.263  5500  5513 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 06:42:25.263  5500  5500 I bt_bluedroid: get_profile_interface socket
,09-23 06:42:25.265  5500  5500 I bt_bluedroid: get_profile_interface sdp
,09-23 06:42:25.265  5500  5516 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
09-23 06:42:25.266  5500  5516 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:42:25.270  5500  5511 I bt_bluedroid: config_hci_snoop_log
,09-23 06:42:25.271   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 06:42:25.275  5500  5512 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 06:42:25.276  5500  5512 D BluetoothAdapterProperties: Setting state to 14
,09-23 06:42:25.276  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 06:42:25.277  5500  5512 D BluetoothBondStateMachine: make
,09-23 06:42:25.278  5500  5517 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 06:42:25.281  5500  5512 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:42:25.283  5500  5500 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 06:42:25.285  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:25.286  5500  5500 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 06:42:25.286  5500  5500 D BtGatt.GattService: Received start request. Starting profile...
09-23 06:42:25.287  5500  5500 D BtGatt.GattService: start()
09-23 06:42:25.287  5500  5500 I bt_bluedroid: get_profile_interface gatt
,09-23 06:42:25.288  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:25.288  5500  5500 D BtGatt.AdvertiseManager: advertise manager created
,09-23 06:42:25.293  5500  5500 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:42:25.293  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:25.293  5500  5500 V BluetoothAdapterState: isBleTurningOn()=true
09-23 06:42:25.293  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:25.293  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 06:42:25.295  5500  5512 I bt_bluedroid: bt_bluedroid
09-23 06:42:25.295  5500  5513 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 06:42:25.295  5500  5513 I bt_hci  : start_up
,09-23 06:42:25.300  5500  5513 I bt_vendor: alloc value 0xf3f88871
,09-23 06:42:25.300  5500  5513 I bt_vendor: init
09-23 06:42:25.300  5500  5513 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 06:42:25.300  5500  5513 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 06:42:25.410  5500  5513 D bt_hci  : start_up starting async portion
,09-23 06:42:25.410  5500  5520 I bt_hci  : event_finish_startup
09-23 06:42:25.410  5500  5520 I bt_hci_h4: hal_open
09-23 06:42:25.410  5500  5520 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 06:42:25.412  5500  5520 I bt_userial_vendor: device fd = 54 open
09-23 06:42:25.406  5521  5521 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:42:25.424  5500  5520 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:42:25.426  5500  5520 D bt_hwcfg: Chipset BCM4358A3
,09-23 06:42:25.426  5500  5520 D bt_hwcfg: Target name = [BCM4358A3]
09-23 06:42:25.426  5500  5520 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 06:42:25.633  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 06:42:25.825  5500  5520 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 06:42:25.825  5500  5520 D bt_hwcfg: Settlement delay -- 100 ms
09-23 06:42:25.825  5500  5520 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 06:42:25.949  5500  5520 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-23 06:42:25.949  5500  5520 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-23 06:42:25.951  5500  5520 I bt_hwcfg: vendor lib fwcfg completed
,09-23 06:42:25.951  5500  5520 I bt_vendor: firmware callback
09-23 06:42:25.951  5500  5520 I bt_hci  : firmware_config_callback
09-23 06:42:25.960  5500  5523 I bt_btu  : btu_task pending for preload complete event
,09-23 06:42:25.961  5500  5523 I bt_btu_task: Bluetooth chip preload is complete
,09-23 06:42:25.961  5500  5523 I bt_btu  : btu_task received preload complete event
,09-23 06:42:25.968  5500  5523 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 06:42:25.968  5500  5523 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 06:42:25.968  5500  5523 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 06:42:25.968  5500  5523 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-23 06:42:25.968  5500  5523 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 06:42:25.968  5500  5523 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_BTM
,09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_GAP
,09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_SDP
09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_GATT
,09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 06:42:25.969  5500  5523 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 06:42:26.050  5500  5523 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f06549
,09-23 06:42:26.050  5500  5523 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f06549 
,09-23 06:42:26.068  5500  5516 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 06:42:26.070  5500  5516 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 06:42:26.070  5500  5516 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 06:42:26.072  5500  5516 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:42:26.075  5500  5516 D BluetoothAdapterProperties: Scan Mode:20
,09-23 06:42:26.075  5500  5516 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:42:26.076  5500  5516 D bt_hci  : do_postload posting postload work item
09-23 06:42:26.076  5500  5520 I bt_hci  : event_postload
09-23 06:42:26.076  5500  5520 I bt_vendor: sco_config_cb
09-23 06:42:26.076  5500  5520 I bt_hci  : sco_config_callback postload finished.
09-23 06:42:26.079  5500  5516 D bt_bte_conf: Device ID record 1 : primary
09-23 06:42:26.079  5500  5516 D bt_bte_conf:   vendorId            = 000f
09-23 06:42:26.079  5500  5516 D bt_bte_conf:   vendorIdSource      = 0001
09-23 06:42:26.079  5500  5516 D bt_bte_conf:   product             = 1200
09-23 06:42:26.079  5500  5516 D bt_bte_conf:   version             = 1436
09-23 06:42:26.079  5500  5516 D bt_bte_conf:   clientExecutableURL = 
09-23 06:42:26.079  5500  5516 D bt_bte_conf:   serviceDescription  = 
,09-23 06:42:26.080  5500  5516 D bt_bte_conf:   documentationURL    = 
09-23 06:42:26.080  5500  5516 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 06:42:26.080  5500  5513 D bt_stack_manager: event_start_up_stack finished
09-23 06:42:26.080  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.085  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.086  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 06:42:26.086  5500  5512 D BluetoothAdapterProperties: Setting state to 15
09-23 06:42:26.086  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 06:42:26.088  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:26.088  5500  5512 I BluetoothAdapterState: Entering BleOnState
09-23 06:42:26.090  5500  5520 I bt_vendor: low_power_mode_cb
,09-23 06:42:26.092  5500  5512 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-23 06:42:26.092  5500  5512 D BluetoothAdapterProperties: Setting state to 11
09-23 06:42:26.092  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-23 06:42:26.096  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:26.098  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:26.099  5500  5500 D HeadsetService: Received start request. Starting profile...
09-23 06:42:26.100  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.101  5500  5500 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-23 06:42:26.101  5500  5500 D HeadsetStateMachine: make
09-23 06:42:26.102  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.110  5500  5512 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:42:26.114  5500  5500 D HeadsetStateMachine: max_hf_connections = 1
09-23 06:42:26.114  5500  5500 I bt_bluedroid: get_profile_interface handsfree
,09-23 06:42:26.114  5500  5516 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 06:42:26.114  5500  5516 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-23 06:42:26.117  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:26.118  5500  5500 D A2dpService: Received start request. Starting profile...
,09-23 06:42:26.119  5500  5500 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 06:42:26.119  5500  5500 I bt_bluedroid: get_profile_interface avrcp
,09-23 06:42:26.125  5500  5500 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 06:42:26.125  5500  5500 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 06:42:26.125  5500  5500 D A2dpStateMachine: make
,09-23 06:42:26.126  5500  5500 I bt_bluedroid: get_profile_interface a2dp
,09-23 06:42:26.127  5500  5516 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 06:42:26.129  5500  5531 D A2dpStateMachine: Enter Disconnected: -2
,09-23 06:42:26.129  5500  5500 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 06:42:26.130  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:26.131  5500  5500 D HidService: Received start request. Starting profile...
09-23 06:42:26.131  5454  5454 D BluetoothInputDevice: Proxy object connected
,09-23 06:42:26.132  5500  5500 I bt_bluedroid: get_profile_interface hidhost
09-23 06:42:26.132  5500  5516 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ee756d
09-23 06:42:26.132  5500  5516 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 06:42:26.132  5454  5454 D HidProfile: Bluetooth service connected
,09-23 06:42:26.132  5500  5500 D HidService: setHidService(): set to: null
,09-23 06:42:26.135  5500  5500 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 06:42:26.136  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
09-23 06:42:26.136  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:26.137  5500  5500 D HealthService: Received start request. Starting profile...
09-23 06:42:26.137  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:42:26.139  5500  5500 I bt_bluedroid: get_profile_interface health
,09-23 06:42:26.140  5500  5500 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 06:42:26.140  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:26.142  5454  5454 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:42:26.143  5454  5454 D PanProfile: Bluetooth service connected
09-23 06:42:26.143  5500  5500 D PanService: Received start request. Starting profile...
09-23 06:42:26.143  5500  5500 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-23 06:42:26.143  5500  5500 I bt_bluedroid: get_profile_interface pan
09-23 06:42:26.144  5500  5516 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-23 06:42:26.146  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:26.147  5454  5454 D BluetoothMap: Proxy object connected
09-23 06:42:26.147  5500  5500 D BluetoothMapService: Received start request. Starting profile...
09-23 06:42:26.147  5500  5500 D BluetoothMapService: start()
09-23 06:42:26.147  5454  5454 D MapProfile: Bluetooth service connected
09-23 06:42:26.147  5454  5454 D BluetoothMap: getConnectedDevices()
09-23 06:42:26.148  5454  5454 D BluetoothMap: Bluetooth is Not enabled
,09-23 06:42:26.150  5500  5500 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-23 06:42:26.151  5500  5500 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 06:42:26.151  5500  5500 D BluetoothMapAppObserver: createReceiver()
09-23 06:42:26.153  5500  5500 D BluetoothMapAppObserver: initObservers()
09-23 06:42:26.153  5500  5500 D BluetoothMapAppObserver: getEnabledAccountItems()
09-23 06:42:26.158  5500  5500 V SapService: SapBinder()
09-23 06:42:26.158  5500  5500 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:26.160  5500  5500 D SapService: Received start request. Starting profile...
09-23 06:42:26.160  5500  5500 V SapService: start()
,09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isTurningOn()=true
,09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.162  5500  5529 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.162  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:26.163  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.164  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.164  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:26.164  5500  5500 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:26.164  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.164  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.164  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 06:42:26.164  5500  5512 D BluetoothAdapterProperties: ScanMode =  20
09-23 06:42:26.165  5500  5512 D BluetoothAdapterProperties: State =  11
09-23 06:42:26.165  5500  5512 D BluetoothAdapterProperties: Setting state to 12
09-23 06:42:26.165  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 06:42:26.166  5500  5512 I BluetoothAdapterState: Entering OnState
09-23 06:42:26.166  3448  3466 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:42:26.167  5500  5516 D BluetoothAdapterProperties: Scan Mode:21
09-23 06:42:26.167  5500  5516 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:42:26.167  5454  5465 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:42:26.168   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:42:26.168   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:42:26.168  3058  3069 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:42:26.169   928   928 D BluetoothA2dp: Proxy object connected
09-23 06:42:26.171  3058  3058 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:42:26.171  3058  3058 D PanProfile: Bluetooth service connected
09-23 06:42:26.171  5337  5337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-23 06:42:26.173  3058  3612 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-23 06:42:26.175  5337  5337 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 06:42:26.176  3058  3058 D BluetoothInputDevice: Proxy object connected
09-23 06:42:26.176  3058  3058 D HidProfile: Bluetooth service connected
,09-23 06:42:26.176   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:42:26.177  5454  5464 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:42:26.177  5500  5500 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:42:26.177  5500  5500 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 06:42:26.178  3058  3069 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:42:26.179  5500  5500 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:26.180  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:26.181  5454  5465 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:42:26.181  5500  5500 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:26.181  3058  3070 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:42:26.182  5454  5464 D BluetoothPan: onBluetoothStateChange on: true
,09-23 06:42:26.182  5500  5500 D ObexServerSockets: Succeed to create listening sockets 
09-23 06:42:26.182  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:26.182  5500  5500 D ObexServerSockets0: startAccept()
09-23 06:42:26.183  5500  5500 D ObexServerSockets0: prepareForNewConnect()
09-23 06:42:26.183  3058  3612 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:42:26.184  3058  3070 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:42:26.184  3058  3058 D BluetoothA2dp: Proxy object connected
,09-23 06:42:26.187  3058  3058 D BluetoothMap: Proxy object connected
,09-23 06:42:26.187   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:42:26.187  3058  3058 D MapProfile: Bluetooth service connected
,09-23 06:42:26.187  3058  3058 D BluetoothMap: getConnectedDevices()
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:26.188  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:26.188   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 06:42:26.190  5500  5500 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 06:42:26.190  5500  5500 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 06:42:26.191  5500  5538 D ObexServerSockets0: Accepting socket connection...
09-23 06:42:26.192  5500  5500 D BluetoothMapService: onReceive
,09-23 06:42:26.192  5500  5500 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 06:42:26.192  5500  5500 D BluetoothMapService: STATE_ON
09-23 06:42:26.192  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:26.192  5500  5539 D ObexServerSockets0: Accepting socket connection...
09-23 06:42:26.193  5454  5454 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-23 06:42:26.197  5500  5541 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:26.198  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:26.198  5500  5541 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 06:42:26.199  5500  5541 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 06:42:26.199  5454  5454 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-23 06:42:26.200  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:26.201  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.202  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.204  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.208  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:42:26.210  5454  5454 D BluetoothA2dp: Proxy object connected
,09-23 06:42:26.212  5500  5500 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:42:26.212  5500  5500 D ObexServerSockets0: prepareForNewConnect()
,09-23 06:42:26.213  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:42:26.216  5454  5454 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:42:26.221  3058  3058 D BluetoothPbap: Proxy object connected
,09-23 06:42:26.221  3058  3058 D PbapServerProfile: Bluetooth service connected
,09-23 06:42:26.226  5454  5454 D BluetoothPbap: Proxy object connected
09-23 06:42:26.228  5500  5545 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:26.227  5454  5454 D PbapServerProfile: Bluetooth service connected
,09-23 06:42:26.240  5500  5549 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:42:26.241  5500  5549 I BtOppRfcommListener: Accept thread started.
,09-23 06:42:26.268   928   928 D BluetoothHeadset: Proxy object connected
,09-23 06:42:26.269   928   945 D BluetoothHeadset: Proxy object connected
09-23 06:42:26.269  3058  3612 D BluetoothHeadset: Proxy object connected
09-23 06:42:26.269  3058  3058 D HeadsetProfile: Bluetooth service connected
09-23 06:42:26.269   928   928 D BluetoothHeadset: Proxy object connected
09-23 06:42:26.269  3448  3467 D BluetoothHeadset: Proxy object connected
09-23 06:42:26.269   928   928 D BluetoothHeadset: Proxy object connected
,09-23 06:42:26.276   928   945 D BluetoothHeadset: Proxy object connected
,09-23 06:42:26.282  3058  3070 D BluetoothHeadset: Proxy object connected
,09-23 06:42:26.282  3058  3058 D HeadsetProfile: Bluetooth service connected
,09-23 06:42:26.287   928   945 D BluetoothHeadset: Proxy object connected
,09-23 06:42:26.302  5454  5464 D BluetoothHeadset: Proxy object connected
,09-23 06:42:26.303  5454  5454 D HeadsetProfile: Bluetooth service connected
,09-23 06:42:26.640  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.642  5337  5383 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 06:42:26.643  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 06:42:26.648  5337  5383 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,09-23 06:42:26.650  5337  5383 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,09-23 06:42:26.658  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.662  5500  5512 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 06:42:26.663  5500  5512 D BluetoothAdapterProperties: Setting state to 13
09-23 06:42:26.663  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 06:42:26.664  5500  5512 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 06:42:26.666  5500  5512 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:42:26.669  5500  5500 D BluetoothMapService: onReceive
,09-23 06:42:26.669  5500  5500 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-23 06:42:26.669  5500  5500 D BluetoothMapService: STATE_TURNING_OFF
09-23 06:42:26.670  5500  5500 D BluetoothMapService: MAP Service closeService in
09-23 06:42:26.670  5500  5500 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 06:42:26.670  5500  5500 D ObexServerSockets0: shutdown(block = true)
09-23 06:42:26.672  5500  5500 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-23 06:42:26.672  5500  5538 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 06:42:26.673  5500  5500 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 06:42:26.674  5500  5525 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 06:42:26.675  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:26.675  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:26.675  5500  5539 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-23 06:42:26.678  5500  5500 I BtOppRfcommListener: stopping Accept Thread
09-23 06:42:26.678  5500  5516 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:42:26.679  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:26.679  5500  5549 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 06:42:26.679  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:26.679  5500  5549 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 06:42:26.682  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 06:42:26.685  5500  5500 D HeadsetService: Received stop request...Stopping profile...
,09-23 06:42:26.687  5454  5465 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:26.688  5500  5500 D A2dpService: Received stop request...Stopping profile...
09-23 06:42:26.688  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:26.688  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:26.689  5500  5531 D A2dpStateMachine: Exit Disconnected: -1
09-23 06:42:26.689   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:26.689  3058  3069 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:26.689  5337  5337 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:26.689  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:26.690   928   928 D BluetoothHeadset: Proxy object disconnected
,09-23 06:42:26.690  3448  3715 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:26.691   928   928 D BluetoothHeadset: Proxy object disconnected
09-23 06:42:26.691  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:26.691  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:26.691   928   928 D BluetoothA2dp: Proxy object disconnected
09-23 06:42:26.691  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:42:26.691  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.691  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.692  5500  5500 D HidService: Received stop request...Stopping profile...
09-23 06:42:26.692  5500  5500 D HidService: Stopping Bluetooth HidService
09-23 06:42:26.693  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:26.695  5500  5500 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 06:42:26.695  5500  5500 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 06:42:26.695  5500  5523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:26.695  5500  5523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:26.695  5500  5523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:26.696  5500  5516 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 06:42:26.696  5500  5516 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
09-23 06:42:26.696  5500  5500 D HealthService: Received stop request...Stopping profile...
09-23 06:42:26.697  5500  5500 D PanService: Received stop request...Stopping profile...
09-23 06:42:26.698  3058  3058 D HeadsetProfile: Bluetooth service disconnected
,09-23 06:42:26.698  3058  3058 D BluetoothA2dp: Proxy object disconnected
09-23 06:42:26.698  3058  3058 D BluetoothInputDevice: Proxy object disconnected
09-23 06:42:26.698  3058  3058 D HidProfile: Bluetooth service disconnected
09-23 06:42:26.698  3058  3058 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 06:42:26.699  3058  3058 D PanProfile: Bluetooth service disconnected
09-23 06:42:26.699  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:26.699  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:26.699  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.699  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.700  5500  5523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 06:42:26.701  5500  5523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:26.701  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:26.701  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:26.701  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.701  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.701  5500  5500 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 06:42:26.701  5500  5500 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 06:42:26.701  5500  5523 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:42:26.702  5500  5523 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:42:26.702  5500  5523 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 06:42:26.702  5500  5523 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 06:42:26.702  5500  5516 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 06:42:26.702  5500  5500 D BluetoothMapService: Received stop request...Stopping profile...
09-23 06:42:26.702  5500  5516 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 06:42:26.702  5500  5500 D BluetoothMapService: stop()
09-23 06:42:26.703  5500  5500 D BluetoothMapAppObserver: deinitObservers()
09-23 06:42:26.703  5500  5500 D BluetoothMapAppObserver: removeReceiver()
09-23 06:42:26.705  3058  3058 D BluetoothMap: Proxy object disconnected
09-23 06:42:26.705  3058  3058 D MapProfile: Bluetooth service disconnected
09-23 06:42:26.706  5500  5500 D SapService: Received stop request...Stopping profile...
09-23 06:42:26.706  5500  5500 V SapService: stop()
09-23 06:42:26.707  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:26.707  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:26.707  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.707  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.708  5500  5500 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 06:42:26.708  5500  5516 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-23 06:42:26.708  5500  5500 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 06:42:26.708  5500  5500 V BluetoothAdapterState: isTurningOff()=true
,09-23 06:42:26.709  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:26.709  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.709  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.709  5500  5500 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 06:42:26.710  5500  5500 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 06:42:26.714  5500  5500 D BluetoothMapService: MAP Service closeService in
09-23 06:42:26.715  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:26.715  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:26.715  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:26.715  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.715  5500  5500 D BluetoothMapService: cleanup()
09-23 06:42:26.715  5500  5500 D BluetoothMapService: MAP Service closeService in
09-23 06:42:26.716  5500  5500 V BluetoothAdapterState: isTurningOff()=true
09-23 06:42:26.716  5500  5500 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:26.716  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:42:26.716  5500  5500 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:26.716  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 06:42:26.716  5500  5512 D BluetoothAdapterProperties: Setting state to 15
09-23 06:42:26.716  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 06:42:26.717  3448  3466 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:26.717  5500  5512 I BluetoothAdapterState: Entering BleOnState
,09-23 06:42:26.738  5454  5464 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:42:26.739  5454  5464 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:42:26.739   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:42:26.739   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:26.740  3058  3612 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:42:26.740  3058  3070 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 06:42:26.740   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:26.741  5454  5464 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:42:26.741  3058  3069 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 06:42:26.742  5454  5464 D BluetoothMap: onBluetoothStateChange: up=false
,09-23 06:42:26.743  5454  5464 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:26.743  3058  3612 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:26.743  5454  5464 D BluetoothPan: onBluetoothStateChange on: false
09-23 06:42:26.744  3058  3070 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 06:42:26.744  3058  3069 D BluetoothMap: onBluetoothStateChange: up=false
09-23 06:42:26.744   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 06:42:26.744  5500  5512 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 06:42:26.744  5500  5512 D BluetoothAdapterProperties: Setting state to 16
09-23 06:42:26.744  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 06:42:26.745  5500  5512 D BluetoothAdapterProperties: onBleDisable
09-23 06:42:26.745  5500  5512 I BluetoothAdapterState: Entering PendingCommandState
09-23 06:42:26.746  5500  5513 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-23 06:42:26.746  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:42:26.746  5500  5516 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:42:26.746  5454  5454 I art     : Waiting for a blocking GC DisableMovingGc
09-23 06:42:26.747  5500  5523 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-23 06:42:26.747  5500  5523 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 06:42:26.747  5454  5454 I art     : Starting a blocking GC DisableMovingGc
09-23 06:42:26.749  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.751  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:26.751  5454  5454 D HeadsetProfile: Bluetooth service disconnected
,09-23 06:42:26.752  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:26.754  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:26.754  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:42:26.756  5454  5454 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:42:26.761  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:42:26.766  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:42:26.770  5454  5454 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:42:26.948  5500  5516 I bt_hci  : shut_down
,09-23 06:42:26.949  5500  5520 D bt_hwcfg: hw_epilog_process
,09-23 06:42:26.950  5500  5520 I bt_vendor: low_power_mode_cb
,09-23 06:42:26.954  5500  5520 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 06:42:26.954  5500  5520 I bt_vendor: epilog_cb
09-23 06:42:26.954  5500  5520 I bt_hci  : epilog_finished_callback
09-23 06:42:26.955  5500  5516 I bt_hci_h4: hal_close
09-23 06:42:26.956  5500  5516 I bt_userial_vendor: device fd = 54 close
,09-23 06:42:27.079  5500  5513 D bt_stack_manager: event_shut_down_stack finished.
,09-23 06:42:27.080  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-23 06:42:27.084  5500  5512 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-23 06:42:27.084  5500  5500 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 06:42:27.085  5500  5500 D BtGatt.GattService: Received stop request...Stopping profile...
,09-23 06:42:27.085  5500  5500 D BtGatt.GattService: stop()
09-23 06:42:27.086  5500  5500 D BtGatt.AdvertiseManager: advertise clients cleared
,09-23 06:42:27.089  5500  5500 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:27.089  5500  5500 V BluetoothAdapterState: isTurningOn()=false
,09-23 06:42:27.089  5500  5500 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:27.089  5500  5500 V BluetoothAdapterState: isBleTurningOff()=true
09-23 06:42:27.090  5500  5512 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 06:42:27.090  5500  5512 D BluetoothAdapterProperties: Setting state to 10
09-23 06:42:27.090  5500  5512 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 06:42:27.091  5500  5512 I BluetoothAdapterState: Entering OffState
09-23 06:42:27.093   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-23 06:42:27.107  5500  5500 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 06:42:27.107  5500  5500 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-23 06:42:27.108  5500  5500 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 06:42:27.110  5500  5513 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 06:42:27.117  5500  5500 I art     : System.exit called, status: 0
,09-23 06:42:27.117  5500  5500 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 06:42:27.145   928  3085 I ActivityManager: Process com.android.bluetooth (pid 5500) has died
,09-23 06:42:27.160  5337  5397 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:27.160  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:27.160  5337  5397 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 06:42:27.160  5337  5397 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:27.161  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:27.174   928   945 I ActivityManager: Start proc 5555:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 06:42:27.232  5555  5555 D AdapterServiceConfig: Adding HeadsetService
,09-23 06:42:27.233  5555  5555 D AdapterServiceConfig: Adding A2dpService
09-23 06:42:27.233  5555  5555 D AdapterServiceConfig: Adding HidService
09-23 06:42:27.233  5555  5555 D AdapterServiceConfig: Adding HealthService
09-23 06:42:27.233  5555  5555 D AdapterServiceConfig: Adding PanService
,09-23 06:42:27.233  5555  5555 D AdapterServiceConfig: Adding GattService
09-23 06:42:27.233  5555  5555 D AdapterServiceConfig: Adding BluetoothMapService
,09-23 06:42:27.234  5555  5555 D AdapterServiceConfig: Adding SapService
,09-23 06:42:27.244   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19fa99c:true
,09-23 06:42:27.244  5555  5555 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 06:42:27.247  5555  5555 I bt_bluedroid: init
,09-23 06:42:27.247  5555  5567 I BluetoothAdapterState: Entering OffState
,09-23 06:42:27.249  5555  5568 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 06:42:27.249  5555  5568 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 06:42:27.249  5555  5568 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 06:42:27.249  5555  5568 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 06:42:27.250  5555  5555 I bt_bluedroid: get_profile_interface socket
,09-23 06:42:27.251  5555  5571 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 06:42:27.252  5555  5555 I bt_bluedroid: get_profile_interface sdp
,09-23 06:42:27.253  5555  5571 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:42:27.257  5555  5566 I bt_bluedroid: config_hci_snoop_log
,09-23 06:42:27.258   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-23 06:42:27.262  5555  5567 D BluetoothAdapterState: Current state: OFF, message: 0
,09-23 06:42:27.262  5555  5567 D BluetoothAdapterProperties: Setting state to 14
09-23 06:42:27.262  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-23 06:42:27.263  5555  5567 D BluetoothBondStateMachine: make
,09-23 06:42:27.265  5555  5572 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 06:42:27.267  5555  5567 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:42:27.268  5555  5555 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 06:42:27.270  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:27.271  5555  5555 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 06:42:27.271  5555  5555 D BtGatt.GattService: Received start request. Starting profile...
09-23 06:42:27.271  5555  5555 D BtGatt.GattService: start()
09-23 06:42:27.271  5555  5555 I bt_bluedroid: get_profile_interface gatt
09-23 06:42:27.272  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:27.272  5555  5555 D BtGatt.AdvertiseManager: advertise manager created
,09-23 06:42:27.277  5555  5555 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:42:27.277  5555  5555 V BluetoothAdapterState: isTurningOn()=false
09-23 06:42:27.277  5555  5555 V BluetoothAdapterState: isBleTurningOn()=true
09-23 06:42:27.277  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:27.277  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 06:42:27.278  5555  5567 I bt_bluedroid: bt_bluedroid
09-23 06:42:27.278  5555  5568 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 06:42:27.279  5555  5568 I bt_hci  : start_up
,09-23 06:42:27.284  5555  5568 I bt_vendor: alloc value 0xf3f88871
09-23 06:42:27.284  5555  5568 I bt_vendor: init
09-23 06:42:27.284  5555  5568 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 06:42:27.284  5555  5568 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 06:42:27.395  5555  5568 D bt_hci  : start_up starting async portion
,09-23 06:42:27.396  5555  5575 I bt_hci  : event_finish_startup
,09-23 06:42:27.396  5555  5575 I bt_hci_h4: hal_open
09-23 06:42:27.396  5555  5575 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 06:42:27.400  5555  5575 I bt_userial_vendor: device fd = 54 open
,09-23 06:42:27.393  5576  5576 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:42:27.413  5555  5575 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 06:42:27.416  5555  5575 D bt_hwcfg: Chipset BCM4358A3
,09-23 06:42:27.416  5555  5575 D bt_hwcfg: Target name = [BCM4358A3]
09-23 06:42:27.416  5555  5575 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 06:42:27.669  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 06:42:27.822  5555  5575 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 06:42:27.822  5555  5575 D bt_hwcfg: Settlement delay -- 100 ms
09-23 06:42:27.822  5555  5575 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 06:42:27.946  5555  5575 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-23 06:42:27.947  5555  5575 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-23 06:42:27.948  5555  5575 I bt_hwcfg: vendor lib fwcfg completed
,09-23 06:42:27.948  5555  5575 I bt_vendor: firmware callback
,09-23 06:42:27.948  5555  5575 I bt_hci  : firmware_config_callback
09-23 06:42:27.957  5555  5578 I bt_btu  : btu_task pending for preload complete event
,09-23 06:42:27.957  5555  5578 I bt_btu_task: Bluetooth chip preload is complete
,09-23 06:42:27.957  5555  5578 I bt_btu  : btu_task received preload complete event
,09-23 06:42:27.963  5555  5578 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 06:42:27.963  5555  5578 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 06:42:27.964  5555  5578 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 06:42:27.964  5555  5578 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 06:42:27.964  5555  5578 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-23 06:42:27.964  5555  5578 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 06:42:27.964  5555  5578 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 06:42:27.964  5555  5578 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 06:42:27.964  5555  5578 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 06:42:27.965  5555  5578 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 06:42:27.965  5555  5578 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 06:42:27.965  5555  5578 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 06:42:27.965  5555  5578 I         : BTE_InitTraceLevels -- TRC_SMP
,09-23 06:42:27.965  5555  5578 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 06:42:27.965  5555  5578 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 06:42:28.040  5555  5578 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3f06549
,09-23 06:42:28.040  5555  5578 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3f06549 
,09-23 06:42:28.056  5555  5571 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 06:42:28.057  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 06:42:28.058  5555  5571 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 06:42:28.060  5555  5571 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 06:42:28.063  5555  5571 D BluetoothAdapterProperties: Scan Mode:20
09-23 06:42:28.063  5555  5571 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:42:28.063  5555  5571 D bt_hci  : do_postload posting postload work item
09-23 06:42:28.064  5555  5575 I bt_hci  : event_postload
09-23 06:42:28.064  5555  5575 I bt_vendor: sco_config_cb
09-23 06:42:28.064  5555  5575 I bt_hci  : sco_config_callback postload finished.
,09-23 06:42:28.066  5555  5571 D bt_bte_conf: Device ID record 1 : primary
09-23 06:42:28.067  5555  5571 D bt_bte_conf:   vendorId            = 000f
09-23 06:42:28.067  5555  5571 D bt_bte_conf:   vendorIdSource      = 0001
09-23 06:42:28.067  5555  5571 D bt_bte_conf:   product             = 1200
09-23 06:42:28.067  5555  5571 D bt_bte_conf:   version             = 1436
09-23 06:42:28.067  5555  5571 D bt_bte_conf:   clientExecutableURL = 
09-23 06:42:28.067  5555  5571 D bt_bte_conf:   serviceDescription  = 
09-23 06:42:28.067  5555  5571 D bt_bte_conf:   documentationURL    = 
09-23 06:42:28.067  5555  5571 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-23 06:42:28.067  5555  5568 D bt_stack_manager: event_start_up_stack finished
09-23 06:42:28.068  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 06:42:28.068  5555  5567 D BluetoothAdapterProperties: Setting state to 15
09-23 06:42:28.068  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-23 06:42:28.070  5555  5567 I BluetoothAdapterState: Entering BleOnState
09-23 06:42:28.071  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:28.072  5555  5567 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 06:42:28.072  5555  5567 D BluetoothAdapterProperties: Setting state to 11
,09-23 06:42:28.073  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-23 06:42:28.073  5555  5575 I bt_vendor: low_power_mode_cb
09-23 06:42:28.074  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:28.078  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:28.080  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:28.086  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:28.087  5555  5555 D HeadsetService: Received start request. Starting profile...
09-23 06:42:28.089  5555  5555 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 06:42:28.090  5555  5555 D HeadsetStateMachine: make
,09-23 06:42:28.097  5555  5567 I BluetoothAdapterState: Entering PendingCommandState
,09-23 06:42:28.098  5555  5555 D HeadsetStateMachine: max_hf_connections = 1
,09-23 06:42:28.098  5555  5555 I bt_bluedroid: get_profile_interface handsfree
09-23 06:42:28.098  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 06:42:28.099  5555  5571 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-23 06:42:28.102  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:28.103  5555  5555 D A2dpService: Received start request. Starting profile...
09-23 06:42:28.103  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 06:42:28.104  5555  5555 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 06:42:28.104  5555  5555 I bt_bluedroid: get_profile_interface avrcp
,09-23 06:42:28.110  5555  5555 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 06:42:28.110  5555  5555 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 06:42:28.110  5555  5555 D A2dpStateMachine: make
09-23 06:42:28.111  5555  5555 I bt_bluedroid: get_profile_interface a2dp
,09-23 06:42:28.112  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 06:42:28.113  5555  5586 D A2dpStateMachine: Enter Disconnected: -2
09-23 06:42:28.113  5555  5555 I BluetoothHidServiceJni: classInitNative: succeeds
,09-23 06:42:28.114  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:28.115  5555  5555 D HidService: Received start request. Starting profile...
09-23 06:42:28.115  5555  5555 I bt_bluedroid: get_profile_interface hidhost
09-23 06:42:28.115  5555  5555 D HidService: setHidService(): set to: null
09-23 06:42:28.115  5555  5571 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ee756d
09-23 06:42:28.116  5555  5571 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-23 06:42:28.116  5555  5555 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-23 06:42:28.117  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:28.117  5555  5555 D HealthService: Received start request. Starting profile...
,09-23 06:42:28.119  5555  5555 I bt_bluedroid: get_profile_interface health
,09-23 06:42:28.119  5555  5555 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-23 06:42:28.120  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:28.120  5555  5555 D PanService: Received start request. Starting profile...
,09-23 06:42:28.121  5555  5555 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 06:42:28.121  5555  5555 I bt_bluedroid: get_profile_interface pan
09-23 06:42:28.121  5555  5571 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 06:42:28.123  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:28.123  5555  5555 D BluetoothMapService: Received start request. Starting profile...
,09-23 06:42:28.124  5555  5555 D BluetoothMapService: start()
09-23 06:42:28.126  5555  5555 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-23 06:42:28.127  5555  5555 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 06:42:28.127  5555  5555 D BluetoothMapAppObserver: createReceiver()
,09-23 06:42:28.128  5555  5555 D BluetoothMapAppObserver: initObservers()
09-23 06:42:28.128  5555  5555 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 06:42:28.135  5555  5555 V SapService: SapBinder()
,09-23 06:42:28.135  5555  5555 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
09-23 06:42:28.136  5555  5555 D SapService: Received start request. Starting profile...
09-23 06:42:28.136  5555  5555 V SapService: start()
,09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:28.138  5555  5584 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:28.138  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isTurningOff()=false
,09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
09-23 06:42:28.139  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:28.140  5555  5555 V BluetoothAdapterState: isTurningOff()=false
09-23 06:42:28.140  5555  5555 V BluetoothAdapterState: isTurningOn()=true
09-23 06:42:28.140  5555  5555 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 06:42:28.140  5555  5555 V BluetoothAdapterState: isBleTurningOff()=false
09-23 06:42:28.141  5555  5567 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 06:42:28.141  5555  5567 D BluetoothAdapterProperties: ScanMode =  20
09-23 06:42:28.141  5555  5567 D BluetoothAdapterProperties: State =  11
09-23 06:42:28.142  5555  5571 D BluetoothAdapterProperties: Scan Mode:21
09-23 06:42:28.142  5555  5567 D BluetoothAdapterProperties: Setting state to 12
09-23 06:42:28.142  5555  5567 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-23 06:42:28.145  5555  5567 I BluetoothAdapterState: Entering OnState
09-23 06:42:28.145  3448  3467 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:28.145  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:28.146  5555  5571 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 06:42:28.146  5454  5465 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-23 06:42:28.148  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:28.148  5454  5551 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:42:28.150   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:42:28.151  5454  5454 D BluetoothInputDevice: Proxy object connected
09-23 06:42:28.151  5454  5454 D HidProfile: Bluetooth service connected
09-23 06:42:28.151   928   928 D BluetoothA2dp: Proxy object connected
09-23 06:42:28.151   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:28.151  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:28.152  3058  3612 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:42:28.154  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:28.154  3058  3070 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 06:42:28.154  5555  5555 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-23 06:42:28.155  5555  5555 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-23 06:42:28.156   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:42:28.156  3058  3058 D BluetoothInputDevice: Proxy object connected
09-23 06:42:28.156  3058  3058 D HidProfile: Bluetooth service connected
09-23 06:42:28.156  5454  5464 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:42:28.157  5555  5555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:28.158  5555  5555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:28.160  5555  5555 D ObexServerSockets: Succeed to create listening sockets 
09-23 06:42:28.160  5454  5454 D BluetoothA2dp: Proxy object connected
09-23 06:42:28.160  5555  5555 D ObexServerSockets0: startAccept()
09-23 06:42:28.160  5555  5555 D ObexServerSockets0: prepareForNewConnect()
09-23 06:42:28.161  3058  3070 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 06:42:28.162  5555  5555 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 06:42:28.162  5555  5555 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-23 06:42:28.162  5454  5551 D BluetoothMap: onBluetoothStateChange: up=true
,09-23 06:42:28.163  3058  3058 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:42:28.163  3058  3058 D PanProfile: Bluetooth service connected
09-23 06:42:28.164  5555  5593 D ObexServerSockets0: Accepting socket connection...
09-23 06:42:28.164  5555  5594 D ObexServerSockets0: Accepting socket connection...
09-23 06:42:28.165  5454  5465 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 06:42:28.166  3058  3612 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:42:28.167  5454  5551 D BluetoothPan: onBluetoothStateChange on: true
09-23 06:42:28.169  3058  3070 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 06:42:28.170  3058  3058 D BluetoothA2dp: Proxy object connected
09-23 06:42:28.170  5454  5454 D BluetoothMap: Proxy object connected
09-23 06:42:28.170  5454  5454 D MapProfile: Bluetooth service connected
09-23 06:42:28.170  5454  5454 D BluetoothMap: getConnectedDevices()
09-23 06:42:28.171  3058  3612 D BluetoothMap: onBluetoothStateChange: up=true
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:28.172  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:28.172   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 06:42:28.172  3058  3058 D BluetoothMap: Proxy object connected
09-23 06:42:28.172  3058  3058 D MapProfile: Bluetooth service connected
,09-23 06:42:28.172  3058  3058 D BluetoothMap: getConnectedDevices()
09-23 06:42:28.173   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,09-23 06:42:28.175  5555  5555 D BluetoothMapService: onReceive
,09-23 06:42:28.175  5555  5555 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-23 06:42:28.175  5555  5555 D BluetoothMapService: STATE_ON
09-23 06:42:28.175  5337  5397 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:28.176  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:28.176  5454  5454 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 06:42:28.176  5454  5454 D PanProfile: Bluetooth service connected
09-23 06:42:28.177  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:28.177  5337  5383 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
09-23 06:42:28.177   928  3451 D WifiService: setWifiEnabled: false pid=5337, uid=10077
09-23 06:42:28.177   928  3451 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 06:42:28.179  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:28.182  5555  5597 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:28.182   928   928 D RttService: SCAN_AVAILABLE : 1
09-23 06:42:28.182   928  3009 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 06:42:28.183  5555  5597 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 06:42:28.183  5555  5597 D BluetoothSdpJni: SDP Create record success - handle: 1
,09-23 06:42:28.184  5454  5454 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 06:42:28.190  3528  3528 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 06:42:28.190  5454  5454 D DockEventReceiver: finishStartingService: stopping service
,09-23 06:42:28.197  3058  3058 D BluetoothPbap: Proxy object connected
09-23 06:42:28.198  3058  3058 D PbapServerProfile: Bluetooth service connected
,09-23 06:42:28.201  5555  5555 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 06:42:28.201  5555  5555 D ObexServerSockets0: prepareForNewConnect()
,09-23 06:42:28.202  5454  5454 D BluetoothPbap: Proxy object connected
,09-23 06:42:28.202  5454  5454 D PbapServerProfile: Bluetooth service connected
09-23 06:42:28.202   928  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-23 06:42:28.203   508   927 D CommandListener: Clearing all IP addresses on wlan0
09-23 06:42:28.205  5555  5602 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:42:28.207   928  2899 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
09-23 06:42:28.208  5450  5450 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:28.218  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:28.219  5555  5606 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:28.220  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 06:42:28.220  5555  5606 I BtOppRfcommListener: Accept thread started.
,09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:28.223  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:28.226  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:28.231  5450  5450 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-23 06:42:28.240  5450  5450 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 06:42:28.242  5450  5450 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 06:42:28.248  5454  5464 D BluetoothHeadset: Proxy object connected
,09-23 06:42:28.248   928   928 D BluetoothHeadset: Proxy object connected
09-23 06:42:28.248  3058  3069 D BluetoothHeadset: Proxy object connected
09-23 06:42:28.248  3058  3058 D HeadsetProfile: Bluetooth service connected
09-23 06:42:28.248   928   928 D BluetoothHeadset: Proxy object connected
09-23 06:42:28.249  3448  3466 D BluetoothHeadset: Proxy object connected
09-23 06:42:28.249   928   928 D BluetoothHeadset: Proxy object connected
09-23 06:42:28.250  5454  5454 D HeadsetProfile: Bluetooth service connected
09-23 06:42:28.251   928   945 D BluetoothHeadset: Proxy object connected
,09-23 06:42:28.256   928   945 D BluetoothHeadset: Proxy object connected
,09-23 06:42:28.266  5454  5465 D BluetoothHeadset: Proxy object connected
,09-23 06:42:28.267  3058  3070 D BluetoothHeadset: Proxy object connected
09-23 06:42:28.267  3058  3058 D HeadsetProfile: Bluetooth service connected
09-23 06:42:28.267  5454  5454 D HeadsetProfile: Bluetooth service connected
,09-23 06:42:28.273   928   945 D BluetoothHeadset: Proxy object connected
,09-23 06:42:28.343  4228  4228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 06:42:28.344   928  2899 D wifi    : In wifi stop Hal
,09-23 06:42:28.344   928  2899 D wifi    : halHandle = 0x7f7e4e7640, mVM = 0x7f9a60d140, mCls = 0x1017b2
,09-23 06:42:28.344   928  5449 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-23 06:42:28.344   928  5449 D WifiHAL : Got a signal to exit!!!
09-23 06:42:28.344   928  5449 I WifiHAL : Exit wifi_event_loop
09-23 06:42:28.346  3389  3944 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:42:28.347  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:28.349  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 06:42:28.349   928  2899 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 06:42:28.349   928  2899 E WifiHAL : Event processing terminated
09-23 06:42:28.349   928  2899 D wifi    : In wifi cleaned up handler
09-23 06:42:28.349   928  2899 I WifiHAL : Internal cleanup completed
,09-23 06:42:28.374   928  5449 D wifi    : set interface wlan0 flags (DOWN)
,09-23 06:42:28.375   928  2899 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 06:42:28.581   928   945 D Tethering: InitialState.processMessage what=4
,09-23 06:42:28.588   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:28.688  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:28.694  5337  5397 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:28.697   928  3427 D WifiService: setWifiEnabled: true pid=5337, uid=10077
,09-23 06:42:28.698   928  3427 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:42:28.700  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:28.703   508   927 D SoftapController: Softap fwReload - Ok
,09-23 06:42:28.709   508   927 D CommandListener: Setting iface cfg
,09-23 06:42:28.710   508   927 D CommandListener: Trying to bring down wlan0
09-23 06:42:28.711   508   927 D CommandListener: Clearing all IP addresses on wlan0
,09-23 06:42:28.718   928  2899 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 06:42:29.203   928  3437 D WifiService: setWifiEnabled: true pid=5337, uid=10077
,09-23 06:42:29.207   928  3437 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:42:29.320   928  2899 D wifi    : set interface wlan0 flags (UP)
,09-23 06:42:29.321   928  2899 I WifiHAL : Initializing wifi
,09-23 06:42:29.324   928  2899 I WifiHAL : Creating socket
09-23 06:42:29.329   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 06:42:29.331   928  2899 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 06:42:29.331   928  2899 D wifi    : Did set static halHandle = 0x7f7e4e7640
,09-23 06:42:29.331   928  2899 D wifi    : halHandle = 0x7f7e4e7640, mVM = 0x7f9a60d140, mCls = 0x1226
09-23 06:42:29.333   928  2899 D wifi    : array field set
09-23 06:42:29.333   928  2899 I WifiNative-HAL: interface[0] = wlan0
,09-23 06:42:29.336   928  5611 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547579917888
09-23 06:42:29.336   928  5611 D wifi    : waitForHalEvents called, vm = 0x7f9a60d140, obj = 0x1226, env = 0x7f7f12ef00
,09-23 06:42:29.400  5612  5612 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 06:42:29.420  5612  5612 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:42:29.431  5612  5612 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 06:42:29.431  5612  5612 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 06:42:29.438   928  2899 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 06:42:29.449  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:29.454   928  2899 D WifiConfigStore: Loading config and enabling all networks 
,09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:29.459  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 06:42:29.461  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:29.466   928  2899 D WifiConfigStore: loaded 0 passpoint configs
09-23 06:42:29.466   928  2899 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:29.466  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:29.466   928  2899 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 06:42:29.467   928  2899 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 06:42:29.468   928  2899 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 06:42:29.469   928  2899 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-23 06:42:29.469   928  2899 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 06:42:29.469   928  2899 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-23 06:42:29.469  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:29.471  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:29.472   928  2899 D WifiNative-HAL: Setting external_sim to 1
09-23 06:42:29.472  4228  4228 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 06:42:29.472   928  2899 D wifi    : setting dfs flag to true, 0x7f80e14b60
09-23 06:42:29.473   928  2899 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 06:42:29.473   928  2899 D wifi    : setting scan oui 0x7f80e14b60
,09-23 06:42:29.473   928  2899 D WifiHAL : Sending mac address OUI
,09-23 06:42:29.477   928  2899 E native  : do suspend false
,09-23 06:42:29.484   928   928 D RttService: SCAN_AVAILABLE : 3
,09-23 06:42:29.484   928  2899 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 06:42:29.485   508   927 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-23 06:42:29.485   928  3009 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 06:42:29.486   508   927 D CommandListener: Setting iface cfg
,09-23 06:42:29.490   928  2884 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-23 06:42:29.490   928  2884 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 06:42:29.498   928  2884 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 06:42:29.503   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=214667 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-23 06:42:29.503   928  2884 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:29.721  5337  5397 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:29.728  5337  5397 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:29.731  5337  5383 D BluetoothAdapter: enable(): BT is already enabled..!
,09-23 06:42:29.732   928  3053 D WifiService: setWifiEnabled: true pid=5337, uid=10077
,09-23 06:42:29.732   928  3053 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 06:42:29.733  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-23 06:42:29.733  5337  5383 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 06:42:29.734  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:42:29.734  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 06:42:29.734  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b98adec removed from the list
,09-23 06:42:29.734  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 06:42:29.734  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@58825b5 removed from the list
09-23 06:42:29.734  5337  5383 D io.jxcore.node.ConnectivityMonitor: stop
,09-23 06:42:29.735  5337  5383 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 06:42:29.735  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:42:29.738  5337  5383 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
09-23 06:42:29.742  5337  5383 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-23 06:42:29.748  5337  5614 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-23 06:42:29.748  5337  5614 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 06:42:30.259  5337  5616 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-23 06:42:30.260  5337  5614 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-23 06:42:30.260  5337  5616 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:42:30.260  5337  5614 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:42:30.262  5337  5614 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:42:30.262  5337  5616 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:42:30.264  5337  5614 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:42:30.265  5337  5616 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:42:30.266  5337  5614 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 06:42:30.268  5337  5618 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 158, name: OutgoingSocketThread/Sender)
,09-23 06:42:30.269  5337  5619 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Sender)
,09-23 06:42:30.270  5337  5616 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 06:42:30.275  5337  5620 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: OutgoingSocketThread/Receiver)
,09-23 06:42:30.276  5337  5621 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: IncomingSocketThread/Receiver)
,09-23 06:42:30.277  5337  5620 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: OutgoingSocketThread/Receiver)
,09-23 06:42:30.277  5337  5620 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 06:42:30.278  5337  5620 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-23 06:42:30.278  5337  5621 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 161, thread name: IncomingSocketThread/Receiver)
,09-23 06:42:30.278  5337  5621 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 06:42:30.279  5337  5621 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 161, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-23 06:42:30.753  5337  5383 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-23 06:42:30.756  5337  5383 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-23 06:42:30.758  5337  5383 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-23 06:42:30.763  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-23 06:42:30.764  5337  5383 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-23 06:42:30.766  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,09-23 06:42:30.766  5337  5383 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-23 06:42:30.767  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-23 06:42:30.771  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
09-23 06:42:30.771  5337  5383 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@478b7d0 Bundle[{}]
,09-23 06:42:30.772  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-23 06:42:30.772  5337  5383 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 06:42:30.772  5337  5383 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-23 06:42:30.773  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
09-23 06:42:30.773  5337  5383 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-23 06:42:30.774  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-23 06:42:30.774  5337  5383 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-23 06:42:30.774  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-23 06:42:30.774  5337  5383 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-23 06:42:30.775  5337  5383 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
,09-23 06:42:30.776  5337  5383 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-23 06:42:30.777  5337  5383 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
,09-23 06:42:30.779  5337  5383 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,09-23 06:42:30.780  5337  5383 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,09-23 06:42:30.780  5337  5383 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
09-23 06:42:30.781  5337  5383 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,09-23 06:42:30.782  5337  5383 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,09-23 06:42:30.784  5337  5383 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-23 06:42:30.786  5337  5622 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-23 06:42:30.786  5337  5622 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 06:42:30.789  5337  5622 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-23 06:42:30.789  5337  5622 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:42:30.789  5337  5622 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:42:30.790  5337  5622 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:42:30.791  5337  5624 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-23 06:42:30.791  5337  5625 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 171, name: OutgoingSocketThread/Sender)
,09-23 06:42:30.791  5337  5624 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 06:42:30.791  5337  5624 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 06:42:30.791  5337  5622 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-23 06:42:30.792  5337  5626 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Receiver)
09-23 06:42:30.793  5337  5624 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:42:30.793  5337  5626 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 172, thread name: OutgoingSocketThread/Receiver)
,09-23 06:42:30.794  5337  5626 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 06:42:30.794  5337  5626 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 06:42:30.794  5337  5627 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: IncomingSocketThread/Sender)
09-23 06:42:30.794  5337  5624 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-23 06:42:30.795  5337  5628 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: IncomingSocketThread/Receiver)
09-23 06:42:30.795  5337  5628 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: IncomingSocketThread/Receiver)
09-23 06:42:30.796  5337  5628 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 06:42:30.796  5337  5628 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 06:42:31.290  5337  5383 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-23 06:42:31.292  5337  5383 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,09-23 06:42:31.294  5337  5383 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-23 06:42:31.299  5337  5383 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-23 06:42:31.301  5337  5383 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
09-23 06:42:31.302  5337  5383 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,09-23 06:42:31.303  5337  5383 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 183)
09-23 06:42:31.304  5337  5383 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,09-23 06:42:31.304  5337  5383 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-23 06:42:31.304  5337  5383 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 184)
09-23 06:42:31.307  5337  5383 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,09-23 06:42:31.310  5337  5383 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,09-23 06:42:31.312  5337  5383 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,09-23 06:42:31.314  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 06:42:31.314  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78b7b16 added. We now have 3 listener(s)
09-23 06:42:31.318  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 06:42:31.318  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 06:42:31.318  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 06:42:31.318  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 06:42:31.319  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee84c97 added. We now have 3 listener(s)
,09-23 06:42:31.319  5337  5383 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 06:42:31.321  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 06:42:31.328  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 06:42:31.335  5337  5383 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 06:42:31.337  5337  5383 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 06:42:31.338  5337  5383 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 06:42:31.341  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:31.343  5337  5383 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
09-23 06:42:31.344  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 06:42:31.344  5337  5383 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-23 06:42:31.345  5337  5383 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-23 06:42:31.345  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
09-23 06:42:31.345  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:31.345  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:42:31.345  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:42:31.345  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:31.347  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:42:31.348  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:42:31.349  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:42:31.350  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 06:42:31.350  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:42:31.350  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-23 06:42:31.350  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:31.350  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 06:42:31.350  5337  5629 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 06:42:31.358  5337  5383 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted,
09-23 06:42:31.359  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 06:42:31.359  5337  5629 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:42:31.353  5595  5595 W Binder_6: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32993]" dev="sockfs" ino=32993 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:31.356  5595  5595 W Binder_6: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32993]" dev="sockfs" ino=32993 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 06:42:31.362  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:42:31.363  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:42:31.363  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:42:31.366  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 06:42:31.367  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:31.367  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-23 06:42:31.367  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:31.367  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:31.367  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:42:31.368  5337  5383 D BluetoothAdapter: STATE_ON
,09-23 06:42:31.371  5555  5565 D BtGatt.GattService: registerClient() - UUID=8044ba26-d457-4805-adf4-8ab564e9e899
,09-23 06:42:31.372  5555  5571 D BtGatt.GattService: onClientRegistered() - UUID=8044ba26-d457-4805-adf4-8ab564e9e899, clientIf=5
,09-23 06:42:31.373  5337  5348 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:42:31.374  5555  5573 D BtGatt.AdvertiseManager: message : 0
,09-23 06:42:31.377  5555  5573 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:42:31.388  5555  5571 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:42:31.396  5555  5571 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:42:31.397  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 06:42:31.397  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:42:31.398  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:42:31.400  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 06:42:31.400  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:42:31.400  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:42:31.401  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
,09-23 06:42:31.401  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:42:31.401  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:42:31.405  5337  5337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:42:31.405  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:42:31.906  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:42:31.906  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:42:31.906  5337  5337 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:42:32.705   928  2899 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 06:42:32.707   928  2899 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
09-23 06:42:32.707   928  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:42:32.719   928  2899 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 06:42:32.753   928  2899 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 06:42:32.755  5612  5612 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 06:42:33.190  5612  5612 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 06:42:33.225  5612  5612 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 06:42:33.225  5612  5612 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
09-23 06:42:33.233   928  2899 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 06:42:33.233   928  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-23 06:42:33.234   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-23 06:42:33.246   928  2899 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 06:42:33.257   508   927 D CommandListener: Setting iface cfg
,09-23 06:42:33.262   928  2899 D WifiStateMachine: Start Dhcp Watchdog 2
,09-23 06:42:33.268   928  5634 D DhcpClient: Receive thread started
,09-23 06:42:33.272   928  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-23 06:42:33.272   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-23 06:42:33.272   928  2901 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-23 06:42:33.352   928  2899 E native  : do suspend false
,09-23 06:42:33.366   928  5633 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 06:42:33.382   928  5634 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172624, domain null
,09-23 06:42:33.383   928  5633 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172624 seconds
,09-23 06:42:33.385   928  5633 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 06:42:33.399   928  5634 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 06:42:33.400   928  5633 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 06:42:33.403   508   927 D CommandListener: Setting iface cfg
,09-23 06:42:33.409   928  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 06:42:33.414   928  5633 D DhcpClient: Scheduling renewal in 86399s
,09-23 06:42:33.422   928  2899 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 06:42:33.423   928  2899 D WifiConfigStore: No blacklist allowed without epno enabled
,09-23 06:42:33.425   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-23 06:42:33.427   928  2901 D ConnectivityService: Adding iface wlan0 to network 101
,09-23 06:42:33.439   928  2899 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 06:42:33.482   928  2901 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 06:42:33.483   928  2901 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-23 06:42:33.485   928  2901 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-23 06:42:33.487   928  2901 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-23 06:42:33.489   928  2901 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-23 06:42:33.498   928  2901 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:42:33.503   928  2901 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-23 06:42:33.503   928  2901 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-23 06:42:33.504   928  2901 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-23 06:42:33.504   928  2899 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 06:42:33.504   928  2901 D ConnectivityService:    accepting network in place of null
09-23 06:42:33.504   928  2899 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 06:42:33.504   928  2901 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 06:42:33.520   928  5632 D NetlinkSocketObserver: NeighborEvent{elapsedMs=218684, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 06:42:33.534   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:42:33.560   508   927 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 06:42:33.564   928  2901 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-23 06:42:33.564   928  2901 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 06:42:33.564  3414  3589 W QCNEJ   : |CORE| network available: 101
,09-23 06:42:33.565  3414  3589 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-23 06:42:33.567  3414  3589 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,09-23 06:42:33.567   928  2901 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-23 06:42:33.567  3414  3589 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
09-23 06:42:33.569   928   945 D Tethering: MasterInitialState.processMessage what=3
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:33.575  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 06:42:33.577  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:42:33.579  4783  4798 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-23 06:42:33.579  4783  4798 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 06:42:33.579  4783  4798 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 06:42:33.579  4783  4798 E SarControlService: no key has been found,reset the power
09-23 06:42:33.580  4783  4823 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 06:42:33.580  4783  4823 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 06:42:33.580  4783  4823 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 06:42:33.580  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:42:33.580  4812  4812 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:33.581  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:42:33.583  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 06:42:33.586  4783  4823 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,09-23 06:42:33.586  4783  4823 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 06:42:33.587  4783  4823 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 06:42:33.587  5337  5337 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 06:42:33.587  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 06:42:33.587  4812  4812 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 06:42:33.589  5337  5337 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 06:42:33.589  3838  3838 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 06:42:33.592  4812  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9234ccc HexData = [00000000ec03000000000000ffffffff]
09-23 06:42:33.592  4812  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:42:33.592  4812  4826 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-23 06:42:33.593  4812  4826 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@9234ccc HexData = [00000000ed03000000000000ffffffff]
,09-23 06:42:33.593  4812  4826 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 06:42:33.593  4812  4826 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-23 06:42:33.593  3838  3838 D SystemUpdateService: onCreate
09-23 06:42:33.594  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:42:33.594  4783  4795 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 06:42:33.595  4812  4812 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 06:42:33.595  4783  4793 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,09-23 06:42:33.598   928  5631 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
09-23 06:42:33.598  3838  3838 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-23 06:42:33.607  3838  3838 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-23 06:42:33.614  3838  5105 I iu.UploadsManager: num queued entries: 0
,09-23 06:42:33.614  3838  5105 I iu.UploadsManager: num updated entries: 0
09-23 06:42:33.615  3838  5105 I iu.SyncManager: NEXT; no task
09-23 06:42:33.615  3838  5644 I SystemUpdateService: active receiver: enabled
,09-23 06:42:33.620  3838  3838 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 06:42:33.621  3838  3838 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 06:42:33.623  5420  5420 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 06:42:33.626  5420  5420 D SprintDMHelper: simOperator: 
09-23 06:42:33.626  5420  5420 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 06:42:33.647  3838  5644 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 06:42:33.655   928  5631 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 10:42:33 GMT], X-Android-Received-Millis=[1474627353654], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474627353626]}
,09-23 06:42:33.655   928  2901 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 06:42:33.655   928  2901 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-23 06:42:33.656   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:42:33.657   928  2901 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 06:42:33.661  3838  5644 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-23 06:42:33.661  3838  5644 I SystemUpdateService: now status is 0 (complete)
,09-23 06:42:33.661  3838  5644 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 06:42:33.661  3838  5644 I SystemUpdateService: file has been verified
09-23 06:42:33.661  3838  5644 I SystemUpdateService: OTA package size = 21989297
,09-23 06:42:33.668  3838  5644 I SystemUpdateService: showing system update notification
,09-23 06:42:33.680  3838  3838 D SystemUpdateService: onDestroy
,09-23 06:42:33.740  4228  5649 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 06:42:34.206   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 06:42:34.207   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 06:42:34.565   928  2901 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-23 06:42:34.903  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 06:42:34.903  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-23 06:42:34.903  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:42:34.903  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-23 06:42:34.903  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:42:34.904  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-23 06:42:34.904  5337  5629 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:42:34.904  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:42:34.904  5337  5629 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-23 06:42:34.904  5337  5629 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 06:42:34.904  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 06:42:34.905  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:42:34.905  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 06:42:34.905  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:42:34.905  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 06:42:34.905  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 06:42:34.908  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:34.908  5337  5383 D BluetoothLeScanner: could not find callback wrapper
09-23 06:42:34.908  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:42:34.908  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-23 06:42:34.910  5555  5573 D BtGatt.AdvertiseManager: message : 1
09-23 06:42:34.911  5555  5573 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:42:34.925  5555  5571 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:42:34.925  5555  5571 D BtGatt.GattService: Client app is not null!
,09-23 06:42:34.926  5555  5595 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 06:42:34.927  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 06:42:34.927  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 06:42:34.927  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 06:42:34.927  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:42:34.928  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 06:42:34.930  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:34.930  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:42:34.930  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 06:42:34.931  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 06:42:34.933  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 06:42:34.933  5337  5337 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 06:42:34.933  5337  5337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 06:42:34.933  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 06:42:34.933  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:34.934  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:42:34.937  5337  5383 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,09-23 06:42:34.938  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:42:34.939  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 06:42:34.939  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 06:42:34.939  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 06:42:34.939  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:34.939  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 06:42:34.944  5337  5383 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:42:34.944  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 06:42:34.950  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:42:34.950  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 06:42:34.951  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 06:42:34.956  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-23 06:42:34.957  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 06:42:34.957  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 06:42:34.959  5337  5383 D BluetoothAdapter: STATE_ON
,09-23 06:42:34.964  5555  5582 D BtGatt.GattService: registerClient() - UUID=3d009b60-5ebc-46e0-be6c-728b63d0b948
,09-23 06:42:34.964  5555  5571 D BtGatt.GattService: onClientRegistered() - UUID=3d009b60-5ebc-46e0-be6c-728b63d0b948, clientIf=5
09-23 06:42:34.965  5337  5347 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 06:42:34.966  5555  5566 D BtGatt.GattService: start scan with filters
,09-23 06:42:34.970  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 06:42:34.970  5555  5574 D BtGatt.ScanManager: handling starting scan
,09-23 06:42:34.971  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 06:42:34.971  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 06:42:34.971  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 06:42:34.972  5555  5574 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@add87cd
,09-23 06:42:34.974  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 06:42:34.974  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:42:34.975  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 06:42:34.976  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 06:42:34.980  5555  5571 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 06:42:34.980  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:34.981  5555  5574 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 06:42:34.989  5555  5571 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 06:42:34.989  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:34.989  5555  5574 D BtGatt.ScanManager: Starting BLE batch scan
09-23 06:42:34.989  5555  5574 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 06:42:35.001  5555  5571 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 06:42:35.001  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:42:35.008  5555  5571 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 06:42:35.008  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:42:35.476  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 06:42:35.476  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:42:35.476  5337  5337 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:42:36.285   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:42:36.451   928  2899 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,09-23 06:42:37.219   928  2899 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,09-23 06:42:37.983  5337  5383 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-23 06:42:37.983  5337  5383 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
09-23 06:42:37.983  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 06:42:37.984  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 06:42:37.984  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 06:42:37.987  5337  5383 D BluetoothAdapter: STATE_ON
,09-23 06:42:37.989  5555  5591 D BtGatt.GattService: stopScan() - queue size =1
09-23 06:42:37.996  5555  5592 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:42:37.996  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:42:37.997  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 06:42:37.997  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 06:42:37.997  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 06:42:37.997  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 06:42:37.997  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-23 06:42:38.001  5337  5383 D BluetoothAdapter: STATE_ON
,09-23 06:42:38.001  5555  5555 D BtGatt.ScanManager: awakened up at time 223165
09-23 06:42:38.005  5555  5591 D BtGatt.GattService: registerClient() - UUID=75e82fd5-0498-4b76-a8bc-80064b344fe4
09-23 06:42:38.006  5555  5571 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 06:42:38.006  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:38.006  5555  5571 D BtGatt.GattService: onClientRegistered() - UUID=75e82fd5-0498-4b76-a8bc-80064b344fe4, clientIf=5
09-23 06:42:38.006  5555  5574 D BtGatt.ScanManager: stopping BLe Batch
,09-23 06:42:38.008  5337  5347 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-23 06:42:38.009  5555  5582 D BtGatt.GattService: start scan with filters
,09-23 06:42:38.014  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 06:42:38.014  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 06:42:38.015  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:38.015  5337  5383 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 06:42:38.015  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 06:42:38.015  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 06:42:38.015  5555  5571 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 06:42:38.015  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:42:38.016  5555  5574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 06:42:38.017  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 06:42:38.017  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 06:42:38.017  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 06:42:38.018  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-23 06:42:38.018  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 06:42:38.018  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 06:42:38.018  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 06:42:38.018  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-23 06:42:38.019  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:38.020  5555  5596 D BtGatt.GattService: stopScan() - queue size =0
,09-23 06:42:38.020  5337  5657 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 06:42:38.021  5555  5591 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:42:38.022  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:42:38.022  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 06:42:38.022  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 06:42:38.022  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-23 06:42:38.022  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 06:42:38.019  5595  5595 W Binder_6: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33054]" dev="sockfs" ino=33054 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:38.019  5595  5595 W Binder_6: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[33054]" dev="sockfs" ino=33054 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 06:42:38.025  5337  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 06:42:38.026  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 06:42:38.027  5337  5383 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 06:42:38.030  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 06:42:38.031  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 06:42:38.031  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
,09-23 06:42:38.031  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:38.031  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 06:42:38.031  5337  5383 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 06:42:38.032  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:38.035  5555  5596 D BtGatt.GattService: registerClient() - UUID=08f1f97f-cb5f-4423-b238-03ca90c585bb
09-23 06:42:38.036  5555  5571 D BtGatt.GattService: onClientRegistered() - UUID=08f1f97f-cb5f-4423-b238-03ca90c585bb, clientIf=5
,09-23 06:42:38.036  5337  5348 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 06:42:38.037  5555  5571 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
09-23 06:42:38.037  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:38.038  5555  5571 D BtGatt.GattService: current time is 223202463538
09-23 06:42:38.038  5555  5573 D BtGatt.AdvertiseManager: message : 0
,09-23 06:42:38.038  5555  5571 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -74, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -74, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -84, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -74, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -89, 32, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -74, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 06:42:38.040  5555  5574 D BtGatt.ScanManager: handling starting scan
09-23 06:42:38.040  5555  5571 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-23 06:42:38.041  5555  5571 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-23 06:42:38.042  5555  5573 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 06:42:38.042  5555  5571 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 06:42:38.043  5555  5571 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-23 06:42:38.043  5555  5571 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-23 06:42:38.044  5555  5571 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 06:42:38.050  5555  5571 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 06:42:38.050  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:38.051  5555  5574 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 06:42:38.062  5555  5571 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 06:42:38.067  5555  5571 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 06:42:38.067  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:38.068  5555  5574 D BtGatt.ScanManager: Starting BLE batch scan
09-23 06:42:38.068  5555  5574 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 06:42:38.073  5555  5571 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 06:42:38.074  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 06:42:38.074  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 06:42:38.076  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 06:42:38.077  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:38.077  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:38.078  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 06:42:38.078  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 06:42:38.078  5337  5337 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 06:42:38.078  5337  5337 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 06:42:38.078  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 06:42:38.081  5337  5337 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 06:42:38.081  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 06:42:38.085  5555  5571 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 06:42:38.085  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:42:38.091  5555  5571 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 06:42:38.091  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:42:38.099  5555  5571 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-23 06:42:38.099  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:38.099  5555  5574 D BtGatt.ScanManager: stopping BLe Batch
,09-23 06:42:38.105  5555  5571 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-23 06:42:38.105  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 06:42:38.105  5555  5574 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 06:42:38.111  5555  5571 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-23 06:42:38.112  5555  5571 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 06:42:38.582  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 06:42:38.583  5337  5337 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 06:42:38.583  5337  5337 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 06:42:39.312   928  2901 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 06:42:41.506   928  2901 D ConnectivityService: handlePromptUnvalidated 101
,09-23 06:42:41.582  5337  5383 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-23 06:42:41.583  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 06:42:41.583  5337  5383 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 06:42:41.583  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 06:42:41.584  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 06:42:41.584  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 06:42:41.584  5337  5657 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 06:42:41.584  5337  5383 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 06:42:41.584  5337  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,09-23 06:42:41.585  5337  5657 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-23 06:42:41.585  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 06:42:41.585  5337  5337 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-23 06:42:41.585  5337  5383 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@78b7b16 removed from the list
,09-23 06:42:41.585  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 06:42:41.585  5337  5337 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-23 06:42:41.585  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 06:42:41.585  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 06:42:41.586  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 06:42:41.586  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-23 06:42:41.589  5337  5383 D BluetoothAdapter: STATE_ON
09-23 06:42:41.589  5337  5383 D BluetoothLeScanner: could not find callback wrapper
09-23 06:42:41.589  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 06:42:41.589  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 06:42:41.591  5555  5573 D BtGatt.AdvertiseManager: message : 1
09-23 06:42:41.593  5555  5573 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 06:42:41.608  5555  5571 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 06:42:41.608  5555  5571 D BtGatt.GattService: Client app is not null!
09-23 06:42:41.610  5555  5592 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 06:42:41.611  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 06:42:41.611  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 06:42:41.611  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 06:42:41.611  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 06:42:41.611  5337  5383 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 06:42:41.614  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:41.614  5337  5383 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 06:42:41.614  5337  5383 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 06:42:41.616  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 06:42:41.618  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:41.619  5337  5337 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 06:42:41.619  5337  5383 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee84c97 removed from the list
,09-23 06:42:41.619  5337  5383 D io.jxcore.node.ConnectivityMonitor: stop
09-23 06:42:41.619  5337  5337 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 06:42:41.619  5337  5383 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 06:42:41.622  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-23 06:42:41.623  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-23 06:42:41.623  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 06:42:41.623  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 06:42:41.623  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 06:42:41.623  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-23 06:42:41.623  5337  5383 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 06:42:41.625  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
09-23 06:42:41.626  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
,09-23 06:42:41.627  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
09-23 06:42:41.628  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
09-23 06:42:41.629  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-23 06:42:41.630  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-23 06:42:41.631  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
09-23 06:42:41.632  5337  5383 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,09-23 06:42:41.634  5337  5383 I StreamCopyingThreadTest: Starting test: testRun
,09-23 06:42:41.637  5337  5659 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 197, name: My test thread name)
,09-23 06:42:42.120  5337  5337 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 06:42:43.313  5337  5659 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 197
,09-23 06:42:43.314  5337  5659 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 197, name: My test thread name)
09-23 06:42:43.314  5337  5659 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 197, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-23 06:42:43.641  5337  5383 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-23 06:42:43.645  5337  5661 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 199, name: My test thread name)
09-23 06:42:43.645  5337  5661 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 199, thread name: My test thread name)
,09-23 06:42:43.645  5337  5661 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 199, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-23 06:42:43.648  5337  5383 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-23 06:42:43.650  5337  5383 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 06:42:43.654  5337  5383 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-23 06:42:43.657  5337  5662 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 203, name: My test thread name)
09-23 06:42:43.658  5337  5662 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 203, thread name: My test thread name): Test exception.
09-23 06:42:43.658  5337  5662 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 203, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-23 06:42:43.663  5337  5383 I jxcore-log: *Native tests were executed*
09-23 06:42:43.663  5337  5383 I jxcore-log: 
,09-23 06:42:43.664  5337  5383 I jxcore-log: Total number of executed tests:  82
09-23 06:42:43.664  5337  5383 I jxcore-log: 
,09-23 06:42:43.664  5337  5383 I jxcore-log: Number of passed tests:  82
09-23 06:42:43.664  5337  5383 I jxcore-log: 
,09-23 06:42:43.665  5337  5383 I jxcore-log: Number of failed tests:  0
09-23 06:42:43.665  5337  5383 I jxcore-log: 
,09-23 06:42:43.665  5337  5383 I jxcore-log: Number of ignored tests:  0
09-23 06:42:43.665  5337  5383 I jxcore-log: 
,09-23 06:42:43.667  5337  5383 I jxcore-log: Total duration:  25515
09-23 06:42:43.667  5337  5383 I jxcore-log: 
,09-23 06:42:43.667  5337  5383 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 06:42:43.667  5337  5383 I jxcore-log: 
,09-23 06:42:43.674  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:42:43.674  5337  5383 I jxcore-log: 
09-23 06:42:43.680  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:42:43.680  5337  5383 I jxcore-log: 
09-23 06:42:43.683  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:42:43.683  5337  5383 I jxcore-log: 
09-23 06:42:43.686  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:42:43.686  5337  5383 I jxcore-log: 
09-23 06:42:43.688  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:42:43.688  5337  5383 I jxcore-log: 
09-23 06:42:43.690  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:42:43.690  5337  5383 I jxcore-log: 
,09-23 06:42:43.694  5337  5337 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-23 06:42:43.694  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:42:43.694  5337  5383 I jxcore-log: 
,09-23 06:42:43.697  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.697  5337  5383 I jxcore-log: 
,09-23 06:42:43.698  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:42:43.698  5337  5383 I jxcore-log: 
09-23 06:42:43.699  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:42:43.699  5337  5383 I jxcore-log: 
09-23 06:42:43.700  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:42:43.700  5337  5383 I jxcore-log: 
,09-23 06:42:43.702  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 06:42:43.702  5337  5383 I jxcore-log: 
,09-23 06:42:43.703  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.703  5337  5383 I jxcore-log: 
,09-23 06:42:43.704  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.704  5337  5383 I jxcore-log: 
,09-23 06:42:43.706  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.706  5337  5383 I jxcore-log: 
,09-23 06:42:43.707  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.707  5337  5383 I jxcore-log: 
,09-23 06:42:43.708  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.708  5337  5383 I jxcore-log: 
,09-23 06:42:43.709  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.709  5337  5383 I jxcore-log: 
,09-23 06:42:43.710  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.710  5337  5383 I jxcore-log: 
09-23 06:42:43.711  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.711  5337  5383 I jxcore-log: 
09-23 06:42:43.712  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.712  5337  5383 I jxcore-log: 
,09-23 06:42:43.713  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.713  5337  5383 I jxcore-log: 
,09-23 06:42:43.714  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.714  5337  5383 I jxcore-log: 
09-23 06:42:43.715  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.715  5337  5383 I jxcore-log: 
09-23 06:42:43.716  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.716  5337  5383 I jxcore-log: 
,09-23 06:42:43.717  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.717  5337  5383 I jxcore-log: 
,09-23 06:42:43.718  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.718  5337  5383 I jxcore-log: 
09-23 06:42:43.718  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:42:43.718  5337  5383 I jxcore-log: 
,09-23 06:42:43.719  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:42:43.719  5337  5383 I jxcore-log: 
,09-23 06:42:43.720  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 06:42:43.720  5337  5383 I jxcore-log: 
09-23 06:42:43.721  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.721  5337  5383 I jxcore-log: 
09-23 06:42:43.722  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.722  5337  5383 I jxcore-log: 
,09-23 06:42:43.722  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.722  5337  5383 I jxcore-log: 
,09-23 06:42:43.723  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 06:42:43.723  5337  5383 I jxcore-log: 
09-23 06:42:43.724  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:42:43.724  5337  5383 I jxcore-log: 
09-23 06:42:43.725  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:42:43.725  5337  5383 I jxcore-log: 
09-23 06:42:43.726  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:42:43.726  5337  5383 I jxcore-log: 
,09-23 06:42:43.727  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 06:42:43.727  5337  5383 I jxcore-log: 
,09-23 06:42:43.728  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-23 06:42:43.728  5337  5383 I jxcore-log: 
,09-23 06:42:43.729  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 06:42:43.729  5337  5383 I jxcore-log: 
,09-23 06:42:43.730  5337  5383 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 06:42:43.730  5337  5383 I jxcore-log: 
,09-23 06:42:44.169  5663  5663 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 06:42:44.175  5663  5663 D AndroidRuntime: CheckJNI is OFF
,09-23 06:42:44.207  5663  5663 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 06:42:44.207   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 06:42:44.241  5663  5663 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 06:42:44.256  5663  5663 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 06:42:44.265   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-23 06:42:44.266   928   941 I ActivityManager: Killing 5337:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-23 06:42:44.314   928   938 I WindowState: WIN DEATH: Window{e6e5bec u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-23 06:42:44.315   928  3053 D GraphicsStats: Buffer count: 2
,09-23 06:42:44.315   928  2900 D WifiService: Client connection lost with reason: 4
,09-23 06:42:44.414   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-23 06:42:44.414   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-23 06:42:44.415   928   951 I art     : Starting a blocking GC Explicit
09-23 06:42:44.415   928   941 E ActivityManager: Failure starting process com.test.thalitest
09-23 06:42:44.415   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-23 06:42:44.415   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:44.415   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:44.415   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:42:44.415   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 06:42:44.416   928   941 I ActivityManager:   Force finishing activity ActivityRecord{f1f8a19 u0 com.test.thalitest/.MainActivity t2}
,09-23 06:42:44.421   928  3464 W ActivityManager: Spurious death for ProcessRecord{9216325 0:com.test.thalitest/u0a77}, curProc for 5337: null
,09-23 06:42:44.425   928   946 W WindowManager: Attempted to add application window with unknown token Token{4d79ade ActivityRecord{f1f8a19 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-23 06:42:44.425   928   946 W WindowManager: Token{4d79ade ActivityRecord{f1f8a19 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{4d79ade ActivityRecord{f1f8a19 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
,09-23 06:42:44.425   928   946 W WindowManager: view not successfully added to wm, removing view
09-23 06:42:44.426   928   946 W WindowManager: Exception when adding starting window
09-23 06:42:44.426   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{d2251b4 V.E...... R.....ID 0,0-0,0} not attached to window manager
09-23 06:42:44.426   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-23 06:42:44.426   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-23 06:42:44.426   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-23 06:42:44.426   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-23 06:42:44.426   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-23 06:42:44.426   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:44.426   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:44.426   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:42:44.426   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 06:42:44.506   928  2899 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,09-23 06:42:44.510   928   951 I art     : Explicit concurrent mark sweep GC freed 37062(2MB) AllocSpace objects, 9(292KB) LOS objects, 33% free, 28MB/43MB, paused 2.145ms total 94.470ms
,09-23 06:42:44.534   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-23 06:42:44.537  5663  5663 I art     : System.exit called, status: 0
09-23 06:42:44.537  5663  5663 I AndroidRuntime: VM exiting with result code 0.
,09-23 06:42:44.541   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-23 06:42:44.552   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-23 06:42:44.557  5555  5555 D BluetoothMapAppObserver: onReceive
09-23 06:42:44.558  5555  5555 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-23 06:42:44.559   928  2865 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-23 06:42:44.574  3389  3879 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-23 06:42:44.578  3333  3333 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-23 06:42:44.592  3333  5676 I Keyboard.Facilitator.DecoderInitializer: run()
,09-23 06:42:44.605  3345  5678 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-23 06:42:44.618   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-23 06:42:44.615  3333  5676 I Decoder : createOrResetDecoder
,09-23 06:42:44.619  3448  3448 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-23 06:42:44.616   412   412 W kworker/4:1: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:42:44.623   412   412 W kworker/4:1: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:42:44.626  3528  3528 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-23 06:42:44.626  3528  3528 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-23 06:42:44.634  3475  3603 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-23 06:42:44.639   412   412 W kworker/4:1: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 06:42:44.645  3838  5681 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-23 06:42:44.645  3838  5681 D AccountUtils: Clearing selected account for com.test.thalitest
,09-23 06:42:44.649   928  3437 I ActivityManager: Start proc 5682:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-23 06:42:44.650  3475  3603 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-23 06:42:44.650  3475  3603 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3475
09-23 06:42:44.650  3475  3603 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:44.650  3475  3603 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 06:42:44.656   928  3427 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-23 06:42:44.657   928  5694 E DropBoxManagerService: Can't write: system_app_crash
09-23 06:42:44.657   928  5694 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 06:42:44.657   928  5694 E DropBoxManagerService: 	... 5 more
,09-23 06:42:44.661  3475  3603 I Process : Sending signal. PID: 3475 SIG: 9
,09-23 06:42:44.672  3838  5681 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-23 06:42:44.707  3528  3528 I ConfigService: onCreate
,09-23 06:42:44.711  3528  5699 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 06:42:44.711  3528  5699 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 06:42:44.711  3528  5699 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-23 06:42:44.713  3528  5699 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-23 06:42:44.729  3838  5681 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:44.729  3838  5681 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-23 06:42:44.729  3838  5681 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 06:42:44.730  3838  5681 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-23 06:42:44.739  3333  5676 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-23 06:42:44.780   928  3451 D GraphicsStats: Buffer count: 1
,09-23 06:42:44.780   928  3437 I WindowState: WIN DEATH: Window{778b64e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-23 06:42:44.785   928  3487 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3475) has died
,09-23 06:42:44.786   928  3487 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-23 06:42:44.820  3838  5702 I GMPM-SVC: App measurement is starting up
,09-23 06:42:44.832  3838  5702 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-23 06:42:44.833  3838  5702 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-23 06:42:45.008   383   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
