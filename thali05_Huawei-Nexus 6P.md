#### Test 86373152291968c_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 04:27:56.853   537   537 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-23 04:27:56.854   537   537 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 04:27:57.317  5350  5350 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 04:27:57.322  5350  5350 D AndroidRuntime: CheckJNI is OFF
09-23 04:27:57.346  5350  5350 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 04:27:57.379  5350  5350 I Radio-JNI: register_android_hardware_Radio DONE
09-23 04:27:57.394  5350  5350 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 04:27:57.398   931   941 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 04:27:57.437   931   941 I ActivityManager: Start proc 5359:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 04:27:57.442  5350  5350 D AndroidRuntime: Shutting down VM
,09-23 04:27:57.779   931  3932 I WindowManager: Screenshot max retries 4 of Token{3a37caa ActivityRecord{241e395 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{f7bf04d u0 Starting com.test.thalitest} drawState=4
,09-23 04:27:57.842  5359  5359 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 04:27:57.876  5359  5359 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 04:27:57.900  5359  5359 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 501-520)
09-23 04:27:57.901  5359  5359 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 04:27:57.920  5359  5359 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {315a6db}
,09-23 04:27:57.920  5359  5359 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 04:27:57.921  5359  5359 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 04:27:57.926  5359  5359 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 04:27:57.927  5359  5359 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 04:27:57.962  5359  5359 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 04:27:57.975  5359  5359 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 04:27:57.975  5359  5359 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 04:27:57.975  5359  5359 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 04:27:57.975  5359  5359 I Adreno  : Build Date                       : 12/06/15
09-23 04:27:57.975  5359  5359 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 04:27:57.975  5359  5359 I Adreno  : Local Branch                     : mybranch17112971
09-23 04:27:57.975  5359  5359 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 04:27:57.975  5359  5359 I Adreno  : Remote Branch                    : NONE
09-23 04:27:57.975  5359  5359 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 04:27:58.031   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e3dc05:true
,09-23 04:27:58.066   740   740 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22301]" dev="sockfs" ino=22301 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 04:27:58.066   740   740 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22301]" dev="sockfs" ino=22301 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 04:27:58.079  5359  5359 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 04:27:58.088  5359  5359 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 04:27:58.116   739   739 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[30225]" dev="sockfs" ino=30225 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 04:27:58.116   739   739 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[30225]" dev="sockfs" ino=30225 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 04:27:58.119  5359  5396 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 04:27:58.119  3518  3518 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22312]" dev="sockfs" ino=22312 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 04:27:58.119  3518  3518 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[22312]" dev="sockfs" ino=22312 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 04:27:58.127  5359  5383 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 04:27:58.156  5359  5396 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 04:27:58.232   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +450ms (total +819ms)
,09-23 04:27:58.258  5359  5359 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5359
,09-23 04:27:58.360  5359  5359 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 04:27:58.511  5359  5399 D jxcore_app_log: JniHelper::setJavaVM(0xf51bc000), pthread_self() = -585361104
,09-23 04:27:58.514  5359  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 04:27:58.514  5359  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 04:27:58.514  5359  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 04:27:58.514  5359  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 04:27:58.514  5359  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 04:27:58.515  5359  5399 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2230a49 added. We now have 1 listener(s)
,09-23 04:27:58.517  5359  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 04:27:58.518  5359  5399 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 04:27:58.518  5359  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 04:27:58.518  5359  5399 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 04:27:58.521  5359  5399 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afd097c added. We now have 1 listener(s)
09-23 04:27:58.521  5359  5399 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-23 04:27:58.525   931  2934 D WifiService: New client listening to asynchronous messages
,09-23 04:27:58.526  5359  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 04:27:58.526  5359  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-23 04:27:58.526  5359  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 04:27:58.526  5359  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 04:27:58.526  5359  5399 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 04:27:58.528  5359  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 04:27:58.528  5359  5399 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 04:27:58.533  5359  5399 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 04:27:58.533  5359  5399 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 04:27:58.533  5359  5399 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 04:27:58.533  5359  5399 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 04:27:58.534  5359  5399 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 04:27:58.536  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 04:27:58.539  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 04:27:58.557  5359  5359 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 04:27:58.860  5359  5405 W jxcore-log: Initializing JXcore engine
,09-23 04:27:58.860  5359  5405 W jxcore-log: JXcore engine is ready
,09-23 04:27:58.886  5405  5405 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11603 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-23 04:27:58.886  5405  5405 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16473]" dev="sockfs" ino=16473 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-23 04:27:58.886  5405  5405 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 04:27:58.886  5405  5405 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31761]" dev="sockfs" ino=31761 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 04:27:58.894  5359  5405 W jxcore-log: Starting JXcore engine
,09-23 04:27:58.951  5359  5405 W jxcore-log: Platform android
09-23 04:27:58.951  5359  5405 W jxcore-log: 
,09-23 04:27:58.951  5359  5405 W jxcore-log: Process ARCH arm
09-23 04:27:58.951  5359  5405 W jxcore-log: 
,09-23 04:27:59.018   931  2933 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 04:27:59.050  5359  5405 I jxcore-log: JXcore Cordova bridge is ready!
09-23 04:27:59.050  5359  5405 I jxcore-log: 
,09-23 04:27:59.050  5359  5405 W jxcore-log: JXcore engine is started
,09-23 04:27:59.059  5359  5399 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 04:27:59.065  5359  5359 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 04:28:06.855   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 04:28:07.856   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 04:28:08.685  5359  5405 I jxcore-log: 2016-09-23 08:28:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
09-23 04:28:08.685  5359  5405 I jxcore-log: 
,09-23 04:28:08.687  5359  5405 I jxcore-log: 2016-09-23 08:28:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
09-23 04:28:08.687  5359  5405 I jxcore-log: 
,09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 04:28:08.694  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 04:28:08.701  5359  5405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 04:28:08.702  5359  5405 I jxcore-log: 2016-09-23 08:28:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
09-23 04:28:08.702  5359  5405 I jxcore-log: 
,09-23 04:28:08.704  5359  5405 I jxcore-log: 2016-09-23 08:28:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
09-23 04:28:08.704  5359  5405 I jxcore-log: 
,09-23 04:28:08.857   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 04:28:08.952  5359  5405 I jxcore-log: Running unit tests
09-23 04:28:08.952  5359  5405 I jxcore-log: 
,09-23 04:28:08.953  5359  5405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 04:28:08.953  5359  5405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27cd7b7 added. We now have 2 listener(s)
,09-23 04:28:08.954  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 04:28:08.954  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 04:28:08.954  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 04:28:08.954  5359  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 04:28:08.954  5359  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76bcb24 added. We now have 2 listener(s)
,09-23 04:28:08.954  5359  5405 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 04:28:08.955  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 04:28:08.957  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 04:28:08.960  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 04:28:08.962  5359  5405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 04:28:08.962  5359  5405 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 04:28:08.962  5359  5405 D executeNativeTests: Running unit tests
,09-23 04:28:08.968  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 04:28:08.974  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 04:28:09.001  5359  5405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 04:28:09.001  5359  5405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cf0df2 added. We now have 3 listener(s)
,09-23 04:28:09.001  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 04:28:09.002  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 04:28:09.002  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 04:28:09.002  5359  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 04:28:09.002  5359  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94dc43 added. We now have 3 listener(s)
09-23 04:28:09.002  5359  5405 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 04:28:09.002  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 04:28:09.004  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 04:28:09.006  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 04:28:09.007  5359  5405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 04:28:09.007  5359  5405 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 04:28:09.009  5359  5405 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 04:28:09.009  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 04:28:09.009  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 04:28:09.009  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 04:28:09.009  5359  5405 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 04:28:09.009  5359  5405 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 04:28:09.010  5359  5405 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 04:28:09.010  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 04:28:09.010  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 04:28:09.010  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 04:28:09.010  5359  5405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 04:28:09.010  5359  5405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 04:28:09.010  5359  5405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 04:28:09.010  5359  5405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 04:28:09.010  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 04:28:09.010  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 04:28:09.010  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 04:28:09.010  5359  5405 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cf0df2 removed from the list
09-23 04:28:09.010  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 04:28:09.011  5359  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94dc43 removed from the list
,09-23 04:28:09.014  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 04:28:09.019  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 04:28:09.020  5359  5405 D io.jxcore.node.ConnectivityMonitor: stop
09-23 04:28:09.020  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 04:28:09.020  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 04:28:09.020  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 04:28:09.021  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 04:28:09.021  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 04:28:09.021  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 04:28:09.021  5359  5405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94dc43 not in the list
09-23 04:28:09.022  5359  5405 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 04:28:09.022  5359  5405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 04:28:09.022  5359  5405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 04:28:09.022  5359  5405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 04:28:09.022  5359  5405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 04:28:09.022  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 04:28:09.022  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 04:28:09.022  5359  5405 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cf0df2 not in the list
09-23 04:28:09.022  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 04:28:09.022  5359  5405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94dc43 not in the list
09-23 04:28:09.022  5359  5405 D io.jxcore.node.ConnectivityMonitor: stop
09-23 04:28:09.022  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 04:28:09.022  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 04:28:09.022  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-23 04:28:09.022  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 04:28:09.023  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 04:28:09.023  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 04:28:09.023  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 04:28:09.023  5359  5405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94dc43 not in the list
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 04:28:09.025  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 04:28:09.026  5359  5405 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-23 04:28:09.026  5359  5405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 04:28:09.026  5359  5405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 04:28:09.026  5359  5405 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 04:28:09.026  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 04:28:09.026  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 04:28:09.026  5359  5405 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cf0df2 not in the list
09-23 04:28:09.026  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 04:28:09.026  5359  5405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94dc43 not in the list
09-23 04:28:09.026  5359  5405 D io.jxcore.node.ConnectivityMonitor: stop
09-23 04:28:09.027  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 04:28:09.027  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 04:28:09.027  5359  5405 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 04:28:09.027  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 04:28:09.027  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-23 04:28:09.027  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 04:28:09.027  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 04:28:09.027  5359  5405 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d94dc43 not in the list
09-23 04:28:09.028  5359  5405 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-23 04:28:09.028  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 04:28:09.031  5359  5405 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 04:28:09.032  5359  5405 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 04:28:09.032  5359  5405 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 04:28:09.032  5359  5405 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 04:28:09.032  5359  5405 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 04:28:09.033  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 04:28:09.033  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 04:28:09.033  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 04:28:09.035  5359  5405 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 04:28:09.035  5359  5405 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 04:28:09.037  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 04:28:09.039  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 04:28:09.039  5359  5359 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 04:28:09.039  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 04:28:09.040  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 04:28:09.041  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 04:28:09.042  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 04:28:09.042  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 04:28:09.042  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 04:28:09.043  5359  5405 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 04:28:09.043  5359  5405 D BluetoothAdapter: STATE_ON
09-23 04:28:09.045  4422  4436 D BtGatt.GattService: registerClient() - UUID=a40d575c-600f-4334-b314-6bb41ec8681d
09-23 04:28:09.047  4422  4510 D BtGatt.GattService: onClientRegistered() - UUID=a40d575c-600f-4334-b314-6bb41ec8681d, clientIf=5
09-23 04:28:09.048  5359  5369 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 04:28:09.050  4422  4434 D BtGatt.GattService: start scan with filters
09-23 04:28:09.055  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-23 04:28:09.055  5359  5405 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 04:28:09.055  5359  5405 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 04:28:09.055  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-23 04:28:09.056  4422  4513 D BtGatt.ScanManager: handling starting scan
09-23 04:28:09.057  5359  5405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 04:28:09.057  5359  5405 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 04:28:09.057  5359  5359 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 04:28:09.057  5359  5405 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 04:28:09.058  4422  4513 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@789a642
09-23 04:28:09.058  5359  5405 I io.jxcore.node.ConnectionHelper: start: OK
09-23 04:28:09.066  4422  4510 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-23 04:28:09.066  4422  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 04:28:09.067  4422  4513 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 04:28:09.073  4422  4510 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 04:28:09.074  4422  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 04:28:09.074  4422  4513 D BtGatt.ScanManager: Starting BLE batch scan
09-23 04:28:09.074  4422  4513 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-23 04:28:09.086  4422  4510 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-23 04:28:09.087  4422  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 04:28:09.093  4422  4510 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 04:28:09.093  4422  4510 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 04:28:09.558  5359  5359 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 04:28:09.559  5359  5359 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 04:28:09.559  5359  5359 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 04:28:09.815   931  2935 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 04:28:09.822   931  2935 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,09-23 04:28:09.858   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 04:28:10.859   537   537 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 04:28:11.859   537   537 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-23 04:28:12.849   931  2935 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,09-23 04:28:12.855   931  2935 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60

```
