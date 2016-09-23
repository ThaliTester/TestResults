#### Test 86453613e903f38_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
09-23 02:09:46.338   931  5114 D NetlinkSocketObserver: NeighborEvent{elapsedMs=178717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-23 02:09:48.384  5353  5353 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-23 02:09:48.389  5353  5353 D AndroidRuntime: CheckJNI is OFF
09-23 02:09:48.417  5353  5353 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-23 02:09:48.450  5353  5353 I Radio-JNI: register_android_hardware_Radio DONE
09-23 02:09:48.465  5353  5353 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-23 02:09:48.468   931  3482 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-23 02:09:48.516   931  3482 I ActivityManager: Start proc 5362:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
09-23 02:09:48.529  5353  5353 D AndroidRuntime: Shutting down VM
,09-23 02:09:48.854   931  3475 I WindowManager: Screenshot max retries 4 of Token{c3c43b3 ActivityRecord{8bead22 u0 com.test.thalitest/.MainActivity t2}} appWin=Window{adcbe7a u0 Starting com.test.thalitest} drawState=4
,09-23 02:09:48.938  5362  5362 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,09-23 02:09:48.971  5362  5362 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-23 02:09:49.043  5362  5362 I LibraryLoader: Time to load native libraries: 67 ms (timestamps 1355-1422)
09-23 02:09:49.044  5362  5362 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-23 02:09:49.083  5362  5362 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e173c62}
09-23 02:09:49.084  5362  5362 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-23 02:09:49.084  5362  5362 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-23 02:09:49.090  5362  5362 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-23 02:09:49.092  5362  5362 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-23 02:09:49.142  5362  5362 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-23 02:09:49.158  5362  5362 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-23 02:09:49.158  5362  5362 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-23 02:09:49.158  5362  5362 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
09-23 02:09:49.158  5362  5362 I Adreno  : Build Date                       : 12/06/15
09-23 02:09:49.158  5362  5362 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-23 02:09:49.158  5362  5362 I Adreno  : Local Branch                     : mybranch17112971
09-23 02:09:49.158  5362  5362 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
09-23 02:09:49.158  5362  5362 I Adreno  : Remote Branch                    : NONE
09-23 02:09:49.158  5362  5362 I Adreno  : Reconstruct Branch               : NOTHING
,09-23 02:09:49.217   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d0a2d2:true
,09-23 02:09:49.247   403   403 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[28197]" dev="sockfs" ino=28197 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 02:09:49.247   403   403 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[28197]" dev="sockfs" ino=28197 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 02:09:49.261  5362  5362 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-23 02:09:49.269  5362  5362 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,09-23 02:09:49.294  2881  2881 W Binder_4: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[29250]" dev="sockfs" ino=29250 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-23 02:09:49.294  2881  2881 W Binder_4: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[29250]" dev="sockfs" ino=29250 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-23 02:09:49.298  5362  5399 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-23 02:09:49.297  3752  3752 W Binder_C: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[28203]" dev="sockfs" ino=28203 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
09-23 02:09:49.297  3752  3752 W Binder_C: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[28203]" dev="sockfs" ino=28203 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,09-23 02:09:49.306  5362  5386 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-23 02:09:49.330  5362  5399 I OpenGLRenderer: Initialized EGL, version 1.4
,09-23 02:09:49.415   931   949 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +558ms (total +933ms)
,09-23 02:09:49.451  5362  5362 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5362
,09-23 02:09:49.557  5362  5362 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-23 02:09:49.919  5362  5402 D jxcore_app_log: JniHelper::setJavaVM(0xf537c000), pthread_self() = -583530192
,09-23 02:09:49.939  5362  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-23 02:09:49.939  5362  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-23 02:09:49.939  5362  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-23 02:09:49.939  5362  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-23 02:09:49.939  5362  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-23 02:09:49.940  5362  5402 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d040c2b added. We now have 1 listener(s)
,09-23 02:09:49.948  5362  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,09-23 02:09:49.953  5362  5402 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 02:09:49.956  5362  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 02:09:49.957  5362  5402 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-23 02:09:49.963  5362  5402 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4cf5646 added. We now have 1 listener(s)
,09-23 02:09:49.964  5362  5402 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 02:09:49.970   931  2890 D WifiService: New client listening to asynchronous messages
09-23 02:09:49.971  5362  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-23 02:09:49.971  5362  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-23 02:09:49.971  5362  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-23 02:09:49.972  5362  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-23 02:09:49.972  5362  5402 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-23 02:09:49.977  5362  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 02:09:49.977  5362  5402 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,09-23 02:09:49.985  5362  5402 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:09:49.986  5362  5402 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 02:09:49.986  5362  5402 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-23 02:09:49.986  5362  5402 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 02:09:49.987  5362  5402 I io.jxcore.node.LifeCycleMonitor: start: OK
09-23 02:09:49.989  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:09:49.994  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:09:50.021  5362  5362 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-23 02:09:51.012  5362  5362 I Choreographer: Skipped 58 frames!  The application may be doing too much work on its main thread.
,09-23 02:09:51.214  5362  5408 W jxcore-log: Initializing JXcore engine
09-23 02:09:51.214  5362  5408 W jxcore-log: JXcore engine is ready
,09-23 02:09:51.237  5408  5408 W Thread-57: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11747 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-23 02:09:51.237  5408  5408 W Thread-57: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[12847]" dev="sockfs" ino=12847 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-23 02:09:51.237  5408  5408 W Thread-57: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-23 02:09:51.237  5408  5408 W Thread-57: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32806]" dev="sockfs" ino=32806 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,09-23 02:09:51.248  5362  5408 W jxcore-log: Starting JXcore engine
,09-23 02:09:51.304  5362  5408 W jxcore-log: Platform android
09-23 02:09:51.304  5362  5408 W jxcore-log: 
,09-23 02:09:51.304  5362  5408 W jxcore-log: Process ARCH arm
09-23 02:09:51.304  5362  5408 W jxcore-log: 
,09-23 02:09:51.399  5362  5408 I jxcore-log: JXcore Cordova bridge is ready!
09-23 02:09:51.399  5362  5408 I jxcore-log: 
,09-23 02:09:51.399  5362  5408 W jxcore-log: JXcore engine is started
,09-23 02:09:51.407  5362  5402 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-23 02:09:51.413  5362  5362 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-23 02:09:57.939   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 02:09:58.077  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-23 02:09:58.077  5362  5408 I jxcore-log: 
,09-23 02:09:58.078  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-23 02:09:58.078  5362  5408 I jxcore-log: 
,09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:09:58.082  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 02:09:58.084  5362  5408 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 02:09:58.085  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-23 02:09:58.085  5362  5408 I jxcore-log: 
,09-23 02:09:58.087  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-23 02:09:58.087  5362  5408 I jxcore-log: 
,09-23 02:09:58.440  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 02:09:58.440  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7270d4 added. We now have 2 listener(s)
09-23 02:09:58.441  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:09:58.441  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 02:09:58.441  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 02:09:58.441  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 02:09:58.442  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@312d27d added. We now have 2 listener(s)
09-23 02:09:58.442  5362  5408 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 02:09:58.442  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 02:09:58.444  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:09:58.446  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 02:09:58.447  5362  5408 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 02:09:58.447  5362  5408 D io.jxcore.node.ConnectivityMonitor: start: OK
09-23 02:09:58.447  5362  5408 D ExecuteNativeTests: Running unit tests
,09-23 02:09:58.448  5362  5408 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 02:09:58.448   931  3090 D WifiService: setWifiEnabled: true pid=5362, uid=10077
09-23 02:09:58.448   931  3090 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 02:09:58.453  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:09:58.459  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:09:58.940   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 02:09:59.942   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 02:10:00.944   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 02:10:01.945   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,09-23 02:10:02.946   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,09-23 02:10:08.453  5362  5408 I com.test.thalitest.ThaliTestRunner: Running UT
,09-23 02:10:08.523  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-23 02:10:08.523  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2706407 added. We now have 3 listener(s)
09-23 02:10:08.524  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:10:08.524  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-23 02:10:08.524  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 02:10:08.524  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 02:10:08.525  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbee934 added. We now have 3 listener(s)
09-23 02:10:08.525  5362  5408 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 02:10:08.526  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 02:10:08.529  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:10:08.533  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 02:10:08.534  5362  5408 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:08.535  5362  5408 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 02:10:08.538  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:08.539  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:08.541  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
09-23 02:10:08.542  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 02:10:08.542  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 02:10:08.542  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 02:10:08.542  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 02:10:08.542  5362  5408 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-23 02:10:08.543  5362  5408 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 02:10:08.543  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-23 02:10:08.543  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:08.543  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:08.543  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:08.543  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
,09-23 02:10:08.544  5362  5408 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-23 02:10:08.545  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
09-23 02:10:08.547  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
,09-23 02:10:08.547  5362  5408 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 02:10:08.547  5362  5408 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 02:10:08.547  5362  5408 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-23 02:10:08.547  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
09-23 02:10:08.547  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:08.547  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 02:10:08.547  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-23 02:10:08.547  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:08.548  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 02:10:08.548  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 02:10:08.549  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 02:10:08.549  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-23 02:10:08.549  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 02:10:08.549  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:08.549  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 02:10:08.549  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 02:10:08.551  5362  5408 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 02:10:08.551  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 02:10:08.553  5362  5410 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:08.554  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 02:10:08.551  4415  4415 W Binder_2: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[29263]" dev="sockfs" ino=29263 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:08.551  4415  4415 W Binder_2: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[29263]" dev="sockfs" ino=29263 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:08.555  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 02:10:08.555  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 02:10:08.556  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 02:10:08.556  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 02:10:08.556  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
09-23 02:10:08.556  5362  5410 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 02:10:08.557  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:08.557  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:08.557  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 02:10:08.557  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:08.560  4400  4611 D BtGatt.GattService: registerClient() - UUID=c802d894-0aa4-4549-9dbe-89fbf92d4cab
,09-23 02:10:08.562  4400  4462 D BtGatt.GattService: onClientRegistered() - UUID=c802d894-0aa4-4549-9dbe-89fbf92d4cab, clientIf=5
,09-23 02:10:08.564  5362  5373 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 02:10:08.567  4400  4466 D BtGatt.AdvertiseManager: message : 0
,09-23 02:10:08.570  4400  4466 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 02:10:08.584  4400  4462 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 02:10:08.591  4400  4462 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 02:10:08.593  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 02:10:08.593  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 02:10:08.593  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 02:10:08.594  5362  5408 I io.jxcore.node.ConnectionHelper: start: OK
09-23 02:10:08.595  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-23 02:10:08.595  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 02:10:08.595  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 02:10:08.595  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 02:10:08.595  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 02:10:08.595  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 02:10:08.599  5362  5362 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 02:10:08.599  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 02:10:09.097  5362  5408 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 02:10:09.098  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-23 02:10:09.099  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-23 02:10:09.100  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 02:10:09.101  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 02:10:09.101  5362  5408 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-23 02:10:09.101  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-23 02:10:09.101  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 02:10:09.101  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 02:10:09.101  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 02:10:09.101  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 02:10:09.101  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 02:10:09.102  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 02:10:09.102  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 02:10:09.102  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 02:10:09.102  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-23 02:10:09.102  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 02:10:09.103  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 02:10:09.103  5362  5410 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 02:10:09.103  5362  5410 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 02:10:09.103  5362  5410 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 02:10:09.104  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 02:10:09.105  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:09.105  5362  5408 D BluetoothLeScanner: could not find callback wrapper
09-23 02:10:09.106  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 02:10:09.106  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 02:10:09.107  4400  4466 D BtGatt.AdvertiseManager: message : 1
09-23 02:10:09.108  4400  4466 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 02:10:09.120  4400  4462 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 02:10:09.120  4400  4462 D BtGatt.GattService: Client app is not null!
09-23 02:10:09.121  4400  4412 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 02:10:09.122  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 02:10:09.122  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
09-23 02:10:09.122  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 02:10:09.122  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 02:10:09.123  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 02:10:09.125  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:09.125  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 02:10:09.126  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 02:10:09.127  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 02:10:09.130  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-23 02:10:09.130  5362  5362 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 02:10:09.131  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 02:10:09.131  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:09.131  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:09.131  5362  5408 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 02:10:09.131  5362  5362 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 02:10:09.131  5362  5408 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 02:10:09.131  5362  5408 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
09-23 02:10:09.131  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:09.132  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
09-23 02:10:09.132  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:09.132  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 02:10:09.132  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-23 02:10:09.132  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:09.133  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 02:10:09.134  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 02:10:09.134  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 02:10:09.134  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 02:10:09.134  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 02:10:09.134  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 02:10:09.134  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:09.134  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 02:10:09.136  5362  5413 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 02:10:09.138  5362  5408 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 02:10:09.138  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 02:10:09.134  4415  4415 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32266]" dev="sockfs" ino=32266 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:09.134  4415  4415 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32266]" dev="sockfs" ino=32266 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:09.139  5362  5413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 02:10:09.141  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 02:10:09.142  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 02:10:09.142  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 02:10:09.144  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 02:10:09.144  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:10:09.144  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
,09-23 02:10:09.144  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:09.145  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:09.145  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 02:10:09.145  5362  5408 D BluetoothAdapter: STATE_ON
,09-23 02:10:09.151  4400  4412 D BtGatt.GattService: registerClient() - UUID=4cd7c522-d30b-43cc-83c0-080626ae1077
,09-23 02:10:09.151  4400  4462 D BtGatt.GattService: onClientRegistered() - UUID=4cd7c522-d30b-43cc-83c0-080626ae1077, clientIf=5
09-23 02:10:09.151  5362  5373 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 02:10:09.152  4400  4466 D BtGatt.AdvertiseManager: message : 0
,09-23 02:10:09.154  4400  4466 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 02:10:09.166  4400  4462 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 02:10:09.171  4400  4462 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 02:10:09.172  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 02:10:09.172  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-23 02:10:09.173  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 02:10:09.174  5362  5408 I io.jxcore.node.ConnectionHelper: start: OK
,09-23 02:10:09.174  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:09.175  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 02:10:09.175  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 02:10:09.175  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 02:10:09.175  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 02:10:09.175  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 02:10:09.177  5362  5362 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 02:10:09.177  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 02:10:09.553   931  2889 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-23 02:10:09.678  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 02:10:09.679  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
,09-23 02:10:09.679  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-23 02:10:09.679  5362  5408 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 02:10:09.679  5362  5362 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 02:10:09.679  5362  5408 V io.jxcore.node.ConnectivityMonitor: start: Already started
,09-23 02:10:09.679  5362  5408 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
09-23 02:10:09.679  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 02:10:09.680  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 02:10:09.682  4400  4466 D BtGatt.AdvertiseManager: message : 1
,09-23 02:10:09.684  4400  4466 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 02:10:09.703  4400  4462 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 02:10:09.703  4400  4462 D BtGatt.GattService: Client app is not null!
09-23 02:10:09.704  4400  4415 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 02:10:09.707  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 02:10:09.707  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 02:10:09.707  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 02:10:09.707  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 02:10:09.708  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
,09-23 02:10:09.708  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,09-23 02:10:09.708  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,09-23 02:10:09.708  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:09.709  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 02:10:09.711  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:09.717  4400  4632 D BtGatt.GattService: registerClient() - UUID=67307863-9a02-41d0-bc7d-0be09b081fa7
,09-23 02:10:09.718  4400  4462 D BtGatt.GattService: onClientRegistered() - UUID=67307863-9a02-41d0-bc7d-0be09b081fa7, clientIf=5
09-23 02:10:09.718  5362  5373 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 02:10:09.720  4400  4466 D BtGatt.AdvertiseManager: message : 0
,09-23 02:10:09.725  4400  4466 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 02:10:09.742  4400  4462 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 02:10:09.752  4400  4462 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 02:10:09.754  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,09-23 02:10:09.754  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 02:10:09.754  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 02:10:09.754  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 02:10:09.754  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 02:10:09.754  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-23 02:10:09.754  5362  5408 I io.jxcore.node.ConnectionHelper: start: OK
09-23 02:10:09.755  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-23 02:10:09.755  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 02:10:09.756  5362  5408 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-23 02:10:09.756  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 02:10:09.756  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 02:10:09.757  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 02:10:09.757  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-23 02:10:09.757  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 02:10:09.757  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 02:10:09.757  5362  5413 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 02:10:09.757  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 02:10:09.757  5362  5413 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 02:10:09.757  5362  5413 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 02:10:09.757  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 02:10:09.757  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 02:10:09.758  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 02:10:09.758  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 02:10:09.758  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-23 02:10:09.758  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 02:10:09.759  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:09.760  5362  5408 D BluetoothLeScanner: could not find callback wrapper
09-23 02:10:09.760  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 02:10:09.760  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 02:10:09.761  4400  4466 D BtGatt.AdvertiseManager: message : 1
,09-23 02:10:09.762  4400  4466 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 02:10:09.772  4400  4462 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 02:10:09.772  4400  4462 D BtGatt.GattService: Client app is not null!
,09-23 02:10:09.773  4400  4611 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 02:10:09.774  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 02:10:09.774  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 02:10:09.774  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 02:10:09.774  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 02:10:09.774  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 02:10:09.775  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:09.775  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 02:10:09.775  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 02:10:09.776  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-23 02:10:09.778  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 02:10:09.778  5362  5362 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 02:10:09.778  5362  5362 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 02:10:09.778  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:09.778  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:09.778  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:09.780  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
09-23 02:10:09.780  5362  5408 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-23 02:10:09.782  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,09-23 02:10:09.782  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 02:10:09.783  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
09-23 02:10:09.783  5362  5408 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-23 02:10:09.784  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
09-23 02:10:09.785  5362  5408 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-23 02:10:09.786  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
09-23 02:10:09.787  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 02:10:09.787  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 02:10:09.787  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 02:10:09.787  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 02:10:09.787  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 02:10:09.787  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:09.788  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:09.788  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:09.788  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-23 02:10:09.788  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 02:10:09.788  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-23 02:10:09.788  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-23 02:10:09.789  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
09-23 02:10:09.789  5362  5408 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 02:10:09.790  5362  5408 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 02:10:09.790  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-23 02:10:09.794  5362  5408 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 02:10:09.794  5362  5408 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,09-23 02:10:09.794  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-23 02:10:09.794  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-23 02:10:09.794  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-23 02:10:09.795  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-23 02:10:09.796  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-23 02:10:09.796  5362  5408 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-23 02:10:09.797  5362  5408 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 02:10:09.797  5362  5408 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-23 02:10:09.797  5362  5408 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 02:10:09.797  5362  5408 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 02:10:09.797  5362  5408 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-23 02:10:09.797  5362  5408 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 02:10:09.797  5362  5408 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-23 02:10:09.797  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-23 02:10:09.804  4611  4611 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[33793]" dev="sockfs" ino=33793 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:09.804  4611  4611 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[33793]" dev="sockfs" ino=33793 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:09.803  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-23 02:10:09.804  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
09-23 02:10:09.804  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-23 02:10:09.805  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-23 02:10:09.805  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-23 02:10:09.805  5362  5408 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-23 02:10:09.805  5362  5408 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-23 02:10:09.805  5362  5408 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-23 02:10:09.805  5362  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 129)
09-23 02:10:09.806  5362  5417 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
09-23 02:10:09.806  5362  5417 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:09.807  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
09-23 02:10:09.807  5362  5408 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-23 02:10:09.809  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
09-23 02:10:09.809  5362  5408 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-23 02:10:09.810  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
09-23 02:10:09.810  5362  5408 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-23 02:10:09.810  5362  5408 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-23 02:10:09.810  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 02:10:09.810  5362  5408 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-23 02:10:09.810  5362  5408 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 02:10:09.810  5362  5408 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-23 02:10:09.810  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 02:10:09.810  5362  5408 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-23 02:10:09.810  5362  5408 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-23 02:10:09.810  5362  5408 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-23 02:10:09.811  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 02:10:09.811  5362  5408 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-23 02:10:09.811  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
09-23 02:10:09.811  5362  5408 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
09-23 02:10:09.811  5362  5408 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-23 02:10:09.812  5362  5408 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
09-23 02:10:09.812  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
09-23 02:10:09.812  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:09.812  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 02:10:09.812  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 02:10:09.812  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:09.813  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 02:10:09.813  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 02:10:09.814  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 02:10:09.814  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 02:10:09.814  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 02:10:09.814  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:09.814  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 02:10:09.814  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 02:10:09.814  5362  5418 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:09.814  4632  4632 W Binder_4: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[29282]" dev="sockfs" ino=29282 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:09.814  4632  4632 W Binder_4: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[29282]" dev="sockfs" ino=29282 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:09.818  5362  5418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 02:10:09.819  5362  5408 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-23 02:10:09.819  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-23 02:10:09.822  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-23 02:10:09.823  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 02:10:09.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 02:10:09.825  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 02:10:09.825  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:10:09.826  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
09-23 02:10:09.826  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:09.826  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:09.826  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 02:10:09.827  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:09.829  4400  4632 D BtGatt.GattService: registerClient() - UUID=fbbd3d2f-36dc-4456-a24c-ebca7cf09137
09-23 02:10:09.829  4400  4462 D BtGatt.GattService: onClientRegistered() - UUID=fbbd3d2f-36dc-4456-a24c-ebca7cf09137, clientIf=5
09-23 02:10:09.830  5362  5373 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
09-23 02:10:09.834  4400  4466 D BtGatt.AdvertiseManager: message : 0
09-23 02:10:09.836  4400  4466 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 02:10:09.848  4400  4462 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
09-23 02:10:09.854  4400  4462 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
09-23 02:10:09.854  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 02:10:09.854  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 02:10:09.855  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 02:10:09.856  5362  5408 I io.jxcore.node.ConnectionHelper: start: OK
09-23 02:10:09.856  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:09.856  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 02:10:09.857  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 02:10:09.857  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 02:10:09.857  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 02:10:09.857  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
09-23 02:10:09.859  5362  5362 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 02:10:09.859  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 02:10:10.358  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 02:10:10.358  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 02:10:10.358  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 02:10:10.358  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,09-23 02:10:10.359  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 02:10:10.359  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 02:10:10.359  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 02:10:10.359  5362  5418 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 02:10:10.359  5362  5418 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 02:10:10.359  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-23 02:10:10.359  5362  5418 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 02:10:10.360  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-23 02:10:10.361  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 02:10:10.361  5362  5362 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-23 02:10:10.363  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2706407 removed from the list
,09-23 02:10:10.364  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 02:10:10.364  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 02:10:10.364  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-23 02:10:10.364  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 02:10:10.364  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 02:10:10.364  5362  5419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 129
09-23 02:10:10.365  5362  5419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 129)
,09-23 02:10:10.365  5362  5419 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 129)
09-23 02:10:10.366  5362  5417 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 129)
09-23 02:10:10.366  4400  4609 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
09-23 02:10:10.368  5362  5408 D BluetoothAdapter: STATE_ON
,09-23 02:10:10.368  5362  5408 D BluetoothLeScanner: could not find callback wrapper
09-23 02:10:10.368  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 02:10:10.368  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 02:10:10.370  4400  4466 D BtGatt.AdvertiseManager: message : 1
09-23 02:10:10.371  4400  4466 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 02:10:10.382  4400  4462 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,09-23 02:10:10.382  4400  4462 D BtGatt.GattService: Client app is not null!
09-23 02:10:10.383  4400  4415 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 02:10:10.384  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 02:10:10.384  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 02:10:10.384  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 02:10:10.384  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 02:10:10.384  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 02:10:10.386  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:10.386  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 02:10:10.386  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 02:10:10.387  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 02:10:10.388  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbee934 removed from the list
09-23 02:10:10.388  5362  5408 D io.jxcore.node.ConnectivityMonitor: stop
09-23 02:10:10.388  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:10.388  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 02:10:10.388  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:10.388  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 02:10:10.391  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,09-23 02:10:10.391  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 02:10:10.392  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:10.392  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-23 02:10:10.393  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-23 02:10:10.393  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-23 02:10:10.393  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 02:10:10.393  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 02:10:10.393  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-23 02:10:10.394  5362  5420 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 02:10:10.394  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
09-23 02:10:10.395  5362  5408 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-23 02:10:10.396  5362  5408 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-23 02:10:10.396  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-23 02:10:10.396  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:10.396  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-23 02:10:10.397  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
09-23 02:10:10.399  5362  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 02:10:10.391  4412  4412 W Binder_1: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32869]" dev="sockfs" ino=32869 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:10.394  4412  4412 W Binder_1: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32869]" dev="sockfs" ino=32869 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 02:10:10.402  5362  5408 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
09-23 02:10:10.403  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 02:10:10.403  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-23 02:10:10.403  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 02:10:10.403  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 02:10:10.403  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 02:10:10.403  5362  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 02:10:10.404  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 02:10:10.404  5362  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 02:10:10.404  5362  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 02:10:10.404  5362  5408 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2706407 not in the list
09-23 02:10:10.404  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 02:10:10.404  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 02:10:10.404  5362  5362 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-23 02:10:10.404  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 02:10:10.404  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 02:10:10.404  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 02:10:10.404  5362  5408 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 02:10:10.404  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 02:10:10.407  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:10.407  5362  5408 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cbee934 not in the list
,09-23 02:10:10.407  5362  5408 D io.jxcore.node.ConnectivityMonitor: stop
09-23 02:10:10.407  5362  5408 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 02:10:10.407  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 02:10:10.407  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:10.407  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:10.408  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:10.408  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
09-23 02:10:10.409  5362  5408 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-23 02:10:10.409  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-23 02:10:10.409  5362  5408 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-23 02:10:10.409  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-23 02:10:10.409  5362  5408 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-23 02:10:10.409  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-23 02:10:10.410  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
,09-23 02:10:10.410  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
,09-23 02:10:10.412  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
09-23 02:10:10.412  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-23 02:10:10.412  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-23 02:10:10.412  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
09-23 02:10:10.413  5362  5408 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-23 02:10:10.413  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 02:10:10.413  5362  5408 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-23 02:10:10.413  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-23 02:10:10.413  5362  5408 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-23 02:10:10.413  5362  5408 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-23 02:10:10.414  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
09-23 02:10:10.414  5362  5408 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-23 02:10:10.414  5362  5408 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-23 02:10:10.414  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
09-23 02:10:10.414  5362  5408 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-23 02:10:10.415  5362  5408 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-23 02:10:10.415  5362  5408 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-23 02:10:10.415  5362  5408 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-23 02:10:10.415  5362  5408 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
,09-23 02:10:10.415  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 02:10:10.415  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b890764 added. We now have 3 listener(s)
09-23 02:10:10.418  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:10:10.418  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 02:10:10.418  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 02:10:10.418  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-23 02:10:10.418  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f0cdcd added. We now have 3 listener(s)
09-23 02:10:10.418  5362  5408 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 02:10:10.419  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 02:10:10.422  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:10:10.425  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 02:10:10.427  5362  5408 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:10.427  5362  5408 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 02:10:10.428  5362  5408 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 02:10:10.429   931  3745 D WifiService: setWifiEnabled: true pid=5362, uid=10077
,09-23 02:10:10.429   931  3745 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 02:10:10.430  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:10.430  5362  5408 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
09-23 02:10:10.432  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:10.433  5362  5408 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
09-23 02:10:10.434  5362  5408 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testStartStop
,09-23 02:10:10.437   931  3091 D WifiService: setWifiEnabled: false pid=5362, uid=10077
09-23 02:10:10.437   931  3091 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 02:10:10.440   931  2889 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-23 02:10:10.440   931  2889 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-23 02:10:10.440   931  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 02:10:10.440   931  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 02:10:10.452   508   930 D CommandListener: Clearing all IP addresses on wlan0
09-23 02:10:10.452   931  5115 D DhcpClient: Clearing IP address
,09-23 02:10:10.455   508   930 D CommandListener: Setting iface cfg
,09-23 02:10:10.458   931  5116 D DhcpClient: Receive thread stopped
,09-23 02:10:10.464  3535  5171 V NativeCrypto: Read error: ssl=0x7f5eff5000: I/O error during system call, Connection timed out
09-23 02:10:10.466  3535  5171 V NativeCrypto: SSL shutdown failed: ssl=0x7f5eff5000: I/O error during system call, Broken pipe
,09-23 02:10:10.466   931  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-23 02:10:10.466   931  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-23 02:10:10.471   931   931 D RttService: SCAN_AVAILABLE : 1
,09-23 02:10:10.472   931  2998 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-23 02:10:10.472   534   534 E Parcel  : Reading a NULL string not supported here.
,09-23 02:10:10.475   931  2891 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-23 02:10:10.478  3422  3540 W QCNEJ   : |CORE| network lost: 100
09-23 02:10:10.479  3422  3540 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,09-23 02:10:10.487   931  2889 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-23 02:10:10.495   931  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 02:10:10.503   508   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 02:10:10.528   508   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-23 02:10:10.528   508   930 D CommandListener: Clearing all IP addresses on wlan0
09-23 02:10:10.529   508   930 D TetherController: Setting IP forward enable = 0
,09-23 02:10:10.530   931  2891 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-23 02:10:10.530   931  2891 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 02:10:10.531   931  2889 D DhcpClient: doQuit
09-23 02:10:10.531   931  2889 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 02:10:10.532  3558  3558 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 02:10:10.533   931  5115 D DhcpClient: onQuitting
,09-23 02:10:10.537   931   948 D Tethering: MasterInitialState.processMessage what=3
,09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:10.542  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:10.540  4184  4184 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dc9c76e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-23 02:10:10.546  3558  3558 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,09-23 02:10:10.547  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:10.551  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:10.551  3558  3558 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-23 02:10:10.553  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:10.554   508   923 W SocketClient: write error (Broken pipe)
09-23 02:10:10.554   508   923 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
09-23 02:10:10.554   508   923 W SocketListener: Error sending broadcast (Broken pipe)
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:10.557  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:10.559  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:10.561  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:10.562  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:10.564  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:10.565  4821  4836 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
09-23 02:10:10.565  4821  4836 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 02:10:10.566  4821  4836 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
09-23 02:10:10.566  4821  4836 E SarControlService: no key has been found,reset the power
09-23 02:10:10.566  4821  4862 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,09-23 02:10:10.566  4821  4862 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 02:10:10.566  4821  4862 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 02:10:10.567  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 02:10:10.567  4850  4850 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,09-23 02:10:10.571  3861  3861 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 02:10:10.572  4821  4862 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 02:10:10.573  4821  4862 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 02:10:10.573  4821  4862 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 02:10:10.573  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 02:10:10.573  4850  4850 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 02:10:10.576  4850  4864 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@560d244 HexData = [00000000ea03000000000000ffffffff]
09-23 02:10:10.576  4850  4864 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-23 02:10:10.576  4850  4864 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
09-23 02:10:10.576  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 02:10:10.576  4821  4832 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 02:10:10.577  3861  3861 D SystemUpdateService: onCreate
09-23 02:10:10.581  4850  4864 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@560d244 HexData = [00000000eb03000000000000ffffffff]
09-23 02:10:10.581  4850  4864 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 02:10:10.581  4850  4864 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,09-23 02:10:10.582  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 02:10:10.582  4821  4833 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 02:10:10.583  3861  3861 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-23 02:10:10.592  3861  3861 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-23 02:10:10.595   508   930 E Netd    : netlink response contains error (No such file or directory)
09-23 02:10:10.596   508   930 D TetherController: Setting IP forward enable = 0
09-23 02:10:10.599  3861  5439 I SystemUpdateService: active receiver: enabled
,09-23 02:10:10.600  3861  5143 I iu.UploadsManager: num queued entries: 0
09-23 02:10:10.600  3861  5143 I iu.UploadsManager: num updated entries: 0
,09-23 02:10:10.601  3861  5143 I iu.SyncManager: NEXT; no task
09-23 02:10:10.602  3558  3558 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
09-23 02:10:10.603  3861  3861 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 02:10:10.604  3861  3861 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 02:10:10.607  5145  5145 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 02:10:10.611  5145  5145 D SprintDMHelper: simOperator: 
09-23 02:10:10.611  5145  5145 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-23 02:10:10.613  3558  3558 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 02:10:10.620  3861  5439 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 02:10:10.624  4244  5444 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-23 02:10:10.626  3861  5439 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-23 02:10:10.626  3861  5439 I SystemUpdateService: now status is 0 (complete)
09-23 02:10:10.626  3861  5439 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 02:10:10.626  3861  5439 I SystemUpdateService: file has been verified
09-23 02:10:10.627  3861  5439 I SystemUpdateService: OTA package size = 21989297
,09-23 02:10:10.632  3861  5439 I SystemUpdateService: showing system update notification
,09-23 02:10:10.636   931  3433 I ActivityManager: Start proc 5445:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-23 02:10:10.649  3861  3861 D SystemUpdateService: onDestroy
,09-23 02:10:10.662  5445  5445 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,09-23 02:10:10.669   931  3090 I ActivityManager: Killing 4802:com.google.android.calendar/u0a36 (adj 15): empty #17
,09-23 02:10:10.717  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 02:10:10.717   931  2889 D wifi    : In wifi stop Hal
09-23 02:10:10.717   931  2889 D wifi    : halHandle = 0x7f5d9ba000, mVM = 0x7f79fcd140, mCls = 0x200af6
,09-23 02:10:10.717   931  3556 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-23 02:10:10.717   931  3556 D WifiHAL : Got a signal to exit!!!
09-23 02:10:10.717   931  3556 I WifiHAL : Exit wifi_event_loop
,09-23 02:10:10.717   931  2889 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
09-23 02:10:10.717   931  2889 E WifiHAL : Event processing terminated
,09-23 02:10:10.717   931  2889 D wifi    : In wifi cleaned up handler
09-23 02:10:10.717   931  2889 I WifiHAL : Internal cleanup completed
09-23 02:10:10.720  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:10.720  3566  3960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-23 02:10:10.721  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:10.722  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:10.750   931  3556 D wifi    : set interface wlan0 flags (DOWN)
,09-23 02:10:10.750   931  2889 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 02:10:10.909  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 02:10:10.946  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:10.950   931   942 D WifiService: setWifiEnabled: true pid=5362, uid=10077
,09-23 02:10:10.950   931   942 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 02:10:10.957   931   948 D Tethering: InitialState.processMessage what=4
,09-23 02:10:10.962   508   930 D SoftapController: Softap fwReload - Ok
,09-23 02:10:10.966   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 02:10:10.967   508   930 D CommandListener: Setting iface cfg
09-23 02:10:10.968   508   930 D CommandListener: Trying to bring down wlan0
,09-23 02:10:10.969   508   930 D CommandListener: Clearing all IP addresses on wlan0
,09-23 02:10:10.975   931  2889 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 02:10:11.460   931  3752 D WifiService: setWifiEnabled: true pid=5362, uid=10077
,09-23 02:10:11.461   931  3752 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 02:10:11.584   931  2889 D wifi    : set interface wlan0 flags (UP)
,09-23 02:10:11.585   931  2889 I WifiHAL : Initializing wifi
09-23 02:10:11.585   931  2889 I WifiHAL : Creating socket
,09-23 02:10:11.587   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 02:10:11.593   931  2889 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,09-23 02:10:11.593   931  2889 D wifi    : Did set static halHandle = 0x7f5d9ba000
,09-23 02:10:11.593   931  2889 D wifi    : halHandle = 0x7f5d9ba000, mVM = 0x7f79fcd140, mCls = 0x2018ea
09-23 02:10:11.593   931  2889 D wifi    : array field set
09-23 02:10:11.594   931  2889 I WifiNative-HAL: interface[0] = wlan0
,09-23 02:10:11.596   931  5460 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547031326720
09-23 02:10:11.596   931  5460 D wifi    : waitForHalEvents called, vm = 0x7f79fcd140, obj = 0x2018ea, env = 0x7f5d99e840
,09-23 02:10:11.683  5461  5461 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 02:10:11.697   931  2889 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 02:10:11.705  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:11.706  5461  5461 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-23 02:10:11.710  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:11.713  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:11.726  5461  5461 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 02:10:11.726  5461  5461 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 02:10:11.741   931  2889 D WifiConfigStore: Loading config and enabling all networks 
,09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:11.745  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:11.748  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:11.751  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:11.752   931  2889 D WifiConfigStore: loaded 0 passpoint configs
09-23 02:10:11.752  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:11.752   931  2889 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 02:10:11.753   931  2889 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-23 02:10:11.753   931  2889 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-23 02:10:11.754   931  2889 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-23 02:10:11.754   931  2889 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 02:10:11.754   931  2889 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 02:10:11.754   931  2889 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:11.755  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:11.756  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:11.757   931  2889 D WifiNative-HAL: Setting external_sim to 1
09-23 02:10:11.757   931  2889 D wifi    : setting dfs flag to true, 0x7f62502be0
09-23 02:10:11.757   931  2889 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 02:10:11.757   931  2889 D wifi    : setting scan oui 0x7f62502be0
09-23 02:10:11.757   931  2889 D WifiHAL : Sending mac address OUI
09-23 02:10:11.758  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 02:10:11.761   931  2889 E native  : do suspend false
,09-23 02:10:11.768   931  2889 D wifi    : android_net_wifi_setLinkLayerStats: 1
,09-23 02:10:11.768   931   931 D RttService: SCAN_AVAILABLE : 3
09-23 02:10:11.768   931  2998 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 02:10:11.768   508   930 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-23 02:10:11.769   508   930 D CommandListener: Setting iface cfg
,09-23 02:10:11.772   931  2888 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '64 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 64 Failed to set address (No such device)'
,09-23 02:10:11.772   931  2888 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 02:10:11.781   931  2888 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 02:10:11.781   931  2888 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 02:10:11.786   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=204165 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,09-23 02:10:11.965  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:11.978  4400  4458 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 02:10:11.978  4400  4458 D BluetoothAdapterProperties: Setting state to 13
,09-23 02:10:11.978  4400  4458 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 02:10:11.980  4400  4458 D BluetoothAdapterProperties: onBluetoothDisable()
,09-23 02:10:11.985  4400  4458 I BluetoothAdapterState: Entering PendingCommandState
,09-23 02:10:11.986  4400  4400 D BluetoothMapService: onReceive
09-23 02:10:11.986  4400  4400 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 02:10:11.987  4400  4400 D BluetoothMapService: STATE_TURNING_OFF
09-23 02:10:11.987  4400  4400 D BluetoothMapService: MAP Service closeService in
09-23 02:10:11.987  4400  4400 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 02:10:11.987  4400  4400 D ObexServerSockets0: shutdown(block = true)
09-23 02:10:11.989  4400  4400 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 02:10:11.989  4400  4633 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
09-23 02:10:11.989  4400  4400 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-23 02:10:11.989  4400  4634 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-23 02:10:11.990  4400  4609 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-23 02:10:11.992  4400  4400 I BtOppRfcommListener: stopping Accept Thread
,09-23 02:10:11.992  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:11.992  4400  5068 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:11.992  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:11.992  4400  5068 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-23 02:10:11.994  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:11.994  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:11.997  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:11.997  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:11.998  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:11.998  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:12.000  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:12.001  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:12.002  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:12.002  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:12.008   931   944 I ActivityManager: Start proc 5465:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-23 02:10:12.009  4400  4462 D BluetoothAdapterProperties: Scan Mode:20
,09-23 02:10:12.009  4400  4458 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 02:10:12.012  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.012  4400  4400 D HeadsetService: Received stop request...Stopping profile...
09-23 02:10:12.015  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.017  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.019  3057  3648 D BluetoothHeadset: Proxy object disconnected
09-23 02:10:12.019  3057  3057 D HeadsetProfile: Bluetooth service disconnected
09-23 02:10:12.019  4400  4400 D A2dpService: Received stop request...Stopping profile...
09-23 02:10:12.019  3449  3472 D BluetoothHeadset: Proxy object disconnected
,09-23 02:10:12.019  4400  4626 D A2dpStateMachine: Exit Disconnected: -1
09-23 02:10:12.020   931   931 D BluetoothHeadset: Proxy object disconnected
09-23 02:10:12.020   931   931 D BluetoothHeadset: Proxy object disconnected
09-23 02:10:12.020   931   931 D BluetoothHeadset: Proxy object disconnected
09-23 02:10:12.020   931   931 D BluetoothA2dp: Proxy object disconnected
09-23 02:10:12.021  3057  3057 D BluetoothA2dp: Proxy object disconnected
,09-23 02:10:12.021  4400  4400 D HidService: Received stop request...Stopping profile...
09-23 02:10:12.021  4400  4400 D HidService: Stopping Bluetooth HidService
,09-23 02:10:12.023  3057  3057 D BluetoothInputDevice: Proxy object disconnected
09-23 02:10:12.023  3057  3057 D HidProfile: Bluetooth service disconnected
,09-23 02:10:12.024  4400  4400 D HealthService: Received stop request...Stopping profile...
09-23 02:10:12.025  4400  4400 V BluetoothAdapterState: isTurningOff()=true
,09-23 02:10:12.025  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.025  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:12.025  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 02:10:12.026  4400  4400 D PanService: Received stop request...Stopping profile...
09-23 02:10:12.027  3057  3057 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 02:10:12.027  3057  3057 D PanProfile: Bluetooth service disconnected
,09-23 02:10:12.029  4400  4400 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 02:10:12.029  4400  4400 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 02:10:12.029  4400  4606 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:12.029  4400  4606 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:12.029  4400  4606 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:12.029  4400  4400 D BluetoothMapService: Received stop request...Stopping profile...
09-23 02:10:12.029  4400  4462 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 02:10:12.029  4400  4400 D BluetoothMapService: stop()
09-23 02:10:12.029  4400  4462 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-23 02:10:12.030  4400  4400 D BluetoothMapAppObserver: deinitObservers()
09-23 02:10:12.030  4400  4400 D BluetoothMapAppObserver: removeReceiver()
09-23 02:10:12.031  3057  3057 D BluetoothMap: Proxy object disconnected
09-23 02:10:12.031  3057  3057 D MapProfile: Bluetooth service disconnected
09-23 02:10:12.031  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:12.031  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.031  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:12.031  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 02:10:12.033  4400  4606 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-23 02:10:12.033  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:12.033  4400  4606 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:12.033  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.033  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:12.033  4400  4606 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 02:10:12.033  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 02:10:12.033  4400  4606 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 02:10:12.033  4400  4606 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-23 02:10:12.033  4400  4606 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-23 02:10:12.033  4400  4462 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-23 02:10:12.034  4400  4400 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 02:10:12.034  4400  4400 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 02:10:12.034  4400  4462 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 02:10:12.035  4400  4400 D SapService: Received stop request...Stopping profile...
,09-23 02:10:12.035  4400  4400 V SapService: stop()
09-23 02:10:12.038  4400  4400 V BluetoothAdapterState: isTurningOff()=true
,09-23 02:10:12.038  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.038  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:12.038  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:12.038  4400  4400 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 02:10:12.038  4400  4462 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-23 02:10:12.039  4400  4400 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 02:10:12.039  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:12.039  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.039  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 02:10:12.039  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:12.039  4400  4400 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 02:10:12.039  4400  4400 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 02:10:12.040  4400  4400 D BluetoothMapService: MAP Service closeService in
09-23 02:10:12.040  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:12.040  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.040  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:12.040  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:12.041  4400  4400 D BluetoothMapService: cleanup()
09-23 02:10:12.041  4400  4400 D BluetoothMapService: MAP Service closeService in
09-23 02:10:12.041  4400  4400 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:12.042  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.042  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:12.042  4400  4400 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:12.042  4400  4458 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 02:10:12.042  4400  4458 D BluetoothAdapterProperties: Setting state to 15
09-23 02:10:12.042  4400  4458 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-23 02:10:12.043  4400  4458 I BluetoothAdapterState: Entering BleOnState
09-23 02:10:12.044  3449  3721 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:12.044  3057  3070 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:12.044  3057  3648 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 02:10:12.045  3057  3069 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 02:10:12.046   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:12.046   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:12.046  3057  3070 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 02:10:12.047   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:12.047  3057  3648 D BluetoothPan: onBluetoothStateChange on: false
09-23 02:10:12.048   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 02:10:12.048  3057  3069 D BluetoothMap: onBluetoothStateChange: up=false
09-23 02:10:12.049  4400  4458 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 02:10:12.049  4400  4458 D BluetoothAdapterProperties: Setting state to 16
09-23 02:10:12.049  4400  4458 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-23 02:10:12.050  4400  4458 D BluetoothAdapterProperties: onBleDisable
09-23 02:10:12.050  4400  4458 I BluetoothAdapterState: Entering PendingCommandState
09-23 02:10:12.050  4400  4459 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-23 02:10:12.052  4400  4606 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-23 02:10:12.052  4400  4606 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:12.052  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:12.052  4400  4462 D BluetoothAdapterProperties: Scan Mode:20
,09-23 02:10:12.054  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.056  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:12.055  5465  5465 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,09-23 02:10:12.057  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.059  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.060  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.072  5465  5465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 02:10:12.077   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ad7b1d:true
,09-23 02:10:12.077  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 02:10:12.091   931  3354 I ActivityManager: Start proc 5477:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-23 02:10:12.098  5465  5465 D LocalBluetoothProfileManager: Adding local MAP profile
,09-23 02:10:12.102  5465  5465 D BluetoothMap: Create BluetoothMap proxy object
,09-23 02:10:12.110  5465  5465 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-23 02:10:12.129  5465  5465 D DockEventReceiver: finishStartingService: stopping service
,09-23 02:10:12.130   931  3482 I ActivityManager: Killing 4184:com.google.android.music:main/u0a59 (adj 15): empty #17
,09-23 02:10:12.137  5477  5477 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,09-23 02:10:12.258  4400  4462 I bt_hci  : shut_down
,09-23 02:10:12.263  4400  4468 D bt_hwcfg: hw_epilog_process
,09-23 02:10:12.263  4400  4468 I bt_vendor: low_power_mode_cb
,09-23 02:10:12.265  4400  4468 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 02:10:12.266  4400  4468 I bt_vendor: epilog_cb
09-23 02:10:12.266  4400  4468 I bt_hci  : epilog_finished_callback
,09-23 02:10:12.269  4400  4462 I bt_hci_h4: hal_close
,09-23 02:10:12.269  4400  4462 I bt_userial_vendor: device fd = 54 close
,09-23 02:10:12.319  5477  5477 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-23 02:10:12.319  5477  5477 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 02:10:12.319  5477  5477 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 02:10:12.319  5477  5477 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.319  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 02:10:12.320  5477  5477 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.r.k.d(PG:583)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.r.e.b(PG:170)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 02:10:12.320  5477  5477 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 02:10:12.320  5477  5477 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.File.exists(File.java:361)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 02:10:12.320  5477  5477 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-23 02:10:12.320  5477  5477 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-23 02:10:12.323  5465  5465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 02:10:12.328  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 02:10:12.333  5465  5465 D DockEventReceiver: finishStartingService: stopping service
09-23 02:10:12.335   931  3475 I ActivityManager: Killing 4472:com.android.providers.calendar/u0a1 (adj 15): empty #17
,09-23 02:10:12.379  4400  4459 D bt_stack_manager: event_shut_down_stack finished.
09-23 02:10:12.379  4400  4458 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
09-23 02:10:12.382  4400  4458 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-23 02:10:12.382  4400  4400 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 02:10:12.382  4400  4400 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 02:10:12.383  4400  4400 D BtGatt.GattService: stop()
09-23 02:10:12.383  4400  4400 D BtGatt.AdvertiseManager: advertise clients cleared
09-23 02:10:12.384  4400  4400 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:12.385  4400  4400 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.385  4400  4400 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:12.385  4400  4400 V BluetoothAdapterState: isBleTurningOff()=true
09-23 02:10:12.385  4400  4458 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-23 02:10:12.385  4400  4458 D BluetoothAdapterProperties: Setting state to 10
09-23 02:10:12.385  4400  4458 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 02:10:12.386   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-23 02:10:12.386  4400  4458 I BluetoothAdapterState: Entering OffState
09-23 02:10:12.392  4400  4400 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 02:10:12.392  4400  4400 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-23 02:10:12.392  4400  4400 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 02:10:12.394  4400  4459 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 02:10:12.402  4400  4400 I art     : System.exit called, status: 0
,09-23 02:10:12.402  4400  4400 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 02:10:12.464   931  3475 I ActivityManager: Process com.android.bluetooth (pid 4400) has died
,09-23 02:10:12.477  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:12.491   931   948 I ActivityManager: Start proc 5510:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 02:10:12.552  5510  5510 D AdapterServiceConfig: Adding HeadsetService
,09-23 02:10:12.552  5510  5510 D AdapterServiceConfig: Adding A2dpService
09-23 02:10:12.552  5510  5510 D AdapterServiceConfig: Adding HidService
09-23 02:10:12.553  5510  5510 D AdapterServiceConfig: Adding HealthService
,09-23 02:10:12.553  5510  5510 D AdapterServiceConfig: Adding PanService
09-23 02:10:12.553  5510  5510 D AdapterServiceConfig: Adding GattService
09-23 02:10:12.553  5510  5510 D AdapterServiceConfig: Adding BluetoothMapService
,09-23 02:10:12.554  5510  5510 D AdapterServiceConfig: Adding SapService
,09-23 02:10:12.564   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@72d189a:true
,09-23 02:10:12.565  5510  5510 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 02:10:12.565  5477  5498 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-23 02:10:12.567  5510  5510 I bt_bluedroid: init
09-23 02:10:12.567  5510  5522 I BluetoothAdapterState: Entering OffState
,09-23 02:10:12.568  5510  5523 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 02:10:12.569  5510  5523 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-23 02:10:12.569  5510  5523 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 02:10:12.569  5510  5523 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-23 02:10:12.569  5510  5510 I bt_bluedroid: get_profile_interface socket
,09-23 02:10:12.571  5510  5526 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 02:10:12.571  5510  5510 I bt_bluedroid: get_profile_interface sdp
09-23 02:10:12.572  5510  5526 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 02:10:12.575  5510  5521 I bt_bluedroid: config_hci_snoop_log
,09-23 02:10:12.576   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-23 02:10:12.579  5510  5522 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 02:10:12.579   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@92ec3a7:true
09-23 02:10:12.579  5510  5522 D BluetoothAdapterProperties: Setting state to 14
09-23 02:10:12.579  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 02:10:12.580  5510  5522 D BluetoothBondStateMachine: make
,09-23 02:10:12.581  5510  5528 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 02:10:12.584  5510  5522 I BluetoothAdapterState: Entering PendingCommandState
,09-23 02:10:12.585  5510  5510 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 02:10:12.586  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:12.587  5510  5510 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 02:10:12.587  5510  5510 D BtGatt.GattService: Received start request. Starting profile...
,09-23 02:10:12.587  5510  5510 D BtGatt.GattService: start()
09-23 02:10:12.587  5510  5510 I bt_bluedroid: get_profile_interface gatt
09-23 02:10:12.588  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:12.588  5510  5510 D BtGatt.AdvertiseManager: advertise manager created
,09-23 02:10:12.592  5510  5510 V BluetoothAdapterState: isTurningOff()=false
,09-23 02:10:12.592  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:12.592  5510  5510 V BluetoothAdapterState: isBleTurningOn()=true
09-23 02:10:12.593  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:12.593  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 02:10:12.594  5510  5522 I bt_bluedroid: bt_bluedroid
09-23 02:10:12.594  5510  5523 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 02:10:12.594  5510  5523 I bt_hci  : start_up
,09-23 02:10:12.599  5510  5523 I bt_vendor: alloc value 0xf4039871
,09-23 02:10:12.599  5510  5523 I bt_vendor: init
09-23 02:10:12.599  5510  5523 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 02:10:12.599  5510  5523 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 02:10:12.707  5510  5523 D bt_hci  : start_up starting async portion
,09-23 02:10:12.707  5510  5532 I bt_hci  : event_finish_startup
09-23 02:10:12.707  5510  5532 I bt_hci_h4: hal_open
09-23 02:10:12.707  5510  5532 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
09-23 02:10:12.704  5533  5533 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
09-23 02:10:12.709  5510  5532 I bt_userial_vendor: device fd = 54 open
,09-23 02:10:12.722  5510  5532 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 02:10:12.724  5510  5532 D bt_hwcfg: Chipset BCM4358A3
,09-23 02:10:12.724  5510  5532 D bt_hwcfg: Target name = [BCM4358A3]
09-23 02:10:12.724  5510  5532 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 02:10:12.986  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 02:10:13.098  5510  5532 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 02:10:13.098  5510  5532 D bt_hwcfg: Settlement delay -- 100 ms
09-23 02:10:13.099  5510  5532 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 02:10:13.222  5510  5532 I bt_hwcfg: bt vendor lib: set UART baud 3000000
09-23 02:10:13.223  5510  5532 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
09-23 02:10:13.224  5510  5532 I bt_hwcfg: vendor lib fwcfg completed
09-23 02:10:13.224  5510  5532 I bt_vendor: firmware callback
09-23 02:10:13.224  5510  5532 I bt_hci  : firmware_config_callback
,09-23 02:10:13.232  5510  5535 I bt_btu  : btu_task pending for preload complete event
,09-23 02:10:13.232  5510  5535 I bt_btu_task: Bluetooth chip preload is complete
09-23 02:10:13.232  5510  5535 I bt_btu  : btu_task received preload complete event
,09-23 02:10:13.240  5510  5535 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 02:10:13.240  5510  5535 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_AVRC
09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_BNEP
09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_BTM
,09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_GAP
09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 02:10:13.241  5510  5535 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 02:10:13.242  5510  5535 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 02:10:13.242  5510  5535 I         : BTE_InitTraceLevels -- TRC_SMP
09-23 02:10:13.242  5510  5535 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-23 02:10:13.242  5510  5535 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 02:10:13.327  5510  5535 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fb7549
09-23 02:10:13.327  5510  5535 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fb7549 
,09-23 02:10:13.346  5510  5526 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 02:10:13.347  5510  5526 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-23 02:10:13.348  5510  5526 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 02:10:13.350  5510  5526 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 02:10:13.353  5510  5526 D BluetoothAdapterProperties: Scan Mode:20
,09-23 02:10:13.354  5510  5526 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 02:10:13.354  5510  5526 D bt_hci  : do_postload posting postload work item
,09-23 02:10:13.354  5510  5532 I bt_hci  : event_postload
09-23 02:10:13.354  5510  5532 I bt_vendor: sco_config_cb
09-23 02:10:13.354  5510  5532 I bt_hci  : sco_config_callback postload finished.
,09-23 02:10:13.357  5510  5526 D bt_bte_conf: Device ID record 1 : primary
09-23 02:10:13.358  5510  5526 D bt_bte_conf:   vendorId            = 000f
,09-23 02:10:13.358  5510  5526 D bt_bte_conf:   vendorIdSource      = 0001
09-23 02:10:13.358  5510  5526 D bt_bte_conf:   product             = 1200
09-23 02:10:13.358  5510  5526 D bt_bte_conf:   version             = 1436
09-23 02:10:13.358  5510  5526 D bt_bte_conf:   clientExecutableURL = 
09-23 02:10:13.358  5510  5526 D bt_bte_conf:   serviceDescription  = 
09-23 02:10:13.358  5510  5526 D bt_bte_conf:   documentationURL    = 
09-23 02:10:13.358  5510  5526 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 02:10:13.359  5510  5523 D bt_stack_manager: event_start_up_stack finished
09-23 02:10:13.361  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 02:10:13.361  5510  5522 D BluetoothAdapterProperties: Setting state to 15
09-23 02:10:13.361  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-23 02:10:13.362  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.364  5510  5522 I BluetoothAdapterState: Entering BleOnState
09-23 02:10:13.364  5510  5532 I bt_vendor: low_power_mode_cb
,09-23 02:10:13.366  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:13.368  5510  5522 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 02:10:13.368  5510  5522 D BluetoothAdapterProperties: Setting state to 11
,09-23 02:10:13.368  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-23 02:10:13.368  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.373  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.375  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.377  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:13.380  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 02:10:13.380  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:13.381  5510  5510 D HeadsetService: Received start request. Starting profile...
,09-23 02:10:13.384  5510  5510 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-23 02:10:13.384  5510  5510 D HeadsetStateMachine: make
,09-23 02:10:13.389  5510  5522 I BluetoothAdapterState: Entering PendingCommandState
,09-23 02:10:13.394  5510  5510 D HeadsetStateMachine: max_hf_connections = 1
,09-23 02:10:13.394  5510  5510 I bt_bluedroid: get_profile_interface handsfree
09-23 02:10:13.394  5510  5526 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 02:10:13.394  5510  5526 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-23 02:10:13.397  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:13.398  5510  5510 D A2dpService: Received start request. Starting profile...
,09-23 02:10:13.398  5510  5510 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 02:10:13.399  5510  5510 I bt_bluedroid: get_profile_interface avrcp
,09-23 02:10:13.404  5510  5510 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 02:10:13.404  5510  5510 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 02:10:13.404  5510  5510 D A2dpStateMachine: make
09-23 02:10:13.405  5510  5510 I bt_bluedroid: get_profile_interface a2dp
,09-23 02:10:13.405  5510  5526 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 02:10:13.407  5510  5545 D A2dpStateMachine: Enter Disconnected: -2
,09-23 02:10:13.408  5510  5510 I BluetoothHidServiceJni: classInitNative: succeeds
09-23 02:10:13.408  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:13.410  5465  5465 D BluetoothInputDevice: Proxy object connected
09-23 02:10:13.410  5510  5510 D HidService: Received start request. Starting profile...
09-23 02:10:13.410  5510  5510 I bt_bluedroid: get_profile_interface hidhost
,09-23 02:10:13.410  5510  5510 D HidService: setHidService(): set to: null
,09-23 02:10:13.410  5510  5526 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f9856d
09-23 02:10:13.410  5510  5526 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 02:10:13.411  5465  5465 D HidProfile: Bluetooth service connected
09-23 02:10:13.411  5510  5510 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 02:10:13.412  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:13.413  5510  5510 D HealthService: Received start request. Starting profile...
,09-23 02:10:13.414  5510  5510 I bt_bluedroid: get_profile_interface health
,09-23 02:10:13.415  5510  5510 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 02:10:13.416  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:13.417  5465  5465 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 02:10:13.417  5510  5510 D PanService: Received start request. Starting profile...
09-23 02:10:13.417  5465  5465 D PanProfile: Bluetooth service connected
09-23 02:10:13.417  5510  5510 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 02:10:13.417  5510  5510 I bt_bluedroid: get_profile_interface pan
09-23 02:10:13.418  5510  5526 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 02:10:13.420  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:13.421  5465  5465 D BluetoothMap: Proxy object connected
09-23 02:10:13.421  5510  5510 D BluetoothMapService: Received start request. Starting profile...
09-23 02:10:13.421  5510  5510 D BluetoothMapService: start()
09-23 02:10:13.422  5465  5465 D MapProfile: Bluetooth service connected
09-23 02:10:13.422  5465  5465 D BluetoothMap: getConnectedDevices()
09-23 02:10:13.422  5465  5465 D BluetoothMap: Bluetooth is Not enabled
,09-23 02:10:13.424  5510  5510 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-23 02:10:13.424  5510  5510 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 02:10:13.425  5510  5510 D BluetoothMapAppObserver: createReceiver()
,09-23 02:10:13.426  5510  5510 D BluetoothMapAppObserver: initObservers()
,09-23 02:10:13.426  5510  5510 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-23 02:10:13.431  5510  5510 V SapService: SapBinder()
09-23 02:10:13.431  5510  5510 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:13.432  5510  5510 D SapService: Received start request. Starting profile...
09-23 02:10:13.432  5510  5510 V SapService: start()
09-23 02:10:13.434  5510  5510 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:13.434  5510  5510 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:13.434  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.435  5510  5543 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOff()=false
,09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.435  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.436  5510  5510 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:13.436  5510  5510 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:13.436  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.436  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.437  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 02:10:13.437  5510  5522 D BluetoothAdapterProperties: ScanMode =  20
09-23 02:10:13.437  5510  5522 D BluetoothAdapterProperties: State =  11
,09-23 02:10:13.438  5510  5526 D BluetoothAdapterProperties: Scan Mode:21
09-23 02:10:13.438  5510  5526 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-23 02:10:13.439  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:13.440  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:13.441  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.441  5510  5522 D BluetoothAdapterProperties: Setting state to 12
09-23 02:10:13.441  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 02:10:13.442  5510  5522 I BluetoothAdapterState: Entering OnState
09-23 02:10:13.442  5465  5476 D BluetoothMap: onBluetoothStateChange: up=true
09-23 02:10:13.442  3449  3721 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:13.443  3057  3070 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:13.444  3057  3648 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:13.444  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:13.446  3057  3057 D BluetoothInputDevice: Proxy object connected
09-23 02:10:13.446  3057  3057 D HidProfile: Bluetooth service connected
09-23 02:10:13.446  3057  3070 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 02:10:13.446  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:13.448   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:13.448   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:13.448  3057  3069 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 02:10:13.448  3057  3057 D BluetoothA2dp: Proxy object connected
09-23 02:10:13.449  5465  5475 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:13.450  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:13.451  5510  5510 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 02:10:13.452  5510  5510 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 02:10:13.452  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:13.453  5465  5476 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 02:10:13.453   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:13.453  5510  5510 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:13.454  3057  3070 D BluetoothPan: onBluetoothStateChange on: true
09-23 02:10:13.455   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 02:10:13.455  5510  5510 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:13.455  3057  3057 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 02:10:13.455  3057  3057 D PanProfile: Bluetooth service connected
09-23 02:10:13.456   931   931 D BluetoothA2dp: Proxy object connected
09-23 02:10:13.456  3057  3069 D BluetoothMap: onBluetoothStateChange: up=true
09-23 02:10:13.456  5510  5510 D ObexServerSockets: Succeed to create listening sockets 
09-23 02:10:13.456  5510  5510 D ObexServerSockets0: startAccept()
09-23 02:10:13.456  5510  5510 D ObexServerSockets0: prepareForNewConnect()
09-23 02:10:13.457  3057  3057 D BluetoothMap: Proxy object connected
09-23 02:10:13.457  3057  3057 D MapProfile: Bluetooth service connected
09-23 02:10:13.457  3057  3057 D BluetoothMap: getConnectedDevices()
09-23 02:10:13.458  5465  5475 D BluetoothPan: onBluetoothStateChange on: true
09-23 02:10:13.458  5510  5510 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 02:10:13.458  5510  5510 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 02:10:13.459  5510  5550 D ObexServerSockets0: Accepting socket connection...
09-23 02:10:13.459   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
09-23 02:10:13.459  5510  5551 D ObexServerSockets0: Accepting socket connection...
09-23 02:10:13.460  5510  5510 D BluetoothMapService: onReceive
09-23 02:10:13.460  5510  5510 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 02:10:13.460  5510  5510 D BluetoothMapService: STATE_ON
09-23 02:10:13.462  5362  5362 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-23 02:10:13.462  5465  5465 D LocalBluetoothProfileManager: Adding local A2DP profile
09-23 02:10:13.464  5362  5362 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-23 02:10:13.466  5510  5553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:13.468  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:13.468  5510  5553 D BluetoothSdpJni: sdpCreateSapsRecordNative:
09-23 02:10:13.469  5510  5553 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 02:10:13.469  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:13.473  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.474  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.477  5465  5465 D LocalBluetoothProfileManager: Adding local HEADSET profile
09-23 02:10:13.480  5510  5510 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 02:10:13.481  5510  5510 D ObexServerSockets0: prepareForNewConnect()
09-23 02:10:13.483  5465  5465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 02:10:13.485  5465  5465 D BluetoothA2dp: Proxy object connected
09-23 02:10:13.489  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 02:10:13.490  5465  5465 D DockEventReceiver: finishStartingService: stopping service
09-23 02:10:13.494  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.494  5362  5408 D io.jxcore.node.ConnectivityMonitor: stop
09-23 02:10:13.495  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 02:10:13.496  5465  5465 D BluetoothPbap: Proxy object connected
09-23 02:10:13.496  3057  3057 D BluetoothPbap: Proxy object connected
09-23 02:10:13.496  3057  3057 D PbapServerProfile: Bluetooth service connected
09-23 02:10:13.496  5362  5408 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
09-23 02:10:13.497  5465  5465 D PbapServerProfile: Bluetooth service connected
09-23 02:10:13.497  5362  5408 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
09-23 02:10:13.498  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.501  5510  5522 D BluetoothAdapterState: Current state: ON, message: 23
,09-23 02:10:13.501  5510  5522 D BluetoothAdapterProperties: Setting state to 13
09-23 02:10:13.501  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-23 02:10:13.502  5510  5522 D BluetoothAdapterProperties: onBluetoothDisable()
09-23 02:10:13.502  3057  3057 D BluetoothPbap: Proxy object disconnected
09-23 02:10:13.502  3057  3057 D PbapServerProfile: Bluetooth service disconnected
09-23 02:10:13.503  5510  5522 I BluetoothAdapterState: Entering PendingCommandState
09-23 02:10:13.504  5510  5526 D BluetoothAdapterProperties: Scan Mode:20
09-23 02:10:13.504  5465  5465 D BluetoothPbap: Proxy object disconnected
09-23 02:10:13.504  5465  5465 D PbapServerProfile: Bluetooth service disconnected
,09-23 02:10:13.505  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-23 02:10:13.507  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:13.507  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:13.508  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:13.508  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:13.510  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:13.510  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:13.511  5362  5362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:13.511  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:13.513  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.513  5465  5465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 02:10:13.514  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:13.518  5510  5510 D BluetoothMapService: onReceive
09-23 02:10:13.518  5510  5510 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 02:10:13.518  5510  5510 D BluetoothMapService: STATE_TURNING_OFF
09-23 02:10:13.519  5465  5465 D DockEventReceiver: finishStartingService: stopping service
09-23 02:10:13.519  5510  5510 D HeadsetService: Received stop request...Stopping profile...
,09-23 02:10:13.521  5510  5510 D A2dpService: Received stop request...Stopping profile...
,09-23 02:10:13.521  5510  5545 D A2dpStateMachine: Exit Disconnected: -1
,09-23 02:10:13.524   931   931 D BluetoothA2dp: Proxy object disconnected
09-23 02:10:13.525  5465  5465 D BluetoothA2dp: Proxy object disconnected
,09-23 02:10:13.525  5510  5510 D HidService: Received stop request...Stopping profile...
09-23 02:10:13.526  5510  5510 D HidService: Stopping Bluetooth HidService
09-23 02:10:13.527  5465  5465 D BluetoothInputDevice: Proxy object disconnected
,09-23 02:10:13.527  5510  5510 D HealthService: Received stop request...Stopping profile...
09-23 02:10:13.527  5465  5465 D HidProfile: Bluetooth service disconnected
09-23 02:10:13.528  5510  5510 D PanService: Received stop request...Stopping profile...
09-23 02:10:13.529  5465  5465 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 02:10:13.529  5465  5465 D PanProfile: Bluetooth service disconnected
09-23 02:10:13.529  5510  5510 D BluetoothMapService: Received stop request...Stopping profile...
09-23 02:10:13.530  5510  5510 D BluetoothMapService: stop()
09-23 02:10:13.530  3057  3057 D BluetoothA2dp: Proxy object disconnected
09-23 02:10:13.530  3057  3057 D BluetoothInputDevice: Proxy object disconnected
09-23 02:10:13.530  3057  3057 D HidProfile: Bluetooth service disconnected
09-23 02:10:13.530  3057  3057 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-23 02:10:13.530  5510  5510 D BluetoothMapAppObserver: deinitObservers()
09-23 02:10:13.530  3057  3057 D PanProfile: Bluetooth service disconnected
09-23 02:10:13.530  5510  5510 D BluetoothMapAppObserver: removeReceiver()
09-23 02:10:13.531  3057  3057 D BluetoothMap: Proxy object disconnected
,09-23 02:10:13.531  5465  5465 D BluetoothMap: Proxy object disconnected
09-23 02:10:13.532  5465  5465 D MapProfile: Bluetooth service disconnected
09-23 02:10:13.532  3057  3057 D MapProfile: Bluetooth service disconnected
,09-23 02:10:13.534  5510  5510 D SapService: Received stop request...Stopping profile...
09-23 02:10:13.534  5510  5510 V SapService: stop()
09-23 02:10:13.535  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 02:10:13.538  5510  5510 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:13.538  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.538  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.538  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 02:10:13.539  5510  5510 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-23 02:10:13.540  5510  5510 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-23 02:10:13.540  5510  5526 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-23 02:10:13.540  5510  5535 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:13.540  5510  5535 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:13.540  5510  5510 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:13.540  5510  5535 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:13.540  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.540  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.540  5510  5526 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-23 02:10:13.540  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.541  5510  5510 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:13.541  5510  5535 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:13.541  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.541  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.541  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.541  5510  5535 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:13.541  5510  5510 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-23 02:10:13.541  5510  5510 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-23 02:10:13.541  5510  5510 V BluetoothAdapterState: isTurningOff()=true
,09-23 02:10:13.541  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.542  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.542  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.542  5510  5535 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 02:10:13.542  5510  5535 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 02:10:13.542  5510  5510 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-23 02:10:13.542  5510  5535 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-23 02:10:13.542  5510  5535 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-23 02:10:13.542  5510  5526 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 02:10:13.542  5510  5510 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-23 02:10:13.542  5510  5510 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:13.542  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.542  5510  5526 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 02:10:13.542  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.542  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.542  5510  5526 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-23 02:10:13.542  5510  5510 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-23 02:10:13.543  5510  5510 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-23 02:10:13.544  5510  5510 D BluetoothMapService: MAP Service closeService in
09-23 02:10:13.544  5510  5510 D BluetoothMapMasInstance0: MAP Service shutdown
09-23 02:10:13.544  5510  5510 D ObexServerSockets0: shutdown(block = true)
09-23 02:10:13.545  5510  5550 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-23 02:10:13.545  5510  5510 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 02:10:13.545  5510  5510 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-23 02:10:13.545  5510  5551 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-23 02:10:13.546  5510  5510 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:13.546  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.546  5510  5537 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-23 02:10:13.546  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.546  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:13.546  5510  5510 D BluetoothMapService: cleanup()
09-23 02:10:13.546  5510  5510 D BluetoothMapService: MAP Service closeService in
09-23 02:10:13.549  5510  5510 V BluetoothAdapterState: isTurningOff()=true
09-23 02:10:13.549  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.549  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.549  5510  5510 V BluetoothAdapterState: isBleTurningOff()=false
,09-23 02:10:13.549  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-23 02:10:13.549  5510  5522 D BluetoothAdapterProperties: Setting state to 15
09-23 02:10:13.549  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-23 02:10:13.550  5510  5522 I BluetoothAdapterState: Entering BleOnState
,09-23 02:10:13.551  5465  5475 D BluetoothMap: onBluetoothStateChange: up=false
,09-23 02:10:13.552  5465  5476 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 02:10:13.552  5465  5475 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:13.553  3449  3773 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:13.553  3057  3648 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-23 02:10:13.553  3057  3069 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 02:10:13.554  3057  3070 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 02:10:13.554   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:13.554   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:13.554  3057  3648 D BluetoothPbap: onBluetoothStateChange: up=false
09-23 02:10:13.555  5465  5476 D BluetoothPbap: onBluetoothStateChange: up=false
,09-23 02:10:13.555  5465  5475 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-23 02:10:13.555   931   948 D BluetoothHeadset: onBluetoothStateChange: up=false
09-23 02:10:13.556  3057  3069 D BluetoothPan: onBluetoothStateChange on: false
09-23 02:10:13.556   931   948 D BluetoothA2dp: onBluetoothStateChange: up=false
09-23 02:10:13.556  3057  3070 D BluetoothMap: onBluetoothStateChange: up=false
09-23 02:10:13.557  5465  5476 D BluetoothPan: onBluetoothStateChange on: false
09-23 02:10:13.557  5510  5522 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-23 02:10:13.557  5510  5522 D BluetoothAdapterProperties: Setting state to 16
09-23 02:10:13.557  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-23 02:10:13.558  5510  5522 D BluetoothAdapterProperties: onBleDisable
09-23 02:10:13.558  5510  5522 I BluetoothAdapterState: Entering PendingCommandState
,09-23 02:10:13.558  5510  5523 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,09-23 02:10:13.560  5510  5535 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-23 02:10:13.560  5510  5535 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-23 02:10:13.561  5510  5526 D BluetoothAdapterProperties: Scan Mode:20
09-23 02:10:13.561  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.562  5465  5465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-23 02:10:13.563  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.565  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.567  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:13.568  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 02:10:13.571  5465  5465 D DockEventReceiver: finishStartingService: stopping service
,09-23 02:10:13.761  5510  5526 I bt_hci  : shut_down
,09-23 02:10:13.762  5510  5532 D bt_hwcfg: hw_epilog_process
09-23 02:10:13.763  5510  5532 I bt_vendor: low_power_mode_cb
,09-23 02:10:13.767  5510  5532 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-23 02:10:13.767  5510  5532 I bt_vendor: epilog_cb
09-23 02:10:13.767  5510  5532 I bt_hci  : epilog_finished_callback
,09-23 02:10:13.768  5510  5526 I bt_hci_h4: hal_close
09-23 02:10:13.769  5510  5526 I bt_userial_vendor: device fd = 54 close
,09-23 02:10:13.897  5510  5523 D bt_stack_manager: event_shut_down_stack finished.
,09-23 02:10:13.898  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-23 02:10:13.901  5510  5522 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-23 02:10:13.902  5510  5510 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-23 02:10:13.903  5510  5510 D BtGatt.GattService: Received stop request...Stopping profile...
09-23 02:10:13.903  5510  5510 D BtGatt.GattService: stop()
09-23 02:10:13.904  5510  5510 D BtGatt.AdvertiseManager: advertise clients cleared
,09-23 02:10:13.908  5510  5510 V BluetoothAdapterState: isTurningOff()=false
,09-23 02:10:13.908  5510  5510 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:13.908  5510  5510 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:13.908  5510  5510 V BluetoothAdapterState: isBleTurningOff()=true
,09-23 02:10:13.909  5510  5522 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-23 02:10:13.909  5510  5522 D BluetoothAdapterProperties: Setting state to 10
09-23 02:10:13.909  5510  5522 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-23 02:10:13.911  5510  5522 I BluetoothAdapterState: Entering OffState
09-23 02:10:13.912   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-23 02:10:13.926  5510  5510 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-23 02:10:13.927  5510  5510 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-23 02:10:13.927  5510  5510 I BluetoothServiceJni: cleanupNative: return from cleanup
09-23 02:10:13.929  5510  5523 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-23 02:10:13.937  5510  5510 I art     : System.exit called, status: 0
,09-23 02:10:13.937  5510  5510 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-23 02:10:13.975   931  3475 I ActivityManager: Process com.android.bluetooth (pid 5510) has died
,09-23 02:10:14.001  5362  5421 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:14.001  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:14.001  5362  5421 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-23 02:10:14.001  5362  5421 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:14.002  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:14.017   931   948 I ActivityManager: Start proc 5565:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-23 02:10:14.078  5565  5565 D AdapterServiceConfig: Adding HeadsetService
,09-23 02:10:14.079  5565  5565 D AdapterServiceConfig: Adding A2dpService
09-23 02:10:14.079  5565  5565 D AdapterServiceConfig: Adding HidService
09-23 02:10:14.079  5565  5565 D AdapterServiceConfig: Adding HealthService
,09-23 02:10:14.080  5565  5565 D AdapterServiceConfig: Adding PanService
09-23 02:10:14.080  5565  5565 D AdapterServiceConfig: Adding GattService
09-23 02:10:14.080  5565  5565 D AdapterServiceConfig: Adding BluetoothMapService
,09-23 02:10:14.080  5565  5565 D AdapterServiceConfig: Adding SapService
,09-23 02:10:14.092   931   948 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ed69a80:true
,09-23 02:10:14.092  5565  5565 D BluetoothAdapterState: make() - Creating AdapterState
,09-23 02:10:14.095  5565  5565 I bt_bluedroid: init
09-23 02:10:14.095  5565  5577 I BluetoothAdapterState: Entering OffState
,09-23 02:10:14.096  5565  5578 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-23 02:10:14.096  5565  5578 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-23 02:10:14.097  5565  5578 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-23 02:10:14.097  5565  5578 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-23 02:10:14.097  5565  5565 I bt_bluedroid: get_profile_interface socket
09-23 02:10:14.098  5565  5565 I bt_bluedroid: get_profile_interface sdp
09-23 02:10:14.098  5565  5581 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 02:10:14.100  5565  5581 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 02:10:14.103  5565  5576 I bt_bluedroid: config_hci_snoop_log
,09-23 02:10:14.104   931   948 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
09-23 02:10:14.107  5565  5577 D BluetoothAdapterState: Current state: OFF, message: 0
09-23 02:10:14.108  5565  5577 D BluetoothAdapterProperties: Setting state to 14
09-23 02:10:14.108  5565  5577 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-23 02:10:14.109  5565  5577 D BluetoothBondStateMachine: make
,09-23 02:10:14.111  5565  5582 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-23 02:10:14.113  5565  5577 I BluetoothAdapterState: Entering PendingCommandState
,09-23 02:10:14.114  5565  5565 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-23 02:10:14.116  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:14.116  5565  5565 D BtGatt.DebugUtils: handleDebugAction() action=null
09-23 02:10:14.117  5565  5565 D BtGatt.GattService: Received start request. Starting profile...
09-23 02:10:14.117  5565  5565 D BtGatt.GattService: start()
09-23 02:10:14.117  5565  5565 I bt_bluedroid: get_profile_interface gatt
,09-23 02:10:14.118  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:14.118  5565  5565 D BtGatt.AdvertiseManager: advertise manager created
,09-23 02:10:14.123  5565  5565 V BluetoothAdapterState: isTurningOff()=false
,09-23 02:10:14.123  5565  5565 V BluetoothAdapterState: isTurningOn()=false
09-23 02:10:14.123  5565  5565 V BluetoothAdapterState: isBleTurningOn()=true
09-23 02:10:14.123  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.123  5565  5577 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-23 02:10:14.124  5565  5577 I bt_bluedroid: bt_bluedroid
09-23 02:10:14.124  5565  5578 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-23 02:10:14.124  5565  5578 I bt_hci  : start_up
,09-23 02:10:14.129  5565  5578 I bt_vendor: alloc value 0xf4039871
09-23 02:10:14.129  5565  5578 I bt_vendor: init
09-23 02:10:14.129  5565  5578 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-23 02:10:14.129  5565  5578 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-23 02:10:14.240  5565  5578 D bt_hci  : start_up starting async portion
,09-23 02:10:14.240  5565  5585 I bt_hci  : event_finish_startup
09-23 02:10:14.241  5565  5585 I bt_hci_h4: hal_open
09-23 02:10:14.241  5565  5585 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-23 02:10:14.237  5586  5586 W irq/448-msm_hs_: type=1400 audit(0.0:121): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 02:10:14.244  5565  5585 I bt_userial_vendor: device fd = 54 open
,09-23 02:10:14.258  5565  5585 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 02:10:14.260  5565  5585 D bt_hwcfg: Chipset BCM4358A3
,09-23 02:10:14.261  5565  5585 D bt_hwcfg: Target name = [BCM4358A3]
09-23 02:10:14.261  5565  5585 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,09-23 02:10:14.510  5565  5577 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,09-23 02:10:14.654  5565  5585 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-23 02:10:14.654  5565  5585 D bt_hwcfg: Settlement delay -- 100 ms
09-23 02:10:14.654  5565  5585 I bt_hwcfg: Setting fw settlement delay to 100 
,09-23 02:10:14.778  5565  5585 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-23 02:10:14.778  5565  5585 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,09-23 02:10:14.779  5565  5585 I bt_hwcfg: vendor lib fwcfg completed
09-23 02:10:14.780  5565  5585 I bt_vendor: firmware callback
09-23 02:10:14.780  5565  5585 I bt_hci  : firmware_config_callback
,09-23 02:10:14.788  5565  5588 I bt_btu  : btu_task pending for preload complete event
,09-23 02:10:14.788  5565  5588 I bt_btu_task: Bluetooth chip preload is complete
09-23 02:10:14.788  5565  5588 I bt_btu  : btu_task received preload complete event
,09-23 02:10:14.795  5565  5588 I         : BTE_InitTraceLevels -- TRC_HCI
,09-23 02:10:14.796  5565  5588 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-23 02:10:14.796  5565  5588 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-23 02:10:14.796  5565  5588 I         : BTE_InitTraceLevels -- TRC_AVDT
09-23 02:10:14.796  5565  5588 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-23 02:10:14.796  5565  5588 I         : BTE_InitTraceLevels -- TRC_A2D
09-23 02:10:14.796  5565  5588 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_BTM
09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_GAP
,09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_PAN
09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_SDP
,09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_GATT
09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_SMP
,09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-23 02:10:14.797  5565  5588 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-23 02:10:14.880  5565  5588 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3fb7549
,09-23 02:10:14.880  5565  5588 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3fb7549 
,09-23 02:10:14.894  5565  5581 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-23 02:10:14.895  5565  5581 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-23 02:10:14.896  5565  5581 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,09-23 02:10:14.898  5565  5581 D BluetoothAdapterProperties: Name is: Nexus 6P
,09-23 02:10:14.904  5565  5581 D BluetoothAdapterProperties: Scan Mode:20
,09-23 02:10:14.904  5565  5581 D BluetoothAdapterProperties: Discoverable Timeout:120
09-23 02:10:14.904  5565  5581 D bt_hci  : do_postload posting postload work item
09-23 02:10:14.904  5565  5585 I bt_hci  : event_postload
09-23 02:10:14.904  5565  5585 I bt_vendor: sco_config_cb
,09-23 02:10:14.904  5565  5585 I bt_hci  : sco_config_callback postload finished.
09-23 02:10:14.907  5565  5581 D bt_bte_conf: Device ID record 1 : primary
09-23 02:10:14.907  5565  5581 D bt_bte_conf:   vendorId            = 000f
09-23 02:10:14.907  5565  5581 D bt_bte_conf:   vendorIdSource      = 0001
09-23 02:10:14.907  5565  5581 D bt_bte_conf:   product             = 1200
09-23 02:10:14.907  5565  5581 D bt_bte_conf:   version             = 1436
09-23 02:10:14.907  5565  5581 D bt_bte_conf:   clientExecutableURL = 
09-23 02:10:14.907  5565  5581 D bt_bte_conf:   serviceDescription  = 
09-23 02:10:14.908  5565  5581 D bt_bte_conf:   documentationURL    = 
09-23 02:10:14.908  5565  5581 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-23 02:10:14.908  5565  5578 D bt_stack_manager: event_start_up_stack finished
09-23 02:10:14.909  5565  5577 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-23 02:10:14.910  5565  5577 D BluetoothAdapterProperties: Setting state to 15
,09-23 02:10:14.910  5565  5577 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-23 02:10:14.912  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:14.914  5565  5577 I BluetoothAdapterState: Entering BleOnState
09-23 02:10:14.918  5565  5585 I bt_vendor: low_power_mode_cb
09-23 02:10:14.919  5565  5577 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-23 02:10:14.919  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:14.919  5565  5577 D BluetoothAdapterProperties: Setting state to 11
09-23 02:10:14.920  5565  5577 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-23 02:10:14.924  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:14.929  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:14.931  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:14.935  3057  3069 D BluetoothHeadset: Proxy object connected
,09-23 02:10:14.935  5565  5565 D HeadsetService: Received start request. Starting profile...
09-23 02:10:14.935  3057  3057 D HeadsetProfile: Bluetooth service connected
09-23 02:10:14.936  3449  3721 D BluetoothHeadset: Proxy object connected
09-23 02:10:14.936   931   931 D BluetoothHeadset: Proxy object connected
09-23 02:10:14.936  5465  5475 D BluetoothHeadset: Proxy object connected
09-23 02:10:14.938  5565  5565 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-23 02:10:14.938   931   931 D BluetoothHeadset: Proxy object connected
09-23 02:10:14.938   931   931 D BluetoothHeadset: Proxy object connected
09-23 02:10:14.938  5565  5565 D HeadsetStateMachine: make
09-23 02:10:14.939  5465  5465 D HeadsetProfile: Bluetooth service connected
09-23 02:10:14.943  5565  5577 I BluetoothAdapterState: Entering PendingCommandState
,09-23 02:10:14.948  5565  5565 D HeadsetStateMachine: max_hf_connections = 1
,09-23 02:10:14.948  5565  5565 I bt_bluedroid: get_profile_interface handsfree
09-23 02:10:14.949  5565  5581 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-23 02:10:14.949  5565  5581 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
09-23 02:10:14.953  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:14.953  5565  5565 D A2dpService: Received start request. Starting profile...
,09-23 02:10:14.954  5565  5565 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-23 02:10:14.954  5565  5565 I bt_bluedroid: get_profile_interface avrcp
,09-23 02:10:14.956  5461  5461 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 02:10:14.962  5565  5565 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-23 02:10:14.962  5565  5565 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-23 02:10:14.962  5565  5565 D A2dpStateMachine: make
,09-23 02:10:14.964  5461  5461 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
09-23 02:10:14.965  5565  5565 I bt_bluedroid: get_profile_interface a2dp
,09-23 02:10:14.966  5565  5581 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-23 02:10:14.968  5565  5597 D A2dpStateMachine: Enter Disconnected: -2
,09-23 02:10:14.969  5565  5565 I BluetoothHidServiceJni: classInitNative: succeeds
09-23 02:10:14.970  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:14.971  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-23 02:10:14.971  5565  5565 D HidService: Received start request. Starting profile...
,09-23 02:10:14.971  5565  5565 I bt_bluedroid: get_profile_interface hidhost
09-23 02:10:14.971  5565  5565 D HidService: setHidService(): set to: null
,09-23 02:10:14.972  5565  5565 I BluetoothHealthServiceJni: classInitNative: succeeds
09-23 02:10:14.972  5565  5581 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3f9856d
09-23 02:10:14.972  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:14.972  5565  5581 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-23 02:10:14.973  5565  5565 D HealthService: Received start request. Starting profile...
,09-23 02:10:14.975  5565  5565 I bt_bluedroid: get_profile_interface health
,09-23 02:10:14.975  5565  5565 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-23 02:10:14.976  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
09-23 02:10:14.976  5461  5461 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 02:10:14.977  5565  5565 D PanService: Received start request. Starting profile...
09-23 02:10:14.977  5565  5565 D BluetoothPanServiceJni: initializeNative(L110): pan
09-23 02:10:14.977  5565  5565 I bt_bluedroid: get_profile_interface pan
09-23 02:10:14.978  5565  5581 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-23 02:10:14.979  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:14.980  5565  5565 D BluetoothMapService: Received start request. Starting profile...
09-23 02:10:14.980  5565  5565 D BluetoothMapService: start()
09-23 02:10:14.983  5565  5565 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-23 02:10:14.983  5565  5565 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-23 02:10:14.984  5565  5565 D BluetoothMapAppObserver: createReceiver()
,09-23 02:10:14.985  5565  5565 D BluetoothMapAppObserver: initObservers()
,09-23 02:10:14.985  5565  5565 D BluetoothMapAppObserver: getEnabledAccountItems()
09-23 02:10:14.991  5565  5565 V SapService: SapBinder()
09-23 02:10:14.991  5565  5565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:14.991  5565  5565 D SapService: Received start request. Starting profile...
09-23 02:10:14.992  5565  5565 V SapService: start()
,09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:14.995  5565  5595 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:14.995  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isTurningOff()=false
,09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isTurningOn()=true
,09-23 02:10:14.996  5565  5565 V BluetoothAdapterState: isBleTurningOn()=false
,09-23 02:10:14.997  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.997  5565  5565 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:14.998  5565  5565 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:14.998  5565  5565 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:14.998  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.998  5565  5565 V BluetoothAdapterState: isTurningOff()=false
09-23 02:10:14.998  5565  5565 V BluetoothAdapterState: isTurningOn()=true
09-23 02:10:14.998  5565  5565 V BluetoothAdapterState: isBleTurningOn()=false
09-23 02:10:14.998  5565  5565 V BluetoothAdapterState: isBleTurningOff()=false
09-23 02:10:14.999  5565  5577 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-23 02:10:14.999  5565  5577 D BluetoothAdapterProperties: ScanMode =  20
09-23 02:10:14.999  5565  5577 D BluetoothAdapterProperties: State =  11
09-23 02:10:14.999  5565  5577 D BluetoothAdapterProperties: Setting state to 12
09-23 02:10:14.999  5565  5577 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-23 02:10:15.000  5565  5577 I BluetoothAdapterState: Entering OnState
09-23 02:10:15.000  5565  5581 D BluetoothAdapterProperties: Scan Mode:21
09-23 02:10:15.000  5465  5476 D BluetoothMap: onBluetoothStateChange: up=true
09-23 02:10:15.000  5565  5581 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-23 02:10:15.002  5465  5475 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-23 02:10:15.004  5465  5476 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 02:10:15.005  3449  3471 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:15.005  3057  3070 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:15.005  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:15.005  3057  3648 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-23 02:10:15.007  3057  3069 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 02:10:15.007  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:15.008  3057  3057 D BluetoothInputDevice: Proxy object connected
09-23 02:10:15.008  3057  3057 D HidProfile: Bluetooth service connected
09-23 02:10:15.009   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:15.009   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
09-23 02:10:15.009  3057  3648 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 02:10:15.009  5565  5565 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 02:10:15.010  5565  5565 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-23 02:10:15.010  3057  3057 D BluetoothA2dp: Proxy object connected
09-23 02:10:15.010  5465  5476 D BluetoothPbap: onBluetoothStateChange: up=true
09-23 02:10:15.011  5565  5565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:15.012  5465  5465 D BluetoothMap: Proxy object connected
09-23 02:10:15.012  5465  5465 D MapProfile: Bluetooth service connected
09-23 02:10:15.012  5465  5465 D BluetoothMap: getConnectedDevices()
,09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:15.012  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:15.013  5465  5475 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-23 02:10:15.013  5565  5565 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:15.014  5565  5565 D ObexServerSockets: Succeed to create listening sockets 
09-23 02:10:15.014  5565  5565 D ObexServerSockets0: startAccept()
09-23 02:10:15.014  5565  5565 D ObexServerSockets0: prepareForNewConnect()
09-23 02:10:15.014   931   948 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-23 02:10:15.015  3057  3069 D BluetoothPan: onBluetoothStateChange on: true
09-23 02:10:15.015  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:15.016  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:15.016   931   948 D BluetoothA2dp: onBluetoothStateChange: up=true
09-23 02:10:15.017   931   931 D BluetoothA2dp: Proxy object connected
09-23 02:10:15.017  3057  3070 D BluetoothMap: onBluetoothStateChange: up=true
09-23 02:10:15.018  5362  5421 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:15.018  5565  5565 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-23 02:10:15.018  5565  5565 D BluetoothSdpJni: SDP Create record success - handle: 0
09-23 02:10:15.019  5362  5408 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
09-23 02:10:15.019  5565  5604 D ObexServerSockets0: Accepting socket connection...
09-23 02:10:15.019  5465  5476 D BluetoothPan: onBluetoothStateChange on: true
09-23 02:10:15.019  3057  3057 D BluetoothMap: Proxy object connected
09-23 02:10:15.019  3057  3057 D MapProfile: Bluetooth service connected
09-23 02:10:15.019  3057  3057 D BluetoothMap: getConnectedDevices()
09-23 02:10:15.020   931  3745 D WifiService: setWifiEnabled: false pid=5362, uid=10077
09-23 02:10:15.020   931  3745 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 02:10:15.020  5565  5605 D ObexServerSockets0: Accepting socket connection...
,09-23 02:10:15.021  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:15.022  5465  5465 D BluetoothA2dp: Proxy object connected
09-23 02:10:15.022  3057  3057 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 02:10:15.022  3057  3057 D PanProfile: Bluetooth service connected
09-23 02:10:15.023   931   931 D RttService: SCAN_AVAILABLE : 1
09-23 02:10:15.023   931  2998 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-23 02:10:15.024  5465  5465 D BluetoothInputDevice: Proxy object connected
09-23 02:10:15.024  5465  5465 D HidProfile: Bluetooth service connected
09-23 02:10:15.025   931   931 I Telecom : BluetoothPhoneService: queryPhoneState
,09-23 02:10:15.025   931   931 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-23 02:10:15.026  5565  5565 D BluetoothMapService: onReceive
09-23 02:10:15.026  5565  5565 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-23 02:10:15.027  5565  5565 D BluetoothMapService: STATE_ON
09-23 02:10:15.029  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:15.030  5465  5465 D BluetoothPan: BluetoothPAN Proxy object connected
09-23 02:10:15.031  5465  5465 D PanProfile: Bluetooth service connected
09-23 02:10:15.031  5565  5608 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 02:10:15.031  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-23 02:10:15.032  5565  5608 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,09-23 02:10:15.033  5565  5608 D BluetoothSdpJni: SDP Create record success - handle: 1
09-23 02:10:15.034   931  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 02:10:15.034   508   930 D CommandListener: Clearing all IP addresses on wlan0
09-23 02:10:15.035  5465  5465 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-23 02:10:15.038   931  2889 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 02:10:15.039  5461  5461 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
09-23 02:10:15.044  3535  3535 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-23 02:10:15.046  5465  5465 D DockEventReceiver: finishStartingService: stopping service
09-23 02:10:15.046  5461  5461 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:15.047  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-23 02:10:15.048  5465  5465 D BluetoothPbap: Proxy object connected
09-23 02:10:15.048  5465  5465 D PbapServerProfile: Bluetooth service connected
,09-23 02:10:15.049  5565  5565 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-23 02:10:15.049  5565  5565 D ObexServerSockets0: prepareForNewConnect()
,09-23 02:10:15.050  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:15.052  5565  5610 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:15.054  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:15.058  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-23 02:10:15.059  3057  3057 D BluetoothPbap: Proxy object connected
09-23 02:10:15.059  3057  3057 D PbapServerProfile: Bluetooth service connected
,09-23 02:10:15.072  5461  5461 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,09-23 02:10:15.074  5565  5616 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-23 02:10:15.075  5565  5616 I BtOppRfcommListener: Accept thread started.
,09-23 02:10:15.077  5461  5461 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-23 02:10:15.083  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 02:10:15.083   931  2889 D wifi    : In wifi stop Hal
,09-23 02:10:15.083   931  2889 D wifi    : halHandle = 0x7f5d9ba000, mVM = 0x7f79fcd140, mCls = 0x2018ea
09-23 02:10:15.083   931  5460 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,09-23 02:10:15.083   931  5460 D WifiHAL : Got a signal to exit!!!
09-23 02:10:15.083   931  5460 I WifiHAL : Exit wifi_event_loop
,09-23 02:10:15.085   931  2889 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,09-23 02:10:15.087   931  2889 E WifiHAL : Event processing terminated
09-23 02:10:15.087  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:15.087   931  2889 D wifi    : In wifi cleaned up handler
09-23 02:10:15.087   931  2889 I WifiHAL : Internal cleanup completed
09-23 02:10:15.088  3566  3960 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 02:10:15.088  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:15.112   931  5460 D wifi    : set interface wlan0 flags (DOWN)
,09-23 02:10:15.112   931  2889 D WifiNative-HAL: HAL event thread stopped successfully
,09-23 02:10:15.319   931   948 D Tethering: InitialState.processMessage what=4
,09-23 02:10:15.328   931   948 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:15.530  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:15.536  5362  5421 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:15.539   931  3482 D WifiService: setWifiEnabled: true pid=5362, uid=10077
,09-23 02:10:15.539   931  3482 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 02:10:15.542  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:15.546   508   930 D SoftapController: Softap fwReload - Ok
,09-23 02:10:15.552   508   930 D CommandListener: Setting iface cfg
,09-23 02:10:15.552   508   930 D CommandListener: Trying to bring down wlan0
,09-23 02:10:15.555   508   930 D CommandListener: Clearing all IP addresses on wlan0
,09-23 02:10:15.558   931  2889 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,09-23 02:10:16.048   931  3351 D WifiService: setWifiEnabled: true pid=5362, uid=10077
,09-23 02:10:16.054   931  3351 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-23 02:10:16.162   931  2889 D wifi    : set interface wlan0 flags (UP)
,09-23 02:10:16.162   931  2889 I WifiHAL : Initializing wifi
,09-23 02:10:16.162   931  2889 I WifiHAL : Creating socket
,09-23 02:10:16.168   931   948 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-23 02:10:16.170   931  2889 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
09-23 02:10:16.171   931  2889 D wifi    : Did set static halHandle = 0x7f5d9ba000
09-23 02:10:16.171   931  2889 D wifi    : halHandle = 0x7f5d9ba000, mVM = 0x7f79fcd140, mCls = 0x10f6
09-23 02:10:16.171   931  2889 D wifi    : array field set
09-23 02:10:16.172   931  2889 I WifiNative-HAL: interface[0] = wlan0
,09-23 02:10:16.175   931  5619 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547031326720
09-23 02:10:16.175   931  5619 D wifi    : waitForHalEvents called, vm = 0x7f79fcd140, obj = 0x10f6, env = 0x7f602f9080
,09-23 02:10:16.239  5620  5620 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-23 02:10:16.262  5620  5620 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-23 02:10:16.270  5620  5620 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-23 02:10:16.270  5620  5620 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,09-23 02:10:16.276   931  2889 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-23 02:10:16.284  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:16.286  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:16.296   931  2889 D WifiConfigStore: Loading config and enabling all networks 
,09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:16.298  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:16.299  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:16.302  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:16.304  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:16.311   931  2889 D WifiConfigStore: loaded 0 passpoint configs
,09-23 02:10:16.311   931  2889 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-23 02:10:16.312   931  2889 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-23 02:10:16.313   931  2889 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-23 02:10:16.314   931  2889 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-23 02:10:16.314   931  2889 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-23 02:10:16.314   931  2889 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
09-23 02:10:16.314   931  2889 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-23 02:10:16.318  4244  4244 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-23 02:10:16.318   931  2889 D WifiNative-HAL: Setting external_sim to 1
09-23 02:10:16.319   931  2889 D wifi    : setting dfs flag to true, 0x7f608369e0
09-23 02:10:16.319   931  2889 D WifiStateMachine: Setting OUI to DA-A1-19
09-23 02:10:16.319   931  2889 D wifi    : setting scan oui 0x7f608369e0
,09-23 02:10:16.319   931  2889 D WifiHAL : Sending mac address OUI
,09-23 02:10:16.323   931  2889 E native  : do suspend false
,09-23 02:10:16.330   931  2889 D wifi    : android_net_wifi_setLinkLayerStats: 1
09-23 02:10:16.330   931   931 D RttService: SCAN_AVAILABLE : 3
09-23 02:10:16.330   931  2998 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-23 02:10:16.330   508   930 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-23 02:10:16.332   508   930 D CommandListener: Setting iface cfg
,09-23 02:10:16.335   931  2888 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '76 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 76 Failed to set address (No such device)'
,09-23 02:10:16.335   931  2888 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-23 02:10:16.344   931  2888 D WifiNative-HAL: p2pGetDeviceAddress
,09-23 02:10:16.344   931  2888 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,09-23 02:10:16.349   931   946 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=208729 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:16.572  5362  5421 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:16.577  5362  5421 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:16.581  5362  5408 D BluetoothAdapter: enable(): BT is already enabled..!
09-23 02:10:16.581   931  3090 D WifiService: setWifiEnabled: true pid=5362, uid=10077
09-23 02:10:16.581   931  3090 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-23 02:10:16.582  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 02:10:16.583  5362  5408 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 02:10:16.583  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 02:10:16.583  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-23 02:10:16.583  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b890764 removed from the list
09-23 02:10:16.583  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-23 02:10:16.583  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4f0cdcd removed from the list
,09-23 02:10:16.584  5362  5408 D io.jxcore.node.ConnectivityMonitor: stop
09-23 02:10:16.584  5362  5408 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-23 02:10:16.584  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-23 02:10:16.587  5362  5408 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
,09-23 02:10:16.590  5362  5408 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testRun
,09-23 02:10:16.596  5362  5622 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-23 02:10:16.596  5362  5622 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 02:10:17.102  5362  5624 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-23 02:10:17.102  5362  5624 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 02:10:17.103  5362  5624 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 02:10:17.103  5362  5624 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 02:10:17.104  5362  5626 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 159, name: IncomingSocketThread/Sender)
,09-23 02:10:17.104  5362  5624 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-23 02:10:17.105  5362  5622 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-23 02:10:17.105  5362  5622 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 02:10:17.105  5362  5622 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 02:10:17.105  5362  5627 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 160, name: IncomingSocketThread/Receiver)
09-23 02:10:17.106  5362  5622 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 02:10:17.107  5362  5627 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 160, thread name: IncomingSocketThread/Receiver)
09-23 02:10:17.107  5362  5627 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 02:10:17.107  5362  5627 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 160, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 02:10:17.107  5362  5622 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-23 02:10:17.108  5362  5628 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 161, name: OutgoingSocketThread/Sender)
,09-23 02:10:17.109  5362  5629 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 162, name: OutgoingSocketThread/Receiver)
,09-23 02:10:17.111  5362  5629 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 162, thread name: OutgoingSocketThread/Receiver)
,09-23 02:10:17.111  5362  5629 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 02:10:17.111  5362  5629 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 162, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 02:10:17.600  5362  5408 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
,09-23 02:10:17.602  5362  5408 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,09-23 02:10:17.607  5362  5408 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
,09-23 02:10:17.611  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,09-23 02:10:17.612  5362  5408 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-23 02:10:17.614  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
,09-23 02:10:17.614  5362  5408 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-23 02:10:17.616  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,09-23 02:10:17.619  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,09-23 02:10:17.619  5362  5408 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c2dc3c8 Bundle[{}]
09-23 02:10:17.620  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
09-23 02:10:17.620  5362  5408 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-23 02:10:17.621  5362  5408 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-23 02:10:17.622  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
,09-23 02:10:17.622  5362  5408 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-23 02:10:17.623  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
09-23 02:10:17.623  5362  5408 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-23 02:10:17.624  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
09-23 02:10:17.624  5362  5408 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-23 02:10:17.624  5362  5408 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
09-23 02:10:17.625  5362  5408 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-23 02:10:17.627  5362  5408 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
09-23 02:10:17.628  5362  5408 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
09-23 02:10:17.629  5362  5408 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,09-23 02:10:17.629  5362  5408 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
09-23 02:10:17.630  5362  5408 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
09-23 02:10:17.631  5362  5408 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,09-23 02:10:17.633  5362  5408 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testRun
,09-23 02:10:17.636  5362  5630 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-23 02:10:17.636  5362  5630 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-23 02:10:17.641  5362  5630 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-23 02:10:17.641  5362  5630 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-23 02:10:17.641  5362  5630 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 02:10:17.641  5362  5630 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 02:10:17.642  5362  5630 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-23 02:10:17.642  5362  5632 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-23 02:10:17.642  5362  5632 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-23 02:10:17.643  5362  5632 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-23 02:10:17.643  5362  5633 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: OutgoingSocketThread/Sender)
09-23 02:10:17.643  5362  5634 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 173, name: OutgoingSocketThread/Receiver)
,09-23 02:10:17.644  5362  5632 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 02:10:17.645  5362  5634 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 173, thread name: OutgoingSocketThread/Receiver)
09-23 02:10:17.645  5362  5635 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: IncomingSocketThread/Sender)
09-23 02:10:17.645  5362  5634 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-23 02:10:17.645  5362  5634 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 173, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-23 02:10:17.645  5362  5632 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-23 02:10:17.647  5362  5636 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 175, name: IncomingSocketThread/Receiver)
,09-23 02:10:17.648  5362  5636 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 175, thread name: IncomingSocketThread/Receiver)
,09-23 02:10:17.648  5362  5636 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-23 02:10:17.648  5362  5636 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 175, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-23 02:10:18.141  5362  5408 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,09-23 02:10:18.144  5362  5408 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
09-23 02:10:18.145  5362  5408 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,09-23 02:10:18.149  5362  5408 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,09-23 02:10:18.152  5362  5408 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,09-23 02:10:18.154  5362  5408 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
09-23 02:10:18.154  5362  5408 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 184)
09-23 02:10:18.156  5362  5408 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,09-23 02:10:18.158  5362  5408 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-23 02:10:18.158  5362  5408 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 185)
09-23 02:10:18.160  5362  5408 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
09-23 02:10:18.161  5362  5408 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,09-23 02:10:18.162  5362  5408 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
09-23 02:10:18.162  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-23 02:10:18.163  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1da48ce added. We now have 3 listener(s)
,09-23 02:10:18.165  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:10:18.165  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-23 02:10:18.165  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-23 02:10:18.165  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-23 02:10:18.165  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@973f3ef added. We now have 3 listener(s)
09-23 02:10:18.165  5362  5408 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-23 02:10:18.166  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-23 02:10:18.172  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-23 02:10:18.179  5362  5408 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-23 02:10:18.182  5362  5408 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-23 02:10:18.182  5362  5408 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-23 02:10:18.184  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:18.186  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-23 02:10:18.188  5362  5408 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
09-23 02:10:18.189  5362  5408 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
09-23 02:10:18.189  5362  5408 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
09-23 02:10:18.189  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
,09-23 02:10:18.189  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:18.189  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 02:10:18.189  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-23 02:10:18.190  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:18.191  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 02:10:18.193  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 02:10:18.193  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-23 02:10:18.194  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 02:10:18.194  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 02:10:18.194  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 02:10:18.194  5362  5637 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:18.195  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:18.195  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-23 02:10:18.194  5592  5592 W Binder_3: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[32491]" dev="sockfs" ino=32491 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 02:10:18.194  5592  5592 W Binder_3: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[32491]" dev="sockfs" ino=32491 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:18.199  5362  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-23 02:10:18.203  5362  5408 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 02:10:18.203  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 02:10:18.207  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 02:10:18.207  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 02:10:18.207  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 02:10:18.209  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-23 02:10:18.209  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:10:18.209  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
09-23 02:10:18.209  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:18.209  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:18.209  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 02:10:18.210  5362  5408 D BluetoothAdapter: STATE_ON
,09-23 02:10:18.213  5565  5592 D BtGatt.GattService: registerClient() - UUID=0ee88d86-574e-4c8f-a8bc-f7c7e1ddc9b0
,09-23 02:10:18.213  5565  5581 D BtGatt.GattService: onClientRegistered() - UUID=0ee88d86-574e-4c8f-a8bc-f7c7e1ddc9b0, clientIf=5
09-23 02:10:18.214  5362  5373 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 02:10:18.216  5565  5583 D BtGatt.AdvertiseManager: message : 0
,09-23 02:10:18.218  5565  5583 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 02:10:18.228  5565  5581 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 02:10:18.234  5565  5581 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 02:10:18.234  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
09-23 02:10:18.234  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 02:10:18.235  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 02:10:18.237  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:18.237  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 02:10:18.237  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 02:10:18.237  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 02:10:18.237  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 02:10:18.237  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 02:10:18.240  5362  5362 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 02:10:18.240  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 02:10:18.741  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 02:10:18.741  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 02:10:18.741  5362  5362 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 02:10:19.519  5620  5620 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,09-23 02:10:19.584   931  2889 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,09-23 02:10:19.586   931  2889 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,09-23 02:10:19.586   931  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 02:10:19.598   931  2889 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,09-23 02:10:19.633   931  2889 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,09-23 02:10:19.635  5620  5620 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-23 02:10:20.062  5620  5620 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-23 02:10:20.095  5620  5620 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-23 02:10:20.095  5620  5620 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,09-23 02:10:20.109   931  2889 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 02:10:20.109   931  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-23 02:10:20.109   931  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-23 02:10:20.126   931  2889 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-23 02:10:20.139   508   930 D CommandListener: Setting iface cfg
,09-23 02:10:20.144   931  2889 D WifiStateMachine: Start Dhcp Watchdog 2
,09-23 02:10:20.149   931  5642 D DhcpClient: Receive thread started
,09-23 02:10:20.153   931  2891 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 02:10:20.153   931  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
09-23 02:10:20.153   931  2891 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-23 02:10:20.235   931  2889 E native  : do suspend false
,09-23 02:10:20.252   931  5641 D DhcpClient: Broadcasting DHCPDISCOVER
,09-23 02:10:20.270   931  5642 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172629, domain null
,09-23 02:10:20.271   931  5641 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172629 seconds
,09-23 02:10:20.273   931  5641 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,09-23 02:10:20.298   931  5642 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-23 02:10:20.299   931  5641 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-23 02:10:20.301   508   930 D CommandListener: Setting iface cfg
,09-23 02:10:20.306   931  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-23 02:10:20.314   931  5641 D DhcpClient: Scheduling renewal in 86399s
,09-23 02:10:20.324   931  2889 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-23 02:10:20.325   931  2889 D WifiConfigStore: No blacklist allowed without epno enabled
,09-23 02:10:20.326   931  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-23 02:10:20.328   931  2891 D ConnectivityService: Adding iface wlan0 to network 101
,09-23 02:10:20.340   931  2889 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-23 02:10:20.377   931  2891 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-23 02:10:20.377   931  2891 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-23 02:10:20.383   931  2891 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-23 02:10:20.385   931  2891 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-23 02:10:20.388   931  2891 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-23 02:10:20.397   931  2891 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 02:10:20.402   931  2891 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-23 02:10:20.402   931  2891 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-23 02:10:20.402   931  2891 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-23 02:10:20.402   931  2891 D ConnectivityService:    accepting network in place of null
09-23 02:10:20.402   931  2889 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-23 02:10:20.402   931  2889 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-23 02:10:20.403   931  2891 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-23 02:10:20.427   508   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 02:10:20.447   931  5640 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212827, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-23 02:10:20.449   508   930 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-23 02:10:20.452   931  2891 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-23 02:10:20.452   931  2891 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-23 02:10:20.452  3422  3540 W QCNEJ   : |CORE| network available: 101
09-23 02:10:20.454   931  2891 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-23 02:10:20.456   931   948 D Tethering: MasterInitialState.processMessage what=3
09-23 02:10:20.459  3422  3540 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,09-23 02:10:20.460  3422  3540 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
09-23 02:10:20.460  3422  3540 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:10:20.465  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-23 02:10:20.467  4821  4836 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,09-23 02:10:20.467  4821  4836 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
09-23 02:10:20.467  4821  4836 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
09-23 02:10:20.468  4821  4836 E SarControlService: no key has been found,reset the power
09-23 02:10:20.468  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:20.468  4821  4862 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
09-23 02:10:20.468  4821  4862 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
09-23 02:10:20.468  4821  4862 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
09-23 02:10:20.468  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 02:10:20.468  4850  4850 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
09-23 02:10:20.469  4821  4862 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
09-23 02:10:20.469  4821  4862 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
09-23 02:10:20.469  4821  4862 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
09-23 02:10:20.470  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
09-23 02:10:20.470  4850  4850 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
09-23 02:10:20.474  3861  3861 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:10:20.475  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 02:10:20.477  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:20.477  4850  4864 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@560d244 HexData = [00000000ec03000000000000ffffffff]
09-23 02:10:20.477  4850  4864 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,09-23 02:10:20.477  4850  4864 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
09-23 02:10:20.477  4850  4864 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@560d244 HexData = [00000000ed03000000000000ffffffff]
09-23 02:10:20.477  4850  4864 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
09-23 02:10:20.477  4850  4864 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
09-23 02:10:20.478  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 02:10:20.478  4821  4832 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
09-23 02:10:20.479  3861  3861 D SystemUpdateService: onCreate
09-23 02:10:20.479  4850  4850 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
09-23 02:10:20.479  4821  4833 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-23 02:10:20.481  5362  5362 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-23 02:10:20.482  3861  3861 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-23 02:10:20.483  5362  5362 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-23 02:10:20.493  3861  3861 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-23 02:10:20.495  3861  5143 I iu.UploadsManager: num queued entries: 0
09-23 02:10:20.495  3861  5143 I iu.UploadsManager: num updated entries: 0
09-23 02:10:20.495  3861  5143 I iu.SyncManager: NEXT; no task
,09-23 02:10:20.500  3861  5653 I SystemUpdateService: active receiver: enabled
,09-23 02:10:20.502  3861  3861 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-23 02:10:20.503  3861  3861 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,09-23 02:10:20.505  5145  5145 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-23 02:10:20.510  5145  5145 D SprintDMHelper: simOperator: 
09-23 02:10:20.510  5145  5145 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-23 02:10:20.522   931  5639 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.209.78,2a00:1450:401b:801::200e
,09-23 02:10:20.538  3861  5653 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-23 02:10:20.548  3861  5653 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-23 02:10:20.548  3861  5653 I SystemUpdateService: now status is 0 (complete)
09-23 02:10:20.548  3861  5653 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-23 02:10:20.548  3861  5653 I SystemUpdateService: file has been verified
09-23 02:10:20.548  3861  5653 I SystemUpdateService: OTA package size = 21989297
,09-23 02:10:20.553  3861  5653 I SystemUpdateService: showing system update notification
,09-23 02:10:20.562  3861  3861 D SystemUpdateService: onDestroy
,09-23 02:10:20.569   931  5639 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 23 Sep 2016 06:10:20 GMT], X-Android-Received-Millis=[1474611020569], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1474611020545]}
,09-23 02:10:20.570   931  2891 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-23 02:10:20.570   931  2891 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-23 02:10:20.571   931  2891 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-23 02:10:20.572   931  2891 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-23 02:10:20.614  4244  5657 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-23 02:10:21.454   931  2891 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-23 02:10:21.739  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,09-23 02:10:21.739  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-23 02:10:21.739  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 02:10:21.740  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-23 02:10:21.740  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 02:10:21.741  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 02:10:21.741  5362  5637 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-23 02:10:21.741  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-23 02:10:21.741  5362  5637 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 02:10:21.741  5362  5637 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 02:10:21.741  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-23 02:10:21.741  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 02:10:21.741  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 02:10:21.741  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 02:10:21.742  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 02:10:21.742  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 02:10:21.745  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:21.745  5362  5408 D BluetoothLeScanner: could not find callback wrapper
09-23 02:10:21.745  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 02:10:21.745  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,09-23 02:10:21.747  5565  5583 D BtGatt.AdvertiseManager: message : 1
,09-23 02:10:21.749  5565  5583 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 02:10:21.763  5565  5581 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 02:10:21.763  5565  5581 D BtGatt.GattService: Client app is not null!
,09-23 02:10:21.765  5565  5575 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 02:10:21.766  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-23 02:10:21.767  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 02:10:21.767  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-23 02:10:21.767  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,09-23 02:10:21.767  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-23 02:10:21.771  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 02:10:21.771  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 02:10:21.772  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-23 02:10:21.773  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 02:10:21.776  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-23 02:10:21.776  5362  5362 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-23 02:10:21.777  5362  5362 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-23 02:10:21.777  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:21.777  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:21.777  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-23 02:10:21.781  5362  5408 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
09-23 02:10:21.781  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 02:10:21.782  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 02:10:21.782  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-23 02:10:21.782  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-23 02:10:21.783  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-23 02:10:21.783  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-23 02:10:21.787  5362  5408 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 02:10:21.787  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-23 02:10:21.791  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 02:10:21.792  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-23 02:10:21.792  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-23 02:10:21.797  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 02:10:21.798  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-23 02:10:21.799  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 02:10:21.799  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:21.802  5565  5607 D BtGatt.GattService: registerClient() - UUID=82e88e9b-1b37-4236-8fb7-2aa13a25eba7
09-23 02:10:21.803  5565  5581 D BtGatt.GattService: onClientRegistered() - UUID=82e88e9b-1b37-4236-8fb7-2aa13a25eba7, clientIf=5
,09-23 02:10:21.803  5362  5372 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 02:10:21.804  5565  5575 D BtGatt.GattService: start scan with filters
,09-23 02:10:21.808  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 02:10:21.809  5565  5584 D BtGatt.ScanManager: handling starting scan
09-23 02:10:21.809  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-23 02:10:21.809  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-23 02:10:21.809  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-23 02:10:21.811  5565  5584 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3ff56e5
,09-23 02:10:21.814  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-23 02:10:21.814  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 02:10:21.814  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-23 02:10:21.816  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-23 02:10:21.820  5565  5581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 02:10:21.820  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 02:10:21.821  5565  5584 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 02:10:21.827  5565  5581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,09-23 02:10:21.828  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:21.828  5565  5584 D BtGatt.ScanManager: Starting BLE batch scan
,09-23 02:10:21.828  5565  5584 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-23 02:10:21.839  5565  5581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 02:10:21.839  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:21.845  5565  5581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-23 02:10:21.845  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:22.315  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-23 02:10:22.316  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-23 02:10:22.316  5362  5362 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 02:10:23.175   931  2891 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-23 02:10:24.821  5362  5408 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,09-23 02:10:24.822  5362  5408 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
,09-23 02:10:24.822  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
09-23 02:10:24.823  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-23 02:10:24.823  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-23 02:10:24.826  5362  5408 D BluetoothAdapter: STATE_ON
,09-23 02:10:24.828  5565  5603 D BtGatt.GattService: stopScan() - queue size =1
09-23 02:10:24.830  5565  5607 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 02:10:24.831  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 02:10:24.831  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-23 02:10:24.832  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-23 02:10:24.832  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-23 02:10:24.832  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-23 02:10:24.833  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-23 02:10:24.837  5565  5565 D BtGatt.ScanManager: awakened up at time 217217
09-23 02:10:24.838  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:24.845  5565  5603 D BtGatt.GattService: registerClient() - UUID=26c7920d-12f6-40be-9f2d-9fc53457104e
09-23 02:10:24.845  5565  5581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
09-23 02:10:24.845  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:24.845  5565  5584 D BtGatt.ScanManager: stopping BLe Batch
,09-23 02:10:24.846  5565  5581 D BtGatt.GattService: onClientRegistered() - UUID=26c7920d-12f6-40be-9f2d-9fc53457104e, clientIf=5
,09-23 02:10:24.846  5362  5373 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-23 02:10:24.847  5565  5576 D BtGatt.GattService: start scan with filters
09-23 02:10:24.852  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-23 02:10:24.852  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-23 02:10:24.852  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:24.853  5362  5408 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-23 02:10:24.853  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-23 02:10:24.853  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-23 02:10:24.854  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-23 02:10:24.855  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-23 02:10:24.855  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-23 02:10:24.855  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-23 02:10:24.855  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-23 02:10:24.855  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-23 02:10:24.855  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-23 02:10:24.856  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-23 02:10:24.857  5362  5666 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-23 02:10:24.857  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:24.858  5565  5603 D BtGatt.GattService: stopScan() - queue size =0
09-23 02:10:24.859  5565  5581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-23 02:10:24.859  5565  5576 D BtGatt.GattService: unregisterClient() - clientIf=5
09-23 02:10:24.859  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 02:10:24.854  5607  5607 W Binder_6: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[32554]" dev="sockfs" ino=32554 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
09-23 02:10:24.854  5607  5607 W Binder_6: type=1400 audit(0.0:125): avc: denied { ioctl } for path="socket:[32554]" dev="sockfs" ino=32554 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,09-23 02:10:24.859  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 02:10:24.860  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-23 02:10:24.860  5565  5584 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-23 02:10:24.860  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-23 02:10:24.860  5362  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
09-23 02:10:24.860  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-23 02:10:24.860  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-23 02:10:24.862  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:24.863  5362  5408 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-23 02:10:24.866  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,09-23 02:10:24.866  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
09-23 02:10:24.866  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
09-23 02:10:24.867  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:24.867  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-23 02:10:24.867  5362  5408 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-23 02:10:24.868  5362  5408 D BluetoothAdapter: STATE_ON
,09-23 02:10:24.871  5565  5576 D BtGatt.GattService: registerClient() - UUID=c80f25ef-6ea9-471e-939f-d0bd27f9599d
,09-23 02:10:24.872  5565  5581 D BtGatt.GattService: onClientRegistered() - UUID=c80f25ef-6ea9-471e-939f-d0bd27f9599d, clientIf=5
09-23 02:10:24.872  5362  5492 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-23 02:10:24.873  5565  5583 D BtGatt.AdvertiseManager: message : 0
,09-23 02:10:24.877  5565  5583 D BtGatt.AdvertiseManager: starting multi advertising
,09-23 02:10:24.881  5565  5581 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
09-23 02:10:24.881  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:24.881  5565  5581 D BtGatt.GattService: current time is 217261816476
,09-23 02:10:24.882  5565  5581 D BtGatt.GattService: Batch record : [-21, 108, 79, -73, -113, 111, 1, -128, -60, 49, 0, 29, 17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 30, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -77, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -78, 34, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 116, -43, -111, -91, -20, -29, 1, -128, -75, 33, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-23 02:10:24.883  5565  5581 D BtGatt.GattService: ScanRecord : [17, 7, 81, -5, 71, 90, -128, -117, 93, -127, 58, 75, 25, -45, -47, 74, -92, -74, 10, 22, -47, 74, 5, -88, -127, -107, -23, 95, 111]
09-23 02:10:24.884  5565  5584 D BtGatt.ScanManager: handling starting scan
09-23 02:10:24.884  5565  5581 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-23 02:10:24.885  5565  5581 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,09-23 02:10:24.885  5565  5581 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
09-23 02:10:24.885  5565  5581 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-23 02:10:24.893  5565  5581 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-23 02:10:24.899  5565  5581 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-23 02:10:24.899  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 02:10:24.899  5565  5584 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-23 02:10:24.904  5565  5581 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-23 02:10:24.905  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-23 02:10:24.905  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-23 02:10:24.907  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-23 02:10:24.908  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:24.908  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:24.909  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-23 02:10:24.909  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
09-23 02:10:24.909  5362  5362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-23 02:10:24.909  5362  5362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-23 02:10:24.909  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-23 02:10:24.910  5565  5581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
09-23 02:10:24.910  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:24.910  5565  5584 D BtGatt.ScanManager: Starting BLE batch scan
,09-23 02:10:24.911  5565  5584 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-23 02:10:24.913  5362  5362 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-23 02:10:24.913  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-23 02:10:24.922  5565  5581 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-23 02:10:24.922  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:24.928  5565  5581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-23 02:10:24.928  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:24.936  5565  5581 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,09-23 02:10:24.936  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 02:10:24.936  5565  5584 D BtGatt.ScanManager: stopping BLe Batch
,09-23 02:10:24.943  5565  5581 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-23 02:10:24.943  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-23 02:10:24.944  5565  5584 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-23 02:10:24.950  5565  5581 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-23 02:10:24.950  5565  5581 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-23 02:10:25.414  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,09-23 02:10:25.414  5362  5362 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 02:10:25.414  5362  5362 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-23 02:10:26.782   931  2889 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 15 -> obsolete
,09-23 02:10:27.946   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,09-23 02:10:27.947   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-23 02:10:28.408   931  2891 D ConnectivityService: handlePromptUnvalidated 101
,09-23 02:10:28.413  5362  5408 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,09-23 02:10:28.414  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-23 02:10:28.414  5362  5408 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-23 02:10:28.414  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-23 02:10:28.414  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-23 02:10:28.415  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-23 02:10:28.415  5362  5408 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-23 02:10:28.415  5362  5666 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,09-23 02:10:28.415  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-23 02:10:28.415  5362  5666 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-23 02:10:28.415  5362  5362 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-23 02:10:28.415  5362  5666 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-23 02:10:28.415  5362  5408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1da48ce removed from the list
09-23 02:10:28.416  5362  5362 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-23 02:10:28.416  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-23 02:10:28.416  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-23 02:10:28.416  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-23 02:10:28.416  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-23 02:10:28.416  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-23 02:10:28.419  5362  5408 D BluetoothAdapter: STATE_ON
09-23 02:10:28.419  5362  5408 D BluetoothLeScanner: could not find callback wrapper
09-23 02:10:28.419  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-23 02:10:28.419  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-23 02:10:28.422  5565  5583 D BtGatt.AdvertiseManager: message : 1
,09-23 02:10:28.423  5565  5583 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-23 02:10:28.436  5565  5581 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-23 02:10:28.436  5565  5581 D BtGatt.GattService: Client app is not null!
,09-23 02:10:28.437  5565  5607 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-23 02:10:28.438  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-23 02:10:28.438  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-23 02:10:28.439  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
,09-23 02:10:28.439  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-23 02:10:28.439  5362  5408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
09-23 02:10:28.441  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:28.441  5362  5408 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-23 02:10:28.441  5362  5408 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-23 02:10:28.442  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-23 02:10:28.444  5362  5408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@973f3ef removed from the list
,09-23 02:10:28.444  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-23 02:10:28.444  5362  5408 D io.jxcore.node.ConnectivityMonitor: stop
09-23 02:10:28.444  5362  5362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-23 02:10:28.444  5362  5408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-23 02:10:28.444  5362  5362 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-23 02:10:28.448  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
09-23 02:10:28.449  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-23 02:10:28.449  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-23 02:10:28.449  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-23 02:10:28.449  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-23 02:10:28.449  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-23 02:10:28.449  5362  5408 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-23 02:10:28.451  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
,09-23 02:10:28.452  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
09-23 02:10:28.453  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
09-23 02:10:28.454  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
,09-23 02:10:28.456  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
09-23 02:10:28.457  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
09-23 02:10:28.458  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
,09-23 02:10:28.459  5362  5408 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
,09-23 02:10:28.461  5362  5408 I StreamCopyingThreadTest: Starting test: testRun
,09-23 02:10:28.465  5362  5668 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 198, name: My test thread name)
,09-23 02:10:28.945  5362  5362 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-23 02:10:29.554   931  2889 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,09-23 02:10:30.150  5362  5668 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 198
,09-23 02:10:30.151  5362  5668 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 198, name: My test thread name)
09-23 02:10:30.151  5362  5668 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 198, name: My test thread name), during the lifetime of the thread the total number of bytes read was 121 and the total number of bytes written 121
,09-23 02:10:30.470  5362  5408 I StreamCopyingThreadTest: Starting test: testRunNotify
,09-23 02:10:30.473  5362  5670 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 200, name: My test thread name)
,09-23 02:10:30.473  5362  5670 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 200, thread name: My test thread name)
09-23 02:10:30.473  5362  5670 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 200, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-23 02:10:30.476  5362  5408 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,09-23 02:10:30.478  5362  5408 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-23 02:10:30.482  5362  5408 I StreamCopyingThreadTest: Starting test: testRunWithException
,09-23 02:10:30.485  5362  5671 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 204, name: My test thread name)
,09-23 02:10:30.485  5362  5671 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 204, thread name: My test thread name): Test exception.
09-23 02:10:30.486  5362  5671 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 204, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-23 02:10:30.492  5362  5408 I jxcore-log: *Native tests were executed*
09-23 02:10:30.492  5362  5408 I jxcore-log: 
,09-23 02:10:30.493  5362  5408 I jxcore-log: Total number of executed tests:  82
09-23 02:10:30.493  5362  5408 I jxcore-log: 
09-23 02:10:30.493  5362  5408 I jxcore-log: Number of passed tests:  82
09-23 02:10:30.493  5362  5408 I jxcore-log: 
09-23 02:10:30.494  5362  5408 I jxcore-log: Number of failed tests:  0
09-23 02:10:30.494  5362  5408 I jxcore-log: 
,09-23 02:10:30.494  5362  5408 I jxcore-log: Number of ignored tests:  0
09-23 02:10:30.494  5362  5408 I jxcore-log: 
09-23 02:10:30.495  5362  5408 I jxcore-log: Total duration:  21967
09-23 02:10:30.495  5362  5408 I jxcore-log: 
09-23 02:10:30.496  5362  5408 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-23 02:10:30.496  5362  5408 I jxcore-log: 
,09-23 02:10:30.504  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 02:10:30.504  5362  5408 I jxcore-log: 
09-23 02:10:30.511  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 02:10:30.511  5362  5408 I jxcore-log: 
09-23 02:10:30.513  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 02:10:30.513  5362  5408 I jxcore-log: 
,09-23 02:10:30.515  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 02:10:30.515  5362  5408 I jxcore-log: 
,09-23 02:10:30.516  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 02:10:30.516  5362  5408 I jxcore-log: 
,09-23 02:10:30.518  5362  5362 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-23 02:10:30.519  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 02:10:30.519  5362  5408 I jxcore-log: 
09-23 02:10:30.522  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 02:10:30.522  5362  5408 I jxcore-log: 
,09-23 02:10:30.524  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 02:10:30.524  5362  5408 I jxcore-log: 
,09-23 02:10:30.526  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 02:10:30.526  5362  5408 I jxcore-log: 
,09-23 02:10:30.528  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 02:10:30.528  5362  5408 I jxcore-log: 
,09-23 02:10:30.529  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 02:10:30.529  5362  5408 I jxcore-log: 
09-23 02:10:30.530  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.530  5362  5408 I jxcore-log: 
09-23 02:10:30.531  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.531  5362  5408 I jxcore-log: 
09-23 02:10:30.531  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.531  5362  5408 I jxcore-log: 
09-23 02:10:30.532  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.532  5362  5408 I jxcore-log: 
,09-23 02:10:30.533  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.533  5362  5408 I jxcore-log: 
09-23 02:10:30.534  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.534  5362  5408 I jxcore-log: 
,09-23 02:10:30.536  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.536  5362  5408 I jxcore-log: 
,09-23 02:10:30.537  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.537  5362  5408 I jxcore-log: 
,09-23 02:10:30.538  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.538  5362  5408 I jxcore-log: 
,09-23 02:10:30.538  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.538  5362  5408 I jxcore-log: 
09-23 02:10:30.539  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.539  5362  5408 I jxcore-log: 
09-23 02:10:30.540  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.540  5362  5408 I jxcore-log: 
,09-23 02:10:30.541  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.541  5362  5408 I jxcore-log: 
,09-23 02:10:30.542  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.542  5362  5408 I jxcore-log: 
,09-23 02:10:30.543  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.543  5362  5408 I jxcore-log: 
,09-23 02:10:30.544  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 02:10:30.544  5362  5408 I jxcore-log: 
,09-23 02:10:30.545  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 02:10:30.545  5362  5408 I jxcore-log: 
09-23 02:10:30.546  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-23 02:10:30.546  5362  5408 I jxcore-log: 
09-23 02:10:30.546  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.546  5362  5408 I jxcore-log: 
,09-23 02:10:30.547  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.547  5362  5408 I jxcore-log: 
,09-23 02:10:30.548  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.548  5362  5408 I jxcore-log: 
09-23 02:10:30.549  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-23 02:10:30.549  5362  5408 I jxcore-log: 
09-23 02:10:30.550  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 02:10:30.550  5362  5408 I jxcore-log: 
,09-23 02:10:30.551  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 02:10:30.551  5362  5408 I jxcore-log: 
,09-23 02:10:30.552  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 02:10:30.552  5362  5408 I jxcore-log: 
,09-23 02:10:30.553  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-23 02:10:30.553  5362  5408 I jxcore-log: 
,09-23 02:10:30.554  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-23 02:10:30.554  5362  5408 I jxcore-log: 
09-23 02:10:30.555  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-23 02:10:30.555  5362  5408 I jxcore-log: 
09-23 02:10:30.556  5362  5408 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-23 02:10:30.556  5362  5408 I jxcore-log: 
,09-23 02:10:31.006  5672  5672 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-23 02:10:31.012  5672  5672 D AndroidRuntime: CheckJNI is OFF
,09-23 02:10:31.040  5672  5672 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-23 02:10:31.074  5672  5672 I Radio-JNI: register_android_hardware_Radio DONE
,09-23 02:10:31.092  5672  5672 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-23 02:10:31.102   931   944 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,09-23 02:10:31.103   931   944 I ActivityManager: Killing 5362:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,09-23 02:10:31.182   931  3433 D GraphicsStats: Buffer count: 2,
09-23 02:10:31.183   931  3433 I WindowState: WIN DEATH: Window{813afc9 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-23 02:10:31.183   931  2890 D WifiService: Client connection lost with reason: 4
,09-23 02:10:31.241   931   944 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-23 02:10:31.241   931   944 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-23 02:10:31.242   931   954 I art     : Starting a blocking GC Explicit
09-23 02:10:31.242   931   944 E ActivityManager: Failure starting process com.test.thalitest
09-23 02:10:31.242   931   944 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
09-23 02:10:31.242   931   944 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:31.242   931   944 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:31.242   931   944 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 02:10:31.242   931   944 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 02:10:31.243   931   944 I ActivityManager:   Force finishing activity ActivityRecord{8bead22 u0 com.test.thalitest/.MainActivity t2}
,09-23 02:10:31.248   931  3090 W ActivityManager: Spurious death for ProcessRecord{259b400 0:com.test.thalitest/u0a77}, curProc for 5362: null
,09-23 02:10:31.252   931   949 W WindowManager: Attempted to add application window with unknown token Token{c3c43b3 ActivityRecord{8bead22 u0 com.test.thalitest/.MainActivity t2 f}}.  Aborting.
,09-23 02:10:31.253   931   949 W WindowManager: Token{c3c43b3 ActivityRecord{8bead22 u0 com.test.thalitest/.MainActivity t2 f}} already running, starting window not displayed. Unable to add window -- token Token{c3c43b3 ActivityRecord{8bead22 u0 com.test.thalitest/.MainActivity t2 f}} is not valid; is your activity running?
09-23 02:10:31.253   931   949 W WindowManager: view not successfully added to wm, removing view
09-23 02:10:31.253   931   949 W WindowManager: Exception when adding starting window
09-23 02:10:31.253   931   949 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{3c9e6fb V.E...... R.....ID 0,0-0,0} not attached to window manager
09-23 02:10:31.253   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
09-23 02:10:31.253   931   949 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
09-23 02:10:31.253   931   949 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
09-23 02:10:31.253   931   949 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
09-23 02:10:31.253   931   949 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
09-23 02:10:31.253   931   949 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:31.253   931   949 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:31.253   931   949 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-23 02:10:31.253   931   949 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-23 02:10:31.320   931   954 I art     : Explicit concurrent mark sweep GC freed 21193(1307KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.731ms total 78.297ms
,09-23 02:10:31.339   931   954 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-23 02:10:31.342  5672  5672 I art     : System.exit called, status: 0
,09-23 02:10:31.342  5672  5672 I AndroidRuntime: VM exiting with result code 0.
,09-23 02:10:31.346   931  2889 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 14, 15 -> obsolete
,09-23 02:10:31.352   931   954 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,09-23 02:10:31.360   931   944 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-23 02:10:31.363  3362  3362 I Keyboard.Facilitator: resetDictionaries() : en_US
09-23 02:10:31.364  5565  5565 D BluetoothMapAppObserver: onReceive
09-23 02:10:31.364  5565  5565 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-23 02:10:31.373  3566  3907 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-23 02:10:31.375   931  2880 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-23 02:10:31.405  3346  5685 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-23 02:10:31.406  3362  5683 I Keyboard.Facilitator.DecoderInitializer: run()
,09-23 02:10:31.428  3449  3449 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-23 02:10:31.430  3535  3535 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
09-23 02:10:31.430  3535  3535 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-23 02:10:31.433  3362  5683 I Decoder : createOrResetDecoder
,09-23 02:10:31.453   931   931 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-23 02:10:31.451   407   407 W kworker/3:2: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 02:10:31.457  3861  5689 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-23 02:10:31.457   407   407 W kworker/3:2: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 02:10:31.465  3861  5689 D AccountUtils: Clearing selected account for com.test.thalitest
,09-23 02:10:31.469  3485  3629 E SQLiteLog: (1546) os_unix.c:29096: (22) ftruncate(/data/user/0/com.google.android.googlequicksearchbox/databases/app_icons.db) - 
,09-23 02:10:31.474   407   407 W kworker/3:2: type=1400 audit(0.0:128): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,09-23 02:10:31.482   931  3354 I ActivityManager: Start proc 5692:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-23 02:10:31.484  3485  3629 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-23 02:10:31.484  3485  3629 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3485
09-23 02:10:31.484  3485  3629 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 1546)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:31.484  3485  3629 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 02:10:31.490  3535  3535 I ConfigService: onCreate
,09-23 02:10:31.491   931  3091 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-23 02:10:31.491   931  5698 E DropBoxManagerService: Can't write: system_app_crash
09-23 02:10:31.491   931  5698 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-23 02:10:31.491   931  5698 E DropBoxManagerService: 	... 5 more
,09-23 02:10:31.494  3485  3629 I Process : Sending signal. PID: 3485 SIG: 9
,09-23 02:10:31.497  3535  5703 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 02:10:31.497  3535  5703 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-23 02:10:31.498  3535  5703 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-23 02:10:31.500  3535  5703 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-23 02:10:31.509  3346  3377 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj584DA79DB) - 
,09-23 02:10:31.514  3362  5683 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-23 02:10:31.528  3861  5689 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-23 02:10:31.549  3861  5689 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:31.549  3861  5689 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:31.549  3861  5689 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 02:10:31.575  3861  5689 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,09-23 02:10:31.587  3861  3861 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-23 02:10:31.587  3861  3861 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-23 02:10:31.599  3861  3861 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-23 02:10:31.599  3861  3861 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-23 02:10:31.637  3346  3377 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
09-23 02:10:31.637  3346  3377 E AndroidRuntime: Process: android.process.acore, PID: 3346
09-23 02:10:31.637  3346  3377 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-23 02:10:31.637  3346  3377 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-23 02:10:31.644   380   380 E lowmemorykiller: Error writing /proc/3485/oom_score_adj; errno=22
,09-23 02:10:31.644   931  3475 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
09-23 02:10:31.645   931  3475 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-23 02:10:31.645   931  3475 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
09-23 02:10:31.645   931  3475 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,09-23 02:10:31.671   931  2879 W InputDispatcher: channel '116f0ad com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-23 02:10:31.671   931  3433 D GraphicsStats: Buffer count: 1
09-23 02:10:31.671   931  3464 I WindowState: WIN DEATH: Window{116f0ad u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-23 02:10:31.671   931  2879 E InputDispatcher: channel '116f0ad com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-23 02:10:31.671   931  3464 W InputDispatcher: Attempted to unregister already unregistered input channel '116f0ad com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,09-23 02:10:31.672  3346  3377 I Process : Sending signal. PID: 3346 SIG: 9
,09-23 02:10:31.677   931  3475 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-23 02:10:31.691   931  3475 I ActivityManager: Start proc 5716:com.google.android.googlequicksearchbox/u0a29 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,09-23 02:10:31.694   380   380 E lowmemorykiller: Error writing /proc/3346/oom_score_adj; errno=22
,09-23 02:10:31.695   931  3091 W ActivityManager: Spurious death for ProcessRecord{1c8e385 5716:com.google.android.googlequicksearchbox/u0a29}, curProc for 3485: null
,09-23 02:10:31.698  4737  5712 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-23 02:10:31.744  3861  5711 W BaseAppContext: Using Auth Proxy for data requests.
,09-23 02:10:31.751  3861  5711 W BaseAppContext: Using Auth Proxy for data requests.
,09-23 02:10:31.792  3861  3861 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-23 02:10:31.806  3861  5730 I GMPM-SVC: App measurement is starting up
,09-23 02:10:31.818  3861  5730 E GMPM-SVC: AppMeasurementService not registered/enabled
,09-23 02:10:31.819  3861  5730 E GMPM-SVC: Uploading is not possible. App measurement disabled
,09-23 02:10:31.859   382   473 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
